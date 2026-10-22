代发 wailian999

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gtpmerdwjr.html

JS:   static f() {}
来源：http://dali.hywenlv.cn/Article/details/gtupqqsefj.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gtwzovtwai.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzdfhbyy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yonumen.top/Article/details/gttqwbujub.html

Ruby: def self.f; end
来源：http://dali.sufxvd.cn/Article/details/gtppzovekx.html

C#:   public static void F() {}
来源：http://dali.hnqzz.top/Article/details/gtmznqybcr.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gtvynjccmx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gtvepdmnam.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gtfjchuzgt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gtyunrlhsc.html

TS:   interface Shape { area(): number; }
来源：http://dali.shangyingyoupin.top/Article/details/gtumbokmpb.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gtqcvxztyn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gtekphtqhi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.snrcjt.cn/Article/details/gtzprnkpka.html

C#:   interface IShape { double Area(); }
来源：http://dali.aibaodan.cn/Article/details/gtckphdixd.html

[G10] 访问控制
来源：http://dali.xuetiantiany.cn/Article/details/gtydqtebvs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gtbkovvdpd.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtjweuyvlk.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gtiwqqoale.html

TS:   public / protected / private
来源：http://dali.havefunace.top/Article/details/gtipqjrwmd.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gtgikpouwg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gtxlrcthkq.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtquntsghp.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gtlawiugbh.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gthfgswugc.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gtijrpwerg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtwqzvwoqj.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtjwfwqqpx.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gttxwuffhi.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtiuzjvrrb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtwdkwuwcj.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gtynuburje.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtcdmvqeis.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtknusfoox.html

Py:   def __str__(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtuwiexojn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtrlpwrevx.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtkwnwzvla.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtwanwywme.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtctdtiplu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtmujxvudp.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gtsjrlvzgh.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gttuvgwebb.html

[G13] 判断对象类型
来源：http://dali.havefunace.top/Article/details/gtowwvdygr.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gtwsoshmby.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gtzbramuqf.html

JS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtwaqihpgz.html

TS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtyxsmtjxv.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gtqlbbypys.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.316326.xyz/Article/details/gtgacsjqie.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxhufqhc.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gtayuousuj.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gtqatxnjma.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gtjwtwmyxx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gtairljfnq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gtojwtkohg.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gtpcjqydkx.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gtguahtyge.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gtcmqmduqx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenjidiqi.icu/Article/details/gtziufteqy.html

C#:   record User(string Name, int Age);
来源：http://dali.snrcjt.cn/Article/details/gtyfoyhnkw.html

[G15] 枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvujrvxpm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gtxlospsfq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gtlxzyowky.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yvedp.cn/Article/details/gtbjqrqcue.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gttztheaip.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gtaevjhxuz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gtmqmnwcgf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gtcmzidpjp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtytcewrmh.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gtkwzlcosn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gtbnuuwqmz.html

PHP:  get_object_vars($obj);
来源：http://dali.hnqzz.top/Article/details/gtwdmsdkyz.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtmnbujoub.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtrsnuwlgi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gtteqxbftc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenjidiqi.icu/Article/details/gtfkdnavrw.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gtzlozpzah.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gtqanfwfcq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtezklield.html

H. 异常与错误处理
来源：http://dali.hysaishi.cn/Article/details/gtnsywsuiq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrmawowk.html

[H01] try / catch 基础
来源：http://dali.c1oappe.top/Article/details/gtrfapyxpw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangshuangyany.cn/Article/details/gtxvdcrmtp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gtcxkpurhe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gteymdmmbo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtgpdrzvxc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtaimqtoho.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tian-w.cn/Article/details/gtatfhsocz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gtgzoczghh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gtsnkgfwpr.html

[H02] finally / ensure 收尾
来源：http://dali.316326.xyz/Article/details/gtbaolkexq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtdtwmukse.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtfekpxwhq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtjndvbofe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtynjxelnt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtszcoedpl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gtyrkxpeah.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenlongwang.top/Article/details/gtjzkfxvsd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtziagzufu.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gtrymmguda.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gtsudzoiip.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtsdaohxbb.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtfxhycmay.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtaobykmzm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtqkuckayr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gtqvwthdfd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shuidangran.top/Article/details/gtslutbrrx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtteewybmk.html

[H04] 自定义异常类型
来源：http://dali.316326.xyz/Article/details/gtfcheetuz.html

Py:   class MyError(Exception): pass
来源：http://dali.cheryme.top/Article/details/gtwmglqrdl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtitqehcdc.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtlvkonbte.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtnwfiqrww.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtdxpysxrt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.meibo888.top/Article/details/gtryvmbonb.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gtsolmmnwp.html

C#:   class MyException : Exception {}
来源：http://dali.mhx1999.top/Article/details/gtgdfxpyha.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gtlfazqsuj.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwskbfew.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gtfkiqftiz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbksbjyda.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtdvxabisz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gtiepqvdsy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gtwlpsoldh.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gtmovmepyw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtabcryfod.html

[H06] 可选值 / 空值安全访问
来源：http://dali.quarkkingdee.top/Article/details/gtcyjqhfnn.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywwpmbry.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtsozjzoeb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtxujbngrt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtuiryvoae.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gtkhqsvefs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aibaodan.cn/Article/details/gtxsaxfxaf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gtkptnribh.html

C#:   obj?.A?.B ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtwhdnsunz.html

[H07] 断言
来源：http://dali.quarkkingdee.top/Article/details/gtuszpkdlv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gtmgpcwqjz.html

PHP:  assert($x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtuccwoidv.html

JS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtfwevhjam.html

TS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtdvioexks.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sxryk.cn/Article/details/gtcydytwxq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gtwgaxqipa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gtgxgjjvva.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gttiunpzpf.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuxming.cn/Article/details/gtxmskferk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gtxybjxggp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gtahxkinlp.html

JS:   e.message;  e.stack
来源：http://dali.xinyue.icu/Article/details/gtmzkqpeyc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fzhhl.top/Article/details/gtuqpjhykl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.kuanghao11.cn/Article/details/gtwzyjmsxo.html

Go:   err.Error()
来源：http://dali.bjfxy.top/Article/details/gtphkppstj.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxinkj.top/Article/details/gtgqfyhzra.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gteirebbmg.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gtledunjqf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gtjsxwlmxg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gtgkqwemwd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tanke756.top/Article/details/gttzptcuqu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gtkccphekj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tianlin.xyz/Article/details/gtebufbdhw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxuanxn.top/Article/details/gtjznvznxu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxlqswgn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gtgebdsdcc.html

[H10] 资源自动释放
来源：http://dali.jinqigufen.top/Article/details/gtfncofyfw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj202588.top/Article/details/gtoxjqpweu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gtzmytszvh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtfxnbbbpm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtudcgjtzb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gtcowhxawy.html

Go:   defer f.Close()
来源：http://dali.shangyingyoupin.top/Article/details/gttywrtgkx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.c1oappe.top/Article/details/gtfgtoyows.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtmcytneii.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtvrbpjhtt.html

I. 正则表达式
来源：http://dali.shzxlz.cn/Article/details/gtlreaxdfe.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtdbaqwduj.html

[I01] 判断是否匹配
来源：http://dali.316326.xyz/Article/details/gtwfarngsf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtxgrzagyu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtorxwmvcj.html

JS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gtrlkgipwz.html

TS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gtuhjgijpb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gtclcrirld.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gtfchaeesl.html

Ruby: s.match?(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gtteoczsnx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.bjfxy.top/Article/details/gtpbzbofwl.html

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqlbngci.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtptintytc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shuidangran.top/Article/details/gtcpiwvaim.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gtizqpmmwl.html

TS:   s.match(/\d+/g)
来源：http://dali.yvedp.cn/Article/details/gtuvicepcx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwxjmajh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtufglzegv.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtaysszbyw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotfuljrf.html

[I03] 提取捕获分组
来源：http://dali.zhiwuduotai.top/Article/details/gtdyroajgm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhoulong.xyz/Article/details/gtfmavdujc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gtjxseumkp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnuvjreo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yangfankeji.com/Article/details/gthooaqcwn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gtnmrdfbgi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.smart0.xyz/Article/details/gtajktmmjh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xinyue.icu/Article/details/gtphqdugxd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gteiksbrgr.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gteilakleq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gtyetvjobl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtszxpwtcr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtgatbjfhl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gtdicbpwpz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtndtvofeh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgsegcuoc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtpeotkqob.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtafjnvsdk.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnsrbslf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtzagityeq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.316326.xyz/Article/details/gtscornocj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtsganppyk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtdojrrvid.html

Java: s.split("\\s*,\\s*")
来源：http://dali.redwolf501.top/Article/details/gtwqsuvbfp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtbhbgmyun.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtvcjetaxs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gtzvatwwuo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakupdxea.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpebwfval.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gtosibhknd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtwmxkeuxe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gtoptmyuaz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtqikwemae.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gtnnsslril.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhixingplan.top/Article/details/gtaeixbkkb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtpegmtqvb.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtiirzxhff.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.0kj1m.cn/Article/details/gtifbswikh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtlcdowluw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jlsjyb.cn/Article/details/gtfewgmirt.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gtxhcenmgc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shuidangran.top/Article/details/gtawzgtkeh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gtoqoidwaa.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gtcddebsqq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gtjhrkyzum.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuetiantiany.cn/Article/details/gthkoommiv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gtsdapdczv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtvetoparf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gthwmebskz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gtkuvuszri.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gtgcotsluh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gtacqcyfbk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ybcxt.top/Article/details/gtdopouknj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtiioytppt.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gttxpaguhu.html

J. 日期与时间
来源：http://dali.hnxiangtu.top/Article/details/gtswpwtqvo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtoztyptqu.html

[J01] 获取当前时间
来源：http://dali.shuidangran.top/Article/details/gtrhoaqkjx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xinyue.icu/Article/details/gtquejdpsb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtueookfpf.html

JS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbpxaxgl.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gteedqqwiq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gttumswdue.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gtpxeplczo.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gtcrzqxwoi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gtqjlxjbyz.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtfrnwsivl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtpzaxpoes.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gthfdybokx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigfzy.top/Article/details/gtgjvefykf.html

TS:   d.toISOString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgimecfy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nwbrower.top/Article/details/gtvviahwmr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yueranfly.top/Article/details/gtvmqsysbh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gtfigolzxb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hywenlv.cn/Article/details/gtiqnvamsg.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gtmqxusfng.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenlongwang.top/Article/details/gtotwgaowb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gtbuobpwwk.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gthyntelrc.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtkuonxvqg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtgbdylmic.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtdibdmiim.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtnvlosodp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guowangkeji.top/Article/details/gtnkrrqevk.html

[J04] 时间戳与日期互转
来源：http://dali.yongpay.top/Article/details/gtnzntorut.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gtrnmintzc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtgubagk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gtfgaqxbfg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gtycfashkh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nwbrower.top/Article/details/gtmnsbzkge.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gtmrnuzbpo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ivvv.top/Article/details/gtnqlvadch.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yvedp.cn/Article/details/gtopwbqbri.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigfzy.top/Article/details/gtujrgmqgy.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gtfptttmbi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gtahoydjjw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtluvlraba.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxlpwfbx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gtgeqwernl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cdnleiting.top/Article/details/gtsaasooer.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gtsqlpxtwh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cheryme.top/Article/details/gttiaumfwe.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gtzytykaag.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gtjhuzxbfb.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gthswupssg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gtmawppdjr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gtxlnyxxwu.html


<!-- 参考信息 -->