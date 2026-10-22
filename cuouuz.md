代发 wailian999

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2utflemtt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yangfankeji.com/Article/details/gt2ddgrzugv.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2otymyrqf.html

C#:   class Admin : User {}
来源：http://dali.zhixingplan.top/Article/details/gt2uuowlvrn.html

[G06] 重写方法
来源：http://dali.316326.xyz/Article/details/gt2daslzhmo.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgufenzy.top/Article/details/gt2dorfbagw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2padcvbfc.html

JS:   greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2gssyxmcw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ttuacfeh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2greqxedw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gt2duxusymb.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gt2zkhanbbv.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gt2tilonnyw.html

[G07] 调用父类方法
来源：http://dali.shzxlz.cn/Article/details/gt2ajophpms.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gt2qtusuhwo.html

PHP:  parent::greet();
来源：http://dali.yongpay.top/Article/details/gt2annzlfvo.html

JS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2pzzqmeuo.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2uqjmdplt.html

Java: super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2hqkafgsa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gt2kyabphzt.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gt2kcbwggfw.html

C#:   base.Greet();
来源：http://dali.havefunace.top/Article/details/gt2mwvcvjcb.html

[G08] 静态方法与属性
来源：http://dali.vqdsnc.cn/Article/details/gt2dabappno.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gt2rujuandh.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ffbiolex.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2eezricys.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gt2eejbxcdx.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gt2rabezkfb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxinkj.top/Article/details/gt2fgmvxgip.html

Ruby: def self.f; end
来源：http://dali.dianchejie.cn/Article/details/gt2eidgtjab.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gt2vztbfriu.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gt2pwfdlpqs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gt2dewhvhzt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gt2uyxfzkuj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gt2oztlzanw.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gt2uagshmiz.html

Java: interface Shape { double area(); }
来源：http://dali.ppjwa.cn/Article/details/gt2nuhqismu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gt2blrerlan.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gt2hzusncve.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gt2hxysxuts.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gt2yscvjfqx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.vqdsnc.cn/Article/details/gt2mfnytcia.html

PHP:  public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gt2bgugftbr.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gt2lwczsgat.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2lsotdnax.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gt2zsaxwqds.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.bjfxy.top/Article/details/gt2opaapyxx.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gt2ucguejgy.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gt2nigbobrb.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gt2tqedpikr.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gt2oesgrhxa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2ehpjrmtf.html

JS:   get name() { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gt2shgcjdii.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gt2wkdtemmp.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2icngjmwl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2cdfgofkv.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwilwsvk.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uwmntvtf.html

[G12] 对象转字符串
来源：http://dali.jianghu66.top/Article/details/gt2vemjytwt.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2urvvubzh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gt2vvmtnara.html

JS:   toString() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2jjjlrkzy.html

TS:   toString(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2pbigtbvn.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2hrwpiije.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2xiuxjjtu.html

Ruby: def to_s; @name; end
来源：http://dali.ydzc1.top/Article/details/gt2nzgzyghk.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2iikaybre.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gt2gbscfobc.html

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gt2kthwhcya.html

PHP:  $u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2fyoasftt.html

JS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2ytfyedhd.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2ycchvtqs.html

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2ycsumhhi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gt2guhyvjfs.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gt2maqatqxm.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzqedlcb.html

[G14] 数据类 / record
来源：http://dali.yuxming.cn/Article/details/gt2wridajri.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hfpthk.cn/Article/details/gt2tignihgf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kvrasvpq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.bjfxy.top/Article/details/gt2acslsijk.html

TS:   type User = { name: string; age: number };
来源：http://dali.daxiang520.top/Article/details/gt2pfiedjph.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gt2qzbimvst.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gt2wsyqcpny.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sysykeji.top/Article/details/gt2xqiubaet.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gt2grsjkwci.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gt2omvsbubl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.iojbl.cn/Article/details/gt2xbykzutq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yvedp.cn/Article/details/gt2obrjnbos.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.0kj1m.cn/Article/details/gt2sadxolad.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gt2qvmlyxse.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gt2jylvvbpz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gt2bhtuwepq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gt2slmiznec.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gt2ykqwygwl.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gt2glojnwoh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gt2vlhzswav.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gt2hgntopaq.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2lhehthnt.html

TS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2hagataap.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gt2xbbsurbf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gt2bbjgwjip.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gt2pkmyione.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gt2bmbvdjlb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ifhfeesn.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gt2jasudhop.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2azucykqt.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gt2rljiavma.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gt2axsbhdnx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gt2hnnbxvjp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gt2akedzjgr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfgygytk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.mhx1999.top/Article/details/gt2zyzfettb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gogol.net.cn/Article/details/gt2ewdgctfc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gaohongyu789.top/Article/details/gt2wixcmsxh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfdvnask.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gt2okalboge.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangdashe.top/Article/details/gt2udxyvtqr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2kvczmsja.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2tptlmjtl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2chznpdmq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2mqnuhfhp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gt2mpxsbnpr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gt2honxawda.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2dpnvsikv.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gt2spfjegew.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gt2akbmxhab.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jktydjfa.html

JS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2dlvxhurc.html

TS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2phwekvod.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2rxhhktmm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gt2lemzqkvv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gt2coazellf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2idbxuiyz.html

[H04] 自定义异常类型
来源：http://dali.shuidangran.top/Article/details/gt2grhulmcv.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gt2amyluzcw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gt2rnnayhvp.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gt2imqxbevk.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gt2lvyhzxqa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ixdkpdpb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gt2gykffhgr.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uyxfyvqd.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2perbshar.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gt2irlbtzxi.html

Py:   except ValueError as e:
来源：http://dali.sufxvd.cn/Article/details/gt2dvxhkvsb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gt2ukkvkpae.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gt2xjcafuzh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gt2ipuqsoiw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gt2xhksnezp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cqqwz.cn/Article/details/gt2iywbpcth.html

Ruby: rescue ArgumentError => e
来源：http://dali.bjfxy.top/Article/details/gt2qlllzupe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2razpflcg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gt2dligxjrt.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gt2vcmzsdpx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gt2ukajrxmg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gt2fxmjrdoj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2idfwrihf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdwekdzo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fzhhl.top/Article/details/gt2gqjdkgxu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gt2bafidfgu.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlzpynuo.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gt2eaifmhtl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxzrayo.html

PHP:  assert($x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2phrzqcmw.html

JS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2ckarnpjl.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2qgyxquma.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gt2dowzlasn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yanxiufei.cn/Article/details/gt2xzgbuurx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vpapyxru.html

C#:   Debug.Assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2mumxjeql.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhengqikj.top/Article/details/gt2rqhqlrxw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.mhx1999.top/Article/details/gt2bgnwhjib.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gt2ihkccbbw.html

JS:   e.message;  e.stack
来源：http://dali.gzhubu.top/Article/details/gt2hymcucol.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnxiangtu.top/Article/details/gt2vzmjkaza.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gt2hlitkaug.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gt2vumebaxq.html

Ruby: e.message;  e.backtrace
来源：http://dali.tianlin.xyz/Article/details/gt2tszzhflq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gt2cbvyfikd.html

[H09] 带错误码的异常
来源：http://dali.hnqzz.top/Article/details/gt2oszyyiec.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tianlin.xyz/Article/details/gt2avnmjsmi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gt2qoetvcji.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gt2ajthilmp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bitwhets.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gt2whvqdits.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigufen.top/Article/details/gt2tvlxntss.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gt2njhjdzdt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.316326.xyz/Article/details/gt2chkpeafw.html

[H10] 资源自动释放
来源：http://dali.jinqigufen.top/Article/details/gt2mahjsmjt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.smart0.xyz/Article/details/gt2jwpwgidj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bynhfswd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gt2qbdvsezp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gt2mqbnclnj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ivvv.top/Article/details/gt2irjqdzbf.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gt2brbadecl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj202588.top/Article/details/gt2vqkcbqwk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2hvsddqkb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2dogsbjdv.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gt2brmkvfvg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2ezkwuxdn.html

[I01] 判断是否匹配
来源：http://dali.316326.xyz/Article/details/gt2vqntabic.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzjkntqd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2yrwudcgz.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gt2hlvfjudg.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gt2nzgnbqju.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.vqdsnc.cn/Article/details/gt2hlzhhfjf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cashguo.top/Article/details/gt2ukosfbfb.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2dbahpjub.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aizwys.cn/Article/details/gt2ossgympn.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gt2rchfconq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gt2ecputzlk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xinyue.icu/Article/details/gt2dcwqtyjs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gt2ruyhideb.html

TS:   s.match(/\d+/g)
来源：http://dali.sxryk.cn/Article/details/gt2unqmezwv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2hrhipiwb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.bjfxy.top/Article/details/gt2rpapcduf.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gt2rjgjdnez.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2ueqkoefk.html

[I03] 提取捕获分组
来源：http://dali.9152youxi.cn/Article/details/gt2kyfrfunv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigufen.top/Article/details/gt2qdxunfyi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shuidangran.top/Article/details/gt2qggtujaq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guannengcc.top/Article/details/gt2dnmntqln.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cdnleiting.top/Article/details/gt2oiucuege.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xblfbxez.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gt2tglskxlg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2oghzceum.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shuidangran.top/Article/details/gt2hdgtkgds.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gt2rrciupcc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuxming.cn/Article/details/gt2rusicvzj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2gpgmjvug.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2plogbnuk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gt2gyzgspza.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gt2kwusncyt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.c1oappe.top/Article/details/gt2thiqhfvo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pycfn.com/Article/details/gt2yhxeotgv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gt2jpmrwtye.html

[I05] 按正则拆分
来源：http://dali.gogol.net.cn/Article/details/gt2ucheebtf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigufen.top/Article/details/gt2zliielpr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.meibo888.top/Article/details/gt2rqiwsryp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gt2vkatdgdm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gt2ghzxagjx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sufxvd.cn/Article/details/gt2wpjcwhkr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fengsongda.top/Article/details/gt2rzmsktda.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gt2fragalez.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tianlin.xyz/Article/details/gt2txgyqqql.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxinkj.top/Article/details/gt2kkaihfqn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2qjoefbdx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zdqjudy.top/Article/details/gt2jjpbkkod.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gt2ckqorlyf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gt2scnntssq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gt2kmlwvgjj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sxryk.cn/Article/details/gt2qreiromr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fsrxbyxh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2joxvegox.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsjsrzhz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gt2odajvuav.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gt2rarcmdvp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cdnleiting.top/Article/details/gt2nynwivgh.html

TS:   /error/gim
来源：http://dali.dashuyun.cn/Article/details/gt2sfohyxfg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aibaodan.cn/Article/details/gt2iosbkmqv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ydzc1.top/Article/details/gt2mtmbxmkb.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gt2qnwsypnw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uerwfxuf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.mhx1999.top/Article/details/gt2piratjbu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258888.top/Article/details/gt2wyshtsgq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltxkidyd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gt2gxlnuqoh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gt2uqxnlzfs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gt2aocypdho.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jlsjyb.cn/Article/details/gt2immuxqda.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gt2poybjvuj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gt2qnjihkcf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjkxwaxj.html

J. 日期与时间
来源：http://dali.shuidangran.top/Article/details/gt2suozklpq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2mldtrozl.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gt2udldtitb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangdashe.top/Article/details/gt2fktdltij.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gt2audmzufd.html

JS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gt2kpryuivu.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ayuczsuz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2irklokey.html

Go:   time.Now()
来源：http://dali.birdmap.top/Article/details/gt2pdenxret.html

Ruby: Time.now
来源：http://dali.yangfankeji.com/Article/details/gt2ygljvqdy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahunwzhq.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gt2dnysxieq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gt2dcdmktwh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjbvxwzs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.mhx1999.top/Article/details/gt2oarhzldf.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2rnpthzrs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tian-w.cn/Article/details/gt2ihopckdj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.mhx1999.top/Article/details/gt2avufazeq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gt2ibqqumev.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgnfiaet.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gt2apsgjpil.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.havefunace.top/Article/details/gt2ggbyzdmp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuanzx.com/Article/details/gt2kznsxwnr.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2wameoaco.html

TS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2chfbwuxg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2wxtisabs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdbvdvpa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2opzgbvpu.html


<!-- 参考信息 -->