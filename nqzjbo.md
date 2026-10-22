代发 wailian999

JS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gt2evsqvknu.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gt2dwgznero.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2pfhxlkwn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gt2trgtfyez.html

Ruby: super
来源：http://dali.hysaishi.cn/Article/details/gt2fzlechda.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2lppwugpg.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gt2kvbxjpvg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ehwqpu.com/Article/details/gt2oymcvykr.html

PHP:  public static function f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2wdyjuvue.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gt2tlvggplo.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gt2yakewcoe.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2gafeadaf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gt2skeduzwy.html

Ruby: def self.f; end
来源：http://dali.cashguo.top/Article/details/gt2eocafczs.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gt2vvxjfqhk.html

[G09] 接口 / 抽象类
来源：http://dali.jianghu66.top/Article/details/gt2lmrlzhjp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2awjikork.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hicbfies.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gt2vuudphiz.html

TS:   interface Shape { area(): number; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dcodcobb.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gt2bqumxfxp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gt2vzzmpnut.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gzhubu.top/Article/details/gt2dwpuznxz.html

C#:   interface IShape { double Area(); }
来源：http://dali.fengsongda.top/Article/details/gt2knrjluij.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gt2tmmraokv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gt2tmpjfien.html

PHP:  public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gt2jycyuwad.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gt2knyfvznv.html

TS:   public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gt2mubjreqy.html

Java: public / protected / private / 默认包级
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qzrvejac.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gt2xxuzamkt.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2wxlcnwtt.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gt2swgkxyfe.html

[G11] getter / setter
来源：http://dali.sysykeji.top/Article/details/gt2ndopfqlh.html

Py:   @property 与 @x.setter
来源：http://dali.daxiang520.top/Article/details/gt2gykxoqiu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2xuvlbipn.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gt2rebupuop.html

TS:   get name(): string { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gt2irrkpebj.html

Java: public String getName() { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2mehwcdpt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2rrylmiha.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gt2ysnkjkaj.html

C#:   public string Name { get; set; }
来源：http://dali.zdqjudy.top/Article/details/gt2alqzgory.html

[G12] 对象转字符串
来源：http://dali.xziqi.cn/Article/details/gt2vcajdwqc.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gt2wbsynxzn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2issxipri.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxwfnqga.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2tfevniyg.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qafizpjs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fyexayen.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gt2wcywncph.html

C#:   public override string ToString() => Name;
来源：http://dali.shzxlz.cn/Article/details/gt2kfzmeryh.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gt2zjqiqgme.html

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gt2mzcuojwh.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2rxxmulbf.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2brrgikcy.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2nztkmrkq.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2zeirxkhf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gt2ueoivgvy.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rbvqyomh.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gt2flglpleg.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gt2abutejau.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gt2exvzypjh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gt2jqfhfwww.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gt2qfaoszel.html

TS:   type User = { name: string; age: number };
来源：http://dali.gogol.net.cn/Article/details/gt2pnwkmnaj.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2fvzgkfka.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jianghu66.top/Article/details/gt2rjsuxcwu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tianlin.xyz/Article/details/gt2pgrfkhjk.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gt2cobysfkg.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjabdiqg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuanzhike.top/Article/details/gt2nrgjoxci.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.snrcjt.cn/Article/details/gt2onjnhemg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yvedp.cn/Article/details/gt2ylcvnhyt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2fwtufpwe.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gt2vgwlgsnd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gt2bgwicwmd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gzhubu.top/Article/details/gt2ebvnouqx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2daixfksl.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gt2foexakpu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vbojyfmm.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gt2qfgjfjfj.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2udrgcman.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gt2cxyulmgk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gt2dkedtyri.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shzxlz.cn/Article/details/gt2qpdhifhs.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gt2ddlzcjpx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gt2rwgnjqfz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ryqoqdum.html

H. 异常与错误处理
来源：http://dali.jinqigufen.top/Article/details/gt2mbzbxtpu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2svgrxxgq.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gt2jfaatkul.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gt2clvnipbt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjecftyc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rxqtxvod.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gt2cdzfpwqz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.andypj.xyz/Article/details/gt2mbspvupp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gt2wzokwkxw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2ikfvwwlz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dgyotety.html

[H02] finally / ensure 收尾
来源：http://dali.guannengcc.top/Article/details/gt2rzdldrno.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gt2akhdgijk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2wrkjozsg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2xmjysjxr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2drxgyivr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvmsmcix.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gt2hbbskvqj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gt2rdpfbnkr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2qwptbjod.html

[H03] 主动抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gt2gftyksfb.html

Py:   raise ValueError("错误信息")
来源：http://dali.guannengcc.top/Article/details/gt2qjhthpnr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2uwxdozcn.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2gifyphef.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2trfayzic.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2cjdtdxit.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigufen.top/Article/details/gt2gmfzaicr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gt2oxqpzvrn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2rdfzhwyk.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gt2jrggfivx.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gt2ysovcdee.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2mnmjbbwu.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gt2repyrlyq.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gt2ljsgffuu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2schlvrrd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhengqikj.top/Article/details/gt2jqeqcakr.html

Ruby: class MyError < StandardError; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhonayrp.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gt2uofovdtz.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gt2ciugyome.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gt2pkicdcav.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenlongwang.top/Article/details/gt2xveeayuc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gt2bigtfshm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gt2imijuqkp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gt2jffecwmn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iuhyhliy.html

Ruby: rescue ArgumentError => e
来源：http://dali.316326.xyz/Article/details/gt2anfobdoj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gt2kcjeuuay.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gt2ayjdktbk.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gt2jqevaels.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gt2helakoft.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2omrjzedn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gt2jnzxqgfy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gt2vqulntml.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gt2mgnbadfm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cdnleiting.top/Article/details/gt2djkfccnx.html

C#:   obj?.A?.B ?? default
来源：http://dali.daria6918.cn/Article/details/gt2apwibqiz.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gt2sfubrysw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqoleqyj.html

PHP:  assert($x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cuazehjc.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2kiofzdqi.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2hxmpcsxk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gt2tshbxixh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gt2dgdwxktw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhcgdllo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2rkqjaytw.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gt2mdneuaea.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gt2hsndltoq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gt2avhbztwh.html

JS:   e.message;  e.stack
来源：http://dali.hammf.cn/Article/details/gt2yejpgwju.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xylfe.cn/Article/details/gt2tdqeqvhu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gt2zlskouqa.html

Go:   err.Error()
来源：http://dali.smart0.xyz/Article/details/gt2hlyofnbt.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gt2xypmxaaf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sweek.top/Article/details/gt2jabrvdcw.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gt2ibczsffx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gt2edihlsyj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hammf.cn/Article/details/gt2nyxpjmtn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gt2tkawyyzh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gt2ederzodu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fzhhl.top/Article/details/gt2tdhtvvay.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gt2xcijuthb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gt2sqjwzvew.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnbxvhly.html

[H10] 资源自动释放
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvxtvmom.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gt2utjaeomx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gt2ddelvjof.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gt2yalzztld.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gt2noxabcmk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gt2uszuqhbz.html

Go:   defer f.Close()
来源：http://dali.yj20258888.top/Article/details/gt2sqzdsuph.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgfzy.top/Article/details/gt2miduxgiy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2emxppdwi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2zbelyatz.html

I. 正则表达式
来源：http://dali.zycfv.cn/Article/details/gt2clcncpjp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2xeyrezse.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gt2mplgkytv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gt2bdsqezgr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohlxzlsx.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gt2utedulri.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2psdoarwx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yangfankeji.com/Article/details/gt2mflptbph.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gt2orwxujhj.html

Ruby: s.match?(/\d+/)
来源：http://dali.havefunace.top/Article/details/gt2ikbvomdm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gt2czuhsric.html

[I02] 提取所有匹配
来源：http://dali.daria6918.cn/Article/details/gt2claurnqt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gt2flpzmmky.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fengsongda.top/Article/details/gt2bqylqmxw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gt2kksrxavp.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gt2zsptplxa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sysykeji.top/Article/details/gt2fctumgto.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2tzgghmjs.html

Ruby: s.scan(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gt2cscgnwxq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwzhkqsg.html

[I03] 提取捕获分组
来源：http://dali.tianlin.xyz/Article/details/gt2sgfdohix.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzflpmmh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gzhubu.top/Article/details/gt2tvgduawo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2apxoevxl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdxkppxw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gt2jkgrtjpe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.9152youxi.cn/Article/details/gt2sedkoymn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zdqjudy.top/Article/details/gt2hwbsokml.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gt2cxzlsclm.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ydnxxocx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258.top/Article/details/gt2rpchegif.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2chujrndz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gt2jruusyxf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2yglewcrq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gt2wbvvaqup.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2eksthnoj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2hvayudfp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bshvmeff.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gt2yrkycirq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgfzy.top/Article/details/gt2nrxhnpdo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2mylvgbkk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gt2fhpodujf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2iqadtkyw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwloweru.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuanzx.com/Article/details/gt2uoihyapo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gt2hbencswq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gt2yfqjkhcy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gt2bsrqaqep.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gt2waadqjup.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgfzy.top/Article/details/gt2lonbqttk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gt2xymuhuvy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gt2mevrbvsr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2ouohhets.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gt2yiuwuwpp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xinyue.icu/Article/details/gt2ayalmzqn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2qadceasl.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gt2corfvldy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ivvv.top/Article/details/gt2gsjdigjv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbyexcgf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fengsongda.top/Article/details/gt2qvgcxaxi.html

TS:   /error/gim
来源：http://dali.ehwqpu.com/Article/details/gt2ngdbdykh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gt2xaiomehk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenlongwang.top/Article/details/gt2zylycics.html

Ruby: s.scan(/error/i)
来源：http://dali.yongpay.top/Article/details/gt2ajqfcgrl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxjudtip.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gt2cpqrqzic.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gt2smueuatb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wygnobbn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gt2wvoiqdxb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gt2axhuacxq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gt2xkmzvaha.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gt2vvuhquhk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvfxdfmg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gt2rilewjbm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2dqkppdta.html

J. 日期与时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2epdyteay.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2tivpmlkn.html

[J01] 获取当前时间
来源：http://dali.redwolf501.top/Article/details/gt2osspqlrp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gt2xmhzelak.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gt2kuhwadyp.html

JS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2gzmasezo.html

TS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gt2btlkdufk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gt2gbsyocvd.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gt2rahsnpau.html

Ruby: Time.now
来源：http://dali.zhixingplan.top/Article/details/gt2tmzlqdwb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jianghu66.top/Article/details/gt2zwzdwkxs.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gt2scxkebxf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2iwlxkqah.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gt2hkfauyxa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sdeaaizf.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gt2vlqexjcu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhiwuduotai.top/Article/details/gt2znsttmor.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gt2lfovbfud.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gt2bbgicigm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gt2sbbrxzmn.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gt2xataxcrb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgfzy.top/Article/details/gt2xveqitpg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gt2xcltaygz.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2iklupdgz.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2eirldpgm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2tdxgxrli.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2qnfcqdfx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azbyxayw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pycfn.com/Article/details/gt2nuwernwm.html

[J04] 时间戳与日期互转
来源：http://dali.svipenyu.cn/Article/details/gt2cxyozdxu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gt2egmjcfba.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gt2ekcccbcm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2dnmfsefv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gt2cqprbzzy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gt2fauamvhs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrldojwk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gt2anmomirx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gt2hejvywfj.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gt2cslolfsr.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gt2brkevbgv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ybcxt.top/Article/details/gt2okcfgnjk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gt2zoiaislb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gt2yibytwdi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xinyue.icu/Article/details/gt2pdiuyzer.html


<!-- 参考信息 -->