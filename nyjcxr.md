代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2bwkaexsh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xdumrxgc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gt2bwzglxjf.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gt2gpagnflz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gt2rqfhrqhr.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gt2tflirqxk.html

Py:   super().greet()
来源：http://dali.daxiang520.top/Article/details/gt2ukfuzoxi.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gt2rmfrmwpl.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gt2lkmcqozl.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gt2ucieuzkt.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnbjxyag.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gt2gwrrsgdd.html

Ruby: super
来源：http://dali.gotoacloud.top/Article/details/gt2eawnzkjg.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2rhcusmks.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gt2eygjjfzp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenzaomai.com/Article/details/gt2qkswsvcx.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gt2alfrltda.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2roknesdt.html

TS:   static f(): void {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tboywoiw.html

Java: static void f() {}
来源：http://dali.pycfn.com/Article/details/gt2jpooakaf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gt2gzilltor.html

Ruby: def self.f; end
来源：http://dali.ybcxt.top/Article/details/gt2emeexknw.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gt2iskjcjgw.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gt2xwlerfgs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jyoumei.cn/Article/details/gt2fhoqaqqt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.bjfxy.top/Article/details/gt2scgjkwif.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.quarkkingdee.top/Article/details/gt2kompsfde.html

TS:   interface Shape { area(): number; }
来源：http://dali.nwbrower.top/Article/details/gt2vnyqgslh.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2adrxnndn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbzcczqc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptibzgax.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gt2vtpbsicm.html

[G10] 访问控制
来源：http://dali.c1oappe.top/Article/details/gt2pjgyoart.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xziqi.cn/Article/details/gt2onuxzxnm.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2mnmuysdl.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gt2yfdpzgfp.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2xffeftvd.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gt2akadxuuz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tian-w.cn/Article/details/gt2napbueho.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2wykejxpz.html

C#:   public / protected / private / internal
来源：http://dali.yanxiufei.cn/Article/details/gt2vfogzqcf.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gt2ghvijsuf.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gt2irrqahth.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnakcyly.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2hqysmiza.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gt2nxohhdio.html

Java: public String getName() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2rbxqmxij.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2dpuuvvft.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gt2bmatybfs.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigufen.top/Article/details/gt2betkpjpl.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gt2pzymykru.html

Py:   def __str__(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gt2bxfpbnwf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2tjcaoklz.html

JS:   toString() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2wfiueyyj.html

TS:   toString(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2jnqgvdqa.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2oclfknhq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gt2xvqkvqwk.html

Ruby: def to_s; @name; end
来源：http://dali.ydzc1.top/Article/details/gt2gekofcab.html

C#:   public override string ToString() => Name;
来源：http://dali.nwbrower.top/Article/details/gt2aivcperz.html

[G13] 判断对象类型
来源：http://dali.gogol.net.cn/Article/details/gt2umvygvgs.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gt2nhmrzzkn.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2bmrifcwi.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zldtbaov.html

TS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2ujhxfodq.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2jbecdust.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gt2bcbtutyc.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258888.top/Article/details/gt2ggcajwhk.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gt2wrrwvypy.html

[G14] 数据类 / record
来源：http://dali.xuanzx.com/Article/details/gt2jrfjyxrt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gt2cvbeioyu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gt2tpfcpsbs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yangfankeji.com/Article/details/gt2uxoninud.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnqzz.top/Article/details/gt2cpaauzwl.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gt2ypeywrci.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gt2knbahrug.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuxming.cn/Article/details/gt2hyffpoqk.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gt2jgrqikbv.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oucgufmw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gt2qqvjzhlg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gt2yfgbzvsu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gt2kvlkakpm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gt2infiethh.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gt2ohhfzaep.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnxiangtu.top/Article/details/gt2sfnefxrq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gt2kvfkjvzo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gt2vaabmptd.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gt2jfgqyihw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gt2otdgorpw.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2boykubjd.html

JS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gt2tdcobcjw.html

TS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2letxmqlw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gt2vhxpqydy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qonvriwv.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gt2sskjblck.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gt2znjnnzer.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2wfxojgzk.html

H. 异常与错误处理
来源：http://dali.birdmap.top/Article/details/gt2xwgdbzwg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2vcavsurh.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gt2sasdcmmg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lroxuoki.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gt2uutmjbwj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gt2ibtxeczc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2fiwzytth.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gt2nuxyefsf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gt2dohuzlrt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gaohongyu789.top/Article/details/gt2kjbuwycs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yueranfly.top/Article/details/gt2dumjggnn.html

[H02] finally / ensure 收尾
来源：http://dali.aizwys.cn/Article/details/gt2kjvmtjct.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gt2hkfjvzis.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2coasopsl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2mpwrhfcv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2jxqgnzqa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2nxqwrqkk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nissljpw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2czvnqyxi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2nclkkhui.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gt2meqrlxbq.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gt2enchyahp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2lnieqsux.html

JS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2siyggyob.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2vanwdaad.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2wnozvvqk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gt2ebxyffjd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gt2tjqrfvvb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2owiwueeu.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gt2kszzumjp.html

Py:   class MyError(Exception): pass
来源：http://dali.yongpay.top/Article/details/gt2cwdnsirb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gt2yyjgnkvs.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gt2ahawydmk.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gt2azocvzbw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gt2bxgrchex.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gt2nohzygxk.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhengqikj.top/Article/details/gt2pdluazkc.html

C#:   class MyException : Exception {}
来源：http://dali.shuidangran.top/Article/details/gt2jdwremaa.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gt2qpoyvcge.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gt2bxzmvezw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gt2axhyicmx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2drtuibpo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gt2vtqumemp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.snrcjt.cn/Article/details/gt2kexegkns.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gt2cisuytsn.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gt2guzwkvnw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258.top/Article/details/gt2zqbhetsd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gt2idwcyhur.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gt2romusfdb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gt2vxarcpdt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gt2ugvpsiyu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2ehmvelmm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gaohongyu789.top/Article/details/gt2yjwisebh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gt2tlsshpsg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2aweiiwmn.html

C#:   obj?.A?.B ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2gugkqucb.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gt2issqfcpx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gaohongyu789.top/Article/details/gt2jpqvyvbo.html

PHP:  assert($x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2lfmzzknh.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2tlqrrdlh.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2rubgpjxc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gotoacloud.top/Article/details/gt2pkaxzrjy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.svipenyu.cn/Article/details/gt2dignjdie.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrzyphby.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2ohjvspek.html

[H08] 获取错误信息与堆栈
来源：http://dali.cdnleiting.top/Article/details/gt2gkfejylk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuetiantiany.cn/Article/details/gt2dqymihyc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.0kj1m.cn/Article/details/gt2qcabwwxj.html

JS:   e.message;  e.stack
来源：http://dali.dashuyun.cn/Article/details/gt2fmqbifaw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gt2zyqdornx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gt2olnoamkh.html

Go:   err.Error()
来源：http://dali.gaohongyu789.top/Article/details/gt2qjiywlpt.html

Ruby: e.message;  e.backtrace
来源：http://dali.dianchejie.cn/Article/details/gt2apdfzmad.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gt2pyoevwju.html

[H09] 带错误码的异常
来源：http://dali.cdnleiting.top/Article/details/gt2inemmstz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.0kj1m.cn/Article/details/gt2mebvloco.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hammf.cn/Article/details/gt2gnyxfnag.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gt2ixqsklkd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gotoacloud.top/Article/details/gt2dglnnala.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gt2kgtstsnb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gt2anjsztwv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxmmtqbw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnqzz.top/Article/details/gt2pnwbdkol.html

[H10] 资源自动释放
来源：http://dali.gzhubu.top/Article/details/gt2jcnwfmlh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuxming.cn/Article/details/gt2hwrkuito.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gt2nglwoqho.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gt2lzoxqxvg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gt2grwyptne.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.snrcjt.cn/Article/details/gt2mkpskexp.html

Go:   defer f.Close()
来源：http://dali.chenzaomai.com/Article/details/gt2ynhlmrfq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gt2ckizsljj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2ddopygjk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2dvhrcymg.html

I. 正则表达式
来源：http://dali.9152youxi.cn/Article/details/gt2jcarfrgd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2hqfhafmu.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gt2lqcjsava.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gt2cfacxmfk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2sdrjdokg.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gt2gfgqrzik.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxozzlfs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daxiang520.top/Article/details/gt2wxgpzgqq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2pysalnji.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwrtfuei.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gt2ateekfee.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2vklqkakj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2odczunfy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gt2tsrqrnqu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gt2dnfxdnzn.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gt2gseabcqh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jianghu66.top/Article/details/gt2laqdrsbr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gt2lmqiznxd.html

Ruby: s.scan(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mgqvnivn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yibvmhqq.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gt2uonkfmeo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xylfe.cn/Article/details/gt2mrqwismo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2egtsltxb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whnkpshh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gt2othaoutf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gt2fdsjwpyh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sysykeji.top/Article/details/gt2okqzoati.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.c1oappe.top/Article/details/gt2wnmsuujn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhongyouzk.top/Article/details/gt2gatolapd.html

[I04] 正则替换
来源：http://dali.guowangkeji.top/Article/details/gt2otybxpex.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhixingplan.top/Article/details/gt2ljoslrxj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2smdizrpk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2grfgqovc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2rlktrykz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2lvculteq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uephhcyb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2xlodomlb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gt2vimnjlyo.html

[I05] 按正则拆分
来源：http://dali.hywenlv.cn/Article/details/gt2cxvtqzvd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sufxvd.cn/Article/details/gt2pyjxfhnt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2brdgzcgz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gt2gjlapqix.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gt2fkujxdui.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gt2edomvtol.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gt2cratsxtx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gt2sbmgrrtx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vlphnkwf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.kuanghao11.cn/Article/details/gt2tgqlegjf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gt2tfstmwmy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj202588.top/Article/details/gt2rgnyavmi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gt2jcflbtay.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gt2eefcfdlq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2jatfrmhg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.smart0.xyz/Article/details/gt2metnlhfj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guannengcc.top/Article/details/gt2qpqvfava.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2arbpwnkf.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258888.top/Article/details/gt2lqlktlrv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gt2nerhhuur.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gt2hacxhzxb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gt2ansbzmpy.html

TS:   /error/gim
来源：http://dali.andypj.xyz/Article/details/gt2uwobgjkv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sweek.top/Article/details/gt2nuvldmny.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ydzc1.top/Article/details/gt2mopaaqhg.html

Ruby: s.scan(/error/i)
来源：http://dali.aizwys.cn/Article/details/gt2byoxvbza.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gt2zigpetzx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2apnezrck.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gt2njqrcuss.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gt2ckduzmrq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gt2keltefby.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gt2cgvgurgr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gt2ehsfkdkf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gt2ffbvfkzp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rzpfqwsj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gt2cuepftzp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gosvmszm.html

J. 日期与时间
来源：http://dali.hammf.cn/Article/details/gt2iqqoimod.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2mpqqbjmu.html

[J01] 获取当前时间
来源：http://dali.gotoacloud.top/Article/details/gt2mvzcswnd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aonykqgb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gt2retbzzza.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gt2ryqgwnhd.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2xmkxabjr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jyoumei.cn/Article/details/gt2lkvpuqyw.html

Go:   time.Now()
来源：http://dali.hnxiangtu.top/Article/details/gt2boxkpftg.html

Ruby: Time.now
来源：http://dali.chenlongwang.top/Article/details/gt2pyosiojm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tianlin.xyz/Article/details/gt2mxarwgnx.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gt2kqgqnszj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gt2wjbfveiq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gt2qgfvsgrd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yvedp.cn/Article/details/gt2hblyskqb.html

TS:   d.toISOString()
来源：http://dali.fengsongda.top/Article/details/gt2bnprcvko.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdugphvi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gt2otcqlmtu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gt2kwxasnym.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gt2yxyijtgq.html

[J03] 字符串解析为日期
来源：http://dali.snrcjt.cn/Article/details/gt2bddncmhj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tian-w.cn/Article/details/gt2bfjhsnyv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gt2uxjkpggc.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2sbpamrjz.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2rfuccbqo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2jjxjljur.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2dtraxmrj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2lovkvyyc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nwbrower.top/Article/details/gt2bjontxwq.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gt2nhuswgyw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gt2qorxyrbm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangdashe.top/Article/details/gt2rccxxtrl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gt2adkxhoiw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gt2dpdwxmvi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2rbdnpklq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gt2ncyzxzwz.html


<!-- 参考信息 -->