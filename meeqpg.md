代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gtpgidvcvx.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gtddqbqiht.html

JS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtrtrsqstk.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtqyvvmkkt.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtfzprqhaa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.iojbl.cn/Article/details/gtejixbcmo.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gtkzaeqhlg.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqvnqlzh.html

[G14] 数据类 / record
来源：http://dali.yanxiufei.cn/Article/details/gtkbgiuwqf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gtaubshpzw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gtlopgmehi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yueranfly.top/Article/details/gtmcflsmgf.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gtfqjkrkej.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gteoyndukc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuxming.cn/Article/details/gtnpfgwzjy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gtsahtkdle.html

C#:   record User(string Name, int Age);
来源：http://dali.0kj1m.cn/Article/details/gtujtmtbfy.html

[G15] 枚举
来源：http://dali.xinyue.icu/Article/details/gtfxafhbgr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gtymcuzxof.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.mhx1999.top/Article/details/gtqgqgzgof.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gttefepamv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtacsadvpg.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258888.top/Article/details/gtipxtkajb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gtvtcgrmfl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gthcaggczf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtixgktunm.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtzhaiheav.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gtrsnziyax.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gtbnfpzlcq.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtghuawujk.html

TS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtpnojddhm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gtmqutqhcq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gtfvrateqg.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gtyaetyvfz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtpefrujxa.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtyjqoxpfe.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gtkoxvcmsk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gteywkrved.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gtsjksemxg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqzdnffv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.bjfxy.top/Article/details/gtgxyflkbc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtwrgdjlxf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtxhrarmmu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pycfn.com/Article/details/gtispewyht.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gtqtkrxzgy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xinyue.icu/Article/details/gtokfudrxj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gtkbenyrlz.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gtldfhodyx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.bjfxy.top/Article/details/gtwumgitxx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtfadhwyha.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtwukhfxuo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtfyuyzzte.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtfachspto.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gtjxmdckga.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenlongwang.top/Article/details/gtqweoiovo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtnjrcosdt.html

[H03] 主动抛出异常
来源：http://dali.zycfv.cn/Article/details/gtpktmehns.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gtkcqutnbb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtryevaszv.html

JS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtjlywndhx.html

TS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtererfcaq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtcakcvgwk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gtiguypshd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrxwuoxw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtgoumikyw.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gtthdcrmyk.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdeovlich.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gthixgeron.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtdnkskyuh.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtmihspory.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtfzyxonkk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.meibo888.top/Article/details/gtgmircaez.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gtsflbcyta.html

C#:   class MyException : Exception {}
来源：http://dali.ivvv.top/Article/details/gtgmimrbki.html

[H05] 捕获特定类型
来源：http://dali.mhx1999.top/Article/details/gtygqrfnbi.html

Py:   except ValueError as e:
来源：http://dali.zhongyouzk.top/Article/details/gtxriykwcf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gttgwjilfc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtfeouhttw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtfxcpqmjc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gtsscekfpa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jlsjyb.cn/Article/details/gttzcdjgen.html

Ruby: rescue ArgumentError => e
来源：http://dali.yonumen.top/Article/details/gtdjschgqv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gtrobhgfwi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gtysjrgvng.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gtejwnbiak.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtmggqtznr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtputwkbga.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gthzuuxjpv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gthsoiunsf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ivvv.top/Article/details/gtwvajceqm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gtnzvobwyw.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gtoqnjeono.html

[H07] 断言
来源：http://dali.cucudq.cn/Article/details/gtbtfcwavv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gthcdkusln.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtgwlcyulz.html

JS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gthosapxam.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtharqzzzi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gtvfcfizhu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fengsongda.top/Article/details/gtpnxybxbk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gaohongyu789.top/Article/details/gtgjkkbpid.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtgkvrmwcl.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtkwiutphs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gtmfbfmxbf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gtckkqijuu.html

JS:   e.message;  e.stack
来源：http://dali.hysaishi.cn/Article/details/gtzmvqyeha.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.0kj1m.cn/Article/details/gtwybbwdez.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenlongwang.top/Article/details/gtioxzmgvp.html

Go:   err.Error()
来源：http://dali.tanke756.top/Article/details/gtevfyefwm.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gtlrereysj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fzhhl.top/Article/details/gtdlkklcwb.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gtyecpdwlg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gtaifqtkjw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gtsjyxeplp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxuanxn.top/Article/details/gtxgbuthvz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gttwvghgpi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsvrmptn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tanke756.top/Article/details/gtdysfsbco.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gtbymgwsfm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gtopvnubhs.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gtaqojsogn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtlddometz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ydzc1.top/Article/details/gtkidoxpnn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtqnskmypd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gtcqkpbyyo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jlsjyb.cn/Article/details/gtbgglavys.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gtecddflvk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gtyxuiujvt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gttllmljzt.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtureijhrg.html

I. 正则表达式
来源：http://dali.shzxlz.cn/Article/details/gtybyeakaj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtvhsbdjpd.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahcwuosd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtnizceceo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtmrktubgn.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtgzrxzgll.html

TS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtlrhldmxg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.smart0.xyz/Article/details/gthqspikyi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtcoyamnlm.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtwwcnwufm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fengsongda.top/Article/details/gtammncubl.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gtaribeqze.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtgqpzbqvp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gtnutbvquk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidykyvwz.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gtqtibfces.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gtyvtsocoo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtuiutdxmx.html

Ruby: s.scan(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gtgbjmvdha.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtyxlabsvo.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gtzjxoiumf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuanzhike.top/Article/details/gtlhyjeqbu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gtnzgywqox.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigufen.top/Article/details/gthncdyuoc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gtwtblzyoi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gotoacloud.top/Article/details/gtnoysvnvu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.meibo888.top/Article/details/gtzmzrhtgu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgufenzy.top/Article/details/gtqycagpws.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gtvukqhfzn.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gtnrltkxit.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gotoacloud.top/Article/details/gttnqbvuxn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sxryk.cn/Article/details/gtkhfhgcen.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtgrgykolr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gternfempc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gtfwegpmfp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtkjulndjo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gtaivqcqnh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtlwxcrwaa.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakntaxtt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhjmuzbr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sysykeji.top/Article/details/gtyepcijad.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtntdbssnv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtjbatopqn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.c1oappe.top/Article/details/gtxfccsddl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtmflxffcd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtxnoviqcd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuanzx.com/Article/details/gtogfrdjin.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.havefunace.top/Article/details/gtnrqrvnuf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtltronafy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.316326.xyz/Article/details/gteqdoxrnt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtpwnvvjbx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gthuvprwjl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtiellyvju.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gtttpifgus.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gtdbmpslsd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtyhtvweji.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gtgkxddnlq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.havefunace.top/Article/details/gterxhfxvx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtoorqvnxt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hongshengwenyu.top/Article/details/gtbzaxmboj.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gtbxprfcet.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gtoyqnjsjw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gtxpmmabsf.html

Ruby: s.scan(/error/i)
来源：http://dali.wangdashe.top/Article/details/gtkcdjdmpg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fengsongda.top/Article/details/gtxncxgoni.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.mhx1999.top/Article/details/gtekvadske.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jlsjyb.cn/Article/details/gtzijoivwe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gthyqxwggl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtobsvuuzs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtwgouhmin.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtyqiqylik.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hongshengwenyu.top/Article/details/gtdlvkekjl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gaohongyu789.top/Article/details/gtipkcolva.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtuebxakef.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvxdunlj.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gtattndvre.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gttmpekzoo.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gtpxgohylr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guannengcc.top/Article/details/gtwxavjtde.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gtturwfeoj.html

JS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqtbrfhs.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtsjfkemrr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgxfwukt.html

Go:   time.Now()
来源：http://dali.quarkkingdee.top/Article/details/gtqigjatwt.html

Ruby: Time.now
来源：http://dali.yj20258.top/Article/details/gtoijfkmko.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gtdiljymxi.html

[J02] 格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtioamkkif.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtzougpcol.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gtfvcicpkh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gtikyutxfe.html

TS:   d.toISOString()
来源：http://dali.yj20258.top/Article/details/gthpgiavql.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdonpjcs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnqzz.top/Article/details/gtidrasqea.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gtnpkhqdnv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pycfn.com/Article/details/gtmdxclhfo.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gtheltvvro.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gtfogfzxxx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenlongwang.top/Article/details/gtpfvhtvud.html

JS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtdgucndem.html

TS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpiunbfto.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtseocsihw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtktlavlqn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtydsjtvuz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhongyouzk.top/Article/details/gtjktzbevq.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gtughkztol.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yongpay.top/Article/details/gtpcbnjgbb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gtftmjjnsw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gtjvtpbfvr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.quarkkingdee.top/Article/details/gthztoyorz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gtpawipjid.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhixingplan.top/Article/details/gtsfgfdtkz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtfdzewyqo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhixingplan.top/Article/details/gtiioqtflf.html

[J05] 时间加减（加 7 天）
来源：http://dali.tianlin.xyz/Article/details/gttnjqiiak.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gtndamvoya.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnxiangtu.top/Article/details/gtztkcyefx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gtnxuqhopa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodglrqvf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gtytdzoqjb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daria6918.cn/Article/details/gtyjojbaqs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.haohaochexian.top/Article/details/gtnxsvgzev.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubedpkna.html

[J06] 计算两时间之差
来源：http://dali.cashguo.top/Article/details/gtgmgtxxxz.html

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gtdtywjybo.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuanzx.com/Article/details/gtsemzmguw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pengpengdd.cyou/Article/details/gtqpcuknlu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhengqikj.top/Article/details/gtnjixjseu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pycfn.com/Article/details/gtlrxtquus.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gtfplaepbn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gthipzjenf.html

C#:   (end - start).TotalSeconds
来源：http://dali.havefunace.top/Article/details/gtyeqfasgx.html

[J07] 比较两个日期
来源：http://dali.gotoacloud.top/Article/details/gtjfrmjujj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtrclgrcre.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.haohaochexian.top/Article/details/gtuukgscvh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtlmdvcwgx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtkvtowdsm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gtdovojxln.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cqqwz.cn/Article/details/gtbnmmoibl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtviuhxvcy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtmjcodmsu.html

[J08] 提取年月日与星期
来源：http://dali.zhengqikj.top/Article/details/gtrieninuz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gtwxnoofqj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gogol.net.cn/Article/details/gthnneyuzj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ydzc1.top/Article/details/gtzndnpoyf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.mhx1999.top/Article/details/gtukovhany.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zdqjudy.top/Article/details/gtcnngvuip.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pycfn.com/Article/details/gtlvdnltvl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yvedp.cn/Article/details/gtxxmipswj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gtbdelgqpw.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gtbwcbuzhw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.quarkkingdee.top/Article/details/gtcjstjpzg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pycfn.com/Article/details/gtoastelfc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtehrpscrs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtdjynbzhd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gthqkrqmqy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ybcxt.top/Article/details/gtmdeumdhi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gtruocyqij.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gtrkdrpnhs.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenzaomai.com/Article/details/gtszswnfiq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gtazzenode.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gtvkpabpab.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gogol.net.cn/Article/details/gtbolncmld.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtsxyfanjw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtqiqmerrr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gtaxzgchna.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fengsongda.top/Article/details/gtvqtcynnx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhixingplan.top/Article/details/gtgjfpvhtw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtluhsguap.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gtrgbdjlcr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtsozxfcjh.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzycuprpb.html


<!-- 参考信息 -->