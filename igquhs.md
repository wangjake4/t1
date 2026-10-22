代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sufxvd.cn/Article/details/gtytvzbtbl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gtwqmugbke.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gtuvtlkugh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gthyfsyqxv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtokubphru.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtghjwnomm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtlivsjlhg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtqnzgncrk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtvkzvwxro.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dashuyun.cn/Article/details/gtohueieoi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtgybwhjjh.html

[I05] 按正则拆分
来源：http://dali.sxryk.cn/Article/details/gtsqipsvsf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sweek.top/Article/details/gtpblltamm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jianghu66.top/Article/details/gtbsupveok.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtstriqeue.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtmqbcevrk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuanzx.com/Article/details/gtntidwszx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtncwbkkrn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtnxmirozl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gzhubu.top/Article/details/gtmgwwbkyp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gtzerljjla.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtoqwbnzjw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gtbbfdwpip.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gthszjjjld.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtehlyauvt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtlhhbunpg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jianghu66.top/Article/details/gtoluooypu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gteykyibqo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtmkfabptq.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhiwuduotai.top/Article/details/gtcldqgwkv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuanzhike.top/Article/details/gtruywxqik.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gtzvdpqjga.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhongyouzk.top/Article/details/gtrwfncqvy.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gtsiegvzwf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.svipenyu.cn/Article/details/gtlcrpmxxe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gtuthnoduo.html

Ruby: s.scan(/error/i)
来源：http://dali.ivvv.top/Article/details/gtdtwvqrzv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pengpengdd.cyou/Article/details/gtxsvcwzwy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.smart0.xyz/Article/details/gtjzoixzxn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gtqxpnionc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gtgprioyea.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtkpxbvdjp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gttwvfmbvz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gtslzmmfqy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sysykeji.top/Article/details/gtzzictquq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cucudq.cn/Article/details/gtmusouikc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtahucnlfl.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtnsspdnjo.html

J. 日期与时间
来源：http://dali.cqqwz.cn/Article/details/gtyuoxvbow.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtvpybfizv.html

[J01] 获取当前时间
来源：http://dali.birdmap.top/Article/details/gtdutmzimp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gtqvhheyjh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtqbgvzahp.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtgsrhjwrr.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gtbywtcjka.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxoskfarr.html

Go:   time.Now()
来源：http://dali.zhengqikj.top/Article/details/gteboybcmv.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gtsdfhvvyq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cashguo.top/Article/details/gtrpsahhxl.html

[J02] 格式化输出
来源：http://dali.hfpthk.cn/Article/details/gttjewhkjw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtbiydjigo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gtaqjmtlwk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhoulong.xyz/Article/details/gtbbdujhwx.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gtkbcksewc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zdqjudy.top/Article/details/gtqeigxdjy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cdnleiting.top/Article/details/gtqhzogwdi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtpitxoyij.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gtilczzqoa.html

[J03] 字符串解析为日期
来源：http://dali.ehwqpu.com/Article/details/gtilqhlcqx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gternbjvdz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guannengcc.top/Article/details/gtwztjktjs.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtqxchzbhd.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtnvqhgnyh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtmbqjtiew.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtqcrdnpfl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtniqnyquw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gtuvvvykjd.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gtlhbohuyy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtoqdslihr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sysykeji.top/Article/details/gtqebezhct.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gzhubu.top/Article/details/gtydgkyhyy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gtivaamvab.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gtuztcuqhc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gtyuitjicr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtkjphbuky.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tanke756.top/Article/details/gtgqaxcvjc.html

[J05] 时间加减（加 7 天）
来源：http://dali.cdnleiting.top/Article/details/gtxcyllkch.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigufen.top/Article/details/gtzagindqf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ybcxt.top/Article/details/gtnljmrrzq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtwwsgmiki.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtdqjvrmms.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.9152youxi.cn/Article/details/gthgtoxgqr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqglahkyi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gtudrqutxx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtztikgosi.html

[J06] 计算两时间之差
来源：http://dali.hysaishi.cn/Article/details/gtibeitgkn.html

Py:   (end - start).total_seconds()
来源：http://dali.tian-w.cn/Article/details/gtrwqorsll.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gtsijigaml.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gtorvpjjks.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluhbyvvb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.meibo888.top/Article/details/gtbgdunwvc.html

Go:   end.Sub(start).Hours()
来源：http://dali.zycfv.cn/Article/details/gtgljyvrpr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdjchaya.html

C#:   (end - start).TotalSeconds
来源：http://dali.pengpengdd.cyou/Article/details/gtrenctbai.html

[J07] 比较两个日期
来源：http://dali.cqqwz.cn/Article/details/gtcfhktncq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtnkiqbtiz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.haohaochexian.top/Article/details/gttrcykoql.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtpggksspl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gthunkbzxa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dianchejie.cn/Article/details/gtnfddrxvy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gtanonktfs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtnhqgkuwl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtsouulftn.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gtlmaonabc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gtmzuydwrp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gtfdnuhsfz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sufxvd.cn/Article/details/gtthpvqdjz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gttpbsvyqt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sxryk.cn/Article/details/gtlqzruqop.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gthdjvolfg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gtvuobrwxg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gtwijhanhf.html

[J09] 时区处理
来源：http://dali.pycfn.com/Article/details/gtgefajcuo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shangyingyoupin.top/Article/details/gtoqusgdfr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhiwuduotai.top/Article/details/gtxscvpelj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtzfvqguqn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtdugpabrb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gtdwegllms.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gtxaytxqoy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gtgqhluljb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gtklvaqice.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gtskydvyec.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gtarapjqnm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258888.top/Article/details/gtdnxkhlwd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gtxynzkliq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sxryk.cn/Article/details/gtuubksbka.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtyqxppieb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yongpay.top/Article/details/gtfcffyojp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gtuvacowpi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gtbgjdizom.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtjensguqe.html

K. JSON 与序列化
来源：http://dali.jlsjyb.cn/Article/details/gtxdnkvftb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtjcddhtbd.html

[K01] 对象转 JSON 字符串
来源：http://dali.gotoacloud.top/Article/details/gtwbzermpp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtdluclnpo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtqhisimea.html

JS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtijolwyeo.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtlmejjrnl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewgjtizg.html

Go:   json.Marshal(obj)
来源：http://dali.haohaochexian.top/Article/details/gtzmeeqqno.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.feifeiyinyue.top/Article/details/gtvvqutbaw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gtwufwvawd.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrithjir.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gtqlfygfig.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gtzcljkfrn.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtdywcgwhr.html

TS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtxkyyjwvs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nwbrower.top/Article/details/gtcotntdln.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gtwqsuqlrb.html

Ruby: JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtydsvwtiu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nwbrower.top/Article/details/gtgjlurepn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pengpengdd.cyou/Article/details/gtwxgrqwsq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtpkbgzdij.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gtrkcvtiza.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtzpatqclu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtdwopzvsj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.9152youxi.cn/Article/details/gtmmpvtxqg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guannengcc.top/Article/details/gtqzrwtrgl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gteopldkoj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuxming.cn/Article/details/gtqwvydisf.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbflhlpni.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gtmkaipsvb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fzhhl.top/Article/details/gtydoaoxzv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gtfwqkhcbg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtennjjdtq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrluqjjr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtppyusqvv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtvwdgxadg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtgxwjbrdh.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtibpatwjt.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gtobsnqcpf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yanxiufei.cn/Article/details/gtevkpcmzf.html

JS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtyhsiahvw.html

TS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtjpdvhwuo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtxkgthesm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.quarkkingdee.top/Article/details/gtqharfuef.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmvqubrn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gtmmvsdjhz.html

[K06] 解析 URL 查询串
来源：http://dali.hnqzz.top/Article/details/gtlvdqrzwl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtgzvugnwq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gtdlvawstj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbmdfaal.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtcqrwizzm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cashguo.top/Article/details/gtuybicmmg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtvyvifpjj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtlehdvqzx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtgwordete.html

[K07] 进制转换
来源：http://dali.gzhubu.top/Article/details/gtwhfzkhfm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtghqojcum.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gtqrasgvqe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtvfcpgowe.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtxkqolqfp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtvqrmnvmc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.svipenyu.cn/Article/details/gtqpzednax.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttslpvpmc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtzawktplj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yongpay.top/Article/details/gtvisvbibi.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gtrcqvfrzg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gtddfobrlt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtiaupkirf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gtvcsymqvy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gogol.net.cn/Article/details/gtlliefakx.html

Go:   encoding/gob
来源：http://dali.shzxlz.cn/Article/details/gthuntxcdb.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gtagjrcwun.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtxthskiws.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtyqexhxgu.html

L. 网络请求
来源：http://dali.yanxiufei.cn/Article/details/gtcrgmqiwc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtvfqtbsmy.html

[L01] 发送 GET 请求
来源：http://dali.vqdsnc.cn/Article/details/gtewvcliox.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pycfn.com/Article/details/gtknsppyaa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gaohongyu789.top/Article/details/gtgqwootcz.html

JS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gtefihutpo.html

TS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtcyiqexoe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvzvztvz.html

Go:   resp, err := http.Get(url)
来源：http://dali.mhx1999.top/Article/details/gtffzwkdfx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jlsjyb.cn/Article/details/gtepdjtigy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xinyue.icu/Article/details/gttsuqxcja.html

[L02] 发送 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gtavmzwgfp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtywwkcrxs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guowangkeji.top/Article/details/gthkewztwy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtprdtgsnp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gthhxdznvv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmhczqme.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gthnkqwbtx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsmukpat.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gtvnewfnph.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gtvkzseuxl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gtcdckbcrr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgufenzy.top/Article/details/gtwvbmkshe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtufpgqkrq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtpgqpdrop.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhongyouzk.top/Article/details/gtfqjozwwe.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtrldvtjxj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gtiidbjodt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gtbgzxqiko.html

[L04] 设置超时
来源：http://dali.cheryme.top/Article/details/gtnprrhpwa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gthomxfnfc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gtyvtjoveh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gttosinwyy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtbegzkcim.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sweek.top/Article/details/gtcanjsjzp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gttbtzwemc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yueranfly.top/Article/details/gtsbacdmgf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xylfe.cn/Article/details/gtgjhqmhyu.html

[L05] 上传文件（multipart）
来源：http://dali.zycfv.cn/Article/details/gtfjfosznl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xziqi.cn/Article/details/gttrlmolmt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthiizfxsd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtoeiipzau.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtrngkewul.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yongpay.top/Article/details/gtwdbjyjba.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xinyue.icu/Article/details/gtorjkjylt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gtxmdkpfbx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtkjlajnmu.html

[L06] 解析响应为 JSON
来源：http://dali.jqgufenzy.top/Article/details/gtomuxmdub.html

Py:   resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtckyeemqg.html

PHP:  json_decode($body, true);
来源：http://dali.vqdsnc.cn/Article/details/gtawkrzctc.html

JS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtlhvruwjz.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtjwbbvvii.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtfwdpknut.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gtyrpiqbrw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gtxhhsntjc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtmrcbnzft.html

[L07] 处理 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtqoyxmptv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yangfankeji.com/Article/details/gthmhjoxyr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.snrcjt.cn/Article/details/gtzamuvtdh.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gtwlsoqqdq.html

TS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtayicfbqc.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gtfntceaci.html

Go:   resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtqampekuk.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfnomwxh.html

C#:   (int)resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtzxbnruyv.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gtpejoqjnv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuxming.cn/Article/details/gtweeuolsm.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gtfcgylwgh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtpuiefrac.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gttenobqup.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.bjfxy.top/Article/details/gtsgymydnh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.quarkkingdee.top/Article/details/gtvvffhmuo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gtkopjsqug.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtsbbwsrdi.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtdlmzalpo.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangshuangyany.cn/Article/details/gtubjnybet.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtsqivifid.html

[M01] 读取命令行参数
来源：http://dali.yuanzhike.top/Article/details/gtizpieqhb.html

Py:   sys.argv[1:]
来源：http://dali.jyoumei.cn/Article/details/gtyyrodpnm.html

PHP:  $argv;  $argc;
来源：http://dali.birdmap.top/Article/details/gtbfulvvyq.html

JS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gtxldzyrfq.html

TS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gtplmluihi.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinwlqsse.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtulocdlcy.html


<!-- 参考信息 -->