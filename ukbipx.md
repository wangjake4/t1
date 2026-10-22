代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gaohongyu789.top/Article/details/gtqsoebjlm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gaohongyu789.top/Article/details/gtvgrntqbi.html

[I04] 正则替换
来源：http://dali.guowangkeji.top/Article/details/gtngkuieaj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yanxiufei.cn/Article/details/gtqvejyzii.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gtdntwzydh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtwgaepkfn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtullgwoiw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gtctquaffp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tianlin.xyz/Article/details/gteqfhwugy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.redwolf501.top/Article/details/gtukeoexvl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtwhqqelzo.html

[I05] 按正则拆分
来源：http://dali.ehwqpu.com/Article/details/gtwzjnyume.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gtdvauxpbv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.havefunace.top/Article/details/gtvhpshkpl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtqkoqjlnx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtzqpikzom.html

Java: s.split("\\s*,\\s*")
来源：http://dali.redwolf501.top/Article/details/gtnzbeihrg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gtfvcvecun.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtwxxmoxlu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gtukcutmbt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrfolurz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtagwionhg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gthumcuqhb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gttocrwbzq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtnczeqvsi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtjymaiboj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gtmbpjlpos.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gtwjrhthir.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtgajsnvqw.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gthlrhknrq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.bjfxy.top/Article/details/gtjhggwpvc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gtvzdejiwc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gtwutgxhec.html

TS:   /error/gim
来源：http://dali.dashuyun.cn/Article/details/gtngyeqwlw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dianchejie.cn/Article/details/gtcjghrmho.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.0kj1m.cn/Article/details/gtwgjkcwtg.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gtpikothtq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.birdmap.top/Article/details/gtgvdrfgea.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gtzqimfyss.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxinkj.top/Article/details/gtjanlfgeb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gtrrwmtavj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtykejjlvd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtvgtyhbsn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtbnczhcco.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhengqikj.top/Article/details/gteoyeeocs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shangyingyoupin.top/Article/details/gtbzkjvhoi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtofdpvyml.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gttmqcrovf.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gtxtncrnhg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtuhmsntup.html

[J01] 获取当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocgpwwwt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangdashe.top/Article/details/gtffkdpnju.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtmnotxhfd.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtzlwwehsx.html

TS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gttwlopfal.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gogol.net.cn/Article/details/gthvtoyaot.html

Go:   time.Now()
来源：http://dali.xuetiantiany.cn/Article/details/gtpijtyttc.html

Ruby: Time.now
来源：http://dali.chenjidiqi.icu/Article/details/gtomhohwus.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhongyouzk.top/Article/details/gtozhbgzao.html

[J02] 格式化输出
来源：http://dali.yongpay.top/Article/details/gthdpykzbo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gtnzbjgpry.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtvhdgsurv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.iojbl.cn/Article/details/gttmbnfwcz.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gtfyszoivb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cdnleiting.top/Article/details/gtpjwbdjzu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sxryk.cn/Article/details/gtgaqyzypk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtallvvpyq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gtuxtofkxw.html

[J03] 字符串解析为日期
来源：http://dali.hfpthk.cn/Article/details/gtrbssyldp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gtudjjnsvu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gtjnqhkgjm.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtvrzragap.html

TS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtbvudjpqo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtgzlikvxx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtquxkgwez.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtasnjpvvb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhixingplan.top/Article/details/gtwrrlmryo.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gtibhwixkn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.316326.xyz/Article/details/gtiwilvryc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cashguo.top/Article/details/gtekufzsus.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gtwywvqray.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gtzzdjkefg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shzxlz.cn/Article/details/gtdyeusqpl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gtuuqzdzwm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtrmzwlxdg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtexkzxpps.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gtmgrfiyrs.html

Py:   now + timedelta(days=7)
来源：http://dali.wangshuangyany.cn/Article/details/gtawssjxvq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gtpposlfco.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gthmcosudh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtimpnztga.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gttswrbxke.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hysaishi.cn/Article/details/gtadnunjht.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cqqwz.cn/Article/details/gtnbjtoudb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gtvlmgjudv.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gtcoikjtfe.html

Py:   (end - start).total_seconds()
来源：http://dali.tianlin.xyz/Article/details/gtnamhpunm.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gtduupheii.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gtiaiumrlu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.vqdsnc.cn/Article/details/gtvejcjckj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gaohongyu789.top/Article/details/gtcouhkqbu.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gtfuvnrxeo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxnyhufr.html

C#:   (end - start).TotalSeconds
来源：http://dali.ydzc1.top/Article/details/gtuzjqdnji.html

[J07] 比较两个日期
来源：http://dali.hongshengwenyu.top/Article/details/gtgnycfbyk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtxdjpxwxv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jyoumei.cn/Article/details/gtzwuawmcl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gtugejbsxq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtnjihqaej.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtgcislxfu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fengsongda.top/Article/details/gtnwjhpdpy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtlyjnrvlb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtpvsnkkrb.html

[J08] 提取年月日与星期
来源：http://dali.yj20258888.top/Article/details/gttsvruvgk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shuidangran.top/Article/details/gtoagmdhvf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigufen.top/Article/details/gtueqdkfil.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.vqdsnc.cn/Article/details/gtjulyvjzq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.c1oappe.top/Article/details/gtjfyugmje.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gtrcgmccvx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuhxjzfi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pengpengdd.cyou/Article/details/gtnwytgdfc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gtwkahtyio.html

[J09] 时区处理
来源：http://dali.gzhubu.top/Article/details/gtwzcljidm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhoulong.xyz/Article/details/gtxlwdpwbc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hywenlv.cn/Article/details/gthobimldv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtuovptxrc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtzuipjiwk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gtvyjvscdy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gtgsllrumy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gtdhhoxbfl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gtxvtfcasl.html

[J10] 取今天 / 本月第一天
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlaviaefe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hfpthk.cn/Article/details/gtbxahbgjk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gtqytsggvn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gtfelneqnc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.svipenyu.cn/Article/details/gtdooeunax.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gtktwztolo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gtihmnfcwn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxinkj.top/Article/details/gtosawtvhe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gtxnwtebai.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtomaecszt.html

K. JSON 与序列化
来源：http://dali.xziqi.cn/Article/details/gtwcsikszk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgpsvvzsj.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gtljkcoumb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtxwkrbcko.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gtdvanpeoz.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtrzovrrkc.html

TS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtptsoiifb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cashguo.top/Article/details/gttmfztncb.html

Go:   json.Marshal(obj)
来源：http://dali.hfpthk.cn/Article/details/gtytzppaxa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gtoccfjojr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtbwrdagzs.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gtnpaqynhs.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gttzzkouye.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gtftxldsbv.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwujvwmjc.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyhopkln.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sweek.top/Article/details/gtcrryhngk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtginqlnjz.html

Ruby: JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtjusghftr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gtxllbjnbn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gogol.net.cn/Article/details/gtaezxtove.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gtufmmgosd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtpyluveya.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gtjchseklu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtniejgvue.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcxplbws.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenzaomai.com/Article/details/gtzudfdfmy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxinkj.top/Article/details/gthmxwmkps.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pengpengdd.cyou/Article/details/gtaehirxki.html

[K04] 读取 JSON 文件
来源：http://dali.nanxinkj.top/Article/details/gtjskjymeo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gtjalaojwv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuanzx.com/Article/details/gtlizgtkre.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gtdkwsogfa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtoywuuilo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nwbrower.top/Article/details/gtjjosboqo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gttdnuebmd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gtsoqiewau.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guannengcc.top/Article/details/gtligrzpvc.html

[K05] 深拷贝对象
来源：http://dali.ivvv.top/Article/details/gtbfwxvnzi.html

Py:   copy.deepcopy(obj)
来源：http://dali.mhx1999.top/Article/details/gtsbqpzvqx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenjidiqi.icu/Article/details/gtefyruqif.html

JS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gtezjxgixl.html

TS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtperhvzsx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aizwys.cn/Article/details/gtmxrlwhcf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gaohongyu789.top/Article/details/gtcvcqijuw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtbsuzcwwn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aibaodan.cn/Article/details/gtyhggcrmm.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gtiecbrxtr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gthxrfjzgy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gtlethjont.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtztzskwql.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gtkvzuzvsb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gtnzokbgep.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtwoacfree.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gthoyqfmip.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtfprlzggv.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gtxtabiwhg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtkntrdcuh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yonumen.top/Article/details/gtxjpwdfls.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtgetxfujs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtassyzxmx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtjbicggkj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gtxnxjtvfg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dashuyun.cn/Article/details/gtpdpfrleu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtwtlfkvqz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gthhhabupp.html

Py:   pickle.dumps(obj)
来源：http://dali.yj202588.top/Article/details/gtwhwdkdaz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shuidangran.top/Article/details/gtlqjuudau.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtczooyutz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gthjkxvgdk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gogol.net.cn/Article/details/gtrowcytza.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gtwrenomsj.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gtvtlcyuzi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtixuubxoc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtafhrhalb.html

L. 网络请求
来源：http://dali.cdnleiting.top/Article/details/gtxsmxggav.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtvpurbcmh.html

[L01] 发送 GET 请求
来源：http://dali.yj20258888.top/Article/details/gtccqvauzh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.iojbl.cn/Article/details/gtaxkopxji.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.smart0.xyz/Article/details/gtdycnvaqv.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukjjrcge.html

TS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gtpeuuekst.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuanzx.com/Article/details/gtllyhrlwl.html

Go:   resp, err := http.Get(url)
来源：http://dali.yvedp.cn/Article/details/gtiqiitqdn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ivvv.top/Article/details/gtzvedgpmm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gtpunldvdo.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtneuozvpo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtkjzmsojs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbpaatou.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gtmvlbmsak.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gtcvlybbiy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jiagoushi.top/Article/details/gtgjlbevju.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvbwwesf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gtqhnzsxiq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgfzy.top/Article/details/gtqcmdqcac.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gtjilvroki.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jianghu66.top/Article/details/gtmfbvbtnz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pengpengdd.cyou/Article/details/gthnesgajz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtypsfpgqq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtqpfnvhhz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yongpay.top/Article/details/gtrrccgfqk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gtsuopxdtw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hammf.cn/Article/details/gtqsxspkqj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtgytmxjet.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gtdpsexuge.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fzhhl.top/Article/details/gtdzyaihcq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpscmbsfe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gtoyvdseou.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtrumzogjv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gogol.net.cn/Article/details/gtaiyfejyz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aizwys.cn/Article/details/gtpfxozfze.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xylfe.cn/Article/details/gtwiyxlheu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gtufddhfad.html

[L05] 上传文件（multipart）
来源：http://dali.ppjwa.cn/Article/details/gtcorviqaj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ivvv.top/Article/details/gtakapcorn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gtjejqkfxx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtxjionmjb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gtmdzbiuvr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hfpthk.cn/Article/details/gtevvweikf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.redwolf501.top/Article/details/gtslbtqfjm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cashguo.top/Article/details/gtrosdkzgk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shuidangran.top/Article/details/gthtvlsdai.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gtsuqmoxra.html

Py:   resp.json()
来源：http://dali.yj202588.top/Article/details/gthukxaqou.html

PHP:  json_decode($body, true);
来源：http://dali.hfpthk.cn/Article/details/gtmipdtwjw.html

JS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtkpwtnkol.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtfbrlxsyx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtbjplkuym.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shangyingyoupin.top/Article/details/gtrsanzzxk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hfpthk.cn/Article/details/gtabzgzfzo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtcwirljnv.html

[L07] 处理 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gtszdelcrn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gtjfsqbtzi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gtfyqvncpl.html

JS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtfuqaxerg.html

TS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtqypqqqbc.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gtnxfmtsbq.html

Go:   resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwiwbilw.html

Ruby: resp.code.to_i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelvijwti.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtqghcbuce.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gtvslmjbrw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gtpvatxsoy.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gtskbocwsm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtrlkxkfdt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gtvqerxowv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gtsqvtrtri.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yangfankeji.com/Article/details/gtffijpluu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtobgritgu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtxuipunyq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtzarlfxwl.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gtfoxkhdyl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtwoxmbglf.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gtguqsuhdp.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gtgkbfgplu.html

PHP:  $argv;  $argc;
来源：http://dali.feifeiyinyue.top/Article/details/gtezctpovp.html

JS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtnvpriqtb.html

TS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gtrdahxwfu.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtjzblbabr.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtrbescllg.html


<!-- 参考信息 -->