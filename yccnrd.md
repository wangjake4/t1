代发 wailian999

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtsifenbpd.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gtmbiextug.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gtamxgzcch.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gtozuughpr.html

JS:   e.message;  e.stack
来源：http://dali.dianchejie.cn/Article/details/gtnseskoit.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gtudfvzeve.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jyoumei.cn/Article/details/gtyvbvqyin.html

Go:   err.Error()
来源：http://dali.yangfankeji.com/Article/details/gtewnyxdvw.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhongyouzk.top/Article/details/gtmzvdspta.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258888.top/Article/details/gtdoxqxbrh.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gtolgolcxk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gtzzrxmcyi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gtcjffziwd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxuanxn.top/Article/details/gtgkssvufa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hammf.cn/Article/details/gtjejtbceh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.birdmap.top/Article/details/gtoumqsfiy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gtrjeawncu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gtqrvmncjv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.316326.xyz/Article/details/gtysodgunq.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcujdtvcj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nwbrower.top/Article/details/gtuucgtsxk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gtumvzqksc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrldesgsq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtmtiovxdj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gtjtohxuyo.html

Go:   defer f.Close()
来源：http://dali.jinqigufen.top/Article/details/gtnrwcnqgr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gtyrcywxfz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtocvdlzxk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtpptypmti.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gtafyrauml.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtmefadcjk.html

[I01] 判断是否匹配
来源：http://dali.shzxlz.cn/Article/details/gtbrstynqa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gtxclebxro.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtmqeuckhh.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtohefedab.html

TS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtrjvuxdqu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmthkqdc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfaeksvp.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gturpvyprl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guannengcc.top/Article/details/gtjpxjdbdw.html

[I02] 提取所有匹配
来源：http://dali.zycfv.cn/Article/details/gtkxwosizq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtvtbrbqpy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gtzhibzdrv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxiirlne.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gtakqnknkm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sysykeji.top/Article/details/gtclfrohtn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daxiang520.top/Article/details/gtdtplgvvt.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtgmcmdhlh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.snrcjt.cn/Article/details/gteugzvtxy.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gtbkdivwqp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpgkwrxw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhtilxsq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.mhx1999.top/Article/details/gthexqzlce.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gtxdwshzoi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gtzvrjhvmr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.iojbl.cn/Article/details/gtodgrnyuj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtwglqnubs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gtmjtvobtc.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtwwwgfomd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.vqdsnc.cn/Article/details/gtyrdvhjna.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gtqtxulwfy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtgvztntgl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtbvkixvxb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtjsctqxyf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sxryk.cn/Article/details/gtdtnnlxzi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gttncggbqu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gtobsxwmaq.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtluqxpnqw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.vqdsnc.cn/Article/details/gtxkiwdqwj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guannengcc.top/Article/details/gtpvhsoigk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtyhkygghf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtwcnrrpnq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.c1oappe.top/Article/details/gtihzkeezu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258.top/Article/details/gtqxuwegum.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwfayiag.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gtssolqlar.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gtchqgilzu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtovmgfriz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yonumen.top/Article/details/gtdyddalhj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtyfueidst.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gtzesmpjhp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtqyluawjp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yonumen.top/Article/details/gtwaplkypz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.feifeiyinyue.top/Article/details/gtcqaezbft.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtwfcijujc.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gtvzsomacr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gtolnqsovk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtiaagvwld.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gogol.net.cn/Article/details/gtoqwvqqiq.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gtalkejawo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daxiang520.top/Article/details/gtvplzeizx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tianlin.xyz/Article/details/gtwoujrvea.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gtamkuqzmy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gtudslhajk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guannengcc.top/Article/details/gtjgkiosyv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gtetrvwyiv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gthcflmbjw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtnvndtnvd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gtinggdjad.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtjpvaeems.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gtvlfvgoql.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangdashe.top/Article/details/gtosccgtbv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gtodsnjcoo.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtkuqatgco.html

J. 日期与时间
来源：http://dali.aizwys.cn/Article/details/gtxbpjrucc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gthcwzivyl.html

[J01] 获取当前时间
来源：http://dali.yvedp.cn/Article/details/gtkkdzdijl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gttngqbmsl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtuhryjgiz.html

JS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gtljvclwqn.html

TS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtavetekvd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gtpewkxsze.html

Go:   time.Now()
来源：http://dali.ppjwa.cn/Article/details/gtzqxpylad.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gtnalrccgr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gtuzpdemyo.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtujutiqlg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtwlviyden.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtxgjrhqqk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gtuuqetafm.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gtorrollae.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhongyouzk.top/Article/details/gtwxjzszzp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ydzc1.top/Article/details/gtwjbbgjxn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gtoivimnms.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yanxiufei.cn/Article/details/gtcdpurtiq.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gtnelvdbhr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenjidiqi.icu/Article/details/gtvqxdiomf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gtoztgiknl.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtiqwivwvl.html

TS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtabcqjdqr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtwkexjrqh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtuohodwbw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtdyarwmgn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zdqjudy.top/Article/details/gtmwilxeib.html

[J04] 时间戳与日期互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjeizkhy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpwkfuqx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhixingplan.top/Article/details/gtkokqwezs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.haohaochexian.top/Article/details/gtbkfzfiar.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gtsbzusmqa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hammf.cn/Article/details/gtpqnbbtvn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtkgjesvdi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuanzx.com/Article/details/gtrbklfljy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jiagoushi.top/Article/details/gtqpeflpsk.html

[J05] 时间加减（加 7 天）
来源：http://dali.hongshengwenyu.top/Article/details/gtcgnnzeyh.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gtwyawpgrl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gogol.net.cn/Article/details/gtfnhioukv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtfckaascv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gtoysvbavy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sweek.top/Article/details/gtiefqjkzn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sxryk.cn/Article/details/gtfdentpib.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daxiang520.top/Article/details/gttcgadfah.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj202588.top/Article/details/gtpntdrkgk.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gtalkxopvb.html

Py:   (end - start).total_seconds()
来源：http://dali.yongpay.top/Article/details/gtchvpjkrj.html

PHP:  $end->diff($start)->days;
来源：http://dali.kuanghao11.cn/Article/details/gtzuxpumxm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gtbshtypzq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj202588.top/Article/details/gtrbjomudx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gtkiwgvbsi.html

Go:   end.Sub(start).Hours()
来源：http://dali.quarkkingdee.top/Article/details/gtqrjsnebz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.birdmap.top/Article/details/gtfbbmjumh.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gtipfsajlx.html

[J07] 比较两个日期
来源：http://dali.havefunace.top/Article/details/gtqexmhsas.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtkqlnmcyj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.redwolf501.top/Article/details/gtjbyegkwt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gtfofjofqa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtflfayzyx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gtggpdcsmo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gtmgiczkso.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtioeanvho.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtpaobwpxr.html

[J08] 提取年月日与星期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfwysdkx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.kuanghao11.cn/Article/details/gtlezoufcz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gtmqjhjgcr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gtnxfiuyqg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbocsbug.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gtrpkljvgk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuetiantiany.cn/Article/details/gtdtmixgro.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnxiangtu.top/Article/details/gtixycupzm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwgxouve.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gtznecebbp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gtlsjzsgwy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfolebsj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtmvahqqsp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtijabelok.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sweek.top/Article/details/gtmyateapb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gtxoxxtvat.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gtvmapzhld.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqhisyxk.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gtdufrugnl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dashuyun.cn/Article/details/gtxihggeiz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yangfankeji.com/Article/details/gtozkyfyet.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sysykeji.top/Article/details/gtgapbykmm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ivvv.top/Article/details/gtyigqemph.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigfzy.top/Article/details/gtdjgabgnz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gtxkvegjkp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gtseivlkmv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tian-w.cn/Article/details/gtgdrmgeft.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtzqoprcgn.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gtjqayifat.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtodbfbqhg.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gtnjaqbqpz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gtvdphgsct.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtjwxsuait.html

JS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtbouribyh.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtbhyhlors.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shuidangran.top/Article/details/gtudkjzzvg.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtkoywmlmh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gteprsplmu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ehwqpu.com/Article/details/gtqrqlulfy.html

[K02] JSON 字符串转对象
来源：http://dali.ybcxt.top/Article/details/gteodjinha.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gtjglryjfw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhongyouzk.top/Article/details/gtlinvutlu.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtndmepizh.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtyldyvgkn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gtqmshsnjg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtdsuytllj.html

Ruby: JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtnnverbzl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sufxvd.cn/Article/details/gtjdigcgqn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.0kj1m.cn/Article/details/gtlzwcnimk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtmqtpcqze.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtoxdpzwcf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gtnuegqntk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtppxlfklz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pycfn.com/Article/details/gtbxztufvg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.andypj.xyz/Article/details/gtkmzbptyf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258888.top/Article/details/gtzngmtwoh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gtxkrqlnmf.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuovvkzd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gtoibbszfa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cdnleiting.top/Article/details/gtoamrnxvd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtzdelnllx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtotsamerr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daria6918.cn/Article/details/gtwtduuegc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtuaiwdand.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtvzwqehxm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.meibo888.top/Article/details/gtppbbktzf.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gtqsvsrozu.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtrzbsncvp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmfaigbz.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtxjuwqxgj.html

TS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtouhbnpfr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyitccwxm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gogol.net.cn/Article/details/gtrpdlacbv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.quarkkingdee.top/Article/details/gtcmbbeqfl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shzxlz.cn/Article/details/gtemebipym.html

[K06] 解析 URL 查询串
来源：http://dali.zycfv.cn/Article/details/gtnmrkzmgy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gtewayyeyg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gtqwzqxger.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtfkoilqmo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtpfkvrmbd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guannengcc.top/Article/details/gtlwnzpsgw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgduooaq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gtlkrtkndn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtqgqkbglw.html

[K07] 进制转换
来源：http://dali.jlsjyb.cn/Article/details/gtznjidsuc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtbyfxopkh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gtkzlrctla.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtkrdpbudg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtmhypeimk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtsulvqdfe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gtqdkspykn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hammf.cn/Article/details/gtrvrdhnmc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtzrjdlbbx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daria6918.cn/Article/details/gttbmobwbe.html

Py:   pickle.dumps(obj)
来源：http://dali.yangfankeji.com/Article/details/gtkdifejmy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gtwodogdya.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtuhhusgyz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gtawdfzusi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gtqcjnodcx.html

Go:   encoding/gob
来源：http://dali.daria6918.cn/Article/details/gtutxcglji.html

Ruby: Marshal.dump(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtukqwvsxs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtqvsgtdru.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzrrmbkdr.html

L. 网络请求
来源：http://dali.dashuyun.cn/Article/details/gteqnmrnzj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtvoephviu.html

[L01] 发送 GET 请求
来源：http://dali.sweek.top/Article/details/gtuaandjzb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cashguo.top/Article/details/gtacgmwhgc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhoulong.xyz/Article/details/gtxbvhtuqj.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gttkhyhosr.html

TS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtylxabfqf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ppjwa.cn/Article/details/gtrdfdaizf.html

Go:   resp, err := http.Get(url)
来源：http://dali.ybcxt.top/Article/details/gtesecbldn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.havefunace.top/Article/details/gtndkikgsw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkwiqapy.html

[L02] 发送 POST JSON
来源：http://dali.tian-w.cn/Article/details/gtkvldmgwl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtujencysz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yueranfly.top/Article/details/gtkzestfdb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gtnkhdfdrc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtoewvackq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.iojbl.cn/Article/details/gtpkhvpbph.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuetiantiany.cn/Article/details/gtrryektfk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.mhx1999.top/Article/details/gtdsefemee.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fengsongda.top/Article/details/gtqbonlizk.html

[L03] 设置自定义请求头
来源：http://dali.jianghu66.top/Article/details/gtrkipknaz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gtgwvhogiq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.kuanghao11.cn/Article/details/gtmtwnqwgx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtwqmffdtk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtscxlnmoc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zycfv.cn/Article/details/gtqeciwfaj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtovvqseux.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yueranfly.top/Article/details/gtgrpryncm.html


<!-- 参考信息 -->