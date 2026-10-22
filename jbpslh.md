代发 wailian999

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2cbhtmixx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenlongwang.top/Article/details/gt2wurkdatw.html

Ruby: class Admin < User; end
来源：http://dali.nanxuanxn.top/Article/details/gt2deucnbkx.html

C#:   class Admin : User {}
来源：http://dali.fengsongda.top/Article/details/gt2hbmziabe.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gt2olslpwng.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gznmuwlf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2fqtahtep.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2jgbyvwnv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2vchopdfe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxogbaic.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gt2epypsyyl.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258888.top/Article/details/gt2ubbnyoku.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gt2bqzasddt.html

[G07] 调用父类方法
来源：http://dali.cashguo.top/Article/details/gt2cikdlnev.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gt2ubzivrdu.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gt2oyyacbgm.html

JS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gt2wtsowhlv.html

TS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2ckrrtyle.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2pglejzjv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gt2rbbjkhij.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gt2jtazcyxe.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gt2kzecpixv.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gt2gymbufao.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dashuyun.cn/Article/details/gt2tttgpjrl.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2enoznkih.html

JS:   static f() {}
来源：http://dali.guowangkeji.top/Article/details/gt2wccfdbpp.html

TS:   static f(): void {}
来源：http://dali.yuxming.cn/Article/details/gt2btbjqklb.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gt2sojpradk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gt2wadmkuyx.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gt2yfwokein.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gt2qxuixtim.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258888.top/Article/details/gt2giygedvy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zycfv.cn/Article/details/gt2ginarbhs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2egdixjpb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gt2boclrrhd.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gt2xlfuebkb.html

Java: interface Shape { double area(); }
来源：http://dali.pycfn.com/Article/details/gt2rxbnfbmj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gt2rvamsqrx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gt2ledjweol.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhixingplan.top/Article/details/gt2trlyrzrb.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gt2wlusglhz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aizwys.cn/Article/details/gt2ybgbmpuz.html

PHP:  public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gt2ekowbieq.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gt2hwmpkwhu.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2azxtbdjb.html

Java: public / protected / private / 默认包级
来源：http://dali.hnxiangtu.top/Article/details/gt2beagwrus.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gt2mytkaksw.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2mzkuonzo.html

C#:   public / protected / private / internal
来源：http://dali.yonumen.top/Article/details/gt2larjkflr.html

[G11] getter / setter
来源：http://dali.pengpengdd.cyou/Article/details/gt2ykmpbszh.html

Py:   @property 与 @x.setter
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnawxcix.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2tdupuwor.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2jedkilyj.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2hpzwesmg.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2aidqfxgk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gt2leyoragf.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gt2tyeabkjw.html

C#:   public string Name { get; set; }
来源：http://dali.sufxvd.cn/Article/details/gt2inmcubve.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gt2izhytjdm.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gt2gyfdgozm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2wlcxnktc.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2nqsmlrtm.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2aqysnqiw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2qfyboobk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gt2wwixkcwu.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2npkvvdtw.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gt2gisduxuc.html

[G13] 判断对象类型
来源：http://dali.shuidangran.top/Article/details/gt2axikxsui.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ptujamzf.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2qdkqvyfr.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2nnohqoeb.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2cnjshfxv.html

Java: u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2meciuvxn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srsiocio.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gt2qfknuszh.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gt2lvogxbpd.html

[G14] 数据类 / record
来源：http://dali.hnxiangtu.top/Article/details/gt2kksyhppt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yongpay.top/Article/details/gt2pocphnqz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gt2fvxrhllr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gt2frnlnsqq.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258888.top/Article/details/gt2sdhzfzwa.html

Java: record User(String name, int age) {}
来源：http://dali.guowangkeji.top/Article/details/gt2haqvtdxb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gt2mrpxfooe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gt2olqskigw.html

C#:   record User(string Name, int Age);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nugylces.html

[G15] 枚举
来源：http://dali.yvedp.cn/Article/details/gt2qvmfqvwi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gt2zqkxfrtg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxkyhwta.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gt2ldpskxbd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wisuflif.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwqeykfm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gt2nlmkzgqk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuxming.cn/Article/details/gt2pwzjxvqp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gt2xiyhsotv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhixingplan.top/Article/details/gt2umfjvkob.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gt2fzzjckdl.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gt2svyihwnc.html

JS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gt2pexreeus.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gt2ccvyolzu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenzaomai.com/Article/details/gt2ufnqdlvg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gt2fmikvfnr.html

Ruby: obj.instance_variables
来源：http://dali.xuetiantiany.cn/Article/details/gt2hfixpnzb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gt2hjibpqmz.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2phnnzjeq.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gt2ccafkvhc.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2bsawzcdf.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gt2obwgixia.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gt2butwwzoa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gt2erjqjedo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gt2xutuyvsk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gt2grjgvcxe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gt2silnnorv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gt2mqfxrmyq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkruwuj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xufqlerx.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gt2ymdncqcn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gt2niprzwjk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2zwjtydqh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2cvvscrbb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2eygvvnfv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qyqnqdmz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gt2ryaujtei.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2ahoyhuyj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2jlklddui.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jntytfmq.html

Py:   raise ValueError("错误信息")
来源：http://dali.cqqwz.cn/Article/details/gt2ykxpvxcb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vsyvqiby.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2cnaafhry.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2snmtmgwl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2bywojipn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gt2cdiptmuq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oategtvm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2ntwozboh.html

[H04] 自定义异常类型
来源：http://dali.smart0.xyz/Article/details/gt2lcxvdoce.html

Py:   class MyError(Exception): pass
来源：http://dali.0kj1m.cn/Article/details/gt2jfgriapf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gt2bsjqyulu.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gt2pzsyjmlv.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fflaaokh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gt2tnacscye.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gt2raulucsz.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gt2fvbwtclk.html

C#:   class MyException : Exception {}
来源：http://dali.gaohongyu789.top/Article/details/gt2zmzpxqqe.html

[H05] 捕获特定类型
来源：http://dali.sxryk.cn/Article/details/gt2fjtwkzvj.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gt2pfqfumru.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258.top/Article/details/gt2hcqreivu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gt2tqeuprfu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gt2clkudnnq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2meqcddyx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gt2xqnjnmrs.html

Ruby: rescue ArgumentError => e
来源：http://dali.kuanghao11.cn/Article/details/gt2swizilop.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awtttayi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gt2iuoqkavp.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gt2dcmymxeg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gt2koelgljj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gt2lkxuagag.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gt2dempdqnj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.0kj1m.cn/Article/details/gt2hfdlwhwe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gt2hvwyloju.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cqqwz.cn/Article/details/gt2ynwvbofb.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gt2fomoeubn.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gt2xwotivli.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2axymjszk.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2dcclnpaq.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fafscnzj.html

TS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2nxevfgjb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.bjfxy.top/Article/details/gt2gbyysbrg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gt2bmlycwqp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tianlin.xyz/Article/details/gt2jcawpboj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2xofntecz.html

[H08] 获取错误信息与堆栈
来源：http://dali.birdmap.top/Article/details/gt2nzoofxyc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yongpay.top/Article/details/gt2yiixxrvd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gt2wczrulhc.html

JS:   e.message;  e.stack
来源：http://dali.dashuyun.cn/Article/details/gt2tabdoapp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gt2xqvkmyok.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ltisygtf.html

Go:   err.Error()
来源：http://dali.hfpthk.cn/Article/details/gt2vbwlzcyq.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gt2oqfhvkjf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gt2yocyxaht.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gt2iqjdmgnw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gt2undqpbpl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhongyouzk.top/Article/details/gt2aeyjcfun.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hywenlv.cn/Article/details/gt2pozbaktj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.smart0.xyz/Article/details/gt2daovajqa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwshbdal.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gt2wptfifut.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gt2lvlfgdid.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gt2xofunsio.html

[H10] 资源自动释放
来源：http://dali.dashuyun.cn/Article/details/gt2oypwokst.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gt2udmkmnor.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qqlupkth.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gt2npsxhhjy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gt2tawvzgia.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.kuanghao11.cn/Article/details/gt2ltgxvrcp.html

Go:   defer f.Close()
来源：http://dali.pengpengdd.cyou/Article/details/gt2eefomcaj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gt2yvetuewv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2fgjlskgk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2okuybkfv.html

I. 正则表达式
来源：http://dali.havefunace.top/Article/details/gt2tnufwati.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2mslfpela.html

[I01] 判断是否匹配
来源：http://dali.jiagoushi.top/Article/details/gt2zcdbehqw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2lafcgslj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2wnjpngzc.html

JS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2xtaqbxhx.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gt2zatmqwfq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.haohaochexian.top/Article/details/gt2ehhiuplx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cucudq.cn/Article/details/gt2ahwlmvel.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gt2rjvwairj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gt2axlbrxkf.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gt2evdtpnhb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gt2eetlmblj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xylfe.cn/Article/details/gt2mpgnliwg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gt2jnqwrjqm.html

TS:   s.match(/\d+/g)
来源：http://dali.meibo888.top/Article/details/gt2ewikmiye.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2ggllhnpc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.birdmap.top/Article/details/gt2lvfgssvc.html

Ruby: s.scan(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kjhqygmh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zgyfnxft.html

[I03] 提取捕获分组
来源：http://dali.meibo888.top/Article/details/gt2yfzuhjvk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2fdwoyhcs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gt2aldnqdep.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aizwys.cn/Article/details/gt2zdbctqbs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.quarkkingdee.top/Article/details/gt2itqprutu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj202588.top/Article/details/gt2eckzezjw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.9152youxi.cn/Article/details/gt2ylmpuekt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gt2dvdyrbpf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenjidiqi.icu/Article/details/gt2cqcclqwm.html

[I04] 正则替换
来源：http://dali.sufxvd.cn/Article/details/gt2wbfzgeqd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxzratef.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2vtdzcgac.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gt2wkdujfar.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thxtjmmz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pycfn.com/Article/details/gt2qcirzxcm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gt2bymhoopl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2iqqggiwa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ivvv.top/Article/details/gt2qxknqrxk.html

[I05] 按正则拆分
来源：http://dali.aizwys.cn/Article/details/gt2hutbxvnq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2grnxxiph.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2wursdtkn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gt2yxhetkqr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gt2sznfqiib.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hysaishi.cn/Article/details/gt2wivleino.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gt2auqpbukx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gt2hwzoauzi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hfpthk.cn/Article/details/gt2cltxqlvx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2korosaeg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2xuydltyw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258.top/Article/details/gt2xjfptfgr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gt2zvcnbrhi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gt2syfzrlcc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gt2lhmxopdz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.bjfxy.top/Article/details/gt2isrzeiyf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yueranfly.top/Article/details/gt2ijflohhe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gt2snyctfwn.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gt2htvqlumr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gt2kgxtvrzu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmbiiaeo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2gppwrpsj.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gt2ygptxwcm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vieewgmj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gt2bujaloye.html

Ruby: s.scan(/error/i)
来源：http://dali.316326.xyz/Article/details/gt2uryycflm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxuanxn.top/Article/details/gt2ldnguahw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hfpthk.cn/Article/details/gt2ffvbkwzv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnqzz.top/Article/details/gt2yybqlsit.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gt2ogybqvnf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gt2bzffwvrr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wksjpjlt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gt2mumlbcno.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shzxlz.cn/Article/details/gt2lllepwsi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.bjfxy.top/Article/details/gt2qxnnglmr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gt2gbhczbfm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ckpgmxnq.html

J. 日期与时间
来源：http://dali.hnxiangtu.top/Article/details/gt2ljgqyyov.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2qhceolbm.html

[J01] 获取当前时间
来源：http://dali.yuanzhike.top/Article/details/gt2hkkgyxnd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhixingplan.top/Article/details/gt2smvwtqof.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gt2gsowiiwp.html

JS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gt2bryxwwru.html

TS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gt2vextmjew.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tianlin.xyz/Article/details/gt2lwsrdhmm.html

Go:   time.Now()
来源：http://dali.nwbrower.top/Article/details/gt2qxuafzbw.html

Ruby: Time.now
来源：http://dali.nwbrower.top/Article/details/gt2blemsuxp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.iojbl.cn/Article/details/gt2fgvlwgrs.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2sogyumok.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jflwduwe.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gt2rmbslhpw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sismidzn.html

TS:   d.toISOString()
来源：http://dali.yj202588.top/Article/details/gt2zbmrroyj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tian-w.cn/Article/details/gt2pjefxabq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yvedp.cn/Article/details/gt2rrhxitfc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gt2yrmkwies.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gt2jjdcarux.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gt2wxaidxdy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gt2gbxocehf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gt2xgfrhnvp.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2joowfjxh.html

TS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2dekwfegy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2nwtkoegl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2jcugnfhy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2uhajeeju.html


<!-- 参考信息 -->