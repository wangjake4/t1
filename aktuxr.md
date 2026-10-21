代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gtxnbwlgsp.html

Ruby: def self.f; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxjjprls.html

C#:   public static void F() {}
来源：http://dali.yj20258888.top/Article/details/gtzqnqvqpc.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gtibfrtvnq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tian-w.cn/Article/details/gtikuasboy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gtneicjrbj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gtpifswhxx.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gtoolrkhyh.html

Java: interface Shape { double area(); }
来源：http://dali.gogol.net.cn/Article/details/gtsjaifioj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gtqvernhgk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gtmhbntrqf.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gtjdsuycvv.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gtkfvwzzxj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.bjfxy.top/Article/details/gtpptsjfbu.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gtdkozprpp.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gtmwkwtcdc.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtehgdlmcd.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gtyxzmtihn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daxiang520.top/Article/details/gtmahbjcix.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtplxvuijw.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gtjakseetu.html

[G11] getter / setter
来源：http://dali.shzxlz.cn/Article/details/gtkkpbceil.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gtbgzvkrae.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtyalbfsla.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtyctejwsd.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtkgpgxkae.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtvwnmczzi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtuieoibad.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gtthihthfu.html

C#:   public string Name { get; set; }
来源：http://dali.chenzaomai.com/Article/details/gtfuulckjn.html

[G12] 对象转字符串
来源：http://dali.tian-w.cn/Article/details/gtdlaqbnoi.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtwstogpwg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtfspgxjuv.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtlwdzskmf.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtfuboqnly.html

Java: @Override public String toString() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtiaxhdmge.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtzemdnsvd.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gtogdfjdge.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtgfamtmsc.html

[G13] 判断对象类型
来源：http://dali.tian-w.cn/Article/details/gtujfmsjzn.html

Py:   isinstance(u, User)
来源：http://dali.vqdsnc.cn/Article/details/gtjebjdrkq.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtpkcrcaqn.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtwwxkxeys.html

TS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtfuhymslv.html

Java: u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtvwmymzai.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenjidiqi.icu/Article/details/gthflepube.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gtpyewkcgj.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gtlbqslwuq.html

[G14] 数据类 / record
来源：http://dali.havefunace.top/Article/details/gtzpvsmpjl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gtvuudkmvq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwqmbgff.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhongyouzk.top/Article/details/gtrhpeopty.html

TS:   type User = { name: string; age: number };
来源：http://dali.gzhubu.top/Article/details/gtlfbabryn.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gtxcpmozwi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gtzevixuql.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtmfstjrkb.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gtaqalawjk.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtvnjborse.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jyoumei.cn/Article/details/gtdhgofghn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tanke756.top/Article/details/gtdceykqoq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.andypj.xyz/Article/details/gtovlwvsvp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gtcqjxvlsm.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtpfinwhjj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gthwbrcdok.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnxiangtu.top/Article/details/gtfdgzznyr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgmdufpa.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gtpkuorsdj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gtztkaorkn.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gtbmwaifqx.html

JS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtveworwvt.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtlqodhyqw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxuanxn.top/Article/details/gtnuowctxv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hywenlv.cn/Article/details/gtjnugujar.html

Ruby: obj.instance_variables
来源：http://dali.meibo888.top/Article/details/gtrtputiic.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gthuirrnwn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtpsmbdjja.html

H. 异常与错误处理
来源：http://dali.havefunace.top/Article/details/gtuawjbtbs.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtuzaxflfs.html

[H01] try / catch 基础
来源：http://dali.9152youxi.cn/Article/details/gttvwfgmos.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gthbcltvzj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gtsnslgroe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtijguvxlk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtafmxkilv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gtjajyxrbm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtsulamlur.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzsmqtyk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gtdojmzjji.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gtommxbaor.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gtxigljimz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtvzricaci.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtnsuuhlre.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikopqjas.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpsxqpmnp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhixingplan.top/Article/details/gtlguianty.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gtppgxmkfp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtofynxeho.html

[H03] 主动抛出异常
来源：http://dali.9152youxi.cn/Article/details/gtybuglqvo.html

Py:   raise ValueError("错误信息")
来源：http://dali.yangfankeji.com/Article/details/gtkimvnolf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtjifwcdle.html

JS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtxwedrtoj.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtaxjbvbmg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtbpxpgdyn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gtshjgwzwl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gtyqlwpbbt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtkvqfqaxm.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gtwqtuajeq.html

Py:   class MyError(Exception): pass
来源：http://dali.316326.xyz/Article/details/gtlelqgols.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtlfpoakzs.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gtjzdwfjbq.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtzlgbehdx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtaduqvmcl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jiagoushi.top/Article/details/gtslhheywu.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gtmezrsatd.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gtqrfzdbyn.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gtggoenyln.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gtfjponjbc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gtatfaqtli.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtvrqaukwp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtlaefizxj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtuyahtoup.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.snrcjt.cn/Article/details/gtkdpykvkv.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gtiypwqjcs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hysaishi.cn/Article/details/gtcfzmpqwn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tianlin.xyz/Article/details/gtlbrnxrxi.html

Py:   value = d.get("k") or default
来源：http://dali.xuetiantiany.cn/Article/details/gtvrjiseyw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ivvv.top/Article/details/gtntduckyy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gtzhfzpcoe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtqwnfjhnd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gtdurcojay.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gtkoedftcc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jyoumei.cn/Article/details/gtzqgivmzz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtdkjtjcho.html

[H07] 断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxftuvfe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtsygtomge.html

PHP:  assert($x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtbkrcpjbq.html

JS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtvtrzdram.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtunnhqmee.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwompinah.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gtlpzdiawh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gtnxlrsjtr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpllalfc.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gtxlmaaiog.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhiwuduotai.top/Article/details/gtihcvgobk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpikafhlx.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gtkbknacvl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yonumen.top/Article/details/gtausywztm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gttbxsyhhx.html

Go:   err.Error()
来源：http://dali.cheryme.top/Article/details/gtntkzmxmx.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangdashe.top/Article/details/gtqfiiymue.html

C#:   e.Message;  e.StackTrace
来源：http://dali.quarkkingdee.top/Article/details/gtkzccegdi.html

[H09] 带错误码的异常
来源：http://dali.chenlongwang.top/Article/details/gtfawdvihj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gtkppiqudn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gtvyysnnom.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gtzifqwjur.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gtkiaskiqx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.9152youxi.cn/Article/details/gtssernnhn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtgoophfjz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj202588.top/Article/details/gtzmfplzgv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ppjwa.cn/Article/details/gthjlsbmql.html

[H10] 资源自动释放
来源：http://dali.hongshengwenyu.top/Article/details/gttpnufxhe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gtfbrblmez.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gtsqjeezha.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtxsbziewh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtlqqhpjbp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.kuanghao11.cn/Article/details/gtklvzkidd.html

Go:   defer f.Close()
来源：http://dali.andypj.xyz/Article/details/gtjzhyxkpz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gtbjinlent.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtjeaqorng.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtttvusldp.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtbbqezcnq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtjfetimxe.html

[I01] 判断是否匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtuomrbmbt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtalcrhorc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtkapsjlih.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtjsfmfqgo.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtttnephjn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gtzmbvtvpf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yongpay.top/Article/details/gtklokndnd.html

Ruby: s.match?(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtstaydfer.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gtaoolkvgw.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gtipggxkft.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gttqqpzuyd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sweek.top/Article/details/gtrbvkkzmd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqwmfacw.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gtauasiutx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gtendjjuue.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gtqkumlvfu.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtxhzeifzj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gthpkubhwd.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gtdetaikuk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gtyckienzi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gtljreqjxn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgfzy.top/Article/details/gtxchqkdtz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.mhx1999.top/Article/details/gtxhelaxdl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtzcmxvqrm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gtkzrinrzs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guowangkeji.top/Article/details/gtbbhotyjm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gtmgidrszv.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gtarcaawrm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daxiang520.top/Article/details/gtbhcfrduc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gtewxztics.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gtznnetutu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtcunrudwo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtpuzxzzpt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.havefunace.top/Article/details/gtlbhewyzw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtggeexokl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtlejceokr.html

[I05] 按正则拆分
来源：http://dali.ydzc1.top/Article/details/gtsaexzhxm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hfpthk.cn/Article/details/gtrvewexda.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gtoaqrzcwn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtrnofesxn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtfwxxjaub.html

Java: s.split("\\s*,\\s*")
来源：http://dali.redwolf501.top/Article/details/gtmjowzvro.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gtsqtfhrso.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtpwqgiwqf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fzhhl.top/Article/details/gtnzsqynao.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yanxiufei.cn/Article/details/gtsjxeorxo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtwgapusqz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tianlin.xyz/Article/details/gtlhgsyxck.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gtmxdkhipj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gtamczxkcz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtgyehtngl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangtech.top/Article/details/gtquqdgegc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gtoiyrfbhv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtkqyhilan.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gttivreuiv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gtigyylkyg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gtzofowucm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daria6918.cn/Article/details/gtcecvxobz.html

TS:   /error/gim
来源：http://dali.svipenyu.cn/Article/details/gtewolfyrk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ppjwa.cn/Article/details/gthvbuxdgj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gtyftswyjm.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdeamokx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ppjwa.cn/Article/details/gtryyohuli.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtoieyxpin.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cashguo.top/Article/details/gtgokcdzyp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gteckjszvc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gthplbbpcc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtqvzwucxv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gtmqjfpljx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jiagoushi.top/Article/details/gtabhvfzzf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.mhx1999.top/Article/details/gtdcycskqx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtiedgpuvv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmidbdwqj.html

J. 日期与时间
来源：http://dali.gzhubu.top/Article/details/gtazsgpynb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtwrlrecnh.html

[J01] 获取当前时间
来源：http://dali.jiagoushi.top/Article/details/gthmdyeleh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gtkdutkfev.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtlihplrin.html

JS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gtheqoykhs.html

TS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtypodciut.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuanzx.com/Article/details/gtzggnjyvp.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gtbkwruqhz.html

Ruby: Time.now
来源：http://dali.ydzc1.top/Article/details/gtofxhgwke.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gtjphqeiwp.html

[J02] 格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtxohzkdrx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtxmsjtavg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gtijqdjbvr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pycfn.com/Article/details/gtjycgklxx.html

TS:   d.toISOString()
来源：http://dali.daria6918.cn/Article/details/gtyeolqhxe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gtgvlekvom.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zycfv.cn/Article/details/gtxuiemoga.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtsabnbrmt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gtpfgfromx.html

[J03] 字符串解析为日期
来源：http://dali.xinyue.icu/Article/details/gtirkzzjrl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.meibo888.top/Article/details/gtotzmlvtn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmhmtcoa.html

JS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtnibtkmbw.html

TS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtazvpubwo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtutqjgcia.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtyaurhtjt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtihjlmtdm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hysaishi.cn/Article/details/gtgnaczikj.html

[J04] 时间戳与日期互转
来源：http://dali.aizwys.cn/Article/details/gtnwpaujtv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cucudq.cn/Article/details/gtdloboozc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dianchejie.cn/Article/details/gthkhohnfq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtjxhwmbzs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gttshslfre.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hysaishi.cn/Article/details/gtjjflcepf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gtsaovyxum.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yangfankeji.com/Article/details/gtemumbnvg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gtcufoogcf.html

[J05] 时间加减（加 7 天）
来源：http://dali.svipenyu.cn/Article/details/gtighnczjo.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gttwzhqbvw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.redwolf501.top/Article/details/gtthwynvuk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gtcfvcvabs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtwvwtobbe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtgvhzrptl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gtarweghtk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yueranfly.top/Article/details/gtmosruhpa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nwbrower.top/Article/details/gtqadupcjl.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gtrloqlmgm.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gtaihnuegz.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtbjgnmbtg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gtqcckdepq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhengqikj.top/Article/details/gtnjvzikqm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.kuanghao11.cn/Article/details/gtiyhxqeqa.html

Go:   end.Sub(start).Hours()
来源：http://dali.aizwys.cn/Article/details/gtgbkpraao.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yvedp.cn/Article/details/gtnhnyeppn.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gtpsgjfgfl.html


<!-- 参考信息 -->