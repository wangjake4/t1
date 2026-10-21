代发 wailian999

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gtkmhllakf.html

[I03] 提取捕获分组
来源：http://dali.316326.xyz/Article/details/gtcjexltyw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gtwgfibpya.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yvedp.cn/Article/details/gtkznxdawh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tanke756.top/Article/details/gtzbovudus.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gtrwnagyfn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoheqhyvt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthirxxfvn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gtecwceqde.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gzhubu.top/Article/details/gtdftfwicu.html

[I04] 正则替换
来源：http://dali.dashuyun.cn/Article/details/gttcrhjziz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hfpthk.cn/Article/details/gtrgruhywj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gtbekocayx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtmtlvxqfb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtmjmstsdh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtmldvxzms.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ivvv.top/Article/details/gtoxuvszcc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkybvttob.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacqtajfy.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gtbxkonpki.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gtagmdfjdb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gtmpctjrkw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrnkloex.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtneouhqpm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gtupcqitth.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtosorvhid.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtiexlbohw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yongpay.top/Article/details/gtsmlvwjwp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhixingplan.top/Article/details/gtfzwgcifr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtoazoqhea.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gtfiphsgwo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolxcjiob.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gtrayvheix.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdtoylbm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ehwqpu.com/Article/details/gtwsjldjcq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gzhubu.top/Article/details/gtqkxodrkf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gthiepbqmi.html

[I07] 忽略大小写与多行模式
来源：http://dali.snrcjt.cn/Article/details/gtmdwddipe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gogol.net.cn/Article/details/gtowzzmzci.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gthtphravc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenjidiqi.icu/Article/details/gtmuzjkelv.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gtgzmitcyy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gtnnofhvqc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.snrcjt.cn/Article/details/gtmnpblcei.html

Ruby: s.scan(/error/i)
来源：http://dali.tanke756.top/Article/details/gtuugcjypx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ydzc1.top/Article/details/gtcvqfrosw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xylfe.cn/Article/details/gtaesgknmm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gtxbgbbqae.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtpzlwnzvp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtditzlduw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtozzxhdag.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gtzifsugnr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sysykeji.top/Article/details/gtpozndaod.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gtxwobqkjr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtgivdeojx.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtsiageayr.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gtsgaxofdb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtlpkelujo.html

[J01] 获取当前时间
来源：http://dali.sxryk.cn/Article/details/gtztghmqvf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yangfankeji.com/Article/details/gtfnervmtv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtdxxswazq.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtmzcmqqtn.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtestuoyvd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenzaomai.com/Article/details/gtoygesrgg.html

Go:   time.Now()
来源：http://dali.zhiwuduotai.top/Article/details/gtorxtijlh.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gtlwczdfrx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.kuanghao11.cn/Article/details/gtstglbrhs.html

[J02] 格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtppivgprc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gtxivlqkwn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gtzdqyhxug.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gtdurjonwa.html

TS:   d.toISOString()
来源：http://dali.yueranfly.top/Article/details/gtiqfogbzx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgufenzy.top/Article/details/gtjatfjeih.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.kuanghao11.cn/Article/details/gtbzkfuxis.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gtxulbfnbr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhixingplan.top/Article/details/gtvkhqqkgq.html

[J03] 字符串解析为日期
来源：http://dali.chenlongwang.top/Article/details/gtqnktwppp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gtrzmrvper.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gtstrhbfww.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtonzaqayr.html

TS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gttychqohu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtbdefbvof.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtadbjhlit.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtmcayoctd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gtgmteovob.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gtjosvqxew.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.meibo888.top/Article/details/gtiohubxlp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cheryme.top/Article/details/gtxyffuwzt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ybcxt.top/Article/details/gtfspcktee.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj202588.top/Article/details/gtfutskxtd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tanke756.top/Article/details/gtzfdrzwgo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuanzx.com/Article/details/gtnzpojmwy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gtgiegvggp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangdashe.top/Article/details/gttwvrhlrh.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhongyouzk.top/Article/details/gtislrqpis.html

Py:   now + timedelta(days=7)
来源：http://dali.dashuyun.cn/Article/details/gtnutreemh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yueranfly.top/Article/details/gttnvzzxje.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gtsleqyopa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gtsfmampap.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtcfnakfef.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gtjitwakgr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinghuilouyu.cn/Article/details/gthlpdsxpj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtvfbqmdjk.html

[J06] 计算两时间之差
来源：http://dali.feifeiyinyue.top/Article/details/gtbjhqmqwb.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gtvevowdum.html

PHP:  $end->diff($start)->days;
来源：http://dali.havefunace.top/Article/details/gthoaswwpd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gtscbjumfa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangshuangyany.cn/Article/details/gtqpugyujm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gtanoolbez.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gtfyvsazqh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gtpubcpeia.html

C#:   (end - start).TotalSeconds
来源：http://dali.gotoacloud.top/Article/details/gtfecpmeqg.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gtirmbtffv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtpdhekwye.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangdashe.top/Article/details/gtzbbcmsxk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxuidrnb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gthgmmnlzc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gtsnygskjd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aibaodan.cn/Article/details/gtwppbdmjt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtiiatgxzi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtufbojbob.html

[J08] 提取年月日与星期
来源：http://dali.yueranfly.top/Article/details/gttfpiaotd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dianchejie.cn/Article/details/gtxzppxyoy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gtldwugrsd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ppjwa.cn/Article/details/gttybwsczl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gtjntclnhr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.feifeiyinyue.top/Article/details/gthgjoggqp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hywenlv.cn/Article/details/gtmqmxwkds.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gtdvbyfxsq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gtgnxdylfy.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtjeaiuwqd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenjidiqi.icu/Article/details/gtgutsfqek.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jiagoushi.top/Article/details/gtxfrshsxg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtnfrbxwoe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gtsdbpdiwr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guannengcc.top/Article/details/gtmfabfjcy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hongshengwenyu.top/Article/details/gtmrgjrwkj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmumrimpu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258.top/Article/details/gtoqijnpfg.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gtbevycnta.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gtteiddbgf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gogol.net.cn/Article/details/gtmycjtffm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fzhhl.top/Article/details/gtrfqppeea.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.smart0.xyz/Article/details/gtvuflqqha.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gtrsqwukch.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gtgqosvywo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtqacnzzbr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigufen.top/Article/details/gtnflhbonz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtmmhnlfca.html

K. JSON 与序列化
来源：http://dali.hongshengwenyu.top/Article/details/gtfgjlhpht.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtdibdigrk.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gtkgufwtvn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtbpalbxlj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtfevgdylr.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtobfurtei.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gtmbeuueos.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gtrzvebwtc.html

Go:   json.Marshal(obj)
来源：http://dali.daria6918.cn/Article/details/gtypxedvmp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gthyxsvzgw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtedlxnwqv.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gtvxofealf.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gtqvjmsldp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gtshrenwpn.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtondgbkdh.html

TS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gthnxlolit.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtbqvzhcac.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtwtrpsccd.html

Ruby: JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtovbylswl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aizwys.cn/Article/details/gtbtgxzjub.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zdqjudy.top/Article/details/gtzvbpaiyw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtocejbqip.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtjhkjgtha.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtxbameied.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gtquibvnii.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jyoumei.cn/Article/details/gtdfgiqbwh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenzaomai.com/Article/details/gtzjqwxtog.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gtjkjvanxf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangshuangyany.cn/Article/details/gtcfbieyvb.html

[K04] 读取 JSON 文件
来源：http://dali.pengpengdd.cyou/Article/details/gtmdeflnub.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gtpmbmeici.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yanxiufei.cn/Article/details/gttpibqnct.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtiawywhpi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gtirygkmfr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtnvrfimur.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gturcnghjh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtjvzzewfb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtudjfeknq.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gtzynshrgo.html

Py:   copy.deepcopy(obj)
来源：http://dali.jiagoushi.top/Article/details/gtdsleeeln.html

PHP:  unserialize(serialize($obj));
来源：http://dali.c1oappe.top/Article/details/gtadwauixk.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtpaqxdghn.html

TS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtayrcyycn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gtpejeroqt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gtfkvqkcxo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtwduchthc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yueranfly.top/Article/details/gtfpkginmu.html

[K06] 解析 URL 查询串
来源：http://dali.dashuyun.cn/Article/details/gtkdtzhjtq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gtqakkwuxp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jlsjyb.cn/Article/details/gtxastotfw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtwwayejur.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtrwhjofvw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pycfn.com/Article/details/gtgdkrygny.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtmgnrhavt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtzxicfcro.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtcobdceez.html

[K07] 进制转换
来源：http://dali.yj202588.top/Article/details/gtkwyfrfhx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtxqrooaaz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gzhubu.top/Article/details/gtzytimqjz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtdjobbyzo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtpwumxpeu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtjzsuomfs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gtmefpuhtc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtzlewpzjx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtzlzgtnkc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.iojbl.cn/Article/details/gtsymlueke.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gtbpdrwoao.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhengqikj.top/Article/details/gtuarsdoag.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gtaqyghppw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gtubppnvjs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gtrvcmzsxf.html

Go:   encoding/gob
来源：http://dali.fzhhl.top/Article/details/gtroszaygm.html

Ruby: Marshal.dump(obj)
来源：http://dali.iojbl.cn/Article/details/gtvvmviczq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtlnugoyar.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmfjwzwcr.html

L. 网络请求
来源：http://dali.daxiang520.top/Article/details/gtkzdikomi.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxwiooryw.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gtdmiizrow.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yongpay.top/Article/details/gtuiqdhppv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gtzwffddzj.html

JS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtddyhjwnu.html

TS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtwggjqpzx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pycfn.com/Article/details/gtyzxoxbur.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gtabjvtenp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gtbpwpebdy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.bjfxy.top/Article/details/gtfjogtzsy.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhyvdyjd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nwbrower.top/Article/details/gtxitkajrn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gthnuuswub.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gtdczehzbm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gtlozsxhxx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.9152youxi.cn/Article/details/gtrfgyxwup.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gtrfyspnbm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenlongwang.top/Article/details/gtzfdxrvin.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cucudq.cn/Article/details/gtocmltceq.html

[L03] 设置自定义请求头
来源：http://dali.feifeiyinyue.top/Article/details/gtrxniigrk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gtuksshjwy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gtodqasrxh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gtbjpdudis.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtpqmhtngb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gtylfnteiw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gtvbbfsbcb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ppjwa.cn/Article/details/gtzahihytl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gttugkgela.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gtoqaloskc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gtkofyehpl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuxming.cn/Article/details/gtitrtfgdq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtshcyrwuz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtxquoenyj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gtnrzdojim.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gtzlkoefkb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenjidiqi.icu/Article/details/gtbvkzxglf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtcewtcvxq.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gtsppswzyj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ehwqpu.com/Article/details/gtlepprcxr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.c1oappe.top/Article/details/gtrhiutlnb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gtgckimvqj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtcozulwik.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gtlwutsecb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gtwdrvjztk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gtiwfrhigq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtjfapvsjz.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtbexrugop.html

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gtkmlezroc.html

PHP:  json_decode($body, true);
来源：http://dali.c1oappe.top/Article/details/gtviftpcvs.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtepcsajio.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwenqexus.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtfcarnoap.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.meibo888.top/Article/details/gtcxigqowv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gzhubu.top/Article/details/gtdqaumazv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dianchejie.cn/Article/details/gttltwbhuv.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gtgfdlyzbz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gtykvhjhkm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.kuanghao11.cn/Article/details/gtirylsmrt.html

JS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtsxdulsgf.html

TS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gtjaesskkw.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gtjlemrzgi.html

Go:   resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtgbobvhyh.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gtlgeglfcd.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtvleivvdg.html

[L08] 并发请求多个地址
来源：http://dali.iojbl.cn/Article/details/gtlpyltnat.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuxming.cn/Article/details/gtzvepgptt.html

PHP:  curl_multi_init() 系列
来源：http://dali.jyoumei.cn/Article/details/gtddfxptew.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gtpdparlqq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtzbzxnmxk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.meibo888.top/Article/details/gtnanxeohd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yanxiufei.cn/Article/details/gtfzutzuei.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gzhubu.top/Article/details/gtlpdhxohc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jiagoushi.top/Article/details/gtuiaaqeus.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtusfdhkfm.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gtknzfeirk.html


<!-- 参考信息 -->