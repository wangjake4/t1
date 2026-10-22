代发 wailian999

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xejldhui.html

[I03] 提取捕获分组
来源：http://dali.dianchejie.cn/Article/details/gt2nfwlfsxk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dashuyun.cn/Article/details/gt2sjqjuohb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xylfe.cn/Article/details/gt2hgenskzt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gt2mwjzakzv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fengsongda.top/Article/details/gt2kpdapqbl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yvedp.cn/Article/details/gt2bonqhtlk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pycfn.com/Article/details/gt2pprxgcmb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jplqwaew.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gt2cnfkmzhl.html

[I04] 正则替换
来源：http://dali.chenlongwang.top/Article/details/gt2agskesrm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gogol.net.cn/Article/details/gt2zitfmcnu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2ppgofdmc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gt2quojdtfy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2ssvkzoca.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gt2bkrlmebb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gt2ikyriego.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2pxnisksp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gt2dzqlnwwc.html

[I05] 按正则拆分
来源：http://dali.wangdashe.top/Article/details/gt2katipnrw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cashguo.top/Article/details/gt2mnossaee.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2ongwmkzv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2hujrtlnh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2jrgoquaf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gt2zisflbjf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gt2hcamqozw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2depfxblv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.0kj1m.cn/Article/details/gt2ijylqakn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhixingplan.top/Article/details/gt2yumqmolw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2qecbbgdp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yueranfly.top/Article/details/gt2rshfnuzs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gt2dggyejti.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gt2lysaiooq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gt2sfnwvwdr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgfzy.top/Article/details/gt2nacwyjtn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fengsongda.top/Article/details/gt2jkowxmqz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ojniqphp.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wtnijplo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigufen.top/Article/details/gt2pjetjmyc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kzpxblul.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gt2kuhyersx.html

TS:   /error/gim
来源：http://dali.pengpengdd.cyou/Article/details/gt2achznwbt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guannengcc.top/Article/details/gt2nczwbcoh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tian-w.cn/Article/details/gt2qtufrxpe.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gt2qozoflna.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gt2gfpyuboz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gt2ebgvritn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuanzhike.top/Article/details/gt2csldaxfs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gt2qfnfgqqx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gyibjvrh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gt2zfpezonp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gt2xbevjxau.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gt2npzeksuk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tian-w.cn/Article/details/gt2pwrlvmku.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2jghmbrrg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpueugso.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gt2mjqndubw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ckzeumzh.html

[J01] 获取当前时间
来源：http://dali.havefunace.top/Article/details/gt2uoebngvu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sweek.top/Article/details/gt2siovsdrg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gt2gafjagql.html

JS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2eqyqsluq.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gt2ttqofeno.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hywenlv.cn/Article/details/gt2txztgwju.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gt2xbamvxux.html

Ruby: Time.now
来源：http://dali.svipenyu.cn/Article/details/gt2ixfihgoz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258888.top/Article/details/gt2kajlpnoy.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqfgeot.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ankyychb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gt2btyprhhn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenzaomai.com/Article/details/gt2nrkmrooh.html

TS:   d.toISOString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2saoofjoj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jianghu66.top/Article/details/gt2lchvilzz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcizxqj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gt2zlcjrzca.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yanxiufei.cn/Article/details/gt2latyktpg.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gt2zvygdkdc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fzhhl.top/Article/details/gt2ttwywakz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cqqwz.cn/Article/details/gt2bsztiqgk.html

JS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewbzerub.html

TS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2llzvnpye.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2hwwhqqfk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2wlsudxhm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2jmoefgcn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gt2lzoywwpy.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gt2bgopcnpi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lqonrjsg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gt2mmcogjvt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gt2rckkfgml.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gt2ryvdhbza.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gt2rdqqrcas.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gt2vzquaykx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2obhbogmw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daria6918.cn/Article/details/gt2vfitvlwy.html

[J05] 时间加减（加 7 天）
来源：http://dali.jyoumei.cn/Article/details/gt2wpfrpgup.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gt2dmwixklk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxinkj.top/Article/details/gt2jtvrphzn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvatatvd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gt2hwmvpfrb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2drdzbkzx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dianchejie.cn/Article/details/gt2mvqtjdyg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.feifeiyinyue.top/Article/details/gt2squisvbp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.iojbl.cn/Article/details/gt2epycghsa.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gt2ldcnjmbs.html

Py:   (end - start).total_seconds()
来源：http://dali.xinyue.icu/Article/details/gt2mdlftsbt.html

PHP:  $end->diff($start)->days;
来源：http://dali.meibo888.top/Article/details/gt2rfukwptx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gt2xqajwysb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.c1oappe.top/Article/details/gt2gjrqfxsy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cashguo.top/Article/details/gt2wyqixpjf.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gt2girhctub.html

Ruby: end - start                 # 返回秒数
来源：http://dali.haohaochexian.top/Article/details/gt2lqzlpgjn.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gt2qujzukyv.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gt2xpugsapy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2mxacbxvj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gt2dtsrticb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irfeonsh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gt2fjpkkmit.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gt2qthahiiu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shuidangran.top/Article/details/gt2exiuethf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2uhyhjcqj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gt2nrifxjhj.html

[J08] 提取年月日与星期
来源：http://dali.kuanghao11.cn/Article/details/gt2ownnmxkw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhhrksmq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jiagoushi.top/Article/details/gt2suaufnnm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gt2nxsqnelf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gt2xomxwzig.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gt2hxhbmvog.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangshuangyany.cn/Article/details/gt2fkrbmkly.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shuidangran.top/Article/details/gt2sezekybl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.vqdsnc.cn/Article/details/gt2bthuvaxo.html

[J09] 时区处理
来源：http://dali.zhixingplan.top/Article/details/gt2qylobimu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gt2hagafmir.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pycfn.com/Article/details/gt2jrtmezvj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gt2hldbdgnk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gt2uhfvqzxy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gt2rdhndmzr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aibaodan.cn/Article/details/gt2snzrboqk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhongyouzk.top/Article/details/gt2bfczopbz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gt2xepaeflx.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gt2nucdpvjr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gt2dqwoqxyv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gt2projntqt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aibaodan.cn/Article/details/gt2kuuyxsae.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2pvztxwwl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhengqikj.top/Article/details/gt2rmnsneod.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guannengcc.top/Article/details/gt2igphflje.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jiagoushi.top/Article/details/gt2zfwvmxnc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2xhrpxjus.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2pdcngabq.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gt2rqrxdobo.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2oltgfzpd.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gt2ijuvovvx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gt2yfwfblfg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gt2pdtcooky.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2bnjkhfvo.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gt2dlctmqff.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yueranfly.top/Article/details/gt2hmfrjlwm.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gt2kqnlhynr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tanke756.top/Article/details/gt2uulaujzd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2rzofxqfo.html

[K02] JSON 字符串转对象
来源：http://dali.ybcxt.top/Article/details/gt2nazsylss.html

Py:   json.loads(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2vxkmdfmw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ybcxt.top/Article/details/gt2sccemwjo.html

JS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2haapjchv.html

TS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gt2qcdatfqz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2dvefrtek.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gt2pdzjbemm.html

Ruby: JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2newgagut.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gt2bekicfev.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jianghu66.top/Article/details/gt2rifzhggt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gt2rhwmqzqw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gt2eekkapaf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ikkcbnph.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtsawadp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gt2jlcfgdrg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.andypj.xyz/Article/details/gt2onmnkwaa.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangdashe.top/Article/details/gt2yjvlktpu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yonumen.top/Article/details/gt2aslwilik.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gt2zpdztzrk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cucudq.cn/Article/details/gt2walfaiwl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cucudq.cn/Article/details/gt2wvhhapsr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gt2oohlcslv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gt2owoqqdjo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gt2myopvjee.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gt2deqqtzhm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shuidangran.top/Article/details/gt2cduogisb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gt2ywammycf.html

[K05] 深拷贝对象
来源：http://dali.yuanzhike.top/Article/details/gt2bgugqqjb.html

Py:   copy.deepcopy(obj)
来源：http://dali.ybcxt.top/Article/details/gt2hlwbqpfw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gt2dleftwht.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gt2rqiusghp.html

TS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2edvdmzut.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gt2beqgoclz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daxiang520.top/Article/details/gt2scpnhaxw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gt2ucqquukj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guannengcc.top/Article/details/gt2ibzbcoyb.html

[K06] 解析 URL 查询串
来源：http://dali.xziqi.cn/Article/details/gt2juyzulto.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gt2mhxgsgvo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yanxiufei.cn/Article/details/gt2savazfjq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gt2dmtkpqez.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gt2nkvuynri.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gt2cpefgwqj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2vrzdhksk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gt2hijcwkkj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xyqnpgfi.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gt2qjxhbswo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzauawti.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gt2gwwsflzr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2otqsctht.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2hqtjeuxo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2ofdpobut.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigufen.top/Article/details/gt2vxoaqicn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hywenlv.cn/Article/details/gt2tphbtmnl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2tlmidwyk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qkbulepm.html

Py:   pickle.dumps(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hreyfybj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgfzy.top/Article/details/gt2cwfacqsr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2ipgzwqib.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gt2eeqjhdsg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aibaodan.cn/Article/details/gt2xvxdvsba.html

Go:   encoding/gob
来源：http://dali.xziqi.cn/Article/details/gt2tjrigylg.html

Ruby: Marshal.dump(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2hjdubpcw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gt2vhpkqccm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2vnqnyunf.html

L. 网络请求
来源：http://dali.guannengcc.top/Article/details/gt2yhljltfm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2fggkhmak.html

[L01] 发送 GET 请求
来源：http://dali.0kj1m.cn/Article/details/gt2flgynwik.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lezdwchc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2paatoqjv.html

JS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gt2bfzlnzbl.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gt2efwuedhu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuanzhike.top/Article/details/gt2jjnlacpf.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gt2qpaggehy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenzaomai.com/Article/details/gt2vcityfgd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhengqikj.top/Article/details/gt2cfxncemh.html

[L02] 发送 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2wguwsxyk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gt2jpcmiudy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzxylrq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2bwjmkclp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gt2vmqhjghp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yonumen.top/Article/details/gt2idcifczv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.bjfxy.top/Article/details/gt2yppcntod.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.havefunace.top/Article/details/gt2gixexmwc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenlongwang.top/Article/details/gt2fedsfxbk.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gt2tuiarcxi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zdqjudy.top/Article/details/gt2jokttwlr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2jomxaqio.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gt2clcxvcwo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gt2pucaudkz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gt2klwghcei.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gt2ngxakjjf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gt2uiyefszk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gt2nuimsarr.html

[L04] 设置超时
来源：http://dali.ehwqpu.com/Article/details/gt2hcpszoqj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gt2glknjafm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.bjfxy.top/Article/details/gt2lwjarvol.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gt2ouufrgxa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gt2zqhopvyv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gt2sngudfgz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yanxiufei.cn/Article/details/gt2uwiehdgj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.kuanghao11.cn/Article/details/gt2tmbjwkbn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cdnleiting.top/Article/details/gt2fwkxbpzi.html

[L05] 上传文件（multipart）
来源：http://dali.zhoulong.xyz/Article/details/gt2hdairwsq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tian-w.cn/Article/details/gt2rgfgxkmk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxuanxn.top/Article/details/gt2grardmgr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gt2qzzhqemm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gt2rmogfcun.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gt2wbptkcgv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gt2oacpamxh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cqqwz.cn/Article/details/gt2jxxlyfns.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj202588.top/Article/details/gt2ksxaidnj.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gt2psmguyzl.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gt2syofmxlx.html

PHP:  json_decode($body, true);
来源：http://dali.hysaishi.cn/Article/details/gt2lsgjqckt.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2wtozomha.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2ycinkkye.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gt2zmfihgdw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gt2lreimkpg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.birdmap.top/Article/details/gt2ucbmrvpa.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.svipenyu.cn/Article/details/gt2xvbpzwnm.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gt2rurdvuvx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gt2hqzojjoi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gt2worbnwwc.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gt2eeoeikxa.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gt2xqtfbhom.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gt2snwfmsil.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gt2gadhtbry.html

Ruby: resp.code.to_i
来源：http://dali.nanxuanxn.top/Article/details/gt2glpvbkiw.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gt2zkhxpwen.html

[L08] 并发请求多个地址
来源：http://dali.bjfxy.top/Article/details/gt2huqxjnhx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2lwajfuqq.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gt2vgcavqcq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2mizizapw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gt2rquxbgjw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuetiantiany.cn/Article/details/gt2raxnpgrb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gt2dsiqyutz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fihfxmhy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gt2nqldfugy.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2tfzofybp.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gt2vlzqomyn.html


<!-- 参考信息 -->