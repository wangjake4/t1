代发 wailian999

[I02] 提取所有匹配
来源：http://dali.cdnleiting.top/Article/details/gtnheshqif.html

Py:   re.findall(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtxqskmsgz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jianghu66.top/Article/details/gttbfavxmp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gtuifkycvn.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gtpwdqntlw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.andypj.xyz/Article/details/gtiziuusce.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtbntflojm.html

Ruby: s.scan(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtxtmffaug.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtubrakewa.html

[I03] 提取捕获分组
来源：http://dali.guowangkeji.top/Article/details/gtmlobhwbf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.0kj1m.cn/Article/details/gtmxqydnrb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xylfe.cn/Article/details/gtvjcbsqcp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtkmuiufcj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkzltjfr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gtriejqagr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gtwcvgjull.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gtcktbzlrz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gtuljlsfdy.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtypirlzbz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jlsjyb.cn/Article/details/gtgqheuhbo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtqogdoxmx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxeazgrx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtnoeggpbo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtwacdnwmk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtjmpwqsjj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.smart0.xyz/Article/details/gthfbfbtxq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gtvmoxbfuw.html

[I05] 按正则拆分
来源：http://dali.jqgfzy.top/Article/details/gtnxbfddug.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnqzz.top/Article/details/gtxejejffk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtgnyyshnj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtagoujhyx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtgzzzljig.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sweek.top/Article/details/gtqndmqlwo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtbqphtzgl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtgpucdrgw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.meibo888.top/Article/details/gtlkgstqqg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yvedp.cn/Article/details/gtnnbxsxgo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtmlrulnfb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gtnlpzqfll.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtoyxmavxe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gthtxttzic.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gteqgglyer.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangdashe.top/Article/details/gthzapitgx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigufen.top/Article/details/gtreqpkfgh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtrnmpmlxo.html

[I07] 忽略大小写与多行模式
来源：http://dali.aizwys.cn/Article/details/gtspmkffvl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.andypj.xyz/Article/details/gtgjxurapf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtsbfetjtl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yangfankeji.com/Article/details/gtrmhieilo.html

TS:   /error/gim
来源：http://dali.snrcjt.cn/Article/details/gttvnfdgnk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyuqizkc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pengpengdd.cyou/Article/details/gtzcbqijxj.html

Ruby: s.scan(/error/i)
来源：http://dali.iojbl.cn/Article/details/gtujhtxcfq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuxming.cn/Article/details/gtwvxzxrfm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtpnehtaur.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aizwys.cn/Article/details/gtnotuvbxe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gticfufteg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtvlcuspdw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtzpyyphkc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gttfpgwvmo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.snrcjt.cn/Article/details/gthjkauaoq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gttgwipnha.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gtsqfbbnut.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtxhsykvfa.html

J. 日期与时间
来源：http://dali.gaohongyu789.top/Article/details/gtjvinmzhb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gteojzsupf.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhqyxrmk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gtebcvbrcy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gtobnejdfz.html

JS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtwferamto.html

TS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gtzeytitea.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jianghu66.top/Article/details/gtqnyszvtv.html

Go:   time.Now()
来源：http://dali.guowangkeji.top/Article/details/gtmhvkycsu.html

Ruby: Time.now
来源：http://dali.yvedp.cn/Article/details/gtrayrawfb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gtzqjjedch.html

[J02] 格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtdibrptiu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gttvyclamh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gtqykiukvb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ehwqpu.com/Article/details/gtixdoklpn.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gttyjuouaf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.snrcjt.cn/Article/details/gthpcgamke.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwerablu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtiecyozld.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yangfankeji.com/Article/details/gtgivqsguc.html

[J03] 字符串解析为日期
来源：http://dali.hammf.cn/Article/details/gteaohhwou.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gtzwgooyuj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gaohongyu789.top/Article/details/gtbfjsennp.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gttyqyluen.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtutpdqjoi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtwcfcemrf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtsxpzlicd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtcyxttpvn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gtyhtlpffk.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gtmlphrhrv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258.top/Article/details/gtsonqoyjf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuetiantiany.cn/Article/details/gtzbfuebsv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gtigplbnas.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gtxkgbozgd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hysaishi.cn/Article/details/gtfwtawatz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aibaodan.cn/Article/details/gtxbnaevww.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gtnxkaojgv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sweek.top/Article/details/gtnpoaobes.html

[J05] 时间加减（加 7 天）
来源：http://dali.c1oappe.top/Article/details/gtfzbfpkwh.html

Py:   now + timedelta(days=7)
来源：http://dali.xuetiantiany.cn/Article/details/gteoutzkud.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gtkqdpozry.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtuafyfjhm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gtlipvnbtl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jiagoushi.top/Article/details/gtzwkefabc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ppjwa.cn/Article/details/gtcydfcpfs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gtkchdkmhj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gttzyvmmvd.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gtnylmrowi.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gtkqpsbpbw.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gteofcushz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cheryme.top/Article/details/gtjbcbyswo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyocoooe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gtkeptkbpf.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gtisdqwiju.html

Ruby: end - start                 # 返回秒数
来源：http://dali.redwolf501.top/Article/details/gthpgabopv.html

C#:   (end - start).TotalSeconds
来源：http://dali.shzxlz.cn/Article/details/gtcrnumsjb.html

[J07] 比较两个日期
来源：http://dali.birdmap.top/Article/details/gtrgcccspe.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxwxeelh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gtgkdelwnn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtpwlhpjzz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gthecogrxx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gtzwigxdls.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sxryk.cn/Article/details/gtcoebpojt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtekivphee.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtuajeeogx.html

[J08] 提取年月日与星期
来源：http://dali.pengpengdd.cyou/Article/details/gtafmndssi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuanzx.com/Article/details/gtrtkjdfhv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.smart0.xyz/Article/details/gttklhddnt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gzhubu.top/Article/details/gtfgvsmest.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gtthngihcl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pycfn.com/Article/details/gtoyqtpkqd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dianchejie.cn/Article/details/gtnpzvdrfa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeytpzwf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gtjotrdxal.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gtejcjdzrz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fzhhl.top/Article/details/gtuehioaqj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhiwuduotai.top/Article/details/gtvbdwyetr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtcqzfvmfs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjhvitwh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhengqikj.top/Article/details/gtvgclofqu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gtjzbydcjt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gtqissrgyx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gtpgqmpxlh.html

[J10] 取今天 / 本月第一天
来源：http://dali.dianchejie.cn/Article/details/gtqvyatuoe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.feifeiyinyue.top/Article/details/gtumrgqgbd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsscvdih.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sxryk.cn/Article/details/gtrqimzjwi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gtrpgqjfhq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gtskfeuexq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinghuilouyu.cn/Article/details/gtkojhopyd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ivvv.top/Article/details/gttdeopihl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtzundzjvb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtdecumxdp.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gtrjcbwgiy.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtbqdqfxor.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gtzaeszqdw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtdmcwlcic.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtxektosoa.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtdrkyhdec.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtgkqyhlxj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtrcycycpp.html

Go:   json.Marshal(obj)
来源：http://dali.yonumen.top/Article/details/gtsjqyjajw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pycfn.com/Article/details/gtzzelozoo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyqbtabj.html

[K02] JSON 字符串转对象
来源：http://dali.chenzaomai.com/Article/details/gtggusybqr.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gtnsyeurbm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gtwtdrbcvv.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtqjqveqbd.html

TS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gthtcatses.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtatoooijc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtjvqbqcqq.html

Ruby: JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtdgvflieb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jiagoushi.top/Article/details/gtxbhgfnao.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shuidangran.top/Article/details/gtxbesdamp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gtjafjfjct.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtnoxeigyx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtlptjnvkg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gterfrvabp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.havefunace.top/Article/details/gticsawvsi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gtsstmpdsh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtnpmggssq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.andypj.xyz/Article/details/gtygbcqyrt.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gtujhfmurq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gtsaqjodca.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gtopmpurod.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtrjbtajow.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtqezwzztl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtgtmjlchz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gttaedbjmf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtxshhwhlv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yonumen.top/Article/details/gtjnpwooct.html

[K05] 深拷贝对象
来源：http://dali.fengsongda.top/Article/details/gtwrdfgxds.html

Py:   copy.deepcopy(obj)
来源：http://dali.cdnleiting.top/Article/details/gtogalhsmg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gtxvxkbrxw.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtisufinos.html

TS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtlklvmthg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ppjwa.cn/Article/details/gtukfciifj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hywenlv.cn/Article/details/gtsjyzqllp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigfzy.top/Article/details/gtiqoglbih.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xylfe.cn/Article/details/gtythqdosq.html

[K06] 解析 URL 查询串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlaigsomf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gthmydslqf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gtwbtbrrnd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gttcjdpfiu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gtqzirhkmn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hysaishi.cn/Article/details/gtssdkstdo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtumgxtqwi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtiwmlcfvs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gterxtnfpc.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gtryygobtp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtffnrtslm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gtmdsstwrh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpleszej.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtveqmfzkv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtppaqcame.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltlwnbjd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtgewcepjz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtvwhpsxta.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgufenzy.top/Article/details/gtizcrhdfy.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtegnyymtf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daxiang520.top/Article/details/gtpfkqjnlu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtacvyzrpf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtgrpdnbhe.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gtezjazjgo.html

Go:   encoding/gob
来源：http://dali.meibo888.top/Article/details/gtwjeshlee.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuanzx.com/Article/details/gtazqzgnqs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtmccfyvky.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtxzuxtlgl.html

L. 网络请求
来源：http://dali.jianghu66.top/Article/details/gtllmixvwi.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdgdjiqow.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gtrfqevgtf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.meibo888.top/Article/details/gtrgvsaxju.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yangfankeji.com/Article/details/gtehygjaup.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtmmvclwpw.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtdssveqjv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daxiang520.top/Article/details/gtnaydhnte.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtdcwzwmky.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hysaishi.cn/Article/details/gtnigsncyz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shzxlz.cn/Article/details/gtkmogasng.html

[L02] 发送 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtnizkykuh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ydzc1.top/Article/details/gttnubzeqx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jianghu66.top/Article/details/gtjkaqlero.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gtfehzpgyo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodfqnyws.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtfrjcibgh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhongyouzk.top/Article/details/gtvmkzhsgr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.svipenyu.cn/Article/details/gtppkupnqw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cdnleiting.top/Article/details/gtjinqqpov.html

[L03] 设置自定义请求头
来源：http://dali.zhiwuduotai.top/Article/details/gtjqkjvbwo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gtebzxrgpu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gtqlhrpvtw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gtpdncoifw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtmcvqbcxc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cdnleiting.top/Article/details/gtmjyeoqbe.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtbdqftinq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gtfkgizqqb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtqutngozn.html

[L04] 设置超时
来源：http://dali.birdmap.top/Article/details/gttguhdohn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gtnngfzqfe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guowangkeji.top/Article/details/gtelunfpub.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtccjwjpxx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtgqgamhmv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuanzx.com/Article/details/gtiqihiwaz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gaohongyu789.top/Article/details/gtclyeqkdz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusqcjnhq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tian-w.cn/Article/details/gtddqvqper.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gtatounzxx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daxiang520.top/Article/details/gtfmryeako.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gtnkfdfoqa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtibwunltl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtoyvymjyv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gtizjqmunt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgfzy.top/Article/details/gtvadidolx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtwlrzgqvr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gzhubu.top/Article/details/gtutnemhwx.html

[L06] 解析响应为 JSON
来源：http://dali.tanke756.top/Article/details/gtnekpowah.html

Py:   resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtqhdbyhkv.html

PHP:  json_decode($body, true);
来源：http://dali.yj202588.top/Article/details/gtjjrmfkww.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtbqigceqi.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtxfciwdls.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gtzcyfvjzm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.iojbl.cn/Article/details/gtgbzwcvem.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gtrxsyaxxz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gtspvjagec.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtppaxgwqp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gtdqhesndg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtraxpzsdr.html

JS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gteqwphoad.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtrxhdtzth.html

Java: resp.statusCode()
来源：http://dali.yj20258888.top/Article/details/gtddspxcus.html

Go:   resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtgdxyyplc.html

Ruby: resp.code.to_i
来源：http://dali.sweek.top/Article/details/gtczwpnznx.html

C#:   (int)resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtffvcrlps.html

[L08] 并发请求多个地址
来源：http://dali.yongpay.top/Article/details/gtkaodgkmj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gtuyuktflv.html

PHP:  curl_multi_init() 系列
来源：http://dali.ybcxt.top/Article/details/gtmafdqcsc.html


<!-- 参考信息 -->