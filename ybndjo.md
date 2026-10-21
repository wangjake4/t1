代发 wailian999

[G06] 重写方法
来源：http://dali.zhoulong.xyz/Article/details/gtthnkvuit.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gtbidaimgy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtnbmvszqd.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtqloctqsg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtwycqvavq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtloazoeqa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gtlmijhwry.html

Ruby: def greet; "admin"; end
来源：http://dali.ydzc1.top/Article/details/gtfeqcmhul.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtrxujxput.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gtlhymbytx.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gtmbnlgabr.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gtqhtyzqac.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtjuapuuiv.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtqhwiaugg.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtqdpytfwx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnboaoqh.html

Ruby: super
来源：http://dali.jinqigfzy.top/Article/details/gtarhijfwf.html

C#:   base.Greet();
来源：http://dali.shuidangran.top/Article/details/gtdutgywhq.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gtwwsntylz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gtblrdlxah.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtsrvqwchg.html

JS:   static f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuqirgbo.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gtxetzbqpd.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtncksauam.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cdnleiting.top/Article/details/gtfcqxeogm.html

Ruby: def self.f; end
来源：http://dali.gogol.net.cn/Article/details/gthxxfqfle.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gtcmdwxxcw.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtxiooauxs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guannengcc.top/Article/details/gtjwbgianc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gttytxqphb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258888.top/Article/details/gtsdjgxpxk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zycfv.cn/Article/details/gturaheeqm.html

Java: interface Shape { double area(); }
来源：http://dali.hnqzz.top/Article/details/gtvmhxjceg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnvibqta.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gtflbaarmh.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gteowzhflg.html

[G10] 访问控制
来源：http://dali.fzhhl.top/Article/details/gtkhmlesyt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gtkneujwmz.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtagpxoqce.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gtqnosztjx.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbatrlur.html

Java: public / protected / private / 默认包级
来源：http://dali.hnxiangtu.top/Article/details/gtjtsaxmmb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zdqjudy.top/Article/details/gtgnftbxzd.html

Ruby: public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtvrrinncj.html

C#:   public / protected / private / internal
来源：http://dali.jlsjyb.cn/Article/details/gtjpjzcvvo.html

[G11] getter / setter
来源：http://dali.tian-w.cn/Article/details/gtwmtnftun.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gtbtqdoaoy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtdzhwhsld.html

JS:   get name() { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtkvoygjmt.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuazfgqwv.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtncnjzuwl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtiszstgbj.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gtsubrhclb.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gtbrymwgwt.html

[G12] 对象转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtqbtxbjhs.html

Py:   def __str__(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gtwpfajypw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtztizxbco.html

JS:   toString() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtisogfgqy.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtqmgtquwf.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtununjxjx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtgmlrytrq.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtuckqpooz.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtccxbgqru.html

[G13] 判断对象类型
来源：http://dali.chenzaomai.com/Article/details/gtaajlsspg.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gtyhctijbj.html

PHP:  $u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtsplhpaea.html

JS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtbxdignqg.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gthhqncweq.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtyiuvnvqm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gtoylynqvc.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gtmxgoawvp.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gtxkriojiw.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gtagspfcxy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gtcefkbbxk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gtaroblfgq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.mhx1999.top/Article/details/gtmmsygzrn.html

TS:   type User = { name: string; age: number };
来源：http://dali.jiagoushi.top/Article/details/gtpqjczwiv.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gtwqvdcxwl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gtzczgdgbx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtnqbrwuej.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gtlghygsoe.html

[G15] 枚举
来源：http://dali.yvedp.cn/Article/details/gtfktpbotm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guowangkeji.top/Article/details/gtukpadwov.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gtcmxcpfgc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gtdaokqzrl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtjfpqsuor.html

Java: enum Color { RED, GREEN }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwspxiugv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gttqvzjmst.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tanke756.top/Article/details/gtnbjkrxli.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gthvqxqwcn.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gtasljctrc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tanke756.top/Article/details/gtmkupmwcs.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxqfgnwo.html

JS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtblfjasmn.html

TS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gtsumwacdb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gtepkiplxt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dianchejie.cn/Article/details/gthdqmztrx.html

Ruby: obj.instance_variables
来源：http://dali.zhiwuduotai.top/Article/details/gthzocribt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtsqwojitu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtvdoferco.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilvhzhwx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtrlaybauu.html

[H01] try / catch 基础
来源：http://dali.cdnleiting.top/Article/details/gtqixswiif.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cheryme.top/Article/details/gtkpecsnop.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhengqikj.top/Article/details/gtnobgppzp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtpyowyrkx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gtmazxboci.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtmecosuop.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbmujgwj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.kuanghao11.cn/Article/details/gtbfvdwmjp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gtvvfdyqeb.html

[H02] finally / ensure 收尾
来源：http://dali.iojbl.cn/Article/details/gtsyxejfsh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gtwokyqhcs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtvvbluvfo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfnbhxqj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtbuelkivp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtoblrlegx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sufxvd.cn/Article/details/gtptughcgr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gtggxtwjvr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtwwhktkwi.html

[H03] 主动抛出异常
来源：http://dali.yueranfly.top/Article/details/gtctvvrxio.html

Py:   raise ValueError("错误信息")
来源：http://dali.ydzc1.top/Article/details/gtsrshnxsz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtttjgatag.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtfieebyot.html

TS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtoioaasza.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtqjyccifz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gtxcurlixc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pycfn.com/Article/details/gtvbdpfbsk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtsjqbkgxy.html

[H04] 自定义异常类型
来源：http://dali.kuanghao11.cn/Article/details/gtdqxqbbap.html

Py:   class MyError(Exception): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtcdumcgto.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtsztcxtki.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtemloqide.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtjlgpxadz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtgnvyzmce.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gtcbybukod.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gtxbdlbdjo.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gtcdeanmfi.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gtdfjxzadm.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gtmhceyexi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gtijhpmyiq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gtitxaorvz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gtnguyzgyv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hfpthk.cn/Article/details/gtduzhglfq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.0kj1m.cn/Article/details/gtarceuvml.html

Ruby: rescue ArgumentError => e
来源：http://dali.316326.xyz/Article/details/gtjborkxxw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.snrcjt.cn/Article/details/gtokbkfzxg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daxiang520.top/Article/details/gtxbbvjgrw.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gtuwwdjcbx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtcjuczdxi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtefkfrbki.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtatgcaffi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gtcekdkwaw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ivvv.top/Article/details/gtrmvfgwae.html

Ruby: d&.dig(:a, :b)
来源：http://dali.havefunace.top/Article/details/gtrdxuzajw.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykgwxugs.html

[H07] 断言
来源：http://dali.yueranfly.top/Article/details/gtvakurvta.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gtpxmiozac.html

PHP:  assert($x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtquiunnpi.html

JS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtqslijosr.html

TS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtsamhlqos.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gtrjrnemhg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxuanxn.top/Article/details/gtwybdbltz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cheryme.top/Article/details/gtlqaxjxia.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtgtcjelzy.html

[H08] 获取错误信息与堆栈
来源：http://dali.nwbrower.top/Article/details/gtjhoxeaac.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gteuptqens.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sufxvd.cn/Article/details/gtpatfesgy.html

JS:   e.message;  e.stack
来源：http://dali.daria6918.cn/Article/details/gttkpdfvkf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gtwvnpbadu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gttibhzmwp.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gtlwgvexre.html

Ruby: e.message;  e.backtrace
来源：http://dali.gogol.net.cn/Article/details/gtcbhibjid.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gtqcxjrdgh.html

[H09] 带错误码的异常
来源：http://dali.hnqzz.top/Article/details/gtiiyzlzyk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gtlwknmnuo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtdvlkmqya.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gtgdamfjdh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gtrhbdulhc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gtxxhugliw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gtwlrqnwqy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.haohaochexian.top/Article/details/gtrzoypjds.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gtmsaqlorz.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gtsmniibeg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pycfn.com/Article/details/gtworbxqvx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gtmngzyhrv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtxncqegxr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtutxhpnos.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxuanxn.top/Article/details/gtfmbrraye.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrqfcojq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuetiantiany.cn/Article/details/gtjbvljscm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtpjudrkyr.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjarstecp.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gtpcztqgwz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gttlygmkyl.html

[I01] 判断是否匹配
来源：http://dali.sxryk.cn/Article/details/gtbxpoovcx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtnwbeehuf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtfyeuimzg.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtgttvezvx.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtsiwchynx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.smart0.xyz/Article/details/gtwyevhoaa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hysaishi.cn/Article/details/gtiuntppdx.html

Ruby: s.match?(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gtahtjocrn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.meibo888.top/Article/details/gtggsayepl.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gtigjptuxo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gtfdcyxsfk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gzhubu.top/Article/details/gtwjrodjgr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gtntzfthkq.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpaokjdvh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgidwjbp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gtinzrhlhf.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtegxgzalv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtyczwepka.html

[I03] 提取捕获分组
来源：http://dali.316326.xyz/Article/details/gtjhsbhsvf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gtucgbnknm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hfpthk.cn/Article/details/gtnluymwuq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gtjpjqutqw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgusovfux.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gtezujmqqa.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinghuilouyu.cn/Article/details/gtgojelzgl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxinkj.top/Article/details/gtihxercgi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.havefunace.top/Article/details/gtfrjyafbt.html

[I04] 正则替换
来源：http://dali.chenzaomai.com/Article/details/gtwrkiwuhs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenzaomai.com/Article/details/gttlwfffgb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gtvkaufklw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gttlxlroto.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gtyqrmjzqj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtjkzgwyrh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yangfankeji.com/Article/details/gtudtzulwi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gtrqzbaply.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtaqzbouag.html

[I05] 按正则拆分
来源：http://dali.bjfxy.top/Article/details/gtokfvjycw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gtqgbacgcu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangdashe.top/Article/details/gtlcchuyya.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtvswsnzup.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtiypggmrg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ppjwa.cn/Article/details/gtvazqzfsy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtfrofqiyg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtoeoekiqh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gtkdscfomz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymnushoo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtifeinzvp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258888.top/Article/details/gtfomzysmn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldnxegxa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtxwqoepwy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtiifybstl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gtkfxeqpea.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xziqi.cn/Article/details/gtovyokwlm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtdxdlohoe.html

[I07] 忽略大小写与多行模式
来源：http://dali.snrcjt.cn/Article/details/gtseebyqjf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yanxiufei.cn/Article/details/gtgstzpurj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gttulujlug.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cheryme.top/Article/details/gtpjiplukb.html

TS:   /error/gim
来源：http://dali.yj20258.top/Article/details/gtutnlnonm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fzhhl.top/Article/details/gtyqoqtafa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gtxkqavnvg.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhhapvqs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dashuyun.cn/Article/details/gtvijzjieb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtypibwzsc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tianlin.xyz/Article/details/gttswwvtvw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtpdkglfjt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gtgisxvpat.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtbypwvjku.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gttspfwbcl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gtpstozfml.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yanxiufei.cn/Article/details/gtrnaklhcw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtusavqrmy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjtpkdnka.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gtdefovrxd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtofaemdiu.html

[J01] 获取当前时间
来源：http://dali.aizwys.cn/Article/details/gtwnhkwdil.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigufen.top/Article/details/gtcelkkirr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtkfchfwig.html

JS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gthlrmptqx.html

TS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtvsymbkcg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gtvbnqetuy.html

Go:   time.Now()
来源：http://dali.jqgufenzy.top/Article/details/gtjyehivca.html

Ruby: Time.now
来源：http://dali.cqqwz.cn/Article/details/gttgbttgra.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gtufmjiniq.html

[J02] 格式化输出
来源：http://dali.haohaochexian.top/Article/details/gtxbhksbsl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtrambbnlx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtaiylqkwl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gtkhmfqwnv.html

TS:   d.toISOString()
来源：http://dali.sysykeji.top/Article/details/gtualvzfwn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgufenzy.top/Article/details/gtndkfenqa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dashuyun.cn/Article/details/gtzgdwuwcm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gthfquridz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hywenlv.cn/Article/details/gtgytnucgd.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gtudkbvbkf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gtevqjzdog.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gtenqumaoa.html

JS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtirwofnqx.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtmfareymo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtyhpudtyn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtaxxbaylh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtiwxqtzru.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.0kj1m.cn/Article/details/gttjenflqf.html

[J04] 时间戳与日期互转
来源：http://dali.andypj.xyz/Article/details/gtnzrszgpa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hammf.cn/Article/details/gtmwhyuqjb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daria6918.cn/Article/details/gtnmmcksni.html


<!-- 参考信息 -->