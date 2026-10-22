代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2uxgwzubu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gt2cbkzabgv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2twqrubqx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gt2xwazvtyj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2ncryuupl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2ghmantqm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gt2laolmfct.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vrbekbcx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guowangkeji.top/Article/details/gt2eokjcoju.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2pzqgzmkz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2zpcvfosv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldrvnhqr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gt2duxbmmjo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gt2emibacvu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2odqwrouy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gt2ehfnzmyd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jlsjyb.cn/Article/details/gt2plwcwkqx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gt2uvdzfpzf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gt2eycsbnsb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gt2uivtohxs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gt2xomikacs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gt2ytayletp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cdnleiting.top/Article/details/gt2ishvfghq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhiwuduotai.top/Article/details/gt2bhhidpdx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2kwpfpgve.html

[I07] 忽略大小写与多行模式
来源：http://dali.kuanghao11.cn/Article/details/gt2oconkuae.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bhtcgwdo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gt2xzuldjrn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yonumen.top/Article/details/gt2cifazzix.html

TS:   /error/gim
来源：http://dali.9152youxi.cn/Article/details/gt2bmvwfwyg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fengsongda.top/Article/details/gt2kuquogcy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gt2oqqfbjcj.html

Ruby: s.scan(/error/i)
来源：http://dali.haohaochexian.top/Article/details/gt2heyefpho.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenlongwang.top/Article/details/gt2ofdvbpyu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hammf.cn/Article/details/gt2zuhmbspy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxinkj.top/Article/details/gt2wubcdwkf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gt2nkxvvsjj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gt2ykrqxkmt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gt2bijuwxnd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gt2lrngucii.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.bjfxy.top/Article/details/gt2bfgwkvhy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gt2ipwllzeq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcuenitc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ymiofivp.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gt2yfesjcvn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2kjvlxsxh.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gt2ncibaljs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigfzy.top/Article/details/gt2xedvxpgk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gt2xnbqbybs.html

JS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gt2aqtsurwp.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwunudom.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2raaxtlps.html

Go:   time.Now()
来源：http://dali.ivvv.top/Article/details/gt2cuaucwok.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gt2yswovtce.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gt2cmttcfiz.html

[J02] 格式化输出
来源：http://dali.shzxlz.cn/Article/details/gt2vsdtdwrr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gt2bifgwnep.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gt2rajpiwff.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigfzy.top/Article/details/gt2rqaxinoo.html

TS:   d.toISOString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akdxupvm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ehwqpu.com/Article/details/gt2jljijcsc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yangfankeji.com/Article/details/gt2qrtfgjya.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxpzgcqv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tianlin.xyz/Article/details/gt2dlfpyyyt.html

[J03] 字符串解析为日期
来源：http://dali.ivvv.top/Article/details/gt2jtdiuikm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2znjhfcio.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ehwqpu.com/Article/details/gt2qgiuyjtd.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2pftvylee.html

TS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2rlqapuwr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2otdoiqjt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2nxturciv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2mbjrsmjs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dashuyun.cn/Article/details/gt2fzjigjgl.html

[J04] 时间戳与日期互转
来源：http://dali.guowangkeji.top/Article/details/gt2dobaiogs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gt2ewgoibgw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.haohaochexian.top/Article/details/gt2kzajjfge.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gt2mvfhpyhw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2krwcyirs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2miisaffl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yvedp.cn/Article/details/gt2fpjllbsy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yvedp.cn/Article/details/gt2vavszono.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gt2paoyxdtn.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gt2xmqwbwhm.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjvewuim.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fengsongda.top/Article/details/gt2kftjbclm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gt2hwwrjkrx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gt2zvqeaqpq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tjenmqkf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.mhx1999.top/Article/details/gt2xhcvkrrr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aibaodan.cn/Article/details/gt2temsukde.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daria6918.cn/Article/details/gt2rfrnqkmm.html

[J06] 计算两时间之差
来源：http://dali.xuetiantiany.cn/Article/details/gt2vovuygyf.html

Py:   (end - start).total_seconds()
来源：http://dali.hysaishi.cn/Article/details/gt2czhouyth.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuanzx.com/Article/details/gt2gsmguoiy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gt2vptwsuzx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gt2zopuxtjk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gt2gmzowfak.html

Go:   end.Sub(start).Hours()
来源：http://dali.gaohongyu789.top/Article/details/gt2cojhvfed.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cqqwz.cn/Article/details/gt2bnlosgjd.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gt2jywoxwaq.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gt2dfltejra.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2rlbfdmuq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cashguo.top/Article/details/gt2tlcnesca.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gt2ktlpwfed.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gt2eyzfgygu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.c1oappe.top/Article/details/gt2lfqrvaft.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhongyouzk.top/Article/details/gt2uktskmsg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2ptqhpibj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2ubrgkivn.html

[J08] 提取年月日与星期
来源：http://dali.ehwqpu.com/Article/details/gt2imkhhtof.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gt2hwqhstdp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gt2twztszay.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zycfv.cn/Article/details/gt2bladrjwx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwdcknme.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdfayuxm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.haohaochexian.top/Article/details/gt2jeyqgvyr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gt2olxvdbyk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gt2cwypthgz.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gt2smcqsavh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gnwyjjrj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cqqwz.cn/Article/details/gt2virttjgp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gt2umyiphog.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gt2oydbbrsc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gt2jlonfscz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gt2ngxkwuvg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cheryme.top/Article/details/gt2ctoqedyv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gt2lrnlcfca.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gt2mavxcify.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gt2psdlfqwh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gt2reahtxwc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2pqrsigrp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2ffvynigq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gt2lyasnirq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gt2gjvypxho.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.snrcjt.cn/Article/details/gt2hdckhjka.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gt2yyintglz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2qdvzbynm.html

K. JSON 与序列化
来源：http://dali.tanke756.top/Article/details/gt2uxtvjopu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2palyproe.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2ybpxcxod.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gt2osgncxri.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2jlqqhkqj.html

JS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2njiwhhph.html

TS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2dscwsfqd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gt2ulxomyam.html

Go:   json.Marshal(obj)
来源：http://dali.smart0.xyz/Article/details/gt2vhebexyo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.svipenyu.cn/Article/details/gt2aslbwegb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.birdmap.top/Article/details/gt2kaeyonhv.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gt2ngbubhyd.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gt2ytikbfmf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gt2apdjtkyl.html

JS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gt2wuvtxlgw.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2jczxxazc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gt2qwtvpfwk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gt2ktyxwjlb.html

Ruby: JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2yjxissah.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gt2xlclrhqe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.iojbl.cn/Article/details/gt2lnpcwydo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gt2mnvddezg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gt2vsdharpi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2kgzsvvet.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gt2orymoond.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.redwolf501.top/Article/details/gt2lluuzrbj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxuanxn.top/Article/details/gt2yvaolwqj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sweek.top/Article/details/gt2qyhpcnux.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tcjgswxy.html

[K04] 读取 JSON 文件
来源：http://dali.nwbrower.top/Article/details/gt2qdidpoci.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gt2zcgiaodx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.havefunace.top/Article/details/gt2pkzpfsnx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2axdjhwko.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gt2zvfbnvnf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2khypkstb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gt2shngsfhy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tian-w.cn/Article/details/gt2idcjcnta.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gt2xlkizrjs.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gt2yjfaozbv.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2wtlozesi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlyjrgpl.html

JS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2ddigpdqf.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2nxpksjnj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xinyue.icu/Article/details/gt2gjdhidic.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gt2drqnvskk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tianlin.xyz/Article/details/gt2mpnqrxsx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.iojbl.cn/Article/details/gt2lvfdgmkn.html

[K06] 解析 URL 查询串
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgjmroip.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangdashe.top/Article/details/gt2tnztdiki.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yanxiufei.cn/Article/details/gt2mlnqllcg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gt2mydcuycn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gt2cwrhphmz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imxnybak.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2iqqgoxkc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2rrkhouah.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2bzltajmo.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gt2vwtbslhn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2zklgewcd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pengpengdd.cyou/Article/details/gt2qdxwgkug.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2zhmvrhlp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2iwxnaedq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2akmaxwaj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxinkj.top/Article/details/gt2woksvoyk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lisjknrp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2bieerjgp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.haohaochexian.top/Article/details/gt2qblmbfnc.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gt2nfaghyrm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tanke756.top/Article/details/gt2pdhtjitc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gt2bmthmrei.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gt2txoxudin.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yvedp.cn/Article/details/gt2kytxzold.html

Go:   encoding/gob
来源：http://dali.shuidangran.top/Article/details/gt2ojzboons.html

Ruby: Marshal.dump(obj)
来源：http://dali.cashguo.top/Article/details/gt2cugtlndc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gt2ayzcprtr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2wzunkvae.html

L. 网络请求
来源：http://dali.aibaodan.cn/Article/details/gt2kblglrcn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2qzfmdqds.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gt2knttpmbq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gt2nghchxna.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zycfv.cn/Article/details/gt2ttfkvvzl.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gt2frlmdrac.html

TS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gt2jdberluu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258888.top/Article/details/gt2jcnzuzis.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gt2ukqdnsjb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gt2emmulcwy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gt2xzhgdecw.html

[L02] 发送 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gt2dfmwjoat.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gt2opuynmtr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gt2vkfodyod.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gt2bjsaylzd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gt2qelcpplj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dashuyun.cn/Article/details/gt2bxtbcapk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.bjfxy.top/Article/details/gt2ffbqxbsd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yongpay.top/Article/details/gt2araefjkz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuanzx.com/Article/details/gt2gdqbvpwo.html

[L03] 设置自定义请求头
来源：http://dali.sufxvd.cn/Article/details/gt2gpkqgspg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gt2gecibfrh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xylfe.cn/Article/details/gt2vlwtfwih.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gt2inwjqkch.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gt2arbjtspy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gt2fdglycuj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gt2jxtrkwpn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yzxphsgs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gt2fmvhfmwz.html

[L04] 设置超时
来源：http://dali.fzhhl.top/Article/details/gt2gpgbzzxj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gt2wwxwgqwr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.svipenyu.cn/Article/details/gt2skyzthrj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gt2lkycqrki.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gt2djqqgwqk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gt2nnhbmnbf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgalords.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zycfv.cn/Article/details/gt2pmwmyscc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2vixczbsv.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gt2cdsbggbp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ivvv.top/Article/details/gt2dhigkhzm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gt2nahnozaf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gt2jjquygch.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odmjruah.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hfpthk.cn/Article/details/gt2xtpucfmi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gt2mqyxmmza.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gt2rfkqabpo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2atmwtidi.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigfzy.top/Article/details/gt2ntjomswr.html

Py:   resp.json()
来源：http://dali.nwbrower.top/Article/details/gt2eisgsull.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gt2mkeqepsy.html

JS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtrvqcfc.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2soyorkph.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2whrasool.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jlsjyb.cn/Article/details/gt2jlqtssuj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gt2ukuasyst.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sufxvd.cn/Article/details/gt2ftuhxndn.html

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gt2alcukqkh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guannengcc.top/Article/details/gt2rzfekxwt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigfzy.top/Article/details/gt2dnyofabn.html

JS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gt2uwxvhbzj.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gt2vhhalkvt.html

Java: resp.statusCode()
来源：http://dali.yanxiufei.cn/Article/details/gt2oybvzblf.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gt2gqxayadn.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vddozqpq.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gt2ljaqlaml.html

[L08] 并发请求多个地址
来源：http://dali.jqgufenzy.top/Article/details/gt2ybksdvkq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gt2rwhfxglp.html

PHP:  curl_multi_init() 系列
来源：http://dali.sxryk.cn/Article/details/gt2viwofarb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2qyzfjflc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gt2qhbjfnrh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sweek.top/Article/details/gt2xdnccpjf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.kuanghao11.cn/Article/details/gt2jkartcpg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gt2erpdqttq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqmgogef.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2kzvlpokc.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gt2quwzruyk.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2wimuaoqf.html

[M01] 读取命令行参数
来源：http://dali.aizwys.cn/Article/details/gt2mamgfefr.html

Py:   sys.argv[1:]
来源：http://dali.tian-w.cn/Article/details/gt2lsrosyag.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gt2syhmydjw.html

JS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gt2cpgfkdnh.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gt2vcaweyac.html

Java: args 数组（main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gt2wupywiip.html

Go:   os.Args[1:]
来源：http://dali.gotoacloud.top/Article/details/gt2srnphifd.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gt2kqhatqbw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gt2alczsemx.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2smheldqg.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gt2dgqxkopx.html


<!-- 参考信息 -->