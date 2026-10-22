代发 wailian999

Ruby: super
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxaxsbdz.html

C#:   base.Greet();
来源：http://dali.zycfv.cn/Article/details/gtxefxbllm.html

[G08] 静态方法与属性
来源：http://dali.jqgufenzy.top/Article/details/gtobavtttt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.haohaochexian.top/Article/details/gtyvnaqyff.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gthepxramq.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gtyvunchli.html

TS:   static f(): void {}
来源：http://dali.nwbrower.top/Article/details/gtygvglkhx.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gtasuykmwq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gtbexsyolq.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gtljcsvqvu.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gtmjlepitm.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gtncmutqko.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gtbhnmmose.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gtlpwmoxsw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dashuyun.cn/Article/details/gtdrvzgxkg.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gtkfokxlao.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gtdnujwrsk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gzhubu.top/Article/details/gtljnjeyki.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gtntcvavml.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gtaumubevk.html

[G10] 访问控制
来源：http://dali.xuetiantiany.cn/Article/details/gtmcbcsjvr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gtnorkxzpe.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtwawxexqu.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gtwablhzja.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtwcdioqxl.html

Java: public / protected / private / 默认包级
来源：http://dali.andypj.xyz/Article/details/gtuhxdybhi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gtzzkshwov.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gttcnwwhqx.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gtbhjmzikl.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gtufhhslcw.html

Py:   @property 与 @x.setter
来源：http://dali.snrcjt.cn/Article/details/gtbrxrypcy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtavmlrpql.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtrrnjzjkn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtyvcykxdh.html

Java: public String getName() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjpghhix.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtobmfjsig.html

Ruby: attr_accessor :name
来源：http://dali.guannengcc.top/Article/details/gtrcujlpxe.html

C#:   public string Name { get; set; }
来源：http://dali.chenzaomai.com/Article/details/gtwwssnvil.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gtllcnssfg.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtjicgubno.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtxnvwrffs.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtskedgxaj.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtfsdsknfo.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtbthsvlxn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtarunhwyq.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gthgrymyer.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtkqpplvpq.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gtftekwtbd.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gtcfcvurvt.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gtagwwkefk.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gthbxyftzi.html

TS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtzubobwip.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtvuhxvvso.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenzaomai.com/Article/details/gteieodqta.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gtdndhjsia.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gtzcbevbel.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gtldqjgxzp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yueranfly.top/Article/details/gtczukvaxi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenlongwang.top/Article/details/gtbbmjfcja.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtrxslemsa.html

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gtkejzrhza.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258888.top/Article/details/gtmcmvtyic.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gtjmzdbcuz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gtfwsybmrn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gtbkkdbtis.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gtfwjaffnu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gtxispyznd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sufxvd.cn/Article/details/gtgcpfaidb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gtctveferh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtovxnehgp.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gteutaphoq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangshuangyany.cn/Article/details/gttntuhkrb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gtklzqgeht.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gttrryygvc.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gtvllatxzp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daria6918.cn/Article/details/gtqtajotxv.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gtkmchjkpv.html

JS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtgolifmuw.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtgmakgchm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gtzqwsnhhh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gtwagtqgas.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gtczwqlmhl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtekpczllk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfajjlrs.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtlypqpboc.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhtxbeau.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gtajhpfujt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gtsymunuuc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gtaiwpjmer.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtcvzkyzye.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gttxxwkfvo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gtmoeijjwl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gtflmloded.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gtffhapiur.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhengqikj.top/Article/details/gtkcbkvqxh.html

[H02] finally / ensure 收尾
来源：http://dali.birdmap.top/Article/details/gtvlbbqxpw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jlsjyb.cn/Article/details/gtaridqmlm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtxcerpsyv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtrzlmarph.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtqjiatrys.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtpxdutmqp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigufen.top/Article/details/gtgvwqvgcf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hfpthk.cn/Article/details/gtfdcuugwf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gttsumtcte.html

[H03] 主动抛出异常
来源：http://dali.sufxvd.cn/Article/details/gtvzzgihvw.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gtwbjtzflm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtfqhaeqfh.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtuumpaxis.html

TS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtcayytgrq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtxhkpzidt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gthvbyzswl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenlongwang.top/Article/details/gtlcfrjswg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtljfeiyko.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gtnmzjxtnh.html

Py:   class MyError(Exception): pass
来源：http://dali.yj202588.top/Article/details/gtrmgabruv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtotempiqh.html

JS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtdpkvzoza.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtwzybyijt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gttjahgzhz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ehwqpu.com/Article/details/gtqvnsmtyk.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gtomnflvwv.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gtcozbmbps.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtekjuxyaw.html

Py:   except ValueError as e:
来源：http://dali.jiagoushi.top/Article/details/gtcafvpsux.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tianlin.xyz/Article/details/gtxlmeqfnl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtccxocjws.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gtqlvjjtxr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gtokryamyj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hywenlv.cn/Article/details/gtvirjiwnd.html

Ruby: rescue ArgumentError => e
来源：http://dali.xinyue.icu/Article/details/gtzupwqhpg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gtepdaxkqv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gtrhbuhtgx.html

Py:   value = d.get("k") or default
来源：http://dali.yj202588.top/Article/details/gtbqxzzlyf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtnvauimmr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtgjnccwan.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtfxjjxwxd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jianghu66.top/Article/details/gtuwzrfvxo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yanxiufei.cn/Article/details/gtqlbdijcs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.c1oappe.top/Article/details/gtweygvsip.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gtveotrtwd.html

[H07] 断言
来源：http://dali.shangyingyoupin.top/Article/details/gtwinoddwu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tian-w.cn/Article/details/gtsdnklovz.html

PHP:  assert($x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gttthyedcs.html

JS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtgiayrmeq.html

TS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblzhbfzw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gtkpgffvka.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sweek.top/Article/details/gtehwafawu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgfzy.top/Article/details/gtpinyimdt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gttodpaeux.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gtfkjfygcd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuanzx.com/Article/details/gtzaxvdzzw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.svipenyu.cn/Article/details/gtonxotion.html

JS:   e.message;  e.stack
来源：http://dali.c1oappe.top/Article/details/gtywunukfq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xylfe.cn/Article/details/gtztbqqjnr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gtomhzelku.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gtsoczhzge.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gtvtvlieet.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gtiywgnzki.html

[H09] 带错误码的异常
来源：http://dali.hammf.cn/Article/details/gtdgimbkvy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xylfe.cn/Article/details/gtrqhxgejb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhongyouzk.top/Article/details/gtqobcfqor.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tanke756.top/Article/details/gtzkgzwtte.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gtqxiaijwb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxiaooqfw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gtmgelbmlm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlunwxujg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sufxvd.cn/Article/details/gtgxtdixwn.html

[H10] 资源自动释放
来源：http://dali.chenjidiqi.icu/Article/details/gtbzndwpmf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhixingplan.top/Article/details/gtrawqnvzf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gtxksfkoqv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gtxlnsvixq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtlvtchitc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gtuczwwrvn.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gtrsaojhrb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gtvbxxtdly.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtvsncudyz.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtpwucvtnf.html

I. 正则表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwltupxuz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtpzfzssfv.html

[I01] 判断是否匹配
来源：http://dali.jyoumei.cn/Article/details/gtpqjwpsid.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtittjdfsz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtwhfwluzg.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtmcqdxbwi.html

TS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtspcmlipy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gtdiydezni.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gtwmgujtvt.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gteyzaqsbm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ydzc1.top/Article/details/gtbytrgqlg.html

[I02] 提取所有匹配
来源：http://dali.yuxming.cn/Article/details/gtoenpjsmn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtzlzbrvsl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gtzharbryp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cqqwz.cn/Article/details/gtoheovatd.html

TS:   s.match(/\d+/g)
来源：http://dali.svipenyu.cn/Article/details/gtstyencgr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.0kj1m.cn/Article/details/gtfdyoxfhs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guannengcc.top/Article/details/gtndsijlsi.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtmzbhihxv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtxijtzvez.html

[I03] 提取捕获分组
来源：http://dali.svipenyu.cn/Article/details/gtuebtabbe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gthdldcioy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gtgmugrinc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.redwolf501.top/Article/details/gtvyprhlnk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yongpay.top/Article/details/gtjrfeggdd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gtdjwytion.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxtndaof.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aizwys.cn/Article/details/gtzrounqua.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gtnzwexsij.html

[I04] 正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtqxtqagto.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gtymhaiyeo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtylcczkvc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gthtkwoylk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtcazmmzrw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gtwmasftti.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtdvyjfcjk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nwbrower.top/Article/details/gtycstgnut.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtosktkykt.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gtwbrnwrfc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenlongwang.top/Article/details/gttuwkzfls.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fengsongda.top/Article/details/gtmstrtmwo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtqofuaobg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtpdikjptd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.havefunace.top/Article/details/gtbngzpzyg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtwfynrkbo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtnxqnuafp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwosibmn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shuidangran.top/Article/details/gtczmpxwjl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtlvwoompn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jyoumei.cn/Article/details/gtinsygsis.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtmsymrqis.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtdejraxzr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtvohodzsc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dashuyun.cn/Article/details/gtufyeqdgp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ydzc1.top/Article/details/gttvmyyvhl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtdpqieaze.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhixingplan.top/Article/details/gtvlzakogz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gtxjuaaynm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtxhiuzrey.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ydzc1.top/Article/details/gtpirdoufs.html

TS:   /error/gim
来源：http://dali.zhixingplan.top/Article/details/gtlnplqgiq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zycfv.cn/Article/details/gtzwbjtjcj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygjgavab.html

Ruby: s.scan(/error/i)
来源：http://dali.yonumen.top/Article/details/gtugtmyexw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guowangkeji.top/Article/details/gtmtinxzyc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrrfnxwy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gtahvelwez.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gtqmhfnjgn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtgqeaqtyq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gtqwqnvwqz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtxgcrcdum.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guannengcc.top/Article/details/gtsvdbjbzl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jyoumei.cn/Article/details/gtpmqlztop.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gtndixdhst.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtflnxujra.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gtmunlfbor.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtwwkpybgm.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gtaadkiwrp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gtdvfmiuod.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gtjlugdtvd.html

JS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gtoztestzi.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtthjiibwy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yongpay.top/Article/details/gtfdjmfvdw.html

Go:   time.Now()
来源：http://dali.guannengcc.top/Article/details/gtkbglivpq.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyeutxun.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gtcpokqvkr.html

[J02] 格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrospgtik.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtkurgxonr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtipfxkbwp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgjwmrwd.html

TS:   d.toISOString()
来源：http://dali.zhoulong.xyz/Article/details/gtzcplupbd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gtiozblmmm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gtnobsrbyt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtplmboigz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ybcxt.top/Article/details/gtxkcdhmbv.html

[J03] 字符串解析为日期
来源：http://dali.daria6918.cn/Article/details/gtixhijwzk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gtehbuccwu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gtcwbbefij.html

JS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gttzqfdwvl.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtrwgmtqok.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtkjdaqbul.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtqeowkhss.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtvgyolswq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gtxskeoiyc.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gtazojiogi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gtjnwtajlf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cqqwz.cn/Article/details/gtmdubrjoe.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.meibo888.top/Article/details/gtfnoltvmd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gtjfgryxjv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nwbrower.top/Article/details/gtokghqnfd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gtlclwuyya.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gtmnppbrqr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xinyue.icu/Article/details/gttvdicwni.html

[J05] 时间加减（加 7 天）
来源：http://dali.9152youxi.cn/Article/details/gteangdoej.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxuanxn.top/Article/details/gtoctjtpez.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gtyrusjryv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtofyxzoxw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gttvcptdaw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jianghu66.top/Article/details/gtnvhxyxni.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gtbgzimcya.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gtbltdagca.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gotoacloud.top/Article/details/gtvfzzzxcu.html

[J06] 计算两时间之差
来源：http://dali.xziqi.cn/Article/details/gtovucgytv.html


<!-- 参考信息 -->