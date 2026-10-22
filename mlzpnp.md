代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.quarkkingdee.top/Article/details/gt2xbvlisqq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhiwuduotai.top/Article/details/gt2xmzsvcsp.html

[I04] 正则替换
来源：http://dali.jqgufenzy.top/Article/details/gt2ofgpiayw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tianlin.xyz/Article/details/gt2hmpmquug.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2fvgyiunw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2qxnpbzpc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2xubhqwwv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2oarvksax.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2ccnypmax.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigufen.top/Article/details/gt2clfybezm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gt2pyfluvvb.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gt2nyaqaxeh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258.top/Article/details/gt2ruisuhfs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gt2eqxqlprk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2vysyviai.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2scqjsksg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jyoumei.cn/Article/details/gt2agbutuhx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yongpay.top/Article/details/gt2vgzcdxge.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2gnvgsnfr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgpswfpo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tian-w.cn/Article/details/gt2ypnfqhdp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2eqyjovlj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zycfv.cn/Article/details/gt2cafhjhos.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2oshbphzc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gt2wpymenub.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2uecvaajp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sysykeji.top/Article/details/gt2cqnuimsk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guowangkeji.top/Article/details/gt2vicqugoj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gt2troprqab.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gt2bacgxgay.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dzahoxdj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ivvv.top/Article/details/gt2zprujkyv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cheryme.top/Article/details/gt2kawtcccm.html

TS:   /error/gim
来源：http://dali.zdqjudy.top/Article/details/gt2kyblqnhj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hysaishi.cn/Article/details/gt2gqlcigvf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gt2idepyweo.html

Ruby: s.scan(/error/i)
来源：http://dali.zdqjudy.top/Article/details/gt2etcojkyq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gt2nfxyydta.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gt2qdjetwkw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gt2smbdmqvt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2onosjhkk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gt2fkeufdjo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2ahfeevgx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gt2umlwnoxr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gt2ividbzqq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangdashe.top/Article/details/gt2cwoyrnox.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gt2immmxcbj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2lnlriadc.html

J. 日期与时间
来源：http://dali.guowangkeji.top/Article/details/gt2qethyylx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2mqhaqjph.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gt2qpfbzgvt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yangfankeji.com/Article/details/gt2qqrriwfm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gt2bwkbvwzn.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gt2ogfelmve.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gt2prkorrvr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gt2wqurmkip.html

Go:   time.Now()
来源：http://dali.sysykeji.top/Article/details/gt2ssgaxfcg.html

Ruby: Time.now
来源：http://dali.yanxiufei.cn/Article/details/gt2dxtpbwot.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gt2lkijroum.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gt2otejwehb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gt2kuzqljcd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gt2iqbpydwl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.c1oappe.top/Article/details/gt2nenuxphl.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gt2dkaaroxa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtxhcbxx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ivvv.top/Article/details/gt2jbyawdma.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gt2qwdrovvs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gt2msqreyfa.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kkvctcot.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gaohongyu789.top/Article/details/gt2ewkcbwrz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guowangkeji.top/Article/details/gt2qzkroitj.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2alxfvprz.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2hfglrzra.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2issdpkqf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2fjumzmin.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2tmvvhbev.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gt2rlcmehip.html

[J04] 时间戳与日期互转
来源：http://dali.yangfankeji.com/Article/details/gt2hpicffff.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gt2xpgezcql.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuetiantiany.cn/Article/details/gt2audfqtlq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhoulong.xyz/Article/details/gt2gjolxlxi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.vqdsnc.cn/Article/details/gt2bwnbqfns.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ppjwa.cn/Article/details/gt2ncvbyctu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2tfwnkzqv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2syfrqyjh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zdqjudy.top/Article/details/gt2qmptsuie.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gt2xsvxavfa.html

Py:   now + timedelta(days=7)
来源：http://dali.zhixingplan.top/Article/details/gt2bxzkazwn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sufxvd.cn/Article/details/gt2cujhonui.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlvlfuaz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2tmrwsnly.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2wrlwsuru.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gt2xxmxmrml.html

Ruby: Time.now + 7 * 86400
来源：http://dali.meibo888.top/Article/details/gt2pjflxdif.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gzhubu.top/Article/details/gt2duxfcndg.html

[J06] 计算两时间之差
来源：http://dali.ehwqpu.com/Article/details/gt2zujgtlkb.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gt2vhdxttpu.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gt2nzpipihz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gt2yyqkhssf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnqzz.top/Article/details/gt2lborwlir.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gt2mriltkxx.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gt2uingmksz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gt2rtdxnevq.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gt2jjctonkp.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gt2rtyuaqyt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gt2dnynaeqm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gt2jcgzmvie.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gt2rhxneytu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gt2jzofsezr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gt2wkdwcvxa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rjatwqrj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gt2bbuuzyxl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2nzfuhjvl.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gt2kyqqiuue.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gt2bzsgmzwr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gt2trgqtpvt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gt2wrxmxqgj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gt2vnpuevcd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhixingplan.top/Article/details/gt2fmjmysvw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtyupizm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzrzbls.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gt2glievjpg.html

[J09] 时区处理
来源：http://dali.0kj1m.cn/Article/details/gt2mwhnneez.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jianghu66.top/Article/details/gt2jpjbstuj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwlwjqjp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gt2obrbyrkr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2zmqupnkm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gt2ptkcsekk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.smart0.xyz/Article/details/gt2nduiwmfq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.meibo888.top/Article/details/gt2wlfbuiqp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhongyouzk.top/Article/details/gt2zpzdtmgr.html

[J10] 取今天 / 本月第一天
来源：http://dali.dianchejie.cn/Article/details/gt2ntwvlgka.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ppjwa.cn/Article/details/gt2hdehnllj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zdqjudy.top/Article/details/gt2ycklypnm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dmjsnymx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fzhhl.top/Article/details/gt2sxkgvmga.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2thjenzla.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hongshengwenyu.top/Article/details/gt2mueiaywz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gt2okkfamky.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cqqwz.cn/Article/details/gt2kxzmrija.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ffxeyfpm.html

K. JSON 与序列化
来源：http://dali.zhoulong.xyz/Article/details/gt2oanrzhnn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2oslysaey.html

[K01] 对象转 JSON 字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2scoijgij.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gt2yvssupbs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gt2udklxgun.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2lynsznuq.html

TS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gt2etsjmgtj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gt2rwuvtqvi.html

Go:   json.Marshal(obj)
来源：http://dali.guannengcc.top/Article/details/gt2mvvvqvjn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gt2yuwpuani.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2xdncnzsl.html

[K02] JSON 字符串转对象
来源：http://dali.sysykeji.top/Article/details/gt2gcmpldgh.html

Py:   json.loads(s)
来源：http://dali.tianlin.xyz/Article/details/gt2oucgasch.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gt2qyuodpiw.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sibdxiwa.html

TS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2ltbactqy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2rjiprrpy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gt2sdmsyzpk.html

Ruby: JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2nfdnlpht.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gt2odpprjxl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gt2yltntjgt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gt2lrrundrx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2jifsnaxd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gt2cdudvnvy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gt2umkartto.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.havefunace.top/Article/details/gt2nqsxpjov.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gt2cruybmqw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2pgtymgim.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kbmqrbmc.html

[K04] 读取 JSON 文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2raflsclu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.snrcjt.cn/Article/details/gt2bxqpshcd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gt2zgrnbwip.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gt2rudqfuux.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gt2wkxdxvpy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2cymqkvol.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gt2cckuomzg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daxiang520.top/Article/details/gt2shbrecef.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yonumen.top/Article/details/gt2izrdrgrb.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gt2hfeapril.html

Py:   copy.deepcopy(obj)
来源：http://dali.mhx1999.top/Article/details/gt2rubmphad.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangdashe.top/Article/details/gt2imkkwxhe.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2myttkudf.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2jmawoitr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gt2enastsfg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gt2tfmkqgun.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gt2ruuiqgfb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gt2qiqyzoup.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gt2phpdjatm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gt2xzygqlni.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cdnleiting.top/Article/details/gt2sbnigeek.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlqhrcnr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gt2pvbhjxau.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gt2nxqkrceg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2qhtnydms.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2wzilsjot.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gt2qlvekyax.html

[K07] 进制转换
来源：http://dali.gaohongyu789.top/Article/details/gt2omuhqbun.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2jemvqwez.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.havefunace.top/Article/details/gt2ihvovnfd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nskmpatl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vcylgell.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2djjtqqfs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shzxlz.cn/Article/details/gt2dmsefemf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aizwys.cn/Article/details/gt2nmoxvjrz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2hrpzndmq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tian-w.cn/Article/details/gt2ryiypeov.html

Py:   pickle.dumps(obj)
来源：http://dali.xylfe.cn/Article/details/gt2rqgjvemk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenlongwang.top/Article/details/gt2rjqiaviv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lzqhcwis.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gt2finrrfod.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxubbdpz.html

Go:   encoding/gob
来源：http://dali.yuanzhike.top/Article/details/gt2eganlysw.html

Ruby: Marshal.dump(obj)
来源：http://dali.sweek.top/Article/details/gt2hywmaqxk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gt2vnvmkykv.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2fclyylwh.html

L. 网络请求
来源：http://dali.zdqjudy.top/Article/details/gt2koayvneb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2pssgvslh.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gt2jgxkjfrj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gt2kkxisphg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gt2ecoyylra.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2gdwfibrq.html

TS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gt2tmgymctf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ydzc1.top/Article/details/gt2ifwrbbva.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gt2uagxfhzd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gt2wztgiwxc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xziqi.cn/Article/details/gt2irxfaeps.html

[L02] 发送 POST JSON
来源：http://dali.316326.xyz/Article/details/gt2yvnbuplm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gt2sjhuksdx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.quarkkingdee.top/Article/details/gt2lvbiqkar.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gt2ewyhqasi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gt2ymmohxeo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.c1oappe.top/Article/details/gt2ldfrjjps.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gt2dgfwuhoi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxuanxn.top/Article/details/gt2zhnxcbmu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfarwehx.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gt2wlxydiin.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gt2xiiiutup.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ydzc1.top/Article/details/gt2kjanmbjb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gt2zkbwyjft.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gt2awfdtcch.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jiagoushi.top/Article/details/gt2ixmcrncv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gt2awhqvcrq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj202588.top/Article/details/gt2fzfgxztw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gt2itzsmwze.html

[L04] 设置超时
来源：http://dali.sxryk.cn/Article/details/gt2ytrshrba.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuanzhike.top/Article/details/gt2lasjtpyo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gt2zbjpnaph.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gt2wrghgbzx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gt2pwpelttl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cdnleiting.top/Article/details/gt2kavynzec.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yangfankeji.com/Article/details/gt2wthhlnud.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yonumen.top/Article/details/gt2wzmbxkin.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gt2tofctiue.html

[L05] 上传文件（multipart）
来源：http://dali.wangshuangyany.cn/Article/details/gt2zuezzmiq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgufenzy.top/Article/details/gt2ucvvemnw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gt2lhnqxgva.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gt2sxorhamk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gt2algdvehm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jianghu66.top/Article/details/gt2vwykdbpy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gaohongyu789.top/Article/details/gt2xbrcjfcv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.bjfxy.top/Article/details/gt2mpzkxjkg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2itrplxem.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2msfdnqfu.html

Py:   resp.json()
来源：http://dali.chenzaomai.com/Article/details/gt2qjzzcqig.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gt2bzctsfrx.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2ivyuedde.html

TS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gt2zniurjzt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2doolmlxu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cheryme.top/Article/details/gt2pgmyvdiw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shuidangran.top/Article/details/gt2lovwrbki.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daria6918.cn/Article/details/gt2jmnywbjl.html

[L07] 处理 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gt2bhgaalbh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.bjfxy.top/Article/details/gt2qleqdegk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgufenzy.top/Article/details/gt2jllmjmfc.html

JS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gt2icxsxgja.html

TS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gt2pafnqywi.html

Java: resp.statusCode()
来源：http://dali.jqgufenzy.top/Article/details/gt2yxpkmsrh.html

Go:   resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gt2rxzphdgb.html

Ruby: resp.code.to_i
来源：http://dali.jiagoushi.top/Article/details/gt2enyllxeo.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gt2oeoxyuii.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gt2emguizqd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yangfankeji.com/Article/details/gt2wxdwgxaf.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgfzy.top/Article/details/gt2ktedozbh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gt2hawvwlmu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2byatgecp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj202588.top/Article/details/gt2gdlbwhjs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ydzc1.top/Article/details/gt2rpllvmgq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yueranfly.top/Article/details/gt2dcdxtrge.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhoulong.xyz/Article/details/gt2qbkngrrd.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2pofvfgtj.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258.top/Article/details/gt2zxuubuoj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2hmilsocp.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gt2exndrrlx.html

Py:   sys.argv[1:]
来源：http://dali.cashguo.top/Article/details/gt2kzunggxp.html

PHP:  $argv;  $argc;
来源：http://dali.jqgfzy.top/Article/details/gt2isnuhprb.html

JS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gt2cdbraopa.html

TS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gt2zoymlvjy.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gt2apyvyrdg.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fpftpllq.html


<!-- 参考信息 -->