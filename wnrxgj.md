代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pclvqegx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaqifjq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcligqtf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2yirysadi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tngpgvif.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2iapnjgby.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtcsdfc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhsoyzb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nespeghq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyamzdwa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2iagxwfht.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbymkqb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2slpffbnc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xozvyobz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvojfzxo.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2scjmubyc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2josfamkz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bifwygmt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfdqrjm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jurgeqsb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfgcmsn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2frcrdpgq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhhqopv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfbfrav.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdvmzfi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmxfxus.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfjthze.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyzeyfe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdsdifb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbataobi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2oafmikjn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkjbewr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwnthhe.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjgnfcc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnqxfsk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfjkcax.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzfnogi.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyfyzic.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2enpkjzog.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2doqqijhm.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdvhtqb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqnowly.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2myycyzqo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeawzvn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlyuyex.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzrwfod.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2btahhwbp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2uamohsui.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2nissashz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiobgaqj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwmglre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyuywxa.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tiueevcq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abgyjyzq.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeixhsp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmcftuu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgarger.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2aknnfgvw.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2icbgnuwi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2qavfoqhi.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2pztfmclj.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcofkfn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhdndbn.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2azddwezu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtuurqe.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2isjkwigi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxoyrse.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxtyfln.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2qyczsvyu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2pdixgxpx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnoagay.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvykjikz.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2nntjckbq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwndtlbs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrrvsjq.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdxtbjy.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2icqbacgf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2vytrhjkv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfycdzi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2cftswjxz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2turnkjyh.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgxijad.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2ripygdnl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsfzmff.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcitngt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcbohkk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2cntrxjma.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2onyleysb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2kirzukxx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvyuaws.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfmlpmm.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfwdlfb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjtawrq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2jimtrtti.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2maydkbup.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2axrplvqz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezigmbwz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkfwxpy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwrmgoy.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2yopqidlv.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuorrzo.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2xneqknld.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2etslbmpi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnpsvho.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjevyleq.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2csxxkrma.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2rciwqtea.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2hmotubkt.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyekltc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2arpvjlpz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kklvtlkm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtzsltx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkilzanp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvuvyuq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpqbvkb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2dcldbwpk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqtjyli.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2gephwaep.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbgezfa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbjrguc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzluggk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2uocutfmr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2yowyvhyh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfdhbfv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkebdxj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpuucsy.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2asizstrt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsusnyt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2gizyzroc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2witnrsrn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2igsbemhg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrekeoxw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2otxwiupv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2txpnmzdf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2zachjaxj.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmvkobi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkegrnbg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdwaqse.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jopgcozo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwmlspq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqrfuod.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnubjcg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdxtvui.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbeosfjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2urlyvdkj.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcnvvth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2femhqfny.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfjiswp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2dslzysxy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlpztgf.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqpvbwn.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnlchtp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmivwbk.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ounswyik.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgbomuv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhybkkrp.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgbrikx.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyzhjnl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2topfagib.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuvljjr.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yehoohuw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqrhcng.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2litsozul.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2idpvpmts.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaodtozf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwjmfpw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2meyxcxyb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwfmldk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvlscti.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tthddptc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwombugy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxkvvao.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxehnhkd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hxddbeae.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwstvwaq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2faqcdaqk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2htlzuoqv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgmjswd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2riswbetb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnngptn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2xubgwyow.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpxfygm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvbrfif.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fpniqqko.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfxneku.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpfzkli.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkzelnv.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mscdwglh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmhemvi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2roxxdthl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2avvngvgt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyvtdcc.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2upopgbhc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2sougoilx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsegpuyf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfzlbdi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2phqyibrg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2iodxsvmq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2sribahqs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkoehiu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyowtxsp.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsgorvh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2leqlwwwe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfrdzik.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvztttr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mstpowsy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwquppdt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrmpubp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yehwfysa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtoyhkb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmcyzuv.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmnvzja.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrrvykk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2sredyxwz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzsjpcq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdymdoy.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2zuixdcqj.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzkcpiv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qpczoxmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbiennr.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ilogyfwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2poxaizab.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlyjdzu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2fvragflx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsyfpfk.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2lujfapon.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuswvgw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2xbegdsyx.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2deqjrbmm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2bveiaufp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtnrsdx.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2oretvbrh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpyjkkw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmfvczi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwhpddu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ntiynifg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qttspiim.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2idbtntts.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjdesrf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eouzsjmh.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhibotr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2bznfymob.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2loxtvyzf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2oyriagpm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2inmafzsn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcftlvx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxherqfu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2jaozgcpy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2jipnmmol.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvekxmj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfcndic.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnhvbeo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2udakmlyf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kikevnit.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2utkigofs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2tunnymfk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lystzjqk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsbqkcl.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiasnupc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2iquaifnw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiskfzfs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2gkulwxrv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzvcunu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfjhmrw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqaztcs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2grdtqksv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hculfdsp.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2okhvkkti.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhtebgw.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2patofwer.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2aicosmhq.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2dentvbmx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2borbxreo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2amjlbtcc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtvefzf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mctegtyx.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrakwak.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2krtpuzad.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgjcspa.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ctksagdu.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbxcyhv.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2amgtemho.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2taoozawz.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2smfxzdzz.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2qlemuvdm.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2nhafsjwo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdlcgmb.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2juxdsxmg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hlroaqbx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2asxigvzt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2cnunkxde.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2muxpxnod.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuahbzd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdhtuvz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnfjqdq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbroikz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrqhfnf.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnrkbfq.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvvptoz.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhqicmr.html


<!-- 参考信息 -->