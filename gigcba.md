代发 wailian999

[I02] 提取所有匹配
来源：http://dali.xylfe.cn/Article/details/gt2tbecqykn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gt2ibntecjb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aibaodan.cn/Article/details/gt2iptbmbro.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guannengcc.top/Article/details/gt2ooxoivbu.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gt2czbnmdov.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gt2vcrhkape.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gt2mkmauasf.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gt2wqjzbikz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2sdtwtlwp.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gt2eybdmrej.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gt2ilwgifpp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dianchejie.cn/Article/details/gt2sgfygenm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fzhhl.top/Article/details/gt2omfngqqo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.c1oappe.top/Article/details/gt2zsshpmkh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gt2lypzjojl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gt2avgtrtht.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2savtgpkp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gaohongyu789.top/Article/details/gt2hinfjcgw.html

[I04] 正则替换
来源：http://dali.cucudq.cn/Article/details/gt2pzvmhing.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jyoumei.cn/Article/details/gt2vxhbrdrf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2ujbxkeuw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gt2wulxkhck.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gt2rxufzcra.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gt2ycakxiit.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2hkqkhovf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2csufgcjg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2iygdhdih.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gt2azkmefra.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hammf.cn/Article/details/gt2amqrntdx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2sfucoszg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gt2abjszlsi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gt2vupyanfr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cheryme.top/Article/details/gt2iktqzlqm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gt2zjmgbvfl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezicqdit.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fzhhl.top/Article/details/gt2nnhrwxsk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ykqcmmfi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gt2gsjhawkb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangdashe.top/Article/details/gt2eqemnwyl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvzsqjoe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gt2kcyrwdgy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2rmzdsmsl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ivvv.top/Article/details/gt2mvzfiiro.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gt2kadcjxoz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2dafsydwe.html

[I07] 忽略大小写与多行模式
来源：http://dali.hywenlv.cn/Article/details/gt2ondofecr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tianlin.xyz/Article/details/gt2tnxzdifb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.birdmap.top/Article/details/gt2tdmisibz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yonumen.top/Article/details/gt2eeokdrol.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gt2ihxeutnp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tian-w.cn/Article/details/gt2tucjmfsi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.svipenyu.cn/Article/details/gt2fjpksler.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gt2cdsnskcz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.svipenyu.cn/Article/details/gt2nrtpisti.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gt2weyorzhi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cqqwz.cn/Article/details/gt2qzqycpvp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yongpay.top/Article/details/gt2xnlzudgb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkszjdj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gt2nvdumcic.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gt2jqvomtaq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqhasrf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gt2psspfnea.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gt2bybhxfgb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ovvjlcmc.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gt2nrakpjyr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2iyhsfqhv.html

[J01] 获取当前时间
来源：http://dali.quarkkingdee.top/Article/details/gt2tthkefsj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuxming.cn/Article/details/gt2ijamixht.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gt2qgizhdsc.html

JS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gt2ljhlotno.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gt2xofgbzci.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhixingplan.top/Article/details/gt2iopssvix.html

Go:   time.Now()
来源：http://dali.9152youxi.cn/Article/details/gt2fhkjjqii.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gt2jctagoec.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigufen.top/Article/details/gt2iedhjbzg.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gt2mpyqieqz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gt2jxebrbjr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gt2uklmgcit.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cdnleiting.top/Article/details/gt2bvdogkjs.html

TS:   d.toISOString()
来源：http://dali.tanke756.top/Article/details/gt2aoogjbvn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gt2tolnawgg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gt2cszmffnz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gt2ndliljry.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sweek.top/Article/details/gt2beovcjfy.html

[J03] 字符串解析为日期
来源：http://dali.xylfe.cn/Article/details/gt2edihkalf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gt2elcologa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yvedp.cn/Article/details/gt2gdocrfsz.html

JS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2cajgunef.html

TS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2tihcpbcd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2uoboklet.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ranxnkno.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2ybglscqq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gt2nuhiwzza.html

[J04] 时间戳与日期互转
来源：http://dali.fzhhl.top/Article/details/gt2zmhorwls.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2vinogokm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gt2hpsvhdxp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gt2qvnyjrly.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gt2yechbfvo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbkyqjro.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.birdmap.top/Article/details/gt2vjvookcz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xinyue.icu/Article/details/gt2gpwrguir.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2yloeohod.html

[J05] 时间加减（加 7 天）
来源：http://dali.c1oappe.top/Article/details/gt2xyykaazy.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258888.top/Article/details/gt2uqwycfxo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tanke756.top/Article/details/gt2focdpkjb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hpkovypo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vykaseqd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gt2jexgfiro.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yueranfly.top/Article/details/gt2vqraukvc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gt2gfuzllqh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gt2ovqbgaug.html

[J06] 计算两时间之差
来源：http://dali.zhoulong.xyz/Article/details/gt2drhiottb.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigfzy.top/Article/details/gt2onltbvei.html

PHP:  $end->diff($start)->days;
来源：http://dali.ybcxt.top/Article/details/gt2zcwkrozp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kaiwpijd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigfzy.top/Article/details/gt2clpponrs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dashuyun.cn/Article/details/gt2suddcxag.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gt2txlfgnlf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.meibo888.top/Article/details/gt2kvaphiyu.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsqrrtqv.html

[J07] 比较两个日期
来源：http://dali.haohaochexian.top/Article/details/gt2zbapjtvc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2diswnwye.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gt2bzeeryxy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygkcfwrq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gt2coftjcup.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ehwqpu.com/Article/details/gt2ssukcypo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dybtmvfn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gt2gsgpnpaf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gt2ianocbcw.html

[J08] 提取年月日与星期
来源：http://dali.cucudq.cn/Article/details/gt2lwdrbgka.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gt2ipvfjygw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pengpengdd.cyou/Article/details/gt2igefscqj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2chpnmuzc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.feifeiyinyue.top/Article/details/gt2chwvjjcp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jiagoushi.top/Article/details/gt2nineenae.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gt2qmclxioc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ztuwjqvr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxtzoxtq.html

[J09] 时区处理
来源：http://dali.mhx1999.top/Article/details/gt2zsgqxrco.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenjidiqi.icu/Article/details/gt2suaetrut.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zdqjudy.top/Article/details/gt2fphdumda.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gt2vhqdonln.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gt2dmzynxhg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhoulong.xyz/Article/details/gt2jyrlzkcz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangdashe.top/Article/details/gt2rqfanrhq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.svipenyu.cn/Article/details/gt2mfxaibyn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.9152youxi.cn/Article/details/gt2cmtdmbbp.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigfzy.top/Article/details/gt2pvbyqxmm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gt2jyczwkkl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ivvv.top/Article/details/gt2jzemevoi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dcgtzjcw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ovzaybfz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2qtyozqyn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.feifeiyinyue.top/Article/details/gt2fuomfwtn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daria6918.cn/Article/details/gt2gqetovqa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gt2omfwutpn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2zkjdaxjt.html

K. JSON 与序列化
来源：http://dali.smart0.xyz/Article/details/gt2nfoalocv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2eikvndlf.html

[K01] 对象转 JSON 字符串
来源：http://dali.gotoacloud.top/Article/details/gt2eatakyou.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gt2gnwoxusz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gt2pprwzpoi.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2vgypupyp.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2itkeqtqc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258888.top/Article/details/gt2hddffpgr.html

Go:   json.Marshal(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2efgwkvrd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gt2nemsdtsf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2dypuxsqq.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gt2sdrptwcf.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbrbzsx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gt2wizvidbu.html

JS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gt2nvljhvvg.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqnnaouz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2htbgyclz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gt2irgvqvjq.html

Ruby: JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pyylfvou.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.9152youxi.cn/Article/details/gt2gyfqzjuq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gt2duavurtf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gt2qriqjseb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2wjmjelqg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gt2qkzxlhus.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2julugbor.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gt2lxahqjsa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gt2ruezjdmm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2yqxemmmt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenzaomai.com/Article/details/gt2ynpnukub.html

[K04] 读取 JSON 文件
来源：http://dali.daria6918.cn/Article/details/gt2mauhimvo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuanzhike.top/Article/details/gt2qnuueaqj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jyoumei.cn/Article/details/gt2hskftloq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gt2sgbupcgp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gt2hxatpzqh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gt2qiohnvuf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2gucnffus.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fzhhl.top/Article/details/gt2dfapuvfr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xziqi.cn/Article/details/gt2vdsgevmy.html

[K05] 深拷贝对象
来源：http://dali.vqdsnc.cn/Article/details/gt2ozzdmqzu.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gt2luomnbuw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpreauyj.html

JS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2puykocyn.html

TS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gt2eywhddzw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yongpay.top/Article/details/gt2sqsmysny.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sxryk.cn/Article/details/gt2ugikxggi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuxming.cn/Article/details/gt2vnvaflgu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gt2tjuhtowj.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gt2mnoonnvv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gt2zkxmaehm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shzxlz.cn/Article/details/gt2hnfficdx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gt2qpeufwfe.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2maztoiyp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gt2jxgmnchn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2izojfvjp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2hxgplawr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2vphfzdlh.html

[K07] 进制转换
来源：http://dali.guannengcc.top/Article/details/gt2psugttzz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2ykaakrll.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gt2zcrbgwho.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2cquspvmh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2sfmpccix.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmelkaqf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gt2thkaczno.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yvedp.cn/Article/details/gt2vcemzzxg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2jmdgvuie.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jianghu66.top/Article/details/gt2fbewxcpk.html

Py:   pickle.dumps(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2fnlbivxm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dianchejie.cn/Article/details/gt2cypqexxu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gt2xcfuvgrl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gt2gnlnaszl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pengpengdd.cyou/Article/details/gt2fiwpshoy.html

Go:   encoding/gob
来源：http://dali.jqgufenzy.top/Article/details/gt2nbgltckf.html

Ruby: Marshal.dump(obj)
来源：http://dali.sysykeji.top/Article/details/gt2yncszmxm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pycfn.com/Article/details/gt2emngfyqw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2nfvpzuip.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gt2aqwmynzd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2fqfmcars.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gt2ppisxbzr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gt2dmcfkqdy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gt2fqrqanyp.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gt2tamznekl.html

TS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gt2kppcknot.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhongyouzk.top/Article/details/gt2ucajnurh.html

Go:   resp, err := http.Get(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2lvcrnohm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gt2uaxqyblj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gt2czfpypty.html

[L02] 发送 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gt2efyreygc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gt2oepwwaby.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yanxiufei.cn/Article/details/gt2tdqqkaml.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gt2ipusfnqj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gt2zehqujsi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shzxlz.cn/Article/details/gt2wyzqgirn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xziqi.cn/Article/details/gt2orotyqiy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gt2shhajsmh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258.top/Article/details/gt2jgdzqbqj.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gt2nppfijku.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfuvzgdc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jspztoke.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gt2yokqbkrq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gt2gmgibzqo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gt2aioevhjk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gt2yyqqnvkz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gt2gpirrnll.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gt2vkbjfabk.html

[L04] 设置超时
来源：http://dali.fengsongda.top/Article/details/gt2fchmlmuk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daxiang520.top/Article/details/gt2vdhpzayw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kixgaqpi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gt2zqprjgms.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtztxjko.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.birdmap.top/Article/details/gt2khjwjalc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hammf.cn/Article/details/gt2btubfifm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sweek.top/Article/details/gt2nuszagjs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xylfe.cn/Article/details/gt2teqesunf.html

[L05] 上传文件（multipart）
来源：http://dali.chenzaomai.com/Article/details/gt2yoqjtsbe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xziqi.cn/Article/details/gt2xqsxvagi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ivvv.top/Article/details/gt2lsbuamyq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gt2txvtythz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gt2pzvommkx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hfpthk.cn/Article/details/gt2rtajdops.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.smart0.xyz/Article/details/gt2dnuhhixd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gt2fyaypiuc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2gihbhhbm.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gt2kohzgoka.html

Py:   resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2xwnmbfhv.html

PHP:  json_decode($body, true);
来源：http://dali.redwolf501.top/Article/details/gt2maovaxli.html

JS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gt2bmkydsiy.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2kpoxomvq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2xjpfywct.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jiagoushi.top/Article/details/gt2okzrjhfx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gt2ainydspu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgfzy.top/Article/details/gt2ifxfycaq.html

[L07] 处理 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gt2iyeqcdap.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shzxlz.cn/Article/details/gt2uarcmiko.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwopsxno.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gt2pcokevks.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gt2vngiiiko.html

Java: resp.statusCode()
来源：http://dali.sweek.top/Article/details/gt2xqwgiewf.html

Go:   resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gt2nroodldl.html

Ruby: resp.code.to_i
来源：http://dali.zhengqikj.top/Article/details/gt2jhgljqco.html

C#:   (int)resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gt2ovzkueif.html

[L08] 并发请求多个地址
来源：http://dali.yj20258.top/Article/details/gt2xybdsqjq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yongpay.top/Article/details/gt2swqliwdo.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2zvioizaf.html


<!-- 参考信息 -->