代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2yuxlgdfv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2dsfrvheg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gt2wbqiulpo.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gt2muxglhcf.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gt2lmchoojv.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gt2fiuquoax.html

Py:   super().greet()
来源：http://dali.dashuyun.cn/Article/details/gt2jpfimsiq.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2wehhspks.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttrorxuv.html

TS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2etmmqijk.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gt2wwqjeqyo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gt2lkmpmqyy.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gt2asbuwlqx.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gt2ldybxcdi.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gt2efdlygbt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gt2odqygkfv.html

PHP:  public static function f() {}
来源：http://dali.yuxming.cn/Article/details/gt2jpajcqrk.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2vkamepjc.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gt2pwimdvoe.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gt2wpwjvwdm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gt2crmwvrpz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjehyve.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozlcrive.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gt2nlzmohiy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.meibo888.top/Article/details/gt2evjllltt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gt2naxfkhkb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cdiwbxfd.html

TS:   interface Shape { area(): number; }
来源：http://dali.hywenlv.cn/Article/details/gt2gsgudfmn.html

Java: interface Shape { double area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aoybhdku.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnqzz.top/Article/details/gt2vpbrvzyo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.quarkkingdee.top/Article/details/gt2xzadrzgj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gt2pmeteyah.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2domavafd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gt2ukdmjnlb.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2naukrgbf.html

JS:   #private 字段；其余公开
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cksltngp.html

TS:   public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2aqwrpyqi.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlyotod.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gt2ghlwlfos.html

Ruby: public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gt2fndjbozq.html

C#:   public / protected / private / internal
来源：http://dali.yangfankeji.com/Article/details/gt2qtjariwq.html

[G11] getter / setter
来源：http://dali.316326.xyz/Article/details/gt2zbtlxhsr.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gt2dlfdriot.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gt2gkijbywk.html

JS:   get name() { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gt2exziutzv.html

TS:   get name(): string { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gt2zdgjvjjx.html

Java: public String getName() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2okolryhx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gt2smixvcwb.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gt2ogkrilfv.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ycyawyrx.html

[G12] 对象转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2atfskhyq.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gt2bkbwpkkq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2faoonpdn.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2dakvilfa.html

TS:   toString(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2vneajmsa.html

Java: @Override public String toString() { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2jwjspwfk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gt2spywjzjn.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gt2zdsnidam.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gt2elbmbkxj.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gt2tkmjvrep.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gt2hhbvpvqu.html

PHP:  $u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2ogtjkmkz.html

JS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2ofeeqldb.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2ircyvtfa.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2fslwhmvt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gt2sgvemdcb.html

Ruby: u.is_a?(User)
来源：http://dali.tanke756.top/Article/details/gt2kjawdwgj.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gt2vnjhjezt.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gt2sijlypal.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gt2wfbvcaec.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gt2nyohpbye.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gt2towsbvdp.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gt2shkopwof.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gt2dbzwbtbo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gt2lmihegky.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gt2uzvxprtk.html

C#:   record User(string Name, int Age);
来源：http://dali.ydzc1.top/Article/details/gt2ynjcvill.html

[G15] 枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khvaenvc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yonumen.top/Article/details/gt2anmiipjo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.mhx1999.top/Article/details/gt2hodpponv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhongyouzk.top/Article/details/gt2bqgqreky.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srhzikff.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gt2allaaama.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gt2xjfrrvxo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gt2iuagtbny.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2nmojjnek.html

[G16] 对象转数组 / 字典
来源：http://dali.ppjwa.cn/Article/details/gt2ghdulptu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gt2jeifatyv.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gt2tmpduqkg.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gt2lfdvdnfi.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gt2zyqrrqla.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuanzx.com/Article/details/gt2vxacwzns.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gt2hgwwrhrd.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkrghjwx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gt2dyvemzqz.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2odvthxgn.html

H. 异常与错误处理
来源：http://dali.ybcxt.top/Article/details/gt2jfbmkyen.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2exmevtuy.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gt2yfrzjcov.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gt2ncvgrmpk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.haohaochexian.top/Article/details/gt2hlyyiwbf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2webckwan.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gt2uqveydxn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gt2cslultya.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gt2txoqhqdo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gt2nbkioobo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gt2tjqiyiqp.html

[H02] finally / ensure 收尾
来源：http://dali.cheryme.top/Article/details/gt2rbfhvzzq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kalbzmnr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2qasxetvc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2kmlwuebb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2utbrjbfx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2yhdhduba.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dyhfiaud.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gt2arveybzc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2iyrjacuf.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gt2idsgxabw.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gt2lngzngcq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2cbejkmqa.html

JS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2dbryctee.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2inbiagsn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2kdpsjpuo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxlkxhcx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gt2fkwujffn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2xolbiwxz.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gt2mbrebujn.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gt2pvwcwsew.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gt2bgtxsdmm.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gt2nuiggflu.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gt2ahfkqeix.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gt2caqmligp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gt2ebpqrzxo.html

Ruby: class MyError < StandardError; end
来源：http://dali.iojbl.cn/Article/details/gt2oxaoivjb.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gt2qomqyfqg.html

[H05] 捕获特定类型
来源：http://dali.yueranfly.top/Article/details/gt2opjkhqat.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gt2eqtzhrpc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2wnnelmsb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2fcuoaasl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gt2tpscbnjj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gt2heslllaz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.0kj1m.cn/Article/details/gt2rdxmzmbk.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gt2ijkdnqgd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wcupfoyl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gt2sirfoqky.html

Py:   value = d.get("k") or default
来源：http://dali.aizwys.cn/Article/details/gt2hwsviiao.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vlgafbdc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2asizaxch.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gt2frsjfwqr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gt2zhlidikz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guannengcc.top/Article/details/gt2uklyjptn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmszlycx.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2pgofvdcq.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gt2labhwbcm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqntkymf.html

PHP:  assert($x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2phvobeuv.html

JS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2ixebrbho.html

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2ozyooydc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmqvicz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmyeiwa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhvbuslf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2eawxjyfh.html

[H08] 获取错误信息与堆栈
来源：http://dali.jlsjyb.cn/Article/details/gt2giegliuo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hysaishi.cn/Article/details/gt2fkzfxufp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gotoacloud.top/Article/details/gt2cjgjxzoy.html

JS:   e.message;  e.stack
来源：http://dali.gogol.net.cn/Article/details/gt2rtywmvbr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hammf.cn/Article/details/gt2yrtljjmu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gt2mxbavxjt.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gt2hjkzdttn.html

Ruby: e.message;  e.backtrace
来源：http://dali.snrcjt.cn/Article/details/gt2siqzdzej.html

C#:   e.Message;  e.StackTrace
来源：http://dali.bjfxy.top/Article/details/gt2dkgmeevb.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gt2uaeciyhx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkazzdtw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.bjfxy.top/Article/details/gt2tpfckhtm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hysaishi.cn/Article/details/gt2mglkmucf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpkejgpr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gt2iapgrfot.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yongpay.top/Article/details/gt2wdkblplu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xcnbhkxi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guannengcc.top/Article/details/gt2jhijvcwz.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gt2xnmcjkct.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cheryme.top/Article/details/gt2zofrtljn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gt2mjckhova.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkashcps.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gt2cfsdwslo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jianghu66.top/Article/details/gt2vweyqdph.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gt2nozmubti.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zdqjudy.top/Article/details/gt2gunehnuh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2czluxvvp.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2pnjnognw.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gt2fspwtaca.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2qxapvlor.html

[I01] 判断是否匹配
来源：http://dali.ivvv.top/Article/details/gt2tazpvkpk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gt2edyjqxfg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2usugougx.html

JS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gt2usxmmjjp.html

TS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gt2geeupsek.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gt2ibmcueuo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangdashe.top/Article/details/gt2sfxbtomw.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2esipnqua.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yueranfly.top/Article/details/gt2cjdubfhx.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gt2rquixliw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gt2sktahpwk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gzhubu.top/Article/details/gt2labdawph.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gt2yluvpwxk.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2esutyqdr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gt2ttsnvwga.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gt2tycmpvpe.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2tyixyipi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jpgjxyyy.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gt2kesgpnsz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guannengcc.top/Article/details/gt2omhmwrkv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhongyouzk.top/Article/details/gt2smikbeao.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aizwys.cn/Article/details/gt2jvgvhfzi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2vcdlpphh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cashguo.top/Article/details/gt2lsumwmkj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fzhhl.top/Article/details/gt2ggtoztxl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gt2aaxmliwv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cashguo.top/Article/details/gt2qwzxqrkd.html

[I04] 正则替换
来源：http://dali.jqgufenzy.top/Article/details/gt2zjapenae.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vuqacvko.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2cdlkdgsl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2rmwuhnfv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gt2zvbiyzmj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gt2gflljakn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2leoeuctu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cucudq.cn/Article/details/gt2soxubfnb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gt2zuaczagt.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gt2vfmcbsfs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gt2jwewasck.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2hjcmsbne.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2igheqwlu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2isouwlkl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gt2uexviqyx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aizwys.cn/Article/details/gt2qaahofsc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2jcakgrsm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cqqwz.cn/Article/details/gt2jiapjicb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwcfnzqm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gt2dcqcwvfa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gt2pgrserth.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gt2ujrjvsns.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gt2cmiyuenk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2sduswkcu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.kuanghao11.cn/Article/details/gt2wfqhkdbh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tian-w.cn/Article/details/gt2bomsxeuo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2puyrtwtg.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gt2fpcjxopy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ivvv.top/Article/details/gt2vmjmahgy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkxormoc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jlsjyb.cn/Article/details/gt2ohwcvmfq.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gt2kzqhjdqb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ppjwa.cn/Article/details/gt2cbamgtvi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhixingplan.top/Article/details/gt2doxqozer.html

Ruby: s.scan(/error/i)
来源：http://dali.hysaishi.cn/Article/details/gt2fgjnvhqs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2twiesmpq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tianlin.xyz/Article/details/gt2axdistqp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gt2zyptrohy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gt2nlrxnnmw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2xzsrnzjr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gt2bqjvdknb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gt2ysnipmpp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gt2mukvhnet.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gt2mwcperja.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gt2zhriokkq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ycssjgxi.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gt2ooxpitrk.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2phbswmky.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gt2hurfzame.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hywenlv.cn/Article/details/gt2mjlmeriq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gt2kmvdstgw.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gt2oeefopeh.html

TS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2skxyaoxg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qtveelrm.html

Go:   time.Now()
来源：http://dali.guowangkeji.top/Article/details/gt2ksiyficb.html

Ruby: Time.now
来源：http://dali.pycfn.com/Article/details/gt2tsqiispi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2icceguhd.html

[J02] 格式化输出
来源：http://dali.shuidangran.top/Article/details/gt2hlmrykzh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gt2tvmbcwbf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gt2qphjykoe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.havefunace.top/Article/details/gt2cpespiqo.html

TS:   d.toISOString()
来源：http://dali.vqdsnc.cn/Article/details/gt2wyjatmnk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gt2yxuszukn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gt2urlvhfiz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gt2digjdurz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenjidiqi.icu/Article/details/gt2gokulscj.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gt2aejejdcd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tianlin.xyz/Article/details/gt2rsigdxwc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sufxvd.cn/Article/details/gt2hjutxdej.html

JS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2sygxlisc.html

TS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2vepvweri.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2gyeuiwnz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2bldhuywl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2fuwgszcj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.0kj1m.cn/Article/details/gt2byjhrmlj.html

[J04] 时间戳与日期互转
来源：http://dali.hywenlv.cn/Article/details/gt2kpdrfvvy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hywenlv.cn/Article/details/gt2pdasdzmy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnxiangtu.top/Article/details/gt2czezrofn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hysaishi.cn/Article/details/gt2lqzvmdjo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj202588.top/Article/details/gt2tomsdccx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2enpmfgnb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gt2diawbdwt.html


<!-- 参考信息 -->