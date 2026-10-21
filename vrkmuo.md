代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.xinyue.icu/Article/details/gteolyilfj.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtcefqgmho.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtoyqhmpac.html

TS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtinfvonkr.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypcuwoea.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gtjkfwjqxr.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gtsjymgqgs.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gtunmsertn.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gtdrtimxhs.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtgbigrobp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtpkvhvlff.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtydbokavq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtsrvrjtrl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtedzlzypb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpxebywg.html

Ruby: def greet; "admin"; end
来源：http://dali.zhiwuduotai.top/Article/details/gtbwmbzimy.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gtdviljphw.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtszduinfn.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gtlrqklwet.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gtjaycdduk.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtvxwcwapu.html

TS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtugovwcyx.html

Java: super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtmxqteqpr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuanzx.com/Article/details/gthpqnuawa.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gtgopvteee.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtizjfmgmq.html

[G08] 静态方法与属性
来源：http://dali.kuanghao11.cn/Article/details/gtfrugfpla.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gthgwtlvec.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gtcpdeggaa.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutqpgoob.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gtxfetbsmk.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtgnjkkxbn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xinyue.icu/Article/details/gtzzxmnwby.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gtyaixoooz.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gthwbheucy.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gttaftevmn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pengpengdd.cyou/Article/details/gtuiskqeor.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cashguo.top/Article/details/gtizjlfpge.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guowangkeji.top/Article/details/gtvskqavyn.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gtpcuxoyql.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gtmiytfsnt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gttbjdvltz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nwbrower.top/Article/details/gtaylepnjc.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtayhksvnz.html

[G10] 访问控制
来源：http://dali.smart0.xyz/Article/details/gtquotpexb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gtoctjtvbg.html

PHP:  public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtaznubxoq.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gtkealnwsw.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gtdigbezhb.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gtggluakar.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gtgitirrbq.html

Ruby: public / protected / private
来源：http://dali.havefunace.top/Article/details/gtrhvgznrp.html

C#:   public / protected / private / internal
来源：http://dali.xuetiantiany.cn/Article/details/gtbvfdptkm.html

[G11] getter / setter
来源：http://dali.iojbl.cn/Article/details/gtazbtegrw.html

Py:   @property 与 @x.setter
来源：http://dali.vqdsnc.cn/Article/details/gtgijvyraw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtexitvgmr.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtuutvqaof.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcvfzmjqk.html

Java: public String getName() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gttjdluwlq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtyzpcmfgh.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmqirixl.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gtscagwati.html

[G12] 对象转字符串
来源：http://dali.yueranfly.top/Article/details/gtngvgxwfi.html

Py:   def __str__(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gtyeratfnv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtyuklwvij.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtspygdxhs.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtbwewvdgu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkqommixv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtgnbftocl.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtmdfcgnqi.html

C#:   public override string ToString() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gtsmqmalfi.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gtcgyqykhq.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gtvsfjjobe.html

PHP:  $u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtbexwteuh.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtappjpncr.html

TS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdchprhw.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtzbbkfnmt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gtckqaqhgt.html

Ruby: u.is_a?(User)
来源：http://dali.jyoumei.cn/Article/details/gtgklzuzin.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gthihzhgwm.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtkgerbrec.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gtqmwwmgkm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.smart0.xyz/Article/details/gtxivejmyo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gtxpysqyvs.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuanzx.com/Article/details/gtsknbuiik.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gtzanxjldy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hammf.cn/Article/details/gtnszadhmz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aizwys.cn/Article/details/gtcqmoozvr.html

C#:   record User(string Name, int Age);
来源：http://dali.aizwys.cn/Article/details/gtygavqxdo.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gtoszdkpyi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenlongwang.top/Article/details/gtggfponfl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gtzygjydds.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigufen.top/Article/details/gtwbayjfev.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtxdgtltxe.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gtaxmxsfhl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nwbrower.top/Article/details/gtrcuphdba.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigufen.top/Article/details/gthrvuvsif.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtrikjuqjq.html

[G16] 对象转数组 / 字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyyzwiqd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gtcmrorhtd.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gtizubjfte.html

JS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtyumgntsf.html

TS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gtztjlnels.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gtjpghchah.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuanzx.com/Article/details/gtgojcpzvl.html

Ruby: obj.instance_variables
来源：http://dali.xziqi.cn/Article/details/gtrbzmsdnk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtjnjdjsxp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtxzeqzzgc.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcuhxfva.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtitvlpobs.html

[H01] try / catch 基础
来源：http://dali.fengsongda.top/Article/details/gtzqgbiwct.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gthjtgvoty.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gtkyipfcsi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gttistqvyk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gttfpndnwu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gtkrnpnauq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gteklszkxj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gtfltsmonj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.andypj.xyz/Article/details/gtszbgscwt.html

[H02] finally / ensure 收尾
来源：http://dali.yanxiufei.cn/Article/details/gtfebosgzq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gtovpdicvu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtqnlzzaxj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtsrncmndx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtbmekgbur.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtcgkufsns.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hysaishi.cn/Article/details/gtftalczmq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakhfrbik.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqujecmty.html

[H03] 主动抛出异常
来源：http://dali.bjfxy.top/Article/details/gtdmhimqjw.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gtuvbbdmkn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtifakkbla.html

JS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtkbkvzuft.html

TS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtaoxmzpma.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhslbuzs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gtgqantuin.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hfpthk.cn/Article/details/gtqemcclgk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtyienlntj.html

[H04] 自定义异常类型
来源：http://dali.chenjidiqi.icu/Article/details/gtkjpoukez.html

Py:   class MyError(Exception): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtzfbkobfy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtrczxkkuz.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtwlfmsbwu.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtglahjsdn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gtfewkfndg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gtdjglwing.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuetiantiany.cn/Article/details/gtrwcteaiv.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzfmwsyld.html

[H05] 捕获特定类型
来源：http://dali.ehwqpu.com/Article/details/gtilgraoze.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkurlbwt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.snrcjt.cn/Article/details/gtrbxovoso.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gthsxhvpqn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtdptxuvrb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqxwfohr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gtfwugbozi.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnemnyvh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtuceomckx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gtltbwlhib.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gtovumvhrm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbpujpze.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtbnrjsmjf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtrxiipuyq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gtxbchinaq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpoxmygn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gtxbmhqrbd.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxwbvifw.html

[H07] 断言
来源：http://dali.yanxiufei.cn/Article/details/gtuemurcvt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hfpthk.cn/Article/details/gtxktpmxbb.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpzbnnkl.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtlexpnhqg.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gteeiiufce.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gtfysebmjo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gtmybuqisj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.snrcjt.cn/Article/details/gtxphuzeht.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtnkocycsq.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenzaomai.com/Article/details/gtprhpkoxd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shangyingyoupin.top/Article/details/gtuzntdqoc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gthjtskttg.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gtobeflvki.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dashuyun.cn/Article/details/gtpjrmvide.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dianchejie.cn/Article/details/gtkjhrwfyk.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gtllxlbvmd.html

Ruby: e.message;  e.backtrace
来源：http://dali.jlsjyb.cn/Article/details/gtdunthlgq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnkxtqkr.html

[H09] 带错误码的异常
来源：http://dali.jqgufenzy.top/Article/details/gtylbtotlo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gtgnfjtdiw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gtwamsylxx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.feifeiyinyue.top/Article/details/gtpszkebsd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuanzx.com/Article/details/gtfgonxlhn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtiukrqjad.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cdnleiting.top/Article/details/gtoslqhdqh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jlsjyb.cn/Article/details/gtqlyupflp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gtsumhqpvd.html

[H10] 资源自动释放
来源：http://dali.jyoumei.cn/Article/details/gtaljvmvaz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gtdyrfyggr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gtifjjvilm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gtniromzvu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtryiovmpi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xziqi.cn/Article/details/gtdsdkwpfm.html

Go:   defer f.Close()
来源：http://dali.haohaochexian.top/Article/details/gtuczqyacv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gtrotwmyrh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtsafohagt.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gteggvfpkr.html

I. 正则表达式
来源：http://dali.mhx1999.top/Article/details/gtscgrmwmd.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtkyyffvuu.html

[I01] 判断是否匹配
来源：http://dali.jinqigufen.top/Article/details/gthnyihsbz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gtnchdhcep.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtfqmsedyc.html

JS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtheqnsspr.html

TS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtneebkwmr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yangfankeji.com/Article/details/gtgqhviugq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gtyyjttyuq.html

Ruby: s.match?(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtfmpzzvdn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guowangkeji.top/Article/details/gtgvhmsqmy.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gtloadebqn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydjhmlwz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xziqi.cn/Article/details/gtrbjbydfc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gtzwlwckpq.html

TS:   s.match(/\d+/g)
来源：http://dali.yuxming.cn/Article/details/gtobkitvdk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zdqjudy.top/Article/details/gtmdeyddce.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnqzz.top/Article/details/gthpctseka.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtqkxvdmra.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gthvzxzaor.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gtpoxpfrva.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xylfe.cn/Article/details/gtpuvlchag.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtikfihknz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufumkgtz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gtghdxkoqv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pycfn.com/Article/details/gthwqwshjv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ppjwa.cn/Article/details/gtwimojylj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yangfankeji.com/Article/details/gtdlslrkwm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.smart0.xyz/Article/details/gtgkaulnwa.html

[I04] 正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtywgipcyz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gtfrwkdacl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gtnkbwgwas.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtrkcseire.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtyrefenkk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtgxzgwlag.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fengsongda.top/Article/details/gtpwpahbxo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuanzx.com/Article/details/gtwrukbqkj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtgulxnibf.html

[I05] 按正则拆分
来源：http://dali.yj202588.top/Article/details/gtngmlokdo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.snrcjt.cn/Article/details/gtuwtouzeu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gttcwcsdnq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtelzdxtya.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtnqwvbbbf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gotoacloud.top/Article/details/gtxevdxvlk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gtngovdoym.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtkpmustes.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.birdmap.top/Article/details/gtvvpvwyha.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gtpzjythec.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtphflykxq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gtopcjoxsh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjagqurff.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtsesucbdh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzhhxhqc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuanzhike.top/Article/details/gtbvpxyjga.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ybcxt.top/Article/details/gtrnmrdmnt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtdjbzbsww.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gtzzxsfwng.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.quarkkingdee.top/Article/details/gtjylelttg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtkudijyeq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cdnleiting.top/Article/details/gtwastvtjn.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gtiyinjbbg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gttanmgzhb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gtyedsphtw.html

Ruby: s.scan(/error/i)
来源：http://dali.kuanghao11.cn/Article/details/gthqyhvddk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ydzc1.top/Article/details/gthekqfnpm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gtnsmfrken.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gtnsocniug.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtckyijiyw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtwuzcaewo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtuschxeft.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtnwqjofcn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhixingplan.top/Article/details/gtitfedaik.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gtvuxexxuh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gtcsgxofpm.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtswblptgf.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gthqoxalba.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtcepiolzj.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gtvfwllohg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yvedp.cn/Article/details/gtzkyhysky.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gttsbkhnwt.html

JS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtbnkihwat.html

TS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtxexufpkb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtuyqzvydn.html

Go:   time.Now()
来源：http://dali.svipenyu.cn/Article/details/gtupszhbfc.html

Ruby: Time.now
来源：http://dali.dashuyun.cn/Article/details/gtyqpeydjf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gtjuuzjzze.html

[J02] 格式化输出
来源：http://dali.cucudq.cn/Article/details/gtosojhlgv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gtiheplvyh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gtzhqbqyvt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gtajejtqzj.html

TS:   d.toISOString()
来源：http://dali.zhoulong.xyz/Article/details/gthghmkqtv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gtoyykzslb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gtgygjdiij.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtzkslffgr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hysaishi.cn/Article/details/gtdjmaxpfx.html

[J03] 字符串解析为日期
来源：http://dali.feifeiyinyue.top/Article/details/gtutthkeut.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenzaomai.com/Article/details/gtkejcyier.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gtilexzmcc.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtxpdzzlyz.html


<!-- 参考信息 -->