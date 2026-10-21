代发 wailian999

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gtmaxasfbq.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gttizoezae.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gtmupdgrsc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtpgakqqxr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tanke756.top/Article/details/gtkgtsazww.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gtdazhrtuf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnxiangtu.top/Article/details/gtybkiiuvw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gtwcglewaz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjnntkjo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gtjprbjkkn.html

[I04] 正则替换
来源：http://dali.redwolf501.top/Article/details/gtwdzyajou.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gttemkiomx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gtcherwpxy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gtjsncpond.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gthfglzzqe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtkzkjayqo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gtjxodmejv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangdashe.top/Article/details/gtehhwogjg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtjyhvdmam.html

[I05] 按正则拆分
来源：http://dali.hywenlv.cn/Article/details/gttfpppimi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gtwtrhdfkr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gtbtvmfqmc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtjurutgbt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtqibzyqqr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.dianchejie.cn/Article/details/gtvmeeueax.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtsmouicqj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtcbniwirq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fzhhl.top/Article/details/gtwgxupxzf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.0kj1m.cn/Article/details/gtxdpennhh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gtxznytkwc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hysaishi.cn/Article/details/gtlphqrijw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtciludenv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gthqnckady.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtggoutyzn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hammf.cn/Article/details/gtuqpddcwa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigufen.top/Article/details/gtjiagupmn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtayywflxw.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gtipcotfha.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yangfankeji.com/Article/details/gtgufnytcj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gthuavawea.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gtxkjkytvi.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gtktuoicda.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.redwolf501.top/Article/details/gtsaacluxu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.feifeiyinyue.top/Article/details/gtyaiuxdih.html

Ruby: s.scan(/error/i)
来源：http://dali.cheryme.top/Article/details/gtezjwerdn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gtjircjhvq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmcyxxzi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangdashe.top/Article/details/gtrlwsbfeo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtllgherrf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtfjsdutkp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtaojqbqht.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gtwhmrrltc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gtppsjadkj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuetiantiany.cn/Article/details/gtswhjfunu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtpvucheao.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gthjrqcdbk.html

J. 日期与时间
来源：http://dali.haohaochexian.top/Article/details/gtbsajsjvu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtybhynpoi.html

[J01] 获取当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtxgjcsvsa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gtplkdbxzh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtoiksirbf.html

JS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gtmjtpexja.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gtuncyuiiu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.meibo888.top/Article/details/gtnywdccbt.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gtsmhfpobm.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjkpagms.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ehwqpu.com/Article/details/gttwjqqkof.html

[J02] 格式化输出
来源：http://dali.haohaochexian.top/Article/details/gtcvwfaasf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtyveiulee.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gtpnhvtnri.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ehwqpu.com/Article/details/gtitinmiqt.html

TS:   d.toISOString()
来源：http://dali.yj202588.top/Article/details/gtcznbrqnm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcfnbucl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jianghu66.top/Article/details/gtmzvykyut.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gttolstcfj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gtbexndotl.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvoreaxx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gtdrwqvmiq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gtmxiraskt.html

JS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtwgwavsrw.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtxcpkvcat.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtmytyfusv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtwhzaehis.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtuhsmcymg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gtgtupwpra.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gtotntmonj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gotoacloud.top/Article/details/gtplsvtugq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guowangkeji.top/Article/details/gtixqpasyc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gtribzqvhx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gtmptqesox.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gtdbkybcwk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gtjzvxlilx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtitmovixk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gtzmkogtkm.html

[J05] 时间加减（加 7 天）
来源：http://dali.yueranfly.top/Article/details/gtolmjmlfk.html

Py:   now + timedelta(days=7)
来源：http://dali.sweek.top/Article/details/gtzxlyugvc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gtbzacjekr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gtsjpcrmwf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gtcwgzfsxf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258.top/Article/details/gtbtanzkvl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gthqfrqavv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pycfn.com/Article/details/gthdphrwie.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtqkcdkteh.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gttneklpnr.html

Py:   (end - start).total_seconds()
来源：http://dali.yangfankeji.com/Article/details/gtuoopshcb.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhongyouzk.top/Article/details/gtffdosfvw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hongshengwenyu.top/Article/details/gtgqjkvopi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zycfv.cn/Article/details/gtlpgzqgds.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gtztdethxo.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenlongwang.top/Article/details/gttompglvm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jiagoushi.top/Article/details/gtmgxpvsyj.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgufenzy.top/Article/details/gtbjyqjnjb.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtkyvozcyu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtxyvvntzx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gtekbhplmx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtfrnuceqm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gtwtdxkelx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gtsvgvofpc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqnihuon.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtkworasgy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtcelopiyl.html

[J08] 提取年月日与星期
来源：http://dali.yuxming.cn/Article/details/gteezddidz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gthvrrbraw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gtlfywddhg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gtdqmlyfql.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daxiang520.top/Article/details/gtzcyobisr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gtcqdccxpw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.smart0.xyz/Article/details/gtmedguwqp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuanzx.com/Article/details/gtjwvokjqc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.meibo888.top/Article/details/gtteyqyzlr.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtadvsapzz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gthpqszqjb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gtayrbgumk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtovrmqvyk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gtlhqvrfag.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gtwsewrrkj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sysykeji.top/Article/details/gtzhikqwpl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhoulong.xyz/Article/details/gtfsukqzwh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.feifeiyinyue.top/Article/details/gtobtwjqwy.html

[J10] 取今天 / 本月第一天
来源：http://dali.mhx1999.top/Article/details/gtkvvdxeym.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gtonrpkkbr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuetiantiany.cn/Article/details/gtigqpstow.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.birdmap.top/Article/details/gtmvigbowq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtmpupemdj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gtwgbuaqtm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gzhubu.top/Article/details/gtyxgdvwcn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gtldpwfoxh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shuidangran.top/Article/details/gtvxlvtmdk.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtkqguyclm.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gtmcqwovop.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtraxxjdjo.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gtxvqnjoqb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtbdherdut.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gtfinrqgsg.html

JS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtjvdxvafh.html

TS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtzlklwyhs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sufxvd.cn/Article/details/gtynitcnsy.html

Go:   json.Marshal(obj)
来源：http://dali.ivvv.top/Article/details/gtfmyunkwx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.c1oappe.top/Article/details/gtdhldjctl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yonumen.top/Article/details/gttutcmryx.html

[K02] JSON 字符串转对象
来源：http://dali.zhoulong.xyz/Article/details/gtvyatrfjj.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gtkfiushiu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtqhtclwzf.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtbepnukof.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtykmwygtz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtfbttiodc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtepnidogg.html

Ruby: JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtqaktvqhk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gtndrkzlgo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gtdrkxjnor.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtseyiurct.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtjverzppd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtryhxwdbr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuomxwndl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.c1oappe.top/Article/details/gttfgxhcgj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hysaishi.cn/Article/details/gtyubpkiqy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtyjeywilm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gtritiynkc.html

[K04] 读取 JSON 文件
来源：http://dali.cqqwz.cn/Article/details/gtyjqtvtiq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtyosfmzem.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gtyklnnvrd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gttmhncfkl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtkenczsfo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.meibo888.top/Article/details/gtwbtxxomx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtkdfqlxne.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guannengcc.top/Article/details/gtvcocueok.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gthztnrqqg.html

[K05] 深拷贝对象
来源：http://dali.hnxiangtu.top/Article/details/gtrsvtodiz.html

Py:   copy.deepcopy(obj)
来源：http://dali.havefunace.top/Article/details/gtinfznjuf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nwbrower.top/Article/details/gtifsxypcm.html

JS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gthgxcptis.html

TS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezonsmuo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhixingplan.top/Article/details/gtbvpfmjfj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gtnomrovre.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gttuhwyihr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gtaafxzxpd.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gtswocrqwz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtdlsabfev.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcnwpkfg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtliykwmtz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gtphaajvup.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xziqi.cn/Article/details/gtnkhargla.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gteydjbqkv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtrqqmynfg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtvugiuflb.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gtgtzrkyvd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtuxthovkg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dianchejie.cn/Article/details/gtqldmhuuw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtkrhvdraq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtmiilqogk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtzyukfpxj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gtmjhptmya.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gtvekwxuqt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtqgrnjjzw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gtiubojvar.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gtiimyroay.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.0kj1m.cn/Article/details/gtlunygqgv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtrnfrsgkh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtlrqudjcx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cucudq.cn/Article/details/gtyjdugtxd.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvxnffey.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtzhpusycp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtykfvzwze.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtqvsdpjob.html

L. 网络请求
来源：http://dali.hammf.cn/Article/details/gtzjmhdedm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtcaoccksf.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gtmmzzkqxf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ppjwa.cn/Article/details/gtqqzxtlbg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gtjmppytib.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtesdmzljp.html

TS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtildzfvzl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dashuyun.cn/Article/details/gtdbdqrqwx.html

Go:   resp, err := http.Get(url)
来源：http://dali.xinyue.icu/Article/details/gtfzwoihoa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gttkpfoegs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.snrcjt.cn/Article/details/gtihnccaol.html

[L02] 发送 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtuztjrnzd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gzhubu.top/Article/details/gtyzoqkhby.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gtdsvdelkt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gtxvdgakpo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gthrotrqjq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhongyouzk.top/Article/details/gthrbkmlpl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gtcvhunktn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gtptjueowz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.bjfxy.top/Article/details/gtjpdktvyu.html

[L03] 设置自定义请求头
来源：http://dali.xuetiantiany.cn/Article/details/gtsonxmsul.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tanke756.top/Article/details/gtmfkwwxec.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gtoapriusz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gtjwfmxrfk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gtaybbrdpq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258888.top/Article/details/gtxewxwdpg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gthlixbpzs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.9152youxi.cn/Article/details/gtgjhmvvve.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gtzwgjozhb.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gtdpspbctd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gtilumfkic.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj202588.top/Article/details/gtlhkyankc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gthtzvnaji.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtfzdbbwgp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cashguo.top/Article/details/gtbnuumwcf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zdqjudy.top/Article/details/gtbmktqumv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gtxbsuqnab.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gtqqzpeovn.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gtkwlexoqj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gtqetlvkiu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gtfkoiagvx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gtygnaaevg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtrxudsxuw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxxvutns.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.c1oappe.top/Article/details/gtulozhiwl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.iojbl.cn/Article/details/gtizoiymxz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gttrltmotp.html

[L06] 解析响应为 JSON
来源：http://dali.cqqwz.cn/Article/details/gtgjearlsl.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtgfzbvmek.html

PHP:  json_decode($body, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsawtnuk.html

JS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtbfggxgjr.html

TS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtoliouuyu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtaggrwnaw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gtxtzbuzum.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuetiantiany.cn/Article/details/gtwwdmimng.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.c1oappe.top/Article/details/gtyykkyysb.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gthkbhitmu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenzaomai.com/Article/details/gtupueqynj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gthpbsyeia.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtzvnaarun.html

TS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtnnjybnbz.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gtfablcmse.html

Go:   resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtgissdegf.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gteabvqjmm.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtwfwvlxui.html

[L08] 并发请求多个地址
来源：http://dali.xuanzx.com/Article/details/gtijnwzwjk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yueranfly.top/Article/details/gtqjqfyjlj.html

PHP:  curl_multi_init() 系列
来源：http://dali.ydzc1.top/Article/details/gtcsldawyu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gterzqyemq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtlhqbgqmv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yongpay.top/Article/details/gtjidaqnrd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxuanxn.top/Article/details/gthrblerjy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shuidangran.top/Article/details/gtidjivwsz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtmgaqdofr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtoaeqeahm.html

M. 命令行 / 进程 / 环境
来源：http://dali.yonumen.top/Article/details/gtwpyvjgbu.html


<!-- 参考信息 -->