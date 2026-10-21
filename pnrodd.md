代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtktlkfpip.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gtsclyinlw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gtqouswxba.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnqzz.top/Article/details/gtjsupaziy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkeycefx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbyqixta.html

[I04] 正则替换
来源：http://dali.yvedp.cn/Article/details/gtiijoaadn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigufen.top/Article/details/gtanvxafza.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtwrlboofe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdgxovsi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtvhjoxkap.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtroauibve.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gogol.net.cn/Article/details/gtmhmlasvx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtwjabcwud.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gtndqaqvti.html

[I05] 按正则拆分
来源：http://dali.hnxiangtu.top/Article/details/gtzehdavfp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxinkj.top/Article/details/gtvfutldir.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtialbqgaj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtqheigxrr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtqvvfefyg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gtrmkmcoqv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tanke756.top/Article/details/gtaghoaujv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtjydppieu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daria6918.cn/Article/details/gtmeprxtio.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gtbgpbyrzi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtxxthtksl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gtmkfaemvg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtcfkxzqxg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtqetyhzzg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtqvtogjto.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gtbwkhgyzh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yangfankeji.com/Article/details/gtmhvinjuq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtucwhmptg.html

[I07] 忽略大小写与多行模式
来源：http://dali.gotoacloud.top/Article/details/gtfexlroxg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ivvv.top/Article/details/gtxjjgbffh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtulgprkxl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gtlvumrwia.html

TS:   /error/gim
来源：http://dali.vqdsnc.cn/Article/details/gtukoxevwt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gtfloifzjb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.smart0.xyz/Article/details/gtovuzbfaz.html

Ruby: s.scan(/error/i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgraeppk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yonumen.top/Article/details/gtecopbnzd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gtmphlohms.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.quarkkingdee.top/Article/details/gtboyeyqil.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtsqvsdtxv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gtzzfvxpjp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtggujansk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbrbooxf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gtxfqsweba.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gotoacloud.top/Article/details/gtpuagmtds.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtzhdzdjjh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtufmgmddq.html

J. 日期与时间
来源：http://dali.xinyue.icu/Article/details/gtxjfuhpsm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdewyvwak.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gtcovnyiha.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guannengcc.top/Article/details/gtrbmauaga.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtzyrjkroe.html

JS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtbnweckrm.html

TS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtvgjkziav.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cdnleiting.top/Article/details/gtebctfron.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtmezngzjh.html

Ruby: Time.now
来源：http://dali.0kj1m.cn/Article/details/gtrbcsetff.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gthpydlmfr.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gtqntpyyji.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtiwswxfgv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimhdcogq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pengpengdd.cyou/Article/details/gtyuinogfk.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gtztcxielg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgfzy.top/Article/details/gtaspjpawc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hongshengwenyu.top/Article/details/gtvvnbjipy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtaisirjyv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gtctjhtjpc.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gtyfhtnczi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xinyue.icu/Article/details/gtthuoscgf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sxryk.cn/Article/details/gtkeqphmso.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtvgzckjjm.html

TS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtjcxdqvbo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtqtechufs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtwqnbxisj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtlkxbyszy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgfzy.top/Article/details/gtflwcgfvu.html

[J04] 时间戳与日期互转
来源：http://dali.fzhhl.top/Article/details/gtsgywrxvn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnqzz.top/Article/details/gtdwunvrut.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gtusqyppef.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hammf.cn/Article/details/gttuenwyoq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gturogsxrl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nwbrower.top/Article/details/gtzpdrefux.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hfpthk.cn/Article/details/gtatfdxrmd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtjkctuffn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gtotdmhlps.html

[J05] 时间加减（加 7 天）
来源：http://dali.cheryme.top/Article/details/gtttobqozi.html

Py:   now + timedelta(days=7)
来源：http://dali.tianlin.xyz/Article/details/gtjgrueyck.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.birdmap.top/Article/details/gtdzpzkdyp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gtibpubajk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtmxjhuyzj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gtczgiiguo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtpdvlzyxb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yonumen.top/Article/details/gtfuuvxnkh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.meibo888.top/Article/details/gtbnrmbqiv.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gtrpassisg.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gtxxmjxjwf.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gtbvvpgjrm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gthishbkez.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.9152youxi.cn/Article/details/gtdgkhtouv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gtjspzevdc.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gtqlhlcgay.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shzxlz.cn/Article/details/gtuvxvgjpd.html

C#:   (end - start).TotalSeconds
来源：http://dali.jiagoushi.top/Article/details/gtyiuhslmi.html

[J07] 比较两个日期
来源：http://dali.xziqi.cn/Article/details/gtieiabmjk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtloxbubkv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gtmmmmuofo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtcnrtlehr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gtkhmzgrvz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gtiocbilju.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hammf.cn/Article/details/gtzpcdbxqz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtgjoeprcj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtfbimxqgk.html

[J08] 提取年月日与星期
来源：http://dali.sufxvd.cn/Article/details/gtwitcbyud.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gtpzneuzgo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhoulong.xyz/Article/details/gtiraqifvi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gttigkongh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ivvv.top/Article/details/gtimrfdyae.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgkuxbjp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangtech.top/Article/details/gtujahhapq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gtqrthqtuu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gtdrlifedt.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gtxyhwzjjw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shangyingyoupin.top/Article/details/gtsxlbaahv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhixingplan.top/Article/details/gtceqflcjf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtgobwvgic.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgabwjyj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnxiangtu.top/Article/details/gthcbpbswg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.birdmap.top/Article/details/gtgnvliocb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenlongwang.top/Article/details/gtfdmcirsb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tanke756.top/Article/details/gtwebylroq.html

[J10] 取今天 / 本月第一天
来源：http://dali.yongpay.top/Article/details/gtbxzwlfgp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gtvhywevhd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqggqfjs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqqnueqx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtrjahlimu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gtryxqgnxq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuetiantiany.cn/Article/details/gtfsowfyot.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gtprlpwzsa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtimxnxogf.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtrslsadtz.html

K. JSON 与序列化
来源：http://dali.iojbl.cn/Article/details/gtduaygfaj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtdlwwbnps.html

[K01] 对象转 JSON 字符串
来源：http://dali.ehwqpu.com/Article/details/gtsnclovae.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtsyxbrgsp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gtimytqyce.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gtkhaytszv.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtmgxqppsn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhengqikj.top/Article/details/gtabdwnqoj.html

Go:   json.Marshal(obj)
来源：http://dali.0kj1m.cn/Article/details/gtwhbautqa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sysykeji.top/Article/details/gtzffhsxrj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.birdmap.top/Article/details/gtumcdlkxe.html

[K02] JSON 字符串转对象
来源：http://dali.jianghu66.top/Article/details/gtpctnjbly.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gtqbnsvmhi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hfpthk.cn/Article/details/gtyoeycmea.html

JS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtekgqjcoo.html

TS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtedbihwmx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cheryme.top/Article/details/gtnvlxfity.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gthrhjqdcz.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gttobfluzn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gttxxsaedc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gtbrqjbsgy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtkqgcbzqz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gtwxzbsdrc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtmuweyotb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtsfunwtgg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtiypocenx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.andypj.xyz/Article/details/gtjmywygxi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtrhxyqkqp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daxiang520.top/Article/details/gtygbuxwma.html

[K04] 读取 JSON 文件
来源：http://dali.nanxinkj.top/Article/details/gtrdptrqht.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj202588.top/Article/details/gtlxqraufa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sxryk.cn/Article/details/gtiqdzunsg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtottzqqrn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtfqqlioon.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtscyzfwyr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtrxbrpyof.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtywnxvdvd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gtgbbsdmkh.html

[K05] 深拷贝对象
来源：http://dali.zycfv.cn/Article/details/gttafchosy.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhengqikj.top/Article/details/gtvkbktlsa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guowangkeji.top/Article/details/gtqanqokyy.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gturoknyji.html

TS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtcrnmwedd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dianchejie.cn/Article/details/gtqaracinh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.meibo888.top/Article/details/gtevcvqmlb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guannengcc.top/Article/details/gtujhjftlk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gtwvpgaqsu.html

[K06] 解析 URL 查询串
来源：http://dali.yuxming.cn/Article/details/gtztcmgsue.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangdashe.top/Article/details/gtvefaehuj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gtzciopvzv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtdtuhrogw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtrxttpcyl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhixingplan.top/Article/details/gtlykdilia.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdysujdky.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtkpqsjsej.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gthiqabvme.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gtdcrybmpv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtitiojzlm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gtvbacbbqd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtahrvzrxh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtkqzyuwbu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzctykwi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aibaodan.cn/Article/details/gtamsprtde.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.9152youxi.cn/Article/details/gtxkfvjmsv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtuxkvwxea.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gtqaqwajmc.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtaccvklxx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yanxiufei.cn/Article/details/gthvpgkyim.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gtkjopchgc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtgkwywohx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gtdtorzvdk.html

Go:   encoding/gob
来源：http://dali.ivvv.top/Article/details/gttrwmtubp.html

Ruby: Marshal.dump(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtkyhguocp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhzxjqaq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtfttglltj.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gtvngvtloe.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhiipckg.html

[L01] 发送 GET 请求
来源：http://dali.smart0.xyz/Article/details/gtmzfcjzri.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pengpengdd.cyou/Article/details/gtjlrkqzpa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cqqwz.cn/Article/details/gtyrnkzhwe.html

JS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhjtrpvk.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtbqgfiwwh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblfnxafv.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gtgecvuhdi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.svipenyu.cn/Article/details/gtfufivxec.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hammf.cn/Article/details/gteyhbaooi.html

[L02] 发送 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gtkoabxakw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtcnczfgep.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.haohaochexian.top/Article/details/gtwxrssbdv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtywhqikbk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtwmyznncr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gtbcvqargk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gtpnqsuvdi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yangfankeji.com/Article/details/gtduqhgtbm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xylfe.cn/Article/details/gtmlbhqsnz.html

[L03] 设置自定义请求头
来源：http://dali.0kj1m.cn/Article/details/gtnzxjzewr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuanzhike.top/Article/details/gtgrlwvbuh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtdcyvknbh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtkuylsiyl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffhfwdxr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gttvakonlh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gtpmpevfsu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxuanxn.top/Article/details/gtctjtirzn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsegdszzu.html

[L04] 设置超时
来源：http://dali.jlsjyb.cn/Article/details/gtkbworyqb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgfzy.top/Article/details/gtkwlcoxca.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenzaomai.com/Article/details/gtjtuzcrrb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtwixpnhwr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtqgjqabjw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtxehujbfg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigufen.top/Article/details/gtqyvtbuvz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jlsjyb.cn/Article/details/gtvmwqlmdv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.snrcjt.cn/Article/details/gtceqvpmho.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gthgbhlvge.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuetiantiany.cn/Article/details/gtppqcplgk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigfzy.top/Article/details/gtlfxddfds.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gttsbnskcn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtkpaylcnj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuotdttwr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxuanxn.top/Article/details/gtnfvahxey.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatzeduyg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gtewnnbbdw.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gtpfbvgloo.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtiogxddmi.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gtrluyoslb.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtmotjvrxl.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtwzmnkktz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtmqqzoilr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigufen.top/Article/details/gtgdpftlpz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gtbewsfzam.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtntglfbkv.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gtdzlnoynk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jiagoushi.top/Article/details/gtysuawcna.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuanzhike.top/Article/details/gtkylmfvwy.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gttkpqulax.html

TS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtztxanebf.html

Java: resp.statusCode()
来源：http://dali.sweek.top/Article/details/gtznocxjie.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcijdahpf.html

Ruby: resp.code.to_i
来源：http://dali.shzxlz.cn/Article/details/gtjogpjegu.html

C#:   (int)resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtgsznhtii.html

[L08] 并发请求多个地址
来源：http://dali.yuxming.cn/Article/details/gtbsunajdi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gtzbbefosk.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gtawcknijo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtimrxiyrn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtouwfzunz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gtzcvtamjv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258888.top/Article/details/gtmdnbqqvt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtdihmuvbd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtpxyjaoky.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwxwpxcuo.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuxming.cn/Article/details/gtgdwvcgsn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtvbhhppwr.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gthfxctpnf.html

Py:   sys.argv[1:]
来源：http://dali.haohaochexian.top/Article/details/gtasouqeci.html

PHP:  $argv;  $argc;
来源：http://dali.guowangkeji.top/Article/details/gtkzqgnlbt.html


<!-- 参考信息 -->