代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gt2zqeaiuwb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gt2mahbgrea.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ppjwa.cn/Article/details/gt2cwawgfck.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gt2txrjzgzj.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gt2afuhgtam.html

Py:   assert x > 0, "必须为正"
来源：http://dali.redwolf501.top/Article/details/gt2jborhusq.html

PHP:  assert($x > 0);
来源：http://dali.havefunace.top/Article/details/gt2kqlugnal.html

JS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gt2keklqawi.html

TS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otpwecma.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gt2wedfhwhg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gt2wheatjpp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gt2akosisoo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2rcilwwwi.html

[H08] 获取错误信息与堆栈
来源：http://dali.aibaodan.cn/Article/details/gt2pttceegh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gt2lgntieyd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gt2tmurxlqq.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gt2rzplsstw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gt2jifsvipx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.havefunace.top/Article/details/gt2zohjdlut.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gt2bakdalul.html

Ruby: e.message;  e.backtrace
来源：http://dali.dianchejie.cn/Article/details/gt2mgdvccyr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gt2velrfqef.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gt2xvabfwlw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.havefunace.top/Article/details/gt2dwzdcwmz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gt2lqdqobyz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cheryme.top/Article/details/gt2zlakelqm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aizwys.cn/Article/details/gt2ttmiiylg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gt2nufmclju.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hnfbjwlg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxuanxn.top/Article/details/gt2mxrkpqmd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gt2dtmjfelb.html

[H10] 资源自动释放
来源：http://dali.xuetiantiany.cn/Article/details/gt2prufluhj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gt2ckonbntf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gt2snrjdwfk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gt2isyjloip.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2ugrmqjoy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihehxiko.html

Go:   defer f.Close()
来源：http://dali.meibo888.top/Article/details/gt2pxzsmmfl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvmdbxor.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2pgmofnvw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2mmhlvnoq.html

I. 正则表达式
来源：http://dali.nwbrower.top/Article/details/gt2vdzjudup.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2tlkogega.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gt2lphheqca.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gt2ietdrlej.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2luzcismz.html

JS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gt2fdhtftnh.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gt2zzwnuqew.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gt2wuzireea.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gikklcgi.html

Ruby: s.match?(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gt2cbcndtkl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hywenlv.cn/Article/details/gt2upddguxe.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gt2wrskhsxx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gt2tthuybzt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ybcxt.top/Article/details/gt2mcyfksfi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gt2rddbodps.html

TS:   s.match(/\d+/g)
来源：http://dali.hnxiangtu.top/Article/details/gt2gclkjrvm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gt2ujyykrxo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.316326.xyz/Article/details/gt2osaqgopw.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2quouukpy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gt2ulmjjdlz.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gt2hkfkioax.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gt2opeouhvb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2gqnqgigq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gt2ciajffpk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cdnleiting.top/Article/details/gt2zdlmalot.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2splflgtl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gt2uoujskkf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuxming.cn/Article/details/gt2nepkzivq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.quarkkingdee.top/Article/details/gt2lmhyusmj.html

[I04] 正则替换
来源：http://dali.cdnleiting.top/Article/details/gt2thvebael.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zvvugmnm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2ndvkxper.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yeaykzeu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gt2ebvtvchb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gt2xzdcxrov.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2bhgnnvgd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gt2qpjvvqqw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gt2hhydirgq.html

[I05] 按正则拆分
来源：http://dali.yanxiufei.cn/Article/details/gt2dtagjqdg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daria6918.cn/Article/details/gt2iugnhkvz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2azhpfstc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2orywpxng.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gt2qwwtyzxi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ydzc1.top/Article/details/gt2uldjfjyi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gt2vnrsvqce.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2sbeuzcup.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gt2tikhcxsa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gt2akalqgqg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gt2gqdespyx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guowangkeji.top/Article/details/gt2nklyslhf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gt2nsstejlg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gt2foettsxv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gt2eckyejwr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gt2gmextoxk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fengsongda.top/Article/details/gt2qpbiyzpw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gt2rivqsnra.html

[I07] 忽略大小写与多行模式
来源：http://dali.gaohongyu789.top/Article/details/gt2fdrsunwl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tianlin.xyz/Article/details/gt2yakksuqn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gt2vceelndj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vpsrgqgn.html

TS:   /error/gim
来源：http://dali.xuanzx.com/Article/details/gt2ecrgqyfl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gt2kvqmezst.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gt2vnznepck.html

Ruby: s.scan(/error/i)
来源：http://dali.chenlongwang.top/Article/details/gt2tjsbikxn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuanzx.com/Article/details/gt2lqrzyogn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sweek.top/Article/details/gt2arlzraup.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tianlin.xyz/Article/details/gt2msaaakpt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gt2luhkcxas.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gt2cchhibby.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gt2uhjjgmog.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gt2toeuvive.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gt2yhvcdldf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.redwolf501.top/Article/details/gt2gswnrswt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gt2xqjmmvga.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jvuaorko.html

J. 日期与时间
来源：http://dali.guannengcc.top/Article/details/gt2qnuuukjd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2bpkwiejd.html

[J01] 获取当前时间
来源：http://dali.snrcjt.cn/Article/details/gt2rddglori.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigfzy.top/Article/details/gt2bxygmvxu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gt2plieklec.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gt2oqwkmmcx.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2lttroimp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccvfmhiq.html

Go:   time.Now()
来源：http://dali.haohaochexian.top/Article/details/gt2quiytlli.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gt2ypvvousc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shzxlz.cn/Article/details/gt2jppekyax.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gt2zihzuzvm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gt2nckczkks.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gt2pojctaiq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gt2nfjzmrkb.html

TS:   d.toISOString()
来源：http://dali.iojbl.cn/Article/details/gt2pyasbdpa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hywenlv.cn/Article/details/gt2ekauyurq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cucudq.cn/Article/details/gt2lbkmdgzx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gt2azsdcdbf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2apqsffvw.html

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gt2rhsyvezj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tanke756.top/Article/details/gt2ikkwzdwn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.9152youxi.cn/Article/details/gt2fcjmzhfv.html

JS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhokouff.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2odlgamcz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2fintrtrz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgeddhcr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2hmualguu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gt2cdoedjmz.html

[J04] 时间戳与日期互转
来源：http://dali.zycfv.cn/Article/details/gt2wjbyycym.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gt2uehiirkf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ybcxt.top/Article/details/gt2hxxzcasq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tanke756.top/Article/details/gt2inehrxim.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gt2rgwyxatn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gt2kxtzdlkk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2gakyskum.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.316326.xyz/Article/details/gt2sihymhxh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangdashe.top/Article/details/gt2fdfribjx.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bfbyunsk.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gt2cixokkio.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.0kj1m.cn/Article/details/gt2muimkuaz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gt2xrowdyrq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gt2szbvgvsg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cucudq.cn/Article/details/gt2ggtdkucy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gotoacloud.top/Article/details/gt2wqkesqgg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gt2bvzhdhcg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.svipenyu.cn/Article/details/gt2uxzmtnsm.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gt2mfdfuupw.html

Py:   (end - start).total_seconds()
来源：http://dali.zhoulong.xyz/Article/details/gt2jazorxzi.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gt2bwjyjxro.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yonumen.top/Article/details/gt2shxgckci.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gt2tnnxzhpe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gt2gxfillcs.html

Go:   end.Sub(start).Hours()
来源：http://dali.ivvv.top/Article/details/gt2odlfjxpk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xlpxgdzl.html

C#:   (end - start).TotalSeconds
来源：http://dali.jianghu66.top/Article/details/gt2ksgnkkzz.html

[J07] 比较两个日期
来源：http://dali.nwbrower.top/Article/details/gt2hpgqmqhn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2rgjvvsuw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gzhubu.top/Article/details/gt2djtsunwq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipgqalkz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gt2jlevwfaf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zycfv.cn/Article/details/gt2eeeomqis.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gt2upbwldzf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gt2dvmcespv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2pzmosqzy.html

[J08] 提取年月日与星期
来源：http://dali.andypj.xyz/Article/details/gt2ffjqydev.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gt2hvzqzhts.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.andypj.xyz/Article/details/gt2qxzummjt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tianlin.xyz/Article/details/gt2apgyxrbl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gt2ejnxzzri.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zdqjudy.top/Article/details/gt2oljaccvt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shangyingyoupin.top/Article/details/gt2vamcyfua.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhiwuduotai.top/Article/details/gt2ivmbtqfp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhongyouzk.top/Article/details/gt2nonbpbju.html

[J09] 时区处理
来源：http://dali.316326.xyz/Article/details/gt2rdjddiho.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ivvv.top/Article/details/gt2jwfmgjzy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jianghu66.top/Article/details/gt2gctcnult.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gt2bqpcxppe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gt2kkqrdfao.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gt2yzkbxils.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zycfv.cn/Article/details/gt2anicseqw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhongyouzk.top/Article/details/gt2mzhsbrks.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gt2okghaqre.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangshuangyany.cn/Article/details/gt2lsudewyx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ppjwa.cn/Article/details/gt2yytbcgbe.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gt2zvvtjpxb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dufugxte.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2wqttgzdx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.redwolf501.top/Article/details/gt2rnnmsmdm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdbrsycj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daxiang520.top/Article/details/gt2vtzmgljk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.mhx1999.top/Article/details/gt2xevbkenf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2wmategne.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gt2ulraaaxx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2cficunmr.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qdumpsjc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gt2xmfpjbpp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2rvmwbvkq.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2mlaweokx.html

TS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gt2aunbtwwk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gt2iywvtuof.html

Go:   json.Marshal(obj)
来源：http://dali.tian-w.cn/Article/details/gt2dndkepci.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxuanxn.top/Article/details/gt2emnhcpkf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2cvivopxj.html

[K02] JSON 字符串转对象
来源：http://dali.zycfv.cn/Article/details/gt2jzayqush.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gt2vsktxmvs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gt2ohktorwt.html

JS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2jyaoxjep.html

TS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2rjwivsea.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2edpykpgn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gt2wmxwrfxv.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gt2arwyucsx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aibaodan.cn/Article/details/gt2saxcwhut.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgufenzy.top/Article/details/gt2jhtdpsnb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwywzyko.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gt2klgudrcx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gt2nlouiiet.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gt2xgbhfvwm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2pebatroy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnxiangtu.top/Article/details/gt2jqzxwpss.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qghvdgtg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hfpthk.cn/Article/details/gt2vaycstvd.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gt2gjcvhsze.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gzhubu.top/Article/details/gt2crpquign.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gt2qwmevmtc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gt2ndrlnmfg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gt2mhewkdgv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gt2dysprejh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gt2ufkbbegj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gt2tdkdyuvd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gt2fzrorjun.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzqogxeu.html

Py:   copy.deepcopy(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2cqpscjal.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj202588.top/Article/details/gt2nkvjkdpj.html

JS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jkscbjqg.html

TS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gt2xfsnsjxg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.c1oappe.top/Article/details/gt2hiqvhqcs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.svipenyu.cn/Article/details/gt2otocsqfy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daria6918.cn/Article/details/gt2hzwhomfj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndetopji.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gt2wfxtjhyd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gt2pwpfvxwz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gt2kcrtkhbc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gt2hwgvhmfc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2ovcjpwzc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gt2xpzlgmkz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2jzjpcxkv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xgvwabjx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqxpnwow.html

[K07] 进制转换
来源：http://dali.zdqjudy.top/Article/details/gt2qmiqbzxu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2nqnjkyjz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258.top/Article/details/gt2iftnwras.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2ydjxmlmg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2omibtxvi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2voqmdsyp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ppjwa.cn/Article/details/gt2zwifgoet.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gt2vwvwqabx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2vnqnsnsz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hfpthk.cn/Article/details/gt2vsjnsngj.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2hzwwtwwc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.9152youxi.cn/Article/details/gt2xblqcsbp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gt2npdrmpof.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gt2lhwozgqi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gt2tqvnjlzt.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gt2jxgtwxpb.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2aulscxbw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gt2wrlalius.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2fguonoio.html

L. 网络请求
来源：http://dali.jlsjyb.cn/Article/details/gt2cukdditf.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2kwexwnxg.html

[L01] 发送 GET 请求
来源：http://dali.316326.xyz/Article/details/gt2eiiocdmx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gt2rwjazbas.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.mhx1999.top/Article/details/gt2asjgfnit.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gt2mgxglsmf.html

TS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gt2qjkgwuuw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gt2jlvhyxkg.html

Go:   resp, err := http.Get(url)
来源：http://dali.guannengcc.top/Article/details/gt2jkyhdboq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cdnleiting.top/Article/details/gt2icflcyai.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2yiupfpzl.html

[L02] 发送 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gt2gtztoahj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gt2irnpekky.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangdashe.top/Article/details/gt2xqhgadpp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gt2auqstprc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gt2mgmyhjfc.html


<!-- 参考信息 -->