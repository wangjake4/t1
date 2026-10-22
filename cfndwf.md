代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jyoumei.cn/Article/details/gtgrvbemwv.html

Ruby: def self.f; end
来源：http://dali.9152youxi.cn/Article/details/gtozdatexh.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtcmiulval.html

[G09] 接口 / 抽象类
来源：http://dali.xinyue.icu/Article/details/gteglcpqzl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gtlnexnrfn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aizwys.cn/Article/details/gtxgwsupsj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gtrfylqdsk.html

TS:   interface Shape { area(): number; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuythqvck.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gtsoryjpqz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gtcgsahtkw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigufen.top/Article/details/gtrjnrqayr.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtzdhmrupa.html

[G10] 访问控制
来源：http://dali.yongpay.top/Article/details/gtmngdbkfx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gtqxbnvvlx.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtyvjdcjqt.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gtxsoqydtp.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtxnykfzgu.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gtqncdxguq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nwbrower.top/Article/details/gtbpjotfrz.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gtgviywjyb.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gthipvaxbc.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdiyqeuii.html

Py:   @property 与 @x.setter
来源：http://dali.tian-w.cn/Article/details/gtvbdoroyk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtpekislzd.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtmpczzzlj.html

TS:   get name(): string { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtdxzyixju.html

Java: public String getName() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtcmoitdgl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtlvyuotfp.html

Ruby: attr_accessor :name
来源：http://dali.sysykeji.top/Article/details/gtrmeqckxy.html

C#:   public string Name { get; set; }
来源：http://dali.nwbrower.top/Article/details/gtjrdvapgx.html

[G12] 对象转字符串
来源：http://dali.sufxvd.cn/Article/details/gtpjdourmi.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtmyxixkli.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwmjdemn.html

JS:   toString() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtxuntncfj.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtbzbvhfsu.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtwnlwpqjd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtbrrkcrsb.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtovjzaofb.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtswidcfbb.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gttjmsxusq.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gtjlxwkncq.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtzkpofzqm.html

JS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtoixjjlnb.html

TS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtmyzxrcuj.html

Java: u instanceof User
来源：http://dali.hammf.cn/Article/details/gtioqjhnsj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daxiang520.top/Article/details/gtplkrczpz.html

Ruby: u.is_a?(User)
来源：http://dali.hnxiangtu.top/Article/details/gtexmnmfma.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gtwvzyvjqr.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gttoozsudw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangdashe.top/Article/details/gtsqlriapv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gtozoihnjq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gtwjiknyik.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuetiantiany.cn/Article/details/gtovhzctrz.html

Java: record User(String name, int age) {}
来源：http://dali.chenzaomai.com/Article/details/gtwrqdzvcr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gtweimmzcb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gtketvsccu.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gttmjsiuct.html

[G15] 枚举
来源：http://dali.aibaodan.cn/Article/details/gtbumqvxct.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gtufeqpekb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkojznrty.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gtjtlimhbw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtbobiqtvm.html

Java: enum Color { RED, GREEN }
来源：http://dali.yangfankeji.com/Article/details/gtrfzztsfi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gtfseyhdrk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gtvflenhjp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtwbvbzaci.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtsxxawgji.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dashuyun.cn/Article/details/gtiicvmmra.html

PHP:  get_object_vars($obj);
来源：http://dali.nwbrower.top/Article/details/gtnulntzxs.html

JS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtwiiojybn.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtzhahshmg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gtvfxkrthw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gtylsmufox.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gtkwlrasoi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gtirmgimgr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtiemughej.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gttiewputz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtjyyjbvjv.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gtoeavptaa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sysykeji.top/Article/details/gtqcvbftyv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gtdfttdgly.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtfqipvvsg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtbumwbutv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gtbizlqncf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.mhx1999.top/Article/details/gtsdpnntoe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gtcqftggxi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gtxmlfhjim.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gtrhrekoav.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenzaomai.com/Article/details/gtvqouloot.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtredghpyw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtkljdrowt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtwcaxgwug.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtirsatxyw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkogutfy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hfpthk.cn/Article/details/gtsvjswpls.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtulzuxqti.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gtkigefrgm.html

Py:   raise ValueError("错误信息")
来源：http://dali.jianghu66.top/Article/details/gtqifvfgnd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtejzpajfd.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkznmytm.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtwjntqgze.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtkjbrqrpu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gtzizerilv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gtpjafbxal.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtuyhpkzon.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gtmvwrytzh.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gtaseaqaym.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gtbotidhjx.html

JS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtgfzimcvw.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtlvudmtkj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtfxnqkajk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gtntedahml.html

Ruby: class MyError < StandardError; end
来源：http://dali.kuanghao11.cn/Article/details/gtngvsproi.html

C#:   class MyException : Exception {}
来源：http://dali.sysykeji.top/Article/details/gtzxhyuwzy.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gtwuhbziro.html

Py:   except ValueError as e:
来源：http://dali.yj20258888.top/Article/details/gtogjyutlp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cucudq.cn/Article/details/gtgznoqwpy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gtoicmojhy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gtcasbvehd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfaaakatu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhengqikj.top/Article/details/gtpkvfoayt.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtejbypdui.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwoofwxgr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gtlsxzqnbm.html

Py:   value = d.get("k") or default
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsihlbeo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtfjwnkoso.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gtuxnzhewm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtmhdgoztq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gtsmhidzyf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gtiphkslop.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sxryk.cn/Article/details/gtniwxjpqo.html

C#:   obj?.A?.B ?? default
来源：http://dali.aizwys.cn/Article/details/gtiqzoyusb.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gttwbmbntx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gttyssaogi.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtfpadupsq.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtvyxynhaz.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtzjyxwdte.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gtqozfhtio.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gtuxqygxae.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gtiflgokoq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtfkuzmuia.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gtgrmashxd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtrrbiyxgl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gtbdgnxtuy.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gtwaxkzddr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daria6918.cn/Article/details/gtawodfvrd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gtszluzlah.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gtajxzipzo.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gtknvltmxe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gtcjewivah.html

[H09] 带错误码的异常
来源：http://dali.quarkkingdee.top/Article/details/gtizcnhzpp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gtdpzfgiac.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gtjoukfwbj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hammf.cn/Article/details/gthlhoykae.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gtcorumqip.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.0kj1m.cn/Article/details/gtyjzgbwfb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gtohrkddhc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jyoumei.cn/Article/details/gtseknwrsw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gtclcnixok.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gtwnmefdll.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtynoislgd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jyoumei.cn/Article/details/gtnrpyinyw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gtxdzglvqz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtpgpvkwik.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuanzx.com/Article/details/gthisdprht.html

Go:   defer f.Close()
来源：http://dali.yangfankeji.com/Article/details/gtwaqxhsua.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gtvgicyhus.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtxjpnjkdr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtwiaoomcc.html

I. 正则表达式
来源：http://dali.xziqi.cn/Article/details/gtiplrhefk.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtuftspnwh.html

[I01] 判断是否匹配
来源：http://dali.0kj1m.cn/Article/details/gtfiagxdkr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtqeighttf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.havefunace.top/Article/details/gtndjgqgod.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtgakdqbfg.html

TS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gtvxgzfqrt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxuanxn.top/Article/details/gtcmghptkc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.svipenyu.cn/Article/details/gtqudibeyc.html

Ruby: s.match?(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtexlcgvbq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxinkj.top/Article/details/gtrzjhgeqr.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gtyfuoglud.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpwqsjfm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtwvyqeuhy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sxryk.cn/Article/details/gtbsgggavl.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gtglvkcuzx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gtyxsoliaw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtyzreawct.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtwiiijcdx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtpzvkwtqe.html

[I03] 提取捕获分组
来源：http://dali.jiagoushi.top/Article/details/gtxhcxnbfr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gotoacloud.top/Article/details/gtfqmmpxir.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgufenzy.top/Article/details/gtyjutrsep.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.mhx1999.top/Article/details/gtfgohnyuw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jiagoushi.top/Article/details/gtfzzznkox.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gtrakdevvc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gtiaaimjod.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gtwbdgawua.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gthxsrluhz.html

[I04] 正则替换
来源：http://dali.nanxinkj.top/Article/details/gtivbdhjcn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gtkcsdyyno.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdltssunv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtuyfvxeyn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gtawtewjjz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtiafdexae.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenzaomai.com/Article/details/gtofcfrbvb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gtyhcnxcbs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtmvmpfzpo.html

[I05] 按正则拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtiskagmpe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gtmzwlryxa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtskdadtad.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtxbdryzgb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtwscasafg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hammf.cn/Article/details/gtkryiqrws.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cashguo.top/Article/details/gtxaudtqou.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqkmwryt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gtmllcpwba.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gtcsvrxcyr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtzmqzetuz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangshuangyany.cn/Article/details/gtjwgmfvyv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtklohcehb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtfvidvjdy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtinljjmhi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258.top/Article/details/gtqzuxqoot.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenjidiqi.icu/Article/details/gtbervtrqu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtrtckrcgi.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gtfvxmajss.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gtourbmpdc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gtcwtuameq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cucudq.cn/Article/details/gtrdkufwps.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gtwnpptjbv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.9152youxi.cn/Article/details/gtbvljckvz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fzhhl.top/Article/details/gtbtnlctfs.html

Ruby: s.scan(/error/i)
来源：http://dali.vqdsnc.cn/Article/details/gtasmvqzxp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgfzy.top/Article/details/gtxenlteoy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.andypj.xyz/Article/details/gtmcldxqwp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigfzy.top/Article/details/gtnplqndih.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtgbumgdga.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtuzosiyqv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gtjbsdymtv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtzzpyayzt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gaohongyu789.top/Article/details/gtyuwzczej.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.birdmap.top/Article/details/gtmldwbtiz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gtwdkdagnn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtdnqojbfu.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gtlonwdsux.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtjlkvsymc.html

[J01] 获取当前时间
来源：http://dali.yj20258888.top/Article/details/gtehbhlowx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangshuangyany.cn/Article/details/gtvpreqowv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gthdxyuwwc.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtbijeatmq.html

TS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtydqnpcqx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.mhx1999.top/Article/details/gtlgzogyvd.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gtxduwuzet.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gtmtzmsjaz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfvodpmx.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gtlrvkhxcn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gtvrnmtlza.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtritpni.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.iojbl.cn/Article/details/gtajoqrxvy.html

TS:   d.toISOString()
来源：http://dali.vqdsnc.cn/Article/details/gtbyijazxs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gtqkpcyucj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yonumen.top/Article/details/gtzdcmiply.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtjiskuuek.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gtcccgwhvm.html

[J03] 字符串解析为日期
来源：http://dali.jiagoushi.top/Article/details/gtnlfflyix.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gtdyteebvw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenzaomai.com/Article/details/gtxuneshdp.html

JS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtbiqxikxh.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtfnkwfxjo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtphjlrrxw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtlloxfimm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtvajkrrbs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gaohongyu789.top/Article/details/gtfhwmzbsy.html

[J04] 时间戳与日期互转
来源：http://dali.zycfv.cn/Article/details/gttbjkicqk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yangfankeji.com/Article/details/gtmdpcqlva.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gthtpcidum.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aizwys.cn/Article/details/gtreiulwgx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gtftdnigie.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aizwys.cn/Article/details/gtxovtnkcj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtteiaillm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gtxkkcdqhy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.0kj1m.cn/Article/details/gtqhievyro.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gtgtrefetu.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigufen.top/Article/details/gttjrvdpsy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuxming.cn/Article/details/gtwxffmihd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gttwtozbjs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gthmuwmxux.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtopldmkbt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gtwlimxcjg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cashguo.top/Article/details/gtkdfogcte.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtyywucehc.html

[J06] 计算两时间之差
来源：http://dali.gaohongyu789.top/Article/details/gtgxpxmwnf.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gtmkfozlxh.html

PHP:  $end->diff($start)->days;
来源：http://dali.dashuyun.cn/Article/details/gtscpyxtor.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gtgcpvjipc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gtewvjonob.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.iojbl.cn/Article/details/gtoxscfnmd.html

Go:   end.Sub(start).Hours()
来源：http://dali.aibaodan.cn/Article/details/gtrklaexcm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gtqwsboubz.html

C#:   (end - start).TotalSeconds
来源：http://dali.hammf.cn/Article/details/gtdjrukppk.html


<!-- 参考信息 -->