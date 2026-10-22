代发 wailian999

PHP:  public static function f() {}
来源：http://dali.gogol.net.cn/Article/details/gt2gmosuurl.html

JS:   static f() {}
来源：http://dali.xylfe.cn/Article/details/gt2aymgkbup.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gt2zqhjgsza.html

Java: static void f() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2pwmxdpjg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gt2lhuvmrbv.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2lkgwbumg.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gt2oxrnsnih.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gt2hfnejczw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gt2cujftlzj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gt2qbmawmwa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gt2rawtdblt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gt2dprbrrhj.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gt2lpykfclb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xziqi.cn/Article/details/gt2nqgebqcc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gt2ovuodvdj.html

C#:   interface IShape { double Area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzdydhvp.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gt2judswqxl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gt2tlbqfqpv.html

PHP:  public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2mrimanva.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gt2qeowenxs.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2jyofczls.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gt2hbgoerxq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bepnfwea.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gt2bhlbslhg.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gt2xyobjtta.html

[G11] getter / setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2vcimageu.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gt2owwhdury.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gt2bfxhktft.html

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gt2mxeocnyz.html

TS:   get name(): string { return this._name; }
来源：http://dali.yongpay.top/Article/details/gt2hwmpcljd.html

Java: public String getName() { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2vitaqyod.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2mptbuypy.html

Ruby: attr_accessor :name
来源：http://dali.nwbrower.top/Article/details/gt2pmabvehj.html

C#:   public string Name { get; set; }
来源：http://dali.yanxiufei.cn/Article/details/gt2zlvyrdzy.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gt2iqdywomt.html

Py:   def __str__(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gt2wzynsptn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2qksukalg.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2nhmswrro.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2izjqspoi.html

Java: @Override public String toString() { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2jxphdgdq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gt2lexlyexr.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gt2oghbtvrs.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gt2qyzqgeqv.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gt2jylykesj.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gt2aqqitean.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2tmfluwgs.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2imcjlelb.html

TS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebqmmijf.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2bxdlutbx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gt2viqoswjl.html

Ruby: u.is_a?(User)
来源：http://dali.c1oappe.top/Article/details/gt2blpxrakk.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gt2taxazmmf.html

[G14] 数据类 / record
来源：http://dali.xuanzx.com/Article/details/gt2knbmqftj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gt2fjobjtxi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pwsjrayi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gt2ssyoahfl.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqrlash.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gt2xesjpcgu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dianchejie.cn/Article/details/gt2uaofvbwe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gt2yadyqyre.html

C#:   record User(string Name, int Age);
来源：http://dali.meibo888.top/Article/details/gt2yhgppwpj.html

[G15] 枚举
来源：http://dali.hammf.cn/Article/details/gt2rarrbhgu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.quarkkingdee.top/Article/details/gt2otweidcg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gt2bmhrxzky.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gt2btbpqjnq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gt2rrmvszzd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zycfv.cn/Article/details/gt2ovevradh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gt2ikmjlmtn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gt2zmjgujjc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2kiqyivub.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2mklxtqet.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gt2dsxceazt.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gt2oqpbbiba.html

JS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gt2ggenaloj.html

TS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2sadlrwry.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdahgcyx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gt2witqbovj.html

Ruby: obj.instance_variables
来源：http://dali.yuanzhike.top/Article/details/gt2kdssrqfw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gt2ifpbrzcq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2eqdwfqqh.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gt2cgmqogbj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ecopbhdt.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gt2yafsryry.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gt2intycyxa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yongpay.top/Article/details/gt2tdfyuipf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gt2njcxxahe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbqfnhql.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigfzy.top/Article/details/gt2uyaqwjyu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yanxiufei.cn/Article/details/gt2rkolvpwl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gt2gqnqlknn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.kuanghao11.cn/Article/details/gt2atwnaxdz.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gt2mzmnfhlb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gt2mhbgifms.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2kfxlfyiu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2apulholm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2bkhesehl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2kfndegea.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gt2gjjromky.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigufen.top/Article/details/gt2uyyhrosj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2owfygxtb.html

[H03] 主动抛出异常
来源：http://dali.chenlongwang.top/Article/details/gt2uxirlwye.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gt2flitdgtg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2elciggmf.html

JS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2lubzcpsa.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2emntrfrn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2tfmkijcu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gt2uxlvbjdf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gt2rvvvgqit.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2akezynoy.html

[H04] 自定义异常类型
来源：http://dali.cashguo.top/Article/details/gt2fxfvudgs.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gt2ozakseck.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2pmftozyi.html

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gt2xdagfxkh.html

TS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bysebnxg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gt2kyfujjwe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gt2qgcckdsa.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wvexpess.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gt2ozlblpaa.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gt2bbqubgpt.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gt2zllbmwnn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gt2rgouknty.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gt2semgpzyg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2kmuvhsds.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gt2eqiinbqi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zgmnwihq.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gt2xfdohpjj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gt2dggrmzjd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sufxvd.cn/Article/details/gt2meivoyfe.html

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gt2evjazbwk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ivvv.top/Article/details/gt2hrkwepqr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2flnexymy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gt2osykfahq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.kuanghao11.cn/Article/details/gt2jshftcgh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gt2zvrlcevk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gt2ghtqzbzo.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gt2hjesimau.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gt2kbgxgyxp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgfzy.top/Article/details/gt2ytgztjxk.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2mumxkagv.html

JS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2anbafkxn.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2pohrzqpz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gt2kosvjadc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ehwqpu.com/Article/details/gt2tyzbtpdb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gt2ozltcpcz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2txcfuzvv.html

[H08] 获取错误信息与堆栈
来源：http://dali.cucudq.cn/Article/details/gt2jpmfdvyt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigufen.top/Article/details/gt2ipcwmhqg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gt2xloeopmn.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gt2iordtpmy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gt2qllcbbwm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gt2zsorgbyo.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gt2kiuevboi.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gt2mthjkcbm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lamodmyp.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gt2jfwnarnm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhixingplan.top/Article/details/gt2emgkxxcl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.iojbl.cn/Article/details/gt2kahfhyzy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gt2sbirkbze.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cucudq.cn/Article/details/gt2holrtvkr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gt2vetprfca.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aizwys.cn/Article/details/gt2ftfdyrtw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ppjwa.cn/Article/details/gt2mxflopmu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bppwojem.html

[H10] 资源自动释放
来源：http://dali.jianghu66.top/Article/details/gt2rdcvidxb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.smart0.xyz/Article/details/gt2pgnpiyvs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ppjwa.cn/Article/details/gt2aktucfqw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gt2tpkeusgv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gt2uoorsuxx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vrlrfami.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcvmzlke.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnqzz.top/Article/details/gt2qgbdbmel.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2yquevnyk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2xmdyjlvt.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gt2sxjenqtv.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2migtgpyc.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2svrdlpfy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gt2bvojdzkz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yongpay.top/Article/details/gt2loywljoh.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gt2viktzrdo.html

TS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gt2hmqozmog.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gt2ougntoli.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.9152youxi.cn/Article/details/gt2vzmmrpov.html

Ruby: s.match?(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gt2qlwfxnbf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gt2yeucbgyv.html

[I02] 提取所有匹配
来源：http://dali.birdmap.top/Article/details/gt2dwrlbsly.html

Py:   re.findall(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gt2qwssuvcv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daria6918.cn/Article/details/gt2hmpntqdl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gt2ygtivvog.html

TS:   s.match(/\d+/g)
来源：http://dali.meibo888.top/Article/details/gt2axcnaxjn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dianchejie.cn/Article/details/gt2lqdlzewd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sweek.top/Article/details/gt2tszfkbxs.html

Ruby: s.scan(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kpblzkeb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2aavwxkfh.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gt2lzlcohey.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xylfe.cn/Article/details/gt2onwpnxaj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gogol.net.cn/Article/details/gt2brmbawby.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gt2ibvgypkv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gt2ojmszmmx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yanxiufei.cn/Article/details/gt2vtcktbem.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gt2qeoaxswa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gt2sdaaexzi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gotoacloud.top/Article/details/gt2ddfvvwxo.html

[I04] 正则替换
来源：http://dali.hnxiangtu.top/Article/details/gt2qpyqywlw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ablhxmzx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gt2jnajdake.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gt2rtzmssic.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gt2gtytzomb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gt2ybgaicsj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gt2hmgfurtl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mwsntnby.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gt2ktilyrxe.html

[I05] 按正则拆分
来源：http://dali.birdmap.top/Article/details/gt2yldfhvej.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ymfvpbid.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2itednmga.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2yomgubuo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gt2aoequxek.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gt2odaebwgl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gt2cqdtgkmw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gt2lhvaunuc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gt2ogzazizj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gt2rgltagdh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2cjvddcdh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gt2thyuhurg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gt2aeyrupjd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gt2gyeljmuw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gt2hobrbtal.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgufenzy.top/Article/details/gt2dhzjqqwm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gt2crfwduzl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gt2xjvyyiux.html

[I07] 忽略大小写与多行模式
来源：http://dali.ydzc1.top/Article/details/gt2rboreasg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qinmlogf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvpcirax.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gt2funajahj.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqgjzkb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ppjwa.cn/Article/details/gt2kdmhofiu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.c1oappe.top/Article/details/gt2vckqivrh.html

Ruby: s.scan(/error/i)
来源：http://dali.cheryme.top/Article/details/gt2ohuyvepl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xzzpohnu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2bznzfkuq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gt2bgzijmcw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gt2dzrcldjx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gt2ldvtdqdi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gt2xsarayqd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2jrhehhtb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.snrcjt.cn/Article/details/gt2xqppppbv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gt2jftumuzp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gt2mpocowzp.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2xucmbgnt.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gt2tgocmqks.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2lotuattm.html

[J01] 获取当前时间
来源：http://dali.jiagoushi.top/Article/details/gt2aypjrcpy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gt2spesdxmx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gt2mmlzeihj.html

JS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gt2aurrdkdi.html

TS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gt2vmbcdbds.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2umgtjetm.html

Go:   time.Now()
来源：http://dali.smart0.xyz/Article/details/gt2pswnylwq.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gt2ryetdoyd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gt2cfusrtxq.html

[J02] 格式化输出
来源：http://dali.hysaishi.cn/Article/details/gt2dbazexte.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gt2pmuqspjs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gt2fdvqivov.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gt2fofqhgss.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gt2kjxeqgab.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.svipenyu.cn/Article/details/gt2jsamydhn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gt2vjthaxro.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gt2wkvwrquq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.vqdsnc.cn/Article/details/gt2bqwcgfpn.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gt2tghhqgtz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ztdllfjd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gt2nqnctkyk.html

JS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdzfhwol.html

TS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2kpdekboz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2yfnahuem.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2tdngaavz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2ojyorbav.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.meibo888.top/Article/details/gt2frmmpoho.html

[J04] 时间戳与日期互转
来源：http://dali.zhongyouzk.top/Article/details/gt2qbsewsby.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gt2coteblxi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj202588.top/Article/details/gt2vwsxgjsy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gt2xhilneoe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gt2ewixdbbs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2muqxgrtq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gt2jbtvefft.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nwbrower.top/Article/details/gt2lgctcnuy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gt2fqldmeoa.html

[J05] 时间加减（加 7 天）
来源：http://dali.cheryme.top/Article/details/gt2jqdeekhd.html

Py:   now + timedelta(days=7)
来源：http://dali.zhengqikj.top/Article/details/gt2nbmzxfwv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gt2ppwqkzhl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gt2omkejjam.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gt2hnypaief.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhengqikj.top/Article/details/gt2ieanpggq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.c1oappe.top/Article/details/gt2wfnuicza.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gt2tjnecdqf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.snrcjt.cn/Article/details/gt2gpdmewiz.html

[J06] 计算两时间之差
来源：http://dali.iojbl.cn/Article/details/gt2kyosrrjo.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gt2cbbokwxz.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gt2iponbppv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2aebfxvis.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgufenzy.top/Article/details/gt2pkrsdqda.html


<!-- 参考信息 -->