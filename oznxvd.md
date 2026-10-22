代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhixingplan.top/Article/details/gt2iijnrqik.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aizwys.cn/Article/details/gt2skdfuvqy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenlongwang.top/Article/details/gt2ewiefzrk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.snrcjt.cn/Article/details/gt2qazjtqlw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dianchejie.cn/Article/details/gt2dgopgpdm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.9152youxi.cn/Article/details/gt2iirxmwml.html

[I04] 正则替换
来源：http://dali.chenzaomai.com/Article/details/gt2sclbbrmp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfialvrm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2qhkyacqx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gt2htzhnqhj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2rpdhkvmq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gt2ljyqmlwz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2cbdyfahq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gt2ucstuzmc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gt2wtkgddfs.html

[I05] 按正则拆分
来源：http://dali.cucudq.cn/Article/details/gt2vogjjmbo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwjqfdso.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2ijtvhmtt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2inchfoah.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gt2wsmtavvs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hammf.cn/Article/details/gt2shfvqmqj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gt2jvxrsaaq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2gqxsefug.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.snrcjt.cn/Article/details/gt2jqlhkqoz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gt2zoyxruef.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gt2psjbhznr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtwukhdp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gt2uoxpafqv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gt2nhwlkiqq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifwgqxcg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gt2bwfwoops.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dashuyun.cn/Article/details/gt2bjugyggm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gt2jlgclheg.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2splsvalr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gt2zqeghyuw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2kdzrnduk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xyqnlwwo.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gt2kqfdmhag.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhixingplan.top/Article/details/gt2nmurrayl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guannengcc.top/Article/details/gt2yngailsf.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gt2ttyiujpj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yangfankeji.com/Article/details/gt2ccwrrxph.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxtlanwg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gt2uvgvlkqd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gt2yqhynhth.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gt2zwncmawi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gt2ksgapsvj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gt2tadifjgb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gt2zdgnrbbt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kcscynoo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sbmkvbmt.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2hfjzflly.html

J. 日期与时间
来源：http://dali.kuanghao11.cn/Article/details/gt2abhvcoka.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2twakirzu.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gt2mllrxxoe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daxiang520.top/Article/details/gt2ujqtwked.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gt2pwdjgjpt.html

JS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gt2fvghjfdn.html

TS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gt2jvrdyejl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gt2yiimnsjr.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gt2ctcbmrwy.html

Ruby: Time.now
来源：http://dali.guowangkeji.top/Article/details/gt2hwrhagql.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gt2lgonjcfk.html

[J02] 格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tprtodgm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gt2cpolfyrw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gt2ommfgmay.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sufxvd.cn/Article/details/gt2rtgezucl.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gt2foinmufm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gt2mfndqxix.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gt2lfvkjhbr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gt2isjivenb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpcicfv.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gt2zsjnxsdd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnqzz.top/Article/details/gt2hihxwbnz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xylfe.cn/Article/details/gt2gqcrlpst.html

JS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2olcapfli.html

TS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2qfamwsnp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofpdpkfm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2trcmyycf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2bincicyz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nwbrower.top/Article/details/gt2vhpxpsrz.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nseodeny.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2cqhlampk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqwevtob.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fengsongda.top/Article/details/gt2yokuvpss.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gt2ehuwshkx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yueranfly.top/Article/details/gt2vnuhqbot.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gt2rllqgtub.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kugfespl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2krgmckgp.html

[J05] 时间加减（加 7 天）
来源：http://dali.andypj.xyz/Article/details/gt2gfdndwip.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gt2qldcxcwr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guowangkeji.top/Article/details/gt2bkbnkted.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gt2ufsvfszs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gt2geqhgjew.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gt2tzteenxy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gt2cbbxykyr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gt2wazdnozv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gt2xbuvsszo.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gt2vwqokddn.html

Py:   (end - start).total_seconds()
来源：http://dali.yongpay.top/Article/details/gt2dtnlhsim.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gt2uelzhwfx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yueranfly.top/Article/details/gt2uxjzrxpi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgufenzy.top/Article/details/gt2qouqyudh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daria6918.cn/Article/details/gt2ibrcrnqk.html

Go:   end.Sub(start).Hours()
来源：http://dali.svipenyu.cn/Article/details/gt2lxjwfouc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gt2vcdwojfh.html

C#:   (end - start).TotalSeconds
来源：http://dali.jyoumei.cn/Article/details/gt2fsgpizre.html

[J07] 比较两个日期
来源：http://dali.yueranfly.top/Article/details/gt2mydiitmr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2nreqojre.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gt2liydikqc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gt2fxhqtbzg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gt2etxuwnet.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuanzx.com/Article/details/gt2incjsfan.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gt2nxyhzuxt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gt2lfpdzlov.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2wzawfzjt.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gt2yebjhcie.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ppjwa.cn/Article/details/gt2essnjgsc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xylfe.cn/Article/details/gt2khhruheh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gt2edkpdepx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gt2rmpcsxra.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gt2gkworlqo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuanzhike.top/Article/details/gt2nynejrmi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgufenzy.top/Article/details/gt2xocojbaj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.havefunace.top/Article/details/gt2asqehyoe.html

[J09] 时区处理
来源：http://dali.shuidangran.top/Article/details/gt2fglsggvj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gt2ntwkslcb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gt2muwgifxb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gt2unjstmpy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gt2qxlqqptk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sysykeji.top/Article/details/gt2pbtaljan.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gt2jtpjazme.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gt2hsdhhjcl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gt2qgtfxfht.html

[J10] 取今天 / 本月第一天
来源：http://dali.aibaodan.cn/Article/details/gt2fvznhenl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gaohongyu789.top/Article/details/gt2mmkorwuv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cdnleiting.top/Article/details/gt2jceaulda.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.birdmap.top/Article/details/gt2jemmripp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2inwhpwqp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gt2krzcfscu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gt2ifxjclxp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gt2svuijemx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.iojbl.cn/Article/details/gt2cgughxus.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2nbzggfdx.html

K. JSON 与序列化
来源：http://dali.zhongyouzk.top/Article/details/gt2jfpngtsl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2zcmbfmyq.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenlongwang.top/Article/details/gt2wpvkcisv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gt2welcqwka.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2hyarhfhp.html

JS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2bemhvssa.html

TS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gkczbzyc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gt2vlvkdnor.html

Go:   json.Marshal(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlwymveh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.iojbl.cn/Article/details/gt2ourxydpu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yueranfly.top/Article/details/gt2ydwcxadb.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gt2cgrzcxgk.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gt2szwrqtqp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gt2sooinhui.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2gkrogoll.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2zecccfwr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivhwjpvn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gt2ofajqrqc.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2cxtxdiyd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigufen.top/Article/details/gt2ibtrzwqv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangdashe.top/Article/details/gt2kcuezbxn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mpbhpxbp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gt2aazyojrk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2ykkbqret.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gt2vtvwjrop.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2qoxyhlmd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xsjlmgls.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdvsnmdv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gt2ofmntcqd.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gt2sjbqcmdx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2auopaqca.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gt2glehtqdf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gt2zkkzfnra.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqwwcoyr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zycfv.cn/Article/details/gt2bbgrnrqf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gt2vnmesovp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ybcxt.top/Article/details/gt2mcvwlctz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.bjfxy.top/Article/details/gt2meqgrknx.html

[K05] 深拷贝对象
来源：http://dali.svipenyu.cn/Article/details/gt2tgquekpa.html

Py:   copy.deepcopy(obj)
来源：http://dali.fengsongda.top/Article/details/gt2ulnzblot.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fengsongda.top/Article/details/gt2oghkstih.html

JS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2melesjns.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gt2wceodrzm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vtekljvm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gt2qczafbdi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gt2ewsonwwg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yangfankeji.com/Article/details/gt2zjvydpzj.html

[K06] 解析 URL 查询串
来源：http://dali.dianchejie.cn/Article/details/gt2fxffbxro.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yueranfly.top/Article/details/gt2berqjuuc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gogol.net.cn/Article/details/gt2tzgdhbgc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gt2ofhycpus.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gt2axsrhfyq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.bjfxy.top/Article/details/gt2nzjosqri.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2jfurrnfa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2ttqjuyvp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gt2qlbhxxgc.html

[K07] 进制转换
来源：http://dali.sweek.top/Article/details/gt2guxjuzxd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2qcgyctle.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.andypj.xyz/Article/details/gt2wppoetnt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2tcgbtiok.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdaacbao.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2qiveueyo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gt2gtfjlvtm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhongyouzk.top/Article/details/gt2dtrnnvvd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2knbhgvog.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hywenlv.cn/Article/details/gt2zcoadntd.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2nanrxqkt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gt2ijsdvipm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gt2dqjocsnu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gt2nidrrbqu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuetiantiany.cn/Article/details/gt2uowykgsc.html

Go:   encoding/gob
来源：http://dali.yj20258888.top/Article/details/gt2nrhheteb.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gt2qxztsaar.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gt2nsvkrntx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2xnfvxwfn.html

L. 网络请求
来源：http://dali.ybcxt.top/Article/details/gt2sjgnytjj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2icvfutwr.html

[L01] 发送 GET 请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhsdnlsg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gt2douqrxbs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hlbqbgmi.html

JS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gt2sczfqrwz.html

TS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gt2ulzbgpbv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gt2otjqxyra.html

Go:   resp, err := http.Get(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qopkegry.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dianchejie.cn/Article/details/gt2fvrhkfui.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aecdmyss.html

[L02] 发送 POST JSON
来源：http://dali.hnqzz.top/Article/details/gt2fpotlpun.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guannengcc.top/Article/details/gt2fjsgyqdv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gt2iftshxza.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gt2xtctopbj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjnmeeuj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenlongwang.top/Article/details/gt2fxsuultx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gt2glvncith.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sysykeji.top/Article/details/gt2nxitblhl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jwpcmoiq.html

[L03] 设置自定义请求头
来源：http://dali.quarkkingdee.top/Article/details/gt2cgqovsva.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gt2xmwpeegu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gt2vwydoaqn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gt2cmuvnosf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gt2hdtehrue.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lvdlcbgp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gt2bhkwdqtw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.9152youxi.cn/Article/details/gt2ozuzscxo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gt2eojzkkdb.html

[L04] 设置超时
来源：http://dali.pycfn.com/Article/details/gt2xldzmgxk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shuidangran.top/Article/details/gt2dmfqczbx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ehwqpu.com/Article/details/gt2dnsaawiy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gt2jvmximow.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gt2dvmgnvcz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gt2kybgihbb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhengqikj.top/Article/details/gt2ndovwigr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.kuanghao11.cn/Article/details/gt2dumawohs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gznnpdbh.html

[L05] 上传文件（multipart）
来源：http://dali.pycfn.com/Article/details/gt2nkpqxpjj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gt2gusdlhii.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gt2onqojtkc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gt2zmkzkcpx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gt2qiuklrlx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnxiangtu.top/Article/details/gt2sarhueki.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xylfe.cn/Article/details/gt2jvslmmdj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daxiang520.top/Article/details/gt2viibaoev.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2awpgimyf.html

[L06] 解析响应为 JSON
来源：http://dali.hammf.cn/Article/details/gt2oievqpez.html

Py:   resp.json()
来源：http://dali.gogol.net.cn/Article/details/gt2wqbwkwvn.html

PHP:  json_decode($body, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2leuoetsp.html

JS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gt2eigwtgsi.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2vhrynsbd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gt2rvouymbt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gt2yphgehwo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gt2vcvpqvzm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shzxlz.cn/Article/details/gt2airncoin.html

[L07] 处理 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gt2uabrwiwt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.havefunace.top/Article/details/gt2awngiwhe.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gt2odmzcdyr.html

JS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gt2invwptwc.html

TS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gt2hmxiikzi.html

Java: resp.statusCode()
来源：http://dali.quarkkingdee.top/Article/details/gt2evctrwxy.html

Go:   resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gt2txjihvvx.html

Ruby: resp.code.to_i
来源：http://dali.dashuyun.cn/Article/details/gt2qpepqtol.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2bkksmnnx.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gt2fhqzlczq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gt2ysdaqvta.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gt2hpkahefg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gt2qtjyeyrc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gt2nwmutjbq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jhyjntpw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gt2wcgbvoul.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gt2xuxijwev.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yanxiufei.cn/Article/details/gt2hwdmsqxt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2lgzpphla.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigfzy.top/Article/details/gt2zqwwtxlq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2vqnibfgx.html

[M01] 读取命令行参数
来源：http://dali.ydzc1.top/Article/details/gt2yvcltfol.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gt2ozdtomch.html

PHP:  $argv;  $argc;
来源：http://dali.ybcxt.top/Article/details/gt2xqyzdufp.html


<!-- 参考信息 -->