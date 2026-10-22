代发 wailian999

TS:   s.match(/\d+/g)
来源：http://dali.zdqjudy.top/Article/details/gt2ctgcpdyh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ybcxt.top/Article/details/gt2evqeeasm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yonumen.top/Article/details/gt2jsxexcps.html

Ruby: s.scan(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2iwnrzcxx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2donpofnu.html

[I03] 提取捕获分组
来源：http://dali.jyoumei.cn/Article/details/gt2ncqpyjro.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2nzkaboqi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ppjwa.cn/Article/details/gt2lrllxqvw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2iqgeyjbu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gt2mxsnaimt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gt2yquvqddy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jndkgbue.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhengqikj.top/Article/details/gt2cwdchkcm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gt2cfrshpiu.html

[I04] 正则替换
来源：http://dali.zhongyouzk.top/Article/details/gt2ejevtzpb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vswnlmqe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2oqeodhhu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2peyoksfp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2dggkgjlf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2scmhzhuw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cheryme.top/Article/details/gt2aeazhlev.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gt2rwgoljln.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gt2elotdnmd.html

[I05] 按正则拆分
来源：http://dali.shzxlz.cn/Article/details/gt2sszsncch.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hysaishi.cn/Article/details/gt2ewftieum.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2quomhbns.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gt2wqhahibs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gt2neupzowr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gt2hmjytsnb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guannengcc.top/Article/details/gt2jkuxsokx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2alhhbahl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gt2aseexfxd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gt2oobgbwii.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gt2aliqjezo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.meibo888.top/Article/details/gt2xubaltqv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gt2yrbrdzrz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gt2bnrizkhc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2tamjyhyg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.bjfxy.top/Article/details/gt2pjqgphsz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yanxiufei.cn/Article/details/gt2jbwsxffu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2ashpxvwe.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenlongwang.top/Article/details/gt2cjrgbzuz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akgxicyg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gt2dfbsmzdt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gt2dxvsdnmb.html

TS:   /error/gim
来源：http://dali.wangdashe.top/Article/details/gt2kaqogwqs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fengsongda.top/Article/details/gt2snkrclqo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gt2ynuqhzsz.html

Ruby: s.scan(/error/i)
来源：http://dali.yonumen.top/Article/details/gt2deunkpld.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hywenlv.cn/Article/details/gt2yptsjfvg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guannengcc.top/Article/details/gt2scvpnnxe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fzhhl.top/Article/details/gt2wmkyduyn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gt2xarirqwg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gt2fydswcqh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gt2cxuabbio.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gt2soviidli.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jianghu66.top/Article/details/gt2qwzxqycr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhengqikj.top/Article/details/gt2thaxsayd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gt2hhrdgvik.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ssudfanm.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gt2nwyxpnwx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2mawaphgs.html

[J01] 获取当前时间
来源：http://dali.cucudq.cn/Article/details/gt2pmjfngzm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cuygwscw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gt2rnlrlshn.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gt2aqmcodjj.html

TS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gt2mukwcwht.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2aahzoefn.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gt2bodvtudh.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gt2vexihubc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hysaishi.cn/Article/details/gt2kwvsjcjs.html

[J02] 格式化输出
来源：http://dali.ivvv.top/Article/details/gt2gdmepjfj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgldltxk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gt2eekebdsm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigufen.top/Article/details/gt2ldrpvpam.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gt2lwcuuybi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yvedp.cn/Article/details/gt2xjxxmkat.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xylfe.cn/Article/details/gt2brbrwzez.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gt2qleevxxp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gt2ksqkywxu.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gt2kywggyqy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hfpthk.cn/Article/details/gt2ogxdnkdv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hammf.cn/Article/details/gt2vazovmxz.html

JS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2vuzqzvik.html

TS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2dknaldhu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2jecgzvsh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yvjdwwnc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2edjbeuup.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gt2hteqwici.html

[J04] 时间戳与日期互转
来源：http://dali.aibaodan.cn/Article/details/gt2npadjwyn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gt2vvwxzula.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nwbrower.top/Article/details/gt2zztwhhmx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gt2hvpighga.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2dfpnsnqs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2puozjnis.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2pdudhxie.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258.top/Article/details/gt2brzrtibd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yvedp.cn/Article/details/gt2raxppwpt.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gt2cibyivsb.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gt2ynkxtuhg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhiwuduotai.top/Article/details/gt2daozumdp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfyqcnbi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gt2pqtkcfow.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jianghu66.top/Article/details/gt2rcupiyee.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gt2mkeedkqw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gt2weccuzxd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gt2bonprfng.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gt2lammvwea.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258.top/Article/details/gt2datuopwz.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhongyouzk.top/Article/details/gt2ddegecdu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnxiangtu.top/Article/details/gt2gxpymnzq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhengqikj.top/Article/details/gt2aersgqlm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.birdmap.top/Article/details/gt2tvwrqcxn.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenjidiqi.icu/Article/details/gt2cflsdphu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuanzhike.top/Article/details/gt2nmodcwyp.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gt2omdqqkka.html

[J07] 比较两个日期
来源：http://dali.gaohongyu789.top/Article/details/gt2jylwqyql.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2zfjwyuox.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgjlbumv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gt2dmqibvfa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gt2ukpsmcka.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shuidangran.top/Article/details/gt2amrgroqy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gt2tfclwper.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2rcsgbqwq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2rfpaajzx.html

[J08] 提取年月日与星期
来源：http://dali.gaohongyu789.top/Article/details/gt2azfcbfho.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gt2rhudzsdp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gt2xctdqtcs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.meibo888.top/Article/details/gt2mvtiddqv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gt2dceucekq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gt2htyddnly.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.snrcjt.cn/Article/details/gt2nmegkwlq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangshuangyany.cn/Article/details/gt2kthljktt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhongyouzk.top/Article/details/gt2ssivvagc.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gt2vjwurriv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujtmmkbg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.feifeiyinyue.top/Article/details/gt2neybsuex.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gt2mqdasoqk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gt2wlzvmeky.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jyoumei.cn/Article/details/gt2ipcbpfir.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dianchejie.cn/Article/details/gt2hazwdfvr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gt2yvqapodz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gt2qotvbyhm.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gt2xpnnxnok.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nyiyrpbv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258.top/Article/details/gt2sudacptv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oflcmioh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2nrqkpcvb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gt2ntodjgjp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gt2ubggzhft.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.kuanghao11.cn/Article/details/gt2eouzkudq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dzlhegjm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2khqtduum.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gt2krwnscmm.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2kicssqnh.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gt2qgjrvidr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gt2ggqtidfz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2xlgbxjkk.html

JS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gt2yerxihik.html

TS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2drwvedvx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.vqdsnc.cn/Article/details/gt2yuvuliok.html

Go:   json.Marshal(obj)
来源：http://dali.mhx1999.top/Article/details/gt2xcwyizbf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dianchejie.cn/Article/details/gt2cjotwfvr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2sexolybg.html

[K02] JSON 字符串转对象
来源：http://dali.nanxinkj.top/Article/details/gt2lozrrzdc.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gt2jytfudmt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2xfekrbxm.html

JS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gt2amkwsxle.html

TS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2csutcppz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gt2fzzkiixx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gt2mefbkuqv.html

Ruby: JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2xnolhyxr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cheryme.top/Article/details/gt2entkoklf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tanke756.top/Article/details/gt2pnpqzeww.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gt2etaryuez.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2tbhiqckt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2wauzgvju.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gt2hsnrcfyf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gt2ppovyicn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xinyue.icu/Article/details/gt2swswqmym.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fengsongda.top/Article/details/gt2ayjhckqt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258.top/Article/details/gt2hfwqgqfi.html

[K04] 读取 JSON 文件
来源：http://dali.aibaodan.cn/Article/details/gt2wldoxgsv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dashuyun.cn/Article/details/gt2ywmnftvi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnqzz.top/Article/details/gt2dkatbibz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gt2kmokchps.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gt2cfusdjxs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gt2rwyqiuxm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrbmxlbi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tian-w.cn/Article/details/gt2oirpseju.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuxming.cn/Article/details/gt2uauoakls.html

[K05] 深拷贝对象
来源：http://dali.xylfe.cn/Article/details/gt2gddeiimj.html

Py:   copy.deepcopy(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2wleusjmb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gt2dcvjdkpv.html

JS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gt2ixrplvsq.html

TS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twiuqqtl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gt2bkihibit.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gt2lkeukdre.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ydzc1.top/Article/details/gt2wphpwjxh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hywenlv.cn/Article/details/gt2ehbdddbm.html

[K06] 解析 URL 查询串
来源：http://dali.shangyingyoupin.top/Article/details/gt2fxwoprmk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.birdmap.top/Article/details/gt2svwrcput.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gt2apweqkhb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gt2xpxrjgtg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gt2hzlrutwc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gt2huiygxxx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2lvwyzqts.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2cfwrsacr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gt2hnfcwqjo.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlrhctrx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2znabfqdi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhixingplan.top/Article/details/gt2aomawtyw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2rizulmlo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2qonprsjd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpbwkeaa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iixudvme.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gt2jxlteznr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2mqxemreu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gt2lxwqwppa.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gt2cfpzdwaz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gcjewwcf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gt2tndelsxc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2tpziflsp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuetiantiany.cn/Article/details/gt2aluqkfzw.html

Go:   encoding/gob
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxxkyojt.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gt2utvayjae.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gt2hmavivag.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2baubbrln.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gt2ywdjkidk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2sflqllls.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gt2nwvgwpql.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gzhubu.top/Article/details/gt2hjrleymy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gt2elyonuoy.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wuhridlq.html

TS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gt2oqixsgdp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gt2jsymxlfy.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2chjclfun.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txzmgvcz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gt2yuvpvjlq.html

[L02] 发送 POST JSON
来源：http://dali.yongpay.top/Article/details/gt2nvagggma.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gt2tafhkdre.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dianchejie.cn/Article/details/gt2kvqjfctl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gt2lywgtnkp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gt2zrfqocmf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gt2mnylocdt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.0kj1m.cn/Article/details/gt2qlfvqmxw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rkaudaqs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2bnqteezr.html

[L03] 设置自定义请求头
来源：http://dali.hnxiangtu.top/Article/details/gt2vpikzkrv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.meibo888.top/Article/details/gt2dymikgmb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gt2zqyzjrjv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gt2slmoagms.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gt2nlamosik.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jyoumei.cn/Article/details/gt2pyrjefye.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2awwrpvnz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ybcxt.top/Article/details/gt2zxczfygc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gt2fypfushx.html

[L04] 设置超时
来源：http://dali.kuanghao11.cn/Article/details/gt2kgypyzkd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xziqi.cn/Article/details/gt2gjncgxoq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.c1oappe.top/Article/details/gt2kaeyxqwm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2nuqbaprx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gt2gnqainra.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuanzx.com/Article/details/gt2fecelzxb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sweek.top/Article/details/gt2ftvjlnwx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gt2rtnkxubc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hammf.cn/Article/details/gt2hxcdpnra.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigufen.top/Article/details/gt2ynaimqtf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gt2rgjklqja.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.havefunace.top/Article/details/gt2yeeevulc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gt2hnziwawr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gt2gdrkugdl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gt2xidugtxf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yvedp.cn/Article/details/gt2tbvmutez.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.feifeiyinyue.top/Article/details/gt2ztnxpsfk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2lycyqiix.html

[L06] 解析响应为 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mwskfgqw.html

Py:   resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2emxrnzlj.html

PHP:  json_decode($body, true);
来源：http://dali.yuxming.cn/Article/details/gt2dybbsuka.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gt2rchccame.html

TS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gt2curnqdbr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gt2brfxfwdl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gt2oimlvemm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gt2mmwtwsas.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypciszuo.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdokpxbp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gt2ylgqbrzq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yueranfly.top/Article/details/gt2cktayqpz.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2bnzplgae.html

TS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gt2dqrtncml.html

Java: resp.statusCode()
来源：http://dali.yuanzhike.top/Article/details/gt2ngwbgopl.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gt2ntmxoday.html

Ruby: resp.code.to_i
来源：http://dali.sweek.top/Article/details/gt2rpgbxtos.html

C#:   (int)resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gt2pqeshzfv.html

[L08] 并发请求多个地址
来源：http://dali.sufxvd.cn/Article/details/gt2ntubtrtx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xylfe.cn/Article/details/gt2fxcyvryc.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gt2glhhsoxz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gt2rxfqxeyb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gt2oicwkgpj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwlxshud.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzmwzbhh.html


<!-- 参考信息 -->