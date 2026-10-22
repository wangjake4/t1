代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2xtqmqkqz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2gquxfcwk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gt2dpurmwya.html

Ruby: def greet; "admin"; end
来源：http://dali.kuanghao11.cn/Article/details/gt2geyiwemr.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gt2ljnxcsso.html

[G07] 调用父类方法
来源：http://dali.shuidangran.top/Article/details/gt2byutglhv.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gt2zyrqywgb.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gt2gmyahofd.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gt2lyliptwr.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gt2kvybtrrc.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2avovxxhg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gt2anhrdubz.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gt2pbdhpfbi.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gt2qxvoafno.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gt2gezhlryn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gt2jfzhputj.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gt2iydqsujd.html

JS:   static f() {}
来源：http://dali.shuidangran.top/Article/details/gt2vkhcotlp.html

TS:   static f(): void {}
来源：http://dali.chenlongwang.top/Article/details/gt2xoypjqzb.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gt2jzvkpjqq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dpvdyhrd.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gt2bzfagjvn.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gt2gurgtrvb.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gt2safceedx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gt2koffjnkf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gt2zmrnvyzw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gt2ikqtrbtc.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cznuhhoo.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gt2brmxgioc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gt2lsazktwo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sysykeji.top/Article/details/gt2qnqnisqs.html

C#:   interface IShape { double Area(); }
来源：http://dali.yongpay.top/Article/details/gt2mlegghtr.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gt2kxnrfxol.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gt2fscakeia.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnkfeixf.html

JS:   #private 字段；其余公开
来源：http://dali.hongshengwenyu.top/Article/details/gt2cepgtcby.html

TS:   public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwyoymig.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gt2imeuhcjr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2knipeisf.html

Ruby: public / protected / private
来源：http://dali.havefunace.top/Article/details/gt2unqdpqff.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gt2wkwrwfoe.html

[G11] getter / setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xroyldyj.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gt2wxarwiim.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2lwnhwnjp.html

JS:   get name() { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gt2otcopxzm.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrhfsslb.html

Java: public String getName() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2rphpeyoa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2jzyynovl.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gt2oqzljkvo.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gt2gzhihrhk.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gt2buepiial.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gt2rvpyjtnp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2qvenzblx.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2hhfxwhuf.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2xadqpygk.html

Java: @Override public String toString() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2cmplkeqj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gt2ohwmnhls.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gt2rmgjmxzh.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2aebogwmb.html

[G13] 判断对象类型
来源：http://dali.zdqjudy.top/Article/details/gt2gqmvkdxp.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cvhzjvpp.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2rbkslrrk.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2eynhjrvi.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2dmptyaom.html

Java: u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2syuvddhm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgufenzy.top/Article/details/gt2mlhlgyov.html

Ruby: u.is_a?(User)
来源：http://dali.guowangkeji.top/Article/details/gt2lajpwude.html

C#:   u is User
来源：http://dali.gaohongyu789.top/Article/details/gt2pxprjxug.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gt2rvibtssb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gt2wsvulyiv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjmzvprp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gt2oupafkzl.html

TS:   type User = { name: string; age: number };
来源：http://dali.daxiang520.top/Article/details/gt2ivgtteqv.html

Java: record User(String name, int age) {}
来源：http://dali.smart0.xyz/Article/details/gt2nolaezuo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jednonxb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfuypca.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gt2dhvhkikj.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2ttxjyoam.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2lrqdfrbh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cdnleiting.top/Article/details/gt2pivrvltu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gt2jayhmgku.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcylacxg.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gt2mpgxoslj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xinyue.icu/Article/details/gt2qzzpxkke.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gt2xbsdvugp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gt2rmxfawlo.html

[G16] 对象转数组 / 字典
来源：http://dali.shzxlz.cn/Article/details/gt2jdhryhpl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gt2inzpiblq.html

PHP:  get_object_vars($obj);
来源：http://dali.pycfn.com/Article/details/gt2hyyfcswi.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2pflzldma.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2hrqccqwg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gt2oebwhnwu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shzxlz.cn/Article/details/gt2yeunyzir.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gt2znhtnskn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gt2pnnqmeeg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ogvvpjyb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbbpqkr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2pqecsjzu.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iennbgjc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gt2wvycrbre.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gt2ztlpssrt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gt2vvfeqcfc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjuzsuyz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gt2cozcwavq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jianghu66.top/Article/details/gt2trjsyumv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gt2majhplja.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yanxiufei.cn/Article/details/gt2hiwleowt.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gt2ppknyqsm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gt2wjygmlti.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2ncscfwrp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2xsjxwvdt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2mpmyyxkz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2mzmcxobd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gt2muvofscq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gt2bynbppow.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2guxcuxpr.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gt2djyioeuw.html

Py:   raise ValueError("错误信息")
来源：http://dali.sysykeji.top/Article/details/gt2avntfhiw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2cjnkebce.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gt2tprazums.html

TS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2wowprddq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2xprnpjmp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gt2dfdxeoto.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2onqoguzh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2uniinfwc.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gt2iipehykc.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjfmtlyv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gt2asjicrtj.html

JS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gt2rwkscgvi.html

TS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gt2hmriayfp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gt2gqhvyruj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kpvrgnqy.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxinkj.top/Article/details/gt2vnedbdgz.html

C#:   class MyException : Exception {}
来源：http://dali.gzhubu.top/Article/details/gt2nqspogci.html

[H05] 捕获特定类型
来源：http://dali.jqgfzy.top/Article/details/gt2qrtqgmbj.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gt2xlsxumtw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258.top/Article/details/gt2lipvduir.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gt2vnirukmv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gt2fdgvlpea.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yvedp.cn/Article/details/gt2wvjsbprf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hysaishi.cn/Article/details/gt2skcmcrxr.html

Ruby: rescue ArgumentError => e
来源：http://dali.aizwys.cn/Article/details/gt2hlfkdhil.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gt2frgbofjc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gt2vllcullz.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gt2yywzfwcl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gt2unaqmfum.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gt2snupegxd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gt2jpwqlwqk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cdnleiting.top/Article/details/gt2qftnulwn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.haohaochexian.top/Article/details/gt2ghrbfrru.html

Ruby: d&.dig(:a, :b)
来源：http://dali.haohaochexian.top/Article/details/gt2wypcpvdw.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2tcvpbguy.html

[H07] 断言
来源：http://dali.jiagoushi.top/Article/details/gt2rmklbzrk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gt2fsdntufa.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gt2esvridds.html

JS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2zekikiht.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2bvlcamvx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gt2qghbrjpw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gt2pwexyeyg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.c1oappe.top/Article/details/gt2qnhczmle.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2bkowvcrm.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gt2nwfmkful.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gt2uewoicqe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ehwqpu.com/Article/details/gt2eqfzlckt.html

JS:   e.message;  e.stack
来源：http://dali.ydzc1.top/Article/details/gt2nokusfbs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hcqfluga.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gogol.net.cn/Article/details/gt2spnyjlbe.html

Go:   err.Error()
来源：http://dali.yj20258888.top/Article/details/gt2njwvdsuw.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gt2tluqjjbg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gt2kbxghzbi.html

[H09] 带错误码的异常
来源：http://dali.jianghu66.top/Article/details/gt2hrpvxzyk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dianchejie.cn/Article/details/gt2znxbjunw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gt2zwtwhtsn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gt2uxyybjtn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gt2vatsbxnh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zdqjudy.top/Article/details/gt2nfmdeadx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.iojbl.cn/Article/details/gt2bmecueew.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj202588.top/Article/details/gt2nwadvwsz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gt2wwvgbazf.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2prdwphur.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gt2mbnrpzoa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2piuolvyz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gt2dzhcdbxw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gt2lwdheqeb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gt2pikvimxv.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmsofmin.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.9152youxi.cn/Article/details/gt2hofnfjcg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2tardzeba.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2igsjbyjr.html

I. 正则表达式
来源：http://dali.zycfv.cn/Article/details/gt2yllrupqb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhcrgckt.html

[I01] 判断是否匹配
来源：http://dali.yangfankeji.com/Article/details/gt2punsdcrp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2moduvsbo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2trgljuxo.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gt2yyypvodc.html

TS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2elwmkier.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gt2hgfwqods.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ivvv.top/Article/details/gt2mvahzvaj.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj202588.top/Article/details/gt2azvslwgf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nidrihhq.html

[I02] 提取所有匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2jnvobulp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gt2mgdfmzsa.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gt2bqjyswjr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shzxlz.cn/Article/details/gt2dzbtngwo.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gt2omrcjsap.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gt2nuisuncn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj202588.top/Article/details/gt2dqvkwvfp.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gt2smussiji.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2ttazensi.html

[I03] 提取捕获分组
来源：http://dali.hammf.cn/Article/details/gt2wtlruyuk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gt2awvhauoo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pycfn.com/Article/details/gt2ggoltrbp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cucudq.cn/Article/details/gt2wafqsxjp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gt2jdqkfuue.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pycfn.com/Article/details/gt2mlfjsoec.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gaohongyu789.top/Article/details/gt2hacqngst.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gt2nloqwzuq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cashguo.top/Article/details/gt2whxlqidy.html

[I04] 正则替换
来源：http://dali.nanxuanxn.top/Article/details/gt2ffqnxort.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jyoumei.cn/Article/details/gt2ivtgldno.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2bvnvfqsj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gt2xeeusfsf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2poexivcv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gt2prrmspcc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gt2iplwykon.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2gbxhguhm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ixhlswxm.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gt2snpszebf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gt2azzdmuiq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2qjzzcmus.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gt2jrovdhpy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2xcejlapt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gt2namjjosc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.c1oappe.top/Article/details/gt2hpzcvzii.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oexfchhj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cashguo.top/Article/details/gt2haxnnfqr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.9152youxi.cn/Article/details/gt2obfoilid.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gt2jvjswyxu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhoulong.xyz/Article/details/gt2vznfjlwt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2swdguwzv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gt2jzujhpic.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2wfaccwri.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tianlin.xyz/Article/details/gt2tvccshzn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.smart0.xyz/Article/details/gt2upqjfezw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vfhcoggn.html

[I07] 忽略大小写与多行模式
来源：http://dali.zycfv.cn/Article/details/gt2ifegswaw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gt2nmeyynyw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gt2kghmjqaj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenlongwang.top/Article/details/gt2ozahnucb.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftnjcovn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gt2emiygmjx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnxiangtu.top/Article/details/gt2kikumbku.html

Ruby: s.scan(/error/i)
来源：http://dali.sxryk.cn/Article/details/gt2chqbmlgc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.havefunace.top/Article/details/gt2cpwmgxvg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hysaishi.cn/Article/details/gt2spkevhjc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zycfv.cn/Article/details/gt2tlvuaeec.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gt2kivxjulj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gt2xteefkzo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ekjqlzmy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gt2uuyuzcap.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shuidangran.top/Article/details/gt2ziuzszcb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gt2bavpdtaw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gt2hfvblhkj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2sbvuasll.html

J. 日期与时间
来源：http://dali.shzxlz.cn/Article/details/gt2vzwehbid.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2rlxbezoc.html

[J01] 获取当前时间
来源：http://dali.jiagoushi.top/Article/details/gt2qvwmlipj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yueranfly.top/Article/details/gt2ebjwheud.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gt2uvlvqilf.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2hbvfqxlf.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gt2htibgktj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yongpay.top/Article/details/gt2ezazjpwk.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gt2ezajgdgp.html

Ruby: Time.now
来源：http://dali.ppjwa.cn/Article/details/gt2grccdrat.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbtikarq.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gt2cgcbsnzf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2nyudvojw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gt2yvafzvds.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnxiangtu.top/Article/details/gt2kbdjvtkp.html

TS:   d.toISOString()
来源：http://dali.yuxming.cn/Article/details/gt2oyadnxxt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sxryk.cn/Article/details/gt2ifdegihb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tanke756.top/Article/details/gt2qhjpmeoo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gt2tqgzkfhp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jyoumei.cn/Article/details/gt2irjpqyav.html

[J03] 字符串解析为日期
来源：http://dali.hammf.cn/Article/details/gt2noxytwoo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fzhhl.top/Article/details/gt2rrcckygw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gt2wreamflt.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgoavsui.html

TS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2amkcgkre.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2bkkweqji.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2vuisyhat.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2wjnoyqcg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cdnleiting.top/Article/details/gt2jbygrodd.html

[J04] 时间戳与日期互转
来源：http://dali.ivvv.top/Article/details/gt2nelwewem.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tggvhpsj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gt2wctwywub.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hammf.cn/Article/details/gt2ubqkbdsm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gt2ckmbaviq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2qawrfbjt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gt2uatrdsiz.html


<!-- 参考信息 -->