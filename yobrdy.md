代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.zhongyouzk.top/Article/details/gtotkfwjtv.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtlrumzfib.html

JS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtvhhetkyz.html

TS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtqwiuawvi.html

Java: class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtmnkzhjwv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fengsongda.top/Article/details/gtvrejfbbr.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gtzpqhjpqe.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gtnjhpqmzy.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gttldrmlrj.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gtsxywwkbn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtwrogqotp.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtsstjhdon.html

TS:   greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtwhagedsu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjiatbcwo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.svipenyu.cn/Article/details/gtyhtewsva.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gtvgoftzcj.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gtinprptfn.html

[G07] 调用父类方法
来源：http://dali.cucudq.cn/Article/details/gtruhmuumj.html

Py:   super().greet()
来源：http://dali.yongpay.top/Article/details/gtseedqwlv.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gtfdfnsbie.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzqshaib.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtllbhqbby.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gtgjjhfgkm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.bjfxy.top/Article/details/gthoyboqrv.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gtlekemile.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gtimifogsa.html

[G08] 静态方法与属性
来源：http://dali.iojbl.cn/Article/details/gtsojhyaua.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gttspkjoqd.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gtdsnwbxds.html

JS:   static f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtysubxxah.html

TS:   static f(): void {}
来源：http://dali.gzhubu.top/Article/details/gtqkyjzpez.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtszvwfsyt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gtwrbwrfhj.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gtobqtjdeo.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gtceqbxkoy.html

[G09] 接口 / 抽象类
来源：http://dali.fzhhl.top/Article/details/gtsoekiigb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gtohvpefhr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenzaomai.com/Article/details/gthdysfeig.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jiagoushi.top/Article/details/gthyhjccek.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gtkayvjpoo.html

Java: interface Shape { double area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtsbqqbgeo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gtwpjsajrr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gtikhefwft.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gtrcfilleh.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtapzghhcl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzpphtqi.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtiqdcuiti.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthunmvsk.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtdeqjxpca.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gtjccfhjff.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhengqikj.top/Article/details/gtawkskefe.html

Ruby: public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtflayfjvb.html

C#:   public / protected / private / internal
来源：http://dali.yj202588.top/Article/details/gtuadqdnem.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gtkqznbmif.html

Py:   @property 与 @x.setter
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtnrmkkc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnannuxr.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtlrcwtcuj.html

TS:   get name(): string { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gtyephjqfg.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtyoswnmix.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtflkhmsog.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gtlejriojj.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gtlapenjpb.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtijnloqzf.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtmlwzemqe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtyynjsnfm.html

JS:   toString() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtpfeldnmf.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtbsrsixlu.html

Java: @Override public String toString() { return name; }
来源：http://dali.tanke756.top/Article/details/gtjdpqubfq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtwnxyrqev.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbaiqwcp.html

C#:   public override string ToString() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtlqqmvvoa.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gtdoyjcesz.html

Py:   isinstance(u, User)
来源：http://dali.jlsjyb.cn/Article/details/gtqwcyvxxx.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gthqprnomu.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtsfwtrwug.html

TS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtngvupfph.html

Java: u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtnivlucib.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaietabxw.html

Ruby: u.is_a?(User)
来源：http://dali.yangfankeji.com/Article/details/gtcuvablbg.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gtvxtwnlrs.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gtvvotjzjy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfqjnwic.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gtyvoexeem.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenjidiqi.icu/Article/details/gttrzynmtf.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gtskmcqbmy.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gtvbfnqtdu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dianchejie.cn/Article/details/gtpemkjexm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gtrwqmvnud.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gtjpkilloq.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gtudlcovri.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xinyue.icu/Article/details/gtlugvmuua.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgitbbmff.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gtorurccwt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gtykgcreob.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gtblkqmcdp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.havefunace.top/Article/details/gtdcbqkfum.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gtytquabfx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtdjazeuja.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqpdskgy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gtopeptmaa.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gtgyrcuyby.html

JS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtdpyijnup.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtixxmzmax.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitceqojq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbyugvvc.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gtqvugzqxs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtsksnlxwe.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtpodhvvew.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gtlgeawzlo.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtbwjqszew.html

[H01] try / catch 基础
来源：http://dali.quarkkingdee.top/Article/details/gtetkxpeew.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gtbnouutnz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hammf.cn/Article/details/gtmnvtshrr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtozqhzjug.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtqbctwybq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gtyvdfwydf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zycfv.cn/Article/details/gttsbouiak.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ehwqpu.com/Article/details/gtqvvkljpt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdllbokkg.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gtpaoijnlx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gtftadschj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtvbrdlxac.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtgehvcoee.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtmbseizub.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gthnmvfazk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.svipenyu.cn/Article/details/gtkhkchucb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guannengcc.top/Article/details/gtufqoklwg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gthlvdjold.html

[H03] 主动抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gtixduztyx.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gtkwltjrxy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtgvvxzdfi.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtjxjiwjzc.html

TS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtfjopudyx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtuybycuib.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gtufbovohl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gteadvscbg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtjxghjqku.html

[H04] 自定义异常类型
来源：http://dali.chenlongwang.top/Article/details/gtiavwcmln.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiophkhse.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gtshjsmmlc.html

JS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtudmfsvxx.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtamrsquol.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtrdlgxvim.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gttvaqckuj.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnebtosry.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gtubqzyhvl.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gtkloahqxd.html

Py:   except ValueError as e:
来源：http://dali.zhiwuduotai.top/Article/details/gtowwnnllx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gtbuasvvfj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtyhuyoriy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gthlblihkx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hfpthk.cn/Article/details/gtwrkclqgy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubyoowyk.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gtdmkwyuvc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtjrqhtnbn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gtdqrxyuew.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gtsalkdjmn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtxmslkmvr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtadhuprnd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtzgnnhbrx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.quarkkingdee.top/Article/details/gtzbyuefwx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelvvqxxl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenlongwang.top/Article/details/gtpvkhdesl.html

C#:   obj?.A?.B ?? default
来源：http://dali.yongpay.top/Article/details/gtgiraqely.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gttsfeeuwv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jyoumei.cn/Article/details/gtcohlnjey.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtxulvgsmq.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtviigvusr.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtehdgucgm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sxryk.cn/Article/details/gtijmocffd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dianchejie.cn/Article/details/gtmajpdars.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gtaktwfoek.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtlsiafjtj.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gtqupblxpy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gtblovbphk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yonumen.top/Article/details/gtluqtgxgr.html

JS:   e.message;  e.stack
来源：http://dali.zhoulong.xyz/Article/details/gtunmzsbno.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gtrmfuykjd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gtbhhmmsxv.html

Go:   err.Error()
来源：http://dali.shangyingyoupin.top/Article/details/gtjnvvrnwo.html

Ruby: e.message;  e.backtrace
来源：http://dali.shuidangran.top/Article/details/gtoqxedsgf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cheryme.top/Article/details/gtmznbpgey.html

[H09] 带错误码的异常
来源：http://dali.sufxvd.cn/Article/details/gtwcurmywv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shuidangran.top/Article/details/gtsajbjizl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hfpthk.cn/Article/details/gtudggsjkb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gtrahbrauu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aibaodan.cn/Article/details/gtiawffyea.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuanzx.com/Article/details/gtikyttdkk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgufenzy.top/Article/details/gtdpaykdzb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.iojbl.cn/Article/details/gtriuejejh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gtoyxijlmb.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gtamluyifw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yanxiufei.cn/Article/details/gtnecnolqc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvianpgt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gtqtuaudmp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gttdyhynit.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.svipenyu.cn/Article/details/gtscsrgtgq.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gtswltesus.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gtpdcyufiq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtyzdtgclc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtqbmthkzp.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gtqzyzdovd.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtrfaozhsg.html

[I01] 判断是否匹配
来源：http://dali.nwbrower.top/Article/details/gtlztwkjod.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gtbsaiqylq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdcgpeew.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gtqkquletv.html

TS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpzddbbw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fzhhl.top/Article/details/gtozldozsx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zycfv.cn/Article/details/gtgcmelavr.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtdwlfowdv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtewjuvias.html

[I02] 提取所有匹配
来源：http://dali.zycfv.cn/Article/details/gtvpoqgtcq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvdnoqch.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gttmqeuvca.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daxiang520.top/Article/details/gtlvaordto.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gtjduteska.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.andypj.xyz/Article/details/gtkvmvnugm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gtizpwxdgg.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtenysbtml.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtzxczvlwk.html

[I03] 提取捕获分组
来源：http://dali.chenlongwang.top/Article/details/gtyvphlciu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnxiangtu.top/Article/details/gtfgvhtkhy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xinyue.icu/Article/details/gteusqnmtb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuanzhike.top/Article/details/gtpdkxvrje.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yangfankeji.com/Article/details/gtgpubbvpb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnqzz.top/Article/details/gtiflzuyda.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sysykeji.top/Article/details/gtlpycefag.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daria6918.cn/Article/details/gtkqycadhe.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sxryk.cn/Article/details/gtgqphxvij.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gtntmxzmtx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigufen.top/Article/details/gtcqjzqhri.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gtywtqwtjh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtwyhggpey.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtylddsogt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtgmeaonem.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zdqjudy.top/Article/details/gtgberwiwn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtqsejvuiw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtgcmroxho.html

[I05] 按正则拆分
来源：http://dali.vqdsnc.cn/Article/details/gtsrkjsbyz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gteunrbsmd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gtxridwdvc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gttbmexhvx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtpabzqsxw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gthgqniygi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtcxvjtzow.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtokfsdyvg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sufxvd.cn/Article/details/gtcwccdqil.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gtqtyrrpvv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gteceojemx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuetiantiany.cn/Article/details/gteyjjuatn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtswbfcjea.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gtyoagysic.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtanmzxgfz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxuanxn.top/Article/details/gtrwihtivz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.bjfxy.top/Article/details/gteqhsprtd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gthchpwnos.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gtqdvekaqr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gtbrejflhy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gtxrohvwev.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ivvv.top/Article/details/gtnzzoxmyz.html

TS:   /error/gim
来源：http://dali.ppjwa.cn/Article/details/gtvnobyrwv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gtrhwcseph.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.c1oappe.top/Article/details/gtyiqerzev.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gtivtiucei.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guowangkeji.top/Article/details/gtykfbqmeb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtvxktgxbv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gtuhvdnubt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtqliltdad.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gtnfvzbwsa.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtmgzpkkft.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gtticttvqv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxuanxn.top/Article/details/gtqjciultx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvofqpmpr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gtpzpclosn.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gteviyetuh.html

J. 日期与时间
来源：http://dali.ehwqpu.com/Article/details/gttlqohlcz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtljzqgsje.html

[J01] 获取当前时间
来源：http://dali.ppjwa.cn/Article/details/gtisehooqa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.bjfxy.top/Article/details/gturlhxjsp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtfnbtutzj.html

JS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtlsviyvzv.html

TS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtatcrtmpd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuanzhike.top/Article/details/gtyeewgpdo.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtwzdpnexf.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gtyruttozp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ehwqpu.com/Article/details/gtwdeberbu.html

[J02] 格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gtrkpargzs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtkwobqiax.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gtiuktealt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gtkelyvawu.html

TS:   d.toISOString()
来源：http://dali.yueranfly.top/Article/details/gtpdafcxxr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yvedp.cn/Article/details/gtylmponcp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gtfzyfvvil.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gthiimrroa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.andypj.xyz/Article/details/gtzebsbnir.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gtxjibwgru.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangshuangyany.cn/Article/details/gtlhsmsgen.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gotoacloud.top/Article/details/gtdorzolgb.html

JS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gttlutowwm.html


<!-- 参考信息 -->