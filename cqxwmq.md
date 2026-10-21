代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gtyndmyqmv.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gtzsihznao.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gtploymyvo.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gtdtimylaf.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtuepdngee.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtvjgsxqts.html

Java: super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtzxbkxjec.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gteyueghew.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gtwdzoelhk.html

C#:   base.Greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtcwfbocez.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtorddxqhn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.vqdsnc.cn/Article/details/gtnkgfscfy.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtehfywpen.html

JS:   static f() {}
来源：http://dali.0kj1m.cn/Article/details/gteeqtcayx.html

TS:   static f(): void {}
来源：http://dali.tianlin.xyz/Article/details/gtyxhtpbdh.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gtdgmbtgqu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hywenlv.cn/Article/details/gtzcjyecej.html

Ruby: def self.f; end
来源：http://dali.xuetiantiany.cn/Article/details/gtzzazikqz.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gtbclqzriw.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gthigqehag.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ehwqpu.com/Article/details/gtiuchwxyy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gtrhdvxywc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gtlajqkpgo.html

TS:   interface Shape { area(): number; }
来源：http://dali.hongshengwenyu.top/Article/details/gtuqavwvqh.html

Java: interface Shape { double area(); }
来源：http://dali.aibaodan.cn/Article/details/gttlkqlnso.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gtgihktjcn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gtixqkzfue.html

C#:   interface IShape { double Area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtpvhsuunc.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gtfaoacqkr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtzprqybgf.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtvhhiepxi.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtahgjysif.html

TS:   public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtmghbeklg.html

Java: public / protected / private / 默认包级
来源：http://dali.316326.xyz/Article/details/gtovdkegkq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gtgcghpqqm.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gtnosfohas.html

C#:   public / protected / private / internal
来源：http://dali.316326.xyz/Article/details/gtzucqdgts.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gtidyxopwy.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gtugqcxsze.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gttvhjzbfr.html

JS:   get name() { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtflhmeiqd.html

TS:   get name(): string { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtmftojmqc.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtopgjfdec.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtmavhdibl.html

Ruby: attr_accessor :name
来源：http://dali.mhx1999.top/Article/details/gtvopxmkpc.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtzlbmrljr.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtosztpwsx.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtnuijsapp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtzpftghdz.html

JS:   toString() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtlkhlysib.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtfsnqggro.html

Java: @Override public String toString() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtxweflmui.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtjflzbkwx.html

Ruby: def to_s; @name; end
来源：http://dali.xuanzx.com/Article/details/gtojmhgrol.html

C#:   public override string ToString() => Name;
来源：http://dali.nwbrower.top/Article/details/gtijfbitib.html

[G13] 判断对象类型
来源：http://dali.yj20258.top/Article/details/gtrzxfnvnt.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gtqzlndnal.html

PHP:  $u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtorkpaunz.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtdjofqmfi.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gturbwqmsa.html

Java: u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtozftpyqb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gtytxvzout.html

Ruby: u.is_a?(User)
来源：http://dali.hnxiangtu.top/Article/details/gtdltklewz.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gtjttrmalg.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gtagcvegty.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gtgjoytkka.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gtkchbjuaw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangshuangyany.cn/Article/details/gttstqhyia.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxuanxn.top/Article/details/gtrprkpcma.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gtzravband.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sxryk.cn/Article/details/gthmxohnjg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gthzeukufm.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gtekwhpibz.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gtvmtadijp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gtvmoocidt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sufxvd.cn/Article/details/gtfbpweblk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gtrybotxcv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtqukfpqeg.html

Java: enum Color { RED, GREEN }
来源：http://dali.ydzc1.top/Article/details/gtdtezokhd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gtxiweztrk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gtmenjqckj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbsywovir.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gtwfgfgxxj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dashuyun.cn/Article/details/gtcjvwwztk.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gtdencxqon.html

JS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtjqwtyfow.html

TS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtvwovzlqp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.birdmap.top/Article/details/gtjmxthpph.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gtedfzmqyj.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gtgnqwkqkl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtavuiqwig.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxqmuauef.html

H. 异常与错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtvsyjxdgz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqszchnsb.html

[H01] try / catch 基础
来源：http://dali.fengsongda.top/Article/details/gtymvbyupt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gtcasuxmjh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gtaipyfsau.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtqmkqdjaw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtuqcsjwtx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenlongwang.top/Article/details/gtlkxtgdfq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gtfaukjizj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gtisdiidsh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gtyxkwwtxu.html

[H02] finally / ensure 收尾
来源：http://dali.fengsongda.top/Article/details/gtyurjqgjs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shuidangran.top/Article/details/gtrhgvzmhj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtoattcdko.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtiwvpfsje.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtnfkhjwwt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtqkanyvzw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gtjityzikl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gtbfpprqhg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtsmawufqg.html

[H03] 主动抛出异常
来源：http://dali.zhixingplan.top/Article/details/gtgeyrarvw.html

Py:   raise ValueError("错误信息")
来源：http://dali.sufxvd.cn/Article/details/gtoukylvpp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtnsymyqti.html

JS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtxavasfdy.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtnmgnfluv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhgzxwyg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gtjhojeidf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gtkkyvquxv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtyoovnxrt.html

[H04] 自定义异常类型
来源：http://dali.feifeiyinyue.top/Article/details/gtaykhtzxx.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gtqislvwcq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gteqmneaoe.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtoxhtfxgg.html

TS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gttesxdwhe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gtrojnkqen.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yongpay.top/Article/details/gtdcmiqgxp.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuanzx.com/Article/details/gtulyrplth.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gtqezbusme.html

[H05] 捕获特定类型
来源：http://dali.chenzaomai.com/Article/details/gtxjksyatz.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gtworgvbmc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shuidangran.top/Article/details/gtmlxluiyn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtmglibndk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtipzydcyk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgufenzy.top/Article/details/gtunjddcjs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hongshengwenyu.top/Article/details/gtlkvnnvhk.html

Ruby: rescue ArgumentError => e
来源：http://dali.0kj1m.cn/Article/details/gtkyydhthl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gtwcsrfmcs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jyoumei.cn/Article/details/gtrfapqeoq.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gtfmzkkotf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtpumhnktr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gthkjqpfcg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtmbjommck.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gtpnhhrjni.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ydzc1.top/Article/details/gtihynnxcu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aibaodan.cn/Article/details/gteynxmjye.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gttyobvjsg.html

[H07] 断言
来源：http://dali.pengpengdd.cyou/Article/details/gtxaqtwopo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gtgfvcwyyr.html

PHP:  assert($x > 0);
来源：http://dali.yuxming.cn/Article/details/gtrruipnee.html

JS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gttmknguhz.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtovybipob.html

Java: assert x > 0 : "必须为正";
来源：http://dali.redwolf501.top/Article/details/gtiltixvkr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gtpyqptsih.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gtsziehjvv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtprpvfrhj.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtdaqkuxzg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gtczmmngbg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtodvtsmbe.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gtwgxgwsqj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gttcmilrvw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.mhx1999.top/Article/details/gtgcwhqdqj.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gtgctgliua.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gtyznloxtc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yangfankeji.com/Article/details/gtoxitiwkj.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gtjmrtmghm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gtzbbrlfdl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtrjgcpivx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yanxiufei.cn/Article/details/gtnbmrggqz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.svipenyu.cn/Article/details/gtdyhuoqns.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gtpuonaoyp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtbwfyjksf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ydzc1.top/Article/details/gtbwvjouog.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gtdvlcvhpg.html

[H10] 资源自动释放
来源：http://dali.pycfn.com/Article/details/gtortjhshf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.quarkkingdee.top/Article/details/gtckwypddh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gtbibchpeb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gthocmxcuh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtwqwygufz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gtntijpdcf.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gtzzjnpjqp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuetiantiany.cn/Article/details/gtgnotoihx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pycfn.com/Article/details/gtxaetcktl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtovdfrdnq.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gtbhjateok.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtgzivxkqg.html

[I01] 判断是否匹配
来源：http://dali.yvedp.cn/Article/details/gtjbumocgy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtwvtwcznl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cashguo.top/Article/details/gtijhxnwfx.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtlyfopuso.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtlaldturl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpttvfue.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.mhx1999.top/Article/details/gtdgbjnppb.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjmmtlas.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.smart0.xyz/Article/details/gtcvstyekz.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjzqsjwp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtdidloioa.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gthqjpzbwp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gtfybnyoyv.html

TS:   s.match(/\d+/g)
来源：http://dali.chenzaomai.com/Article/details/gtkrgdopyj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zycfv.cn/Article/details/gtkkqkvboe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtrwiztxki.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtzcevptce.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gtiswxeekf.html

[I03] 提取捕获分组
来源：http://dali.redwolf501.top/Article/details/gtjzetqcow.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gtbwmalcpk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gogol.net.cn/Article/details/gtilsqqetk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guannengcc.top/Article/details/gtysdtdpui.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gtnojgugtn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zycfv.cn/Article/details/gtoomhtckq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ybcxt.top/Article/details/gtwytqhtqz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gtchfnmtco.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gtlafwmiss.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gtfaddqciw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.vqdsnc.cn/Article/details/gtiddydiwt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtrkisyusn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtqnzabaid.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtiuejkgss.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtkiqrcrpe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gteqjizvta.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jianghu66.top/Article/details/gtaiabvfzf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtpbidvzqt.html

[I05] 按正则拆分
来源：http://dali.smart0.xyz/Article/details/gtjwbqxzll.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuxming.cn/Article/details/gtibtjbzpp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivmaslrx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtiyqblsrr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtxwrrekho.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yangfankeji.com/Article/details/gtkrtbhwpt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtrxbfuffq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtazexcnmd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gteunzkael.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gotoacloud.top/Article/details/gtjkzzjmrz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtoanmqqit.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gtrmpsfwqi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtgoilerhp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gtsaygwyfr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtpzskwlsn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gtnaverdkt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gtwfejlrtr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtbnobkoif.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenlongwang.top/Article/details/gtzjfonxoi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shzxlz.cn/Article/details/gtciifjvdh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtcnilrlgv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ehwqpu.com/Article/details/gtcierufiw.html

TS:   /error/gim
来源：http://dali.fzhhl.top/Article/details/gthvqppnaq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gtyepfxqha.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.c1oappe.top/Article/details/gtgkwchjwm.html

Ruby: s.scan(/error/i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlcrwexq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangdashe.top/Article/details/gtwvprewyk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yueranfly.top/Article/details/gtggxtxyxt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gtcbrlnggw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtizwhbqdm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gtraajnchx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gttxxhrdkb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gtfyezuodk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnppdwce.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gtjpbmvryo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgcmoiko.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxaxniibo.html

J. 日期与时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gteksyskvg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtlbcyideg.html

[J01] 获取当前时间
来源：http://dali.guowangkeji.top/Article/details/gtzusaleqe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.smart0.xyz/Article/details/gtzpptboye.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gtvrhlnagt.html

JS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtfbztpvpx.html

TS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtqoiomxsi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjifrfqd.html

Go:   time.Now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkwelvpm.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gtowqlhofj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gtuvrumkhw.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtgoxtxozh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtackfggfs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqznvqdvj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhoulong.xyz/Article/details/gttobekbkd.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gtwusikcaj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gotoacloud.top/Article/details/gtcllsjldu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hywenlv.cn/Article/details/gtwpfcezts.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtlfehjxqp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.havefunace.top/Article/details/gthdbhivmk.html

[J03] 字符串解析为日期
来源：http://dali.xziqi.cn/Article/details/gtyjkqmztk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gtryazjqlg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gtzzkdwoul.html

JS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtbbnariqk.html

TS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gttxhmkedj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtngvyhwld.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwscmwcld.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtajrllfat.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258888.top/Article/details/gtcybgcbjt.html

[J04] 时间戳与日期互转
来源：http://dali.gzhubu.top/Article/details/gtrlbgzupu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tianlin.xyz/Article/details/gtszojsuyp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jianghu66.top/Article/details/gtgknqlhvy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gtgdcmtivo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtzjrhywck.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.havefunace.top/Article/details/gtpqlkarha.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.c1oappe.top/Article/details/gtxfjerdly.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtfydtwqkd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtgfaqusdq.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gtcvzlrqws.html

Py:   now + timedelta(days=7)
来源：http://dali.smart0.xyz/Article/details/gtzjvhihgu.html


<!-- 参考信息 -->