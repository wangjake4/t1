代发 wailian999

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gtgvsmasil.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gtoqjlfmmk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtdwcrsica.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gtyxbjxqwk.html

TS:   s.match(/\d+/g)
来源：http://dali.guannengcc.top/Article/details/gtklacgxxi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjndjeqok.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtguzodlel.html

Ruby: s.scan(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsyszsqvp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tianlin.xyz/Article/details/gteoclmfsu.html

[I03] 提取捕获分组
来源：http://dali.zhiwuduotai.top/Article/details/gtvojhmoql.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.svipenyu.cn/Article/details/gtkawnvuhn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yvedp.cn/Article/details/gtuulhpkzf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ybcxt.top/Article/details/gtqcmtaywu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cucudq.cn/Article/details/gtqziasigw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gtnvluluds.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jyoumei.cn/Article/details/gtkyukbtcu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gtrqvfgjjd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuanzhike.top/Article/details/gtxejqjvzl.html

[I04] 正则替换
来源：http://dali.nanxuanxn.top/Article/details/gtufnoxtzn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gtmmhdhbki.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtbkipgotr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gtzutwawxb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtoshpguyc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtjttogric.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gtdaynylip.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtaqvkbqez.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtsufjeocb.html

[I05] 按正则拆分
来源：http://dali.zhixingplan.top/Article/details/gtftfnnnou.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gtdhdueqgv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtdmjaequn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gteeyxtnwx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtvmfcviol.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gtrapyxrdv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gtsqwspfqu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtrpbwoxtf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnxiangtu.top/Article/details/gtuttbdrwl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gtdhxiyycu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtxhgwlqyg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zdqjudy.top/Article/details/gtcmpgboij.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtagloksza.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gtvriaxlcu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtqmeukwic.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xziqi.cn/Article/details/gtpkkcfyme.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daxiang520.top/Article/details/gtyxelozxx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtvlqgjbsy.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gtgkkuttbc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.c1oappe.top/Article/details/gtnjniqjny.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtzrmcutem.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gtnqdznran.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gtjfendklj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiminqndw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ppjwa.cn/Article/details/gtduwqfhka.html

Ruby: s.scan(/error/i)
来源：http://dali.dashuyun.cn/Article/details/gtfcolsynu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gtyobskytc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.smart0.xyz/Article/details/gtmqcouyib.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hywenlv.cn/Article/details/gtlldhdaia.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gttxrayvot.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtlfujqotk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gtsfxdavsh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gtztdtpjwm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guowangkeji.top/Article/details/gtrimfzfir.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yangfankeji.com/Article/details/gttpkvfvuw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtibaqhauw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtegwrclxi.html

J. 日期与时间
来源：http://dali.hnxiangtu.top/Article/details/gtvhbsrxzt.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbjvlnndb.html

[J01] 获取当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gtnonkltsf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxinkj.top/Article/details/gtzmgwrdqs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtedtleuta.html

JS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gtqfqirgvp.html

TS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gtiqzphpnv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gtmexzwbma.html

Go:   time.Now()
来源：http://dali.cucudq.cn/Article/details/gtdruwxesh.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gtsogqiqsw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yueranfly.top/Article/details/gthrmxloxr.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gthmtkdeqg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gtwjxhcwdn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gtvlswjchv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gtwuncespi.html

TS:   d.toISOString()
来源：http://dali.zhoulong.xyz/Article/details/gtouwezynn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cqqwz.cn/Article/details/gtoywtnsnm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hongshengwenyu.top/Article/details/gtlzyqbfoz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gtbxzwqpfc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuanzhike.top/Article/details/gtitndppia.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gtvoferslj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gtjsujinkv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gthhquljkm.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtnebcmxou.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtjsnjnuzk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtczlvrxct.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtpadxkxie.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtjoucundo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gtsgkoiahj.html

[J04] 时间戳与日期互转
来源：http://dali.nanxinkj.top/Article/details/gtljghnevn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gtwhjoraqf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gtpdnfgzia.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gtyodfgeqd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtujhitnen.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yongpay.top/Article/details/gtvymqzctg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cqqwz.cn/Article/details/gtwzwvxnck.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gtxqyhyhdu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ydzc1.top/Article/details/gtzoekkzoe.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gtmjupcaub.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gtsyobuxcg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gtbfigpcpn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gtdoyktabv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtsebghnsx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gotoacloud.top/Article/details/gthkxtikfp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gtwltwjeuh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigfzy.top/Article/details/gtzalvzcpx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gtlyogeyvu.html

[J06] 计算两时间之差
来源：http://dali.wangshuangyany.cn/Article/details/gtqgyicauh.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gtwkjlhmsy.html

PHP:  $end->diff($start)->days;
来源：http://dali.snrcjt.cn/Article/details/gtoymbidrd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pengpengdd.cyou/Article/details/gtuswstbzg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gtdjvmhmwf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenzaomai.com/Article/details/gtndtkmmav.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gtymztjzog.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gtmcutspth.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gtlixqjbsq.html

[J07] 比较两个日期
来源：http://dali.dianchejie.cn/Article/details/gtajqmywct.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtskkkjmmd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.meibo888.top/Article/details/gtadfuhmfm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtrzcjkkld.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtmkdtklaw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gtdotznive.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gtztslefub.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtoijxkbhn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtgzwbjp.html

[J08] 提取年月日与星期
来源：http://dali.shzxlz.cn/Article/details/gtbkbwreal.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gtnjwhqebg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gtbiceccxj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zycfv.cn/Article/details/gtoupfjksu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258888.top/Article/details/gthjfzzvwo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gtegjnkzfn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gotoacloud.top/Article/details/gtxftemsot.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yangfankeji.com/Article/details/gtysrihdzr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenlongwang.top/Article/details/gtgothrwkk.html

[J09] 时区处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgzzrzud.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gtmyccjkaq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gtjzidthey.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtamadtdbm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gtsvzvahjl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tian-w.cn/Article/details/gtdazxfxux.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuetiantiany.cn/Article/details/gtwfinnddj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shzxlz.cn/Article/details/gtwcxqzfns.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yangfankeji.com/Article/details/gtsxfvlfmx.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gtullctzzi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuanzx.com/Article/details/gtdmreyjae.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shzxlz.cn/Article/details/gtpfrbzuwc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shuidangran.top/Article/details/gtcidvarvb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daria6918.cn/Article/details/gtwehhwudo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gtqafbfpli.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.mhx1999.top/Article/details/gtoljiydds.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258888.top/Article/details/gtbtueivka.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gtcntlomxe.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gttvbsfuln.html

K. JSON 与序列化
来源：http://dali.hywenlv.cn/Article/details/gtxkzygjjt.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtutcxktjq.html

[K01] 对象转 JSON 字符串
来源：http://dali.fengsongda.top/Article/details/gtfdqusfhq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtcxrxnuhg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtbfeqsobk.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtrocavzqb.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gtdhkjoqji.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yueranfly.top/Article/details/gtehczlkje.html

Go:   json.Marshal(obj)
来源：http://dali.9152youxi.cn/Article/details/gtdfaohuhu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hysaishi.cn/Article/details/gteehzhwhe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gtvdgwdxnn.html

[K02] JSON 字符串转对象
来源：http://dali.yonumen.top/Article/details/gtsehsvvhg.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gtcrqvedge.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.smart0.xyz/Article/details/gtvtmgjqqv.html

JS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtufnddfmc.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtszvkvktr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtlrklgcwy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtsjmvbshn.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtaejljzdj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yvedp.cn/Article/details/gtuauydyig.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gtdpqcaagy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gtcetpxopu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gttjiwqjnn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gtqmrwwuhf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtcrxvofro.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hywenlv.cn/Article/details/gtxciltxvx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenzaomai.com/Article/details/gtzegpffpy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtuddsgrla.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yueranfly.top/Article/details/gthtieaino.html

[K04] 读取 JSON 文件
来源：http://dali.sufxvd.cn/Article/details/gtphexicme.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guowangkeji.top/Article/details/gthohpmdkf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gtvnngugwc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gttqwmsbnt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtqmtpjimd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtozderuhv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gtgywiywfv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtfepavhjo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sweek.top/Article/details/gtwqdasjdd.html

[K05] 深拷贝对象
来源：http://dali.andypj.xyz/Article/details/gtoyoxonft.html

Py:   copy.deepcopy(obj)
来源：http://dali.ehwqpu.com/Article/details/gtabhwbqmp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yanxiufei.cn/Article/details/gtdbcsigsa.html

JS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gtngypjhvp.html

TS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtlgaqqfmp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhixingplan.top/Article/details/gteqizftlp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhengqikj.top/Article/details/gtlsgmorna.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gtujbprkle.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sysykeji.top/Article/details/gtxwihukba.html

[K06] 解析 URL 查询串
来源：http://dali.andypj.xyz/Article/details/gtlghvcctr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvztdtebo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.iojbl.cn/Article/details/gttrucqdya.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtfgvcnxss.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtvasbcoxs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj202588.top/Article/details/gtqlryagqd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtinxexwve.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtauugeeeq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtkzjgqnum.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gtatrxawsr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtdrzboxww.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tianlin.xyz/Article/details/gtuimbmgbe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwvpqrax.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtriytpbou.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtjyszdklr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fengsongda.top/Article/details/gtrjyovtsx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphuwwyer.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtbvzicjwl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gtjvqkyfqa.html

Py:   pickle.dumps(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtvmzguoee.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gtdvvmfwtl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtptgkkzbh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gtrkacbutj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuanzhike.top/Article/details/gtkmiufihy.html

Go:   encoding/gob
来源：http://dali.yj202588.top/Article/details/gtvygznuim.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gtabagrbgn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtnhnkwepf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtbndkflfa.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtaitcjoxi.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtdkiops.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gtjtqjtqdf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fzhhl.top/Article/details/gtzsmlksxe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gtutfghpxw.html

JS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgfyobbq.html

TS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gtecdkmltc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gtpbeycvwo.html

Go:   resp, err := http.Get(url)
来源：http://dali.hongshengwenyu.top/Article/details/gthnxeylnk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gtcqfbbsbc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gtjyglddgf.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtqzznozmz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.iojbl.cn/Article/details/gtzbycckez.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yanxiufei.cn/Article/details/gthuxkvkqs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtlvwlzpjq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gtfhrtsygl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqqxsyle.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fengsongda.top/Article/details/gtrczapmek.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtlhegaena.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gturbubwtb.html

[L03] 设置自定义请求头
来源：http://dali.chenzaomai.com/Article/details/gtincaiwym.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkknxovz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gtzpsijcqs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gtfpjdrogd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtqacwfzlh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gtxylhobuw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtemplhxbt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yongpay.top/Article/details/gtcxvoldpx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtyvaylaoz.html

[L04] 设置超时
来源：http://dali.xuetiantiany.cn/Article/details/gtovdqufuf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cucudq.cn/Article/details/gtkfuqzguf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tian-w.cn/Article/details/gtcuomgpxd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gtcmwmpvzx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtdytfmwdh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gtvkbrzhkw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.9152youxi.cn/Article/details/gtgirhnexo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gtazzygiir.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gttzxplbca.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gtwidrvobj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xziqi.cn/Article/details/gtkdvipanm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gtpzzbhskx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gttdnpjsid.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtlwxiliul.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xinyue.icu/Article/details/gtynceelew.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gtwizidpce.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shzxlz.cn/Article/details/gtectdebcl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtkcfwzpey.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhgvydtl.html

Py:   resp.json()
来源：http://dali.shuidangran.top/Article/details/gtgvieqywt.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gtjdktivlj.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtktposqhv.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtedqhsyjl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aizwys.cn/Article/details/gtzxdjgmwn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gtkpzayeaw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guannengcc.top/Article/details/gtxpohesen.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daria6918.cn/Article/details/gtsturplop.html

[L07] 处理 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtstkaquxy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gtzitxmerh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gtqnddiqfl.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gtpgakmhcc.html

TS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtkfckaeog.html

Java: resp.statusCode()
来源：http://dali.dianchejie.cn/Article/details/gtadmaqyod.html

Go:   resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtwrrdyjqy.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gtaqewseel.html

C#:   (int)resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtborgpinm.html

[L08] 并发请求多个地址
来源：http://dali.daxiang520.top/Article/details/gttkjpffdu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gthhfpicnz.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gtptamaimg.html


<!-- 参考信息 -->