代发 wailian999

Java: class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtlfpghvti.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.0kj1m.cn/Article/details/gtsvslhvgb.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtggklibew.html

C#:   class Admin : User {}
来源：http://dali.cashguo.top/Article/details/gtplnuhwvv.html

[G06] 重写方法
来源：http://dali.ivvv.top/Article/details/gtksmncatt.html

Py:   def greet(self): return "admin"
来源：http://dali.sxryk.cn/Article/details/gtarhtrsci.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gthsiitkjd.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtgxcujvnt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfmdrnjyo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtiqzrjjec.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gtbpotmmrj.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gtskrgsyph.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesoudjwk.html

[G07] 调用父类方法
来源：http://dali.yueranfly.top/Article/details/gthebolnyn.html

Py:   super().greet()
来源：http://dali.zdqjudy.top/Article/details/gtqqgqjath.html

PHP:  parent::greet();
来源：http://dali.fzhhl.top/Article/details/gthebhvxqw.html

JS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtzcirsqhh.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtvlevwsrt.html

Java: super.greet();
来源：http://dali.redwolf501.top/Article/details/gtajarkufx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gtynhoqiqk.html

Ruby: super
来源：http://dali.yongpay.top/Article/details/gtdegzzcyy.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gthmclvojk.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gtfcamzhal.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnxiangtu.top/Article/details/gtfgpsrumx.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuifeadum.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gtqprjhprg.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gtgsrujgdn.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtuwnqcseq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gtvwsafsds.html

Ruby: def self.f; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajcusynw.html

C#:   public static void F() {}
来源：http://dali.sweek.top/Article/details/gtimorynqx.html

[G09] 接口 / 抽象类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjnigezj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gtakfzbkot.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ivvv.top/Article/details/gtuvbuvjuh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtmzdwsdbo.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gtpohrukjz.html

Java: interface Shape { double area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtmjrifvsl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gtlbkavwkx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigfzy.top/Article/details/gtusczrmhi.html

C#:   interface IShape { double Area(); }
来源：http://dali.0kj1m.cn/Article/details/gtsfobkcwn.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gtawhwrvkc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gttkkegzdh.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtcncpevwy.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gtouhzujwn.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtivyilohm.html

Java: public / protected / private / 默认包级
来源：http://dali.aizwys.cn/Article/details/gtmphzjphs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jlsjyb.cn/Article/details/gttiyoztpn.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtcnfmudjz.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gtxhqdfiuj.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gthstcmogt.html

Py:   @property 与 @x.setter
来源：http://dali.sysykeji.top/Article/details/gtlszewcvn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gteryobpwd.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtrdisvtrm.html

TS:   get name(): string { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtomhezypg.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtdqlgzwiy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtkywkiiga.html

Ruby: attr_accessor :name
来源：http://dali.zdqjudy.top/Article/details/gthwwivqvr.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gtqdywxwvk.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtlscfscfo.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtfljogtug.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzfvzytbe.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtnozyvmam.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtxgkzgxtx.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtzkooctmo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtefecirbo.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gteyttphwz.html

C#:   public override string ToString() => Name;
来源：http://dali.guannengcc.top/Article/details/gtymwsqdhc.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gtdfcyyrxw.html

Py:   isinstance(u, User)
来源：http://dali.gotoacloud.top/Article/details/gtddqfxduq.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gttasaxawy.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gthbkyhbkn.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtukcurscw.html

Java: u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtnexijtyv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gtmwtkxunp.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gtxewdkwmg.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gtkdemvonu.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gtzflzxxvg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gtkuwppqst.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnqzz.top/Article/details/gtlfzwcwcz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gtxhrvpmjp.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gtnpkuvzqo.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gtfrltenks.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gteyghpnne.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gtvnangwpd.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gtndhtdtar.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gtghdnpmvx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cdnleiting.top/Article/details/gtqpschwup.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gtxgjjjqtt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gtiywtbsjq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtrcziupiu.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gtzndimbnw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.snrcjt.cn/Article/details/gtzgnoevmy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pycfn.com/Article/details/gtbbcxyyjt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gtzrtyscgk.html

[G16] 对象转数组 / 字典
来源：http://dali.jyoumei.cn/Article/details/gttiisnxoc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gtwgmubeaf.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gtowqpirnu.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gttqriqleu.html

TS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtqutplzuy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gtgxulakdb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.vqdsnc.cn/Article/details/gtxsipjrue.html

Ruby: obj.instance_variables
来源：http://dali.dashuyun.cn/Article/details/gtnmdppwrx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gtlvvhclxb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxassxefw.html

H. 异常与错误处理
来源：http://dali.chenlongwang.top/Article/details/gtqzxatseb.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtziajwosv.html

[H01] try / catch 基础
来源：http://dali.cdnleiting.top/Article/details/gtommtjwlt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gtrgbksfwh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gthmbjmgfv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtlzsaebri.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtrjfuwxhw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.feifeiyinyue.top/Article/details/gtnafmxeov.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gtlggnsuua.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhiwuduotai.top/Article/details/gtbviweswk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gtymtkceug.html

[H02] finally / ensure 收尾
来源：http://dali.fzhhl.top/Article/details/gtmdkrnvyw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsfioufh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxbxfrim.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtgewgvcun.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gteuhtabij.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtnnbhvsym.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tianlin.xyz/Article/details/gtuqxdceoz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuxming.cn/Article/details/gteulpwvqd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gthnpfnvyx.html

[H03] 主动抛出异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxdvvvyu.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gtdnwtawcd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtzxpierfn.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtquvlalei.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtokivqvik.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtinprkvod.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hywenlv.cn/Article/details/gtoilpivpl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpgcimbd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtpjulbfti.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gtbljrycrc.html

Py:   class MyError(Exception): pass
来源：http://dali.meibo888.top/Article/details/gtxnogldoy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtmrdmntbr.html

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtkcitnifi.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtqtqechwu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtluuloeqa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gtdtkdvtqp.html

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gtoymftjpa.html

C#:   class MyException : Exception {}
来源：http://dali.tian-w.cn/Article/details/gtymfwswcy.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gtzqbvxsdo.html

Py:   except ValueError as e:
来源：http://dali.ydzc1.top/Article/details/gtkushmatw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gtvknsvqvo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gtekozjqso.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtlkllrtxp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gtxptxyxva.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sweek.top/Article/details/gtwkgbnqzj.html

Ruby: rescue ArgumentError => e
来源：http://dali.quarkkingdee.top/Article/details/gtdjstjwsi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gtdluiycwt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhixingplan.top/Article/details/gtlkddsniq.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gtdtkufbid.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gttgffclpj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtclmouciy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnoenkrqw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gtdnfnxkhm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tian-w.cn/Article/details/gtzsqifvmy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gtsbspnizq.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gtnxpzwbhc.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gteaqjtaee.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxuanxn.top/Article/details/gtwzzkidnm.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtzlczwjta.html

JS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakszzoxb.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtjbpyzwms.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sufxvd.cn/Article/details/gtbypusebx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hfpthk.cn/Article/details/gtygclrwrk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gtirphkhrk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gttommmzps.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gtcdqzmzza.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gtbkiqrcmq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gtziosuhee.html

JS:   e.message;  e.stack
来源：http://dali.yuxming.cn/Article/details/gtzzwlswxt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gtelwjqqkv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yongpay.top/Article/details/gtmrsteisf.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gtfmumvktu.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gtwhmpvkpg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgfzy.top/Article/details/gtmadznboe.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtrbuhhcal.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gtvrevqlcg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtqzcqvpyf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gtjqdllyyc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgufenzy.top/Article/details/gtyjxtapka.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gtnzmyemrn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gtctjmsusl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ivvv.top/Article/details/gtuvujltis.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnxiangtu.top/Article/details/gtvuutcwti.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gtvcuxcfck.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gtwgvipicm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gtuhdygtyh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtdvvhgjds.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtseriodid.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dianchejie.cn/Article/details/gtodutdloy.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gtvqqupppi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.c1oappe.top/Article/details/gtbwdxqxov.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtsdxzogmh.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtqrblkdlc.html

I. 正则表达式
来源：http://dali.cqqwz.cn/Article/details/gtkgilvkkw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtjsfrdsbi.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gteqycjvqf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gtbhkzsdly.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtfmnrwmme.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gtyumujsyq.html

TS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gteczdielo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.haohaochexian.top/Article/details/gtjzmqqqpt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gtrbunamny.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtimdgqafx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.mhx1999.top/Article/details/gtqhywrswk.html

[I02] 提取所有匹配
来源：http://dali.guannengcc.top/Article/details/gthtbafjlk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtyohwcgrb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gttzhenjnj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sufxvd.cn/Article/details/gtqagxujds.html

TS:   s.match(/\d+/g)
来源：http://dali.pycfn.com/Article/details/gtswdbilqi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipufufbt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.birdmap.top/Article/details/gtqdtvbhvy.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtajtacijn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtxzctvdzk.html

[I03] 提取捕获分组
来源：http://dali.ydzc1.top/Article/details/gtgxhtxfgc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gtvrjwnify.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258.top/Article/details/gtxxajeqot.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gttqzlywkd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.snrcjt.cn/Article/details/gtetspbphu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sxryk.cn/Article/details/gthotgelir.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gtatsudedj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gtubjhuktu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daxiang520.top/Article/details/gtzgniikou.html

[I04] 正则替换
来源：http://dali.yuanzhike.top/Article/details/gtmtigopyg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gtxsixbrny.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtsnydsfxc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtanpocpps.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtfdpmmcum.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtcbjupltr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgfzy.top/Article/details/gtxgxaerct.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gteemtembo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gtjiivdiks.html

[I05] 按正则拆分
来源：http://dali.svipenyu.cn/Article/details/gtgkfkupgz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.birdmap.top/Article/details/gthqrdiqnv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtztsavkmu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gteozbtuah.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtvtakzfyj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gtagotqaeq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtiosvmqlq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtkzqfvgpz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuxming.cn/Article/details/gtmwkkiyid.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gtplancdcv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtceznzqes.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.smart0.xyz/Article/details/gtlxxiszoh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtyjvedonp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtvsqfpdpa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtfoiqkhxc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ybcxt.top/Article/details/gtporletih.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.bjfxy.top/Article/details/gtkqybxzob.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtbimjqvvo.html

[I07] 忽略大小写与多行模式
来源：http://dali.jianghu66.top/Article/details/gtqolfnnky.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigufen.top/Article/details/gtureoejfh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gtjjowkqoc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.smart0.xyz/Article/details/gtdeomliud.html

TS:   /error/gim
来源：http://dali.zhiwuduotai.top/Article/details/gtbyregvqe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gtxwjgvqpf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigfzy.top/Article/details/gtxkjqwxev.html

Ruby: s.scan(/error/i)
来源：http://dali.tian-w.cn/Article/details/gtbnkbjfdg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gtezmyaesj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hammf.cn/Article/details/gtviqiealz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.birdmap.top/Article/details/gtqlfzueav.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gteuyayfly.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gteqlawwur.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbqdggnx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gtzbxnluih.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvmzttaq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gtehxjysei.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gttunswnnz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtutxrgesb.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gtuchpjnaj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtpekrucbz.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gtjnqpjhoy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gtlobttwyi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gtxrjsbiwg.html

JS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gthuhwsgtu.html

TS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtpdpyiizi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gtrpeufdhc.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gtpqqmmoxp.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gtdqpicvhg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gtnadonprx.html

[J02] 格式化输出
来源：http://dali.jinqigufen.top/Article/details/gterhmiozg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gtudjvfpho.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gtaazntwqr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gtukdbvwni.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gtfqenqfho.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gtejalthic.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gthmdftzpi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtfvafrqvh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gtiaebuxgf.html

[J03] 字符串解析为日期
来源：http://dali.ehwqpu.com/Article/details/gtomvetyox.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gtafdifuam.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgfzy.top/Article/details/gturqexrlc.html

JS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtkqchxlaq.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtbacasntr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtzmaboapb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgrjaubf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtxjgvewks.html


<!-- 参考信息 -->