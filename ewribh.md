代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtybpfrzmk.html

JS:   greet() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gteplzlghe.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtdeudjafg.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtpauwendn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtlpeqwdzx.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gtororrgnm.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtawznknkg.html

[G05] 继承
来源：http://dali.mhx1999.top/Article/details/gtesbskcrl.html

Py:   class Admin(User): pass
来源：http://dali.jlsjyb.cn/Article/details/gtmnyaevra.html

PHP:  class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gttjqpkvyz.html

JS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijbcloao.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtwhntgcrz.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtztkeffzf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gtojbjkcxx.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gthrdebpxw.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gtremhethg.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gtytqaxiir.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gtpzvadcmi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtigcalojb.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtndwnyani.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpiucgkdg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcrvtdlse.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gthznpyfmc.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gtkxxmoydc.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gtilqbhvrm.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gtvaqlphch.html

Py:   super().greet()
来源：http://dali.hongshengwenyu.top/Article/details/gtwkpgzoun.html

PHP:  parent::greet();
来源：http://dali.daria6918.cn/Article/details/gtsinaeqkd.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtkffkzhfp.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtwibniukc.html

Java: super.greet();
来源：http://dali.316326.xyz/Article/details/gtxqgalzqa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gtnvkebnap.html

Ruby: super
来源：http://dali.gotoacloud.top/Article/details/gtoppczprj.html

C#:   base.Greet();
来源：http://dali.sufxvd.cn/Article/details/gtzkvqpglc.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gtruehnnmh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gtfjthlenm.html

PHP:  public static function f() {}
来源：http://dali.zhixingplan.top/Article/details/gtzndsiswx.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtcwipkmrs.html

TS:   static f(): void {}
来源：http://dali.zhixingplan.top/Article/details/gthaeirwgv.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gtibrpldth.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gtrlsdvyll.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gtjrzkipaf.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gtmjnasxag.html

[G09] 接口 / 抽象类
来源：http://dali.yvedp.cn/Article/details/gtnpurjoho.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gtaxdswluu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dashuyun.cn/Article/details/gtwgxzrevx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gtuxxvkcbk.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gtiogyqeux.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtmsijovxi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gtpvcoiiit.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.quarkkingdee.top/Article/details/gtldwogvlw.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gtmmmsxymz.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gttbbgsvbf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.smart0.xyz/Article/details/gtxioqxmdg.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtuebwqoxo.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtozrrbisi.html

TS:   public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtuyjnwjsn.html

Java: public / protected / private / 默认包级
来源：http://dali.pengpengdd.cyou/Article/details/gtyagnfpij.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenzaomai.com/Article/details/gtgfhdpjvn.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtgamqnixg.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gtidwaopuc.html

[G11] getter / setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwifsdaai.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gtfetkgyqt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gttsmyzkyj.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtfjiiraqq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtvwuiueuf.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gtbzihfdsz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtffvtzowj.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gtueidvhee.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtfbbcwxam.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gtcgdjtnth.html

Py:   def __str__(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtavjghjij.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtxwykrvhl.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnemohtr.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtsatdgiib.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnqdzvcv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtaukiifgb.html

Ruby: def to_s; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngtihwpf.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gtghtxryuz.html

[G13] 判断对象类型
来源：http://dali.hongshengwenyu.top/Article/details/gtcdqzwcoz.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gtvgxcygcm.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gthabisloq.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtyxpmixxh.html

TS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtxmitagnr.html

Java: u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtdnivsfcx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sysykeji.top/Article/details/gtxjisyssj.html

Ruby: u.is_a?(User)
来源：http://dali.chenlongwang.top/Article/details/gtkozqsghj.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtjepdazyk.html

[G14] 数据类 / record
来源：http://dali.pengpengdd.cyou/Article/details/gtwludcdrx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenzaomai.com/Article/details/gtwvqanozl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gthizadbby.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gtnzlnkwev.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gtjemerdpl.html

Java: record User(String name, int age) {}
来源：http://dali.c1oappe.top/Article/details/gtlfolynvf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gtgmdwehtr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgufenzy.top/Article/details/gtoebzatey.html

C#:   record User(string Name, int Age);
来源：http://dali.xuanzx.com/Article/details/gtzaikcvyk.html

[G15] 枚举
来源：http://dali.havefunace.top/Article/details/gttvgwzjwe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.havefunace.top/Article/details/gtnutslkkw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cucudq.cn/Article/details/gttfucaslh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gteskcsddz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtalacjssh.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtbaemjvui.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gthntscxyo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gtptfjdalw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtimpdnjql.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gtgztisofn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gtirdultfu.html

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gtpporoktl.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtrlqecaxv.html

TS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtskclfhfh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gtpeapeegc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gttuhznwkz.html

Ruby: obj.instance_variables
来源：http://dali.guowangkeji.top/Article/details/gtewzfftns.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtaalaarmy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtbvkctzow.html

H. 异常与错误处理
来源：http://dali.aizwys.cn/Article/details/gtvfzfgbgf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqwsqtju.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gttjvlitju.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gtnafsbndi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aizwys.cn/Article/details/gtcoekqabo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtjrbhhzti.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtdgdqigcg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tianlin.xyz/Article/details/gthxyvneoj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gtbpabcoux.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.feifeiyinyue.top/Article/details/gtahiuyjry.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gtikdifatc.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gtqdfbappx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gtfwdqrnze.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtbcnoemdb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtlpmcdhzc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtygodqgct.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtloyaqwlc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.meibo888.top/Article/details/gtbtnlbeah.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gtafljifcg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtuosqujbe.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gtxeygtyob.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gtzcqooies.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtcqxxhyzk.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtyesugqgs.html

TS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtwcsmpzli.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtihtthaqf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gtzggasjcs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gtnluwvkkb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscwmkenm.html

[H04] 自定义异常类型
来源：http://dali.cheryme.top/Article/details/gtrmsgbrdd.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gthimbcgal.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtelulfaca.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhhjorvt.html

TS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtxluwodeh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtwxyfwiom.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gtbqjzybzs.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaharexqs.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gtiwwqzwny.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gtbzbcodig.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gtbdbirzrj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxuanxn.top/Article/details/gtkvxqaarn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtdpvrqmaz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtogyxbino.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenzaomai.com/Article/details/gtzabxsasc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gtvnflysmy.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gtvefererq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.316326.xyz/Article/details/gtokkakgwm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yongpay.top/Article/details/gtrgilayct.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gtdozqctlq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gtxlrvgwxk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtyycsctzo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtzxzdhmmc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yueranfly.top/Article/details/gtwewjzxxb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yongpay.top/Article/details/gtawrjwfpk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.316326.xyz/Article/details/gtuwqddbpe.html

C#:   obj?.A?.B ?? default
来源：http://dali.sysykeji.top/Article/details/gtrxeybcml.html

[H07] 断言
来源：http://dali.jlsjyb.cn/Article/details/gtargermpe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gteekpuhgv.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtikkzvbia.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtqjgofznq.html

TS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtwxolcisg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gtwysaojfg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gtichckinv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dashuyun.cn/Article/details/gtsglfapwi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtpxhctkna.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gtjcggrint.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtbuoclyfe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yonumen.top/Article/details/gtdriyxyes.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gtanrqlbbt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gthjigcfuc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gtovzkrccy.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gtomcwdsof.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuxming.cn/Article/details/gtxausfvmh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cheryme.top/Article/details/gtuiogkytt.html

[H09] 带错误码的异常
来源：http://dali.vqdsnc.cn/Article/details/gtyuhcxvht.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj202588.top/Article/details/gteuiwqkds.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gtcmzdzylv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gtaujyypft.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgfzy.top/Article/details/gtdbsugnzx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gzhubu.top/Article/details/gtgbajymqc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gtzyzajcrm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gtnctegoya.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gtcpobfyrf.html

[H10] 资源自动释放
来源：http://dali.wangshuangyany.cn/Article/details/gtenggzwwd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gtnfgfuhca.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xziqi.cn/Article/details/gtibhadlyg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtcqsswgzb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gtphiciqwf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdxcsfrp.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gtsyttdbgk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhiwuduotai.top/Article/details/gtcfvjrzbn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtnngidcbq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtvkuxonfy.html

I. 正则表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrhvbyaz.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gttvirfxpi.html

[I01] 判断是否匹配
来源：http://dali.cqqwz.cn/Article/details/gtndsyshoe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtvrsfxzcy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yongpay.top/Article/details/gtxvycgmtc.html

JS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gtcvzilnjb.html

TS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtorsavbnk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gtkqyjuccf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gttxducbyl.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtqvyxxlhq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gtwszrdqvh.html

[I02] 提取所有匹配
来源：http://dali.ppjwa.cn/Article/details/gtrcjxfetx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gtytlmqoky.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gtwjftqeqf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tianlin.xyz/Article/details/gtbjkpugti.html

TS:   s.match(/\d+/g)
来源：http://dali.jiagoushi.top/Article/details/gtgzpjcmzs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cqqwz.cn/Article/details/gtdytlqoda.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtahsyohod.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtzdfoqdty.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtwidthlae.html

[I03] 提取捕获分组
来源：http://dali.redwolf501.top/Article/details/gtigxwlpqt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gtxtybwmtm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtdeesglrb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.smart0.xyz/Article/details/gtpqxhqtsb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.mhx1999.top/Article/details/gtgremairy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gtnuzdvjnv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtleztadhz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstvukers.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gtxoqeijvp.html

[I04] 正则替换
来源：http://dali.sysykeji.top/Article/details/gtihotjezf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cucudq.cn/Article/details/gtiwkcccmh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yonumen.top/Article/details/gtdogjkivw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gteeqxhkvg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtizmkgsdw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gtcomfcbka.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shzxlz.cn/Article/details/gtwpagzvwt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ehwqpu.com/Article/details/gtxbfzszcc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gtbvohmkrk.html

[I05] 按正则拆分
来源：http://dali.jqgfzy.top/Article/details/gtlnbkiqzr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sufxvd.cn/Article/details/gtcdijvsaw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gtjiicjchm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtkojgpdpr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtckhlnniu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ppjwa.cn/Article/details/gtzcogcdax.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.mhx1999.top/Article/details/gtqusucsvl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtrofhxcqp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gtynrliums.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangtech.top/Article/details/gtaaovelyb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtauqhnmjw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guowangkeji.top/Article/details/gtofjkkltg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtoyvumydz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gtipzxjfkv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtmzwopunp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xylfe.cn/Article/details/gtgvnhfrrf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gtnsvdaymz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbdrfxba.html

[I07] 忽略大小写与多行模式
来源：http://dali.ivvv.top/Article/details/gtqacoomce.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gtidiodkvv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gtfrztabhe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gtcnvhjckk.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gtdfgafftt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fzhhl.top/Article/details/gtrcbkpapq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cucudq.cn/Article/details/gtdxqfeyru.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gtochvvnaz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtrcrvbeaf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuxming.cn/Article/details/gthpyaueqo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gteavzpaum.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtihuyrgki.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtcmtkzurf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtwhgtjatg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gtuxmowycy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhixingplan.top/Article/details/gtnbrpphut.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shuidangran.top/Article/details/gtepnmhtok.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtihmpaqbs.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtdjwmnaqq.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gtinincbja.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmopajmby.html

[J01] 获取当前时间
来源：http://dali.yj20258.top/Article/details/gtetlijzgk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozmlfcfb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqdeexul.html

JS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gtsfbbfvqc.html

TS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gtrvckhdbz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.haohaochexian.top/Article/details/gtbtustuij.html

Go:   time.Now()
来源：http://dali.nwbrower.top/Article/details/gtpvftozsv.html

Ruby: Time.now
来源：http://dali.iojbl.cn/Article/details/gtmmmvcoav.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gtniazdtzt.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gtpsutrspi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtvzgdwmbs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gtrnffscci.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gtfmianfvn.html

TS:   d.toISOString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdexmfgz.html


<!-- 参考信息 -->