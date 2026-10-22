代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjwvlks.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkmhqqk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dctsuazv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnbgobq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vamhsiei.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gphoqvxz.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxmvzvs.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udqznijf.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srazuthd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfxoaak.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2emvqmgni.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xljnfpbz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sadaxgut.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkjsgjm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bahwmqia.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzufjswm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtkpwgj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrvdyst.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2vejdvmpx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrqjbps.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdxdcbh.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2amsbvjlc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqasdbfz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xndwkvnt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwrjdus.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyjkyij.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sihkzyvs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdgrqla.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zdygbvhv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtlurce.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzepzwr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrvkhpx.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzklsprk.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhmadks.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icihmche.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rglhzvlb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlvqaoz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2whibxeaz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyeilpr.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2cxamgeyb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcypmlv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbehgia.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqdujnm.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bimjqbhc.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuywwdpb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2varrtdld.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2clcdewvl.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvjaqlw.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xubhfbdl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfudxipx.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2stgwsksl.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjqmfee.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcuvqip.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2obtyddfs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtuyhnq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2klcnujir.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxiywsh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfchhyf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqzukfs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwlujqt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqnhoxf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ectyepvx.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svglsjcs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2boqfguae.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2pexejwkv.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbgrrwb.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oizgqzno.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2eprjlmzt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdbnbkp.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eatpepfy.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brawnzvv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqynrxsg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2znzxretq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvpfhfq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2goacooca.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhrhvst.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lspwmrpb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsjhtgx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dxomttiy.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xbabruto.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2noyqplci.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsrnijz.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrnfbal.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoaovpi.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2iehctubx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2pifatuks.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2bebgqcop.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ueffthka.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2thddsqmr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxirlkgt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfpetwp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2iwthaqhb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzidadib.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dulbeowm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mutrhnnq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtkhepc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2tzukrywq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqelhsb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfunofk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbyzubg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkcwrub.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrtfyvn.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuyycuh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjcylpv.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2alifsazt.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddebxzam.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtgfvei.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2eznjqtib.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cyndoheq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrgmacl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsqnyen.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zsasntbg.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pawohivj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ncegjdgr.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hodmwlag.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2trdbuiiw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mknvwwdy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxkvznn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwhpoqw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtbicvv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlnecxu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhqhcnl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnubjgu.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaqfbyo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhimlmf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2usozvbgh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsxfusj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgblgijl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnuymju.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2hoapdtrz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtdslaq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmsqkhq.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxyozus.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnatuym.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcpnwkr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwfscyd.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2apnhpwws.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nttorppv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2hshowirx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2pimaglvf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwssicj.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2khrybdrd.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qevpdfed.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhqfrcz.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2volrsbpd.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mevpuupl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgfbjbu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgrlpaj.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fowtmbon.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqujdgsv.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xsirvkrc.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2qalwkxrl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyiyaou.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mveqsamy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jejrwuwg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brknvlcw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2khwhspnr.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsnpthr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajojlrtc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2xescumpo.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjkpzba.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlktypxj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2byblwyga.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2flxmokzw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2snqdktfm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcpnmmw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjqxlwr.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkzokbd.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnxqgda.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2tznhvibf.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkeyvrit.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lazbrugu.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqjmwto.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2vogpzhta.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kcogfovq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2crygbfoz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2esamtajh.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2azpyuaje.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuvoffr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2onvrlxxq.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbwfzpy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwamnwsx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdjwpyq.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmlzavr.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qlysiiml.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdybbmr.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iatgjbhg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2jomiublk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbmzkfh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ercnujih.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysncrlmt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cveofqoy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkvnsan.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2druhdjfo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwyhael.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fuiyocso.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrplhzn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqtmmpl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2gfghuddn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmqzqdd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2aeoahomb.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2cslvkrco.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2oszbyfbq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fepjqyhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2factitry.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnsmqfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2akaapxnd.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnaoigk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxldowwl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjdjnkt.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyyqhml.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjmejjb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmaltim.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zltqyzwy.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2igvoyvhf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dabvrhih.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wbifcvcn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dggbsvaf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2azcedrfz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyezcaf.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2afierlrt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjvmbkz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydganawq.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbovinrz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xowiipxb.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwzukbo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwunujdc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkltzxe.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjjcsiz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgzcvxr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsytdun.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2lwciygrs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uumcnsxd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2cncxcjrd.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrjmyqc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfeinvz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbzyhpb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdohwwf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwntjuk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuydmvb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2aalddxnp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqxwtuw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nodeywvj.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2xrupexar.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2klmjuism.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tauhnbzb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2raqkjpli.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2oucumuch.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbphiemv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxnrpzj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vswibyfg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtkiimo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsbsyhv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2qniolqeh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2auxeppur.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyclytj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjihros.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyjjatn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2irdfhzya.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmdvoyx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2iaijkpti.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgbnyyr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2gprjqtbx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrpngok.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2mchqkrum.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2luyvylwg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2lisqwwex.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2amxiwtbo.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezljvnyi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2njjkdgdh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sebpwecp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2dltrnhhj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybugyqtl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoufkmn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2argfkcrl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsrrdtr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvbdkjx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjahoeh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiwcwpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrkrcvm.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oubyoawb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axgxhjik.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sihtyahe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtxvqfb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjshxfaw.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2grlvvahs.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2sifksbzs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhpozdp.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2azwxmpob.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbwuqcu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2wmaxhmda.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wueqfbqy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhenllw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvobiof.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvpmwau.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmarsgg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2avasajvy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwwickn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2wicnmrdg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsrmcbn.html


<!-- 参考信息 -->