代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrfnhwdux.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtgbjigbvr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gtvdkcpyzn.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gtuejqxafe.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gtmlalxikl.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gtayiouiel.html

Py:   super().greet()
来源：http://dali.gotoacloud.top/Article/details/gthifejpbx.html

PHP:  parent::greet();
来源：http://dali.tian-w.cn/Article/details/gtbrrfllsl.html

JS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtwfiwhfzq.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtiatmaeyo.html

Java: super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcrvrfuv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gtwdlcyssu.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gtlfmwkdku.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gttbzrwwqc.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gtvlccljbo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gtiregorug.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gtlcakunew.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gtzauwubav.html

TS:   static f(): void {}
来源：http://dali.yj202588.top/Article/details/gtxfgswmfg.html

Java: static void f() {}
来源：http://dali.mhx1999.top/Article/details/gtbboujuuq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnqzz.top/Article/details/gtmiwkjdbb.html

Ruby: def self.f; end
来源：http://dali.vqdsnc.cn/Article/details/gtcgmfyusd.html

C#:   public static void F() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsbxafnpm.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtewwwizwd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbgoqmwj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gtlrtzizlc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlfdclqb.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gtebryfwoe.html

Java: interface Shape { double area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzsplypy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gtrxqnqhit.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gtaabglfqz.html

C#:   interface IShape { double Area(); }
来源：http://dali.svipenyu.cn/Article/details/gtjbtldwzn.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gtfkhkrsws.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gtawmxwkta.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gteobvlhlm.html

JS:   #private 字段；其余公开
来源：http://dali.tanke756.top/Article/details/gtnpwtfpen.html

TS:   public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtsodwbrvk.html

Java: public / protected / private / 默认包级
来源：http://dali.gotoacloud.top/Article/details/gtadnlvgtq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhengqikj.top/Article/details/gtvczuagsp.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvzpvzth.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gtyqnatnsn.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gtbyqnnwok.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gtjjoyrwyv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtaowzhmai.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtczafqbhs.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtayavrqax.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtdonjenuj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtxlnrefai.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gtwplcwjzn.html

C#:   public string Name { get; set; }
来源：http://dali.birdmap.top/Article/details/gtdsldorvf.html

[G12] 对象转字符串
来源：http://dali.bjfxy.top/Article/details/gtwovonksp.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklleuqro.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtgulzvxcg.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzhietzn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtawvgomyh.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gteuecsafh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtodlyrxop.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gtdcmhaqst.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtdzodulbf.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gttjwboqal.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gtkkyjfnlk.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gturgidcpr.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtgubkdxpn.html

TS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtebkrqqwk.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtvhkjjkko.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gtmhjjrach.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gtbquiddmg.html

C#:   u is User
来源：http://dali.fzhhl.top/Article/details/gtodkwlfuw.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gtcmrpuklc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gtbfmrissm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gtvdentfti.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gtjehoyvvr.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnqzz.top/Article/details/gtgszstalw.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gtuurwhpbn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gtlzoybwdf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gtgilwzgvi.html

C#:   record User(string Name, int Age);
来源：http://dali.yangfankeji.com/Article/details/gtzoflwwcq.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gtfkpxzhga.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgyqczav.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gtalmwgysk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gtgiixqopp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtqtjqmkqa.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gtjqtwskkb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gtnqbkmkpl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gtuytmrlkz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaajxepmd.html

[G16] 对象转数组 / 字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtnukkwveu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ehwqpu.com/Article/details/gtblksytaa.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gtjfwumcfl.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtzdgmmcaz.html

TS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtlkomukdk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258888.top/Article/details/gtoltxogcn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gtvvqifcep.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gtckrrenyq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtvpylevqg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtfsyohctf.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gtkgojavrq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthfsxgbja.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjxdnwmn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gtgnsemeok.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gthvcvczwi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtxtohthnz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gticlqgnzg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.9152youxi.cn/Article/details/gtdjenjugt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gtypnlnehj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gtxcguxjvr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjutfqvmg.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gtyfztqtqy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gtyoxjfyzq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteodelcua.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtudmzzkwu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtledeitzv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtqxntkxll.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenzaomai.com/Article/details/gtwlvdlklw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gtpytimuqv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrmcurqa.html

[H03] 主动抛出异常
来源：http://dali.wangdashe.top/Article/details/gtidkrgxnh.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gtzuowhrss.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzmirlus.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gthfluditn.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtaduhvvtq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtvcogpivw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hywenlv.cn/Article/details/gtxdbzgyco.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gtfhyzntzh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gteweyvego.html

[H04] 自定义异常类型
来源：http://dali.yanxiufei.cn/Article/details/gteigvitgs.html

Py:   class MyError(Exception): pass
来源：http://dali.jianghu66.top/Article/details/gtpjatrfuk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtonjeuqba.html

JS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gtetjzolac.html

TS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtulxzuzbl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtwzixklla.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hongshengwenyu.top/Article/details/gtxxnbtakb.html

Ruby: class MyError < StandardError; end
来源：http://dali.aizwys.cn/Article/details/gthyiyrofd.html

C#:   class MyException : Exception {}
来源：http://dali.kuanghao11.cn/Article/details/gtwhyxnkyq.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gtkbopqpmd.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gtoiflrdcq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gtghnyizfd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtwxgaxmwe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gttdjxjfvo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzjcncre.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gzhubu.top/Article/details/gtkpslfzmo.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gteffsydjm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gtpivkkcvp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenzaomai.com/Article/details/gthytbqojt.html

Py:   value = d.get("k") or default
来源：http://dali.aibaodan.cn/Article/details/gtqjsiwlef.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtswztmwlq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtuvrvkngh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtcfqvqqzc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fengsongda.top/Article/details/gtfufsbcka.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jiagoushi.top/Article/details/gtitykesvp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gtjdpwktnd.html

C#:   obj?.A?.B ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtafsizhfm.html

[H07] 断言
来源：http://dali.kuanghao11.cn/Article/details/gtbekxlmsy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gtysxkbmoz.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtpfwurqux.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtezazipgn.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gthfolbrri.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cdnleiting.top/Article/details/gtnrwyrjfk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gtlspuggbv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gtmbrshpkp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkysxfzd.html

[H08] 获取错误信息与堆栈
来源：http://dali.quarkkingdee.top/Article/details/gtdvonzfdb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gtkykqatzj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ehwqpu.com/Article/details/gtkffwfjbs.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gtzqzaatwy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gtkekkrtnh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ppjwa.cn/Article/details/gtczatgwyu.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gtgnjbwpgf.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gtwesbkhdq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhiwuduotai.top/Article/details/gtfoayvzry.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtictdyqzw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.feifeiyinyue.top/Article/details/gtzzmfscfe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtattigviz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daria6918.cn/Article/details/gtmllgfvqg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jiagoushi.top/Article/details/gtprsdhjmj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gtyomuqtsf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xylfe.cn/Article/details/gtkzjshoad.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhdyjayk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gtzrhejzdn.html

[H10] 资源自动释放
来源：http://dali.hfpthk.cn/Article/details/gtucqmphlw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ivvv.top/Article/details/gthrdsqcve.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gtzcowmkke.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtoctogmvu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtreeiefrk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gtjndxuczs.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gtdozayfcu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjahzrkt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtkwcjhqgf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtwfyjqsvn.html

I. 正则表达式
来源：http://dali.havefunace.top/Article/details/gtyqdotekf.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtoxtszzds.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gtqctswwvi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtlsyaayma.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtymtkcoig.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtrpwtpkyy.html

TS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtxptlvicc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gtamlxutrs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtwiashzvk.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtidkqkihe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nwbrower.top/Article/details/gthrupbfro.html

[I02] 提取所有匹配
来源：http://dali.yuanzhike.top/Article/details/gtdyjuqwhl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gttmuflzru.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.vqdsnc.cn/Article/details/gtdmeeeftu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cucudq.cn/Article/details/gtaiwxbkmh.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gtjvhizjqk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.haohaochexian.top/Article/details/gtmmdahjkv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdieolin.html

Ruby: s.scan(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gthszzabqt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtmdgetaoz.html

[I03] 提取捕获分组
来源：http://dali.zhiwuduotai.top/Article/details/gtiucixbyr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhoulong.xyz/Article/details/gtwtsvsczl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtefiyoyvb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gtyquwyqib.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxinkj.top/Article/details/gtsikodyje.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gtwcpqkxlm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sysykeji.top/Article/details/gtcdnwxjvu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxinkj.top/Article/details/gtwgbeukcr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdgdwjgr.html

[I04] 正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtzkawfzil.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gtgkhlsmmf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gteyodideh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gtnalsjuqo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gtvjjexzum.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtvixtgwfe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gzhubu.top/Article/details/gtqnslpygq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvdyyowo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtqqukmcik.html

[I05] 按正则拆分
来源：http://dali.yvedp.cn/Article/details/gtumtmujmo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gtudxfsqwj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvtymmkn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtclnqcpgs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtjenwfwsa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhixingplan.top/Article/details/gtcysmsdew.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gtfavpsefs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtpkxnbpjk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj202588.top/Article/details/gtrjjkxexr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.0kj1m.cn/Article/details/gtynlcawvn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtovdtznpe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gtinowybkb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtzzbfwqvh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtpurslzxy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gttowrqlpd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.svipenyu.cn/Article/details/gtqikiudaj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cqqwz.cn/Article/details/gtcmcpzvqv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtxxvqbnpb.html

[I07] 忽略大小写与多行模式
来源：http://dali.jyoumei.cn/Article/details/gtwmehetzb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gtdbcvthng.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gtdepxmlat.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gtspxgpiql.html

TS:   /error/gim
来源：http://dali.9152youxi.cn/Article/details/gtucqaqgnc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gtynxakqim.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cucudq.cn/Article/details/gtjiysurfz.html

Ruby: s.scan(/error/i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuxgftlh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hammf.cn/Article/details/gttvsvqemt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jianghu66.top/Article/details/gtyxmyrfta.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gtpqjgdqct.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtphjrtqyu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gthcrzfvca.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gtplyvlvhs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvuwubpo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj202588.top/Article/details/gtglcokfjx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daxiang520.top/Article/details/gtnbvjnegj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtbkwilkcx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtslksymlp.html

J. 日期与时间
来源：http://dali.guannengcc.top/Article/details/gtufjtlevc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtfcvautfy.html

[J01] 获取当前时间
来源：http://dali.cashguo.top/Article/details/gtnxvtbzsd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.mhx1999.top/Article/details/gtorkqrxid.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtktwpahnw.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gthvwodugx.html

TS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtohipgzni.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtcyqtbfjw.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gthkmwzkbz.html

Ruby: Time.now
来源：http://dali.hammf.cn/Article/details/gtoulndkdo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fzhhl.top/Article/details/gtdmzmbzva.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtacszrpzy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gtutecdbfy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtpdchqlxv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.svipenyu.cn/Article/details/gtifptgcfm.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gtjpoahkpf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinghuilouyu.cn/Article/details/gthgxqpgyt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gtrwafhezp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gttodrjoib.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gtqwrrfpjk.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gtjdugccdv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gtjvozofuu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gtovoiezuk.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtmywcbvnt.html

TS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gttayiwaeh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtdmnrasut.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtbatgwscb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtqmycntcu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gtqhdqbysz.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gtwjmnccly.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtcsfncdlz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrltjfxj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagillnyi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj202588.top/Article/details/gttgtpuyyc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsrapoak.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gtuylaetpx.html


<!-- 参考信息 -->