代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rppvfehp.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcuxmfy.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqfuwds.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfcrktw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hskpcwnw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uugtulcm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgdkmgx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2iyurqwvg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2duufurrk.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eicwkhra.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hydtrohu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2foaivqdx.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbodavq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzuubvo.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2awcewnix.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2caujtniv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkvppvy.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2yljuywwx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieszoahq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjjhuuu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrzqjwl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvseota.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2eurdsxud.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuhdzkp.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ujftynij.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnirlwy.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxcfryo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2clfshhep.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxasabx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vndzmekc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmsocls.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2urlxqzvr.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2chbptlsa.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhihjkm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyapdrn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlfdvlq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2elmhlsvb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vabyumpa.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awnfszck.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzrwfql.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcuvtes.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnumldq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeoudfi.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wqozsbdu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvumvec.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbiwosdp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnpwyxu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuavpuws.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qccuslgf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjblreqi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2odfumrnx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjlcvdq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2bttldpes.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzpjdjn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oodvacyb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2xclfmzdo.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mepjeyxj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2nqamllct.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2izdxsuhu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bscvndog.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2utgztmms.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zcviojps.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrpyzcm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjgeqia.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpvovff.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djpxpmkd.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcytbtc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysijaolq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2sehndvzk.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqnjcpc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlhisor.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2icaodbzr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxmmxmm.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrfzgct.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eauvkmct.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbpyvva.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcptigep.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxayfim.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2focletun.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdzenyj.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpamnafu.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2phzvxfol.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cipwtacb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oskvuhln.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mpenvldj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2myyfumhs.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2htkufzpy.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwbftmf.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2dqklbffg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2diqnsqmi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiderga.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqmbmrg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2hzupaqmg.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzyuhek.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwigptw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2uzojbdeh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmrhbpa.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2csdqdilw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eositnva.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgbhcjj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2uboljwku.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjzwunq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2smtdfjhh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzambcby.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2axolnizk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bryfnwey.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rcewdqku.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhsfcjk.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbqtxjo.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwtqsfn.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2szzuwkxv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhipzvj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjthsev.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvmzejl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxfugjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xehrjgcn.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2efaxggvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydleyape.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2rasywvki.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxuczqb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kspbtbqi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2khznmiga.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbilhqpw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2igbgunhg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2awwijxao.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhjaefk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxvfxpl.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gurgrmpj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqehcdbz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmzcwsf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfwnirm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdurfbu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtezacxx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2copjrkgv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bmexzfby.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsibnhg.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzqrsjb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvvflym.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnxyicz.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxvoyiw.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pujwczxu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtwwudr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2upegwlme.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2yttzplng.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdvkpnk.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dswwyobx.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yklyiili.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqllkql.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hncvxqec.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yapbzjtw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfysrzgh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqvhiou.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xomdytov.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvsfcdq.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wyoonbiv.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcgkrfl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eijrmkjd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpwlwub.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmneqdc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbacoush.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2zivramkv.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2pejifzap.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pstwgldv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsivbjt.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxjckjz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvingdm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2llksiacu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zjusmbpw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlpykiz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsikhkic.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxgrqpu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2moqkxbxo.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qmycjtbr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2orqbdxga.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dminzlsv.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfryxbf.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfzdmpn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2shzhfqri.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2egxfybwp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2usbvflzr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzfxazm.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoakybp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxskpkx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtgkwlv.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2qezqmhqt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dircltlt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjkeibg.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2klrdtijg.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdtpppr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgemjfp.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zoeodvcb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2tupqcpjz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxzdpgu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2isywckvc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2trwoiqzy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whifkzjd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhkuyaz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2boebjxpo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hspywjov.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlsufxh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2witwjcap.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2kckewqgy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjtbehh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkucnxq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhcvlcy.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnhidkv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2mephzscp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bndppqxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwcypcu.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfyyamm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjfqfoj.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxrrbil.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2amoacvps.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tivevgkz.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aljhhmok.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojukqphy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2udhocjom.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bckojmkh.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2inoclmzu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2denulklz.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfsyscg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgekjof.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmfbvey.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcbnhub.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2xygwpbce.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypehuiof.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxxoijg.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hreohjny.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oszrdiyq.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hfygnses.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kelduqcb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzuvmjj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2igwsbvea.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hkksnjgx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwmkilt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhvyfis.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2crdhyras.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2erdatinq.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjmqiwd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwffjpug.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2whasokxh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgmxmqi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxghnvqz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2svpvriia.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvevybw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xloouylf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbpfbdo.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2kwykrotu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnjiptc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2domrqenb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mklzlqje.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxecjga.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoizvwr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbabgnoj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2htbrrmda.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2panxcbvt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2xorsuknx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2uiinzprj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2noqdpfmx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2icqcqjng.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwnjura.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpksfkni.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfapawu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2cwminpjn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmftagv.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2okbrxlqi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2uakxydqu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2czvsbryz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2carougjb.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfcjkfq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbjwddl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrslfjjk.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvyeweh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuztlex.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kdirzzzt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2noyohadw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2hivzmdbh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2mszguxux.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2forqcqzw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzylqlrz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmagmrf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpomonrq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfzcamy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkawxln.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzxdfli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fofqnxru.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xippdicy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekslmwdn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2hohlgpea.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwvvgtg.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxyaxhg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibljqiid.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbyrvlr.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2juwuovbw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2yxaftpam.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfzgjoc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2koovmozg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2nubqvecv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufucgvhz.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwexuzkb.html


<!-- 参考信息 -->