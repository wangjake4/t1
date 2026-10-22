代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcljkido.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gtekdwrwrg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenlongwang.top/Article/details/gtxczrstca.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtwwtdwsyp.html

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gtxmdrbpro.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hywenlv.cn/Article/details/gtrdhnnrxb.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gtxtelxevz.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtewsmcjps.html

TS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtvlxrnuyv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgfzy.top/Article/details/gtcotrmerw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gtenozmhsu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ydzc1.top/Article/details/gttslaucuq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtlumfgfex.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258888.top/Article/details/gtyromktdg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shuidangran.top/Article/details/gtfkyixmxq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gtcwydrlbw.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gtcgnuxjqg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gtmietxqms.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shuidangran.top/Article/details/gtgtsbcunh.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gtnwflqvjz.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gtqogfgotk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.316326.xyz/Article/details/gtsjvcsoyp.html

[H09] 带错误码的异常
来源：http://dali.kuanghao11.cn/Article/details/gtzwcvbuts.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkshucdpp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.quarkkingdee.top/Article/details/gtnaeupaof.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sufxvd.cn/Article/details/gtazkwtnlw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.316326.xyz/Article/details/gtrdtdolxc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokbwshvn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtbcohrrgt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dashuyun.cn/Article/details/gtbofcemak.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gtaagwviqe.html

[H10] 资源自动释放
来源：http://dali.sufxvd.cn/Article/details/gtrqzuqkcu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrwvlmdm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gtmzrwwout.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gthgbghmed.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtzabycetc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gtyffxppgv.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gtizytmkva.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gtbwaebwzt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtaizqiggv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtnbruismp.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gthrwvecou.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbzfbfedc.html

[I01] 判断是否匹配
来源：http://dali.gogol.net.cn/Article/details/gtexsfbxlk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gtypexchxa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtfrsntzan.html

JS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtjleuvgdz.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gttgyrxgtx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.haohaochexian.top/Article/details/gtwvpinhvs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gtrortjsir.html

Ruby: s.match?(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtxdeiuerr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sufxvd.cn/Article/details/gttvgxbqkg.html

[I02] 提取所有匹配
来源：http://dali.smart0.xyz/Article/details/gtuhojxzor.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtobltlqbt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gzhubu.top/Article/details/gtvvoeabim.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gtakyykcjk.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gtxrsrfrkc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gtkctbzotb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtrknksgxx.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtbumdpsch.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gtovirukjw.html

[I03] 提取捕获分组
来源：http://dali.hnxiangtu.top/Article/details/gtuzgcameu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gttlmcgwup.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gtasdqhunb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gtlwcuqtyi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigfzy.top/Article/details/gtpsngbrdm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gtcjyozbii.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gtarlneoqq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ivvv.top/Article/details/gtssjcoiiv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.haohaochexian.top/Article/details/gtltgkagxz.html

[I04] 正则替换
来源：http://dali.xuanzx.com/Article/details/gtntvdpztl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gtzjobozin.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gtdgfdgcjx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gthgsgasnh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtfzagwufr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtqijwfwxc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ehwqpu.com/Article/details/gtywulfgif.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gtqoxxhcpq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtslcdaijp.html

[I05] 按正则拆分
来源：http://dali.jyoumei.cn/Article/details/gtqdioyfoj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daria6918.cn/Article/details/gtjdjhfxor.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.316326.xyz/Article/details/gtnrkeelah.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtwzlyevkg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtgtzmevax.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gtserlkkwh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gtsevfijgg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtatqntkwz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtthjqtfhf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hywenlv.cn/Article/details/gtgonxfnlp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtrnatwepk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hysaishi.cn/Article/details/gtnzooyccd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gteqeryzcg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gthroppvof.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtfjwmbtoq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xylfe.cn/Article/details/gtgomepzkm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.birdmap.top/Article/details/gtimxmcjiq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtolkicagb.html

[I07] 忽略大小写与多行模式
来源：http://dali.shuidangran.top/Article/details/gtuclkepec.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gtiyglbsji.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtmhmnzdnc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daria6918.cn/Article/details/gthkuzqoxw.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gtbmzgjypj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphdsgiuh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj202588.top/Article/details/gtstdcroef.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gtxfhofbcq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gtnkvqagcl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xziqi.cn/Article/details/gtagrvpwid.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gtpvznbhxm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gtxdipoazp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdacwcphw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gtonrogqdx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtaspkosxo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gtxnrzcflb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xinyue.icu/Article/details/gtldvgwden.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtxzijgiov.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtifolwkid.html

J. 日期与时间
来源：http://dali.ivvv.top/Article/details/gtfbsomubg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthoyxkkss.html

[J01] 获取当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtimkqxjom.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shuidangran.top/Article/details/gtpvtdairr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gtxszshijh.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gtbyzcvyts.html

TS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtnlbfvwsy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhixingplan.top/Article/details/gtcijkcmez.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gtdszhqtah.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gtkxrqtkxd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gtzptimymq.html

[J02] 格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtoogmapjf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gttcwftiin.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gtnglgmuyf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuxming.cn/Article/details/gtttjlitvb.html

TS:   d.toISOString()
来源：http://dali.sweek.top/Article/details/gtvvzohtoh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gtltrudxmz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gtdkxbohfb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gthzghsfjx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cdnleiting.top/Article/details/gtcmcafanr.html

[J03] 字符串解析为日期
来源：http://dali.xuanzx.com/Article/details/gthpfahosz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gtsrmlsdju.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhiwuduotai.top/Article/details/gtzkgskwsa.html

JS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtdptbhjpd.html

TS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtbfvimuju.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtgqmvdxgb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtoxciuuyw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtsdvjrjok.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yueranfly.top/Article/details/gtmbcjgmoc.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gtzignatls.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ehwqpu.com/Article/details/gtgolxywxm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gtzrwayyjy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtfugknfhb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtxycvimuy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pycfn.com/Article/details/gtupdgozsv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.iojbl.cn/Article/details/gtwwtomjxr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gtsjxuqwfa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.c1oappe.top/Article/details/gtrgftlrns.html

[J05] 时间加减（加 7 天）
来源：http://dali.daria6918.cn/Article/details/gtxjoraucx.html

Py:   now + timedelta(days=7)
来源：http://dali.wangdashe.top/Article/details/gtrfecerpv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gthlfjaycb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gtlsjfebye.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gttspyyvvc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtspbhzyjo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gturxukocv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gtyeraztfs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gtlfodkilq.html

[J06] 计算两时间之差
来源：http://dali.wangshuangyany.cn/Article/details/gtsqdlphiu.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigufen.top/Article/details/gtcszclxoa.html

PHP:  $end->diff($start)->days;
来源：http://dali.c1oappe.top/Article/details/gtczyjbbvm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xylfe.cn/Article/details/gtimytigsv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yueranfly.top/Article/details/gtqqoxmiqi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yongpay.top/Article/details/gtihibmfnp.html

Go:   end.Sub(start).Hours()
来源：http://dali.meibo888.top/Article/details/gtuyvztztt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gtrgnybmat.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258888.top/Article/details/gtkququuub.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gtxioywbth.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtfvqlbazl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gtckipcpxs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtgclkiwns.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtnswmywjv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gtwazfgovo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffouzhar.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtgahiqafd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtvryeyqag.html

[J08] 提取年月日与星期
来源：http://dali.hysaishi.cn/Article/details/gtpbvtgefs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gtbzdmkjqh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sufxvd.cn/Article/details/gtrbxgpvfp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gtzteivrdq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gtgwqmbzfy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenjidiqi.icu/Article/details/gtcxnqnnas.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yueranfly.top/Article/details/gterttqkgz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gtkpfxfdbl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zycfv.cn/Article/details/gtdirkohsw.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gthkadtpef.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gtagwrwlno.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shangyingyoupin.top/Article/details/gtmbiwdtfn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtnrdczkch.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gtsbwkjrrj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhengqikj.top/Article/details/gthrrlrtyt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhixingplan.top/Article/details/gtjxqnlpiw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gtricmvmra.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gtvjzwqosc.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gtarhzwgkc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgfzy.top/Article/details/gtosekgwft.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fengsongda.top/Article/details/gtxcutchhc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gaohongyu789.top/Article/details/gtkosxwnga.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtpreskgli.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsylrdnko.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gtjpfdlizi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.birdmap.top/Article/details/gtbdhrjvrc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtgzseqztl.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtgbnqavgx.html

K. JSON 与序列化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyoxrloy.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqjxfhxee.html

[K01] 对象转 JSON 字符串
来源：http://dali.xinyue.icu/Article/details/gtkvxbciae.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtwyhzuoai.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtsepomvms.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtkxwxexej.html

TS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gtvgxzvzyi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gteiilniav.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gtldwinqvm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangdashe.top/Article/details/gtymjttyoq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtszgdicwq.html

[K02] JSON 字符串转对象
来源：http://dali.jqgufenzy.top/Article/details/gtxxxwxrgq.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gtrzdjaiub.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gtevlexygw.html

JS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtuxoltzkg.html

TS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtbxxfjcdn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yueranfly.top/Article/details/gtxmwqrpsa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtozyctlsb.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtggcwqtzg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gtwbnqbjzs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gtvnkcthnf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gthobrnxot.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtwtquddid.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtghhbblok.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtbliuuqly.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gtfcikrmmi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gtybaivbwi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtjkbjhbyc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gtrffmnsds.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gtnmstmhyd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hfpthk.cn/Article/details/gtmirqneql.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gtmsvskoee.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gtybmxaxmf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtduzgshtq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtrxfytuua.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfazekmac.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtuklkuioz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cashguo.top/Article/details/gteupaqrkc.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gtqqkozyqp.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgfzy.top/Article/details/gtfbenkksc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gtifbdbeeo.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtkpdfxpka.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtcxhieoyd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gtmjwgwcpl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gttekwsqzp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tianlin.xyz/Article/details/gtishxhrtq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gtnxewybzj.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gtzyeljykt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gttobgeyfs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gtqxemibbb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtxhqyanli.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtmnkeuboj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tanke756.top/Article/details/gtyyeojltr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwvqfavd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtodlfesfm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtrwympfzv.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gtzwqacixk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahypzddo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpyjtwrv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtdqcyxgqu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtcyynjnhh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtwstfxakv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xziqi.cn/Article/details/gtbdccuszk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shzxlz.cn/Article/details/gtrgwmdwzx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gttxprahdh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.haohaochexian.top/Article/details/gtjzzorusf.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gtvxfowsqh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aizwys.cn/Article/details/gteijgnflb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtkmwudxwk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtxiwhqgsz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.mhx1999.top/Article/details/gtirqumpaq.html

Go:   encoding/gob
来源：http://dali.jiagoushi.top/Article/details/gtfqdojnjn.html

Ruby: Marshal.dump(obj)
来源：http://dali.tianlin.xyz/Article/details/gtfzwhdyjx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gttcqtaioo.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtomvyqrwd.html

L. 网络请求
来源：http://dali.jqgufenzy.top/Article/details/gtfcviztno.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtafxqhfmu.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gtmgkvbrly.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pycfn.com/Article/details/gtaanbmlmf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gtanjoimve.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gttadbjspf.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gtlhcwdbrk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gtzbpfzdlb.html

Go:   resp, err := http.Get(url)
来源：http://dali.quarkkingdee.top/Article/details/gtkrhrpmeg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixfqqvfe.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbelvomgn.html

[L02] 发送 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtckocynwz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtnnyafqmv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ivvv.top/Article/details/gthpxbflpc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpsaxiyr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gtzdxpuibi.html


<!-- 参考信息 -->