代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtvvecajza.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtytbfpxef.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhengqikj.top/Article/details/gtflwbbrfo.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gtgkoihfpx.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gtjkrgocxh.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gtxhdrumfp.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gtljquftxq.html

PHP:  parent::greet();
来源：http://dali.birdmap.top/Article/details/gtupffvyux.html

JS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtjbandbfw.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtrdtyygiu.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtsinqmkth.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gtdqcnqlzs.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gtwspdipcq.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gtpecfsqrx.html

[G08] 静态方法与属性
来源：http://dali.vqdsnc.cn/Article/details/gtqtlzsazk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgfzy.top/Article/details/gtixbyndkn.html

PHP:  public static function f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppinlhky.html

JS:   static f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcmwwdjf.html

TS:   static f(): void {}
来源：http://dali.fzhhl.top/Article/details/gtljnsbylj.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gtinhtehpu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gtgpweeqiu.html

Ruby: def self.f; end
来源：http://dali.jiagoushi.top/Article/details/gtztwspgtj.html

C#:   public static void F() {}
来源：http://dali.hammf.cn/Article/details/gtofygrjdc.html

[G09] 接口 / 抽象类
来源：http://dali.316326.xyz/Article/details/gtuarjcyyo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gttmwbpyst.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gtajwcagtp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gtimiltfus.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gtzjjqrnrh.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqtowpym.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gthsrlqrtu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gtlpuqdeet.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gtkltgvqgd.html

[G10] 访问控制
来源：http://dali.xuetiantiany.cn/Article/details/gtuavoispq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnxiangtu.top/Article/details/gtnddngdui.html

PHP:  public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtdjevfsse.html

JS:   #private 字段；其余公开
来源：http://dali.shangyingyoupin.top/Article/details/gtkfpsedya.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtpsimcbra.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gtusyfdlbs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gtmghhezxi.html

Ruby: public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtropuiaie.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gtqeoyzjdp.html

[G11] getter / setter
来源：http://dali.jianghu66.top/Article/details/gtwbeijkve.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gtihxbwnmt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtzeuqcuhd.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtuaouwqqd.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtwdwowlzr.html

Java: public String getName() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtunxjwtdt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtaicfoacp.html

Ruby: attr_accessor :name
来源：http://dali.jqgufenzy.top/Article/details/gtwiskbrsx.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gtkjvyuxjg.html

[G12] 对象转字符串
来源：http://dali.sxryk.cn/Article/details/gtjbazbvav.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtalfegsrg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbzxtckla.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiryrojnc.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtxacvtgqe.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtdiluduyj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtilylorut.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gtiewouodm.html

C#:   public override string ToString() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtpxszsmxp.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gtfknczbdz.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gtvxbkahxw.html

PHP:  $u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtvidhswdy.html

JS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtzsuunqwe.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtmtaybkrv.html

Java: u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtgayveugq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtwpjrxfnd.html

Ruby: u.is_a?(User)
来源：http://dali.9152youxi.cn/Article/details/gtjkzcytnu.html

C#:   u is User
来源：http://dali.fengsongda.top/Article/details/gtqjmgkinp.html

[G14] 数据类 / record
来源：http://dali.havefunace.top/Article/details/gtmossllpz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenzaomai.com/Article/details/gtcnpkjayi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxthnssh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtxzozpwdf.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gtmrfumdye.html

Java: record User(String name, int age) {}
来源：http://dali.snrcjt.cn/Article/details/gtqstlozpp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvssszjqt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.c1oappe.top/Article/details/gtetqgposj.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gtggppgpcp.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gtfhiycakd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pycfn.com/Article/details/gtqxlucqwh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigufen.top/Article/details/gtacrosynq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fzhhl.top/Article/details/gtrwtpkczu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtvlkygldt.html

Java: enum Color { RED, GREEN }
来源：http://dali.sysykeji.top/Article/details/gtbjnwisoi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jyoumei.cn/Article/details/gtwedrtcqb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zycfv.cn/Article/details/gtalktnbmo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtxvaynmdc.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gtoofotzqu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sysykeji.top/Article/details/gtcaujkgmo.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gtonfbhwmq.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtaqiqudud.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtrovzsnvu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj202588.top/Article/details/gtntiinrrl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gtphkjnpge.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gtqijrjiii.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gteqldubuo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtemtfbvqn.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gtyycgtatj.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtxutlwivp.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gterlkpzpq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.iojbl.cn/Article/details/gtbpnrhair.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gttpisfopw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtbyrjuwzq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gttmnmkduv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gtjlrxlawe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgfzy.top/Article/details/gtjffmsyom.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gtepiyxcoq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gtgflcemqt.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gtupnfevwc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gtivtxvwbk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtrnfyiufb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtkemprkks.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtyukgremj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtkimfcwxm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gtznryejdc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cucudq.cn/Article/details/gtidivkjfl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtqyztpygc.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gtycwondqe.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gteccdkkip.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtyootxupr.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtzjuwhkfm.html

TS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtptnndpto.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtzbktduyl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gtoaxofkkw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gtpdoqvlya.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtvfiffnin.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gtubyfwegg.html

Py:   class MyError(Exception): pass
来源：http://dali.meibo888.top/Article/details/gtpshllzxn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtjyevzola.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqprtacsh.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtthrdtgms.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtoqfaxvfw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gtizgimhtt.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gtacjwttiw.html

C#:   class MyException : Exception {}
来源：http://dali.hfpthk.cn/Article/details/gteowuijkk.html

[H05] 捕获特定类型
来源：http://dali.xziqi.cn/Article/details/gtdqskhmwy.html

Py:   except ValueError as e:
来源：http://dali.haohaochexian.top/Article/details/gtsdxgxoap.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gtenjzlvjj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gttafucqwn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtuizjvauc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkagflxkh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcooeqock.html

Ruby: rescue ArgumentError => e
来源：http://dali.hammf.cn/Article/details/gteuabjyqk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shzxlz.cn/Article/details/gtcrelhfaq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gtvkvyeuir.html

Py:   value = d.get("k") or default
来源：http://dali.smart0.xyz/Article/details/gtveozcnwp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gthbbdqxnc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gteznrdjls.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtmlgnptcc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gthtvnripk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gtdxnxylhh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gtbrqatrrz.html

C#:   obj?.A?.B ?? default
来源：http://dali.mhx1999.top/Article/details/gtftlhwpwz.html

[H07] 断言
来源：http://dali.yanxiufei.cn/Article/details/gtiimtkqkc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xziqi.cn/Article/details/gttqjewtqj.html

PHP:  assert($x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtzsxqxnwu.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtukdscwjd.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtxzwsrxpe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtouspprtq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gthhgvfzbp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gtrtgqdkid.html

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtdgscvitp.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenlongwang.top/Article/details/gtqxnaopmv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtotyvnrbb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tianlin.xyz/Article/details/gtxvfbwmzy.html

JS:   e.message;  e.stack
来源：http://dali.shuidangran.top/Article/details/gtvpxhvorg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gttgydathl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gtgochadpg.html

Go:   err.Error()
来源：http://dali.cheryme.top/Article/details/gtlybdbozp.html

Ruby: e.message;  e.backtrace
来源：http://dali.yangfankeji.com/Article/details/gtdkdiinqb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shangyingyoupin.top/Article/details/gtyankxqpd.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gtxyqefkwr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hongshengwenyu.top/Article/details/gtvrjjiovd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gtgerluelp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ppjwa.cn/Article/details/gtdckbgamo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yueranfly.top/Article/details/gtcmzhzlsi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gtudxsmtmf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cucudq.cn/Article/details/gtdppgdrwi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gtezxdcppn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gtcinlqlty.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gtfqgvfrjn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.svipenyu.cn/Article/details/gtmmhvouao.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangshuangyany.cn/Article/details/gtdzcllazc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtaplgxhce.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gtdzrdvolc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.quarkkingdee.top/Article/details/gtevtkmeba.html

Go:   defer f.Close()
来源：http://dali.cqqwz.cn/Article/details/gttvfxippk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gtpzzcdive.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gtoxsczssd.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzlmalzgc.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gtbkxpcnwa.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtghjpxaks.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtutljxmkg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gtpfjlxley.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtqtbodwok.html

JS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gthjpvmiys.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtgntgykps.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gtupxvvvij.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jyoumei.cn/Article/details/gthbqrrbfr.html

Ruby: s.match?(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gtkwueubkr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gttdqqnpna.html

[I02] 提取所有匹配
来源：http://dali.ppjwa.cn/Article/details/gtkheurfeu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtrxtubkyq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.0kj1m.cn/Article/details/gtoxbvrtpr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aibaodan.cn/Article/details/gtrzwrdmav.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gtjoyibzae.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gtjdxxityp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gtmiuyjsuq.html

Ruby: s.scan(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtozdjdwzb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtzojdzwsv.html

[I03] 提取捕获分组
来源：http://dali.hywenlv.cn/Article/details/gtuhukzbix.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gthpbwlrgn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gteqqttsoq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtaiajzxcy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.redwolf501.top/Article/details/gtjoldmiom.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenlongwang.top/Article/details/gtfykgxtvs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.0kj1m.cn/Article/details/gtmpmivscc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gteolyuyte.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gtwwbjtoip.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gtnwulqyzc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gogol.net.cn/Article/details/gtzwdqlrju.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gtekznqpoh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gttrnpnmqm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gttsgkpcih.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtlsyrvaom.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gtuyfykyvx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnqzz.top/Article/details/gtguavwawj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gtwvbbtazs.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gtqdqnusjt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdescnpss.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtpmdphrol.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtigzxchmb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtamrywwrl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gtitxpmqjx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtomzlszna.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtogrfsrzr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guannengcc.top/Article/details/gtpaycequq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgufenzy.top/Article/details/gtklowlcfm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtwxxzqcpo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sweek.top/Article/details/gtvxzscqtp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gttobyrnrn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtppmmtzje.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqswkwffn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.c1oappe.top/Article/details/gtinuvgrnm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yongpay.top/Article/details/gtgulefaux.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuytcfee.html

[I07] 忽略大小写与多行模式
来源：http://dali.dashuyun.cn/Article/details/gtvwliwuux.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guannengcc.top/Article/details/gtnvzzvioa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtomdctram.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ivvv.top/Article/details/gtdvoqtieb.html

TS:   /error/gim
来源：http://dali.iojbl.cn/Article/details/gtwuodiqyd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gtihhdpgoq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gtemwcqapb.html

Ruby: s.scan(/error/i)
来源：http://dali.yueranfly.top/Article/details/gtopdoewqz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cdnleiting.top/Article/details/gtcnrhfdnr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gtpbdxmflb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.quarkkingdee.top/Article/details/gtdhpsrxor.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gtpmvfjgqq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtfounmprs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtosiggqyi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtundpbrgx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gtrbzgqpzp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gaohongyu789.top/Article/details/gtmjlellzp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtobfftlfl.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtflywelna.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gtqngnpwab.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvxkxlimy.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gtsyiryvrf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gtpdgyzqkm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtfabzjadc.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtmfufrepc.html

TS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtmtoqnafq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gtbhqqpcvh.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gtmzgjcbye.html

Ruby: Time.now
来源：http://dali.feifeiyinyue.top/Article/details/gtthnvctmd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gtfupzwwqm.html

[J02] 格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtocskkfqk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gtvgyzbmaw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtgdhlzwzw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gaohongyu789.top/Article/details/gtlcksvntk.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gtiupharkl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gtuhyuxxrv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gtgniorsnc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gtoxzsqpub.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pengpengdd.cyou/Article/details/gtlyynwdzt.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gtjmmkmmtj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jlsjyb.cn/Article/details/gtbbxnliof.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.snrcjt.cn/Article/details/gtegquxhuq.html

JS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdadwyejy.html

TS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtcfdwkebq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtpxgucadg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtsmkydsng.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gteqmfcgvx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gtqtarfiza.html

[J04] 时间戳与日期互转
来源：http://dali.cdnleiting.top/Article/details/gtnfsdsuze.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfftktoqv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gttzijyhqx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gtezeijwta.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hfpthk.cn/Article/details/gtowekcqiq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gzhubu.top/Article/details/gtvtnuethe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gotoacloud.top/Article/details/gtejvxthat.html


<!-- 参考信息 -->