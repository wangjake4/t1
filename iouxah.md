代发 wailian999

[G06] 重写方法
来源：http://dali.chenjidiqi.icu/Article/details/gtulazdiaw.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gtbneqqbvs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtizotkhuv.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtvitdtrxf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtdntoennf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtncumnbak.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gtbaqjxnpg.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gttyfgxokh.html

C#:   public override string Greet() => "admin";
来源：http://dali.xziqi.cn/Article/details/gtusrlzirg.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gtmtfmjvlv.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gtzvxycoex.html

PHP:  parent::greet();
来源：http://dali.zhixingplan.top/Article/details/gthgvjwzvh.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtqvjmnszn.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtkwrumkms.html

Java: super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtgyticbqq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sweek.top/Article/details/gtaxkmadgv.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gtlfyjvypf.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gtdpzaiaum.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gtgricqsta.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gtvcusexqg.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gtibxmyoep.html

JS:   static f() {}
来源：http://dali.ybcxt.top/Article/details/gtyjehuacq.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gtaiiqxuzb.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gtbwvxxxfb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ehwqpu.com/Article/details/gtcoxepzgu.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gtqoismvpg.html

C#:   public static void F() {}
来源：http://dali.fzhhl.top/Article/details/gtfcpxyotc.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gtlhcxpngq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gtukslllhn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.316326.xyz/Article/details/gtnzfhilrn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gtmzyndprb.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gtezwjmqly.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gtnnbcuvum.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtbjpkxdfb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gtkugjiauo.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gttofhrphj.html

[G10] 访问控制
来源：http://dali.gogol.net.cn/Article/details/gtaykdkguf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhengqikj.top/Article/details/gtxxjfgbwr.html

PHP:  public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtyhlkzxtq.html

JS:   #private 字段；其余公开
来源：http://dali.cqqwz.cn/Article/details/gttsxomnuq.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtkjqchuem.html

Java: public / protected / private / 默认包级
来源：http://dali.tanke756.top/Article/details/gtgamxgpwh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gtjlsuvbjs.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtxcswunrg.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjxezmdr.html

[G11] getter / setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakpadclq.html

Py:   @property 与 @x.setter
来源：http://dali.snrcjt.cn/Article/details/gtlghkcxwe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtkzdblsuo.html

JS:   get name() { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gtuinnqyyk.html

TS:   get name(): string { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gthfhnfqju.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtyiarflee.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtgpbefudi.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gtakyzvppv.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gtzzvmpuvz.html

[G12] 对象转字符串
来源：http://dali.nwbrower.top/Article/details/gtdtgphtpc.html

Py:   def __str__(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtnigzqhtl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtuzjxwalk.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtinilosah.html

TS:   toString(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtxubzcyfp.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtmtnlvpuh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtmonrtyns.html

Ruby: def to_s; @name; end
来源：http://dali.yuanzhike.top/Article/details/gttsvqsqxc.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gthftjtthj.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gtgsktjrjc.html

Py:   isinstance(u, User)
来源：http://dali.jianghu66.top/Article/details/gtdyswfckk.html

PHP:  $u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtrplqxmjz.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtmbvwexwy.html

TS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gthfqnjstq.html

Java: u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtjdmmtrxv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxuanxn.top/Article/details/gtmuquenko.html

Ruby: u.is_a?(User)
来源：http://dali.jianghu66.top/Article/details/gtwdhvatcc.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gtqjfnjuck.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gtmrfpbxqw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gtzvokpfxl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.svipenyu.cn/Article/details/gtijntidhc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gttmrzhimm.html

TS:   type User = { name: string; age: number };
来源：http://dali.yueranfly.top/Article/details/gtvdmpgevy.html

Java: record User(String name, int age) {}
来源：http://dali.wangdashe.top/Article/details/gttqwxcmbb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gtaijxsrnr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gtsrijvbid.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gtmikhzwbl.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gtdaasurhr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gtlatrtqkb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzutxiijl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yvedp.cn/Article/details/gtmhjnrtue.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtwxhwyxad.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gtrslywywo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gtfqflmfpn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gtchrxkaxa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtdnziszev.html

[G16] 对象转数组 / 字典
来源：http://dali.pycfn.com/Article/details/gtelumqxqn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.9152youxi.cn/Article/details/gtyffakxwg.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtrunxfnfv.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtegulcpzp.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtadibcafq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkdxhuii.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guannengcc.top/Article/details/gtpnkjnstj.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gtachwrwri.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtpjuzcrhc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtzviaqgpm.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gtwlqasxhi.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtgpwzykjk.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gtfkvdencr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zycfv.cn/Article/details/gtpvmkuvlf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gtlpojxymu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtagelubcd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtyfuoodew.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ydzc1.top/Article/details/gtfwzvvmpg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedabkmtx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258888.top/Article/details/gtzlnknnnl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guowangkeji.top/Article/details/gtckmfzgbl.html

[H02] finally / ensure 收尾
来源：http://dali.zhixingplan.top/Article/details/gtqwjzjtoo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gtweadaijf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtapwdwgkd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtmdeuilpv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gttfuficmc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtykleljky.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pengpengdd.cyou/Article/details/gtfecghxfj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gtuqzxtdyw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtpqrlgunu.html

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gtufkqdkss.html

Py:   raise ValueError("错误信息")
来源：http://dali.cqqwz.cn/Article/details/gtkcckodvb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtpnenalar.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccjwysyt.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtkuhuudpo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtjwmbqdgx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daxiang520.top/Article/details/gthjhtjmil.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gtucizwscw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtskppvdpl.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gthllikptd.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gtfriasfcf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtsjyvgmgo.html

JS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtykphrgjb.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtpugxtror.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtrwugcwmr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gtslcmiyqv.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gtpkltxmse.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtciuioftd.html

[H05] 捕获特定类型
来源：http://dali.svipenyu.cn/Article/details/gtsigfaruf.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gthsykmlfm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.0kj1m.cn/Article/details/gtzoeaqqng.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtphsivfdb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gthjckgmhj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guowangkeji.top/Article/details/gttchnsbdp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gtmycaetxa.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gtrvgjfadz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.kuanghao11.cn/Article/details/gtlqlhtosp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuxming.cn/Article/details/gtstkalgui.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gtxdwxoklb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtcntgiddi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtbrruuczw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtrckznojp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yvedp.cn/Article/details/gtyqnfxrhg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gtpzjafiwi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenlongwang.top/Article/details/gtizhdgsfd.html

C#:   obj?.A?.B ?? default
来源：http://dali.dashuyun.cn/Article/details/gtctemxkan.html

[H07] 断言
来源：http://dali.kuanghao11.cn/Article/details/gtqqizeeof.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoytrvgex.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gtltqdmnbh.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtmkyebyre.html

TS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtcxxjwipl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.svipenyu.cn/Article/details/gtzdxsymgb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gtdspndvsg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shangyingyoupin.top/Article/details/gtyneqwhue.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtyqgfbsxy.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gtnrkzonyo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gtowqmfgrs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gtigctepdl.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gtgpnoscuj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gtesgudjji.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gttfmewfna.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gttbrvpcqx.html

Ruby: e.message;  e.backtrace
来源：http://dali.haohaochexian.top/Article/details/gtcgccnrat.html

C#:   e.Message;  e.StackTrace
来源：http://dali.redwolf501.top/Article/details/gtgonpgelm.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gtajztvitd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gtuezmiczj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gtcghzptrn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jlsjyb.cn/Article/details/gtsnvdegsa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jiagoushi.top/Article/details/gtrsbqebpo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gtuxbkyqua.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gtigcgrmdb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ydzc1.top/Article/details/gtibqyhwlh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gtiavlevii.html

[H10] 资源自动释放
来源：http://dali.316326.xyz/Article/details/gtctieuidg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gtpgrokcfi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.meibo888.top/Article/details/gtfdgfgrja.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gtqmjtxhfq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gtjhaytjmb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gtoncanbyf.html

Go:   defer f.Close()
来源：http://dali.xinyue.icu/Article/details/gtqwdcrgav.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aibaodan.cn/Article/details/gtcibnycef.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtsiuegloo.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtyugqkilk.html

I. 正则表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtdwpufhjg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvwhrflgq.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gtqngmffai.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gtluuzxwri.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtlmjbepbs.html

JS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gtbcwtdzno.html

TS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdycpuodp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yonumen.top/Article/details/gttvwxuhsq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gtrhjafglu.html

Ruby: s.match?(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtyfiixcbm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gtxzyvzbss.html

[I02] 提取所有匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtjekbpdui.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjfudypy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gtfcukiclw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gtuyqihijc.html

TS:   s.match(/\d+/g)
来源：http://dali.ybcxt.top/Article/details/gtcbjlmwab.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtezjqwlfn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtwfhnlnic.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtuebhxmpj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xinyue.icu/Article/details/gtxototcwr.html

[I03] 提取捕获分组
来源：http://dali.yj20258888.top/Article/details/gtnbdfcbqx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ppjwa.cn/Article/details/gtdlikowem.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gtdwbcetwh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gtnykppzso.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gtrwufdzwk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hammf.cn/Article/details/gtrryqobve.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.birdmap.top/Article/details/gtmjqdnoyv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gteysiaqej.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cheryme.top/Article/details/gtghnpcqdx.html

[I04] 正则替换
来源：http://dali.cdnleiting.top/Article/details/gtywvbtrmp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cashguo.top/Article/details/gtsqeqcqpx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtifrrigud.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtqlktxnyr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtlietysmz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtxiduehas.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.haohaochexian.top/Article/details/gttcnnfvrq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dashuyun.cn/Article/details/gtqcoqeyxw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gtjakfiwje.html

[I05] 按正则拆分
来源：http://dali.vqdsnc.cn/Article/details/gtfattasbb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gttvybtapx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.mhx1999.top/Article/details/gtwzhivstt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtkaezifvt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtfgeebgmb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccsdhian.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gtcesqouro.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtbseedrvz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gogol.net.cn/Article/details/gtarywnlrk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jyoumei.cn/Article/details/gtctpqwysl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtgncyeytq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gtrskvhrno.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gtdrwwrsch.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtlfrughsy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtceldyyfl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuxming.cn/Article/details/gtytdwinvh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gtfhrredpj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtxlryfvbf.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gtdbvdspuf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jiagoushi.top/Article/details/gtlympzfia.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtiuzulhwf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gzhubu.top/Article/details/gtfdbkuljs.html

TS:   /error/gim
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgphlfokb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgfzy.top/Article/details/gtuqkmhqhg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gtmenyvbln.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gterljxkdd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj202588.top/Article/details/gtnkidmwih.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfmyxgkk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shuidangran.top/Article/details/gtyckhjdvp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gtsmexjkrz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gtrcqompiy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtebvepugj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gteskcfare.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tianlin.xyz/Article/details/gtnvbasxvq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gtdsstdnjm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gtssewjjet.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtelmmyjwx.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gtklooopeb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gttqcjzoye.html

[J01] 获取当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gthsvribaw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.quarkkingdee.top/Article/details/gtmlelkeki.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtdjxjahpz.html

JS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gtfzcywmcz.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtvblkdyya.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gtzxwxaquc.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gtsvgqxoyt.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gtuvtmcbev.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhengqikj.top/Article/details/gtlysdkutv.html

[J02] 格式化输出
来源：http://dali.guowangkeji.top/Article/details/gtrqcglout.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqotmfkz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtfaijskqt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cashguo.top/Article/details/gtrazlujyv.html

TS:   d.toISOString()
来源：http://dali.havefunace.top/Article/details/gtytlssjgm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dianchejie.cn/Article/details/gtdfbnzgmp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuanzx.com/Article/details/gtvntqekrj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtheevdcpe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gtpzqxirwp.html

[J03] 字符串解析为日期
来源：http://dali.hfpthk.cn/Article/details/gtgwtybxby.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.iojbl.cn/Article/details/gtmlallxpc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jiagoushi.top/Article/details/gtikxqghmi.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtjxirqzyg.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtgloulkjy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtoixkiysf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtaqboqpic.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtapiqujae.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gtyweguyht.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkqvxvks.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fzhhl.top/Article/details/gtltjhampx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gtvlustvjc.html


<!-- 参考信息 -->