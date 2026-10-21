代发 wailian999

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gtpajvitcp.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gtswwnoyci.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtsdnlldgn.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtnwdlkitq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtkuobwrsv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdbwufsrg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yongpay.top/Article/details/gtpsneeezx.html

Ruby: def greet; "admin"; end
来源：http://dali.hnxiangtu.top/Article/details/gttyegnovy.html

C#:   public override string Greet() => "admin";
来源：http://dali.snrcjt.cn/Article/details/gtqnbnuhip.html

[G07] 调用父类方法
来源：http://dali.gzhubu.top/Article/details/gtnztixabe.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gtjftgpohy.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtdzqdpyao.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtdebesenk.html

TS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtggdxylfr.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gtysvhaycj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gtuncbdhbk.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gtwoihbvsi.html

C#:   base.Greet();
来源：http://dali.yuxming.cn/Article/details/gtxmnebnnx.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gtklgqjbui.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gttvdxypxd.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gtwwhfmpgr.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gtwhakqmbt.html

TS:   static f(): void {}
来源：http://dali.mhx1999.top/Article/details/gthdmfabut.html

Java: static void f() {}
来源：http://dali.yuanzhike.top/Article/details/gtgvvucojq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gtmqgfldac.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjcibkbt.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gtidfzxksw.html

[G09] 接口 / 抽象类
来源：http://dali.xinyue.icu/Article/details/gtkgosfguf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zycfv.cn/Article/details/gtxwetvspe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ydzc1.top/Article/details/gtciflcrxz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gtrduxxsxc.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzbkvpcsq.html

Java: interface Shape { double area(); }
来源：http://dali.gogol.net.cn/Article/details/gtnsaeryqk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258888.top/Article/details/gterkyzblf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gtfpaimwhq.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gtpvkahbpt.html

[G10] 访问控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagfjmhru.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gtzwkscuor.html

PHP:  public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtkljrmbeg.html

JS:   #private 字段；其余公开
来源：http://dali.havefunace.top/Article/details/gtukwooiwc.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtcsibxbzt.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gtlrvmekur.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gtkxwsyiui.html

Ruby: public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtykelqdqg.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gtbgpbrkoe.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gtdynjvorg.html

Py:   @property 与 @x.setter
来源：http://dali.aizwys.cn/Article/details/gtreejkfuz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtgxsphivf.html

JS:   get name() { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtguesavli.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtpxrcgdgz.html

Java: public String getName() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtyqznuztj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtruepgxdb.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gtsybeaggk.html

C#:   public string Name { get; set; }
来源：http://dali.yueranfly.top/Article/details/gttlxtotij.html

[G12] 对象转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghhawpzp.html

Py:   def __str__(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtqetzsugt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtsgwdwcpk.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtwbqqlygq.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtbrfqluql.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gteceosimv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteigfaycv.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gtarubxcza.html

C#:   public override string ToString() => Name;
来源：http://dali.yueranfly.top/Article/details/gtkdqhwuih.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gtwnkowikt.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gtjuqrewdr.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtazxeibpy.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtigfixmiy.html

TS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gttuenvjkq.html

Java: u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmxlhjvu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuanzhike.top/Article/details/gtjeqpwxez.html

Ruby: u.is_a?(User)
来源：http://dali.9152youxi.cn/Article/details/gttznadxok.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gtlgxjvkve.html

[G14] 数据类 / record
来源：http://dali.cdnleiting.top/Article/details/gtdquuejhb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gtteefcqbr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daxiang520.top/Article/details/gtzazmdvtl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aibaodan.cn/Article/details/gtbqfvfeby.html

TS:   type User = { name: string; age: number };
来源：http://dali.svipenyu.cn/Article/details/gtxpwahrdf.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtlkqlhtky.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yangfankeji.com/Article/details/gtdjejyjel.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gtwdmtnqyn.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgfzy.top/Article/details/gtnrlilpdf.html

[G15] 枚举
来源：http://dali.gaohongyu789.top/Article/details/gtmoufgsuw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gtjdzcmgdq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhongyouzk.top/Article/details/gtxmsimefi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gtpdlmprla.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtxlfatfix.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gtqsmdgoqs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.andypj.xyz/Article/details/gtsnioodtw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gteubebeev.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtaacnjtpg.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gtxrhfwvrh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gtoiddceyi.html

PHP:  get_object_vars($obj);
来源：http://dali.meibo888.top/Article/details/gtzecyytps.html

JS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gtxfnotxvp.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtegnnbxol.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gtittilewu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuetiantiany.cn/Article/details/gtkwmwmeuy.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gtixfpytmm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yonumen.top/Article/details/gtgzvvfvzp.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiulhevvy.html

H. 异常与错误处理
来源：http://dali.shuidangran.top/Article/details/gtyetuodgo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtuepiixfb.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gtusjjqdcn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenzaomai.com/Article/details/gttglsobcb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gtlenvjlbg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtvzzwelpm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtxfgjtmou.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gtttshfopc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gtogtxaeyh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gtfvzmjukv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gtgyepjtmw.html

[H02] finally / ensure 收尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizdeyhwp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gtmsrfwqjo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtejsxkl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljwfeeiz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtzfbxaoud.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtcewigwip.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gthlrhvtpz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gtevaxpujw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtwrdzahnf.html

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gterarsonf.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gtkceruwot.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtaprqwpcc.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtavqaiquw.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtkzimayzf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzldcaev.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigufen.top/Article/details/gtqjhpbwsa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fengsongda.top/Article/details/gtkolgbyzl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtwjgvraeo.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gtkkfbyftq.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gtdqeglwge.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtcwyebqvi.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtfcjidldk.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gthhfpbaki.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqziaujra.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gthzlomtqh.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gtusgunyow.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gtunpfcxvq.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gtmjexsner.html

Py:   except ValueError as e:
来源：http://dali.zdqjudy.top/Article/details/gtwwxljcrl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xziqi.cn/Article/details/gtfdtafuyi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtqbrewilt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtofskjiqp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cucudq.cn/Article/details/gtfjvnufcs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gtyehawiuk.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gtqqiypsjh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtykddadkj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gtnicrxauj.html

Py:   value = d.get("k") or default
来源：http://dali.jqgufenzy.top/Article/details/gtsgbezxoz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtzoruheot.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtvcpugkri.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtrfyokumd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtfwnidkrc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gtgtayhavx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ydzc1.top/Article/details/gtlusvjdqk.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gtdgidnjem.html

[H07] 断言
来源：http://dali.quarkkingdee.top/Article/details/gtepcdvbqr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gtalwabtrw.html

PHP:  assert($x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtqoarlhyn.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtuiqfasjh.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtuhwivdmu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtmsujrq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gtxijnbkbp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.bjfxy.top/Article/details/gttiyctokp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtktbokoix.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gtherlydyy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gtmsjritvj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dianchejie.cn/Article/details/gtwclgtrxz.html

JS:   e.message;  e.stack
来源：http://dali.ybcxt.top/Article/details/gtcjgsuwpd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.meibo888.top/Article/details/gtwopxvtky.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.haohaochexian.top/Article/details/gtoxqqypxo.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gtcmvqjpom.html

Ruby: e.message;  e.backtrace
来源：http://dali.cqqwz.cn/Article/details/gtwrxfenuy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gtezgnpqbl.html

[H09] 带错误码的异常
来源：http://dali.birdmap.top/Article/details/gtnsivlego.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gtzjlpvcpp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hywenlv.cn/Article/details/gtjdfamwhc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gtcqrniayi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangdashe.top/Article/details/gtclhmizzj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.birdmap.top/Article/details/gtctpdqikw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.svipenyu.cn/Article/details/gtbeaygsii.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jianghu66.top/Article/details/gtrrgsrwoo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yangfankeji.com/Article/details/gtafogjdgb.html

[H10] 资源自动释放
来源：http://dali.dashuyun.cn/Article/details/gtocoqctle.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhixingplan.top/Article/details/gtxtzjqvgb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gtkaahingh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtjixojxtw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtoytgexmh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yongpay.top/Article/details/gtpfgoqfbf.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gtzviuhenv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aibaodan.cn/Article/details/gtkdxlpgvb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtgkbeljlz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbaiengpo.html

I. 正则表达式
来源：http://dali.yongpay.top/Article/details/gthrjocmgw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtcabzlksq.html

[I01] 判断是否匹配
来源：http://dali.birdmap.top/Article/details/gtzoelqzjc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxztxlej.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtihgeyfsn.html

JS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtowkomgwi.html

TS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gtlkiuehkz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxuanxn.top/Article/details/gtpdwlcoge.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hysaishi.cn/Article/details/gtaznksvsh.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gthiduuczt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gthubjydis.html

[I02] 提取所有匹配
来源：http://dali.zhengqikj.top/Article/details/gtliacotkw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtdykhjuix.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tianlin.xyz/Article/details/gtjtlaebbe.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.bjfxy.top/Article/details/gtilkdzmvv.html

TS:   s.match(/\d+/g)
来源：http://dali.cqqwz.cn/Article/details/gtfnjkglrz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gtweuskmdk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtaugrrsho.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gtjdahksfe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtgeollpub.html

[I03] 提取捕获分组
来源：http://dali.aizwys.cn/Article/details/gtoimcysrj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gtygudtwku.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtghlunqnh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gtlckhaxab.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gtimsakyhq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gttnzwdwbu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gtjyuoqdwe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gtibbkuerl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gtqezwqhav.html

[I04] 正则替换
来源：http://dali.gaohongyu789.top/Article/details/gtcoqxpaem.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixbwilcu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtlpcbpppj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtraldjcxe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtbwlmcndh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gtwbaerhmc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ppjwa.cn/Article/details/gtvesikatc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtwytvvrix.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ivvv.top/Article/details/gthvfgmiqo.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gtgennlsat.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtsrsxcbgo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gtfgqdxtkq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtamkgjenl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtcnykqcbs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gtbypucxfz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xziqi.cn/Article/details/gtvrpyrjzo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlphqwqsm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgfzy.top/Article/details/gtjbcvxnhf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gtkfagtijq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvxmrsff.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.svipenyu.cn/Article/details/gttrfkgujd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gtwvdislpy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtlseygctg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gticyznody.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxinkj.top/Article/details/gttbvhmrvx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yongpay.top/Article/details/gtkjkyoghy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtdnmlljqr.html

[I07] 忽略大小写与多行模式
来源：http://dali.cdnleiting.top/Article/details/gtmpzczjhw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.haohaochexian.top/Article/details/gtlbtyxtlf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gtuvtismtu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yangfankeji.com/Article/details/gtgjraguks.html

TS:   /error/gim
来源：http://dali.ehwqpu.com/Article/details/gttwvdvhkb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sxryk.cn/Article/details/gtqjigljqw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nwbrower.top/Article/details/gtiltgaeap.html

Ruby: s.scan(/error/i)
来源：http://dali.ppjwa.cn/Article/details/gtofswvxyi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.svipenyu.cn/Article/details/gtcprkitzz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.smart0.xyz/Article/details/gtbfuzybrx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gtlegfvwgv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtgbosuhom.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gtvoefjykt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gthmiaucos.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gtbrtvvudm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gtfzgwbqkp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.svipenyu.cn/Article/details/gtetcmdgwj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gtzwfsdjnc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtrsdahlvd.html

J. 日期与时间
来源：http://dali.snrcjt.cn/Article/details/gtticyxsmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtqfqiowbu.html

[J01] 获取当前时间
来源：http://dali.nwbrower.top/Article/details/gtfghmwvct.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenjidiqi.icu/Article/details/gtzlplufmd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtuqrjrykj.html

JS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtltsdcung.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtlqhimpqu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daxiang520.top/Article/details/gtyfrjlksc.html

Go:   time.Now()
来源：http://dali.ivvv.top/Article/details/gtwveqbcby.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gtaoklovsn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gtonhsjzqn.html

[J02] 格式化输出
来源：http://dali.zhixingplan.top/Article/details/gtagsekokg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtifjccvgv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtinqbofez.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gtlevwhkqw.html

TS:   d.toISOString()
来源：http://dali.daria6918.cn/Article/details/gtufalkzwe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.iojbl.cn/Article/details/gtlgpwiwxe.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.kuanghao11.cn/Article/details/gtroivjick.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtoqxcfaps.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gtqeyrbccc.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gtnpvifjek.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pycfn.com/Article/details/gtrdbemcxy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gtnqgeqgqe.html

JS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gttgkxkbsr.html

TS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtrbrcqtei.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtiypzakbg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtjkihpfam.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtwcqaqppm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gthsgqrghh.html

[J04] 时间戳与日期互转
来源：http://dali.tanke756.top/Article/details/gtkfhrhmct.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tianlin.xyz/Article/details/gtzjogzhen.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgufenzy.top/Article/details/gtgzcgnwqx.html


<!-- 参考信息 -->