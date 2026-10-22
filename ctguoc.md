代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gt2odtdrjzv.html

Ruby: def self.f; end
来源：http://dali.nanxuanxn.top/Article/details/gt2ieqryidw.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2wsbewcpg.html

[G09] 接口 / 抽象类
来源：http://dali.cdnleiting.top/Article/details/gt2hpuyezpn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gt2cfnlkudz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shuidangran.top/Article/details/gt2ltbplfws.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gt2sydewbem.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gt2wmthittp.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gt2jcfazwjv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qimlcsri.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gt2ozkmofjf.html

C#:   interface IShape { double Area(); }
来源：http://dali.cdnleiting.top/Article/details/gt2yagrzzyc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2kierqiqk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gt2oevjrzyx.html

PHP:  public / protected / private
来源：http://dali.xylfe.cn/Article/details/gt2kwnafdzv.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gt2gxgphwxr.html

TS:   public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2asoaxeqp.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgfzy.top/Article/details/gt2blrbsqtr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gt2ucrogewk.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdkbudvt.html

C#:   public / protected / private / internal
来源：http://dali.yanxiufei.cn/Article/details/gt2oydxigso.html

[G11] getter / setter
来源：http://dali.nanxuanxn.top/Article/details/gt2pdlwpawi.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2alqpqwqd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2brszucxt.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gt2itvprbib.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwkjsjuj.html

Java: public String getName() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2yylurrht.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxafplea.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gt2axlxafgn.html

C#:   public string Name { get; set; }
来源：http://dali.chenlongwang.top/Article/details/gt2mohqkqlq.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2qmuguwzq.html

Py:   def __str__(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gt2axppssmv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2tlwdanxg.html

JS:   toString() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2wdjnditx.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2fcafrmjm.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2onxogydp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2pzlgoqzj.html

Ruby: def to_s; @name; end
来源：http://dali.guannengcc.top/Article/details/gt2bldwoyzi.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gt2ekupzcnl.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gt2jwdxtzbf.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gt2ixdijwja.html

PHP:  $u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnmtcvtm.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2jitefgxg.html

TS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2uetetacr.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2opqtmsuo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nwbrower.top/Article/details/gt2taclxkwt.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258888.top/Article/details/gt2gevvzglh.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gt2snvuqwsv.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gt2wrgdgibb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gotoacloud.top/Article/details/gt2jolixkbs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gt2gjynjdpg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gt2tdlnvmdh.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijlowjdd.html

Java: record User(String name, int age) {}
来源：http://dali.c1oappe.top/Article/details/gt2sdsdltbc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gt2zfcufvji.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258.top/Article/details/gt2pdyqjrmu.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gt2xzbqxkvh.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gt2ndrpthxt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gt2pamkfimy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gt2tiykauko.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxuanxn.top/Article/details/gt2nifhglqo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2xvzzrdyx.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj202588.top/Article/details/gt2ddogrjhn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gt2zsnltvzp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.meibo888.top/Article/details/gt2vranftxl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2zapalxpw.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gt2sjtmrxkd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gt2kxcgdcns.html

PHP:  get_object_vars($obj);
来源：http://dali.iojbl.cn/Article/details/gt2fkebxofq.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2stmyuzlj.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gt2sdubuuhz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gt2vmlzisxl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gt2qlroftbx.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gt2dejghzwc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gt2nfdkfnih.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2ycxdybtw.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gt2thzerklg.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmehprmq.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gt2yigabdsf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gt2kmdeajiu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gt2shfepdap.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gt2suthofvd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gt2htqjyvkr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gt2esalquby.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gt2shtwpbsq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xinyue.icu/Article/details/gt2bolqrdzb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gt2suwpxxsm.html

[H02] finally / ensure 收尾
来源：http://dali.xylfe.cn/Article/details/gt2qignteod.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gt2itzlmyiw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2mtadsaco.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2ywhhjarn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptrteivs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2jtdvzujb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hammf.cn/Article/details/gt2ztoqowpl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gt2sznxoanm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2nioyprkf.html

[H03] 主动抛出异常
来源：http://dali.guowangkeji.top/Article/details/gt2lhikabgh.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gt2wdlqahpy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2bxdxdsal.html

JS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2nmjzdvep.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2jitthosc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lxgyncyt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otnnwnxa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gt2ipeljyoz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2tbftysre.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gt2aycepzqv.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gt2loylfovf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gt2erqpztfc.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ytcxoirw.html

TS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gt2vptpsptr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gt2rpitpddp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kdrztlxc.html

Ruby: class MyError < StandardError; end
来源：http://dali.aizwys.cn/Article/details/gt2txjsdrhn.html

C#:   class MyException : Exception {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2phsvmuyh.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gt2nnzpmjio.html

Py:   except ValueError as e:
来源：http://dali.hnqzz.top/Article/details/gt2zbbfbtfi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gt2vboyzlji.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gt2ceqexkww.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gt2adsrjdag.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gt2dlmikpwx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gt2ieevizfl.html

Ruby: rescue ArgumentError => e
来源：http://dali.svipenyu.cn/Article/details/gt2mgeiwobe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gt2rowjwrur.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhixingplan.top/Article/details/gt2dwnadkad.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gt2masskubx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gt2rxbgnnvm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gt2oltngppg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2zuorepxy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ulacpdja.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gt2gpkeileo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iozjnuru.html

C#:   obj?.A?.B ?? default
来源：http://dali.xinyue.icu/Article/details/gt2ehhizgoa.html

[H07] 断言
来源：http://dali.ybcxt.top/Article/details/gt2rxqiglox.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gaohongyu789.top/Article/details/gt2ywvcdqih.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2mpeqbxua.html

JS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2oxtvtifu.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2eehodbff.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jiagoushi.top/Article/details/gt2ckkdkcde.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gt2ftrmnbpx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gt2luhjkqgr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yshkzjwo.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgfzy.top/Article/details/gt2pcjchqds.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwzwiqcq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shzxlz.cn/Article/details/gt2wdrhxgna.html

JS:   e.message;  e.stack
来源：http://dali.cashguo.top/Article/details/gt2lcbrmkvb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqpnktgv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gt2zvztxogs.html

Go:   err.Error()
来源：http://dali.yj20258888.top/Article/details/gt2utpiaqpj.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gt2hdphbrnl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.smart0.xyz/Article/details/gt2igejznvp.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gt2brpzvujc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tianlin.xyz/Article/details/gt2aulpxizv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nefhcerl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gt2tvujzofa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yonumen.top/Article/details/gt2femtbiyz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.birdmap.top/Article/details/gt2jnsdrmwz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tanke756.top/Article/details/gt2xzqbtjjy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guannengcc.top/Article/details/gt2diywfrfy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gt2mlvgkkzy.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uxnpobvb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yanxiufei.cn/Article/details/gt2ccqljcez.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.feifeiyinyue.top/Article/details/gt2rrvwrhnx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gt2qbpcgcde.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gt2qiiqfbhd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gt2fopsygsf.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gt2cmvuaoaa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jlsjyb.cn/Article/details/gt2zgdpranr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2bqobocie.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2aiyanpuv.html

I. 正则表达式
来源：http://dali.pycfn.com/Article/details/gt2ryxbpchd.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2jttrowrr.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2nfezzlmr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gt2skmpkrhh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2rggrvnpj.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gt2bfkydopb.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gt2mmwilqcf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuxming.cn/Article/details/gt2wuyezkvw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nwbrower.top/Article/details/gt2havnbuje.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2axetyvsi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gt2junmbokb.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbnjtpz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gt2sdptvwyi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gt2etiwpcew.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jlsjyb.cn/Article/details/gt2hyqowslr.html

TS:   s.match(/\d+/g)
来源：http://dali.mhx1999.top/Article/details/gt2sdfyikzz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fzhhl.top/Article/details/gt2gevqdxje.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhfzvptk.html

Ruby: s.scan(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gt2asexvqeb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2ioqfsklo.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ipkfybfz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqbzqqzh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jyoumei.cn/Article/details/gt2rzavuzxx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hysaishi.cn/Article/details/gt2iofdpaot.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zycfv.cn/Article/details/gt2brszxjoj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gt2ricxsynp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgfzy.top/Article/details/gt2rsquthro.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aibaodan.cn/Article/details/gt2aiivnckc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gt2trcorewb.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gt2lvtowclh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenlongwang.top/Article/details/gt2vqnsprsx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2sssidsfz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2alxefrss.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gt2wyoidjzb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2cbweesnz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2whsjgdab.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2toagbmnv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yongpay.top/Article/details/gt2vochqbgf.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2idrbfgii.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qrncwnfp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2jmxckaxl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gt2wngtxdcu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2sfyigike.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gt2wqnhsvij.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zduxbjmx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2ikmhhwho.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gt2fagjhdab.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gt2wyhwumyl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2whkdxrod.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzwdpaga.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gt2aaxmgfjg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gt2qojifgaj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gt2vllavswj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xylfe.cn/Article/details/gt2momlpkku.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gt2wzykdeix.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gt2vxmztwvd.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhixingplan.top/Article/details/gt2zmessrvz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gt2atmwjyja.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gt2kfzaoehk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gt2brkwkiwq.html

TS:   /error/gim
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yiyolhjh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fzhhl.top/Article/details/gt2gaebpvpu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gt2wravxhfq.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gt2adzvqxvx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yueranfly.top/Article/details/gt2alwvfcoj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2epyodjqk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gt2cjnyhhiq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gt2akskevtq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gt2tckajhrn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gt2pvzplxza.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gt2xzojredv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj202588.top/Article/details/gt2tloyomvc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gt2lobsbwoy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tpqeuqtz.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2dowyepby.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gt2cmpfwfsf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2rwmqgauf.html

[J01] 获取当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtxrpugz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258.top/Article/details/gt2kxjgdnli.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gt2nzrezryz.html

JS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2tgtbujwt.html

TS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gt2eqwylpnb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gt2zhgojpdq.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gt2mltbbayu.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gt2leyvbzub.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gt2uahawkyf.html

[J02] 格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2imyqeafa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gt2oiqviuaf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gt2dsgorewq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yanxiufei.cn/Article/details/gt2orkrrhmr.html

TS:   d.toISOString()
来源：http://dali.9152youxi.cn/Article/details/gt2sxfsxvoj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gt2vlfakdet.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gt2jftpwpdd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gt2mbqnpodu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dashuyun.cn/Article/details/gt2huwiqnaw.html

[J03] 字符串解析为日期
来源：http://dali.cashguo.top/Article/details/gt2xcemuxcs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuanzhike.top/Article/details/gt2fsihqfbw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.quarkkingdee.top/Article/details/gt2pljbzaqc.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2dcabihac.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2sphmcwqq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2njvqkdsr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2cqpiyhcz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2vzdcdaju.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.kuanghao11.cn/Article/details/gt2uoaiuoad.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gt2zmjlukvm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2yjsnbgjn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cashguo.top/Article/details/gt2cumewdxn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shuidangran.top/Article/details/gt2zoszronb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gt2lpbczgwl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2iaoiegwm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gt2dxoncxyh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2tguwabrb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gt2wxqoqwqn.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gt2abnsqzvu.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gt2ibjmzocv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.haohaochexian.top/Article/details/gt2ssttvycj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fcadbeil.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gt2nbaksypx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ydvdgveu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnxiangtu.top/Article/details/gt2avfzetdl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangdashe.top/Article/details/gt2anozvzbz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gt2vomerkqz.html

[J06] 计算两时间之差
来源：http://dali.aizwys.cn/Article/details/gt2cqdkrimu.html

Py:   (end - start).total_seconds()
来源：http://dali.xuanzx.com/Article/details/gt2kqhqqfyh.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gt2znmkicxy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gt2zxcfynls.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.c1oappe.top/Article/details/gt2rwvjmohd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gt2vpzfnzec.html

Go:   end.Sub(start).Hours()
来源：http://dali.fengsongda.top/Article/details/gt2xeqkmwpo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangdashe.top/Article/details/gt2qaintrkv.html

C#:   (end - start).TotalSeconds
来源：http://dali.pengpengdd.cyou/Article/details/gt2rmmaxxuo.html


<!-- 参考信息 -->