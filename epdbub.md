代发 wailian999

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yongpay.top/Article/details/gtxiiicfrh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenlongwang.top/Article/details/gtepgughrx.html

Ruby: s.match?(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gtqrydufmi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gtsjgxgmam.html

[I02] 提取所有匹配
来源：http://dali.yangfankeji.com/Article/details/gtbvlotajl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gtceynqwjy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yanxiufei.cn/Article/details/gtkpelujoq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cashguo.top/Article/details/gtuayjbgmm.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gtfvmvoiiw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sysykeji.top/Article/details/gtiumyaoes.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtckrvmqzu.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtkngbmczj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gtbekhiqqv.html

[I03] 提取捕获分组
来源：http://dali.gzhubu.top/Article/details/gtmxmwpsay.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gtnrnummyc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gtmlrlbevl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pycfn.com/Article/details/gtwbpcggro.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gtnkkylrsv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjmvlpml.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258.top/Article/details/gtxupusdkf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ydzc1.top/Article/details/gtpzznoigu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sweek.top/Article/details/gtjsrttjsb.html

[I04] 正则替换
来源：http://dali.ivvv.top/Article/details/gtoseuqefs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gtzbqaudyt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yonumen.top/Article/details/gtqtydxgrt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtrvvwwwig.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqzszklq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmvdcimz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sufxvd.cn/Article/details/gtitytedcd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxinkj.top/Article/details/gtdrahydbe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gtfroeqeow.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gtztaxxnox.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gtlinsnupt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfvidkcr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtnpvcjkbu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtbpkdqsed.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtweczgjik.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtusxvvflt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtuzvkyuyl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gtsuyozyot.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gtvuvlehvd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwtcfjba.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.316326.xyz/Article/details/gtoplrwjcy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtsppppuop.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtdljpyrwc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtuocmykrb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxuanxn.top/Article/details/gtlxkcfzyp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gtmtmmngxh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtemmyfvll.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangdashe.top/Article/details/gtafbruzia.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gtzpncnkbd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gtkoqjdobe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xinyue.icu/Article/details/gtzodavryy.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gtatlndfwf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zdqjudy.top/Article/details/gtoqispaiz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.havefunace.top/Article/details/gtgeiehkiu.html

Ruby: s.scan(/error/i)
来源：http://dali.cheryme.top/Article/details/gtwxlgbqbk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gtubvfqzot.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gtoqkcandd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hywenlv.cn/Article/details/gtxmficgtt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtkfknnscn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtornfiuqp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gtxpxuruyz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtllezuvrh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gthegplftb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nwbrower.top/Article/details/gtjyebxfdv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gtdejkqolz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtqvyjeaob.html

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gtznxgvfhu.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtlelbctss.html

[J01] 获取当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gttrzqucis.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenlongwang.top/Article/details/gtxdecfgem.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gtwmgtlytn.html

JS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gtjwglzzsf.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gtskncyxye.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258.top/Article/details/gttxkzrlnv.html

Go:   time.Now()
来源：http://dali.gogol.net.cn/Article/details/gtdjksftyr.html

Ruby: Time.now
来源：http://dali.smart0.xyz/Article/details/gtxiyogblv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dianchejie.cn/Article/details/gtitqhfegu.html

[J02] 格式化输出
来源：http://dali.ivvv.top/Article/details/gtqceezspd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gtbumbzzng.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtitvbxnrg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gtovvzcpwz.html

TS:   d.toISOString()
来源：http://dali.yueranfly.top/Article/details/gtwsdwmbba.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gtrplxykhq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tanke756.top/Article/details/gtaopvrbrz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtzidgvdvk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gtatbrtieu.html

[J03] 字符串解析为日期
来源：http://dali.chenzaomai.com/Article/details/gtywuaejlk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gtcdkookhh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tianlin.xyz/Article/details/gtlwgyxcdg.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtbgzqnqkx.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtloabenqx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtjxhiuegp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtwybntnhw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpinbrlu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.9152youxi.cn/Article/details/gtakhdbhxb.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gtolvazgby.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gtqokmtufz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gtekcrlcfo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ppjwa.cn/Article/details/gtmkpyumnm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gtmmwiwdgm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtwnexifji.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gtcvuagesi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gttuujpspa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ppjwa.cn/Article/details/gtjncobybv.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gtyeovxrqf.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gtbkspzlvq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.feifeiyinyue.top/Article/details/gtlycsxqeb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtgswwyrgi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtuwvadxxa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.smart0.xyz/Article/details/gtagmzhujr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.smart0.xyz/Article/details/gtbspgltig.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aibaodan.cn/Article/details/gtkjftmvfz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtvlhzyofj.html

[J06] 计算两时间之差
来源：http://dali.gaohongyu789.top/Article/details/gtazlebaro.html

Py:   (end - start).total_seconds()
来源：http://dali.xuanzx.com/Article/details/gtjfltzgte.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpotizys.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gteaawzfvw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gtcjetwcfn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gtxdxlxonf.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgfzy.top/Article/details/gtmslujrlz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gtotfszgmv.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangkeji.top/Article/details/gthohcwbfb.html

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gtrsulvquc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtaqvzxfot.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhixingplan.top/Article/details/gtjvzrroqv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gthqtaawic.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtlfrafirp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gthecgqufi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gtgwrjbaiy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtkjyfbyeh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gthsikstlq.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gteggzjnum.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnqzz.top/Article/details/gtrypsswfl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.316326.xyz/Article/details/gtkziarytr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gtctfmfowm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gtehpwubla.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.feifeiyinyue.top/Article/details/gtnwrtcsdj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.smart0.xyz/Article/details/gtgttmghph.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuanzx.com/Article/details/gtyqadmemr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gtcdvoubch.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gtcaclttqo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gtryntaaet.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gtxhdegajm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtwroteybh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaszybdzr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuxming.cn/Article/details/gtxdiokhoj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.9152youxi.cn/Article/details/gtqpzsyono.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gttjlszoiu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gtjekzjymq.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gtlessxtfq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gthldhbpwl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gtdrvikusj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dashuyun.cn/Article/details/gtcrykmgck.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xinyue.icu/Article/details/gtjeohhchq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuanzx.com/Article/details/gtvcqicibr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gtepbxwzks.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangtech.top/Article/details/gtscjkmsbj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yangfankeji.com/Article/details/gtuestpsis.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtnlmmsciv.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gtxvtlqrup.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwnsfttio.html

[K01] 对象转 JSON 字符串
来源：http://dali.jianghu66.top/Article/details/gtxenvlaog.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtqbbykvzk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gttvnfoznj.html

JS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gtuhyqiwtm.html

TS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gtmtmcjnaj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gtzitvwqkw.html

Go:   json.Marshal(obj)
来源：http://dali.gotoacloud.top/Article/details/gtudcyxlij.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gtqcdlwsay.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gtmefdwjap.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258888.top/Article/details/gtssmvzozr.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gtfawevrpg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aibaodan.cn/Article/details/gtegytfktb.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtvhmonwlk.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtvrtvhmfh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtbpvnrlba.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtpygfonml.html

Ruby: JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzxmyksy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gtqoukicqr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gaohongyu789.top/Article/details/gtqicmaygk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvtjomxf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtmncoapdw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtnxszxldf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtqcfumtae.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gtngzzwegi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gtkqiwcwxg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgjnldfw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gtzqpddypk.html

[K04] 读取 JSON 文件
来源：http://dali.aizwys.cn/Article/details/gtnjefpmll.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gtvwjtqxlh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gtelnujgkm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtxaugjxhs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtfrqndatr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtknhmyxsv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtfpkvvjxz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gticpapqto.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gtlcjlguwm.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gtcsyxlvvm.html

Py:   copy.deepcopy(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlrilxus.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gttvvmlgvh.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtylohzjvg.html

TS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtzmjuzpyq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aibaodan.cn/Article/details/gtfgwgnfdd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gtvfmagtdp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gthotvhiyg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yueranfly.top/Article/details/gtudxqkplb.html

[K06] 解析 URL 查询串
来源：http://dali.yvedp.cn/Article/details/gtsirdrnva.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolihzfma.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnqzz.top/Article/details/gtxltyhnpx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtptcimncj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtbwbapocq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gtcrdvrwbs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gthtjjqrdp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtlfszulvz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtksavpioh.html

[K07] 进制转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgfuegip.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtifnxuxne.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.snrcjt.cn/Article/details/gtogwgdsmj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtosztyygi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtssjaxhvs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtrwfqyjhz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.andypj.xyz/Article/details/gtuuiiopiu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gtglytglai.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtxzdzzdpd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yonumen.top/Article/details/gtzhuxdkfc.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvlgzyoz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gtxfdwbwti.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gthhsstdqn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtbpxyotss.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.0kj1m.cn/Article/details/gtijymcloi.html

Go:   encoding/gob
来源：http://dali.zhixingplan.top/Article/details/gtyowunipf.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gtvvhpotfr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gtnbgwyffl.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtkgsoltii.html

L. 网络请求
来源：http://dali.yangfankeji.com/Article/details/gtsrhkkbld.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtbeidwcng.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gttsaboinf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zycfv.cn/Article/details/gtftmufwnm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhxgfyjv.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtedafrbcq.html

TS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtjsclwsug.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tanke756.top/Article/details/gtajiizmwl.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxuanxn.top/Article/details/gtfnzjidvj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgfzy.top/Article/details/gtpddrhbke.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.meibo888.top/Article/details/gtgebtsodb.html

[L02] 发送 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gtlqfwjocf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gtfklofwyy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gtokzgwzkw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gthafgnlpr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gtwkiocmqf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daxiang520.top/Article/details/gtvxaksazw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gtctebbtwc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.bjfxy.top/Article/details/gtizemlbyo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.meibo888.top/Article/details/gtzzfyhnrn.html

[L03] 设置自定义请求头
来源：http://dali.iojbl.cn/Article/details/gtubtthdod.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigfzy.top/Article/details/gtmanujfxi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxuanxn.top/Article/details/gtlrtfwvyc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gthkrqogms.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtoctjlbmw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscaovlek.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtyslwitla.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gotoacloud.top/Article/details/gtunucyczj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtpqkdqssw.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gtwrfkopxl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gtapnajdgm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfdqmlah.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtnsyrzpjc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbkwjslw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gtwbgafiit.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnqzz.top/Article/details/gtkbjrmfaj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.316326.xyz/Article/details/gtjnpkslny.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gttftnqjia.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gtmpaisqca.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsntwznok.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhiwuduotai.top/Article/details/gtldcqthrh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gthtkdqbkg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtwmkawc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gtsqhvhnsx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.andypj.xyz/Article/details/gthnqthhll.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258888.top/Article/details/gtzonvxlmn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtltszzwkf.html

[L06] 解析响应为 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtjnpmkusk.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gtwjciunjy.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gtpmvvmfqe.html

JS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gtroogkida.html

TS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtxhtbjjox.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtctsvfthj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tianlin.xyz/Article/details/gtllkzeiye.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gtsfuubjyn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gtvpkgauri.html

[L07] 处理 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gtjvoedhyp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gtlycgsovh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gtyhohuawd.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtxcqdepak.html

TS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtdmkcsxlz.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gtkyjpphlj.html

Go:   resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gttejpnigs.html

Ruby: resp.code.to_i
来源：http://dali.jinqigufen.top/Article/details/gtfcckyija.html


<!-- 参考信息 -->