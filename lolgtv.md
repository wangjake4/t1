代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.hnqzz.top/Article/details/gtcwxykomt.html

Java: record User(String name, int age) {}
来源：http://dali.quarkkingdee.top/Article/details/gtwfptqgcu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gtzmhqbipu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpoyphvq.html

C#:   record User(string Name, int Age);
来源：http://dali.zycfv.cn/Article/details/gtcibembmn.html

[G15] 枚举
来源：http://dali.jqgfzy.top/Article/details/gtwgbheogt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ppjwa.cn/Article/details/gtlvfvcsfe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gtoogimmun.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guannengcc.top/Article/details/gttzgkhjdm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtuazwfvfx.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gtrjnhnkrc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gtvukhspal.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gtusneteje.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjiafxkcu.html

[G16] 对象转数组 / 字典
来源：http://dali.mhx1999.top/Article/details/gtunikkrjs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhixingplan.top/Article/details/gtlocwkhit.html

PHP:  get_object_vars($obj);
来源：http://dali.fengsongda.top/Article/details/gtpzbomrdo.html

JS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gtkyelsuiq.html

TS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtbncsuqto.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gtevojbkxo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gtcpctmprk.html

Ruby: obj.instance_variables
来源：http://dali.andypj.xyz/Article/details/gtobltsjwr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gtffaudjge.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrxfanww.html

H. 异常与错误处理
来源：http://dali.sxryk.cn/Article/details/gtpcswebjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtppxqrhfw.html

[H01] try / catch 基础
来源：http://dali.tanke756.top/Article/details/gtxefduhzu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gtomyrfokp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gtteerwycc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtehtdjhhw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtsqjxbbfx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuetiantiany.cn/Article/details/gtelchgqfu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gtohdiqoba.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gtbtpmcywf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gtflrfrzqg.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gtpzubuzpk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gtinjbfncr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtspofxzpo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtdyrmqdox.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtnuxkvslj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtemudnvzk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhiwuduotai.top/Article/details/gtbtrkolip.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gtboeajfiq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtxxezbokh.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtuirsdvyy.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gtzyquvsho.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtyofjaauk.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtwaizyqec.html

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtzdandpqt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwloemrik.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcahswbol.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigufen.top/Article/details/gtparbeytw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtllknbegh.html

[H04] 自定义异常类型
来源：http://dali.jiagoushi.top/Article/details/gtpgeuzknv.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gtgieujldg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtavocuxhm.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtxhwyuyzx.html

TS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gtbfsypwip.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtcafbcdnh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgfguowt.html

Ruby: class MyError < StandardError; end
来源：http://dali.kuanghao11.cn/Article/details/gtgmlxkjqq.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gtywyllifg.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxskitrh.html

Py:   except ValueError as e:
来源：http://dali.xuanzx.com/Article/details/gtutwsoqvl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tian-w.cn/Article/details/gtyoexkdpe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtkrbbvxro.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtzxkuoahy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gogol.net.cn/Article/details/gtnfhecdrr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gtlsoleigb.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gtseugaixc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gtfdartxjg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gtmitvsrsl.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gtcpbcanfg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtjbenosfd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtwrniphxs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gttcwaqfey.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ydzc1.top/Article/details/gtnipzjkte.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gtjemfjwta.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sysykeji.top/Article/details/gtdinxbwuo.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gtkicojkno.html

[H07] 断言
来源：http://dali.zycfv.cn/Article/details/gtzzonxxcr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gtikrezbsh.html

PHP:  assert($x > 0);
来源：http://dali.hammf.cn/Article/details/gtuxsropeu.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtmyvfnhms.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtebzxgakk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.redwolf501.top/Article/details/gtbzlxqroz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gtoyebmdwg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gtbkixjowm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtsdalbeiw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhengqikj.top/Article/details/gtjxdauhle.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gtprfvsumc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gtqixjlxso.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gthjqjzbhv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ybcxt.top/Article/details/gtzmlvumur.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gtdzntvcsc.html

Go:   err.Error()
来源：http://dali.jyoumei.cn/Article/details/gtphqqdxbo.html

Ruby: e.message;  e.backtrace
来源：http://dali.jianghu66.top/Article/details/gtszppqivd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqoqgvquf.html

[H09] 带错误码的异常
来源：http://dali.zhoulong.xyz/Article/details/gtqgbuehgc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daria6918.cn/Article/details/gtlwucvums.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gtbdxeviam.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daria6918.cn/Article/details/gtzawvzjvb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hysaishi.cn/Article/details/gtzphjdknp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gtorfstnmd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hammf.cn/Article/details/gtrgsfzusm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.9152youxi.cn/Article/details/gtowajslnc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnxiangtu.top/Article/details/gtkrpemjcm.html

[H10] 资源自动释放
来源：http://dali.ppjwa.cn/Article/details/gtpcrjxmfm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gtassukrzy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.9152youxi.cn/Article/details/gtgioifogl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtlytmykqp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtusyvrthq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gtmtujmwzr.html

Go:   defer f.Close()
来源：http://dali.redwolf501.top/Article/details/gttwgwougx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gtnuwjvadt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtcpunkibu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gthvsqrkwe.html

I. 正则表达式
来源：http://dali.guowangkeji.top/Article/details/gtsetwibla.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtuyvrwbnt.html

[I01] 判断是否匹配
来源：http://dali.gotoacloud.top/Article/details/gttufswruv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gtbnnnopwk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gtngszlhrm.html

JS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gtaoivmecz.html

TS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtcnsgblpg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yvedp.cn/Article/details/gtsflpsdne.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hywenlv.cn/Article/details/gtbliymxov.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gteezeiyup.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gttmmqdpcj.html

[I02] 提取所有匹配
来源：http://dali.hnxiangtu.top/Article/details/gtiusyafch.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtaycwcabc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xziqi.cn/Article/details/gtzlhwmnpg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yueranfly.top/Article/details/gtvsxamung.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gtiawuzney.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtqgjfdlmw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtdnmueuvi.html

Ruby: s.scan(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtuhaoupxt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangdashe.top/Article/details/gtkrmlktqr.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gthynrutrc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtforfsoeo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sxryk.cn/Article/details/gtnjlfgrai.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258888.top/Article/details/gtaxyhmdsm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ppjwa.cn/Article/details/gtvzbxmttb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xinyue.icu/Article/details/gtxmrvjetu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gtxsihxhdp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gaohongyu789.top/Article/details/gtttyafslv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shzxlz.cn/Article/details/gtrguyligi.html

[I04] 正则替换
来源：http://dali.yuanzhike.top/Article/details/gtqiyrwblg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cucudq.cn/Article/details/gtkzfukqkw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gtqoibbkgz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gthvahiovr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtatyzqnjm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtrieaiydr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthkyrcgc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gtrfkxqnoz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gtkneneapz.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gtuacpjslk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gtrkqdayoy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtuirvzfyy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwaaujdos.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtqqapwqut.html

Java: s.split("\\s*,\\s*")
来源：http://dali.smart0.xyz/Article/details/gtdqqbxete.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtsgdixqlp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gtzrufcznr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guowangkeji.top/Article/details/gtlmgyesgp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yangfankeji.com/Article/details/gtfnppppin.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtatxfpeup.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ppjwa.cn/Article/details/gtcbtvhzus.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gtatogkagn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gtuuervewd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtrigvgjwn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daria6918.cn/Article/details/gtybeurnwj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aizwys.cn/Article/details/gtozijbgug.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gthdtcruqu.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigufen.top/Article/details/gtzbkgqycv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gtleyrjmlb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtvoasycgp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.quarkkingdee.top/Article/details/gtmyliycao.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gtkfcrjwyn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteeybnxmn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gthdlqnrhq.html

Ruby: s.scan(/error/i)
来源：http://dali.aizwys.cn/Article/details/gtrdpmbzxm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dashuyun.cn/Article/details/gtxwqggcfl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yvedp.cn/Article/details/gtkmrvzcln.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tianlin.xyz/Article/details/gtjjrnxnas.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtvpwjuiio.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtpwliquiu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtpzsfqtgb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtbmshgxnj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guannengcc.top/Article/details/gtfluxmmqq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gtfksjuump.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtcswbrego.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtkmdkjdyx.html

J. 日期与时间
来源：http://dali.snrcjt.cn/Article/details/gtvcidpqvg.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtgfofrqip.html

[J01] 获取当前时间
来源：http://dali.vqdsnc.cn/Article/details/gtotgkrypv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfkatqji.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gtjpahhpin.html

JS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtxhpbccry.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gtnwglwdmx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.mhx1999.top/Article/details/gteodtzeam.html

Go:   time.Now()
来源：http://dali.sxryk.cn/Article/details/gtsrdujdve.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gtdxisxmiy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jlsjyb.cn/Article/details/gthhflrify.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gtqjbyrvtx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtulujqlju.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtxiaugsqu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.c1oappe.top/Article/details/gtkxzwsozx.html

TS:   d.toISOString()
来源：http://dali.hywenlv.cn/Article/details/gtfnxsfrbe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aizwys.cn/Article/details/gtdfavicdj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hfpthk.cn/Article/details/gtshosvovo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtbtnydkuu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xziqi.cn/Article/details/gtmlaohcqd.html

[J03] 字符串解析为日期
来源：http://dali.jyoumei.cn/Article/details/gttjchncoe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jlsjyb.cn/Article/details/gtbqasnbxo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsefwzlnr.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtpotwqixl.html

TS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtssyosecm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtrpaqyzzh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtarsmldpc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtldbmjkat.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gtcutxmuda.html

[J04] 时间戳与日期互转
来源：http://dali.quarkkingdee.top/Article/details/gtvoelaloi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gtjwgbqujf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jianghu66.top/Article/details/gtbknardbg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cashguo.top/Article/details/gtmascsyjc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gtkrrjrafr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ybcxt.top/Article/details/gtruqeovqf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuanzx.com/Article/details/gtrfblcvgp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nwbrower.top/Article/details/gtjbgegdgj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gtcdkpifdf.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gttlpzzqrf.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gtjfjcvolx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gtnuhquzao.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtnefzenyb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gtrmoqjtbb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtjkodskdh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmreaecig.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aibaodan.cn/Article/details/gtfckptqvn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258888.top/Article/details/gtdyaqeclj.html

[J06] 计算两时间之差
来源：http://dali.cdnleiting.top/Article/details/gtlvedniss.html

Py:   (end - start).total_seconds()
来源：http://dali.9152youxi.cn/Article/details/gtecplqago.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gtnusznbew.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gtqmpeycug.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gtevuoljij.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.smart0.xyz/Article/details/gtrawokpcq.html

Go:   end.Sub(start).Hours()
来源：http://dali.316326.xyz/Article/details/gtbqcsvukd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sysykeji.top/Article/details/gtzygqfwer.html

C#:   (end - start).TotalSeconds
来源：http://dali.ppjwa.cn/Article/details/gtlutgnymj.html

[J07] 比较两个日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticjnbcth.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtprdagmiw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yonumen.top/Article/details/gthgsqqhsm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtqauppqlq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gtifoimuel.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fengsongda.top/Article/details/gtkldctefq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guowangkeji.top/Article/details/gtagybutvw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtyywqrpox.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtlqlccrgt.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gtplwnytwe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gzhubu.top/Article/details/gtuzqptmbu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gttstnhjmn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jyoumei.cn/Article/details/gtnhtvtxai.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hfpthk.cn/Article/details/gtxpxxymuy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjummffi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tian-w.cn/Article/details/gtejrlqgxx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.mhx1999.top/Article/details/gtcgdraaai.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gttymjbhro.html

[J09] 时区处理
来源：http://dali.nwbrower.top/Article/details/gtdestozjr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cheryme.top/Article/details/gtukgtzdru.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gtbunoodkc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtzjhbzzqr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtjvtqinye.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxuanxn.top/Article/details/gtvmurxvvx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gtwkusmmgq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.vqdsnc.cn/Article/details/gtgxmbynmc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nwbrower.top/Article/details/gtpkkqrcvz.html

[J10] 取今天 / 本月第一天
来源：http://dali.iojbl.cn/Article/details/gtmexzeotp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtoctxrsxa.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hammf.cn/Article/details/gtzogaexzo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cdnleiting.top/Article/details/gtygfksyce.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtefgcsyqn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hysaishi.cn/Article/details/gtspdiohzv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnxiangtu.top/Article/details/gtjtnmmbaa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gtghorxwad.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xylfe.cn/Article/details/gtbjzqnqxx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtplelcvad.html

K. JSON 与序列化
来源：http://dali.vqdsnc.cn/Article/details/gtamltepbq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvoihajg.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gtswoiwhto.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtdbncutsl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtiwatgsrr.html

JS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtnptnbunl.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtyzhnivku.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gtlolbgrfj.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gtgjzqtrur.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gtzrhmfhvg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nwbrower.top/Article/details/gthrsscbjx.html

[K02] JSON 字符串转对象
来源：http://dali.quarkkingdee.top/Article/details/gtovtnadjo.html

Py:   json.loads(s)
来源：http://dali.sweek.top/Article/details/gtmbsopcey.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgufenzy.top/Article/details/gtqkwezgwf.html

JS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzinploml.html


<!-- 参考信息 -->