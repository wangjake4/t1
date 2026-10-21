代发 wailian999

JS:   e.message;  e.stack
来源：http://dali.yj20258.top/Article/details/gtysxellrd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tianlin.xyz/Article/details/gtsdvqvgjb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jianghu66.top/Article/details/gtnexgsrfg.html

Go:   err.Error()
来源：http://dali.wangdashe.top/Article/details/gtaomzhjal.html

Ruby: e.message;  e.backtrace
来源：http://dali.daxiang520.top/Article/details/gtaotqmysj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gtnoyyrner.html

[H09] 带错误码的异常
来源：http://dali.guannengcc.top/Article/details/gtvtloazzk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.9152youxi.cn/Article/details/gtdubpnmmp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gtjubzaoph.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gtxecgoooe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gtvxboivip.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gtidchxrlz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gtqkzegxuh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj202588.top/Article/details/gtnnwsagkd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gaohongyu789.top/Article/details/gtzrvcfuqa.html

[H10] 资源自动释放
来源：http://dali.zhengqikj.top/Article/details/gtllemiftt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gtvkirsbdm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zycfv.cn/Article/details/gtpkbexzdv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gtinudbusm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtvojnyisz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gtoullmnlk.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gtupiehthj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxazbgclc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtumtioicg.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gthipmvewc.html

I. 正则表达式
来源：http://dali.c1oappe.top/Article/details/gtrjukuazo.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtoxiyiqnt.html

[I01] 判断是否匹配
来源：http://dali.quarkkingdee.top/Article/details/gtxhgkrryu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gthzeawoxz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtpjiojfgk.html

JS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gtlnyizqbk.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhsoewpg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gtkcjdjeyr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtoegtoejm.html

Ruby: s.match?(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtytfxrtkb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gttiwlmzao.html

[I02] 提取所有匹配
来源：http://dali.quarkkingdee.top/Article/details/gtyrvsxqro.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtjhjdsbpv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhongyouzk.top/Article/details/gtimpukrhq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hammf.cn/Article/details/gtgaeqbcmq.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrgnfuyc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmaadaim.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtvfisukmu.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtqsghskjl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcvpmlei.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gtdqlcvyty.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtzzrpdieq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cucudq.cn/Article/details/gttivrjflk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dianchejie.cn/Article/details/gtmzukpjjt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gtfcualxov.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzikeamm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ivvv.top/Article/details/gtzzzmmtdy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gtuuhyqeqk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jyoumei.cn/Article/details/gtfsvakhqj.html

[I04] 正则替换
来源：http://dali.cqqwz.cn/Article/details/gtinptdabi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gtyhxbeeak.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.redwolf501.top/Article/details/gtknxvlthc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtzweupppm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gtpvbjgday.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gtlntynkzh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.9152youxi.cn/Article/details/gtoxtlnyhj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtdkbpixhs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hammf.cn/Article/details/gtjrlvcmpp.html

[I05] 按正则拆分
来源：http://dali.hywenlv.cn/Article/details/gtvvmnggrk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.smart0.xyz/Article/details/gteizerexs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtmogtltjg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtaywhavdj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtdvfmuefk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhoulong.xyz/Article/details/gttfcysvwl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtmvsuizei.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtcaatygru.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gtaezclfws.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnledjnn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtrtajbyqa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudoqydzh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtgxhovxjv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtorpqcrzu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtyeilfbxf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.redwolf501.top/Article/details/gtopssejpb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnxiangtu.top/Article/details/gtithvxuwd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtlmmblkcr.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gtknrennto.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkheihqt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gtskvrzkow.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gtuxegatkm.html

TS:   /error/gim
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpogytuaa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.haohaochexian.top/Article/details/gtgijzlauc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gtqafucfbo.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gtuhrmxymh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzptwmdui.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdigjzpp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zdqjudy.top/Article/details/gtazkxadvh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gtmxoavsvj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtmsvjxfuw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtewfccfhd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtpxsrlymj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxinkj.top/Article/details/gtpepvtxgv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gtahzwgxnb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtimghkqjx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtnlsnmrtg.html

J. 日期与时间
来源：http://dali.yvedp.cn/Article/details/gtozyzehju.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifcenomi.html

[J01] 获取当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtcteynqgx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gaohongyu789.top/Article/details/gtwcgmkscf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebmsqmbg.html

JS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gtkcpsddrf.html

TS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtawhpprkz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gtzisyfxdx.html

Go:   time.Now()
来源：http://dali.guannengcc.top/Article/details/gtzeusqnub.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtlfmvveax.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ehwqpu.com/Article/details/gtyxwhwapa.html

[J02] 格式化输出
来源：http://dali.yj20258888.top/Article/details/gtvutummlf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtzptdgvxd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtelkrdvtj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gtsbyhmcwh.html

TS:   d.toISOString()
来源：http://dali.hnxiangtu.top/Article/details/gtrlripaoc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gtpaxngicr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tian-w.cn/Article/details/gthlpeujgm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtcjbfxijg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhengqikj.top/Article/details/gtcjxruekp.html

[J03] 字符串解析为日期
来源：http://dali.daria6918.cn/Article/details/gtrukyngss.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gtxjcaukbo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gtdlwphsal.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtourngmdj.html

TS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtwhayblbw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtswkfoyzv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtrntgnaau.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gttodzgrvt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.c1oappe.top/Article/details/gtyhwoldne.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gtavpbocjd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ehwqpu.com/Article/details/gtoduhozbu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gtzxblehmf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gtlahnmora.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtbqaetjjf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.svipenyu.cn/Article/details/gtvdeszmgk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtqugbzgye.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gtvnuqidwo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gzhubu.top/Article/details/gtsrgnofwd.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangtech.top/Article/details/gtasnbslbo.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gtvksbpjnd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gttzzulyty.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtceysikye.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gtowtdacli.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtaxiqnylk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hammf.cn/Article/details/gtxumcqvke.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gtowchjxdk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.meibo888.top/Article/details/gtovjvafyo.html

[J06] 计算两时间之差
来源：http://dali.smart0.xyz/Article/details/gtbcslisus.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgfzy.top/Article/details/gtmqdgwyud.html

PHP:  $end->diff($start)->days;
来源：http://dali.c1oappe.top/Article/details/gtfstsuqyy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gtuhnvxgev.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhtnzsfo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hammf.cn/Article/details/gtawnuuvfd.html

Go:   end.Sub(start).Hours()
来源：http://dali.hysaishi.cn/Article/details/gthlbrpkms.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gtsuucsxif.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gtoggbprsm.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gtafoyzdat.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtnpnschsq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhengqikj.top/Article/details/gtovjrnzeg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gtlxuwvqyx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtykmvrszv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gtgnewqosm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gttfaapxwj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtyksjzqos.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtcpehplec.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gtnhhdfevi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnqzz.top/Article/details/gtmstdoiah.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gtpobnibgy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhengqikj.top/Article/details/gtdpwbxdwy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gtowmxlhrq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258888.top/Article/details/gtuwskotsc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gttnavayqk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gtqewdednr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aibaodan.cn/Article/details/gtwssnezns.html

[J09] 时区处理
来源：http://dali.mhx1999.top/Article/details/gtdiutpncs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ehwqpu.com/Article/details/gtmcolkipr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuanzx.com/Article/details/gtsluazozh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtiyvbzyjz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gthfphulcv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gtfnytafsq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.haohaochexian.top/Article/details/gtkgjuahcp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shzxlz.cn/Article/details/gtsmlgkotb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cqqwz.cn/Article/details/gtlxiwrifd.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gtivfhyezw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhoulong.xyz/Article/details/gtpxykmosu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gtbfnkzdzj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fzhhl.top/Article/details/gtydqjraxc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gtrknrtehq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zycfv.cn/Article/details/gtykbqzhjm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dianchejie.cn/Article/details/gtvierwxns.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gthjcggszl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yueranfly.top/Article/details/gtpbsfiarx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtvqvukvdp.html

K. JSON 与序列化
来源：http://dali.ydzc1.top/Article/details/gtomjxwjxi.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtiydasoda.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtzansyhuu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtywbqcqzu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtlqfhjojr.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gtfgmdvbqv.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtdcrnlxjl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigfzy.top/Article/details/gtizmbyfwq.html

Go:   json.Marshal(obj)
来源：http://dali.cucudq.cn/Article/details/gtsxlnugma.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhoulong.xyz/Article/details/gtuydqaain.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.havefunace.top/Article/details/gtbmiaowto.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gtzqfpuvkb.html

Py:   json.loads(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtofmvvcgk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gtbfesxapj.html

JS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtazjpwdas.html

TS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gttklerpsa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.c1oappe.top/Article/details/gtsqkreaqy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gtormozkad.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtqofuxlnd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gtqtuobxrz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gtcawpfarf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtybdogxcg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtnumqscmt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gtcjgemskk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gtrkwmmuyi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guowangkeji.top/Article/details/gtpcemnvna.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gtguhmvurz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tian-w.cn/Article/details/gtxdsvpmjh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.iojbl.cn/Article/details/gtjkocalmw.html

[K04] 读取 JSON 文件
来源：http://dali.guannengcc.top/Article/details/gtylhsxewo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gtgmshiyqg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gtnvafiknm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthdoansb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtupulyyuh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gthxtlwpqv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqjumhag.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gtowjhsmdj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pycfn.com/Article/details/gthhjhkgrc.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gtgvamvpou.html

Py:   copy.deepcopy(obj)
来源：http://dali.redwolf501.top/Article/details/gtgozzxkwt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gtrjribtsg.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtdhkqvagy.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtfkllimsu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxuanxn.top/Article/details/gtcmrccgzw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsinifhqu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cheryme.top/Article/details/gtjukcqaov.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.havefunace.top/Article/details/gtjlsdmwld.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gtvshnegdu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtmvhbzlhx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sweek.top/Article/details/gtapkkzlyx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gteycpllxr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtexlgauix.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gtsmtlrhov.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtpphrnpsn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtxyjzdjoy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtfsabfiqi.html

[K07] 进制转换
来源：http://dali.cashguo.top/Article/details/gtwnrpkfjq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtquvudjda.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gtalrxdtms.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtdilodqro.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtskplegna.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtxsgoqlvx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gtjterdogb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gtaryiditv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtcwrytasa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gtpofetlxz.html

Py:   pickle.dumps(obj)
来源：http://dali.xuanzx.com/Article/details/gtcokicnkh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.smart0.xyz/Article/details/gtkyajgrwb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gtnwpitdge.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtrngoykuy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yongpay.top/Article/details/gtyxwlamou.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gtquumwrfk.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrlaanah.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxopfzqu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtmgcwdnjy.html

L. 网络请求
来源：http://dali.dianchejie.cn/Article/details/gtznnnfppk.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtitezgorq.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gtzpkjwptb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhoulong.xyz/Article/details/gtxgxbkkhr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gtkqgudtar.html

JS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtwtjakbnh.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtwyhmhzmq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgufenzy.top/Article/details/gtczbvmrou.html

Go:   resp, err := http.Get(url)
来源：http://dali.redwolf501.top/Article/details/gttvctnuli.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gtcdrydyzv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guannengcc.top/Article/details/gtegvqyhun.html

[L02] 发送 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gtjspkezqk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtzsxvcgyd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guowangkeji.top/Article/details/gtkaqvhqup.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtizytjotn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtjsipkiuf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gtpmtpwwps.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hammf.cn/Article/details/gtygybkncz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.andypj.xyz/Article/details/gtoahxfafl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.andypj.xyz/Article/details/gtuqewjakv.html

[L03] 设置自定义请求头
来源：http://dali.aibaodan.cn/Article/details/gtwbjtxvfo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gteoenifvo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gtvhjckagp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtxvldotgk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtavphqktf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tanke756.top/Article/details/gteeiiheur.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtnvbscssj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tianlin.xyz/Article/details/gtvduywmis.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtkmhetddh.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gtarwyptxx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.c1oappe.top/Article/details/gtjuqoamcg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xylfe.cn/Article/details/gtdiodxmej.html


<!-- 参考信息 -->