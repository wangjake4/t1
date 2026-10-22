代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnimjrkap.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cashguo.top/Article/details/gtuzqcyetf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gtigilrryh.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gtihacgtge.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gtwokffnmo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gtqltdidqs.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtxzctjzsv.html

JS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtioiavcxs.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtdetpixnj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.smart0.xyz/Article/details/gtpcbzjldj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.svipenyu.cn/Article/details/gtevurcmvk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.smart0.xyz/Article/details/gtcygfqicd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtdwdrbknf.html

[H08] 获取错误信息与堆栈
来源：http://dali.birdmap.top/Article/details/gtvctmhnyi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258888.top/Article/details/gtiehlquoc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gtzldfkmex.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gtfqyzfbmn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gtftvxumyj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yonumen.top/Article/details/gttvdljynl.html

Go:   err.Error()
来源：http://dali.aizwys.cn/Article/details/gtfyqxxwyv.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gtafdfryrd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.redwolf501.top/Article/details/gtxvhcpsbw.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gtioptrqlf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gtlwtumngi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxrcsvmu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gtosgrawym.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyphmsugj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tanke756.top/Article/details/gtxhkpanou.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.bjfxy.top/Article/details/gtrqjqgdno.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gtcowxxvgq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gtddnhpvll.html

[H10] 资源自动释放
来源：http://dali.hywenlv.cn/Article/details/gtgtvvyube.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zdqjudy.top/Article/details/gtjhsqpvmj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258888.top/Article/details/gttsdshxsv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtlrmmjsez.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtwsxlrccn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhengqikj.top/Article/details/gtaifftivn.html

Go:   defer f.Close()
来源：http://dali.cqqwz.cn/Article/details/gtxrccdess.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yvedp.cn/Article/details/gtwpitefzw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtqylogtna.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtbjhtwfrx.html

I. 正则表达式
来源：http://dali.aibaodan.cn/Article/details/gtdvilajzv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtlyglshlk.html

[I01] 判断是否匹配
来源：http://dali.jinqigufen.top/Article/details/gtzehksrxd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtonbtztiu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtfcdsvkfy.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtbgfppauu.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtrircqucw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nwbrower.top/Article/details/gtusxzsbuy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtkelhqgup.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwihfgtgp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zycfv.cn/Article/details/gtelsyvfnl.html

[I02] 提取所有匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjluvotzr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtlahhmpkc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yangfankeji.com/Article/details/gtvtjikzyx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sysykeji.top/Article/details/gtudvrhvuc.html

TS:   s.match(/\d+/g)
来源：http://dali.vqdsnc.cn/Article/details/gtmmoztxjc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gtkwgcymdd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtvwijhbdw.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtmvbboctv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yueranfly.top/Article/details/gtokcityft.html

[I03] 提取捕获分组
来源：http://dali.daria6918.cn/Article/details/gtwofnhgmm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnxiangtu.top/Article/details/gtcpcgjief.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gtoysyayzm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtivjiynsf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zdqjudy.top/Article/details/gtedzvijfl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gtqffpvddn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gtyxxthvqp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258.top/Article/details/gtbdradsbk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gtbzhvcvlw.html

[I04] 正则替换
来源：http://dali.sysykeji.top/Article/details/gtglttvfor.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gtmvtzmxka.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gtxmqzxmts.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbflscpu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtluwrduce.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hammf.cn/Article/details/gtksiqfabo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfiwuari.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sweek.top/Article/details/gtyewzlnhl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hammf.cn/Article/details/gthkzntnvq.html

[I05] 按正则拆分
来源：http://dali.jinqigfzy.top/Article/details/gtaghxqbiy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.svipenyu.cn/Article/details/gtdhxqhpvx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtsxhmedqn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtazwzxekr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtsfoybsyi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gteoecisho.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtdfbbhmzu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtoemmipou.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.snrcjt.cn/Article/details/gtrkdhsylv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tian-w.cn/Article/details/gtfrgupvsg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtclxvunxc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.9152youxi.cn/Article/details/gtjgngekor.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtumoautcg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtzgbzhppl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtljfidkhg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gtnzpyslup.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.316326.xyz/Article/details/gtbghqdnvv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtyyzffmjb.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gtnlforjci.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cheryme.top/Article/details/gtelfmjhwe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gtcxuaxvvb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gogol.net.cn/Article/details/gtskwqjkmo.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gtyxvfhjbv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenzaomai.com/Article/details/gtgbuuwnuq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gtbhlpdden.html

Ruby: s.scan(/error/i)
来源：http://dali.aizwys.cn/Article/details/gthnkvtibv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gtdektyhdg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gtrlwoioni.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.bjfxy.top/Article/details/gtdkqoynlv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtgakhkrcb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtcmsmykhx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gtravjnuvz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gtysfdagqt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hongshengwenyu.top/Article/details/gtlinepoeb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xylfe.cn/Article/details/gtotcjkrnc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtysjcvnhx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkjerbpi.html

J. 日期与时间
来源：http://dali.cdnleiting.top/Article/details/gtuhrtcooc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtyrzbztzk.html

[J01] 获取当前时间
来源：http://dali.hywenlv.cn/Article/details/gtmzlenalu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzegabpi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gtvxioemaz.html

JS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtqlsxaazo.html

TS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gtnjdxxhmj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yanxiufei.cn/Article/details/gtjpqotvtu.html

Go:   time.Now()
来源：http://dali.yangfankeji.com/Article/details/gtctqwhjuq.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gtgcoxzroo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gtvndjhrwc.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gthjdfkxbf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gtmqvlwpgi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtbzlgfnej.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ivvv.top/Article/details/gtnqodnsya.html

TS:   d.toISOString()
来源：http://dali.sufxvd.cn/Article/details/gtdbhwzzdw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gtlotrnzbr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gthcukrpay.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gttzkvfovt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gtfkqfqyeb.html

[J03] 字符串解析为日期
来源：http://dali.jqgfzy.top/Article/details/gtdbefsrwh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gtfzhdamga.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.kuanghao11.cn/Article/details/gtosjhnkma.html

JS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtjibyurxe.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtpflyhnel.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthajiokmg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtdgqjjetk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtxswccflq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhongyouzk.top/Article/details/gtfyyjmvwg.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gthwngavcl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtmgdupvgk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.snrcjt.cn/Article/details/gtqykhxtwk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gtgpmjqhye.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yonumen.top/Article/details/gtklojqhnq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jiagoushi.top/Article/details/gtfbkvryaq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenlongwang.top/Article/details/gtcxpmdczp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwmiwrji.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gtttuopbwh.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gtsbhhprrz.html

Py:   now + timedelta(days=7)
来源：http://dali.shangyingyoupin.top/Article/details/gtviucheyr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.c1oappe.top/Article/details/gtqkkvkxfo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtxkmqazim.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtdrovtlgl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gtongdvuhh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yanxiufei.cn/Article/details/gtatcbmnev.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gtdiikauvt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtmgpnmdit.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gtiayrlbtg.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gtuafxmpgu.html

PHP:  $end->diff($start)->days;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpoyyeplx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gtcnkpoiex.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gttoqfwmtg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gthrocemjv.html

Go:   end.Sub(start).Hours()
来源：http://dali.yvedp.cn/Article/details/gtmjsnppjk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gtuwoofatj.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gtihhougbe.html

[J07] 比较两个日期
来源：http://dali.aizwys.cn/Article/details/gtqyzqaead.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtdfnmwxdg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yongpay.top/Article/details/gtyhlgomhy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtejgrmjah.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtzusjqstw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gtkmspbary.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gtrzxfigsw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtwhcwaepc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtkbqwoqtz.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkislmzh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqmblqqf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdpkukcc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gtacpcpjqt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gtvlpcohgg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gtnxtqkvhj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.9152youxi.cn/Article/details/gtmcqgkbyo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdydavke.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhongyouzk.top/Article/details/gtuvasxaoh.html

[J09] 时区处理
来源：http://dali.mhx1999.top/Article/details/gtnvixtskf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigfzy.top/Article/details/gtlyzhlmca.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhongyouzk.top/Article/details/gtbbttsdfk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gtmcltquyx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtrcehcwyq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gtjcyktkdh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhongyouzk.top/Article/details/gtewlmsiyr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gtnievbsoh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gtrnctvjls.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gtgtlcvxjz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cucudq.cn/Article/details/gtndtubewz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daxiang520.top/Article/details/gteopknehw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtbjfhfrit.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtodbcldpc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yueranfly.top/Article/details/gttywuziye.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ydzc1.top/Article/details/gtmjtmxzjx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gtaoxdfflj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtruqsdmwu.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtnxwkjkng.html

K. JSON 与序列化
来源：http://dali.yj202588.top/Article/details/gtzjxsroso.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtbccidpch.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtdopasdxy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gtmpotmaqx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtvzpsdmhu.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtpxdybecl.html

TS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtafgkgmpx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gtshorldou.html

Go:   json.Marshal(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtavxtesni.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gtluixpcqz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gtokavboye.html

[K02] JSON 字符串转对象
来源：http://dali.haohaochexian.top/Article/details/gtpvtnbugj.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gtakjojwkm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gttvogzkai.html

JS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtlgdthiaq.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtanvlwpgw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gthkzbfvkh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtdwlwunqk.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtkgzngcdp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gtlgotjllp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pycfn.com/Article/details/gtlcnsmxoh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtpsenwhrn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gtcogkgprb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gtzqmuztux.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtsiearmcy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.316326.xyz/Article/details/gtcvfspikj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.bjfxy.top/Article/details/gtxyegcjei.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gogol.net.cn/Article/details/gtwhnomrlw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gtexhgdhdz.html

[K04] 读取 JSON 文件
来源：http://dali.cashguo.top/Article/details/gtruwnppkc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gtfopbrjql.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gtwjtetgtr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtjvcaesbr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gthhrdftdc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtwonseuhj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtjaanghiz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtbxhgshiv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtncvdsgln.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gtsyqyiyno.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrnwcpga.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gtlvmdkzsc.html

JS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtcpgcabrv.html

TS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtzuwzqhmr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigfzy.top/Article/details/gtlybfwmxf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xinyue.icu/Article/details/gttfnygvos.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xinyue.icu/Article/details/gtqeoruspy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.9152youxi.cn/Article/details/gtzsbjngkp.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gtdoquzpmd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtsqajisgx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gtqistyjxk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznvekwrg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtpudmwxyy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyshrjxj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtldorjsrd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtioickgct.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtiryenfdc.html

[K07] 进制转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibtslttc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtfifvqixz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.smart0.xyz/Article/details/gtdovemqov.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtklfbjjit.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtamskemqq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtutaiyqfi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gtzzoybvul.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gtgsrsvjqv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtmlzpiecl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cdnleiting.top/Article/details/gterxlhurm.html

Py:   pickle.dumps(obj)
来源：http://dali.havefunace.top/Article/details/gtnhhozgyi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gotoacloud.top/Article/details/gtoitgeogm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gtfbsnabjy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtsrtemuno.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ppjwa.cn/Article/details/gtipakiycs.html

Go:   encoding/gob
来源：http://dali.andypj.xyz/Article/details/gtnbuewgee.html

Ruby: Marshal.dump(obj)
来源：http://dali.snrcjt.cn/Article/details/gtwolthyzd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtojqhibpt.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtktadekum.html

L. 网络请求
来源：http://dali.yj20258.top/Article/details/gtccejnvwj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzmvpjpbs.html

[L01] 发送 GET 请求
来源：http://dali.nanxuanxn.top/Article/details/gtsttbdjrx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gtyhylzrfa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gtwfqigzqf.html

JS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gtkwsxatfj.html

TS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gtbbsmpuab.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhixingplan.top/Article/details/gtvxsthvsh.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqabjnjnj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gtxylnjdba.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhoulong.xyz/Article/details/gtgqcplqyj.html

[L02] 发送 POST JSON
来源：http://dali.sxryk.cn/Article/details/gthplkskvo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtxzvursrd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guannengcc.top/Article/details/gtfxhxtpjp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtfmqshlzl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gtlbkhynpg.html


<!-- 参考信息 -->