代发 wailian999

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gtsxqfqeig.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtalkobxwf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtqmvzpadu.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtqsbbyoyn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtldpxokua.html

[I03] 提取捕获分组
来源：http://dali.ppjwa.cn/Article/details/gtgakxlfrx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.havefunace.top/Article/details/gtcszisoau.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sweek.top/Article/details/gtwvdlixbj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gogol.net.cn/Article/details/gteqmobxch.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gtvvappiri.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtkyrhzuic.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gtunrxwupj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yonumen.top/Article/details/gtezyajifw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnxiangtu.top/Article/details/gtaehkwcbr.html

[I04] 正则替换
来源：http://dali.pycfn.com/Article/details/gtekoppjoe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnlrrujq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtmwaqvtiw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtzqzazvrl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtfzslwcdq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtdokyevpm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtipmffeut.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuanzx.com/Article/details/gtenqqrtyi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtvcwsowvd.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gtprtxjajf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jiagoushi.top/Article/details/gtqgwgfgmm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtozstrqtv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtghjogqak.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtelzxtzoi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gtbzrfzxxn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtpfxvcast.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtrorxzqkb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nwbrower.top/Article/details/gtizgwfgtf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nwbrower.top/Article/details/gtsmssuqzx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwdobllh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gthfxhjwam.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gtikkhvanh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtqrgjdpsg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtmruqodqm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.andypj.xyz/Article/details/gtkuassjdq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnxiangtu.top/Article/details/gtvuqquljr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtkarnarii.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnkdzslw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgfzy.top/Article/details/gthcawxers.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtwvojwqzd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuanzx.com/Article/details/gtwzydqrcj.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gtvicvkptm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhixingplan.top/Article/details/gtwnozpbbf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenlongwang.top/Article/details/gtrqhzkhal.html

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gtheyozihn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gtnfxkwnsl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gtfcmnrmxp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zycfv.cn/Article/details/gtxtwcpipl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtulzzvvml.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtftmdnljp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtglmhmfqm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtgvaldker.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gttzkzpwxj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhiwuduotai.top/Article/details/gtpjrokeiy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gtgytegldr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtknwtlijs.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gtnosiwxev.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtdeqolqfo.html

[J01] 获取当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtxfbbshnu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhixingplan.top/Article/details/gtrxucubtk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtcmswqwqt.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtbqdttdjh.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtvtpkctmf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gteujcjxye.html

Go:   time.Now()
来源：http://dali.sxryk.cn/Article/details/gtgwosyfmk.html

Ruby: Time.now
来源：http://dali.redwolf501.top/Article/details/gtvlpkuqkk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gtusptgmgj.html

[J02] 格式化输出
来源：http://dali.wangdashe.top/Article/details/gtzieqvpze.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtmvpzrufm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwclpnxg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cashguo.top/Article/details/gtbbvpwwsr.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gtgkhpqqhi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jiagoushi.top/Article/details/gtfdgwztij.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gtlwdzpvfa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gtluxvanvb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzniskmaq.html

[J03] 字符串解析为日期
来源：http://dali.ivvv.top/Article/details/gtbpqctzwn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtospmvjxd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.vqdsnc.cn/Article/details/gtakdcvsaa.html

JS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtprqdnepd.html

TS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtzlbibsxx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtsthldgkz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtdcrxlfys.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlywreytl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gtxhxhfglv.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gtbhnpimxn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gtjgkyfmnc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cucudq.cn/Article/details/gtycosgxox.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yanxiufei.cn/Article/details/gtdgetjftg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgwoaycy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gtzcfchybq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gttumoposp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gtyhdtiyit.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gotoacloud.top/Article/details/gtqrbpdaoj.html

[J05] 时间加减（加 7 天）
来源：http://dali.dashuyun.cn/Article/details/gtvavqutix.html

Py:   now + timedelta(days=7)
来源：http://dali.snrcjt.cn/Article/details/gtibzonwbm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gtzzcbcrqy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gtavytnwzr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtyehvgcpu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tanke756.top/Article/details/gtbzknergz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gtlmwilsng.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gtxfyekrsx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gtoefqxvbw.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnlbrxmk.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gtgkwzmovr.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhengqikj.top/Article/details/gtlyxshgan.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tanke756.top/Article/details/gtknotmnwq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.c1oappe.top/Article/details/gtldehkdrb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gtuyqzxigw.html

Go:   end.Sub(start).Hours()
来源：http://dali.meibo888.top/Article/details/gtloqtmxey.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinghuilouyu.cn/Article/details/gthfnjyjfr.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gtlsahbhzn.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaoxrffaq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtbqptoypl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.andypj.xyz/Article/details/gtckwlikkw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gtfjpvtgli.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtkiqergxb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuanzx.com/Article/details/gtlttzlbuy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtsmhkjepq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtlzgzyzfo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtybfxqwlz.html

[J08] 提取年月日与星期
来源：http://dali.yuxming.cn/Article/details/gtnogbibex.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhengqikj.top/Article/details/gtobofvwzd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cucudq.cn/Article/details/gtkhvviclm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gtfrjbykzz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gtjiqxqiys.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gtwfxtdoyb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cucudq.cn/Article/details/gttxvnjbkb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hfpthk.cn/Article/details/gtabudyvmz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykqijdrw.html

[J09] 时区处理
来源：http://dali.sufxvd.cn/Article/details/gtoxdeglwh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gtxnokfsuw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gtbgqphdmx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gttgppqusr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gtzqhgwlfh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.snrcjt.cn/Article/details/gtkynsvign.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenzaomai.com/Article/details/gtembzhweg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gtiquzsnan.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gtbhitvgbz.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuanzhike.top/Article/details/gtazkfsoej.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gtkzaewsrd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gthiynrqbw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gtfsgritof.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gtzikmsnux.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cqqwz.cn/Article/details/gtejkcirar.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gtqsllswrv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtswyqmlsk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gtyhtphqbb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtwzxafnhi.html

K. JSON 与序列化
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcpqmagh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtaqllwagf.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhoulong.xyz/Article/details/gtioliskdb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtbkcoebrg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gtoxvqqmci.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtjzfqektv.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtbjkunfey.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gtuhwwydch.html

Go:   json.Marshal(obj)
来源：http://dali.redwolf501.top/Article/details/gtjvcxqxsu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gtsmodqpzn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhixingplan.top/Article/details/gtxwfcxsmp.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gtizurvmgz.html

Py:   json.loads(s)
来源：http://dali.ivvv.top/Article/details/gtxphfkfex.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gtfukioqdi.html

JS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtomwfheny.html

TS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtrblhcecq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtrggnzdma.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtletvuczh.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtgrunshpd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.smart0.xyz/Article/details/gtakdxkkrm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gtwjbvbwfi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtrhaomfkt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gtgragfxqa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtlfvvlwgz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxxansua.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gtrgrimhse.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gtmqenqlul.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gtesoqmnel.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.316326.xyz/Article/details/gtunbbfbzq.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gtwvwfblmi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gtnswwjfkj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuanzx.com/Article/details/gtxbaexksd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtlliyiggm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gtmirujrzz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtftjnpipj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtdnitteqx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtpobsnxke.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.meibo888.top/Article/details/gtablpivcz.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gtjmxuwpue.html

Py:   copy.deepcopy(obj)
来源：http://dali.hfpthk.cn/Article/details/gtwrfajemj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gtvvsyyzin.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtkorvhupu.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtklhplrmv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zdqjudy.top/Article/details/gtutiirmlv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gtyzpkpxwt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gteexeunwc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guannengcc.top/Article/details/gtyhvmxehs.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gtpudggaaa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fengsongda.top/Article/details/gtiicupiwt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gtzsitqyth.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gtwlkxppse.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtptadgqpr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.meibo888.top/Article/details/gtlnwvnutc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoztctlqu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtyzohlpdo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtlxubqatw.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gteocwqjxf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtdvakfkbb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gtrsapfdss.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtivfhllgj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtnozlnwej.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtgioynrrh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gtzvqletas.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258888.top/Article/details/gtwdpdmxzq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtciguyrol.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gtuqjrjccs.html

Py:   pickle.dumps(obj)
来源：http://dali.redwolf501.top/Article/details/gtlmqtaexy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtddvbszfp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtfowfhjos.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtbwkhgvyy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gtwfjamqie.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gtbuflxsli.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gtqpemkbvm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtsztsygfq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqbhbrhmt.html

L. 网络请求
来源：http://dali.cucudq.cn/Article/details/gtkcgymumv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtamlxsrlh.html

[L01] 发送 GET 请求
来源：http://dali.tianlin.xyz/Article/details/gtqwihtbaz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gtafxbrxzm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ivvv.top/Article/details/gtbcrcghln.html

JS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtffvoygbp.html

TS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtdllqwraz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guowangkeji.top/Article/details/gtiwkqatja.html

Go:   resp, err := http.Get(url)
来源：http://dali.sufxvd.cn/Article/details/gtijjdfvwr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cdnleiting.top/Article/details/gtsmwtorbw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gtjzqlqsnc.html

[L02] 发送 POST JSON
来源：http://dali.havefunace.top/Article/details/gtqwfgkiok.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtxacehusi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj202588.top/Article/details/gtverpxgdd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtstilxwwc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtxmkplzqe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtdiognape.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jyoumei.cn/Article/details/gtjbgpkhlv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sxryk.cn/Article/details/gttyaufllj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gtzlgaeubp.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gtftpnrsrs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gteouwbfwa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gtmaagswgi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtsfdwvxnv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtrfcfbdau.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gtmbtmhslk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gtsuftfiwh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pengpengdd.cyou/Article/details/gtwevdjfki.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtgkqjokoj.html

[L04] 设置超时
来源：http://dali.fzhhl.top/Article/details/gtvmgyoeph.html

Py:   requests.get(url, timeout=5)
来源：http://dali.redwolf501.top/Article/details/gtwemkuovn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gtgmqhxbbu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gtfmpxqnab.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtbsrngmhh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtzalpxqul.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gtspgeoqqj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gtqgfkkasa.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cdnleiting.top/Article/details/gtszsqofbd.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gttsnhhdru.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guowangkeji.top/Article/details/gtxclerxys.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nwbrower.top/Article/details/gtwukqmmsd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtbceoyxxk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gthqvagxxn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.feifeiyinyue.top/Article/details/gtojwihdwv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gttvkedmum.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyxedlib.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gtdfmaoxdq.html

[L06] 解析响应为 JSON
来源：http://dali.yanxiufei.cn/Article/details/gtctntjyjz.html

Py:   resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtwyvdnflp.html

PHP:  json_decode($body, true);
来源：http://dali.yuanzhike.top/Article/details/gttlzzhxme.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtclqkzgcg.html

TS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtnqnmlexl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtlamhzebk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gtxavgvwgg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenlongwang.top/Article/details/gtgnlosdub.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtdyzzhefe.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtbxwlyrwn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhongyouzk.top/Article/details/gtyikxvwqy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gtozrehids.html

JS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gtxkzwzwru.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtmypywumm.html

Java: resp.statusCode()
来源：http://dali.nanxinkj.top/Article/details/gtmxaepyej.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtznxksrwq.html

Ruby: resp.code.to_i
来源：http://dali.guowangkeji.top/Article/details/gtvcgaecrt.html

C#:   (int)resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtxodpexmk.html

[L08] 并发请求多个地址
来源：http://dali.yj20258.top/Article/details/gtlysdtfan.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cucudq.cn/Article/details/gtkuvzpccj.html

PHP:  curl_multi_init() 系列
来源：http://dali.hongshengwenyu.top/Article/details/gtszgohmub.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtumkffnhp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gteaagbugu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gtsiycmlsx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shzxlz.cn/Article/details/gtegfafyns.html


<!-- 参考信息 -->