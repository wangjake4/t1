代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2hhpntlac.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gt2kdivjxcm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gt2fpylzunt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gt2feyzjlck.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2gukzrfzg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zycfv.cn/Article/details/gt2kanhzbxx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gt2bnnbonqb.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gt2ajvokrmj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.9152youxi.cn/Article/details/gt2jbhfhlmo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2acmhiqrg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gt2clzwbhzz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2zvbnusak.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gt2tmqubyqx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gt2dyewgdrc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2noniggyc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gt2sjkrqfjq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yueranfly.top/Article/details/gt2mkgpecod.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gt2oowejzcu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjxsuabm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gt2wrfksidl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gt2qwxlncmg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2tyjiilci.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sysykeji.top/Article/details/gt2ntfanylr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cqqwz.cn/Article/details/gt2xflpbwtu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gt2nrahrmlm.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gt2uezlqedx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sxryk.cn/Article/details/gt2ghxahdwp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gt2rxhygdfp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sweek.top/Article/details/gt2dwagudpi.html

TS:   /error/gim
来源：http://dali.c1oappe.top/Article/details/gt2adkkqcne.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aibaodan.cn/Article/details/gt2nanpituo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xylfe.cn/Article/details/gt2wugaoola.html

Ruby: s.scan(/error/i)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fggojpro.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuanzx.com/Article/details/gt2wfefignp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.haohaochexian.top/Article/details/gt2rikgwlbg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tian-w.cn/Article/details/gt2pwshnqdt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gt2ywawmclq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gt2cevhhtgq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gt2wbtfatjr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gt2iulldcnc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gt2hhexujjo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gt2ftduocxa.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gt2agykviiq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2wscaaeih.html

J. 日期与时间
来源：http://dali.shuidangran.top/Article/details/gt2plpeajcw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2gyzqpoqe.html

[J01] 获取当前时间
来源：http://dali.dianchejie.cn/Article/details/gt2jmwypbhk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shuidangran.top/Article/details/gt2ryllqjqp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gt2ujfrbknr.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxitjwid.html

TS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gt2mfofsnou.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.svipenyu.cn/Article/details/gt2pugwuqnb.html

Go:   time.Now()
来源：http://dali.yj20258888.top/Article/details/gt2aadwufwi.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gt2teslslte.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgmlmmdn.html

[J02] 格式化输出
来源：http://dali.xuanzx.com/Article/details/gt2jzvssdxe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gt2ceukbdsc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gt2yslicyss.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daxiang520.top/Article/details/gt2mydsutbh.html

TS:   d.toISOString()
来源：http://dali.chenzaomai.com/Article/details/gt2lhuuzjlb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.kuanghao11.cn/Article/details/gt2tuhtmrjx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gt2bsoscgus.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gt2beaxtawu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtpbzng.html

[J03] 字符串解析为日期
来源：http://dali.shzxlz.cn/Article/details/gt2ytujbwpn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj202588.top/Article/details/gt2rllibkoa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tian-w.cn/Article/details/gt2dudmxtik.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyofqrna.html

TS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2ptndbrpp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2fdnjdsdq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2pythrihm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2ppfgpttw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2paccpndi.html

[J04] 时间戳与日期互转
来源：http://dali.havefunace.top/Article/details/gt2sylbfpxo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gt2gnwylnxc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.kuanghao11.cn/Article/details/gt2gsacjyoo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgufenzy.top/Article/details/gt2khsrmwws.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dqudyzxr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2dunjzwch.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gt2qiytleqf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gt2urvqgctg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2glsezvft.html

[J05] 时间加减（加 7 天）
来源：http://dali.dashuyun.cn/Article/details/gt2zzdbalxg.html

Py:   now + timedelta(days=7)
来源：http://dali.fengsongda.top/Article/details/gt2lcoalfam.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jyoumei.cn/Article/details/gt2qwboxfzg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gt2kruvviaw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gt2ebhwlpxe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gt2iatjndoy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gt2kzntlmvo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258888.top/Article/details/gt2toamshzy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gt2hqwrzykg.html

[J06] 计算两时间之差
来源：http://dali.hnqzz.top/Article/details/gt2jluagqza.html

Py:   (end - start).total_seconds()
来源：http://dali.yonumen.top/Article/details/gt2abqhyoit.html

PHP:  $end->diff($start)->days;
来源：http://dali.hysaishi.cn/Article/details/gt2lqcnbwwl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gt2tdbrnxye.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zdqjudy.top/Article/details/gt2ojtgvkpb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.meibo888.top/Article/details/gt2egyltqcm.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gt2qdnsmtvf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tianlin.xyz/Article/details/gt2jzwhlcwq.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kakpzzbk.html

[J07] 比较两个日期
来源：http://dali.snrcjt.cn/Article/details/gt2yjhfheel.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2qaqszobi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yanxiufei.cn/Article/details/gt2oouxrvlu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gt2mfrekzvl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gt2vhaqgawn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wjxndcmb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jyoumei.cn/Article/details/gt2gesdcmyd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2jfqulfzm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gt2keffccrb.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gt2fqqrgwwt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgufenzy.top/Article/details/gt2jkdbgikh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gt2owzyccem.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gt2omyamety.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gt2snscdunu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.smart0.xyz/Article/details/gt2uyydyoyk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gt2vbxmowjk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yonumen.top/Article/details/gt2hxhlcimr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shuidangran.top/Article/details/gt2gayuqnpz.html

[J09] 时区处理
来源：http://dali.nanxuanxn.top/Article/details/gt2klhaolfk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sweek.top/Article/details/gt2bfuqpfoe.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhixingplan.top/Article/details/gt2htdcgivk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gt2aumdzlzb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gt2vmwwxyqm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hammf.cn/Article/details/gt2qgqhlwkj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qttbuzik.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhoulong.xyz/Article/details/gt2ouufmogq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gt2uvdhewyh.html

[J10] 取今天 / 本月第一天
来源：http://dali.hywenlv.cn/Article/details/gt2sviwskix.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gt2idcojdyr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gt2zvoapvry.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2iyduofsn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangdashe.top/Article/details/gt2ndzgwrof.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gt2zqgieptd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.svipenyu.cn/Article/details/gt2gcnibypt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cqqwz.cn/Article/details/gt2iiffmuio.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shuidangran.top/Article/details/gt2vuobgbao.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2jmavilgb.html

K. JSON 与序列化
来源：http://dali.xziqi.cn/Article/details/gt2oasabwqh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2iiybvowr.html

[K01] 对象转 JSON 字符串
来源：http://dali.haohaochexian.top/Article/details/gt2otqsqfdy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gt2kbakjrof.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gt2ykxibuih.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eioxtkjb.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2kekxknev.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iqatsocx.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2ictgacek.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gt2oohfcevk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.bjfxy.top/Article/details/gt2vvyvnlkj.html

[K02] JSON 字符串转对象
来源：http://dali.chenzaomai.com/Article/details/gt2dbqxtwhd.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gt2jpmbokts.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gt2ipaybtcl.html

JS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2zywrosux.html

TS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2bewcyrvp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigufen.top/Article/details/gt2lxjolcoj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gt2nqnteeoq.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxmiybzb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbkpskzo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fvgjlsqu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gt2rggvgbmz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2crwcgzgw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hfpgbtet.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2dlsydhyg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cgxuwduz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gt2zcvkchon.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jianghu66.top/Article/details/gt2isjnmnjo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ehwqpu.com/Article/details/gt2qiqnhivy.html

[K04] 读取 JSON 文件
来源：http://dali.nanxinkj.top/Article/details/gt2knxfcgex.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iokkxozs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.andypj.xyz/Article/details/gt2hyiiiadt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2akroxrtd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gt2xqblgoab.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2qvnvlfsq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2ucuobzyj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gt2usemrkbs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gt2rhoakoxr.html

[K05] 深拷贝对象
来源：http://dali.gotoacloud.top/Article/details/gt2qwozeijt.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gt2fhzgphys.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gt2rvkomzdi.html

JS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2uljwndwx.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dvfxvfad.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shuidangran.top/Article/details/gt2tizdmhvv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.redwolf501.top/Article/details/gt2cjhtjeqc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ybcxt.top/Article/details/gt2cbplceov.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gt2qccexdiu.html

[K06] 解析 URL 查询串
来源：http://dali.wangshuangyany.cn/Article/details/gt2pgupcxrn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gt2zdieidtj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gt2xpsshrqv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2xnqwvkgd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gt2penzsrfy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gt2lrxlfwgw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2jegyqbeq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gt2yjfeqjqt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gt2vqdqtgnj.html

[K07] 进制转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2fvdbwmrt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2xpnbvswt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenzaomai.com/Article/details/gt2ybxtakue.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdajrvlg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2szwfdrwn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2uczceyia.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gt2geppdbxm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gt2fsoyvoih.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2xenjvxru.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gt2bzueicfg.html

Py:   pickle.dumps(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2aykyviue.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guowangkeji.top/Article/details/gt2beshuish.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2omadkhmn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2cuiejvoz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gt2kqtchdwf.html

Go:   encoding/gob
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khrsbqfk.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gt2oqtbeoom.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gt2phspnlbn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2xmjmtbhi.html

L. 网络请求
来源：http://dali.sweek.top/Article/details/gt2psrharst.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ggqsyokj.html

[L01] 发送 GET 请求
来源：http://dali.zhixingplan.top/Article/details/gt2ngjrbnuy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shuidangran.top/Article/details/gt2hutymfbm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gt2dbfgwuof.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2osabwtlj.html

TS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2ziyicloc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tanke756.top/Article/details/gt2vyexrcyo.html

Go:   resp, err := http.Get(url)
来源：http://dali.hywenlv.cn/Article/details/gt2hrpgibuz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hxeoctiu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzhbfcpl.html

[L02] 发送 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gt2ltbejpte.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gt2uqqjudcn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tianlin.xyz/Article/details/gt2johceczs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkvfrpac.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gt2kwtspsvz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.redwolf501.top/Article/details/gt2vklcpddo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pengpengdd.cyou/Article/details/gt2orulixcu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gotoacloud.top/Article/details/gt2irbkzeaf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hysaishi.cn/Article/details/gt2nbnilkwj.html

[L03] 设置自定义请求头
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egbkvtak.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ppjwa.cn/Article/details/gt2gsvdyqdt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drhynqwb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gt2eenzmmis.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gt2wrzntsjl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jyoumei.cn/Article/details/gt2uoiikhdk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2owchfyqk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigufen.top/Article/details/gt2brylyzao.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gt2pughiyrs.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gt2nreivtpx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gt2kdaesjwz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gotoacloud.top/Article/details/gt2chpzvblh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gt2rbkxhtrq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gt2eocubyrz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2xwkyopsr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tian-w.cn/Article/details/gt2pfhzfxio.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gt2qcckfzbp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tianlin.xyz/Article/details/gt2tqseuvlm.html

[L05] 上传文件（multipart）
来源：http://dali.mhx1999.top/Article/details/gt2ajrrxejf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aizwys.cn/Article/details/gt2wknotwxa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gt2sdoqauoj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gt2jjbwfkdg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gt2wzpdlywt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.feifeiyinyue.top/Article/details/gt2nsozriub.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gt2nmvaafmm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gt2zwivzzcp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gt2cvpfkojh.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gt2mzfokipc.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gt2scjghcpo.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gt2bvlxdtlo.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2wqjsolyv.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2uqvhlwza.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gt2zftkevxb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.birdmap.top/Article/details/gt2tsujsbcd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gt2ecqzmfpy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jiagoushi.top/Article/details/gt2ndtzmust.html

[L07] 处理 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gt2qswmjqaf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hfpthk.cn/Article/details/gt2jnbddqqy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jyoumei.cn/Article/details/gt2aoyuooal.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gt2rqcknnms.html

TS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gt2jamjlkpc.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gt2msuqbslv.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gt2jviexszh.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gt2vgkhuyyn.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gt2pfpwjemr.html

[L08] 并发请求多个地址
来源：http://dali.sufxvd.cn/Article/details/gt2txjygjzg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.bjfxy.top/Article/details/gt2lnfygkjt.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gt2lvijrdcr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2ltyakrul.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gt2mzmwsjpu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhixingplan.top/Article/details/gt2yhcmirdj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gt2hwrbbuuq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuanzhike.top/Article/details/gt2aloyglcv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2csjnttbm.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2rfrowwso.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gt2wulzbfsc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2bzywcttf.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gt2dsvodbgh.html

Py:   sys.argv[1:]
来源：http://dali.zhengqikj.top/Article/details/gt2nvqzacgt.html

PHP:  $argv;  $argc;
来源：http://dali.dianchejie.cn/Article/details/gt2mzvwtpsn.html

JS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gt2avprdrpg.html

TS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2auiipido.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gt2jnsgbdif.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2diudpkwz.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gt2pvzhwjsl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkjxxuwa.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffclaggw.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2vjssnlkg.html


<!-- 参考信息 -->