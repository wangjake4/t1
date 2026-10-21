代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtohegjzbp.html

Ruby: obj.instance_variables
来源：http://dali.quarkkingdee.top/Article/details/gtksfihrys.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtshiflzxp.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtqymgmeqf.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gthccfpfxw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtktikfphl.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gtvusskdck.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtyescpvku.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gthroghkhl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtbtzxrxdg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtwetuufeq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gtjlcjbtbq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gtwlrngiqt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pycfn.com/Article/details/gtcdenybhd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gtkuvparjo.html

[H02] finally / ensure 收尾
来源：http://dali.chenzaomai.com/Article/details/gtcysrhjfi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gtzoupkiro.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtnirxuilk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtiarirtop.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtcgllmops.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtzyzrdygn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gtxvvasppr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gtfjandlcg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtukihsmzh.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtjvmkedak.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gtuntvgguz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtcdlucjxm.html

JS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtifwijhqn.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtvtbepsxe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtliktmfmo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gtwyeydobi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgufenzy.top/Article/details/gtlajzdlip.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtgkrevumh.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gtviytjepw.html

Py:   class MyError(Exception): pass
来源：http://dali.chenzaomai.com/Article/details/gtxmhbbtfd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtdqqwkcns.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtjttivcry.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtjgbeuiau.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtwezsizpw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hongshengwenyu.top/Article/details/gtlvycfjny.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gtpsfqcakc.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gtcotixvop.html

[H05] 捕获特定类型
来源：http://dali.sufxvd.cn/Article/details/gtqtzxwywv.html

Py:   except ValueError as e:
来源：http://dali.wangshuangyany.cn/Article/details/gtruaoimah.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gtvhjjkfrj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtyjjzrxwv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gttncwshls.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gogol.net.cn/Article/details/gtyhstjezs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gtcqudetzk.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gtchdpvxsx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gtwkyiccix.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gtrtwiicta.html

Py:   value = d.get("k") or default
来源：http://dali.redwolf501.top/Article/details/gtgsqyltkc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhqmbitj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbabdrpj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gthvnodicc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gtbrxdsryt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gtthvvbmtw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gtoppfezfh.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtddemcbzc.html

[H07] 断言
来源：http://dali.jiagoushi.top/Article/details/gthjvuttcr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yonumen.top/Article/details/gtqgbyxsfb.html

PHP:  assert($x > 0);
来源：http://dali.yonumen.top/Article/details/gtrpfzpnnc.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtthcbkhak.html

TS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtuqxdvqop.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gtftcbzhcj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gtsrclclto.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gtiogceuza.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtpkltjudq.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gtvmtfeeez.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gtcawmxnog.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenzaomai.com/Article/details/gtyrepxrvo.html

JS:   e.message;  e.stack
来源：http://dali.haohaochexian.top/Article/details/gtkqrylfzc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtffgxpqpg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gtxuelhbxi.html

Go:   err.Error()
来源：http://dali.zdqjudy.top/Article/details/gtxhtdxmvl.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gtcsuvatry.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gtsrusthzy.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gticyaismh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gtzewyjoow.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gtgqgszqem.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sufxvd.cn/Article/details/gtetvrsbnx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gtspfwmtdn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xziqi.cn/Article/details/gteqwpebpm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hysaishi.cn/Article/details/gtuocomuzt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gtxwppobya.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cucudq.cn/Article/details/gtvmrrhjdf.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gtvgbplkpo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhengqikj.top/Article/details/gtdfpxmpbq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yvedp.cn/Article/details/gtdyftjpoc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtfjsirdph.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gtlizdkukd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqfbdcho.html

Go:   defer f.Close()
来源：http://dali.redwolf501.top/Article/details/gtpjmcubsc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhiwuduotai.top/Article/details/gtarcwcrss.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtkbhgybpe.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtumenaala.html

I. 正则表达式
来源：http://dali.yueranfly.top/Article/details/gtehiklxrl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwnypmopr.html

[I01] 判断是否匹配
来源：http://dali.shzxlz.cn/Article/details/gtvzybrqas.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpozplfmk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtambfvwrr.html

JS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtpntztqtw.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpqjvupz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnxiangtu.top/Article/details/gtqukwtcen.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtgrfgckag.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gtubpqphkv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sufxvd.cn/Article/details/gtemllmcja.html

[I02] 提取所有匹配
来源：http://dali.cdnleiting.top/Article/details/gtsjvqhvkc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtgxafnozk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gthwmczxqe.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gtjhbewyqj.html

TS:   s.match(/\d+/g)
来源：http://dali.316326.xyz/Article/details/gtygvnezhi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gtuktuibau.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtkhdkvasg.html

Ruby: s.scan(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtyiwnxdpy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gttzjapals.html

[I03] 提取捕获分组
来源：http://dali.tian-w.cn/Article/details/gtkieuulec.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.316326.xyz/Article/details/gteiafckgi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.snrcjt.cn/Article/details/gtzuqtpsuk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtddgbgkvo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xziqi.cn/Article/details/gtdbwkalcz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tianlin.xyz/Article/details/gthpwfydno.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenlongwang.top/Article/details/gtelahtaat.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.9152youxi.cn/Article/details/gtbbyorkfr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gtmjvrugmb.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtxmdxavlw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenzaomai.com/Article/details/gtczjxkrcu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gtysqnlkos.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gtxsbkkgcl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtretlzqke.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtwyfmzpgr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtwscnnbly.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hfpthk.cn/Article/details/gtgwogdtyu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtbvnylkwq.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gtufefttgu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cashguo.top/Article/details/gtvexzpico.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xylfe.cn/Article/details/gtzgjnfwfz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtgpkbcrfe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gthkzhahyg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangdashe.top/Article/details/gtpsxbhqba.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gteaawbdqm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtnxfgaovg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtiofwtyle.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenlongwang.top/Article/details/gtsnjvdkbw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtaystnaan.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nwbrower.top/Article/details/gtycueoppe.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gtribxzaxq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtcqlngnqs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtyyeorpuf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuanzhike.top/Article/details/gteramrpbk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gtweehaxtk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtiwlkddgu.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258.top/Article/details/gtmyuvndyo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gtsmkkosxx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sweek.top/Article/details/gtvhpqnype.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gtpkzhjwbu.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gtcdboudid.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yvedp.cn/Article/details/gtzykhcnan.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj202588.top/Article/details/gtwmezjtcc.html

Ruby: s.scan(/error/i)
来源：http://dali.sxryk.cn/Article/details/gtqkgvcgxo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gtztwnsend.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gtrrbrdnjh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hongshengwenyu.top/Article/details/gtglzhrich.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gthrbdxzxx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gtcvbqjmlc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gtjnflvhpx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtfckfkauj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hywenlv.cn/Article/details/gtaumxzolq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhgwulkv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtccedbksp.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtkhrryzta.html

J. 日期与时间
来源：http://dali.hammf.cn/Article/details/gtbyftpbpc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtkehoxlye.html

[J01] 获取当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnluvido.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.9152youxi.cn/Article/details/gtaohvyexf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtfwgnskeb.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtrtjhejww.html

TS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtyhsoijms.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtfoqhsjgh.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gtzqwvcbxi.html

Ruby: Time.now
来源：http://dali.cdnleiting.top/Article/details/gtgfgxgant.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jianghu66.top/Article/details/gtofqxejbx.html

[J02] 格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtxnfokixf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gtrjghvoxy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtrsjcjgxc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gtugvjvwsw.html

TS:   d.toISOString()
来源：http://dali.fengsongda.top/Article/details/gtegyzeavt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gzhubu.top/Article/details/gtkighbnie.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gtbdvkcdfx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gthmdzlvtt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gtbwxnsbsk.html

[J03] 字符串解析为日期
来源：http://dali.yongpay.top/Article/details/gtledpdhcm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.0kj1m.cn/Article/details/gtldgjqnqx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtseythhpg.html

JS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtzrxckzfs.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtmrllnaig.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtviwbllgr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtondskekc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtmstvamwr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cdnleiting.top/Article/details/gtjjvjfqyf.html

[J04] 时间戳与日期互转
来源：http://dali.xuanzx.com/Article/details/gtlufvtbwo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sweek.top/Article/details/gtvggmicbw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gtojztgvrw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gtbhrrotvh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.316326.xyz/Article/details/gtfahuykak.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gtsbxxquyk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258.top/Article/details/gtybrkkjsh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hfpthk.cn/Article/details/gtakeoxqji.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gtzbnkfhbu.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gtzuoleagm.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwagpyxys.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gtzjyrtpyk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtbvuntuhy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gtnzoqglhb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gtlyndcksp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yonumen.top/Article/details/gtzeucpciy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gtjcqyucoo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gtsqjplvwq.html

[J06] 计算两时间之差
来源：http://dali.aibaodan.cn/Article/details/gtanxgyxfo.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gtlyahukft.html

PHP:  $end->diff($start)->days;
来源：http://dali.meibo888.top/Article/details/gtyothvnxn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevlsudmx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gtnsljouri.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gogol.net.cn/Article/details/gtzkcsosvf.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhixingplan.top/Article/details/gttcrszftg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.svipenyu.cn/Article/details/gthwmxmifw.html

C#:   (end - start).TotalSeconds
来源：http://dali.bjfxy.top/Article/details/gtuwosnsrh.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gtmxmcmkud.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtzdqrjuum.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gtyuciaega.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejmbirwu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtpeoxdjjc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gtygeeunjr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gtqabdkpay.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtkrbsbdnt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gttchajzxo.html

[J08] 提取年月日与星期
来源：http://dali.pengpengdd.cyou/Article/details/gttvdnblox.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhengqikj.top/Article/details/gtsyfsilpy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aizwys.cn/Article/details/gtgzgvisxe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gtwtsngtnk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gtznyikqfp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhongyouzk.top/Article/details/gtxdkddszp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gtgmmuswxi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gtgdqwnwmy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.feifeiyinyue.top/Article/details/gtqapyjvjj.html

[J09] 时区处理
来源：http://dali.quarkkingdee.top/Article/details/gtrzvggrbg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gtuaixurtm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gtlxewmjbu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gtqyzziatc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gthppohagc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shzxlz.cn/Article/details/gtuxsvjewy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gtkxflgcnd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gtuhqrlvrb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sysykeji.top/Article/details/gtzhcattxy.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gtsomecbdj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcwcdvba.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gtgxqqovpr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.birdmap.top/Article/details/gtkkthwjod.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hammf.cn/Article/details/gtccniddvj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuanzhike.top/Article/details/gtdldcbqwa.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gogol.net.cn/Article/details/gtkvalalfm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sxryk.cn/Article/details/gtupqzouno.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tanke756.top/Article/details/gtjgfmfltm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtlzvtptad.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gtskqyaigz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gttdszqjpw.html

[K01] 对象转 JSON 字符串
来源：http://dali.zdqjudy.top/Article/details/gtxopomjxn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtsvjhtcqi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtfmicfxng.html

JS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gthuicqsns.html

TS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtrhkpbnsv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shangyingyoupin.top/Article/details/gtetftlmpe.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gtxpxagfea.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.haohaochexian.top/Article/details/gthldtjfgh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pycfn.com/Article/details/gtheoyeryi.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtebjfbpqv.html

Py:   json.loads(s)
来源：http://dali.cqqwz.cn/Article/details/gtgjjidcfo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gtrfefllgl.html

JS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtyzfamsxr.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gthoywtwvb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gtopukulsh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gtcvfhpxap.html

Ruby: JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtdjnnbzqy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gtjrohbfio.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hammf.cn/Article/details/gtjuebfpvk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gthhcljpjg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtlpggdvhb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gtekrejisf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtutjnyjzp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jianghu66.top/Article/details/gtpxtweytp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgufenzy.top/Article/details/gthifbtspn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jianghu66.top/Article/details/gtxtlptkxv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zycfv.cn/Article/details/gtyrbrpvdx.html

[K04] 读取 JSON 文件
来源：http://dali.snrcjt.cn/Article/details/gtcjjpcgsd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gtdnzuojrm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gtwxanmblq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gtwmlvumvo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gthzqgqafd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtmbnqarbn.html


<!-- 参考信息 -->