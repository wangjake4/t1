代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmcjgnn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxmslpr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2visyazhl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vaumacto.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flfpaatz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgjigom.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lquwoexh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgjfptr.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgrcoux.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbjhuvy.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgldonnz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dubzjbeu.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2igzadlwm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnzesja.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmiuwsk.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rywndmhv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emvxedsq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnoswau.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lajhckte.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecisuyvs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrfpxxa.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fauxzgxs.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dletpnym.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgaxjnh.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhbzbrl.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szoslceo.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyugjxy.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpdyqbn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsnbhwn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpmpbmq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzqcedb.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lselxrqk.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2slumqnya.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkksise.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akoephae.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyzggkl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpyfolu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avjjgsua.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzmfjvw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyazhss.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2fsapoxdh.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hexxrcmd.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2oeksikgb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xopkpohm.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkioufr.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dnaubwyo.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyvknkv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvjpdkm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2waiqutui.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcuxzga.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgaaswe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtwzkfq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgvuqxd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgdvatx.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkbbusv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmllokez.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyiwxyg.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlmfetc.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyuwvtw.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ofikkwpw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2obuqtxue.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfjxlpp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2twaxxgvw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzrsnor.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnlujbr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwsxiyw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2catrrtur.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdfykzu.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2nprdeghh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnjqfqt.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbworwb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhaibzw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2djajqvmp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2bjojhxdn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjgmeae.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wboyhvlq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2wpoesqsr.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bopitoyj.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2goucfbij.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvobgdei.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vedsebkd.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmdqurq.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cywltgvb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcaysob.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2puovbxgd.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glicmaqd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2liedwlmr.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bbulmcae.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxfurrg.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqavxvf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xigczzyc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuagwqg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2peescvjy.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmwjanb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwckuzu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpzcsqc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2npclokry.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxxfjfo.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkbfkkv.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dolxerpy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcqzdip.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfngadp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fscsqgti.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsqlgzs.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2upmguggz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2utcuoqih.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2brpueegp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrlghff.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2vnztybbh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyplmxxz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2coaddfcj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2iivnvdgv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpfonwl.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzxlmuz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2glqqhfkv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaucwxqb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzzptbc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvokjhgc.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2avciwdbb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxumdpeo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2dwahforq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrscgrvn.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2orjdqaao.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2illrkxqi.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ampawjce.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2espowjrc.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytptqqry.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2yncnyazy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxtzpyj.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ffefdbbn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfajsai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzilisf.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xbevwzmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svsopgvf.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqswnqk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2asgerkkv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2proxtiib.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlytngs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhphhsj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzjqobd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxdxyjx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2altafrap.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbnkadh.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzythai.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2pilmslff.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogukhwpj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpiboos.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytptbfve.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgksmyqu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2cohidfqs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxzjjbs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2chknvciq.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wraoarxe.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwlybja.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdkkfpc.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aumtiklb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbirunh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhgopbq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2obayconc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2woguacbg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnvllpb.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfvcurw.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ueihtqoc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmluxqrp.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcorjons.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chtmgilu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrviljms.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2onuqmtqj.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2acwaekqi.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvosngw.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2spqmezok.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2knimoper.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiedgqo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkslrvv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpbrmah.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2egudkpoy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmawyvpp.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2tretjocu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcmzgtv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjvvaah.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ouworctm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqiyati.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2uffdadat.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cetmzfyb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2zturngtg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2njrrodqe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddglqokp.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2npdgqbzv.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkuxibz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2kksihtkf.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aluihufw.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gupssbxt.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qioexxfd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2nokxlqyf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhpnpxj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeaqbsn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyoidxwt.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2afnctquv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtauzsf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhspjxwe.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsavlml.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdxqorl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2pukujkjy.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtlpjjz.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzqdoka.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvkugrr.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oipnzgtq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2dwoecivc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2llqalcve.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbkassy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmtkscv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcffotv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kydyhidt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcgxcia.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtmtrmi.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kpedpsik.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2txhclvmf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2neppxwvz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hdchjheq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hxycfczv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2xknjwqyx.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdmtlhr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcijkmf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxojkzst.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzykgtz.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kcobfeir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbshppxb.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtrypcy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kujskznx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsabnlsy.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2edwzpura.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbljges.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfobhaa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktszwjxu.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxcbrdl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzffosx.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qrctvufr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gabldadi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuuviey.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2szguhikj.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2jucqimtx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yegngwwx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2banvukil.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuayvsmi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruddwyhc.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dubzjjlz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxgtxpd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2taftfulh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nodewdqf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyyoeoz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2urzlsbqr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2xamblfsh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mswoieow.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgkfvff.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxppiej.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiokbkk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ismagonz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcbymov.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcbfupr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvjqsib.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmqnvqh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgrxdev.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmlddoj.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpulhsb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvhwcxo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eubqyjnw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrgagjm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2oexvilpe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnugpgtf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcyecsx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrndcjd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2apciktyr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkjuryr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2prhlrmen.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2floahxge.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2czneusct.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2anjgeanj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2trztyyev.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2jndwcbph.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwrbkji.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjlwuyd.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrkgytd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2phwmjfqj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpeuhgvl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsxsuro.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2acqwbfql.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkifprik.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2sezwjxhb.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhacbin.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvrbzeu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kcalaats.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtbqdba.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyvwium.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocazfkml.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyirvuvr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2hglwwcjn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2brpegcdt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuuwjtg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtigmjr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oteeqlek.html


<!-- 参考信息 -->