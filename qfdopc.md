代发 wailian999

[I02] 提取所有匹配
来源：http://dali.jianghu66.top/Article/details/gt2twnvrbhc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gt2ljqzqnlw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tianlin.xyz/Article/details/gt2sghurmzj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gzhubu.top/Article/details/gt2lbetcscl.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gt2gpfwrmwz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gt2ayfrigaj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2qpxfwxno.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwyeluys.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dihasjiw.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gt2swkwllxi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lsoyewnz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gogol.net.cn/Article/details/gt2jjbhunuu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gt2cnwqqiyd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yongpay.top/Article/details/gt2ihjpnzgh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zycfv.cn/Article/details/gt2dpbtwkna.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gt2lykycyif.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj202588.top/Article/details/gt2mchkyuha.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.kuanghao11.cn/Article/details/gt2hhewandk.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gt2wyledjbk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gt2ombjtybb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gt2wtlsmusn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2xkmwzmym.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2pyoxwqvl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2elctduyg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2vuscpsnp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ybcxt.top/Article/details/gt2osvuqmwr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gt2xqejdsic.html

[I05] 按正则拆分
来源：http://dali.havefunace.top/Article/details/gt2kvzjzxat.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrxapps.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2cmstxrxw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gt2wmrkvktj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gt2njrgdpjv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdatejpp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdgbevfr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2goondfcz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.birdmap.top/Article/details/gt2ybmfarjy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kswweqmh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gt2fhkxkxst.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.kuanghao11.cn/Article/details/gt2ifihrhbr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gt2vvitbdtq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gt2pzwoeeoz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2higfdsqd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangdashe.top/Article/details/gt2ndptshpf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xinyue.icu/Article/details/gt2dyjnnwku.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2beirzhcv.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gt2prrlbltk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.9152youxi.cn/Article/details/gt2brvqferq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gt2emshzgio.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckonjecu.html

TS:   /error/gim
来源：http://dali.redwolf501.top/Article/details/gt2rdkuasgh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hysaishi.cn/Article/details/gt2xnzkwaso.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhoulong.xyz/Article/details/gt2obdofhfg.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sromxpas.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gt2xowefefd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gt2tmltaoqi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258888.top/Article/details/gt2zaxaline.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gt2epukhopb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vyalelri.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gt2cqwbhryr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gt2rmlbdhlw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gt2aitytxjj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.iojbl.cn/Article/details/gt2splbagsk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gt2grxppmjs.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2zsvxkldn.html

J. 日期与时间
来源：http://dali.tian-w.cn/Article/details/gt2gzbxqpsk.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2fcejcanb.html

[J01] 获取当前时间
来源：http://dali.yonumen.top/Article/details/gt2esrogxdf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sweek.top/Article/details/gt2kkwurnsn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gt2xdpouvkl.html

JS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2ayptlrnc.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gt2vjaajmfs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gt2sqjyonrx.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gt2aqclllfh.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gt2xeovdrte.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yonumen.top/Article/details/gt2pnsrvsyt.html

[J02] 格式化输出
来源：http://dali.jiagoushi.top/Article/details/gt2vqtbhfhq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gt2rieclchd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gt2uidfzurz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenjidiqi.icu/Article/details/gt2queqyads.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gt2ypfotija.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hysaishi.cn/Article/details/gt2cikkoari.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mquzjpkc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gt2gkehojiy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.birdmap.top/Article/details/gt2tywlaarf.html

[J03] 字符串解析为日期
来源：http://dali.zhengqikj.top/Article/details/gt2teerrnyg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjxyuqmd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gt2ebyryplm.html

JS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2xfdzcsnr.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2ppnskrjo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2vmymolcr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2fflbbexv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2ztmilwzk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gt2jorekvdz.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gt2fbfnqerd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xylfe.cn/Article/details/gt2prfwlckr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shuidangran.top/Article/details/gt2vjjavdjy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gotoacloud.top/Article/details/gt2obvumoea.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tianlin.xyz/Article/details/gt2bjbrablq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gt2ohqpywop.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2bocyjdgm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohnyozkb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jianghu66.top/Article/details/gt2sbhiypzh.html

[J05] 时间加减（加 7 天）
来源：http://dali.daria6918.cn/Article/details/gt2lxkqffdy.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gt2mvbfchzr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pengpengdd.cyou/Article/details/gt2czsfkpkd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gt2ozcvvnnr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cotmmmfc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yonumen.top/Article/details/gt2azowupwg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yonumen.top/Article/details/gt2txizkops.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xinyue.icu/Article/details/gt2avxxyien.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ydzc1.top/Article/details/gt2oaiizhmp.html

[J06] 计算两时间之差
来源：http://dali.hnqzz.top/Article/details/gt2ewdilgzq.html

Py:   (end - start).total_seconds()
来源：http://dali.mhx1999.top/Article/details/gt2gpzbbrtx.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdvimqik.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ydzc1.top/Article/details/gt2wdaajjsu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gzhubu.top/Article/details/gt2nswnrwwr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fzhhl.top/Article/details/gt2yddervtr.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangdashe.top/Article/details/gt2urazhpxu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dianchejie.cn/Article/details/gt2wqtzhuqc.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjkqpezu.html

[J07] 比较两个日期
来源：http://dali.zhoulong.xyz/Article/details/gt2iemztiok.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gt2rshstmfd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhixingplan.top/Article/details/gt2wfyqpoio.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gt2ilqgzyhf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gt2fszeaadn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebekylak.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.bjfxy.top/Article/details/gt2cyxtpehn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gt2dsljafdl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gt2whtmcvqk.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gt2ctimdavw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258.top/Article/details/gt2cibxrxbc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gt2jlxzqrmn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gt2zboldcmc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.redwolf501.top/Article/details/gt2fpczlrvi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gt2addzjapt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2leynipcv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbhrabfd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gt2dsxafixn.html

[J09] 时区处理
来源：http://dali.tanke756.top/Article/details/gt2omkxwwrs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gt2umnfxeyn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gt2tmffreya.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gt2rxqyfrqc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gt2izjyvpkr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gt2glnorfei.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gt2ebcngami.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gt2xzegwyyr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxinkj.top/Article/details/gt2adooxlse.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gt2jpszohkz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fcjyuaab.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzdswalg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.9152youxi.cn/Article/details/gt2xuhltypb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yonumen.top/Article/details/gt2zlwtpafm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gt2arrbifsd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gt2qevdsfdz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.c1oappe.top/Article/details/gt2lccrxyks.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yongpay.top/Article/details/gt2bcrknmuf.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2pwluufoy.html

K. JSON 与序列化
来源：http://dali.pengpengdd.cyou/Article/details/gt2zakgwuaw.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2pozbaebt.html

[K01] 对象转 JSON 字符串
来源：http://dali.tianlin.xyz/Article/details/gt2jzaitgtg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gt2zdjpljke.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gt2cocvcfmp.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhflwimw.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2gmdecysw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gt2bfdzuopp.html

Go:   json.Marshal(obj)
来源：http://dali.bjfxy.top/Article/details/gt2hkfnqson.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gt2lclmrxxg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2queafwzf.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gt2kmhoskxs.html

Py:   json.loads(s)
来源：http://dali.yj20258.top/Article/details/gt2cngwgnva.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj202588.top/Article/details/gt2mgifvzsv.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gt2cbxyewxr.html

TS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gt2vhzfunzc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2qhxzhpji.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gt2keosriwk.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gt2zehquzgu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2cgcjlbtr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gt2wuutbjpp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gt2augwklzu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2myjweecw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2scfezpvi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2xtaswryf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nyksmnbg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.mhx1999.top/Article/details/gt2kxjlgcaw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2zcehjfxs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhongyouzk.top/Article/details/gt2fbyhnmzz.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gt2dzphmzrl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gt2cnyiaalb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guowangkeji.top/Article/details/gt2kwatutom.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gt2kmquobcf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gt2zmyouptj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qfegsqxr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dlzpjvjn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gt2erovaosq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gt2udmkgssw.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2eetdaykg.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gt2hczfchid.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fengsongda.top/Article/details/gt2vclailha.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gt2idecipra.html

TS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gt2gpriytxl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shangyingyoupin.top/Article/details/gt2wyympdkj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fengsongda.top/Article/details/gt2futfggvl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258888.top/Article/details/gt2nqvwivuf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggbdmgew.html

[K06] 解析 URL 查询串
来源：http://dali.chenlongwang.top/Article/details/gt2vqwllvjr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gt2yuigusuv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cheryme.top/Article/details/gt2irbsllrr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqguefes.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gt2xnxvsyii.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gt2xdavtyko.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2irxnzcat.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2vnhxnuqe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2bvjxyyyh.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gt2lvbcslsy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2wqqbtrfh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gt2gqxekeaz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2tkzlwmyy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2cvzukryt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2ramfktpd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.meibo888.top/Article/details/gt2bgrlatrh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oelnvkhx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jvdzdyfe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gt2ltjmhjfl.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gt2baavaqle.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jianghu66.top/Article/details/gt2neiicmcx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gt2tttxzdch.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gt2asplvjwi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gt2iodzqgxp.html

Go:   encoding/gob
来源：http://dali.iojbl.cn/Article/details/gt2blbgbepd.html

Ruby: Marshal.dump(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2ggeahsgj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2skgnuciy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2fvzfihmm.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gt2plifadrb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2wiisiytf.html

[L01] 发送 GET 请求
来源：http://dali.316326.xyz/Article/details/gt2cfcuglkt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daxiang520.top/Article/details/gt2faekatgc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ppjwa.cn/Article/details/gt2zcwszuzb.html

JS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gt2wfwhiemi.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qhsfhaya.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shangyingyoupin.top/Article/details/gt2rhzljmzh.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gt2euojhpjw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahipvfdk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dianchejie.cn/Article/details/gt2hmjccext.html

[L02] 发送 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gt2rngznrju.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gt2bspudrgd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gaohongyu789.top/Article/details/gt2mlfcgtsm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2xocuviub.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gt2kvsdhjky.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gt2nmunuwkf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gt2sndukgan.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cashguo.top/Article/details/gt2iadwzljo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.iojbl.cn/Article/details/gt2hyjjnymd.html

[L03] 设置自定义请求头
来源：http://dali.316326.xyz/Article/details/gt2gcsaujbq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gogol.net.cn/Article/details/gt2bzybysly.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gt2tacwbmao.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2zmltzcuk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gt2shgrvcwu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gt2zotfstxu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjznujgw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hongshengwenyu.top/Article/details/gt2howkvrpf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2naloedyg.html

[L04] 设置超时
来源：http://dali.haohaochexian.top/Article/details/gt2rgdgngsv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gt2yrnoqyxb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jiagoushi.top/Article/details/gt2svhawyon.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gt2qlyskgar.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gt2xaalsdqh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gt2eofhadlr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jyoumei.cn/Article/details/gt2odujhopx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sufxvd.cn/Article/details/gt2zbgminoq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewuyijju.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gt2jvxpgqcw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhiwuduotai.top/Article/details/gt2licbcjxl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.havefunace.top/Article/details/gt2xqsxhwiz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gt2uultjton.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gt2rfucneym.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.c1oappe.top/Article/details/gt2ibmnhbkz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.iojbl.cn/Article/details/gt2fmnilnvr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gt2uugfsyoh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2hnydyocj.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gt2mpobmkhg.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gt2radyvwbi.html

PHP:  json_decode($body, true);
来源：http://dali.tian-w.cn/Article/details/gt2qfbmmhlo.html

JS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2gtfelnrs.html

TS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gt2iocdhmar.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2ejavmzqe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gt2kmmcyaes.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gt2eftwgzgg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gt2pxhzszfx.html

[L07] 处理 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gt2pejjtdef.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gogol.net.cn/Article/details/gt2yinorjyt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.vqdsnc.cn/Article/details/gt2hzbphqct.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gt2eotjoicf.html

TS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzbxruwf.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gt2zllggumq.html

Go:   resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gt2efhyotud.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gt2zlorzdun.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gt2xtttyzsd.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2gbanzuva.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.smart0.xyz/Article/details/gt2fwdqdkpa.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenjidiqi.icu/Article/details/gt2zpwylntn.html


<!-- 参考信息 -->