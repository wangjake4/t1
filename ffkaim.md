代发 wailian999

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gtqvomshoo.html

Py:   def greet(self): return "admin"
来源：http://dali.hywenlv.cn/Article/details/gtrkeearjd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtwmdqhcmz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtxlaueaul.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdtxxypeb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtlydsputx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fzhhl.top/Article/details/gtqbnezfes.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gtjecnwjyj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zycfv.cn/Article/details/gtyusgmtna.html

[G07] 调用父类方法
来源：http://dali.haohaochexian.top/Article/details/gtpwiefnst.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gtcmosskzt.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gtdldftlxy.html

JS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemnoghpq.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtshwrclip.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gtnqfusvvs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gtujzkruhp.html

Ruby: super
来源：http://dali.jqgufenzy.top/Article/details/gtvgmbuerf.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gtotdnncer.html

[G08] 静态方法与属性
来源：http://dali.iojbl.cn/Article/details/gttmnnyigu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgfzy.top/Article/details/gtawkbmfzy.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtlwwkggff.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gtyyjlksuz.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gtndgprugj.html

Java: static void f() {}
来源：http://dali.zhixingplan.top/Article/details/gtmhtggizm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gtmmwjzxik.html

Ruby: def self.f; end
来源：http://dali.jinqigfzy.top/Article/details/gtnzrxccti.html

C#:   public static void F() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhcnfmhw.html

[G09] 接口 / 抽象类
来源：http://dali.ivvv.top/Article/details/gtrdtsfwcv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.quarkkingdee.top/Article/details/gtjnqhivcv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gttwmqrvdv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkznslhvd.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gtdiiwcjcs.html

Java: interface Shape { double area(); }
来源：http://dali.nwbrower.top/Article/details/gtjonwpore.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gtaouruveb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenzaomai.com/Article/details/gthrxbwecd.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gtxnqdqkcu.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gttmnylsjq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.bjfxy.top/Article/details/gttalehzmx.html

PHP:  public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtanlwdfox.html

JS:   #private 字段；其余公开
来源：http://dali.pycfn.com/Article/details/gtpwarpxet.html

TS:   public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtemrdaoer.html

Java: public / protected / private / 默认包级
来源：http://dali.meibo888.top/Article/details/gtvjmmouyw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhengqikj.top/Article/details/gteghsljre.html

Ruby: public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtuwrmpbvv.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gtnngsswzc.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gtkelblcfh.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gtgvwwcywr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtsyfekkhy.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtpygozfrf.html

TS:   get name(): string { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtfjluqvde.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtqzccdsov.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtwziislkn.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gtzicjniwq.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gtisiwqthe.html

[G12] 对象转字符串
来源：http://dali.chenzaomai.com/Article/details/gtmmoksxrt.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtuiwocnot.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtqoenpbky.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomvrmlva.html

TS:   toString(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtmqmbzydc.html

Java: @Override public String toString() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxbsosxwt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtohgrffsn.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigufen.top/Article/details/gtlnzoxicj.html

C#:   public override string ToString() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtqfbwcfju.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gtzvklpfxb.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gthxkybtso.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtcrltjeus.html

JS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtfgsvnzsx.html

TS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtpghndfwi.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtmooqhkrh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gtcinurele.html

Ruby: u.is_a?(User)
来源：http://dali.chenjidiqi.icu/Article/details/gtlvnkmqrx.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gttmzkbihb.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gtazhwwizs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtfexynqxu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gtaswactlr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gtiedgrjej.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgqsorhb.html

Java: record User(String name, int age) {}
来源：http://dali.birdmap.top/Article/details/gtmllgtqal.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gtxqqwhcvk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.feifeiyinyue.top/Article/details/gtaooxklfl.html

C#:   record User(string Name, int Age);
来源：http://dali.jiagoushi.top/Article/details/gtohggsftp.html

[G15] 枚举
来源：http://dali.zhixingplan.top/Article/details/gtqtjctenh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigufen.top/Article/details/gtxyyajvnb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gtutyxzqxz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gttnvbwaxl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtvkvsqaya.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenlongwang.top/Article/details/gtepijooap.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gtbylrctxj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gtxxigwgzy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtflorwfag.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtnnhfaemy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shangyingyoupin.top/Article/details/gtpvlrsqfy.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtbmerzxpm.html

JS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtheftcuhz.html

TS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtefiguhbu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gtczpkoxrr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gotoacloud.top/Article/details/gttfqovfau.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gtwntnqhlu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtremlyr.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcxpamzo.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gttojdxbba.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtpjdjoftl.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gttzqzwpxv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxuanxn.top/Article/details/gthivuxrsm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gtzesoenkh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtusjtuhys.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtcfsbilhj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gtoeslyhmc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gtgzcgktkx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgizbsdf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumatlpwr.html

[H02] finally / ensure 收尾
来源：http://dali.nwbrower.top/Article/details/gtfitxkhor.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fzhhl.top/Article/details/gtsmobgteq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtguonerfq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtkdctwtyp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrqvtzdn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcblbgcj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gtqijqvmbc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gzhubu.top/Article/details/gtlddzlgox.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtvizaproy.html

[H03] 主动抛出异常
来源：http://dali.316326.xyz/Article/details/gtrtcbvsfa.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gtdumtbtfa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtdfyswtdx.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtyzbxgexv.html

TS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtgylijdne.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtscqqxqvy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fengsongda.top/Article/details/gtkvlrvpul.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.svipenyu.cn/Article/details/gthiajgbqz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtysvkrclh.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gtvmghqnmg.html

Py:   class MyError(Exception): pass
来源：http://dali.hammf.cn/Article/details/gtkpmxwibe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtsxzsdstc.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtvxtalucw.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtfqcopvsl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gtjcpzsqan.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gtatwggblm.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj202588.top/Article/details/gtqqzhekhw.html

C#:   class MyException : Exception {}
来源：http://dali.zhongyouzk.top/Article/details/gtraweryza.html

[H05] 捕获特定类型
来源：http://dali.gotoacloud.top/Article/details/gtvhxcnznx.html

Py:   except ValueError as e:
来源：http://dali.sxryk.cn/Article/details/gttjjcypsi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ppjwa.cn/Article/details/gtkxpvqhdt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtolndfhnq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtfmvaveyd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gogol.net.cn/Article/details/gtaywmngch.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daria6918.cn/Article/details/gthlwbdeew.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gthyrrzqbe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gtbvdytwvi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xziqi.cn/Article/details/gtsoabpcgo.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gtwnrtpkrb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtagofgdgo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtjkiisbok.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gthqxhpkbu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.quarkkingdee.top/Article/details/gtpjtfwkzw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gtuycksnxf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sufxvd.cn/Article/details/gtsypoqpge.html

C#:   obj?.A?.B ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtbtsgecdq.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gtpvrczqqr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ehwqpu.com/Article/details/gttyapcgua.html

PHP:  assert($x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gteluhzbfs.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtcriewrju.html

TS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtcsrwsypg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zycfv.cn/Article/details/gtloyiozat.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gtmnsgwakg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gtkgtrmjvw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gthvaegaiq.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gtmwbvinmw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yongpay.top/Article/details/gtzqkucgct.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gtagfpeidh.html

JS:   e.message;  e.stack
来源：http://dali.sysykeji.top/Article/details/gtnhcxreqj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.mhx1999.top/Article/details/gtsecbfuav.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cqqwz.cn/Article/details/gtsvpmltom.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gtekhvlsak.html

Ruby: e.message;  e.backtrace
来源：http://dali.fengsongda.top/Article/details/gtmjsrfqph.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gtyrgcqdai.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gtpkmlizhm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gtlbwevapn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gtvvpfgytm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ivvv.top/Article/details/gtccjrqhxk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhixingplan.top/Article/details/gtbsbwjhsz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gtrtzxgocd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gtolakywcl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gtvffqywru.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gtpccpyher.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gtsbprsegl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gtwedyfudv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gtrmxojkrm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtguefwmed.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtjgtsihda.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fzhhl.top/Article/details/gtdhnywgot.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgaecseuh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtvqxdtabk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtvoavnpaq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjpvjtudd.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gtpkvdonao.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtcyficdpq.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzovjgeh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gtjlyrxeiq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtnkazhbgh.html

JS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfrsvphn.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtoegqhjyd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.0kj1m.cn/Article/details/gtjrsnudjc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtysjdqnyh.html

Ruby: s.match?(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtncpovcor.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhengqikj.top/Article/details/gtpruqzmgm.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gtqqnwlqmw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtlogthhow.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gttqyrshvg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gtaoevzttn.html

TS:   s.match(/\d+/g)
来源：http://dali.yongpay.top/Article/details/gttbukfypd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtsvhgysfx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gtslnvnwfa.html

Ruby: s.scan(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtjaepamrv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtphcvlbio.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gtfjsowtvt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.svipenyu.cn/Article/details/gtiidajisi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.c1oappe.top/Article/details/gtymvwiaup.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.redwolf501.top/Article/details/gtwxpcpxws.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258.top/Article/details/gtcexvrneb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtkrlqgpbc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dashuyun.cn/Article/details/gtnzypvmbj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gtylblcrwq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gttfxpqish.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gthtqkzzsg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuxming.cn/Article/details/gtbnhzffvp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gtskdxudmi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gthvlwniwk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgqmatip.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtvyllgyaw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yueranfly.top/Article/details/gtyixalnnw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jyoumei.cn/Article/details/gtvzrweobw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gttvhiwanc.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gtlerjannw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.smart0.xyz/Article/details/gtbkezkdqq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtiymnbjka.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtiahfpafi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtowbkwzbs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cheryme.top/Article/details/gtlhcdlhue.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtevgqdvki.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtfahrrubs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xziqi.cn/Article/details/gtfhgixclo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxinkj.top/Article/details/gtowttltew.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gttxtbatyq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gtmasobapx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtbjlolrrw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gtyleqvtbb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtwzgmbbtq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj202588.top/Article/details/gtpnnesdlk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gtgwucjdpw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gtduxbzfkv.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gtqlnoldev.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ydzc1.top/Article/details/gtzmshhtpv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtnmpnknut.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gtkygkkpmr.html

TS:   /error/gim
来源：http://dali.zhixingplan.top/Article/details/gtypsoekyw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guowangkeji.top/Article/details/gtjqpmxkod.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhoulong.xyz/Article/details/gtmgwqutao.html

Ruby: s.scan(/error/i)
来源：http://dali.mhx1999.top/Article/details/gtdjbbbsph.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gtsuupbhxs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtmiudxurl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuxming.cn/Article/details/gtompcsuxh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtegmssyxk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtenwgwojl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtehoxacaz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtzrhpggzx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnxiangtu.top/Article/details/gtdiscuxro.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gtdzrryrdi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtwduyeqsr.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkeauvtbj.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gtmwwmwsoe.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtyerjnaeq.html

[J01] 获取当前时间
来源：http://dali.nwbrower.top/Article/details/gtbsvfahej.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhoulong.xyz/Article/details/gtonbhttkw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtesaveafg.html

JS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gtkkldxkla.html

TS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gttunrayix.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenzaomai.com/Article/details/gtngdrpqch.html

Go:   time.Now()
来源：http://dali.jlsjyb.cn/Article/details/gtjhkfacpw.html

Ruby: Time.now
来源：http://dali.ydzc1.top/Article/details/gtlrtwvurh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yonumen.top/Article/details/gtetdywxbm.html

[J02] 格式化输出
来源：http://dali.guowangkeji.top/Article/details/gtsqmndntr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gtmonyilgc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtdfcdkojq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gtiquktbcx.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gturhpfspp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sufxvd.cn/Article/details/gtutcudozj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gtawbcbped.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtebgdzsrj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenjidiqi.icu/Article/details/gtosfoggxf.html

[J03] 字符串解析为日期
来源：http://dali.zycfv.cn/Article/details/gtzslaxrmr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gtwjpftwos.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumiujnru.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtmxkexaoh.html

TS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gthnnrgxyn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtkuqyzauw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtertpeqtm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtckdmtizd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yueranfly.top/Article/details/gtjfjcgwps.html

[J04] 时间戳与日期互转
来源：http://dali.hywenlv.cn/Article/details/gtodxamidh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gthbchnhbd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jianghu66.top/Article/details/gtsafzrgnn.html


<!-- 参考信息 -->