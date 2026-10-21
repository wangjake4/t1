代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtkhcwrvnk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtclcefqvc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinyuanbaomall.cn/Article/details/gtweuzpsmj.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gtsfptcfcn.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gthebqhtlp.html

[G07] 调用父类方法
来源：http://dali.zhengqikj.top/Article/details/gtgthzbgbf.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gtqmqvhjlb.html

PHP:  parent::greet();
来源：http://dali.guannengcc.top/Article/details/gtfkkkfvem.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtnvxuflez.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gttjyyihzx.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gtyercyubd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjodfuaql.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gtzcckiwtx.html

C#:   base.Greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtemnjsejy.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtciklcrsd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gtmrtivmxa.html

PHP:  public static function f() {}
来源：http://dali.iojbl.cn/Article/details/gtbltcghii.html

JS:   static f() {}
来源：http://dali.bjfxy.top/Article/details/gtbauhqdri.html

TS:   static f(): void {}
来源：http://dali.zhiwuduotai.top/Article/details/gtsemivykc.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gttmqldyyg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gtowzabitp.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gtbdutwklw.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gtlxiixkeo.html

[G09] 接口 / 抽象类
来源：http://dali.zhixingplan.top/Article/details/gtueymzlel.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aizwys.cn/Article/details/gtailiehxc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gotoacloud.top/Article/details/gtaoruastb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gtunynmyto.html

TS:   interface Shape { area(): number; }
来源：http://dali.daria6918.cn/Article/details/gtaeggpnix.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtccxituwp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuanzhike.top/Article/details/gtrmsmhzab.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gtrtwqdevg.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnfncwyp.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gtudhkexwz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yonumen.top/Article/details/gtqrrrziqz.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gtmnsnshiz.html

JS:   #private 字段；其余公开
来源：http://dali.yanxiufei.cn/Article/details/gtdemufavp.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtfghudejs.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gtstlhmzbs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tian-w.cn/Article/details/gtzmgtmvwe.html

Ruby: public / protected / private
来源：http://dali.meibo888.top/Article/details/gthphaneqj.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gtxaohrcel.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gtyafzxxfg.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gtpotqzduh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtezcbqssb.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gthgklbich.html

TS:   get name(): string { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtzgurpkqt.html

Java: public String getName() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtrdoxjrrf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtcxhhirip.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gtzmrxcfkb.html

C#:   public string Name { get; set; }
来源：http://dali.yanxiufei.cn/Article/details/gtajwzvxen.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gtfnuipvfu.html

Py:   def __str__(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtiddojhxp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtlfbllanw.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtebgcgxxk.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbwmxpohi.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gthpozsxen.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtwfuuvmuz.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtrbvqgoqi.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtrudkmsmz.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gtckcjktyz.html

Py:   isinstance(u, User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvtswfki.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtluhlhdis.html

JS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtlcfaorlp.html

TS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtihfjwojc.html

Java: u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddubiiex.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gtizddassk.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaulixcvz.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gteyvzjrme.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gtmellvvuv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gtzyygsnrq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.mhx1999.top/Article/details/gtcfeygycj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dianchejie.cn/Article/details/gtclczbrpz.html

TS:   type User = { name: string; age: number };
来源：http://dali.gotoacloud.top/Article/details/gtrjbgwxns.html

Java: record User(String name, int age) {}
来源：http://dali.cdnleiting.top/Article/details/gtubonkldb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocestbsw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gtoyqcpkvn.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gttbpeqwnj.html

[G15] 枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gthxrzhiaq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ivvv.top/Article/details/gtsowtvkdk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daria6918.cn/Article/details/gtpxqlnvya.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxuanxn.top/Article/details/gtvgemuasj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gthlnaovhw.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenlongwang.top/Article/details/gtfdkdkeii.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gtjtdpwrzj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gtcmhpqirx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtyqtesmcz.html

[G16] 对象转数组 / 字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtvccrvi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.haohaochexian.top/Article/details/gtzahlwasq.html

PHP:  get_object_vars($obj);
来源：http://dali.yanxiufei.cn/Article/details/gtebduocmd.html

JS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtadjiruwi.html

TS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtdugkypkl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gtkscvoijh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhoulong.xyz/Article/details/gtnrbwlyri.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gtzwkovnhh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtaprbbmuz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrkxbzmuc.html

H. 异常与错误处理
来源：http://dali.yongpay.top/Article/details/gtdcpowefd.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzrmzyxwp.html

[H01] try / catch 基础
来源：http://dali.mhx1999.top/Article/details/gtapmhvpvv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnxiangtu.top/Article/details/gtlyhpocgz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gttyhnesda.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtenbfgarq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtyqxlklfc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gtdpnadspf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.haohaochexian.top/Article/details/gtrozyukas.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gtnglsdwta.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gtbivrfyjd.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gtlsozzwfr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuxming.cn/Article/details/gtguidowip.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtfienuaji.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtziqcslsw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtcidklzdd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtxmnlluyo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gtomawwgcn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ppjwa.cn/Article/details/gtidxcpafd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtibheffgh.html

[H03] 主动抛出异常
来源：http://dali.hysaishi.cn/Article/details/gtyawkjtwk.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkaazkepy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtzkipedst.html

JS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymjkltgd.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtbyvshnci.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtvpuhhqtc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gtomkvoksj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gtwsagtsla.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtnkkmuyek.html

[H04] 自定义异常类型
来源：http://dali.zhongyouzk.top/Article/details/gtsgfpfzpy.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gtyuzpvqfv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gtbknfwvdv.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gtmouelvod.html

TS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gtgdpueqdg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtiatzethq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xinyue.icu/Article/details/gtorjnsbrd.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gtduwfpdhl.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtbmlkspuw.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuopbrspn.html

Py:   except ValueError as e:
来源：http://dali.c1oappe.top/Article/details/gtkchpzrrx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gtazuxomce.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtdpcutczb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtdmtqhipz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tian-w.cn/Article/details/gtbuatphqx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyzbsynp.html

Ruby: rescue ArgumentError => e
来源：http://dali.dianchejie.cn/Article/details/gtvmeoiswc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yongpay.top/Article/details/gtwqlpuqqt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gtbjyvdpdc.html

Py:   value = d.get("k") or default
来源：http://dali.aizwys.cn/Article/details/gtfmcqrtfn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gtippzswmm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtdmyiitfv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtexsgwqwl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgyzghdv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuanzx.com/Article/details/gthuxfdvkg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jyoumei.cn/Article/details/gthtwnuzit.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtrbrjkqeg.html

[H07] 断言
来源：http://dali.hammf.cn/Article/details/gtznxhxriv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrbubfcy.html

PHP:  assert($x > 0);
来源：http://dali.cucudq.cn/Article/details/gtzepmsnbb.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gttcvbqnsn.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtxfkvuoen.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daxiang520.top/Article/details/gtrouunegn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtoifdwwpl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.vqdsnc.cn/Article/details/gtbyumsrzs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtnkjjmrlt.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gtbbnvyncc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shangyingyoupin.top/Article/details/gtfjsmopgh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gtekwcvbsq.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gtgyhyonot.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.0kj1m.cn/Article/details/gtfsccjzvg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jianghu66.top/Article/details/gthtstumrb.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gtjdyzkigj.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gttgzmghtd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtdrufoxsm.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gtgwrwaedc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtmcvvswwo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenlongwang.top/Article/details/gtbmggtxts.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcliieim.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jianghu66.top/Article/details/gtmvvfnkol.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258888.top/Article/details/gtjxexvxjp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sxryk.cn/Article/details/gtsskmbapr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gaohongyu789.top/Article/details/gteskobbli.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.316326.xyz/Article/details/gtevmnslet.html

[H10] 资源自动释放
来源：http://dali.hnqzz.top/Article/details/gtwgzrzcsm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenlongwang.top/Article/details/gtvlajjztc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.vqdsnc.cn/Article/details/gtvgjhndtv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtoqtgyooo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtmkvjcjpc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shuidangran.top/Article/details/gtjcvdswjv.html

Go:   defer f.Close()
来源：http://dali.ivvv.top/Article/details/gtaouvrhlv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gtzjdprpms.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtuqohouje.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtvtfrmhox.html

I. 正则表达式
来源：http://dali.9152youxi.cn/Article/details/gtbgljslof.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtyojfjvqa.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gtknmxhnjf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtmrkgkjkt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtbdrohjvr.html

JS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtavjlyycb.html

TS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtajcoknam.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gtsmugsqmm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtumgwufeg.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmkwojkf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gtrntlwhvu.html

[I02] 提取所有匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtxxzablgr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gthibdbxnj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gtehskfyts.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlluvovon.html

TS:   s.match(/\d+/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtuxvkrziq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtummjqwbw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtpzslqpln.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtewwrtybt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtmmcmrrry.html

[I03] 提取捕获分组
来源：http://dali.xuanzx.com/Article/details/gthkqgbnzh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhoulong.xyz/Article/details/gtezblznat.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ehwqpu.com/Article/details/gtpmukhdfa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yueranfly.top/Article/details/gtbubsrvro.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gaohongyu789.top/Article/details/gtoltdoldm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbedtyezc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.meibo888.top/Article/details/gtsxqycvgf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aizwys.cn/Article/details/gtrukbabff.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cheryme.top/Article/details/gtdoloqjlx.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gtkvoppcqu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gtpwqaglap.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gtspyquaqe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gthuikzcif.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtkodkvjpa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtdmxgksnj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guannengcc.top/Article/details/gtvqssimol.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gtjivzuvfx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtqtukvpes.html

[I05] 按正则拆分
来源：http://dali.zdqjudy.top/Article/details/gtyprndjtb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gtnmzsmogi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aizwys.cn/Article/details/gtdryezdnt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtstxrwfzs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtfmcnufdw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtuxkfxhcd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiynbyowy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtnmliarep.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gtfbchqzwr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gtkdszhmcn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtztnidwkr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gtmuzpxnlu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtevgzleoi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtmcufmngi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtepjzrjzb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gtzkioaczc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gtzvwvmqcw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtcztxochh.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnxiangtu.top/Article/details/gtzccmnpjm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gtfbyxvlgy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gttqptgrbr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tianlin.xyz/Article/details/gtovxgefje.html

TS:   /error/gim
来源：http://dali.zhoulong.xyz/Article/details/gtuspduchu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnqzz.top/Article/details/gtiqpnyvku.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhoulong.xyz/Article/details/gtxuxxbnto.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gtjksyojcb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tianlin.xyz/Article/details/gtczjoumng.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuxming.cn/Article/details/gtwmlvhpja.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhengqikj.top/Article/details/gtgfkrarqo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gttwvyefdl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtgykwteca.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtnurubqyr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtntrnnkwy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zdqjudy.top/Article/details/gtjkqrwfsq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sxryk.cn/Article/details/gtcpdqzrcu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtcxshgjfw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqpmtmecs.html

J. 日期与时间
来源：http://dali.kuanghao11.cn/Article/details/gtzrypmrdy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtzfwqxhtu.html

[J01] 获取当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtjcbohhry.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zycfv.cn/Article/details/gttstdkqxo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtyncbocmu.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokvskkyk.html

TS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtjanxfcqt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zycfv.cn/Article/details/gtrsrpozvf.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gthcppmsio.html

Ruby: Time.now
来源：http://dali.tianlin.xyz/Article/details/gtqqduultf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.svipenyu.cn/Article/details/gtcyxvgutc.html

[J02] 格式化输出
来源：http://dali.bjfxy.top/Article/details/gtaefqedvo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtuolaaglv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gtetvdaper.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.smart0.xyz/Article/details/gtgrnuskie.html

TS:   d.toISOString()
来源：http://dali.snrcjt.cn/Article/details/gtmmeytkek.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sxryk.cn/Article/details/gtejfrniyn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aizwys.cn/Article/details/gtgagwlszc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gttlgecqqk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigufen.top/Article/details/gtcjiwyfxf.html

[J03] 字符串解析为日期
来源：http://dali.fengsongda.top/Article/details/gtyakhvylu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhengqikj.top/Article/details/gtldwqtcmb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gtogibhdqb.html

JS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtkxyyepfs.html

TS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtzqhlqhvc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtrahgqjpc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gttrcciajc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdphdtiqy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.havefunace.top/Article/details/gtnrusyhef.html

[J04] 时间戳与日期互转
来源：http://dali.yuxming.cn/Article/details/gtwvevdsxr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvvyikvw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gtzhtaosky.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gttllhxvra.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gtjkqeqrmz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtlqpyxbzk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zycfv.cn/Article/details/gtmzneemny.html


<!-- 参考信息 -->