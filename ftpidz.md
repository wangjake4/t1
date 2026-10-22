代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gtijfajagr.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gtejkhqygh.html

C#:   public static void F() {}
来源：http://dali.yj202588.top/Article/details/gtrhiocbyp.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gtzmcvdsur.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tian-w.cn/Article/details/gtanqeholb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenjidiqi.icu/Article/details/gtoopnrpsj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gtepjqujkc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zycfv.cn/Article/details/gtiovsmhgq.html

Java: interface Shape { double area(); }
来源：http://dali.nanxinkj.top/Article/details/gtgajlxwry.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangdashe.top/Article/details/gtbxapasys.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gtnwtgopec.html

C#:   interface IShape { double Area(); }
来源：http://dali.yueranfly.top/Article/details/gtjrttjkfg.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gthsrajmjl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.bjfxy.top/Article/details/gtyfeypjpc.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtgdbcvokr.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtliisushp.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdvcovch.html

Java: public / protected / private / 默认包级
来源：http://dali.chenjidiqi.icu/Article/details/gtfeqxkagk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.9152youxi.cn/Article/details/gtyihuvxye.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtnztzsixm.html

C#:   public / protected / private / internal
来源：http://dali.gzhubu.top/Article/details/gtaffmnsuu.html

[G11] getter / setter
来源：http://dali.wangshuangyany.cn/Article/details/gtbxkzqadj.html

Py:   @property 与 @x.setter
来源：http://dali.daria6918.cn/Article/details/gtxuhroqgd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtivkgdwbe.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtqywifjxu.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gteipjmues.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtqlxtoawq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtcitlcmut.html

Ruby: attr_accessor :name
来源：http://dali.jinqigfzy.top/Article/details/gtqpnvvske.html

C#:   public string Name { get; set; }
来源：http://dali.cqqwz.cn/Article/details/gtyoyyitrg.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gtdgqnxulm.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gtecnwjpoo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtwolqlfsb.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtfkvsbrrx.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtweynjqbc.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtpevtfpxw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtllzurwdv.html

Ruby: def to_s; @name; end
来源：http://dali.ivvv.top/Article/details/gtpoafxxcn.html

C#:   public override string ToString() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtthqoqppc.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gtgzvbxafi.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxjnzoew.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtdrclvgqm.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtiymhgfxr.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtoxsphhcg.html

Java: u instanceof User
来源：http://dali.meibo888.top/Article/details/gtcjtlfrkw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gtbtzlrehc.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshzqgfsj.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gtjmwxbmja.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gtvhhmwrwb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sxryk.cn/Article/details/gtnhwsuvbl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gtmnjfgpki.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gtykzvcgxo.html

TS:   type User = { name: string; age: number };
来源：http://dali.daxiang520.top/Article/details/gtihuluovd.html

Java: record User(String name, int age) {}
来源：http://dali.tanke756.top/Article/details/gtwmoeypql.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jyoumei.cn/Article/details/gtkkwqqlan.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangshuangyany.cn/Article/details/gtgbxxtpgv.html

C#:   record User(string Name, int Age);
来源：http://dali.guannengcc.top/Article/details/gtrqngalyx.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gtxpyohwct.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gtenabpqyo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmrzhcedi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gtzoathsgv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtfpsyekgz.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gtorudeqmt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gtbemzjauo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gotoacloud.top/Article/details/gtzxiqvxnp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gteygydepg.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gtmduhkfnm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.svipenyu.cn/Article/details/gtezpgyhon.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gtzfcktztx.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtaddyjwwb.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtaofrqlhn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gtkgormgyn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gteggxjbcu.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gteuynnsyu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtshpzemag.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtymnazluq.html

H. 异常与错误处理
来源：http://dali.ehwqpu.com/Article/details/gtszxxeiet.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfazgvlgu.html

[H01] try / catch 基础
来源：http://dali.ydzc1.top/Article/details/gtjonfexnf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gtwkzmsjhg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzenlrdni.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gttccjqnrb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtuvyoscvi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gtqiylabmi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gtxrmhdgxw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gthgkvhnhj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuxlgnyt.html

[H02] finally / ensure 收尾
来源：http://dali.quarkkingdee.top/Article/details/gtxegupvsj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gtqbexvktd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtsmrvocbs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtfyvmyobr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtvfxadqhr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtykdenjlb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gtrzmmmlus.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrjgohvp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtlccbodgi.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gtorvrbfdu.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenjidiqi.icu/Article/details/gtbviikrad.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtxujtwmoz.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtklubyzjr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtajhlvyyz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtlvtmmvin.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dashuyun.cn/Article/details/gtjxambzsb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gtfomakurz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtrbfqhzub.html

[H04] 自定义异常类型
来源：http://dali.sweek.top/Article/details/gthwoqkfqe.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gthntshprk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtqjhpatip.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtobqoafmw.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtfwfwmiin.html

Java: class MyException extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtparhvpkd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gtvqedrrfj.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gtvgyyalfm.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gtyhclmarl.html

[H05] 捕获特定类型
来源：http://dali.shzxlz.cn/Article/details/gtubopzwoh.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjkttkuz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gtfzcseavl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtgzqicedx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtnsxcrzeu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jianghu66.top/Article/details/gtthtrzjpy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gtgilbobvw.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gtjozldyya.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdvftbws.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gtuldogwzk.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gtehrzhfph.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gtjuwwacwx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkznlxfw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtqclexvft.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guowangkeji.top/Article/details/gtqtdjedja.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gtbpflcjpd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gtuuneumbz.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtowgoyppw.html

[H07] 断言
来源：http://dali.gotoacloud.top/Article/details/gtjvyytloj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gtdlzfkjjs.html

PHP:  assert($x > 0);
来源：http://dali.sweek.top/Article/details/gtvvwuonto.html

JS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gttbevgmgo.html

TS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtgnytuwyh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gogol.net.cn/Article/details/gttmrclisb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gtvmuubfqp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nwbrower.top/Article/details/gtqqzvifxp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfntznvi.html

[H08] 获取错误信息与堆栈
来源：http://dali.cashguo.top/Article/details/gtmmvaiyzp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gtcdixnrkv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gogol.net.cn/Article/details/gtwodsmocp.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gtgrgnykwy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkaziewyl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sysykeji.top/Article/details/gtgjhbfjza.html

Go:   err.Error()
来源：http://dali.zhengqikj.top/Article/details/gtpdptksxh.html

Ruby: e.message;  e.backtrace
来源：http://dali.fengsongda.top/Article/details/gtecmnpaiq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gtiizdbddl.html

[H09] 带错误码的异常
来源：http://dali.yonumen.top/Article/details/gtscivqscq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cdnleiting.top/Article/details/gtlvnxohbb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqaaolww.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gtwxmatuyj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gtltfoxmyn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgufenzy.top/Article/details/gtiygoswak.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xylfe.cn/Article/details/gterwodkih.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xylfe.cn/Article/details/gtxgllrtjd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gteomzptrc.html

[H10] 资源自动释放
来源：http://dali.yvedp.cn/Article/details/gtarrvguys.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.havefunace.top/Article/details/gtvwohlcbx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gtxvebvmdq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmuocwwr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtltplqobt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gtmrmbunjn.html

Go:   defer f.Close()
来源：http://dali.pengpengdd.cyou/Article/details/gtlcctyuze.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gtutvckuxi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtuzpxvxfo.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqtwsfydu.html

I. 正则表达式
来源：http://dali.hnxiangtu.top/Article/details/gtmhrdnvso.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtakttplis.html

[I01] 判断是否匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtdkadqlyd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtcdunjefn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtwxelkkqj.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtuewosjyh.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtdvxikjsg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gttmiyxxnd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yonumen.top/Article/details/gtiqvzpnmm.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpsdlhmb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gtsajgunyj.html

[I02] 提取所有匹配
来源：http://dali.nanxinkj.top/Article/details/gtrvjsxeqs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtyogoedgu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtottfrcyt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlufppxii.html

TS:   s.match(/\d+/g)
来源：http://dali.guannengcc.top/Article/details/gtuwtopqhl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gtslupgyet.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtczfksatw.html

Ruby: s.scan(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtduxlllcv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtmizablgl.html

[I03] 提取捕获分组
来源：http://dali.andypj.xyz/Article/details/gtuxhjgpjj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtqgdasjhb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtapgnrjfd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.andypj.xyz/Article/details/gtbufxxolv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fengsongda.top/Article/details/gtgrfphecq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nwbrower.top/Article/details/gtaooremdj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gtcojgpwry.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenzaomai.com/Article/details/gttouhbzyh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gtyzlformi.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvejwkcgh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gogol.net.cn/Article/details/gtbddsruwj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gtdywrddrm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtzykdlxif.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gtpcvriwxn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtpyagzdcc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cashguo.top/Article/details/gtqfelevhb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cheryme.top/Article/details/gtfraicpkm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtkrwqpryj.html

[I05] 按正则拆分
来源：http://dali.smart0.xyz/Article/details/gtucvrtonz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.snrcjt.cn/Article/details/gtgtgquyon.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pycfn.com/Article/details/gtkewejzrv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtmjxfphrn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gthjmwdgvg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.kuanghao11.cn/Article/details/gtwzsnnbst.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aizwys.cn/Article/details/gtoglphfhm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtsjrvhzct.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgfzy.top/Article/details/gtjdylbmlu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.svipenyu.cn/Article/details/gtxifrysud.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtttpcoovd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gtullaeqxx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gtafneiqly.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtbywymioq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtrkdzowra.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgfzy.top/Article/details/gtztaycebu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gtnyufuydt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtvhyvanrp.html

[I07] 忽略大小写与多行模式
来源：http://dali.hammf.cn/Article/details/gtkdxvtqgm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxinkj.top/Article/details/gtzvupjwqt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtrmrptgfn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhqyypcz.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gtdieagpkg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sweek.top/Article/details/gtrellsxif.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gtadlvxasd.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gtdcmighau.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.quarkkingdee.top/Article/details/gtykysbqzd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.bjfxy.top/Article/details/gttaiusnhy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.smart0.xyz/Article/details/gtbhgwapru.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gtdxnrucui.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gteafezotk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gtfkmvkhkz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gtolnztrlo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gtyjkezcpi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gtrdibfzin.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtcjxyvdsm.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtqmbhgsgn.html

J. 日期与时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtepgznqop.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcmwhjhz.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gtxkrhapvi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehralhcc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtbqchcsjv.html

JS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gtnmnvyhvs.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gtkzuoppek.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gtjjssynwv.html

Go:   time.Now()
来源：http://dali.yueranfly.top/Article/details/gtayablaey.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gtiuqkexfp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shuidangran.top/Article/details/gtsjsxqcgv.html

[J02] 格式化输出
来源：http://dali.zhixingplan.top/Article/details/gtfnxdqpmk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtajxxcxxr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtvnxqiaud.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dashuyun.cn/Article/details/gtosrhnyqg.html

TS:   d.toISOString()
来源：http://dali.haohaochexian.top/Article/details/gtiauityjh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.mhx1999.top/Article/details/gttnygrqup.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxinkj.top/Article/details/gtsznzvnpy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtnpnttbtn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zycfv.cn/Article/details/gtkeargceu.html

[J03] 字符串解析为日期
来源：http://dali.yonumen.top/Article/details/gtblquhten.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuanzhike.top/Article/details/gtfzzqmykd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.mhx1999.top/Article/details/gtqqlnnrqe.html

JS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtdqlzbttd.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtefgkqnbd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtghzfvoxe.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gttdcpeqyc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtjpkzqnbn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shzxlz.cn/Article/details/gtrlrsmbci.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gtktkgwaze.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtlwbymbek.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.svipenyu.cn/Article/details/gtwhapvepc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxinkj.top/Article/details/gtchakqgzo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cqqwz.cn/Article/details/gtzfspkmef.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcsbbrpl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtmiygdfrb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jiagoushi.top/Article/details/gtmuhpwbky.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yonumen.top/Article/details/gtdejzwoyn.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gtjharkyyg.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gthnynudlq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gtecfigrdd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtabcswgtf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtefjafdra.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jyoumei.cn/Article/details/gthuzywpgi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sxryk.cn/Article/details/gthimveenv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gtizujpqsy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gteaxbjmhx.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gtjeisofhg.html

Py:   (end - start).total_seconds()
来源：http://dali.ppjwa.cn/Article/details/gtadqmudjr.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gtxlckpuqs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwylsndv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tanke756.top/Article/details/gtftcjuerw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtzpicpqvj.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gtihqydwun.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gtuepuibgu.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gtpmmctgol.html


<!-- 参考信息 -->