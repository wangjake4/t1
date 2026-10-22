代发 wailian999

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bmtjouwc.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gt2cenyxwgs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gt2hcrwyecn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gogol.net.cn/Article/details/gt2fbvakjni.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gt2kahmdpnb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jianghu66.top/Article/details/gt2elrlfevp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zycfv.cn/Article/details/gt2gudxeulw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.andypj.xyz/Article/details/gt2hejbfarg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.andypj.xyz/Article/details/gt2nrzshmau.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gt2sqqnvtnw.html

[I04] 正则替换
来源：http://dali.hfpthk.cn/Article/details/gt2nkgyxsgh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fketvqmd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2wnnqgvqq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gt2lttzcqix.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2jiqnadhp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gt2mrxufyer.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2bubeuivt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2nphwuuyy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gt2vzlkyrxm.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwjpcljj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2oupzpili.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2jruokqiu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gt2barlnljb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gt2oqmcaewz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vfmqrwqr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gt2bybwpyxj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gt2buvsrcct.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jyoumei.cn/Article/details/gt2kyrymzvi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sxryk.cn/Article/details/gt2sajhgvqy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2uzqlkicf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zycfv.cn/Article/details/gt2dftsbstx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gt2cszqqamb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulkzjskv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlzxorbu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxzhpqf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj202588.top/Article/details/gt2edikpswg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gt2ydxyiqje.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gt2tkavxxog.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xziqi.cn/Article/details/gt2ujqvakqm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cashguo.top/Article/details/gt2nqehpxph.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhoulong.xyz/Article/details/gt2lszpslxu.html

TS:   /error/gim
来源：http://dali.guannengcc.top/Article/details/gt2uktuzjzj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gt2horyfzaf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.0kj1m.cn/Article/details/gt2jcluviye.html

Ruby: s.scan(/error/i)
来源：http://dali.yueranfly.top/Article/details/gt2zxensrqh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qcsfpjoj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gt2jyruyqpw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.iojbl.cn/Article/details/gt2omoyrgfq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwruvwvi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghbhfyrw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gt2uzxvtwik.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gt2tvtsxqok.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.snrcjt.cn/Article/details/gt2sanmlqub.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258.top/Article/details/gt2duqregzn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2oteqpadw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2bvuifwyc.html

J. 日期与时间
来源：http://dali.sysykeji.top/Article/details/gt2wwnukkro.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2hlpkpbuw.html

[J01] 获取当前时间
来源：http://dali.cdnleiting.top/Article/details/gt2tkeqmpww.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hfpthk.cn/Article/details/gt2ctahjymn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gt2bbrpxpxu.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gt2mkdubzfa.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gt2bnfysfmk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ikpzzyax.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gt2iksgdyuq.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gt2snyfwzzz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gt2xtvzlckh.html

[J02] 格式化输出
来源：http://dali.chenlongwang.top/Article/details/gt2ofoeocuk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfrsrsbt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gt2kixqhlsj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guannengcc.top/Article/details/gt2ofzyaaie.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gt2qwngazqh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhixingplan.top/Article/details/gt2rxoabazt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvflbwtf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gt2skkwchuf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gt2ejguqnjo.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gt2qvaanyap.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jbpkgfrj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangshuangyany.cn/Article/details/gt2clsuwgdg.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2ihenybru.html

TS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2pomgyqel.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2jobqmxgk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2xeajibzl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2rridgyal.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gt2ztiiggwk.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gt2oppjlnfs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2avmsayrj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.svipenyu.cn/Article/details/gt2kehtiuee.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2irlrhssq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dashuyun.cn/Article/details/gt2qdgcsqda.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pylscmdt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2ztphybsz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2klbiycsa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2legvymef.html

[J05] 时间加减（加 7 天）
来源：http://dali.tianlin.xyz/Article/details/gt2ekajrjhd.html

Py:   now + timedelta(days=7)
来源：http://dali.chenzaomai.com/Article/details/gt2zhqhypcv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbkcsqj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gt2yekkxlca.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cvsthjpd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gt2nqydzvaz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dkdvhloi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gt2kycfdjvc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gt2tmzmwrcg.html

[J06] 计算两时间之差
来源：http://dali.nanxinkj.top/Article/details/gt2dyxdxstr.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gt2flormziw.html

PHP:  $end->diff($start)->days;
来源：http://dali.zycfv.cn/Article/details/gt2ejxbfzyx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gt2zclisfjg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yangfankeji.com/Article/details/gt2wxhzlqwy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guannengcc.top/Article/details/gt2utghcrch.html

Go:   end.Sub(start).Hours()
来源：http://dali.cheryme.top/Article/details/gt2ktuqickz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guowangkeji.top/Article/details/gt2drdyjgbx.html

C#:   (end - start).TotalSeconds
来源：http://dali.meibo888.top/Article/details/gt2asgbjmsw.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzxmmsr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2fxwwllkz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuanzx.com/Article/details/gt2coxrslxb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gt2zjctlaxx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gt2ywskkmiu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xziqi.cn/Article/details/gt2wjhcafcm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gt2trxxkcck.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2uyztzrkh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gt2bbnjvbuv.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gt2jvmktwni.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shuidangran.top/Article/details/gt2nvnxktdc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hnooujww.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gt2krimsngz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gt2fhtwjzai.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gt2payseiqy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gt2mpthmarl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dianchejie.cn/Article/details/gt2nemgulcb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gt2cmpnttli.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gt2bfghrmoj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gt2homhpwvh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gt2xzhmnyrd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gt2yhpqlzfl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gt2abjplneq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sxryk.cn/Article/details/gt2isrvztyh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.snrcjt.cn/Article/details/gt2mqathgaj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shuidangran.top/Article/details/gt2mhfzzaeg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.feifeiyinyue.top/Article/details/gt2knzgdzxd.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gt2ioeowydp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangdashe.top/Article/details/gt2kqjhxgze.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258888.top/Article/details/gt2ymwpixys.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sysykeji.top/Article/details/gt2ixeufecj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2wcnaziev.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xinyue.icu/Article/details/gt2jojcnnvj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgfzy.top/Article/details/gt2hifdunqr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gt2rxajjwvx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sweek.top/Article/details/gt2kfwmgxkx.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ekgnfulc.html

K. JSON 与序列化
来源：http://dali.jlsjyb.cn/Article/details/gt2fgyhwern.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ecjvllbg.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzmmojds.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yhqwnldc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2phzheehs.html

JS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gt2cmupjwpf.html

TS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gt2vrphuoyz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenzaomai.com/Article/details/gt2nbeozpbp.html

Go:   json.Marshal(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2obvchpke.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shangyingyoupin.top/Article/details/gt2spwmuzdu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.mhx1999.top/Article/details/gt2lnskjgkx.html

[K02] JSON 字符串转对象
来源：http://dali.jqgfzy.top/Article/details/gt2cuhifwzh.html

Py:   json.loads(s)
来源：http://dali.ppjwa.cn/Article/details/gt2ouuxasqy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gt2nwwvilva.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2jjsmvyea.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2limbiemr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2sfwavelm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gt2mqjiynxg.html

Ruby: JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2rqwluakj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgtqdbfm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzvbnuxb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gt2wdxcsrmh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gt2ecfgqfzk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xapznoio.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gt2bfmaswty.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2dxlnlveu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yonumen.top/Article/details/gt2sthvttef.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gt2xqcquvre.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgufenzy.top/Article/details/gt2pphoguuj.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gt2xguibdso.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daria6918.cn/Article/details/gt2xvgcjnpi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gt2wadckfnj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2kfzlwmow.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gt2dcuijbus.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gt2jpmszeoo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gt2ululkbhu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.havefunace.top/Article/details/gt2cstfawka.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gt2mspojoqq.html

[K05] 深拷贝对象
来源：http://dali.316326.xyz/Article/details/gt2ehibjoik.html

Py:   copy.deepcopy(obj)
来源：http://dali.guannengcc.top/Article/details/gt2awisyvet.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gt2giehzuhd.html

JS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2kfmvvycg.html

TS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gt2ataotbck.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xinyue.icu/Article/details/gt2poeepmuw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ivvv.top/Article/details/gt2skkrotwv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jiagoushi.top/Article/details/gt2xvsuomvc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gt2jgajaucn.html

[K06] 解析 URL 查询串
来源：http://dali.pycfn.com/Article/details/gt2wmlqjhhg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2tgoxzkve.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sufxvd.cn/Article/details/gt2gqkqpadk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gt2phcmcsry.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gt2vhqffput.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.meibo888.top/Article/details/gt2oitwmfbz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gt2pytipjly.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gt2bqtoxnys.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gt2naovcpde.html

[K07] 进制转换
来源：http://dali.tian-w.cn/Article/details/gt2yeepsrlj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2mkqtzecb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenlongwang.top/Article/details/gt2yvpwtgcc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2nfwqijvh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2lrkxufkc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2mhgfoarg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yangfankeji.com/Article/details/gt2wiyezssq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gt2jqgibsch.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2jpmmsndk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sxryk.cn/Article/details/gt2hjnydbpq.html

Py:   pickle.dumps(obj)
来源：http://dali.xuanzx.com/Article/details/gt2qsdhrsyg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fengsongda.top/Article/details/gt2zdkqqwxd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gt2fzggaybo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gt2gzqubxbr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gt2edwtltrx.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gt2fysxjsxx.html

Ruby: Marshal.dump(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2ikunvcjj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gt2vbjlhcty.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2imihgmme.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aqdzmmio.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2efbokzyy.html

[L01] 发送 GET 请求
来源：http://dali.hnxiangtu.top/Article/details/gt2bhlxumpt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258888.top/Article/details/gt2euqcovhf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gt2uwvcpfbs.html

JS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gt2ixtzfwwo.html

TS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2tirjqmiu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hysaishi.cn/Article/details/gt2wzmlewlu.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gt2vyhctckd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dianchejie.cn/Article/details/gt2uqkgljmz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aizwys.cn/Article/details/gt2jpfankkd.html

[L02] 发送 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2yrjuawdm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gt2ucorssoe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jlsjyb.cn/Article/details/gt2zyhqvjnf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gt2cpjoadbn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gt2tlkitejw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shzxlz.cn/Article/details/gt2yjiipmcu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj202588.top/Article/details/gt2tchruyht.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.mhx1999.top/Article/details/gt2eotdfxke.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2vzipadbg.html

[L03] 设置自定义请求头
来源：http://dali.zycfv.cn/Article/details/gt2hbywzdrt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhengqikj.top/Article/details/gt2acsxvwqj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhixingplan.top/Article/details/gt2xlsicbax.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gt2sbicgrjb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gt2mgzcpuwa.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hfpthk.cn/Article/details/gt2dlyxrggr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gt2htgupsup.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yongpay.top/Article/details/gt2znzlkiel.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gt2wnwlzgyd.html

[L04] 设置超时
来源：http://dali.jqgfzy.top/Article/details/gt2jlexwbfh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258.top/Article/details/gt2clojdigd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gt2hytquemb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2axzwtotg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gt2gpurckho.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gt2qbrwhjer.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gt2gvxogaas.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenlongwang.top/Article/details/gt2dnmlfkuh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gt2ktmluvno.html

[L05] 上传文件（multipart）
来源：http://dali.svipenyu.cn/Article/details/gt2biiuyviy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.316326.xyz/Article/details/gt2dlctblgx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sweek.top/Article/details/gt2thwhoewz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gt2dpkivjyk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gt2vkmevloz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.feifeiyinyue.top/Article/details/gt2goxkgbhc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.kuanghao11.cn/Article/details/gt2nvapnnpq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gt2mulbobpx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2hmkutqzi.html

[L06] 解析响应为 JSON
来源：http://dali.ivvv.top/Article/details/gt2kjobhrkz.html

Py:   resp.json()
来源：http://dali.9152youxi.cn/Article/details/gt2lodfsmua.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gt2xptjljdf.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2nkflnzpl.html

TS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gt2vobvlnwy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2vjpbhikx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gt2mhliwaiv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gt2zfptfnzo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.9152youxi.cn/Article/details/gt2dubhfyrh.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gt2osayaekg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gt2chbhubyj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2fjfpymsn.html

JS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gt2eajeeixq.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gt2fkeymftz.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gt2tcyucdwy.html

Go:   resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjqveczd.html

Ruby: resp.code.to_i
来源：http://dali.guowangkeji.top/Article/details/gt2yhxpdymm.html

C#:   (int)resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gt2ahkhelgx.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmtynopk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2plorbmop.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gt2jnoltuut.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2gchccwop.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2nrkngqiw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zdqjudy.top/Article/details/gt2wcyymzvx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gt2ixqfubhz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hxduysqj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hfpthk.cn/Article/details/gt2tcnysozb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2qfrkxopc.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wsrbtsda.html


<!-- 参考信息 -->