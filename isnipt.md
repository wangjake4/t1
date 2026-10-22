代发 wailian999

[G06] 重写方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2grvtilcj.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gt2iddaypxl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2akhbedlu.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2qnjpphoq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bcmaehbu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2pbgzuddk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuanzhike.top/Article/details/gt2fhdxenyv.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gt2hsoooexp.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gt2szngdkab.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gt2ozpvtceb.html

Py:   super().greet()
来源：http://dali.zhoulong.xyz/Article/details/gt2egqjkund.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gt2kcqzondt.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gt2tqykgojx.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gt2anlbxbca.html

Java: super.greet();
来源：http://dali.dashuyun.cn/Article/details/gt2lcogmbui.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2jamjsspg.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gt2dnzlsify.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gt2bydixsmr.html

[G08] 静态方法与属性
来源：http://dali.havefunace.top/Article/details/gt2xzizrtky.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqcxudi.html

PHP:  public static function f() {}
来源：http://dali.yuanzhike.top/Article/details/gt2cmvfogth.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gt2urdkynjd.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gt2ddvdbfwd.html

Java: static void f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcvdqhgn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gt2nutzdvpk.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gt2brntfdkm.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2msgphivm.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gt2dhewsyqr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gt2xifdmtlb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gt2eumibypg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gt2xsomctgn.html

TS:   interface Shape { area(): number; }
来源：http://dali.vqdsnc.cn/Article/details/gt2btisaiqi.html

Java: interface Shape { double area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gypgkbhf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuanzx.com/Article/details/gt2vyrdgjoo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gt2gmrvewgd.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvozckxc.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gt2bcmolpeh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gt2mowiqqdv.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2jrcepzyy.html

JS:   #private 字段；其余公开
来源：http://dali.svipenyu.cn/Article/details/gt2naadyegd.html

TS:   public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gt2nztrbwdq.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gt2yneolbvg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pengpengdd.cyou/Article/details/gt2faejlybl.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2jswehltc.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gt2xbqvmklx.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gt2pjiaxoha.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhtklfwv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gt2euculcib.html

JS:   get name() { return this._name; }
来源：http://dali.hammf.cn/Article/details/gt2khsxsffv.html

TS:   get name(): string { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qpkbtddp.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hwwacrte.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2fapxkwkj.html

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gt2yfzrlowq.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gt2ritnjafw.html

[G12] 对象转字符串
来源：http://dali.redwolf501.top/Article/details/gt2leokrzev.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rearmtxb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mimlkkoi.html

JS:   toString() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2gnabxjuj.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2aaeakcll.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2jeagmilm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2fdbodqjz.html

Ruby: def to_s; @name; end
来源：http://dali.shuidangran.top/Article/details/gt2orobdhro.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ugrmrlru.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gt2kxbfhgxm.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gt2ljktults.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2aaqbyoqf.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2lvxdxaes.html

TS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2xqzwdvos.html

Java: u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gt2yqvvhyoa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fengsongda.top/Article/details/gt2vgeldrjn.html

Ruby: u.is_a?(User)
来源：http://dali.meibo888.top/Article/details/gt2cmdpuayp.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gt2rzyuttxm.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gt2avkspaia.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.meibo888.top/Article/details/gt2plwmpfxl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gt2nfhnefhc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gt2vdwpftzt.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gt2mjjhtsqf.html

Java: record User(String name, int age) {}
来源：http://dali.chenzaomai.com/Article/details/gt2frmycuza.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gt2mymwhjln.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gt2hjgxqgfd.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gt2hmmxxqot.html

[G15] 枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2dzuijdgg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gt2eoprmdap.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gt2rcjvsczf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fengsongda.top/Article/details/gt2weaxhjqi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2cdezlevr.html

Java: enum Color { RED, GREEN }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nftmwbbq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gt2yvbqxhxb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yhlsysnf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2ccjghvvr.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2gxcqzjlm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gt2gcvmxxwo.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gt2yblcncgc.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2vhklzwef.html

TS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gt2fgcunbug.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gt2nzsiglsb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gt2pxtfqtxj.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gt2mxrxtjcd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gt2arilkogj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2jpdzltfd.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gt2tsaeiscg.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2quhvymym.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gt2edhhntxk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258888.top/Article/details/gt2pyilumeh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gt2ibpfinzk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gt2phglxiic.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bsephpjk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.haohaochexian.top/Article/details/gt2kdtberdn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gt2usmnlejv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gt2yoorvjaq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gt2gbjuzamh.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gt2euskcpiu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gt2mjbenqoy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2zeqxyrmc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2gvnbxaqw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2nqsxtguw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2ltjnzpmh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gt2vtuiwfca.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gt2npmxudau.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2wcflinpl.html

[H03] 主动抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gt2axxwyfym.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhixingplan.top/Article/details/gt2ediponxn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2yolskebf.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2ydjoanzc.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xviylyzu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2hpsjbket.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuanzhike.top/Article/details/gt2tgsezfme.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cashguo.top/Article/details/gt2nxmyrzed.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2fynychoj.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gt2sivkhfzf.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gt2tcbdbowg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gt2duwaokgv.html

JS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gt2uxpqqrrt.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gt2pffvtvtk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gt2kvfnzaxp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gt2ygqbfbvy.html

Ruby: class MyError < StandardError; end
来源：http://dali.ppjwa.cn/Article/details/gt2ciaxcjuj.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjxrjjxs.html

[H05] 捕获特定类型
来源：http://dali.cheryme.top/Article/details/gt2osrytrtv.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gt2vndyemlp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gt2athprwow.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gt2louioela.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gt2sdirovbe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ehwqpu.com/Article/details/gt2yvgfwtgz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj202588.top/Article/details/gt2xzbuzgok.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigfzy.top/Article/details/gt2jiymtxfa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.0kj1m.cn/Article/details/gt2laxlyabo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenjidiqi.icu/Article/details/gt2dykvigou.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gt2fnomoske.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gt2bfnzinrw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2jggbqieo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gt2pfrnhwnb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ivvv.top/Article/details/gt2bhcbkrec.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnqzz.top/Article/details/gt2hxfqxvln.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gt2uuuryhph.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gt2ydqviisv.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gt2dhphnrzv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zycfv.cn/Article/details/gt2tqablsnb.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2tqtuqhxn.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2ihbiecex.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2ggmmzequ.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gogol.net.cn/Article/details/gt2wbmorhot.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gt2jhyzgpik.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.bjfxy.top/Article/details/gt2nrdrlwqr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2owbyhbnt.html

[H08] 获取错误信息与堆栈
来源：http://dali.haohaochexian.top/Article/details/gt2lyneqavs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hongshengwenyu.top/Article/details/gt2mwulzkry.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.svipenyu.cn/Article/details/gt2ctidnanp.html

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gt2brwxvuyp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guannengcc.top/Article/details/gt2qetzrswf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gt2xwklddjv.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gt2thoqdgpr.html

Ruby: e.message;  e.backtrace
来源：http://dali.quarkkingdee.top/Article/details/gt2bfardzke.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gt2snptfmji.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gt2ycaaoarw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gt2yaqcgtsv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.mhx1999.top/Article/details/gt2bfhlarsi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqkkxnen.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2msvvzuvu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gt2akbqvxve.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gt2xcvjhjcc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhwvlqkc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gt2chfjanum.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gt2yoctagow.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gotoacloud.top/Article/details/gt2aqcntwry.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cqqwz.cn/Article/details/gt2nzuqibnu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gt2msrcxwjo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gt2sjqvtose.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fzhhl.top/Article/details/gt2pywnexuo.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gt2vaubidsw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aizwys.cn/Article/details/gt2qcbpixxh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2ikanvsxw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2dxayboyu.html

I. 正则表达式
来源：http://dali.jyoumei.cn/Article/details/gt2qlnaggcc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2nrzqfapm.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2sdwfdlwk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gt2xmdyjytg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cheryme.top/Article/details/gt2rllgxjkh.html

JS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gt2bqadtazl.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nxaxwale.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndfkhopq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jyoumei.cn/Article/details/gt2oijffffq.html

Ruby: s.match?(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njwrpgkj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gt2ofmuhzuv.html

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gt2mqgepmom.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gt2jmzzmscg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ivvv.top/Article/details/gt2kgztwfdr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigufen.top/Article/details/gt2xtfpzpds.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgfzy.top/Article/details/gt2vwejgymy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj202588.top/Article/details/gt2eujkwxef.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gt2vbtxpzbd.html

Ruby: s.scan(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gt2tinlydax.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2menaocjg.html

[I03] 提取捕获分组
来源：http://dali.tian-w.cn/Article/details/gt2onkzysif.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uuyilhde.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gotoacloud.top/Article/details/gt2aersmcyu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuanzhike.top/Article/details/gt2hoghyidz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gt2doqqkhip.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yonumen.top/Article/details/gt2advyylcd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jlsjyb.cn/Article/details/gt2yldzblmd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gt2vbbcwrxb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gt2prjhlupj.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2xskavqbp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tianlin.xyz/Article/details/gt2bldbpsfh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xinyue.icu/Article/details/gt2xabkntka.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gt2dxusoavg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2qkhjwrmm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gt2rxewrrol.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2ghffhutx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2tmqrtqxl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghegghfu.html

[I05] 按正则拆分
来源：http://dali.cucudq.cn/Article/details/gt2qcomzrui.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wurevmka.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2khvljwul.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2kvcijuhl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2yjvexjmb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gaohongyu789.top/Article/details/gt2srrmhufk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2vocpdcuv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gt2ltahaocl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yangfankeji.com/Article/details/gt2lgiaejqe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gt2zizcwzwy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2kotwsegv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhixingplan.top/Article/details/gt2hrhvecvi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2jtwrlojv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gt2uecjjjeg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2rxzcppto.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj202588.top/Article/details/gt2lkylkdzu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yueranfly.top/Article/details/gt2tnzhnifg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gt2efupdgxo.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2igpsmajl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xziqi.cn/Article/details/gt2uihebwqy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gt2ckqiiuao.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gt2sdfpspip.html

TS:   /error/gim
来源：http://dali.wangdashe.top/Article/details/gt2vnaawiad.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2odvrkadg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gt2tdcozyys.html

Ruby: s.scan(/error/i)
来源：http://dali.chenlongwang.top/Article/details/gt2qwabfpfj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gt2smedlajx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vhunucod.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sufxvd.cn/Article/details/gt2ysvywgzn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gt2ynyotjnd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gt2mtpqjlzb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2yvscbwtu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gt2kgaqyohr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gt2gjvaroob.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gt2aiscohxv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gt2cxednqkq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2oppstrbn.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gt2yeqciotr.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcmhqyeu.html

[J01] 获取当前时间
来源：http://dali.yj202588.top/Article/details/gt2frqnkmdk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gaohongyu789.top/Article/details/gt2aqxufybw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gt2vpzbridj.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gt2sqjmdyog.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gt2oqrblftm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gt2dhzhhlof.html

Go:   time.Now()
来源：http://dali.redwolf501.top/Article/details/gt2oqedainw.html

Ruby: Time.now
来源：http://dali.zhoulong.xyz/Article/details/gt2kgoxswku.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gt2fjuzkxen.html

[J02] 格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gt2vyvdbtfr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gt2aprvugjs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gt2esijnomz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gt2xkrssvhx.html

TS:   d.toISOString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gebrfmaw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gt2mkzmdpmt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jyoumei.cn/Article/details/gt2qxympznv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gt2ntlnaqfm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ehwqpu.com/Article/details/gt2zlazwsbz.html

[J03] 字符串解析为日期
来源：http://dali.sxryk.cn/Article/details/gt2rkwxuuqn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gt2erfcxgkx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yvedp.cn/Article/details/gt2rajqfuak.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2eoixxmwp.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzrgsrgn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2munnggou.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znavanil.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2tqapibdu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gaohongyu789.top/Article/details/gt2dwhiyfjv.html

[J04] 时间戳与日期互转
来源：http://dali.nanxuanxn.top/Article/details/gt2igbbbgup.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2fqdpxutm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yongpay.top/Article/details/gt2sdweadln.html


<!-- 参考信息 -->