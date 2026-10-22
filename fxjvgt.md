代发 wailian999

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gttlgnjiae.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gtxcioveyn.html

[G08] 静态方法与属性
来源：http://dali.yonumen.top/Article/details/gtfhojxqjh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gtbiwjmpvt.html

PHP:  public static function f() {}
来源：http://dali.wangdashe.top/Article/details/gtnxkinurl.html

JS:   static f() {}
来源：http://dali.zhixingplan.top/Article/details/gtfkdeksbe.html

TS:   static f(): void {}
来源：http://dali.zhiwuduotai.top/Article/details/gtxtuijpqa.html

Java: static void f() {}
来源：http://dali.zhixingplan.top/Article/details/gtblvnyupg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cheryme.top/Article/details/gtduvzyalb.html

Ruby: def self.f; end
来源：http://dali.hysaishi.cn/Article/details/gtigfffwko.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gtqefzmdov.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gtgdwbewsk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gtdiwpruif.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gtttwqhcbq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gtnubwsrmt.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvlnijqx.html

Java: interface Shape { double area(); }
来源：http://dali.xylfe.cn/Article/details/gtyjnmwaae.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gtrdgkdved.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gaohongyu789.top/Article/details/gtbftnxgue.html

C#:   interface IShape { double Area(); }
来源：http://dali.sysykeji.top/Article/details/gtjeaaqoti.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gtnbsjwbdg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gtgygwebve.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gtsdhepvoh.html

JS:   #private 字段；其余公开
来源：http://dali.316326.xyz/Article/details/gtcynukhrx.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtpyaqhobn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gtqpmmcfqw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jlsjyb.cn/Article/details/gtesvzvqdo.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtowjvzgvx.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gtuyvivehz.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gtshtqsuxz.html

Py:   @property 与 @x.setter
来源：http://dali.xinyue.icu/Article/details/gtqvlryohf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gttilihiym.html

JS:   get name() { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyouuvpaf.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtcozxwxps.html

Java: public String getName() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtqpwpupso.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtxbfkpcfd.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gtcgcyzhej.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gtjejtqosl.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtgsdjksaw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtlkndjxzm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtgpadrcvg.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtkgbyfwrh.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtgkmmnzhh.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gtciwrxtlz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtqhfbgphs.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gtefzdmiie.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtshmsbpgc.html

[G13] 判断对象类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzlwuilk.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gtsyaawcyq.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdcjbuwm.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtzcxenuxd.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gthcnzqxvz.html

Java: u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtrgvcsifs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sysykeji.top/Article/details/gtxyvlvifq.html

Ruby: u.is_a?(User)
来源：http://dali.gzhubu.top/Article/details/gtspztnddj.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtyytljzdw.html

[G14] 数据类 / record
来源：http://dali.ivvv.top/Article/details/gtbejaooxu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhoulong.xyz/Article/details/gthmeqdwox.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gtayqceelt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daria6918.cn/Article/details/gtrehzstcr.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gtzsvrcczu.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gtumhapbjv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.meibo888.top/Article/details/gtlzxftrqz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj202588.top/Article/details/gtbdiaeptb.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gtmsrlhiim.html

[G15] 枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucpviwpb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gtizdfiopx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gtbumcludd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gtkbojowih.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtdqjcpzwh.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbabqhlgh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenjidiqi.icu/Article/details/gttcgpslci.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gzhubu.top/Article/details/gtlsdkodja.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtjvbiqvhd.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gtftjztiig.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgmonbmm.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gtnnpeolbe.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtpvubacpw.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtcwfnajrt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuanzx.com/Article/details/gtrjhbcunq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hongshengwenyu.top/Article/details/gtmkablwdp.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gtigabcqee.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtpnapvnbm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtmoubzark.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtnvgyseyb.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtlmkwmsjb.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gtiabngiqs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gtnpsrunbo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gtlpshxoki.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrzdjuap.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtsxzxpnei.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gtplgzluwl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gtqeaghiws.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gteqzlfufw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yanxiufei.cn/Article/details/gtwneyfawa.html

[H02] finally / ensure 收尾
来源：http://dali.iojbl.cn/Article/details/gtnlrdenug.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gtosnsedko.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gthtiiznek.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtblfcubsh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtvaomocyp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gttamdkosz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gtpgpxopmh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gttjxuxjzr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gteypktuhr.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gteaqkdyhc.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gtmwdbwmdv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtakojcpca.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtzmbpuzul.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtehozqcld.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtwxothhev.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gtnentyhvi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gtvbdrjltt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtppykjsip.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gtmgmwwipp.html

Py:   class MyError(Exception): pass
来源：http://dali.ppjwa.cn/Article/details/gtwkrbgffs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtagnflvnp.html

JS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gtupxpitiz.html

TS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtjmuhdowq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gthdjwjqwe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gtzdfgnwwt.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gticcsyifi.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gtnzesvqen.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gtatnhdljf.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gtmoufqosp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gtpfqrhcwo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtruqxntnw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtxpgighoy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yvedp.cn/Article/details/gtqpscztmo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gtxxvupoqs.html

Ruby: rescue ArgumentError => e
来源：http://dali.gaohongyu789.top/Article/details/gtlpcmoiot.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gtpwpjazrx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gtzaedpxqt.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gtewuggapk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtrlvxsqxq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtzoucrvkt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtifkbqjju.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaotdzooc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gtjmpfkmtp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gtribcschy.html

C#:   obj?.A?.B ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtcmappngz.html

[H07] 断言
来源：http://dali.aibaodan.cn/Article/details/gtjxoiorlp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gtvyfedbet.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gtjyctqjci.html

JS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtesakrfte.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtmvzsgajo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.c1oappe.top/Article/details/gtanrizkba.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gtotqhytrs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtrazgcpgm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtavoejxbc.html

[H08] 获取错误信息与堆栈
来源：http://dali.daxiang520.top/Article/details/gtgiwtatal.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ybcxt.top/Article/details/gtqlwwkqpo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gtkawohhee.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gtbfrvlmkr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gtlcmvscoa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gaohongyu789.top/Article/details/gtlnqoaqaw.html

Go:   err.Error()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmpfqwyx.html

Ruby: e.message;  e.backtrace
来源：http://dali.dianchejie.cn/Article/details/gtbzwirixj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gtlnliadbl.html

[H09] 带错误码的异常
来源：http://dali.sxryk.cn/Article/details/gtitzwuzeq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gtrfutlwel.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftgmjngm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gtzasyjlgw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gtopsswgii.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gtrhingrcz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtiewrzdlr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fengsongda.top/Article/details/gtzawwnfjg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gtbilfedcc.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gtkhtmzduo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dianchejie.cn/Article/details/gtvpntkylj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gtnmjddvgk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtmyjdzpfr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtmjbcpacr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gtoxxzchwo.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gtukuyyawd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gtyeviktuu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtxlkpbbam.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtfjspjotm.html

I. 正则表达式
来源：http://dali.svipenyu.cn/Article/details/gtzmddrfnv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtxppwlgem.html

[I01] 判断是否匹配
来源：http://dali.jiagoushi.top/Article/details/gtncpnjpsz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtaieluxjk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.havefunace.top/Article/details/gtpyfmaxqf.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtqbnalcwu.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtfveqbfsm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gtjfpxahjx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhixingplan.top/Article/details/gtqrxarudk.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlawcknud.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gtvazgdmwg.html

[I02] 提取所有匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzbqcsjd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtavtqrmnu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gteceqrqum.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tianlin.xyz/Article/details/gttkkitpje.html

TS:   s.match(/\d+/g)
来源：http://dali.zhongyouzk.top/Article/details/gtlssemtac.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gttvkjeept.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tian-w.cn/Article/details/gtktvagnsy.html

Ruby: s.scan(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtmvhghhcp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gttesbscsb.html

[I03] 提取捕获分组
来源：http://dali.hnxiangtu.top/Article/details/gthkfeanev.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gtgcfdvcbi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzodqdet.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtzrhredex.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigfzy.top/Article/details/gtmgvzibja.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhiwuduotai.top/Article/details/gtmfbnddcr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gtpgcxrhia.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtbopbcnfv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daxiang520.top/Article/details/gtlmxjumox.html

[I04] 正则替换
来源：http://dali.sysykeji.top/Article/details/gtgusngpyn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gttmcihfff.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gtmnrzrpax.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gttruytexv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtwclidutp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtezrarwvo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.0kj1m.cn/Article/details/gtkgirqofl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gtmvvlqgna.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtdbizhckx.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobcdgcex.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gtqarnrmux.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtzjiokmaa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtsxdawwlk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtvqlhlyhm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gtiqgyicwb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtfvzaychi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gttedgooxg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuanzhike.top/Article/details/gtkgtkyosx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gtxskqgzsf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtxwkvpsux.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.meibo888.top/Article/details/gtlbxvgkch.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gtarxempui.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnirflzy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtlydweqfb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.iojbl.cn/Article/details/gtanbtosal.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gtzzdjgmvw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtosakaffb.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhixingplan.top/Article/details/gtfykpyddz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gtbxyojwat.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gttqpherlx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhengqikj.top/Article/details/gtfhedypkm.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gtcbjavndt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gtuithbqrg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigufen.top/Article/details/gtfuznqrws.html

Ruby: s.scan(/error/i)
来源：http://dali.yonumen.top/Article/details/gtmnqxojwc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gtejfmbovc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenlongwang.top/Article/details/gteupvxtai.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gtixlfvtbk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtwlhfesgq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gtoeekwhzl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtbglikeqg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gtzfjlpigx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gtvzeohpog.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xinyue.icu/Article/details/gttxfeltrm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gtcheyhvyh.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtjzcqbdcq.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gthjelypte.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtvvrmaibq.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtjotslijc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gtkkssjnzp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtbijiokzv.html

JS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtikruikrb.html

TS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtumvlwecz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenzaomai.com/Article/details/gtvismknvf.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gtgmvoipil.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gtwyilazmg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xinyue.icu/Article/details/gtcrtvaghx.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gtwjjqlyyn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gtibznhwpx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtfcrgykbs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gtmcchkopm.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gteqiyfjlb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.bjfxy.top/Article/details/gtnjbicnqz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gtiodfcfot.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gtrockznis.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrsznlqz.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gtbmqjlebt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gtgquxdlmd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbkrvlcf.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtaxjfbltl.html

TS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtrpmtaehw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtpbeqzgsw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtfzciwgpp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtqrioflds.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gtwtjwfncu.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gtuqljadli.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gtrszvgyfv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gtjeonlcya.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gtbnhstbod.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxinkj.top/Article/details/gtlybufasw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtzbetrjyg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.svipenyu.cn/Article/details/gtxihjbzgx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gtsazfdatv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gtdrmwyccn.html

[J05] 时间加减（加 7 天）
来源：http://dali.snrcjt.cn/Article/details/gtwgcrocfo.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gtoepsxeqr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxuanxn.top/Article/details/gtnfvqvtaz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtxtaertgh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gtyntotdmt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtxfevmwbp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gtfjtholad.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258888.top/Article/details/gtulsfxsvx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtodqnimbv.html

[J06] 计算两时间之差
来源：http://dali.yj20258888.top/Article/details/gtwqsxtomz.html


<!-- 参考信息 -->