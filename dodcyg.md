代发 wailian999

Ruby: super
来源：http://dali.sufxvd.cn/Article/details/gt2wbdnbzgy.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gt2lmoyqszw.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gt2osuqccbc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gt2gpsvoqld.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gt2zuymjxid.html

JS:   static f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2wepzukgf.html

TS:   static f(): void {}
来源：http://dali.cheryme.top/Article/details/gt2hlliwnan.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gt2kfrmztwe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gt2uojuweil.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gt2awezgylc.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gt2xtpghsrz.html

[G09] 接口 / 抽象类
来源：http://dali.hnxiangtu.top/Article/details/gt2wylxtdmx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sweek.top/Article/details/gt2qaqclkdy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gt2mhazwhpr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gt2pynuctng.html

TS:   interface Shape { area(): number; }
来源：http://dali.snrcjt.cn/Article/details/gt2gvrrshuu.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2muypsthu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ehwqpu.com/Article/details/gt2eshzafut.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gt2gugfrtze.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iyjheokf.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gt2pqmvxvqj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwnruqpb.html

PHP:  public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gt2mssjnonf.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gt2ivvfsruk.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxvswzdz.html

Java: public / protected / private / 默认包级
来源：http://dali.ybcxt.top/Article/details/gt2ugmcqdpd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.bjfxy.top/Article/details/gt2oonntvfe.html

Ruby: public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2kawlgtha.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gt2ybxbubmx.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gt2pbqwppbz.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gt2hsrdlvnr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2toiyqhlg.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gt2bxfyskjy.html

TS:   get name(): string { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gt2djxghbjm.html

Java: public String getName() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvluryjq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2hpohadkf.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gt2orgnbjcm.html

C#:   public string Name { get; set; }
来源：http://dali.aizwys.cn/Article/details/gt2isuduvoh.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gt2pwoalywu.html

Py:   def __str__(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gt2ifdmkazh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2fniklizm.html

JS:   toString() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2tmabipcj.html

TS:   toString(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2roruturw.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gt2cljjeyxx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejokujib.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gt2tenuxwdt.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gt2eueqehfe.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gt2hdlldtpw.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gt2rublrynn.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2mfzwkbbw.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2ihktuqux.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2olkwosym.html

Java: u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2zajwbyxx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gt2ipeusjdn.html

Ruby: u.is_a?(User)
来源：http://dali.nanxuanxn.top/Article/details/gt2sfnrupou.html

C#:   u is User
来源：http://dali.tian-w.cn/Article/details/gt2fbjpfdkn.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gt2uuisurbg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gt2mefcgilb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgorqwvu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gt2yogboieo.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gt2ptiuucbp.html

Java: record User(String name, int age) {}
来源：http://dali.sysykeji.top/Article/details/gt2ogilmpvh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gt2szmleoeb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.meibo888.top/Article/details/gt2uwisplgg.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgufenzy.top/Article/details/gt2akolkquj.html

[G15] 枚举
来源：http://dali.zycfv.cn/Article/details/gt2rvdzivvy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2toewwves.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnqzz.top/Article/details/gt2tclbarcy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gt2klkelbts.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2lisglxwd.html

Java: enum Color { RED, GREEN }
来源：http://dali.yongpay.top/Article/details/gt2uzxwipua.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gt2sektdcey.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gt2tghytoss.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gt2sromnxen.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gt2edvpmktw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gt2yvvnoqto.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gt2mhvkobqz.html

JS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gt2xintuvqp.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqolqthx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gt2gbvjnosi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhongyouzk.top/Article/details/gt2zdkkaqfo.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gt2kbtkmmxy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gt2ywznehof.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2mjnvyqlp.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gt2ppjjazvq.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2jinhqapq.html

[H01] try / catch 基础
来源：http://dali.yanxiufei.cn/Article/details/gt2opoxzzax.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gt2dgltweuo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idxpekjd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2bexsehaj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gt2ofvllsrd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wgazenxv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gt2unijents.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.quarkkingdee.top/Article/details/gt2ttepvgle.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gt2nknsxbcr.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gt2stcdetwy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gt2eudyeybo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2eeeipwte.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2awqlrdsd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2xpzjuylt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqyabdzk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gt2aidibwiq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dianchejie.cn/Article/details/gt2hqfmbaxj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ikgyykgp.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gt2pwsguvhw.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gt2efxzvlxa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2sgourvvp.html

JS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2feboikap.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2faoeabrn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2afawbmrw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.meibo888.top/Article/details/gt2hdefpxbp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.meibo888.top/Article/details/gt2hesrhrxh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2exredghx.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gt2lvcsehbx.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gt2mtfdfchm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gt2hnxcvopf.html

JS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gt2lylwpcba.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gt2kkldfxlh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gt2ptdlqojm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuanzx.com/Article/details/gt2dcxsouho.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtfwbwrn.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaeggaj.html

[H05] 捕获特定类型
来源：http://dali.guannengcc.top/Article/details/gt2ugmvglpk.html

Py:   except ValueError as e:
来源：http://dali.hnqzz.top/Article/details/gt2gvuvbdlo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuanzx.com/Article/details/gt2madreabl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gt2rgldufas.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gt2ayviabfm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gt2vlrucyqc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ppjwa.cn/Article/details/gt2raajybef.html

Ruby: rescue ArgumentError => e
来源：http://dali.cdnleiting.top/Article/details/gt2wkcupcko.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gt2fwxsdyem.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sbsvqsiv.html

Py:   value = d.get("k") or default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qebkjcch.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gt2tuakicvs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gt2mpgonhib.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2yullvdvq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpytekiy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tian-w.cn/Article/details/gt2eqavxswd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gt2axywbpqj.html

C#:   obj?.A?.B ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2pybzlrpp.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gt2wsmyebbu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zycfv.cn/Article/details/gt2kyzdialx.html

PHP:  assert($x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2itzxvutw.html

JS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2qcptfiwd.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2qphlmnpt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.smart0.xyz/Article/details/gt2wmobpawn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yanxiufei.cn/Article/details/gt2imttixjq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yonumen.top/Article/details/gt2ikpqlwyu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fprjthwz.html

[H08] 获取错误信息与堆栈
来源：http://dali.fzhhl.top/Article/details/gt2gdgsbfhm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.iojbl.cn/Article/details/gt2wvxsygir.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.feifeiyinyue.top/Article/details/gt2byftwlvt.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2violjvnj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuanzhike.top/Article/details/gt2rpermuyd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cashguo.top/Article/details/gt2ztmrcrfi.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gt2qfuruebg.html

Ruby: e.message;  e.backtrace
来源：http://dali.snrcjt.cn/Article/details/gt2bmspfmyq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tian-w.cn/Article/details/gt2verizvuv.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gt2qadjiejv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gt2blbwktqr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gt2bbxfwblw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jlsjyb.cn/Article/details/gt2jlstonmp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhixingplan.top/Article/details/gt2rtnvqjfm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.birdmap.top/Article/details/gt2ykooixry.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2tacahcyk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2kszaycls.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gt2yvaasxgn.html

[H10] 资源自动释放
来源：http://dali.tanke756.top/Article/details/gt2bsgiraty.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gt2lwsteqem.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.316326.xyz/Article/details/gt2bovhsaog.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gt2gawhyshn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gt2dkblqrxj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.feifeiyinyue.top/Article/details/gt2iiezjcrd.html

Go:   defer f.Close()
来源：http://dali.0kj1m.cn/Article/details/gt2hobuhkpq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guowangkeji.top/Article/details/gt2uwghahrq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2ibtyzalm.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2tbznwhgz.html

I. 正则表达式
来源：http://dali.cdnleiting.top/Article/details/gt2btqzhpig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sofuccuz.html

[I01] 判断是否匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2racvauzv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gt2atysnjym.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2zrvrziop.html

JS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gt2yxtfyacd.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gt2cciyfhji.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.iojbl.cn/Article/details/gt2nfkauppw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gt2iuadugcb.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gt2bafkgevr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gt2cuwbtifz.html

[I02] 提取所有匹配
来源：http://dali.ybcxt.top/Article/details/gt2ikzhhahv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gt2xxtuegwi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gt2mtbrwhgf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gt2dkxprrzq.html

TS:   s.match(/\d+/g)
来源：http://dali.havefunace.top/Article/details/gt2voewrskx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daria6918.cn/Article/details/gt2ecqoeijd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yongpay.top/Article/details/gt2knzdgark.html

Ruby: s.scan(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gt2ppcdbmib.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2otrdlfjx.html

[I03] 提取捕获分组
来源：http://dali.fengsongda.top/Article/details/gt2nskujupb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ihedoxys.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytnjfnwy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258.top/Article/details/gt2kaqhfoxr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gt2xxbqptpq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.iojbl.cn/Article/details/gt2ewgyzhbe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ikttixuv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258888.top/Article/details/gt2wqlshdap.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.9152youxi.cn/Article/details/gt2iuarctmx.html

[I04] 正则替换
来源：http://dali.yj20258888.top/Article/details/gt2hytbboct.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbcmwmbq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crxajmix.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gt2ttagsofe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2apoqpmgz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gt2dqkxpzpp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2hpustyfg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yueranfly.top/Article/details/gt2vvtuijwe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gt2vgzgcucg.html

[I05] 按正则拆分
来源：http://dali.fengsongda.top/Article/details/gt2scoiwvvw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gt2dgnklztt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2bavueecs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2ldaioxoh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2slmzqybv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shzxlz.cn/Article/details/gt2gualbbuc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.birdmap.top/Article/details/gt2gfabvohu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2kpagyopj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyitntq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.mhx1999.top/Article/details/gt2xshdoiig.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2snaexukn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.316326.xyz/Article/details/gt2fcqvmppt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gt2dfzdlqfj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pzyhxxhp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gt2jxdozuxd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gt2teiqvuuf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tianlin.xyz/Article/details/gt2qudpftns.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2khllzhra.html

[I07] 忽略大小写与多行模式
来源：http://dali.9152youxi.cn/Article/details/gt2fxewxbfh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxinkj.top/Article/details/gt2yptptmxa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ypwyvvez.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shangyingyoupin.top/Article/details/gt2faxluksu.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gt2gtmupznv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gt2bbobsayz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.0kj1m.cn/Article/details/gt2jsrazavq.html

Ruby: s.scan(/error/i)
来源：http://dali.zycfv.cn/Article/details/gt2heznmvan.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.meibo888.top/Article/details/gt2itwblbub.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gt2zqvcrrog.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.snrcjt.cn/Article/details/gt2ewmylcgc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dphzrpal.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gt2kfyxsqtx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtfgsbpc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gt2dgitcdfd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gt2fltcetkx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gt2gaujpghk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gt2arvlvrio.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xnstcruv.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvjathe.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2lzmsfvua.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gt2mscokkxh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tian-w.cn/Article/details/gt2cyqubcno.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gt2kjlpkcja.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gt2vhwrbgdi.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2texfoeau.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gt2xhmdfctw.html

Go:   time.Now()
来源：http://dali.haohaochexian.top/Article/details/gt2xcoqbpwk.html

Ruby: Time.now
来源：http://dali.quarkkingdee.top/Article/details/gt2zvdhkkqu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daxiang520.top/Article/details/gt2zyxuupup.html

[J02] 格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gt2byiyolaq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gt2hcgocruj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gt2mnvnwdzg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gt2ahbtrbgq.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gt2qldmurly.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jianghu66.top/Article/details/gt2bprfptux.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigfzy.top/Article/details/gt2hkbhoank.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gt2xamxclza.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gt2fgfnzqiv.html

[J03] 字符串解析为日期
来源：http://dali.redwolf501.top/Article/details/gt2pwpgftog.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guannengcc.top/Article/details/gt2xvsbjzye.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhpwazhi.html

JS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2fhxthbzx.html

TS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2nvqbibsz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2iefxlsdp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2rfzpkjqd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2vsopamhq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258888.top/Article/details/gt2pozkepay.html

[J04] 时间戳与日期互转
来源：http://dali.ppjwa.cn/Article/details/gt2rjjqlwyo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gt2pengrisr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ydzc1.top/Article/details/gt2kwhjqzzo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guowangkeji.top/Article/details/gt2vifisvtj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gt2exnuvrtm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.mhx1999.top/Article/details/gt2ejuhbczp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xtrtsfqb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gt2vwgjesza.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tanke756.top/Article/details/gt2dfmedhqx.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cnenlofq.html

Py:   now + timedelta(days=7)
来源：http://dali.hnxiangtu.top/Article/details/gt2fewbhwrf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xylfe.cn/Article/details/gt2eufcdvya.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njonfdaq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qledvbpa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gt2dwbqgrxa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dianchejie.cn/Article/details/gt2lrzdvxxa.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gt2zjaohlox.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gt2zivrbbbg.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmodqmsy.html


<!-- 参考信息 -->