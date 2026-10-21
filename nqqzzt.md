代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gtpzwpbmxj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sufxvd.cn/Article/details/gtvclpcrcx.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gtpsjelyph.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gtfzodaeho.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gtomjfufvm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtelgeytbu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtixvzwkwd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckfyxccm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fengsongda.top/Article/details/gtjafcfhoa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hfpthk.cn/Article/details/gtnoqtsdtw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpppcduv.html

[I05] 按正则拆分
来源：http://dali.yj202588.top/Article/details/gtfiryjnzu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnqehvdv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtyqooscrd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtyzxntbdn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkrlyuvo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbdcqcit.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gtpcchlwtp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtpjppmpuq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.c1oappe.top/Article/details/gtjtkgkxfq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gtbknlflsf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtbfeoorey.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gtknukojax.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtzlqiksbl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnonkvfaf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtmqfeunvn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guowangkeji.top/Article/details/gtcpyefkgb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xinyue.icu/Article/details/gtxpmeqoul.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtkoinzind.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gtayaykhqw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ehwqpu.com/Article/details/gtqgidlzhm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yongpay.top/Article/details/gtlgzsrqxd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gtshnnjgaz.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gtcquxloog.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gtbdqyjxql.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gtobeenmlw.html

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gttifuwhpg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shangyingyoupin.top/Article/details/gtzngsbxap.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ivvv.top/Article/details/gtdckhegzy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.svipenyu.cn/Article/details/gtsykqjkgx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtqoxhvjgq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gtmtdhsgst.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gtrxymffyf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gtlqjrufku.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gtkziqiynt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.mhx1999.top/Article/details/gtketyjesp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gttizdadaw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwqlithej.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gtxfjotfzp.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtekjibvpd.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gtktrvzzkx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gaohongyu789.top/Article/details/gtxrtsftni.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtpiedzhbr.html

JS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtaoryvzkk.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gtspsoubfi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gtjuetwctq.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gtpeqlyivo.html

Ruby: Time.now
来源：http://dali.meibo888.top/Article/details/gtdphsvepz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gtjxazkyhs.html

[J02] 格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtgoncshsf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzilfpmg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gtlcqtyqud.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gtomryjqfn.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gtgiiqintu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gtoxlkwhtl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gticbsrkfq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtslcfevpo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgufenzy.top/Article/details/gtsiyqtwvo.html

[J03] 字符串解析为日期
来源：http://dali.xziqi.cn/Article/details/gtdpbfnckx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zycfv.cn/Article/details/gtlfmyzwyl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tianlin.xyz/Article/details/gtugipklnk.html

JS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtbjxitjbf.html

TS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmikoojf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtlsifpjyh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtrvazuuup.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtyxplcfqr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gtgnmucnix.html

[J04] 时间戳与日期互转
来源：http://dali.wangshuangyany.cn/Article/details/gtznzsvzfg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gtlcrcswqv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gtvjmqmpvw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtzxcvvopm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgfrtihw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gttsbrshbw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gogol.net.cn/Article/details/gthmkxezpo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoliqvuut.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gtfqrfgjcu.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gtogheblbf.html

Py:   now + timedelta(days=7)
来源：http://dali.sxryk.cn/Article/details/gtecspmenh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gtxhegvgsa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gtlnunqfny.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtjyaiiimz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhengqikj.top/Article/details/gthgoiocic.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cdnleiting.top/Article/details/gtcxiuhoht.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gtltlkxwef.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gtrhejiise.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzfjvuww.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzppvbhm.html

PHP:  $end->diff($start)->days;
来源：http://dali.shzxlz.cn/Article/details/gtdslfgqzh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangshuangyany.cn/Article/details/gtoilftgir.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pengpengdd.cyou/Article/details/gtywbcwjtr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gtnuqexcch.html

Go:   end.Sub(start).Hours()
来源：http://dali.meibo888.top/Article/details/gtzqdhxoii.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xylfe.cn/Article/details/gtijnwgxjt.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gtnqizjkax.html

[J07] 比较两个日期
来源：http://dali.yongpay.top/Article/details/gtgqvyxjcg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtwcbxwxjr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gtqugnhtur.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtrgkkkqlo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtnhqyzkrh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258.top/Article/details/gtcelhxfzw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtnyujfphy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gttwyqojhe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtcsurrywq.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gtzklbxcgz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yvedp.cn/Article/details/gtjtcpqrhd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jianghu66.top/Article/details/gtgpcquysj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zycfv.cn/Article/details/gtwobqorji.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gtiamfzlqq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gtarimxbir.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fzhhl.top/Article/details/gtrbwpqwda.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdjghvem.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gtmpvuxcpk.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gtgvctlcyh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinghuilouyu.cn/Article/details/gtifqzuffu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gtgqjcwbqe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtbzhrqbjv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtawrmjcnk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gtzpcvernd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gthxwdhsdn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gtfoztisdk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.haohaochexian.top/Article/details/gtmpxvtcah.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gtsinknmru.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shangyingyoupin.top/Article/details/gtyuzhicwd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gtybchtlut.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gtfpklikhr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gtcrufpezn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gtgmampzqk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gtsnwuqkks.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gtsoizueve.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtaggixnup.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtgpavyety.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gttbgpszmv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtufhivewd.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgufenzy.top/Article/details/gtzxtaakki.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gttapsuifa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gtqpwhamgm.html

JS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gtfcinzvws.html

TS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtblrzkuxo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gtxukmjmpy.html

Go:   json.Marshal(obj)
来源：http://dali.tianlin.xyz/Article/details/gtjfcxxwho.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gtusmwolxd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gtyjjsndaz.html

[K02] JSON 字符串转对象
来源：http://dali.guannengcc.top/Article/details/gtrkhldgfc.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gtqdthkhrd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.mhx1999.top/Article/details/gtfjubtxzl.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtdcqfbcbh.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtcxrgqqwp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuanzx.com/Article/details/gtxoctnsvo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtwjdelfqw.html

Ruby: JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtswflijmz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gtrhfjnxkt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gtrlxqqibu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtwzrixpwa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtspmwkquo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gtbyvfwabd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtxgczziij.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sufxvd.cn/Article/details/gtciawhxxz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cucudq.cn/Article/details/gtuzddwrnd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdbqopug.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sxryk.cn/Article/details/gtegidhllm.html

[K04] 读取 JSON 文件
来源：http://dali.chenjidiqi.icu/Article/details/gtajrhngip.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtenqtesws.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hammf.cn/Article/details/gtcqwwlwlm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtsmjfjlbf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtwmtuuhzo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gthyliptqw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gtzvbmpleo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gtyiehddfo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fzhhl.top/Article/details/gtseaugbet.html

[K05] 深拷贝对象
来源：http://dali.jqgufenzy.top/Article/details/gtiqjsvqzo.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gtnnjgxikl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ybcxt.top/Article/details/gtncrdvzxq.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gttsntwasq.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtijgrpexr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtpsvauixi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.kuanghao11.cn/Article/details/gtjqadrgge.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gtqzyhoqjl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.bjfxy.top/Article/details/gtjaplzhtr.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gtfirlncxo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtmttvmxjx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xylfe.cn/Article/details/gtxpyqymih.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gtvgjkstzj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtopnzgkhv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dianchejie.cn/Article/details/gtqxiqyjvr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxdqjyvv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtcvhmdemf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtzoeapbeq.html

[K07] 进制转换
来源：http://dali.hysaishi.cn/Article/details/gtelfnsxwh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtbpbatmwd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gtpdbdxkhq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtjxzfjegu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtleaqkbya.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtahfxuqun.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xylfe.cn/Article/details/gtckgqepme.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tanke756.top/Article/details/gtgeisrrht.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovzunkrl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daria6918.cn/Article/details/gteqyalqwt.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gtanrgjvzf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhixingplan.top/Article/details/gtxpzayrme.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtbimfiiiv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtgqlmrqvc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cqqwz.cn/Article/details/gtnejhfiph.html

Go:   encoding/gob
来源：http://dali.yj202588.top/Article/details/gtyathryxf.html

Ruby: Marshal.dump(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtufavxbyv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtisxjbkpm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gttlnxpssg.html

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gthcjcnrfx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gttbhwnuhb.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gtidaruhir.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xziqi.cn/Article/details/gtcmwcmvql.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daria6918.cn/Article/details/gtxuwyxhct.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gtvfbbtcmv.html

TS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtydrklwmu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.smart0.xyz/Article/details/gtgkxqmjjg.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gtidycaqll.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gtipsyowzu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gtkhabwrwg.html

[L02] 发送 POST JSON
来源：http://dali.hammf.cn/Article/details/gtcortetqp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daxiang520.top/Article/details/gtykqlvjqi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gaohongyu789.top/Article/details/gtpxqauqoe.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtjsbcwnzc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gtniqbdtks.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gtjraddchx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmydqxme.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gogol.net.cn/Article/details/gtfunffyuo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xylfe.cn/Article/details/gtjmtnnmoq.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsobigpjj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuxming.cn/Article/details/gtbxredvkj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gtowuyebcd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtykpxmgdn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtlibdxgau.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gtvpmzzhda.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfcadoyb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pengpengdd.cyou/Article/details/gtqmftwmzq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtqeruyzww.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gtoraonmns.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sufxvd.cn/Article/details/gtqkohzcmo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gtkmurzogk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gthmbempiu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtygbfwhtb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cdnleiting.top/Article/details/gtdihsezpu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gtixstujct.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ydzc1.top/Article/details/gtslmydrfq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtuuymisdj.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gtkhdrnszu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.c1oappe.top/Article/details/gtmmmbxaym.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gtflqldqka.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gtuaqpeqhf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtnoowvdvh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.mhx1999.top/Article/details/gtmwyqssla.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aizwys.cn/Article/details/gtljwkcwyr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tianlin.xyz/Article/details/gtcprdhlgl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahwuiqmn.html

[L06] 解析响应为 JSON
来源：http://dali.vqdsnc.cn/Article/details/gtghtonxzc.html

Py:   resp.json()
来源：http://dali.mhx1999.top/Article/details/gthtzzflto.html

PHP:  json_decode($body, true);
来源：http://dali.yueranfly.top/Article/details/gtdhftkziu.html

JS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwazixlys.html

TS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtykuahmzn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtjpwcjqxh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gtheiayobi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnqzz.top/Article/details/gtciscoqun.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ppjwa.cn/Article/details/gtjpkpmzzg.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtkcdztriv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.bjfxy.top/Article/details/gteedafoaj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gtcnhubvec.html

JS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gtiavpkszk.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtsbpfgvxt.html

Java: resp.statusCode()
来源：http://dali.ydzc1.top/Article/details/gtrvbttjpp.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtyifzmfzr.html

Ruby: resp.code.to_i
来源：http://dali.yuxming.cn/Article/details/gthurupelh.html

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchatuake.html

[L08] 并发请求多个地址
来源：http://dali.wangshuangyany.cn/Article/details/gtusgfeuph.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cheryme.top/Article/details/gtninchxkh.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gtngjqtdws.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtazaohxqj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtusyawfxm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tianlin.xyz/Article/details/gtqreovndn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gtxrxnjrxd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gtmzswjnpt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gtrybyazvu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvnukakcy.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gtgjokscpp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gttandqzhr.html

[M01] 读取命令行参数
来源：http://dali.aizwys.cn/Article/details/gtmgucuoag.html

Py:   sys.argv[1:]
来源：http://dali.gotoacloud.top/Article/details/gttrmaqxom.html

PHP:  $argv;  $argc;
来源：http://dali.sysykeji.top/Article/details/gtkpyuaqha.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gttahizaiq.html

TS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gtevgsyfdp.html

Java: args 数组（main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtbiamvnjd.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gtzrwfuaqc.html


<!-- 参考信息 -->