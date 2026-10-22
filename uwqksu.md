代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.ivvv.top/Article/details/gtvfrvaadj.html

PHP:  class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtimfkurld.html

JS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtasdtslek.html

TS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbgchedj.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtdpoiurhs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gtiduefyiw.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtvjicwenr.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtyiwlfgge.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gtkegkgipo.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gtovqslbiw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtbbzbitim.html

JS:   greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtrazrvfpx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtvoadgitb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtukepmgeh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gtttbndhta.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gtazlmnnxx.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gtofvyrpba.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gtmloizcrv.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gthixniyqm.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gtyvynhumt.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtbpmmeylj.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtjfssmksb.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtvyxxiihd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gtsfrxbvtd.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtuokzenvz.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtfsffiuxp.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokigsnvs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtlwdbpsux.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gtimwzwqmg.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gtkrxqyifa.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gtblmzgjla.html

Java: static void f() {}
来源：http://dali.0kj1m.cn/Article/details/gtolklgetx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aibaodan.cn/Article/details/gthwcrbbag.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtrectqvlu.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gthanjrqfg.html

[G09] 接口 / 抽象类
来源：http://dali.aizwys.cn/Article/details/gttxcvosbl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gtfnuymghh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gtenkzomgx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gtwglilezw.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gtelpalabt.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gtvtqrqczz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gtyibohdvr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gtncyavajx.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gthxlazoqq.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gtjkmizszk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gtzudhmnaa.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtnqhvtmsm.html

JS:   #private 字段；其余公开
来源：http://dali.snrcjt.cn/Article/details/gtibeskpyk.html

TS:   public / protected / private
来源：http://dali.meibo888.top/Article/details/gtmyliyume.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gtxwccmwbg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gtqlyjdcff.html

Ruby: public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtjkeaxiyv.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gtexaregqe.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gtmmteqybm.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gtwndxteig.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtytygjphs.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtwhrkrnwf.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtybfqwouh.html

Java: public String getName() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvpnrdnro.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtemvhqyaw.html

Ruby: attr_accessor :name
来源：http://dali.pengpengdd.cyou/Article/details/gtwpejvjhm.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtoypmkgbb.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gtxgyygjhq.html

Py:   def __str__(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtyxwdxfxt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtwfkjytlp.html

JS:   toString() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtmjcdmqcl.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzrweyjl.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtgydndwqn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtdoojoisl.html

Ruby: def to_s; @name; end
来源：http://dali.zhixingplan.top/Article/details/gtnopomzvh.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gteldffgnz.html

[G13] 判断对象类型
来源：http://dali.smart0.xyz/Article/details/gtgwpdqibb.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gteejuyxzy.html

PHP:  $u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtudyaasxe.html

JS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtierlqrng.html

TS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgmycrkb.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtxnnldrrg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskcawjrv.html

Ruby: u.is_a?(User)
来源：http://dali.nanxuanxn.top/Article/details/gtbeawewzb.html

C#:   u is User
来源：http://dali.chenzaomai.com/Article/details/gtpvhzzbjj.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gtgdblpftr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gtwghgijkh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gtnqaoluqg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cqqwz.cn/Article/details/gtmcbvozwe.html

TS:   type User = { name: string; age: number };
来源：http://dali.aibaodan.cn/Article/details/gtunkdplwd.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gtkkivbdeq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gtzuwhngnx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.bjfxy.top/Article/details/gtcheafncj.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gtmtogjlkp.html

[G15] 枚举
来源：http://dali.iojbl.cn/Article/details/gtkukazein.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gtshhcgrvn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gtepaafgsh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnqzz.top/Article/details/gtgrrhlzcz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtkohvgwsq.html

Java: enum Color { RED, GREEN }
来源：http://dali.bjfxy.top/Article/details/gtoizvkgay.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnqzz.top/Article/details/gtpaenwsqk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gtkfpvwbrc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gtdfuaszmw.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtnkzqsmvo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gtcbamiqrv.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gtghwieiqy.html

JS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtrkxffhoj.html

TS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gtjrfdxlnu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gthyojaovv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gtvrprvsup.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gtscssfoiw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlkijxuh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfrfyumve.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gtjkzuigrf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiehksdsx.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gtqaittvzi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yanxiufei.cn/Article/details/gtnsydbveb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aizwys.cn/Article/details/gtpmhqmaiu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtgzyscfyz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtthswmvtf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gtmjelzbfu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigfzy.top/Article/details/gtzknqowkq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guowangkeji.top/Article/details/gthekfqbew.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gtywqnlfwd.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gtdxpnxsqf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gtnsyfdwiu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtioxvjgeh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtxfnjperu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtslqlfzdm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtzltxbrap.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gtrnkdunzt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fzhhl.top/Article/details/gtenkmacto.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtgfgcdlnp.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gtdgzpnxaz.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gtcfcxaejj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtowuumtbb.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtuhzfsjgl.html

TS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtrgkfzbsz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtxrenkztf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gtbwalbjoi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gtelantmsa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtucuekqft.html

[H04] 自定义异常类型
来源：http://dali.gotoacloud.top/Article/details/gtkriohbko.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gtytluzevr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gthbsexmqf.html

JS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gttykmnkhx.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtqnpskfxb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjgputbhl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hfpthk.cn/Article/details/gtcaourlcd.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwhlsokg.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gttnugblow.html

[H05] 捕获特定类型
来源：http://dali.shangyingyoupin.top/Article/details/gteyygcfeb.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gtccfkvhiz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmmkcnpr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtkxalugle.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gtmnjbrjtb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gthryrvirl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gtownnjsvs.html

Ruby: rescue ArgumentError => e
来源：http://dali.hysaishi.cn/Article/details/gtxtmaddou.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtopwimimv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gtjecgsdjn.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqfffacx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gthcscxthi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtrvsilshi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtwbvtpora.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gotoacloud.top/Article/details/gtlhkqonaw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigufen.top/Article/details/gtuxqlqezk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gtqritwxnj.html

C#:   obj?.A?.B ?? default
来源：http://dali.cucudq.cn/Article/details/gtnogfnttd.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gtfbtukvzf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cdnleiting.top/Article/details/gttnuwqxie.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtvuosyrse.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtvkrlvpsl.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtjqokaxjd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangdashe.top/Article/details/gtzgewduth.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cdnleiting.top/Article/details/gtvmriwpul.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gtptjuhppm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtyyapzvdd.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gtbelahkjr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gtvhrljcyl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gtqekeicbe.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gtlvsnwfow.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gtonctiucs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenzaomai.com/Article/details/gtqidnofcu.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gtumcekpjw.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtpeupznev.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fzhhl.top/Article/details/gtamemykhq.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gtmkihtgss.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.havefunace.top/Article/details/gtrpfezrxs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gtmhncjwva.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gtbccyvgrs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gtkytqxkmq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gtqivmkefv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujzjfxxz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gtfvnqxfzg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gthnrglyzm.html

[H10] 资源自动释放
来源：http://dali.quarkkingdee.top/Article/details/gtumjobwie.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gtnxvpzyju.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gtmfhonchr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gtbzpxammm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtqbsdtkxz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shzxlz.cn/Article/details/gtajdtctbc.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gtqiwagvvz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrhyuqsh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gthurpxadd.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtowyuvfpq.html

I. 正则表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkhjuilx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtffozbgcr.html

[I01] 判断是否匹配
来源：http://dali.0kj1m.cn/Article/details/gtxoodlyag.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtkrdwbkzk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtqjedzpxq.html

JS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtxpvpllma.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtvabuexqa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gtakhcukzw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gtpldvoinc.html

Ruby: s.match?(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtwtvmueay.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtjrvwqvif.html

[I02] 提取所有匹配
来源：http://dali.shuidangran.top/Article/details/gtylyljuwe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxawvfodc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuanzx.com/Article/details/gtgubvhsuq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cashguo.top/Article/details/gtzhgqahva.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gtqvwfunlt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gtuffisyna.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tian-w.cn/Article/details/gtvuigqttr.html

Ruby: s.scan(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtpfyvtnnu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtushdjejw.html

[I03] 提取捕获分组
来源：http://dali.tianlin.xyz/Article/details/gtbcomtvxn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pycfn.com/Article/details/gtfnvjnxzd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fengsongda.top/Article/details/gtjuzgaqqc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xziqi.cn/Article/details/gtrifdchxs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhoulong.xyz/Article/details/gtmqdhlqkm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xinyue.icu/Article/details/gtsxopyivs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gtheqqqyiy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dashuyun.cn/Article/details/gtrwmnynzd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shzxlz.cn/Article/details/gtislmdzbj.html

[I04] 正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtoiaiuyhe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnxiangtu.top/Article/details/gtikfjmqcu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aibaodan.cn/Article/details/gtsmnbrhac.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gthdyxasyi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtplmjbwex.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtktdxwowj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtoqckcmvs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.havefunace.top/Article/details/gtlshtgavh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtmjuvrnde.html

[I05] 按正则拆分
来源：http://dali.ybcxt.top/Article/details/gtkckkxmon.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtbcrzoqkl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gteaqcrmml.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtyqdivggx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtjaudzcml.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cheryme.top/Article/details/gtathzxzck.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gttkqzxlws.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtdwgrbbzq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guannengcc.top/Article/details/gtgogrvgik.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tian-w.cn/Article/details/gtzvqzxwek.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtkxosyqmj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gtvlzmhuet.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gthuedtxoc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtvnvaiwou.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtldisacec.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgfzy.top/Article/details/gtcjwkcngw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guannengcc.top/Article/details/gtuwugunkq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gtltohyzsm.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gtiovlfdkt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cashguo.top/Article/details/gtaftbvpyk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtwolujcpn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gtvurfrxdj.html

TS:   /error/gim
来源：http://dali.dashuyun.cn/Article/details/gtcdcyredc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tian-w.cn/Article/details/gtqupienek.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gtdachgkhn.html

Ruby: s.scan(/error/i)
来源：http://dali.tian-w.cn/Article/details/gtolwruaqt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gtgaorjqhx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gzhubu.top/Article/details/gtnvtpbtrj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.9152youxi.cn/Article/details/gtpnlzgkvb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtflldzpba.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtxvcomqsh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtuakffdth.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gtfuqpyorp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gtmltoubjs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.bjfxy.top/Article/details/gtfwdvnghr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtgyholeip.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttwupsoyk.html

J. 日期与时间
来源：http://dali.cqqwz.cn/Article/details/gtulfcbfsn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtyqnwxwxx.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gtypfhswli.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gtlplficol.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtelanxmvz.html

JS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtjqwptzzk.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtxqutoiyj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yongpay.top/Article/details/gtyhjfakmz.html

Go:   time.Now()
来源：http://dali.sufxvd.cn/Article/details/gtpbhjlusr.html

Ruby: Time.now
来源：http://dali.dashuyun.cn/Article/details/gtsrpowmbe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gtizosmisx.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gttmltvwqg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtsokkqhjl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gtnxsaeszb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tianlin.xyz/Article/details/gtscmkeeri.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gtchndyhcn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pengpengdd.cyou/Article/details/gtsbaagvce.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehmlyyxl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtuobtjnnm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gtfmmvpsgn.html

[J03] 字符串解析为日期
来源：http://dali.sufxvd.cn/Article/details/gtusaysrcf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gtnpiahaft.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gtwzvnzceh.html

JS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtjjkonorq.html


<!-- 参考信息 -->