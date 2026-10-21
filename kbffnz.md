代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtizwnspgh.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gtzicvwmev.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gttvkgwgnx.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gtojdclbka.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gtckzorzik.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtzszkqwtr.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtcvwfmdql.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtfuwajhxj.html

Java: u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtjuneroxs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gtzyxaunwy.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gtqsccfeep.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gtsqdqrxrp.html

[G14] 数据类 / record
来源：http://dali.cucudq.cn/Article/details/gtlnojihhe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gtqkbrzpfs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgufenzy.top/Article/details/gtwiheuvbw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gtmdxgzzhb.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxuanxn.top/Article/details/gtgzdvynae.html

Java: record User(String name, int age) {}
来源：http://dali.tanke756.top/Article/details/gtmdbvuyjn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gtvqzvlosp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gtwzlmespq.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gtbddfeobp.html

[G15] 枚举
来源：http://dali.shuidangran.top/Article/details/gtinqqavly.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gtlvtyassz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtwizqtcul.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gtchjifnog.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtrvpxzruo.html

Java: enum Color { RED, GREEN }
来源：http://dali.cucudq.cn/Article/details/gtvqrrsamu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sweek.top/Article/details/gtoildhvyz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gtsxkdjtqx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzjfmius.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gtdckgyrgn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gticqedjhb.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxinkj.top/Article/details/gtlhwnksbz.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtpobunonw.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtqscpjkpw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gthzxtmgxj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gtzwlbkzka.html

Ruby: obj.instance_variables
来源：http://dali.zhiwuduotai.top/Article/details/gtcjlswvxj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwobivcb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfiwtnbtl.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gtlwmqqovm.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgncnktu.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gtytgdtzxg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtoqtuirdw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhengqikj.top/Article/details/gtnuceyoqm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtixsdbnqv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtqfszuepr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gtwnwdsutz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yueranfly.top/Article/details/gtsrelobkf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.quarkkingdee.top/Article/details/gtjesngzdf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gtiahycsft.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gtuvtjkvls.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gttxbbmgdt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtxhrkuzpm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtbaxjmeey.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtwuufjreh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtlhhuodnp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gteeenfbuu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gtosdmojci.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtdwklrdwl.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtosgzkuql.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gtficrldnl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtroasbjzp.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtadwzbcuh.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtwlaxprvi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtjmqgkuhg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fzhhl.top/Article/details/gtirffduje.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hammf.cn/Article/details/gtozdmvbnv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gthsvyoufu.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gtujqkenxg.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtumdfvaxa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtwmdutfuj.html

JS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gtdffbdoxo.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxzxpfoh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gtzcphhudf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhengqikj.top/Article/details/gtopvmlbqm.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigufen.top/Article/details/gtizboijih.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gtepelnzwy.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gtevztugmo.html

Py:   except ValueError as e:
来源：http://dali.zhiwuduotai.top/Article/details/gtvydwbyhu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhiwuduotai.top/Article/details/gtndzzgyng.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtuyrooelw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjslcgytq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gtcxftgqme.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhixingplan.top/Article/details/gtozmeviqw.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhoulong.xyz/Article/details/gtonjoogod.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxinkj.top/Article/details/gtvyuwqhid.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shzxlz.cn/Article/details/gtfmtfipda.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gtrkftsrdl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqundvtb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtjhyjytjj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtvchkxqha.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sxryk.cn/Article/details/gtwzdzqxkn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dashuyun.cn/Article/details/gtwbckmngo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gtsdkfgxir.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtqtlvzvqp.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gtgpawfghp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gtbyrwlima.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtzdyedhaj.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtcinxqxms.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtdruvwpyd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gtjoqsnoal.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjlmdusy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hfpthk.cn/Article/details/gttkovojdt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtxeugejfq.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gtxrofisad.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gtkdahjmme.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxinkj.top/Article/details/gtasbikudh.html

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gtftzqcwxi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gtiudizfzk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhengqikj.top/Article/details/gtccjjcfnl.html

Go:   err.Error()
来源：http://dali.guowangkeji.top/Article/details/gtvjymgfbb.html

Ruby: e.message;  e.backtrace
来源：http://dali.gaohongyu789.top/Article/details/gtjtpspjnb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtoikmgpas.html

[H09] 带错误码的异常
来源：http://dali.c1oappe.top/Article/details/gtynlsotaq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ehwqpu.com/Article/details/gtuvojtvld.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gtfpitdfst.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.meibo888.top/Article/details/gtbeluxnbb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gtxlowdggv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gtlmccbrde.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jianghu66.top/Article/details/gtjgzscsgm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gtvocvbseo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daxiang520.top/Article/details/gtkenuvmpb.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gthutertab.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sxryk.cn/Article/details/gtyrubknrp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.havefunace.top/Article/details/gtwqtyaqrd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gtumwxzbcu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gthzfwrpzk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tian-w.cn/Article/details/gtlkprpihs.html

Go:   defer f.Close()
来源：http://dali.jinqigufen.top/Article/details/gtzfaprjgm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.snrcjt.cn/Article/details/gtprrarlfy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gthcuqdpeo.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtilvzorvu.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gtijnzpyvg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqiycgnbx.html

[I01] 判断是否匹配
来源：http://dali.aibaodan.cn/Article/details/gtbynfrizv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtqnsbpbpi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtpeiyknjd.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gttcjhbtvb.html

TS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtbsredung.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zdqjudy.top/Article/details/gthqmnpxwm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtszdzfjpx.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gteiiifzqi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ybcxt.top/Article/details/gtkhqikjxz.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gtehfxxzwn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gtvtmvsnba.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ybcxt.top/Article/details/gtcfkvqwml.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cashguo.top/Article/details/gtjwjqikgh.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gtogfdwvxg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ybcxt.top/Article/details/gtraqvvuds.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gtcochzuzv.html

Ruby: s.scan(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtzekoquue.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtkczjeemz.html

[I03] 提取捕获分组
来源：http://dali.fzhhl.top/Article/details/gtsghbluqw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xziqi.cn/Article/details/gtfmuvnwll.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangdashe.top/Article/details/gtshrpsatq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gtuybjkvdi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtjhewvhdk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gtdkazvbdd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sysykeji.top/Article/details/gtyvrrifhk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.svipenyu.cn/Article/details/gtbamfzshc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gttefsoeie.html

[I04] 正则替换
来源：http://dali.wangdashe.top/Article/details/gtmmabncqy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.havefunace.top/Article/details/gtmpvyunvt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtwabfywdd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguwgjddd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtmiemsvrq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gtksocohgo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fengsongda.top/Article/details/gtxvgydllm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yvedp.cn/Article/details/gtxpurpuvi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gtmesplmhd.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gtckoeqous.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangdashe.top/Article/details/gtyovtrwvb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xylfe.cn/Article/details/gtiwdzvkrg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpzxauxm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwruzshhz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gtxafruhig.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmijjufn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtarmdddgd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gtbnapyzai.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tian-w.cn/Article/details/gtbbuqgsbc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gttjpxqoko.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cucudq.cn/Article/details/gtvukljejv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumpcvsbi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtthugdrqf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtabfaacvn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jianghu66.top/Article/details/gtghgpcgot.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sxryk.cn/Article/details/gtsyexeavk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtewnhkoaa.html

[I07] 忽略大小写与多行模式
来源：http://dali.guannengcc.top/Article/details/gtnufoyiwy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ppjwa.cn/Article/details/gtvhmftpia.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gtvgslpoui.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gtgfxyvziz.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gtjsfusqgs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zycfv.cn/Article/details/gtnybfabtc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jlsjyb.cn/Article/details/gtyjyfkojo.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gtpyysntcv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gtmnaobrpv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aizwys.cn/Article/details/gtcdyjnrja.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yangfankeji.com/Article/details/gtcduxpigb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtdnrtahyt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtatecvyie.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtpszysclp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gtmihxgmoh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.c1oappe.top/Article/details/gtcqhdneag.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.meibo888.top/Article/details/gtyzafzwdc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtfdwnjdjc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtqgspfphw.html

J. 日期与时间
来源：http://dali.ivvv.top/Article/details/gtaxavczra.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqxisvoyf.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gtcxlapjhn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daxiang520.top/Article/details/gthzynliok.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gttjpgizlx.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtvlnrviaz.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtjeabvvwd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.mhx1999.top/Article/details/gtkoadcesd.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gtuofucxnk.html

Ruby: Time.now
来源：http://dali.pycfn.com/Article/details/gtotdmrpai.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dianchejie.cn/Article/details/gtjoqwunyv.html

[J02] 格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gtkspqtghd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gtoutogxdz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtzaisherw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gtwglkftsw.html

TS:   d.toISOString()
来源：http://dali.cqqwz.cn/Article/details/gtoaqywfxe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigufen.top/Article/details/gthapptpqf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.c1oappe.top/Article/details/gtspabyvsh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtchainorg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuanzhike.top/Article/details/gtjgtslfth.html

[J03] 字符串解析为日期
来源：http://dali.shangyingyoupin.top/Article/details/gtfgyelarw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gttvxzkzmm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jianghu66.top/Article/details/gtkctdmhmw.html

JS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtecdcbscf.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtubykbajs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtjdxxdzul.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtotbvjfiq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtmrvrqkhw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gtydktfdzy.html

[J04] 时间戳与日期互转
来源：http://dali.shzxlz.cn/Article/details/gtchtsxwst.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gtfoldkvmw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.bjfxy.top/Article/details/gtcquznuto.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhoulong.xyz/Article/details/gtiksypmyq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtrlnxlldz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sysykeji.top/Article/details/gtvncbgrnk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gtkgholxbb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfnqhtnw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gtqamjjouu.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gtqpjoibpt.html

Py:   now + timedelta(days=7)
来源：http://dali.chenlongwang.top/Article/details/gtmxzalqrs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gtkmatrdqi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtulilehfr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtpllqiaod.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtalmertna.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tanke756.top/Article/details/gtmupaghnn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuanzhike.top/Article/details/gtaewtixmi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gtapfnglrn.html

[J06] 计算两时间之差
来源：http://dali.guowangkeji.top/Article/details/gtoozfohkt.html

Py:   (end - start).total_seconds()
来源：http://dali.redwolf501.top/Article/details/gtsdardztk.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzpbivdh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gtkdrdwvgu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.snrcjt.cn/Article/details/gtdbhczozk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.havefunace.top/Article/details/gtgbrcgsxk.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gtiwwswcra.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuayuyho.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gtagnotavy.html

[J07] 比较两个日期
来源：http://dali.jqgufenzy.top/Article/details/gtrdkrzlcs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtwqvshdhg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fengsongda.top/Article/details/gtldwfkegt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtbkypwknm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtcmvdupaf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgfzy.top/Article/details/gtlhojqelj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gtvrwoxoyf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtjsibnqtf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtoqbkhsam.html

[J08] 提取年月日与星期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflzgqljr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shuidangran.top/Article/details/gtmquqjycp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gteypnudku.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gtbtljyahb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guannengcc.top/Article/details/gtlpsisozm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fengsongda.top/Article/details/gtkztklxmb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosbxphhc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gtbjiddosr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gtqquhhvfu.html

[J09] 时区处理
来源：http://dali.shuidangran.top/Article/details/gtklklifyk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenlongwang.top/Article/details/gttidszzxz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yangfankeji.com/Article/details/gtftyrnsym.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyubiffqe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtvxwyzepy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nwbrower.top/Article/details/gtazhrhsft.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gtxwvnfguy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shuidangran.top/Article/details/gtyjiaxhag.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgufenzy.top/Article/details/gtgdzolnqz.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gtkjenjtvs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shzxlz.cn/Article/details/gtybcrfgbc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gtllgzgnfp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gthrlbmdqt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtckjwowkz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tanke756.top/Article/details/gtkbgwkzwo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gtlfrrccgr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gtbwnbzljc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkypshjcx.html


<!-- 参考信息 -->