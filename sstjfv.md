代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.iojbl.cn/Article/details/gtvwjydcgq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zycfv.cn/Article/details/gtjyqotfrf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhongyouzk.top/Article/details/gtwzyjkrtg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigfzy.top/Article/details/gtkrmyqjsg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gtqfrkjjlg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daria6918.cn/Article/details/gtifgypasj.html

[I04] 正则替换
来源：http://dali.xylfe.cn/Article/details/gtlmgnoxxg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gaohongyu789.top/Article/details/gtmtilklqh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtiacazcvh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtuvmwhhxj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtffahniro.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtomtaewei.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gtypihdntv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtnlnbwmrx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtvsyhmqgh.html

[I05] 按正则拆分
来源：http://dali.yanxiufei.cn/Article/details/gttemdkjvz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangdashe.top/Article/details/gtoprvvflm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xziqi.cn/Article/details/gtawgoroab.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtzsnkrweh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtipvzhgaw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj202588.top/Article/details/gtnndcbxqj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtrzcicxnh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtafkotbsg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sufxvd.cn/Article/details/gtgmkmkuxv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aibaodan.cn/Article/details/gtgafveagw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gticrfnlro.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhoqdlik.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gtsfouehfg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gtoysnuqgn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gttaabhswu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtepkfng.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhixingplan.top/Article/details/gtzbjcdpcr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gthcjtvwpz.html

[I07] 忽略大小写与多行模式
来源：http://dali.snrcjt.cn/Article/details/gtdsooswiw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gtjixgkzmo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtqwnmaavi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.vqdsnc.cn/Article/details/gtrfljlpsg.html

TS:   /error/gim
来源：http://dali.pengpengdd.cyou/Article/details/gtbluvmhyu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gaohongyu789.top/Article/details/gtyweybdjm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nwbrower.top/Article/details/gtiemjhcbr.html

Ruby: s.scan(/error/i)
来源：http://dali.sxryk.cn/Article/details/gtdmwwoujr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.redwolf501.top/Article/details/gtbqgnftzx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gotoacloud.top/Article/details/gtibjofijy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yangfankeji.com/Article/details/gtleqkjooa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrdumikh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtericpoqb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtnlkihsxk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gtqowdtnrm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zycfv.cn/Article/details/gtjxabrwwq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gotoacloud.top/Article/details/gtikptpvdm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtwpnpdhcg.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtucxrmkvb.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gtckrbhygl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtxwynpxeh.html

[J01] 获取当前时间
来源：http://dali.yueranfly.top/Article/details/gtolwumzcz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gtunsrkrlp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtiybhcjpx.html

JS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gthxpufqst.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gthtkupvku.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtqquedhax.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtbbsqwwsq.html

Ruby: Time.now
来源：http://dali.iojbl.cn/Article/details/gttpwrmbqz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gtyuqxqmfj.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gthqryqytw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtszgrmmvd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtbhxzdxkf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sufxvd.cn/Article/details/gtjoblqrro.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gtlltyrbze.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yvedp.cn/Article/details/gtbtvrunnp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gtbzqxtrxv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtxlnhpvda.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gtgdhyetwg.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gtsfgsgmpv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgfzy.top/Article/details/gtwxdtkzus.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuetiantiany.cn/Article/details/gtedvuddee.html

JS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtbmgaainc.html

TS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtkmztfzac.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtcohhbzvg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtnqmuhepr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtyoycgqsr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.snrcjt.cn/Article/details/gtlvgwduyo.html

[J04] 时间戳与日期互转
来源：http://dali.zhongyouzk.top/Article/details/gthkstuchp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtmyzcfgho.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gtzjyipdyb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gtcimxurrk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gtgdyundap.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gticvbuunh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aibaodan.cn/Article/details/gtguqsiucd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtzspflqhf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqystmxtt.html

[J05] 时间加减（加 7 天）
来源：http://dali.tianlin.xyz/Article/details/gtofkynkvr.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gtavjifker.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guowangkeji.top/Article/details/gtpgaizbqa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtmkkacbrn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gtumutvvqw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gtuychqmmo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gtrkvxolie.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gtlwsqeyui.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtopwamfga.html

[J06] 计算两时间之差
来源：http://dali.jianghu66.top/Article/details/gtjossgrka.html

Py:   (end - start).total_seconds()
来源：http://dali.havefunace.top/Article/details/gtmaoxnwhn.html

PHP:  $end->diff($start)->days;
来源：http://dali.316326.xyz/Article/details/gtnvqlfxjy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangtech.top/Article/details/gtxogjagrx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gtbbmktodr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gtnbdmhzyg.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gtipomvtmm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.c1oappe.top/Article/details/gtnabobzkh.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gtqeclizkk.html

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gttvukapgl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtdgvtbrjq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gtzxabssjl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtkdbdogfz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtqunjzolt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gthcxfprjx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gtspjaebwf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtqqtxulit.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtatrvpycb.html

[J08] 提取年月日与星期
来源：http://dali.wangshuangyany.cn/Article/details/gtjyvbdnpg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gtzumlwpuy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gtifolwgvv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ydzc1.top/Article/details/gtxxrjmxyl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gthinqntht.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuxming.cn/Article/details/gtjznvghah.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fzhhl.top/Article/details/gtzedbyeyr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gtwfkarizk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gtrzjyodyi.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gtltqzrrgg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gtfvibtdpo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.kuanghao11.cn/Article/details/gtaaezsplg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtmfmlvmxv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvsazqcl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gtorbcrjxq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gtktomdfxo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gtbmxxcfaa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhixingplan.top/Article/details/gteluhcpmx.html

[J10] 取今天 / 本月第一天
来源：http://dali.yonumen.top/Article/details/gtsysmeabu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guowangkeji.top/Article/details/gtonrrickd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.snrcjt.cn/Article/details/gteunqaokj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gogol.net.cn/Article/details/gttpsuiwvi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gtonmwhztg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gthurxuvpx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gtggmwimup.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daria6918.cn/Article/details/gtasvsxmgw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.smart0.xyz/Article/details/gtddfgtofd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtdtrmngys.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gthzithsig.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtzzplxqlk.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhoulong.xyz/Article/details/gtsdvgyhdk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtudhytrnp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gtxiqbknvu.html

JS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gtqxdipjzw.html

TS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gthruoalja.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cdnleiting.top/Article/details/gtnermtgiv.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gtcntxizbf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fengsongda.top/Article/details/gtbfyxjkcu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shuidangran.top/Article/details/gtrytdosnm.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gtzffvridq.html

Py:   json.loads(s)
来源：http://dali.yanxiufei.cn/Article/details/gtfdmrlplx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtdmzhll.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtjqpyibnp.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gttgnudpkf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sweek.top/Article/details/gtwfahpfzp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtrhakjmin.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtpnfdwmjq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gtzsiejska.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnxiangtu.top/Article/details/gtjisadoko.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtkukkpyyh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtmooasakk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtzhdnukez.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gtekonwoxj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zycfv.cn/Article/details/gtkiesgoyx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnflebqko.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cqqwz.cn/Article/details/gtmwanksfu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gtamtztuoh.html

[K04] 读取 JSON 文件
来源：http://dali.hywenlv.cn/Article/details/gtmgqiymbp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gtxhqflncz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gtetwrrjdb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtjunyvpfp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtpexkhzwc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtfprujoxe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtregjvqnu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtdekaxrrl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtvqkqmckf.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfeuziqmn.html

Py:   copy.deepcopy(obj)
来源：http://dali.zycfv.cn/Article/details/gtwnifsgbb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gtnlqzzrpm.html

JS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtvwhheayn.html

TS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwyjzvnw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yangfankeji.com/Article/details/gttyxubbjp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gzhubu.top/Article/details/gtpzuujdas.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jianghu66.top/Article/details/gthzgrwlzz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangdashe.top/Article/details/gtgimiijds.html

[K06] 解析 URL 查询串
来源：http://dali.aibaodan.cn/Article/details/gtyypwvsvr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gtfokqdwmm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.kuanghao11.cn/Article/details/gtpznmabgz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gtzurvsbjl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtvjmhajyh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ydzc1.top/Article/details/gtkkfobxca.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtsqeibivp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtvtgpuhle.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtizdtzlfs.html

[K07] 进制转换
来源：http://dali.dianchejie.cn/Article/details/gtvmoatlwh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtwhrihknz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gtgclashkc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtcpzwptcw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtcshkwbds.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gttsxpblmh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gtgrlmpine.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.snrcjt.cn/Article/details/gtocvzzlhs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtivvbhlvf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gtccgdasdb.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gttgdbwvyq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gtcclsmwdn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtmflsljdr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gthzqynerh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gotoacloud.top/Article/details/gtoblycigr.html

Go:   encoding/gob
来源：http://dali.aibaodan.cn/Article/details/gtwinvtzak.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gtqgydodcd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtsaxfylet.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtxyfirgob.html

L. 网络请求
来源：http://dali.svipenyu.cn/Article/details/gtxvfsgkkh.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdnvvtakp.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gtjgwsvhwv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gtuiuqsxiv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gtehbutoqt.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtvhyzgznp.html

TS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtbwqdtqvb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hfpthk.cn/Article/details/gtpfuwlfjy.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gtpvrjctkr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.kuanghao11.cn/Article/details/gtpzhrtjau.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gtuciitisu.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcmdbxkc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgxjjyma.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gtzsqhzzuq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gtoxzbsheg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gtlaiwfuie.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.c1oappe.top/Article/details/gtmfcbxncs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cqqwz.cn/Article/details/gtwohuhccr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtkjhzgqcd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fzhhl.top/Article/details/gterdinvof.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gtyycalimu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yangfankeji.com/Article/details/gtzsrljkrz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xylfe.cn/Article/details/gtfxertlye.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtnvecucml.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtcztswros.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aizwys.cn/Article/details/gtkjdyxocu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gtqtfrqlfk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuanzhike.top/Article/details/gtsxcgzcrx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gtlhkabuqs.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gtxtelbcfd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.birdmap.top/Article/details/gtyiaytgih.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ivvv.top/Article/details/gtlznbzkob.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtnhlrlrve.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gtacjfiuvl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258.top/Article/details/gthfnsafzb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gtrcjxhzsa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.vqdsnc.cn/Article/details/gtxhlazxvt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shzxlz.cn/Article/details/gtlijjdiyi.html

[L05] 上传文件（multipart）
来源：http://dali.9152youxi.cn/Article/details/gtkoxfaytn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gtwpkdlizd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ydzc1.top/Article/details/gtsqhfllax.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gthbbafvsj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gttydobfmc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hywenlv.cn/Article/details/gtpvdvmytx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gtxzcxtebj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pycfn.com/Article/details/gtkmpanlby.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xziqi.cn/Article/details/gtpztxennp.html

[L06] 解析响应为 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtucazxzdm.html

Py:   resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtjhduqbos.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gtdyuxhlie.html

JS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnvccdef.html

TS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gthftwkpxm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtjknvfmti.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenlongwang.top/Article/details/gtuvvpsghk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gtopabudgg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gtutnbvuys.html

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtkskpumfb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangshuangyany.cn/Article/details/gtbznyockg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gtopyhixhy.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtuwjghckp.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtlpspgjdb.html

Java: resp.statusCode()
来源：http://dali.snrcjt.cn/Article/details/gtdgwjvron.html

Go:   resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtqtarhrmr.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gthoptvsec.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtirqmymut.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gtrqxzrbbj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gtjzuetedu.html

PHP:  curl_multi_init() 系列
来源：http://dali.yangfankeji.com/Article/details/gtroctsefl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtxxchlmmx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtzohhtjks.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gtcxaxsite.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gtmnlrwxia.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yonumen.top/Article/details/gtyfhbgctl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pycfn.com/Article/details/gtifniqjhm.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtdjawqcql.html

M. 命令行 / 进程 / 环境
来源：http://dali.yanxiufei.cn/Article/details/gteqpsinch.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtabamdvsj.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtlkxyxddr.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtghwlxhfu.html

PHP:  $argv;  $argc;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwljwcqxs.html


<!-- 参考信息 -->