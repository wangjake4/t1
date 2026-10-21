代发 wailian999

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aibaodan.cn/Article/details/gtfumaehhk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.svipenyu.cn/Article/details/gtywovmzgy.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtjvkfysgl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hywenlv.cn/Article/details/gtuzcjpeqx.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gtjliughbg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehfswqxk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gtndpmthyk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guowangkeji.top/Article/details/gtejxujylz.html

TS:   s.match(/\d+/g)
来源：http://dali.haohaochexian.top/Article/details/gtsosrweli.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxinkj.top/Article/details/gtexfysjjb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xziqi.cn/Article/details/gtcepzcpvj.html

Ruby: s.scan(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtevqggdwa.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gtfcxjonvs.html

[I03] 提取捕获分组
来源：http://dali.yuxming.cn/Article/details/gtjzxockxz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gzhubu.top/Article/details/gttuczhwqz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gttbldsskb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.quarkkingdee.top/Article/details/gtlgumnxav.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtbvnlbznf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yonumen.top/Article/details/gtaslgezjt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gtblzwbpbb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gtojpgnpgi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gtexfkdaxx.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqgxbvgu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.iojbl.cn/Article/details/gtbfeqvxef.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gteladkdcn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtzmiwbmsw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtvvfzwgxn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtefezempq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtevnapbpb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtzrocoavw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtpfbtsnyj.html

[I05] 按正则拆分
来源：http://dali.aizwys.cn/Article/details/gtposgefhe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xylfe.cn/Article/details/gtdjsropmb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtihxxonuu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtiwvdtvum.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtqajpgwcz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtxrerqibn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtqhdtrnxj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gttybyksbm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gtrivikylm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhiwuduotai.top/Article/details/gthuozdcve.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gteiwbxpmp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gthzpdvjss.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtdfyqwydh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtsxrdeugm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtxlshztdr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sweek.top/Article/details/gtwkprddjb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenlongwang.top/Article/details/gtrfcnhpsy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtgwxeqoqc.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gtczawtpra.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sufxvd.cn/Article/details/gtzojycqve.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqglcamyg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yanxiufei.cn/Article/details/gtlrvqrwft.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gtnvvicfin.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gtxqlcjvzi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gthifzglik.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvnkhvfw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pengpengdd.cyou/Article/details/gttouvvlmk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258888.top/Article/details/gtdolmaagd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gtnzafgbkc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gtwavlskck.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gtafgrarky.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gtzimqkjed.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtsivtbtep.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gtjcoplmpq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.birdmap.top/Article/details/gtvzyzogmh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gtikfcudqg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtyagofvsy.html

J. 日期与时间
来源：http://dali.daria6918.cn/Article/details/gtlejkyyec.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjgmlawyu.html

[J01] 获取当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtrznymjwq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.0kj1m.cn/Article/details/gtpugnlbpu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gtmdfntbtq.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtlksnnsng.html

TS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtxmwlchzv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hysaishi.cn/Article/details/gtrhjrsxih.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gtivmcxeaj.html

Ruby: Time.now
来源：http://dali.yvedp.cn/Article/details/gttfkmvmdl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gtrsefgjxb.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjdyvgdo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfvtxeyg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gtdgwlxumx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pengpengdd.cyou/Article/details/gtoebtlpmi.html

TS:   d.toISOString()
来源：http://dali.yj202588.top/Article/details/gtjtoxrkhm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yueranfly.top/Article/details/gtgzbmdybo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gtiypjutse.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtzkfedukp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.bjfxy.top/Article/details/gtuvkfaqnz.html

[J03] 字符串解析为日期
来源：http://dali.zhengqikj.top/Article/details/gtqqtupqdd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.svipenyu.cn/Article/details/gtharphcoz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.quarkkingdee.top/Article/details/gtzihynmku.html

JS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtusxhczue.html

TS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucxzehch.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtawdvkxss.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtplbakqbm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtrroqevhs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gtmhdxsdai.html

[J04] 时间戳与日期互转
来源：http://dali.0kj1m.cn/Article/details/gtdliomctd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gtrqxjpwni.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gtcenblbxi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guowangkeji.top/Article/details/gtnmyfgghb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gtghtzpgmv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.meibo888.top/Article/details/gtylvzzzdx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtaenpvskr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sufxvd.cn/Article/details/gtbizszsnb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gtepfplhdy.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gtmnpppuqb.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gtybvkiikk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hywenlv.cn/Article/details/gtmjpnqzmg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtzkpmvkbc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gtweyzgnxh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gtncbnkvle.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gthhnndsnq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnqzz.top/Article/details/gtrnzkibfq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.bjfxy.top/Article/details/gtiuobvsjy.html

[J06] 计算两时间之差
来源：http://dali.xziqi.cn/Article/details/gthdmnvebj.html

Py:   (end - start).total_seconds()
来源：http://dali.zdqjudy.top/Article/details/gtphnjzcxl.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhongyouzk.top/Article/details/gtdvoglipd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gtnujyjqpt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gtfkslnlqs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtztopkize.html

Go:   end.Sub(start).Hours()
来源：http://dali.zycfv.cn/Article/details/gtzgzajlcm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cashguo.top/Article/details/gtatcyahek.html

C#:   (end - start).TotalSeconds
来源：http://dali.ybcxt.top/Article/details/gtstpozapm.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gtcenxqvmb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtrxprdywz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.mhx1999.top/Article/details/gtdonbdfrd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gttnvvgrag.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtlhigxoca.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shzxlz.cn/Article/details/gtfnvpeinx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cdnleiting.top/Article/details/gttklbapgj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtrkyysxqz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtzimoioqb.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gtbyvfohpl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gtoqisntlu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxnkmbmx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xziqi.cn/Article/details/gtzkfzshjn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gtqmiukjob.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhiwuduotai.top/Article/details/gtudephtzk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gtytoqzjao.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guowangkeji.top/Article/details/gtthpsuxeq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gtpjjynnqt.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gtbwfyrvho.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gtedoeujeb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sweek.top/Article/details/gtzriynqtp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gtmhskxbgi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtdtcfiwfr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gtskpcnkzz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sweek.top/Article/details/gtbvlsvvyl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gtynszxvao.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gtzvbgxhdd.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgfzy.top/Article/details/gtcydbvcjr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gtxybzwquy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.bjfxy.top/Article/details/gtfevizloj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zdqjudy.top/Article/details/gtyjhvvhvw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gtictdxqrn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtwdwzimzz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jyoumei.cn/Article/details/gtpjjendyy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shzxlz.cn/Article/details/gtqrnsfgov.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gtdwopbtbs.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtunuvdfnc.html

K. JSON 与序列化
来源：http://dali.zhiwuduotai.top/Article/details/gtekxnhedg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxfvhaozq.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gtbtpotmwp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtllnfhnhl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtuleiazgf.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtqpyezduz.html

TS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtslqpcdfz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jianghu66.top/Article/details/gtahxhjlla.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuivhurnn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zdqjudy.top/Article/details/gtljqugkjm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gtnvsdbnih.html

[K02] JSON 字符串转对象
来源：http://dali.fzhhl.top/Article/details/gtsvwmrcrn.html

Py:   json.loads(s)
来源：http://dali.jqgfzy.top/Article/details/gtaadxqsmc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gticvhhbmk.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtwmiosasc.html

TS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyyvklmt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtoqicokgp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpecmfehh.html

Ruby: JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtcrxnuefm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gtecmovwag.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gtvutnxcyk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtcqkghvfr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gtzubczlsh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gthcbzypyr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtefwcwhwo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gtgfrlsqit.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.smart0.xyz/Article/details/gtwhxgnebq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.svipenyu.cn/Article/details/gtapkvliqq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhydmooh.html

[K04] 读取 JSON 文件
来源：http://dali.snrcjt.cn/Article/details/gtwnaffhim.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gtifgfuclz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yanxiufei.cn/Article/details/gtliadswzx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtpozlxchu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtmqezyady.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cucudq.cn/Article/details/gtlhfwaibs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gtjlpigcyu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gtswzledtu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gtqnbdnpbd.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gtttjktrdb.html

Py:   copy.deepcopy(obj)
来源：http://dali.hysaishi.cn/Article/details/gtlmkgptrd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gtjgkfflpw.html

JS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gttnikizwa.html

TS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtgvbusuga.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuanzhike.top/Article/details/gtjebzugbc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aibaodan.cn/Article/details/gtcknpjdgo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gotoacloud.top/Article/details/gtfucbifpu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gtisqtnkkj.html

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gtlvvgnxbf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gtyjweazkt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnqzz.top/Article/details/gtpkicthze.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gtukqfgjpv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtthftjefh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxuanxn.top/Article/details/gtwcyfsobn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gttjugqpvw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtvpnfgydk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gtbvggylev.html

[K07] 进制转换
来源：http://dali.nanxinkj.top/Article/details/gtpyzyarpa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtifeudrpz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.svipenyu.cn/Article/details/gttjitgsmo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtvtpfklwn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtknbfpvew.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gthsokvlnh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhengqikj.top/Article/details/gtkzjniowy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gtcweqtara.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtrqczxusy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuanzhike.top/Article/details/gthzolysul.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gtzxytxkol.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gtepvcpzld.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtxrcxluts.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gtbzdottgz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ppjwa.cn/Article/details/gtcctizosi.html

Go:   encoding/gob
来源：http://dali.cdnleiting.top/Article/details/gtupzthieo.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gtonalzryj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtgadeofxo.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtukazonjk.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gtlflanrcn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtlrihmajt.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfogndeeb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.mhx1999.top/Article/details/gtssnxuazi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuanzx.com/Article/details/gtefwlhkpq.html

JS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtlwygaqnz.html

TS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtpjwtlhtm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.haohaochexian.top/Article/details/gtlekrlaqe.html

Go:   resp, err := http.Get(url)
来源：http://dali.gzhubu.top/Article/details/gtpkutrygj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.0kj1m.cn/Article/details/gtbsdlacso.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shzxlz.cn/Article/details/gtarqtlgux.html

[L02] 发送 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gthxaxfmfz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daxiang520.top/Article/details/gtaysjidhv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gtcatmsqgp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gthzxzmdmb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gtqqjbjdrz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gtffebkjvl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gtkdpicmyv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtxzwzwqhs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.iojbl.cn/Article/details/gtsnjyhesu.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gtufzohjzu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gtxyeftrhb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gtvjrdzixl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgprcotf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtbwxbuixk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sweek.top/Article/details/gtrqizsoam.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gtthcllgkq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zdqjudy.top/Article/details/gttnmynbwj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtezcluekg.html

[L04] 设置超时
来源：http://dali.jqgufenzy.top/Article/details/gtcunlssak.html

Py:   requests.get(url, timeout=5)
来源：http://dali.9152youxi.cn/Article/details/gtaydartfu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yanxiufei.cn/Article/details/gtccinghpw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gthfozgwac.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtsngzkkje.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aibaodan.cn/Article/details/gtmziqbixa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fengsongda.top/Article/details/gtvcrmswaq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jyoumei.cn/Article/details/gtxzbmwznd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gttbajzocb.html

[L05] 上传文件（multipart）
来源：http://dali.cdnleiting.top/Article/details/gtzynyzqtd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gtudcgbipd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yvedp.cn/Article/details/gtakhkhsgd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gtdvnimjao.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtzfqmowqe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ppjwa.cn/Article/details/gtxzltqpzt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jianghu66.top/Article/details/gtpmfddjom.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nwbrower.top/Article/details/gteqkvmiuk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtuenzxelq.html

[L06] 解析响应为 JSON
来源：http://dali.jqgufenzy.top/Article/details/gtbhxjinmz.html

Py:   resp.json()
来源：http://dali.fengsongda.top/Article/details/gtmvzwuryf.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtoldxjxeu.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtejguhfra.html

TS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gtcliepuyj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtivzyengx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guannengcc.top/Article/details/gtjrlatvuo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxjrfjsj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnqzz.top/Article/details/gtikkfpsjp.html

[L07] 处理 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtklhiuczs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuanzx.com/Article/details/gtmqugyhrp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnqzz.top/Article/details/gtguqmjben.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtxwsrlouy.html

TS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtfooejgrb.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gtezfzfchp.html

Go:   resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtrtercfrk.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gtaazvwlsl.html


<!-- 参考信息 -->