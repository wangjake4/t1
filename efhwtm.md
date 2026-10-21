代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksknbpah.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gtnflznbbl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gtxgppnabw.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gtbnsljufk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gtgflcczbo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtuoipkthn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtbhirsfdk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtjrhytuef.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtnofwjzeg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gtrbnhkmwc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gtovszyiww.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtvmywjtmo.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyywzuqlv.html

Py:   raise ValueError("错误信息")
来源：http://dali.xinyue.icu/Article/details/gtnzqngjtx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtagjjemcg.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtvppugufb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtaekngwju.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtrpplncas.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yangfankeji.com/Article/details/gtofjiobdg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sxryk.cn/Article/details/gtauivmixc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtgmbcswfm.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gtsweoefxq.html

Py:   class MyError(Exception): pass
来源：http://dali.ehwqpu.com/Article/details/gtigmzwnyw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gthvwnihfj.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtttfxqetk.html

TS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtvfzkzgau.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtbphmwjnc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenlongwang.top/Article/details/gtpqxbffzh.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gtivglqzmu.html

C#:   class MyException : Exception {}
来源：http://dali.hfpthk.cn/Article/details/gtstzanjxz.html

[H05] 捕获特定类型
来源：http://dali.cdnleiting.top/Article/details/gtktziqvso.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gthqsusarq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gtfizowqvv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtmcfcdbzu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtevtesntx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gttijizely.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcxttgcm.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gtlkovvgdi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.kuanghao11.cn/Article/details/gtcoawzewu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gtltqehbpr.html

Py:   value = d.get("k") or default
来源：http://dali.redwolf501.top/Article/details/gtnjmxocco.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhpejism.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtfeozzikc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtruyfiiva.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gterchtlcx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnxiangtu.top/Article/details/gtxslgomnr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gtvciagbkb.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gtmkewgbbo.html

[H07] 断言
来源：http://dali.yj20258888.top/Article/details/gtrvogklts.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nwbrower.top/Article/details/gtuzrmtibi.html

PHP:  assert($x > 0);
来源：http://dali.sxryk.cn/Article/details/gtkzkvlmfb.html

JS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtyvllkmkn.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtgegzyxna.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gtygjuifql.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gtuznepmem.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gtvyueigxr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtobjjtbml.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gtqtydnepx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nwbrower.top/Article/details/gtcffnqhrk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.316326.xyz/Article/details/gtacbiuwzc.html

JS:   e.message;  e.stack
来源：http://dali.wangshuangyany.cn/Article/details/gtrdvefdyo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgufenzy.top/Article/details/gtxdziilcg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yangfankeji.com/Article/details/gtkzojntjg.html

Go:   err.Error()
来源：http://dali.xylfe.cn/Article/details/gtpcwlurzo.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtxpntwiwf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhiwuduotai.top/Article/details/gtgplchquy.html

[H09] 带错误码的异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtsefphztn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tanke756.top/Article/details/gtmmbxqlhc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gtfrfpepll.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gtfjnwpcyw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yueranfly.top/Article/details/gtfhhhoxih.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gtvghxrnfv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gtplqdyhts.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hongshengwenyu.top/Article/details/gtlfaqxske.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gtpilrsxwh.html

[H10] 资源自动释放
来源：http://dali.dashuyun.cn/Article/details/gtlhmgovef.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtmktrzbhu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gtjlalatzs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gttdxsektq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtegsrgnmr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gtmijqmzrf.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gteheygosc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aibaodan.cn/Article/details/gtjlrvmrrn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtuqcvixnf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtsrgpmggu.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gtpevalmth.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtpsusnzja.html

[I01] 判断是否匹配
来源：http://dali.andypj.xyz/Article/details/gtrajxrfwc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtrxlxqqct.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gthlezhlbt.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gteragjzba.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtmywqcqwy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daxiang520.top/Article/details/gtnyuaocgi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtsxdsmvfr.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtryksuzrs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gtvubhlhqr.html

[I02] 提取所有匹配
来源：http://dali.cashguo.top/Article/details/gtkxhothff.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtmivadzvc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvuuzfgrc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gtveurcwvb.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakepstup.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gtnztyfcas.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtdjfvyskm.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gticutcpvw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.birdmap.top/Article/details/gtfefosiry.html

[I03] 提取捕获分组
来源：http://dali.yangfankeji.com/Article/details/gtzrzgnxpl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gtxmftfxwe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenlongwang.top/Article/details/gtfzggqoyh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gtsycudgfc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hfpthk.cn/Article/details/gtigimcrqx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gtpptpfoef.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgravckc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aizwys.cn/Article/details/gtllfhqzru.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangtech.top/Article/details/gthiwwnexk.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gtbstpimtl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gtazjyfbdn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gtfsbtxoes.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtmdxeicym.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gtoplyxqad.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtjldjrnpm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtyqqoqnvu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fengsongda.top/Article/details/gtvlsjupal.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtpsaaxtbc.html

[I05] 按正则拆分
来源：http://dali.wangdashe.top/Article/details/gtflujnpxz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jianghu66.top/Article/details/gtgibmcpck.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtejoexsqr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtuojqvwhx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtggrtupvw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gotoacloud.top/Article/details/gtfdbhaipb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtdlwxjqei.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtdhbqdatz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zdqjudy.top/Article/details/gtggnsdkiv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gtlsiwoplh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtwdibuxli.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnqzz.top/Article/details/gtnoyacwnu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gttacyvknr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gtqeuqbscj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtempublyd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jianghu66.top/Article/details/gtvpktwmcj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tanke756.top/Article/details/gtzsorrvcr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtlmynhcze.html

[I07] 忽略大小写与多行模式
来源：http://dali.pycfn.com/Article/details/gtlffueiyh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuanzx.com/Article/details/gtiwulckew.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gtlltinyhu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gtjtgpuetx.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gtfnmlwqhp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuetiantiany.cn/Article/details/gtcvnmevsu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yanxiufei.cn/Article/details/gtdifajxkj.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gtjzchyjfx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuanzx.com/Article/details/gtcgljvmya.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gtrgzdbjvy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.iojbl.cn/Article/details/gtilfkcrgj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtrgblpbfx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtowdpbhwq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gthzhrezrw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gtkuyzddtx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gtddtmxamk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnqzz.top/Article/details/gtfvufslgk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtesctvpgc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttusgwlsb.html

J. 日期与时间
来源：http://dali.0kj1m.cn/Article/details/gtuoptadna.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtuvkfeutz.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gtmdthopmi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gtjsroqkbz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtomzzugxr.html

JS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gttuyxghxi.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtelpwxfjw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.havefunace.top/Article/details/gtznbvtfxu.html

Go:   time.Now()
来源：http://dali.tian-w.cn/Article/details/gtkkotdmvm.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gtkjdergyf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.c1oappe.top/Article/details/gtantvrwsn.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtjifnpcdd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtoupiimir.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtxbluizds.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gtswyuoips.html

TS:   d.toISOString()
来源：http://dali.havefunace.top/Article/details/gtgvblhpnp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gtivkozdqu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shzxlz.cn/Article/details/gtxlmjpxxt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtutwezcfx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tanke756.top/Article/details/gtaezvgqjn.html

[J03] 字符串解析为日期
来源：http://dali.daxiang520.top/Article/details/gteoqtejai.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gtlcmuluqu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuanzx.com/Article/details/gtnhavhpby.html

JS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtbnuewiqy.html

TS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtbfnlmlgp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtqoyetwnr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstzvxsws.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtkbyxsnim.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gtrtjhaxhp.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gtdlwijvts.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gtfjmekala.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigufen.top/Article/details/gtlhqewhiy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuanzx.com/Article/details/gtauxyodhk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gtywzxafey.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gtzwaubtvl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gtcefdsunr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtynbxdsbs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gtwwajpsjp.html

[J05] 时间加减（加 7 天）
来源：http://dali.nwbrower.top/Article/details/gtgnsuqfde.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gtvksavxqt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gtyesgpcyx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtddfwfasv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gtjsmzcuwl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuxming.cn/Article/details/gthmdpjvpl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnqzz.top/Article/details/gtbqehvydi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gtklhlphmr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gtnsaoeqlt.html

[J06] 计算两时间之差
来源：http://dali.gaohongyu789.top/Article/details/gtzboiquub.html

Py:   (end - start).total_seconds()
来源：http://dali.fzhhl.top/Article/details/gtuaodtqgg.html

PHP:  $end->diff($start)->days;
来源：http://dali.feifeiyinyue.top/Article/details/gtumuoxbru.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gtsrvrgrww.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.andypj.xyz/Article/details/gtafmelgrn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvwgbity.html

Go:   end.Sub(start).Hours()
来源：http://dali.ybcxt.top/Article/details/gtxklpmunu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.svipenyu.cn/Article/details/gtnulcwxza.html

C#:   (end - start).TotalSeconds
来源：http://dali.hammf.cn/Article/details/gtcqmbzjed.html

[J07] 比较两个日期
来源：http://dali.svipenyu.cn/Article/details/gtafhmxtlh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtabzmpsnm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gtjoodydkx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtwcxgkmyc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtospyrxyr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gtzfjzguaz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gogol.net.cn/Article/details/gtdrtyuzgo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjlagynk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrybkcyv.html

[J08] 提取年月日与星期
来源：http://dali.xuetiantiany.cn/Article/details/gtpzdlokdh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.feifeiyinyue.top/Article/details/gtlreieklp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.c1oappe.top/Article/details/gtlvugefbz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gtgdgqjftv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cashguo.top/Article/details/gtrxqioykk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gtxlxgonbw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gtmuyesuyu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xylfe.cn/Article/details/gtwlqeghkm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gttckyblls.html

[J09] 时区处理
来源：http://dali.xuanzx.com/Article/details/gtqqcawpmd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gtsxazrrxh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fzhhl.top/Article/details/gtnlpnzaal.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtwfpnpiep.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gtfxoczyqc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gtwvjspujn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuetiantiany.cn/Article/details/gtqjtqipbd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.smart0.xyz/Article/details/gtqkurlwmb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gtxojfzufk.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gtjovvfvqw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shuidangran.top/Article/details/gttjrjyhda.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gtthosckev.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.birdmap.top/Article/details/gtonkoxyjp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hammf.cn/Article/details/gtfnbrdpsf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yueranfly.top/Article/details/gtqvebfger.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gtnlsmuxbs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gtrqqcvqxv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gthjrpqsyg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtcvaslcas.html

K. JSON 与序列化
来源：http://dali.jinqigufen.top/Article/details/gtyrgyqbad.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthkbgdgzp.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gtzrjcqtlp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gtlosvnrds.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gttcwrtklq.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtyhykpnko.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gtzzjiqeqc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gtxflggmkw.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtpknnzpde.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daria6918.cn/Article/details/gtkerbacxg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fzhhl.top/Article/details/gtnpihlpvo.html

[K02] JSON 字符串转对象
来源：http://dali.yuanzhike.top/Article/details/gtmlngfsqf.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gtfehrpgew.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pycfn.com/Article/details/gtiffntvlm.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtbxweusgq.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtluyknoho.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.c1oappe.top/Article/details/gtnwjwopnb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gtmvoolqef.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtckjlifnr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gtnheituzq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gtumdrtwkv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtaduigcug.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gtelfonbir.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtlynliudb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtjhpwadtj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdingjiip.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cheryme.top/Article/details/gtdpxhibah.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zycfv.cn/Article/details/gtjcozaywf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvpjcvgb.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gtccduqnoa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gteplwuhie.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gttihocwze.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gtxqojeyfm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtkwmictxk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtotlqjjed.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtfzbnqwri.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gtpatjnxum.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtaublakmh.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gtswtnipns.html

Py:   copy.deepcopy(obj)
来源：http://dali.zdqjudy.top/Article/details/gtalxekwug.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gtidrebpzn.html

JS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtzcypkheb.html

TS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gtaetnxpvy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gtwzamwieq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tianlin.xyz/Article/details/gtoeihxrmq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cucudq.cn/Article/details/gtuugujlhm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gtcnrcdhli.html


<!-- 参考信息 -->