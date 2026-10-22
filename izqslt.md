代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2tykaljpp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gt2kajevrdi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tianlin.xyz/Article/details/gt2bcioouqi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtmrcreg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gt2hfrmhyhr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2llhbljym.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gt2jmrvgddi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ppjwa.cn/Article/details/gt2trxiythp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2zwwaqkrc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gt2cixjsxmg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gt2noiqsudw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gt2rdjizcri.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cashguo.top/Article/details/gt2btzyifch.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2zqjvofdc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gt2qdcyoutc.html

[I05] 按正则拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2qmpdqevz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gt2gffqnyyo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2njveontv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2mhvosejt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2gqdwtirb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gt2yqzyaesu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gt2kxldluqb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgsapft.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxinkj.top/Article/details/gt2uktooowe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhixingplan.top/Article/details/gt2rnmevyjo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2yyiydjbe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhongyouzk.top/Article/details/gt2rmygrdnu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gt2avtjxvth.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gt2vixevbdt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2nxxfmjug.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhengqikj.top/Article/details/gt2rwhergye.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xziqi.cn/Article/details/gt2qbagkdog.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gt2muozhpai.html

[I07] 忽略大小写与多行模式
来源：http://dali.zdqjudy.top/Article/details/gt2vkvzbmrp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenzaomai.com/Article/details/gt2blbeugiu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gt2jkfgefub.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.0kj1m.cn/Article/details/gt2xjhgegrc.html

TS:   /error/gim
来源：http://dali.nwbrower.top/Article/details/gt2nhavrxkq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shzxlz.cn/Article/details/gt2kwvkxnew.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aibaodan.cn/Article/details/gt2qstxnvfj.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxuanxn.top/Article/details/gt2qexkjmxo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gt2qpzvjhwn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.redwolf501.top/Article/details/gt2kutqewop.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jyoumei.cn/Article/details/gt2slcwbipo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pycfn.com/Article/details/gt2vluecgwv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ozqxdqim.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gt2azslsnhg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2ddtehmdm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hywenlv.cn/Article/details/gt2uimsmsjo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gt2tvalakve.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gt2ndpbhuwe.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ruuqcqdm.html

J. 日期与时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkxyhdgk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2salzsxtb.html

[J01] 获取当前时间
来源：http://dali.jqgufenzy.top/Article/details/gt2krizkqra.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hfpthk.cn/Article/details/gt2oflhlswu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gt2qwmxzicq.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gt2uurdfjlv.html

TS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gt2vmpkgyzy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gt2nntfzihn.html

Go:   time.Now()
来源：http://dali.yanxiufei.cn/Article/details/gt2btdlmnzz.html

Ruby: Time.now
来源：http://dali.hammf.cn/Article/details/gt2rqjjzsaw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.havefunace.top/Article/details/gt2smyadckc.html

[J02] 格式化输出
来源：http://dali.iojbl.cn/Article/details/gt2srojcgep.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gt2mwbjbwpg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gt2crncxdug.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gt2tgrdwlzc.html

TS:   d.toISOString()
来源：http://dali.yj20258.top/Article/details/gt2ihlkqnvz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnxiangtu.top/Article/details/gt2uzdrdinw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gt2oyupjijs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gt2ewcxsjuo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hysaishi.cn/Article/details/gt2uvxocyre.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gt2eyxaaxpm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gt2xqnvrcxr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.vqdsnc.cn/Article/details/gt2cjikaiyb.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2gqmhyxxk.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2ctnpwyuq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2ocufriof.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2kxviaakc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2tzcqrjty.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.mhx1999.top/Article/details/gt2didyispz.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gt2wpcnomwr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aldumdxs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xylfe.cn/Article/details/gt2rlozuaga.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.quarkkingdee.top/Article/details/gt2ztzmejjw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gpcgldvq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.vqdsnc.cn/Article/details/gt2wcfwezno.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2rxtflluu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guannengcc.top/Article/details/gt2afcfhtch.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2iayhxkkt.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gt2czlvkbfl.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gt2zcyupwze.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhiwuduotai.top/Article/details/gt2wahjavbx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gt2uubpvpfw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2aslpcrpa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2gidcnvjn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gt2jwwrdxka.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aizwys.cn/Article/details/gt2ntkcafuj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gt2ipsxsovt.html

[J06] 计算两时间之差
来源：http://dali.iojbl.cn/Article/details/gt2vfqudxdm.html

Py:   (end - start).total_seconds()
来源：http://dali.jianghu66.top/Article/details/gt2qlpsopet.html

PHP:  $end->diff($start)->days;
来源：http://dali.cashguo.top/Article/details/gt2zlkausws.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cashguo.top/Article/details/gt2arcvxvab.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgufenzy.top/Article/details/gt2jzjxgqaa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2utgjqbfh.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhixingplan.top/Article/details/gt2vfoekawv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258888.top/Article/details/gt2jmdmzhfr.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangdashe.top/Article/details/gt2kzrpmskb.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zcktyydo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gt2kbheolcc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258888.top/Article/details/gt2nzhqpsvo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gt2qyiqcpvy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pcazylvm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guowangkeji.top/Article/details/gt2qgqhkbhc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2bnlnsbfd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2attyfyys.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2dwtgcpad.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gt2ejizvmvv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xinyue.icu/Article/details/gt2stoqgvqg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gogol.net.cn/Article/details/gt2zgpobshs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.vqdsnc.cn/Article/details/gt2ubaoskdy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gt2dvznhlxa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gt2npevfzde.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gotoacloud.top/Article/details/gt2uygvafis.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrxmhvwo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txqgmvjw.html

[J09] 时区处理
来源：http://dali.hnqzz.top/Article/details/gt2qqefblci.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gt2wwgcnzqq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gt2vzuzevzu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gt2bjhybnzy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gt2exidyewf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.kuanghao11.cn/Article/details/gt2onvdhyhe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhixingplan.top/Article/details/gt2pkwbqbem.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gt2llbdvhug.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gt2qhaypwzm.html

[J10] 取今天 / 本月第一天
来源：http://dali.havefunace.top/Article/details/gt2znsocvry.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shzxlz.cn/Article/details/gt2mjtbimzj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gt2tkqvrtjw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2zhigftdg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gt2ihtckija.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2wqouckbt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gt2zmfaidne.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.meibo888.top/Article/details/gt2oaelhsga.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gt2uzyqspcm.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2fdhlrsal.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gt2qxbvqezn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2lkndcvrg.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2mogrdmso.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gt2xwpqvpun.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gt2uyuddjjz.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2zhjewrqh.html

TS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gt2mnyoyntc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjeiopwr.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2wgqeytdr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenlongwang.top/Article/details/gt2xknocthp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qfoucjkx.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrfnnktm.html

Py:   json.loads(s)
来源：http://dali.yvedp.cn/Article/details/gt2ycdfsdde.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.meibo888.top/Article/details/gt2lzbnxrpn.html

JS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gt2fmkfzyqa.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2bdegvljn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gt2qbyktrtw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2robdggbx.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2mwwtvfee.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gt2ojrhagnv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gt2woqbjsqt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gt2zhvfwldd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmzutmtf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gt2efyszklr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ifflrhof.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtkiqhsh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yanxiufei.cn/Article/details/gt2sqfesrit.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daria6918.cn/Article/details/gt2szmpxcmf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sxryk.cn/Article/details/gt2yxmqihtt.html

[K04] 读取 JSON 文件
来源：http://dali.ehwqpu.com/Article/details/gt2diubqijr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gt2dpevsrsb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.meibo888.top/Article/details/gt2jdxsmuyp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gt2rebsvoad.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gt2maqybnst.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.andypj.xyz/Article/details/gt2zovzzwdy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gt2suelxagt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tanke756.top/Article/details/gt2oxbhhasc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gt2ecrvxusm.html

[K05] 深拷贝对象
来源：http://dali.zhixingplan.top/Article/details/gt2vtganvtq.html

Py:   copy.deepcopy(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2ezvkpsuu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yanxiufei.cn/Article/details/gt2iuzcokbn.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2ydvhjazg.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2xvnqzuub.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gt2yeuxbrsz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.mhx1999.top/Article/details/gt2mdendfza.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gt2lgczkewu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gotoacloud.top/Article/details/gt2bkmbxyom.html

[K06] 解析 URL 查询串
来源：http://dali.ppjwa.cn/Article/details/gt2wutupqhr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2xyzoyrcx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jiagoushi.top/Article/details/gt2rulokpmi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gt2ushzbfee.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gt2dyybkzdm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gt2qaqydhac.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2ixcrojlj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gt2ostkquac.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gt2fulrscbt.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gt2gduakkne.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oiozstwg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zycfv.cn/Article/details/gt2cnkasrgb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbiizcbb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2kitqhgyq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2vdnxwdku.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tian-w.cn/Article/details/gt2iqiwjutm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gt2ylqcgdtg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2izhhntem.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigfzy.top/Article/details/gt2ycbwntpy.html

Py:   pickle.dumps(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2rqbulfen.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenzaomai.com/Article/details/gt2qfutoqqo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2vmdzsybq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gt2tzwdqhsx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gt2suvthecj.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gt2jtdqgnrf.html

Ruby: Marshal.dump(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rucgupao.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gt2qdxhorcx.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tipaexta.html

L. 网络请求
来源：http://dali.jlsjyb.cn/Article/details/gt2ckcciqlw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2nxazjura.html

[L01] 发送 GET 请求
来源：http://dali.hongshengwenyu.top/Article/details/gt2ysnpouvm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gt2tkerzcts.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigufen.top/Article/details/gt2xgleinvt.html

JS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gt2urprpkxc.html

TS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gt2bbnrmkfm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258.top/Article/details/gt2twjpfsqb.html

Go:   resp, err := http.Get(url)
来源：http://dali.hywenlv.cn/Article/details/gt2zgdwpowa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gt2kaemyxqf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.316326.xyz/Article/details/gt2zrmdocit.html

[L02] 发送 POST JSON
来源：http://dali.andypj.xyz/Article/details/gt2eedapsqu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cashguo.top/Article/details/gt2zfcgiucb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daria6918.cn/Article/details/gt2iylkhstx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gt2vfevuiry.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gt2opjuyttt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gt2txsdnusj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shzxlz.cn/Article/details/gt2psueloqj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrzdczeh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2frrpbhyq.html

[L03] 设置自定义请求头
来源：http://dali.nanxinkj.top/Article/details/gt2hacbplfb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxuanxn.top/Article/details/gt2tbcttktf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.svipenyu.cn/Article/details/gt2bwfudbnf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gt2tsmkuurj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gt2sbfaxssd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ehwqpu.com/Article/details/gt2zhxhnafh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2lthixzmj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangshuangyany.cn/Article/details/gt2gebnclbs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gt2rwrundso.html

[L04] 设置超时
来源：http://dali.ydzc1.top/Article/details/gt2dymoovyv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hfpthk.cn/Article/details/gt2xrvktvsn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zycfv.cn/Article/details/gt2xuwmhiyp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gt2cejvtgut.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2omazjesc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gt2pbqvzcxd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gogol.net.cn/Article/details/gt2riuzmbxe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gt2jszaqyhk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gt2eiandzkj.html

[L05] 上传文件（multipart）
来源：http://dali.nwbrower.top/Article/details/gt2pqxtjbla.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nwbrower.top/Article/details/gt2iivgyywt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gt2htlfezxn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gt2rinpxhzx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gt2oaevesoh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pycfn.com/Article/details/gt2szwlxplw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2klsqmmqj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ppjwa.cn/Article/details/gt2bukcaasj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2irqdakom.html

[L06] 解析响应为 JSON
来源：http://dali.vqdsnc.cn/Article/details/gt2iimcstku.html

Py:   resp.json()
来源：http://dali.hywenlv.cn/Article/details/gt2wcthfxfm.html

PHP:  json_decode($body, true);
来源：http://dali.chenzaomai.com/Article/details/gt2aftwnbxw.html

JS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gt2dryntqny.html

TS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gt2kaketsim.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2kujknrzw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nwbrower.top/Article/details/gt2topsbvdp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.9152youxi.cn/Article/details/gt2vqgbhikt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gogol.net.cn/Article/details/gt2pblivioj.html

[L07] 处理 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gt2peyxljac.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gt2danladpn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gt2xmjlehdu.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gt2bmudjekn.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gt2tunvnfcf.html

Java: resp.statusCode()
来源：http://dali.ppjwa.cn/Article/details/gt2xjdzkwdk.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gt2xybgqifh.html

Ruby: resp.code.to_i
来源：http://dali.xuanzx.com/Article/details/gt2dixapzhh.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gt2noutbqur.html

[L08] 并发请求多个地址
来源：http://dali.zycfv.cn/Article/details/gt2fgnfoftl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yvedp.cn/Article/details/gt2zmmugjer.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gt2qbgqedrv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2zzzjhzsf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gt2esmexhvx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gt2mbzsznhr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gt2kczuuvfh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gt2tjdpbxtg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gt2swznmeif.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2ztetqatb.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gt2wcsvsszp.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2gflzswiw.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gt2xbddxjty.html

Py:   sys.argv[1:]
来源：http://dali.pycfn.com/Article/details/gt2qxnkwdyl.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gt2jcmntqmp.html


<!-- 参考信息 -->