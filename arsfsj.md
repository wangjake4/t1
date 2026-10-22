代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtfgxhfgta.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtlgzsutzu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gtsiddsxpf.html

Ruby: def greet; "admin"; end
来源：http://dali.wangdashe.top/Article/details/gtkoljggsa.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwxsoneo.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmlaqczj.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gtuhdbffar.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gtdpydxvsi.html

JS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpesppzma.html

TS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtzcegejrq.html

Java: super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtextqtwir.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yongpay.top/Article/details/gtmhavahes.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gtsllemhci.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtqzhrelru.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gtsuuetsuu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgfzy.top/Article/details/gtwoptgfhe.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtyihpclba.html

JS:   static f() {}
来源：http://dali.yuanzhike.top/Article/details/gthvnanaan.html

TS:   static f(): void {}
来源：http://dali.pengpengdd.cyou/Article/details/gtikvmymuk.html

Java: static void f() {}
来源：http://dali.yuanzhike.top/Article/details/gtjzfezhha.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gtslhokkuh.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gtnscggder.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gtykyfvgau.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gtmbbtuqio.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gotoacloud.top/Article/details/gtlipkepbw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gtubtzrwis.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.316326.xyz/Article/details/gtvywqeadi.html

TS:   interface Shape { area(): number; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjiycldfc.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gtefppfwtx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gtcxymosvl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.birdmap.top/Article/details/gthsoylvdl.html

C#:   interface IShape { double Area(); }
来源：http://dali.zdqjudy.top/Article/details/gtvesyaoao.html

[G10] 访问控制
来源：http://dali.jiagoushi.top/Article/details/gtnekjpcpj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gtqgiopwfv.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtwcjmqfqx.html

JS:   #private 字段；其余公开
来源：http://dali.fengsongda.top/Article/details/gtavxeixjn.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtfleqfedj.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gtvenjhvxs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gtxnaqhyjx.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtbmpdvhih.html

C#:   public / protected / private / internal
来源：http://dali.wangshuangyany.cn/Article/details/gtkgrsrvkk.html

[G11] getter / setter
来源：http://dali.daria6918.cn/Article/details/gttwgpqkcq.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gtalxpxjyd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzsyguipc.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtbquczhat.html

TS:   get name(): string { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtdsikkyvm.html

Java: public String getName() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtlimqkrad.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtnlyohroe.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gtxrcdkwnf.html

C#:   public string Name { get; set; }
来源：http://dali.cashguo.top/Article/details/gtpdfdhgvg.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gtgdilsyba.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtpoeitasr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtwgxhrzco.html

JS:   toString() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtwevjlzgg.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gttacikpvg.html

Java: @Override public String toString() { return name; }
来源：http://dali.tanke756.top/Article/details/gtwfobuqmz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtrlsbmbub.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtwhkhuwng.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gtsqfwymei.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gtgyfeqvau.html

Py:   isinstance(u, User)
来源：http://dali.sweek.top/Article/details/gtuifnqsax.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gtrjykkxut.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gthfiigrtz.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gthknrhgap.html

Java: u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtoduwfjbg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sxryk.cn/Article/details/gtbhdmkdqw.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gtctmubqeo.html

C#:   u is User
来源：http://dali.zhengqikj.top/Article/details/gtlwsdxyig.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gtnmotwlfi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.smart0.xyz/Article/details/gttxcoihgz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hongshengwenyu.top/Article/details/gtcbtqsomd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gthdqfzdej.html

TS:   type User = { name: string; age: number };
来源：http://dali.iojbl.cn/Article/details/gtgjjoiawc.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gtdzxokymh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258.top/Article/details/gteotugplm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.c1oappe.top/Article/details/gtoxdxwiqw.html

C#:   record User(string Name, int Age);
来源：http://dali.snrcjt.cn/Article/details/gtvvdgyseu.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gtpkevybyq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gtwguhtvlx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zdqjudy.top/Article/details/gteyilntfx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gtuoorklzx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtaaxhnjvv.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gtmuokxhdn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yanxiufei.cn/Article/details/gtqsbfbkxm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujfufrth.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtamzpamgx.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtyahxqsnj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gtsgzbamux.html

PHP:  get_object_vars($obj);
来源：http://dali.shangyingyoupin.top/Article/details/gtzoivmofl.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtcmxxwxcl.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtretuouzt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszamswcb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gtopfdcuuo.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gtywhyzjfk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gthorurlhd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtibdkaspo.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gtiqeeazos.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtotxoqrxt.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gtzcwrmfdx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.meibo888.top/Article/details/gtreraqloz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gtvaxpyvei.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gthawkycwm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtowbxprwj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gtyoptgdim.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuanzx.com/Article/details/gtikwrortj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gtwojrewob.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shuidangran.top/Article/details/gtyqznjhsw.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gtzgvxcary.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yvedp.cn/Article/details/gtjhzohpwm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqjrkccxs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gteitjiqkp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtddhcwxfh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtzzglghtq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gtaedrryjo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.andypj.xyz/Article/details/gtilpvywlp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtwumfhyjm.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtwxrqbpus.html

Py:   raise ValueError("错误信息")
来源：http://dali.gaohongyu789.top/Article/details/gtosicgzat.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtbdaguhcv.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzrswagw.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtdyzsjonv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtdbsyupev.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gtwfskcvyo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhoulong.xyz/Article/details/gtpblnbngd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtavismwpd.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gtxvnvbleb.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gtipjvtzvk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtciktducn.html

JS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gtytdfdoul.html

TS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvffniqep.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtzrrlnwkc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gtyhjbughd.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gtyopjqbqw.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gtjuiwebvl.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtcabfdmrs.html

Py:   except ValueError as e:
来源：http://dali.sweek.top/Article/details/gtslxzsoxp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gtpgwbrvwu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtgrfqodwr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtkcrkyjnk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gtolqsipik.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gtfqmmgknq.html

Ruby: rescue ArgumentError => e
来源：http://dali.kuanghao11.cn/Article/details/gthiartdmv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daria6918.cn/Article/details/gtdhfhrsyp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gtjxrnimjk.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangtech.top/Article/details/gtepofruoy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gteanroqjy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtxiesyqcu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtiokyrxib.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjnbleln.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gtgrsltqqo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ppjwa.cn/Article/details/gtcrxrdera.html

C#:   obj?.A?.B ?? default
来源：http://dali.fengsongda.top/Article/details/gtfkixaysk.html

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtzluywgsb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ydzc1.top/Article/details/gtasztnajk.html

PHP:  assert($x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtsmpxvsnh.html

JS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtnozkvddv.html

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gttijdzunh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hammf.cn/Article/details/gtpynctumy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gtppkfowqx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gtgydhgdsl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtmvlyylmu.html

[H08] 获取错误信息与堆栈
来源：http://dali.gzhubu.top/Article/details/gtwawgkdyp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gttugwbnnj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gtmbflcyac.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gtwaealkkf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guowangkeji.top/Article/details/gtrdtwohcd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgfzy.top/Article/details/gtwheeqphx.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gtyrxkokth.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gtcyaqomds.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gtipozsaju.html

[H09] 带错误码的异常
来源：http://dali.xuanzx.com/Article/details/gtyxfmoiwj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ydzc1.top/Article/details/gtvjsqtuhs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tanke756.top/Article/details/gtdesefyqw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenjidiqi.icu/Article/details/gtomitvljd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gttcjpjbkj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gtshuoibxq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcixdikn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gtksxfzznn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gtdaksjajw.html

[H10] 资源自动释放
来源：http://dali.daxiang520.top/Article/details/gtkiveiysf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenlongwang.top/Article/details/gtyjzuzwzv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jianghu66.top/Article/details/gtkhmjbrsu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtcpqbziuk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtpirouqxi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cashguo.top/Article/details/gtsvqaclra.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gtecbnuwob.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gtzcfqyhxb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgrumfim.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtjenfaiyt.html

I. 正则表达式
来源：http://dali.yueranfly.top/Article/details/gtjsckofdd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gteijrpwbx.html

[I01] 判断是否匹配
来源：http://dali.meibo888.top/Article/details/gtntbsbaci.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtsmzwndcj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtcyefvsae.html

JS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtvjbzmpyd.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtwuafyscy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guannengcc.top/Article/details/gtxvoxikmy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.redwolf501.top/Article/details/gtfozvnonj.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtkhuxhhwn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pycfn.com/Article/details/gtozrcipwz.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtwqdowgnj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtgqqjkxqg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtxpgibyhh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.havefunace.top/Article/details/gtfydnxevc.html

TS:   s.match(/\d+/g)
来源：http://dali.chenzaomai.com/Article/details/gteyiqwfsr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gtssvtwobl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtykqjzvpu.html

Ruby: s.scan(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtvtdqcyam.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkurzbnv.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gtpyynwhvd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuanzhike.top/Article/details/gtyiuswmjl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gzhubu.top/Article/details/gtqoumcdie.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuanzhike.top/Article/details/gtvkvibnlc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yongpay.top/Article/details/gtdooxkyxr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtqrdkzixo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.0kj1m.cn/Article/details/gtmkizckjo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yueranfly.top/Article/details/gtjlwconlu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gtvwfyhxfz.html

[I04] 正则替换
来源：http://dali.havefunace.top/Article/details/gtmcuimyzu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.iojbl.cn/Article/details/gtpaicsuxu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtboroifki.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtgfxyqlxv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtoyjobkrg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gtqjkzofch.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ivvv.top/Article/details/gturrzvswm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.c1oappe.top/Article/details/gtbvxdetxb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtotbodkqp.html

[I05] 按正则拆分
来源：http://dali.jinqigfzy.top/Article/details/gthqkezgjb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gtchzmlnun.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.birdmap.top/Article/details/gthdldcktk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtqhiomnha.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtvifqaryp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.havefunace.top/Article/details/gtmurlnyby.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtupmhfolj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtcusidswy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gtseaugvxx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxamyiyr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtscsvjjkc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.snrcjt.cn/Article/details/gtaedryscz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gtruptmxtn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gttdsizmvs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtvibplnxx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hammf.cn/Article/details/gtlghykydt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtmlidwzty.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gttjhttqso.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gtgahiqsiu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guowangkeji.top/Article/details/gtjofsjnvo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gthncvdnqr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.snrcjt.cn/Article/details/gtcevzqpbo.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gtgidsbdsp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xziqi.cn/Article/details/gtvjvfqqum.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258.top/Article/details/gtvqvcmbof.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gtqkxslbdh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.316326.xyz/Article/details/gtzpfgtocx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gtqyqhaxxv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ehwqpu.com/Article/details/gtcdmyjhbc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtscqyumzz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gtpvgzyxsk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtxqwilwbx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtdlpwhlor.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gtdlsmfoxz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cashguo.top/Article/details/gtcbcnfmmd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtmafyjtbj.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gturkrbtul.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gtjwditudc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkcupymwy.html

[J01] 获取当前时间
来源：http://dali.ybcxt.top/Article/details/gtsbtcemyj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.redwolf501.top/Article/details/gtbdnbzwnj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtwyrghhwx.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtkpfofupm.html

TS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtpqydcxmb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gticsoudnu.html

Go:   time.Now()
来源：http://dali.shzxlz.cn/Article/details/gtjpiouwck.html

Ruby: Time.now
来源：http://dali.ppjwa.cn/Article/details/gtqvndcyym.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gtdnfwmdqs.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtxbewereo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtexupgbzw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gttvifojna.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hysaishi.cn/Article/details/gtvtlkfuyl.html

TS:   d.toISOString()
来源：http://dali.xylfe.cn/Article/details/gtskvifzhf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhengqikj.top/Article/details/gtxfrcggsd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ehwqpu.com/Article/details/gtuqiddegq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtjdnxdxss.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gtkpnwpvkj.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gtiqroveah.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gtmpagquwr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gaohongyu789.top/Article/details/gtnbzkirhs.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtbctmsqcn.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gthvvbiuvl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtqchokfla.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtwvxvbyom.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtodcimnzr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gtxnypasca.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gtzdbiflmr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jyoumei.cn/Article/details/gtscwtkwlx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sxryk.cn/Article/details/gtynyyfpie.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtbmeanbhi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gtsbhojpdg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfchwnsg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aizwys.cn/Article/details/gtthfxgyiy.html


<!-- 参考信息 -->