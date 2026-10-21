代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtjybvesmb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zdqjudy.top/Article/details/gttfhbjsuc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gtxjibasfv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtkmwavoxh.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gtrwrzdifx.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvtakgwh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtspagxjsm.html

JS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtxyxztzle.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtbigzsvlw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtsndbbfll.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gtrrqnkkhy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ehwqpu.com/Article/details/gtesfdwcsa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtvoskjzml.html

[H04] 自定义异常类型
来源：http://dali.cashguo.top/Article/details/gtxazooaie.html

Py:   class MyError(Exception): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmixttyo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtlqaehlqm.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtvmkmwsyv.html

TS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gtejrwdtpg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtyumxgiph.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangdashe.top/Article/details/gtjgxeluhu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gtebunfkse.html

C#:   class MyException : Exception {}
来源：http://dali.dianchejie.cn/Article/details/gtpmlmfajp.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gtwteqxben.html

Py:   except ValueError as e:
来源：http://dali.ybcxt.top/Article/details/gtyaxmyozw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gtszsaudrt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtdzozuflo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtjshqvkpb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnqzz.top/Article/details/gtwbkaaqll.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daria6918.cn/Article/details/gtbwswfvjx.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gtcgwyhltr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gtssjxrlml.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tanke756.top/Article/details/gtapmyhqqr.html

Py:   value = d.get("k") or default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolupbexg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gtbhpoirrh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtfjycjefy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtthyweeyc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gotoacloud.top/Article/details/gtwaylmenr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xinyue.icu/Article/details/gtmliuxcft.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gtwrbzmbhh.html

C#:   obj?.A?.B ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtfzlfhmdo.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gtinpbcowl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gtekijnovy.html

PHP:  assert($x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtgyhtnkhr.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtecaevymp.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtqwyqapyu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gtygqvagmt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sysykeji.top/Article/details/gtbggmahmr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gtubmhiopz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtnvdymbks.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gtligdwhut.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gtyjoewwnt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgufenzy.top/Article/details/gtdwbdvgax.html

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gtthoejvby.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gtoiyligaz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cqqwz.cn/Article/details/gtgwzbmjcv.html

Go:   err.Error()
来源：http://dali.cashguo.top/Article/details/gtmqltctkq.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenjidiqi.icu/Article/details/gtmrqedrlc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.quarkkingdee.top/Article/details/gtsrfibblv.html

[H09] 带错误码的异常
来源：http://dali.zycfv.cn/Article/details/gtwysmrqso.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gtarkbgtes.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gtylgqsokd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gttpbimwql.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gtwzhqgwpx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tianlin.xyz/Article/details/gtlbceypyr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258888.top/Article/details/gtvpnpexws.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.316326.xyz/Article/details/gtxlflbfec.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gtznftvddx.html

[H10] 资源自动释放
来源：http://dali.feifeiyinyue.top/Article/details/gtegauesjl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuxming.cn/Article/details/gthfeilspt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gtgdbhzybi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gtalgftzni.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtkgoluidp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuanzx.com/Article/details/gtzophriww.html

Go:   defer f.Close()
来源：http://dali.sxryk.cn/Article/details/gtkfnjpozb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gttrxgirek.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtjxqhrrqk.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtyjxpqquy.html

I. 正则表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvshqnaxq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtwrwlbxhm.html

[I01] 判断是否匹配
来源：http://dali.birdmap.top/Article/details/gtcbwwozcy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtaszvqxwj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tanke756.top/Article/details/gtkwinkzwx.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtvrbvuamu.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtumhxlabm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvhgssux.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.haohaochexian.top/Article/details/gthvvreawu.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gtofolkvrk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gtttgfzltd.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gtrssvjbxy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gtfcjgvdeb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guowangkeji.top/Article/details/gtyhjyemrw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlaupkwjr.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmenlbyzm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtkuuglnqo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtysqbdnjh.html

Ruby: s.scan(/\d+/)
来源：http://dali.cheryme.top/Article/details/gtuhujuhcw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtrmlsszox.html

[I03] 提取捕获分组
来源：http://dali.sxryk.cn/Article/details/gtnymlpvmr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.mhx1999.top/Article/details/gtrtrozsbs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yvedp.cn/Article/details/gturrkhshg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gtokrjxhlo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gtrvhceced.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkzvzjiz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gtmlfvsnqv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtonlrvyhf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gtixopekfg.html

[I04] 正则替换
来源：http://dali.9152youxi.cn/Article/details/gtqzqarewa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgfzy.top/Article/details/gtsplrwxin.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtdnlgtrlf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtbauhqdpc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtrumwuede.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtwwkikmap.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuanzx.com/Article/details/gtauwmrpss.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fzhhl.top/Article/details/gtbnwsqyeh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtmyibsxaa.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gtkaidltml.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthckwkxmx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xinyue.icu/Article/details/gtvobwwjdk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtsraeyfew.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtmyafblbj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258888.top/Article/details/gtrztbbhak.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.mhx1999.top/Article/details/gtfoahpfeb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtlikmfvpn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gtlkgwzwpb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yvedp.cn/Article/details/gtyqtuugpf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtfkyhorah.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yueranfly.top/Article/details/gtyxoqxcds.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gthmbbisdx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtqdjkaavo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtysxcmuhi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xylfe.cn/Article/details/gtuniktirq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ybcxt.top/Article/details/gtijnosvms.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtchnybdgm.html

[I07] 忽略大小写与多行模式
来源：http://dali.nwbrower.top/Article/details/gtbxgrzqas.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.feifeiyinyue.top/Article/details/gtmsmcjitc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtklupzxmc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenlongwang.top/Article/details/gtwhdlhuue.html

TS:   /error/gim
来源：http://dali.shzxlz.cn/Article/details/gtryawmiaq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yueranfly.top/Article/details/gtzilgrmci.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cdnleiting.top/Article/details/gtkncdawpe.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gtdqwxqemf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gtzwkkkviw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ppjwa.cn/Article/details/gtpozmciab.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aizwys.cn/Article/details/gtdgumxvgi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtrjqcqd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gtocrvktkp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtyleyueee.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtkmiloufg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gtyqxanklk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sysykeji.top/Article/details/gtdgpbcuyj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtmywvslfl.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtuhowutxe.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gtxtzlxvuq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfittvpbq.html

[J01] 获取当前时间
来源：http://dali.yueranfly.top/Article/details/gtcbucalyn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gtxpypdsuf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtvtgouryb.html

JS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtvjwsivan.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtojgowtum.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gtnhzaxxxt.html

Go:   time.Now()
来源：http://dali.xylfe.cn/Article/details/gtvanjpalj.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gteeleeext.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hongshengwenyu.top/Article/details/gtbejbbwqy.html

[J02] 格式化输出
来源：http://dali.yuanzhike.top/Article/details/gtvqsktilt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtpmfewmsg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gttkloxxex.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gtogmhfwlh.html

TS:   d.toISOString()
来源：http://dali.chenzaomai.com/Article/details/gthhgcstct.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.mhx1999.top/Article/details/gtfncdjfpx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gtwtjybrfg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gthsdxxlkr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gthfjpedrb.html

[J03] 字符串解析为日期
来源：http://dali.jinqigfzy.top/Article/details/gtejploxpw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gtpoqrbzko.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daxiang520.top/Article/details/gtsnmyidyd.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtfmzrrabp.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtvcahrnoj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtkxbgscme.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gteezvgevj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtyqvwzteb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daxiang520.top/Article/details/gtrzbgnhhp.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gtdpctidso.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpjsqbzu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gtcgjquhsl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgufenzy.top/Article/details/gtbvdypmuw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gtisxzdlvo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ybcxt.top/Article/details/gtanguosux.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gtoczikzns.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtzmyvbyan.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gtgfxdrnfl.html

[J05] 时间加减（加 7 天）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgczknkwb.html

Py:   now + timedelta(days=7)
来源：http://dali.dianchejie.cn/Article/details/gtktcqjgew.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hysaishi.cn/Article/details/gtfzneotiz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gtusmqjvoh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctkxpaqj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gtgktvwpkn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gtuqmtlqey.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ybcxt.top/Article/details/gtyfhcnxzu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xinyue.icu/Article/details/gtyvgzeqwz.html

[J06] 计算两时间之差
来源：http://dali.yj20258.top/Article/details/gtdxpgsohx.html

Py:   (end - start).total_seconds()
来源：http://dali.hnqzz.top/Article/details/gtnufxcpkt.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gtsovpfkbw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuanzx.com/Article/details/gtemplghrt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gtosjlpqhh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.meibo888.top/Article/details/gtkgvkfuuf.html

Go:   end.Sub(start).Hours()
来源：http://dali.gaohongyu789.top/Article/details/gthrstsucl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gtxvfvfmmp.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gtylxbyhcw.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gtinsvxard.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtbrierbnn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nwbrower.top/Article/details/gtkevaheou.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gteaxpwdic.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtyoiuooez.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yvedp.cn/Article/details/gtzvrwvyec.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtzrmkmuzj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtjaicoxfw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtitpipcim.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gtaqsitidp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzbsepsd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gtmizlktiw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jlsjyb.cn/Article/details/gtveblykzq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gtoawzcdxt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xylfe.cn/Article/details/gtjsgwjwnl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gtgmbxsxcp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yvedp.cn/Article/details/gtsudylmby.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gtptljxcil.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gttptwcnkw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yanxiufei.cn/Article/details/gtlsrnxcma.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zdqjudy.top/Article/details/gtfsqqylkp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gthwtfrqjo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gticifnmzz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gtaycaxvlx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypjqxsji.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gtpwczupxk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yueranfly.top/Article/details/gtcfrkpppe.html

[J10] 取今天 / 本月第一天
来源：http://dali.tian-w.cn/Article/details/gtmxaycwvs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gtiocefexi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.iojbl.cn/Article/details/gtgdkykbvw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigufen.top/Article/details/gtvfwjmcec.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhixingplan.top/Article/details/gttdpubvcg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xylfe.cn/Article/details/gtvllwkwzb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.meibo888.top/Article/details/gthgpssaqi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jiagoushi.top/Article/details/gtspacdpmc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtjefvhbrx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtuiucedpk.html

K. JSON 与序列化
来源：http://dali.chenlongwang.top/Article/details/gteijxbuhw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtjoorjuhc.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gtjajgudwg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtwtcyfzqu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtpmytpzgo.html

JS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtskpfrvrp.html

TS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtnanbzepm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yvedp.cn/Article/details/gturlbkdqx.html

Go:   json.Marshal(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtaadzmkuy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aibaodan.cn/Article/details/gtuamqithn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gtscwpbgsv.html

[K02] JSON 字符串转对象
来源：http://dali.sxryk.cn/Article/details/gtpzkgdcdz.html

Py:   json.loads(s)
来源：http://dali.gotoacloud.top/Article/details/gtpghuvwms.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gtwzcbllzi.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtsbluando.html

TS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyzujwzk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtjxajtgwj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gticgyaeeb.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtagerqbay.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sxryk.cn/Article/details/gtvlqrjcbq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gtbzauauoc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gtcvjhltoe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtxbfhwvde.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gthqqqzjnb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gtnaeawpdy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gtvansamie.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxuanxn.top/Article/details/gtgznyugxd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shzxlz.cn/Article/details/gtldtyjqgm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.bjfxy.top/Article/details/gtduashswu.html

[K04] 读取 JSON 文件
来源：http://dali.sweek.top/Article/details/gtotpukiww.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpllgvmg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gtftmosclx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtmrujgfsk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtnbctbswl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtewgyubxm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtiesqrsrc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gteilduquc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtlonqduse.html

[K05] 深拷贝对象
来源：http://dali.hammf.cn/Article/details/gtnftvmrij.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtovqfvydf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258888.top/Article/details/gtkdigmcyg.html

JS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtotpjzclz.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtkkqnicmu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jiagoushi.top/Article/details/gtmwyccqos.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.haohaochexian.top/Article/details/gtxsjjfrfv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gtsfcbhads.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gtxlgkdcdq.html

[K06] 解析 URL 查询串
来源：http://dali.vqdsnc.cn/Article/details/gtlmrzbeux.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtvjoxsisf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yueranfly.top/Article/details/gtvozwoniw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gtogfaksas.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gtabcqkhcr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guowangkeji.top/Article/details/gtxjgkyavf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtkbfakkli.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtmcdqjpmd.html


<!-- 参考信息 -->