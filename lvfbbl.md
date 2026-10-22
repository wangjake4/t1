代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdlidkjf.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gt2fbgledgo.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gt2kmrnwhow.html

PHP:  parent::greet();
来源：http://dali.tianlin.xyz/Article/details/gt2cfwgpbct.html

JS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2odbkquks.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gt2hngpbwax.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gt2rfrgyrkf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gt2toewbqlm.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gt2ihlnhwtr.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2ynutkmhz.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gt2nieossqf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gt2csinqwuh.html

PHP:  public static function f() {}
来源：http://dali.hnqzz.top/Article/details/gt2gtggqlec.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gt2vidwuzet.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gt2bjdpjmpw.html

Java: static void f() {}
来源：http://dali.haohaochexian.top/Article/details/gt2qxssaaym.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gt2bqpvbexd.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gt2heqaqzux.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gt2wkbcuibf.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gt2msoiftbd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sweek.top/Article/details/gt2mqxhnwwx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gt2pnpdfbyh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jianghu66.top/Article/details/gt2wmhgbvht.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gt2ubzxazeo.html

Java: interface Shape { double area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvpmjqcq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgufenzy.top/Article/details/gt2cnfosdbd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gt2qvzycpmu.html

C#:   interface IShape { double Area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbbbtvvj.html

[G10] 访问控制
来源：http://dali.yangfankeji.com/Article/details/gt2vweaidvi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tanke756.top/Article/details/gt2woddzcnc.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2fwuykkvf.html

JS:   #private 字段；其余公开
来源：http://dali.wangshuangyany.cn/Article/details/gt2dajbxviu.html

TS:   public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2ttyknuxn.html

Java: public / protected / private / 默认包级
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbsyfdac.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gt2tfubhhto.html

Ruby: public / protected / private
来源：http://dali.yvedp.cn/Article/details/gt2mtceybnr.html

C#:   public / protected / private / internal
来源：http://dali.gzhubu.top/Article/details/gt2uharvokp.html

[G11] getter / setter
来源：http://dali.nanxinkj.top/Article/details/gt2hcmlegem.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2ijbqswdx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gt2sutdwybn.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gt2oegysqfg.html

TS:   get name(): string { return this._name; }
来源：http://dali.cheryme.top/Article/details/gt2gjivpqck.html

Java: public String getName() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2olgqotbh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2ujamsyty.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gt2lessoutu.html

C#:   public string Name { get; set; }
来源：http://dali.hammf.cn/Article/details/gt2xzotklmz.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gt2avcjhhqf.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gt2obogsqfr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gt2juepnvbn.html

JS:   toString() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2xevzpmcm.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2upfhhqqd.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2iskbvjnj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2zfuhnquj.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gt2pkyrgpux.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gt2tqyxgagx.html

[G13] 判断对象类型
来源：http://dali.yueranfly.top/Article/details/gt2pnexkxkw.html

Py:   isinstance(u, User)
来源：http://dali.yuxming.cn/Article/details/gt2wscgkdan.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2fjruqeox.html

JS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2iaaufzbc.html

TS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2xfuvpgqh.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gt2jtxyeees.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gt2jrmsjigs.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gt2yjqskbkl.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gt2rhqxzmgp.html

[G14] 数据类 / record
来源：http://dali.quarkkingdee.top/Article/details/gt2xlehsguq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cashguo.top/Article/details/gt2womuhens.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gt2qdzjiwgr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.redwolf501.top/Article/details/gt2petqycem.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gt2nmvoanfa.html

Java: record User(String name, int age) {}
来源：http://dali.guowangkeji.top/Article/details/gt2sbwluocr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gt2ngpsfdes.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gt2dswcyowv.html

C#:   record User(string Name, int Age);
来源：http://dali.ybcxt.top/Article/details/gt2hxzhfpzd.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gt2dbijgkpi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.haohaochexian.top/Article/details/gt2xxbyqzwz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmdcgais.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gt2cjuvkddq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gt2ugfcoycj.html

Java: enum Color { RED, GREEN }
来源：http://dali.hywenlv.cn/Article/details/gt2addsyieh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gt2bmprewrd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gt2vkknyaul.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffnpieid.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gt2wgmiveoh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gt2ayfqxpxb.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gt2nnyhzkgh.html

JS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gt2srhvwmzp.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqwiindj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gt2kvmhmstl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gt2lsgqafkn.html

Ruby: obj.instance_variables
来源：http://dali.tian-w.cn/Article/details/gt2qxgxlmrv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gt2axujaajy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifrsinsz.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gt2sndmlpnb.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2fhlkkcwe.html

[H01] try / catch 基础
来源：http://dali.tian-w.cn/Article/details/gt2usgrdnmp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gt2xnzshofo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gt2mlkbuzcx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gt2xbbqtpur.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gt2xgagdrim.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jianghu66.top/Article/details/gt2wkucztzx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2kymbqnbg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gt2dktmtwdi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daria6918.cn/Article/details/gt2nnmdyqpo.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gt2tobsnptn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangdashe.top/Article/details/gt2sbgrcqib.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2jcwmgupd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2uiuhkjin.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2awupltdc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2fttaljhr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gt2ecvayozc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gt2gzxkivcq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkbxovdv.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfwxtvlm.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gt2swnvokoj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ljvwizpc.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2gcycjjvj.html

TS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2csruidrl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2sxwbugac.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gt2deliivfx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hammf.cn/Article/details/gt2ayoybrto.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2eeovlcff.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gt2ohieghem.html

Py:   class MyError(Exception): pass
来源：http://dali.smart0.xyz/Article/details/gt2fdmyopxw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gt2xdwrohcs.html

JS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gt2xnwgviyy.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwiwqyzb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gt2vtzcrldj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aizwys.cn/Article/details/gt2ruerfjgn.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjqwpdhb.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gt2qayetalu.html

[H05] 捕获特定类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2jvxjmdvo.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gt2mgosfmoc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yonumen.top/Article/details/gt2jujjvfyk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2zrihabcb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gt2mheeaixh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gt2dziawfoh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.haohaochexian.top/Article/details/gt2aotuwtox.html

Ruby: rescue ArgumentError => e
来源：http://dali.hammf.cn/Article/details/gt2sfzqadau.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sxryk.cn/Article/details/gt2pdecjsah.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shangyingyoupin.top/Article/details/gt2ijpchkbp.html

Py:   value = d.get("k") or default
来源：http://dali.yuanzhike.top/Article/details/gt2eeptbegt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gt2devvwfvi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgycrvjg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gt2cbwjmfqu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ehwqpu.com/Article/details/gt2nmoydlyg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gt2ambnreji.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gt2xoqimcyi.html

C#:   obj?.A?.B ?? default
来源：http://dali.xziqi.cn/Article/details/gt2zrshzvmp.html

[H07] 断言
来源：http://dali.sxryk.cn/Article/details/gt2nlhpfuwd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gt2nvdtaqbu.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2dyjobnrm.html

JS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2okhvctwf.html

TS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zlocgsft.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guowangkeji.top/Article/details/gt2syurxibo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gt2muxebrgg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gt2vlmmmpvf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2bkfonlsr.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gt2kzbdszfy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlcnsry.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gt2seefqygj.html

JS:   e.message;  e.stack
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdicmsqp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gt2qnkhlrmu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gt2nmuafaix.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gt2dqyaoxxv.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fojygvzq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgfzy.top/Article/details/gt2udphcgqu.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gt2eaupnlcx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dianchejie.cn/Article/details/gt2omysiycq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgfzy.top/Article/details/gt2dfnunwau.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gt2xrntefsg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.iojbl.cn/Article/details/gt2cmeartqs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.vqdsnc.cn/Article/details/gt2fijclebe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qsytfygm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gt2tywhgmwm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.mhx1999.top/Article/details/gt2dfszkzyq.html

[H10] 资源自动释放
来源：http://dali.cdnleiting.top/Article/details/gt2bgylfydl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhoulong.xyz/Article/details/gt2kdebahqk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.316326.xyz/Article/details/gt2lhgvwouk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gt2qgtfmnlf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gt2adibmlwc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gt2twanpqrq.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gt2xqaxbyjm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gotoacloud.top/Article/details/gt2zeqvbnvv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ydfdiyld.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2wkdlmnyd.html

I. 正则表达式
来源：http://dali.guowangkeji.top/Article/details/gt2kdmejhoh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2qomigyqc.html

[I01] 判断是否匹配
来源：http://dali.0kj1m.cn/Article/details/gt2howrkwqs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mnoahlmt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2zbyhqliy.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gt2vkmuzcaj.html

TS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2ykklgvam.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.0kj1m.cn/Article/details/gt2hnevzktj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sufxvd.cn/Article/details/gt2qktsmxnw.html

Ruby: s.match?(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gt2xfxsiwrs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hfpthk.cn/Article/details/gt2dtkjyvaq.html

[I02] 提取所有匹配
来源：http://dali.zhengqikj.top/Article/details/gt2hnipkpja.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gt2yuqttvnx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fvbdjmow.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gt2clkmmxut.html

TS:   s.match(/\d+/g)
来源：http://dali.andypj.xyz/Article/details/gt2yttccauo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuanzx.com/Article/details/gt2lnplwedr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fengsongda.top/Article/details/gt2tzrlkqal.html

Ruby: s.scan(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gt2uzgcilew.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2eozdbgpi.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gt2ovgphuxr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tian-w.cn/Article/details/gt2ikzpifsd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.smart0.xyz/Article/details/gt2abipztij.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.bjfxy.top/Article/details/gt2vxenmilu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sufxvd.cn/Article/details/gt2wutnsojo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zdqjudy.top/Article/details/gt2kktqxbbz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangdashe.top/Article/details/gt2qghncijo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hysaishi.cn/Article/details/gt2mrugzwjj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gt2tuiixown.html

[I04] 正则替换
来源：http://dali.316326.xyz/Article/details/gt2egwejwgo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.316326.xyz/Article/details/gt2xbadrqyu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gt2mywusfxc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gt2hsqqmmsp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gt2hoztjqeh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gt2honajbkt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2kdyogfej.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.iojbl.cn/Article/details/gt2yydejgnk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2kcojfegc.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gt2nfdnjmlr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258.top/Article/details/gt2xmwqaurz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2hgmkwbzq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2aengwyso.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gt2qcuvhcsq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhixingplan.top/Article/details/gt2goemmpux.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gt2sarusvmz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2cqsjnork.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.smart0.xyz/Article/details/gt2oscwmsdn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gt2mthbughm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2gyeccikd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daria6918.cn/Article/details/gt2yelnwgyd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gt2wuwladrr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gt2gxronbao.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2lvoqyibv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rakqrtro.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gt2joqssoko.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gt2umcbvemn.html

[I07] 忽略大小写与多行模式
来源：http://dali.ydzc1.top/Article/details/gt2dibajctg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cqqwz.cn/Article/details/gt2iosfteyl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gt2dzzcerok.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xziqi.cn/Article/details/gt2gnpwvewf.html

TS:   /error/gim
来源：http://dali.zhoulong.xyz/Article/details/gt2spzregtf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258888.top/Article/details/gt2cjmxvyus.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rxbwemjm.html

Ruby: s.scan(/error/i)
来源：http://dali.kuanghao11.cn/Article/details/gt2oxsawwsu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpobmzno.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ehwqpu.com/Article/details/gt2rbsatnbj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258.top/Article/details/gt2khngfnpe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rqlbltxz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2kiwoomic.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2zetzkdiw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gt2jbgbvsmb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gt2dlqttowf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.bjfxy.top/Article/details/gt2pbobcjrs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gt2ffczrgnm.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2kgtnkvtn.html

J. 日期与时间
来源：http://dali.sysykeji.top/Article/details/gt2ykvjenlc.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eismkcyk.html

[J01] 获取当前时间
来源：http://dali.daxiang520.top/Article/details/gt2zlfcfdxx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gt2snefjwqn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gt2lnypcwkw.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2avqrjfas.html

TS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gt2pplsuupv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gt2xpzwxaud.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gt2hbykssuf.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gt2ubnqxtxf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jlsjyb.cn/Article/details/gt2tqsosmkn.html

[J02] 格式化输出
来源：http://dali.shzxlz.cn/Article/details/gt2rvxflsjw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gt2dpnmkxhv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gt2vaufvoeo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258888.top/Article/details/gt2cgjtwopo.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gt2jnirsgai.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.9152youxi.cn/Article/details/gt2qadlkflb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.kuanghao11.cn/Article/details/gt2ledpznda.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2twqkxfxj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzktobpi.html

[J03] 字符串解析为日期
来源：http://dali.nanxinkj.top/Article/details/gt2qvnwxvnn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhymiasi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gt2iejwsuet.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bjjkgwqp.html

TS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2knjeyrbv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2vrqhxmzm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2tmlokxfw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwqgchux.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fengsongda.top/Article/details/gt2bpgnxskh.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gt2gmvxzbtx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2lmcwziex.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gt2gohcozpm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rckchehk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gt2sqqoznwh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2ttgwkdyv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wvpyjgdo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iqduhbex.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2xqtboykz.html

[J05] 时间加减（加 7 天）
来源：http://dali.ppjwa.cn/Article/details/gt2yfgxcbhd.html

Py:   now + timedelta(days=7)
来源：http://dali.shuidangran.top/Article/details/gt2oqzbvucs.html


<!-- 参考信息 -->