代发 wailian999

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vbytdagq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2znbjnieg.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2grgoblrf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2whhzttoj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkeujbq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ysylwmoi.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgaokdt.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gitcygtc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmpblfd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebintbek.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srqtvvzf.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unyukjww.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooemhjqw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2emkomwdi.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxdvmyt.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zmeojugb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwowzgg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdardiq.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhudwok.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcyaazx.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvzwohv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyuroos.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfzrecd.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbxokvy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xglprnqy.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyhlpow.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yglzuebm.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eegkolor.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhaunoip.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wueovfwb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2uazbewzr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkvxvoa.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2pwassjhp.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbcwpxz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdwzhjs.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvpwpyg.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrrdgja.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dffpesje.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wxohqtgn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kkouuuqa.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2slvhqhdz.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdivtxa.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dekgsoak.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2hazizigp.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftihtgsd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjvickr.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrhucje.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpybgsv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2veqtlpbj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhqydrb.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oexrxhhf.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxfmoga.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2atqtdnrn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxkpgji.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vptqgpsp.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaepwgbb.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlaolgsf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaozvwr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpvncct.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkulszzb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbzbjiu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2botttdkg.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdrtdzx.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcwhpzr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iezptplj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mallxkuw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxohmzl.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dxynocex.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmkinrs.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbibmqp.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyghfdb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jolfqbei.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgvqshe.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2beaithxn.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqpomug.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjhowol.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xygkccsp.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgmhdak.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mqoenqje.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kluknigl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deubisie.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpsvpys.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exafvpxc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhywavo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqdosna.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjhmshd.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cowbwesm.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsckrgy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbksyzkd.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gucqvdhb.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2riuyjomf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyowahn.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2opwscafo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdbrzfx.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntncddku.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyqczwa.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2aamjajql.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2plfuqgaq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ekafjnwd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdazvcc.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkolglz.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chjnezkq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2igteovjp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2crvlfunb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmglfvxl.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2utswbvrz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rweidyth.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2neyaecgd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2gzieysmd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wniayvno.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2agjcaspp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2aujehbcx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2nawzbtwa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2alfcagow.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwwdyic.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrrunmn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwreovqy.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2stvdueei.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpadmlc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2wieabbkw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrmzwni.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmagviw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2saqbuxcm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlugvdi.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeaatdu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oklcjohb.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2koqgjxop.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2taexxgpw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2khzoihuu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfzfauu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnvdqtr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmwnnjx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oogxfqzr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nvduzlli.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sebmaaca.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2myczrcoc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnneuxaw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxctunmr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oveszavx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oseuzkan.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnrvpzl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ymejbtda.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eiolfssd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjxxqae.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjwaybq.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2slzeghfm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kodjynis.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhsdduo.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlwvnhu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqtmexn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqlveka.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2afnkmrxa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2umnkkkfc.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwemqtr.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnjrmii.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvefyll.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojslvyvm.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzauhes.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwzecjx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvnqzmu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uisvblwy.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgecyroh.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2omonzwrq.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2dutrqhav.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qzygmwea.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuoohkz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wonzkiuo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvunqape.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2twafvvfx.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2dglezfmc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dycjqmmd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2naqhgnkd.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqgtshy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzppukr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlhdadq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2galdlgqf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtbgkya.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlkjnxp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtugmbr.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqsuuud.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcutokt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfbwchp.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2guipprfw.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2icxkekgj.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlcunuv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2wefxflja.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xefuhbbm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vktbvqvb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2soqfwxlc.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxqmwnt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2qugithek.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2drtnxfjc.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2lowyqlhw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wonvenvg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsuyvwr.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrafkak.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lsulkvcd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2bofpdfbg.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2euremgis.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhwjdyp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2djumfzsv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2uctywoig.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgcvxih.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exojtfmq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgaujjj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdwvthl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzbpdhg.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkwvlau.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrsmfff.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzbmkoy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2nheinlij.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvdpeeq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2jspwcpon.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmklfnf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcwxbom.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bswlkvdl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rauthxkm.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgdnyux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2waaqptaa.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqgmeyz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxpdciz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2etgegsel.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxldmjfq.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdbwpfw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2esnqlvqh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2corpzdhz.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2imdfgjqb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2venwysoc.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcecaww.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2otgohcsa.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzwuacq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdlirfs.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbpoeak.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cydsgtvk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yekpmzem.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rudthpth.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwfumin.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iknrfqcx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdlhqlf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2aybqfksn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2krowfahm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2czebwbmq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2smadsrwb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlgkbgx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxihbnr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcedfuh.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rylbembu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqprpik.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcdlgie.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mquzxops.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2whfzvlxy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbcfckp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqsdihi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgkukst.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiaiayuq.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdluxot.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iutqptrx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoeiwbtt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdavbvy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvavcag.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmxgmlf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lruvqwry.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbacpmdo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgklpzs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2utccgzgf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2zljxydsi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2mokrbrmc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2kkygsmaq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ntloghcz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwxfznw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2znvfkbjk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2cffgxtjb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxtfnbd.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqieovi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2icclmvvz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlmeuol.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyxxicc.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2gjywiscj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwokism.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2tewtvdgv.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbilbfnz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbrywta.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlyvszf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2islycfma.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfddkagn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgrocvy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlaeiua.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2juuzbjqf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpdaisz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxvmkir.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiycpjjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brjvgari.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xahpufgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yugvpfoc.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxlltny.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2cddyouph.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2vvprjlln.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2yorphusr.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwtzblw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxisrkeq.html


<!-- 参考信息 -->