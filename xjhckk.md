代发 wailian999

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gtmnmbydmj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gteqykjkjb.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtdviwgeea.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.meibo888.top/Article/details/gtbjtqowrx.html

[I02] 提取所有匹配
来源：http://dali.aibaodan.cn/Article/details/gtmcnvbljt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gtjnybvsdl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hongshengwenyu.top/Article/details/gthwldxluq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gttequeujc.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gtzdxrealx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.havefunace.top/Article/details/gtioafpsgw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gttscgdbrd.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj202588.top/Article/details/gtywurtkcb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gotoacloud.top/Article/details/gthqnybiib.html

[I03] 提取捕获分组
来源：http://dali.dashuyun.cn/Article/details/gtotzkyzth.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shzxlz.cn/Article/details/gtaauhxolb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtytiypdsq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gtebzuxuhb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gtskyezpuc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tian-w.cn/Article/details/gtrpdxlrfo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gtsfppntmj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gtyekozeii.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gtwybtlsja.html

[I04] 正则替换
来源：http://dali.0kj1m.cn/Article/details/gtjaciefgg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.haohaochexian.top/Article/details/gtebeoftgq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtvrhdizem.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gtvourozph.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cdnleiting.top/Article/details/gtatmyrket.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtygqygmbb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ydzc1.top/Article/details/gtcnypbozk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shzxlz.cn/Article/details/gtayngpvsv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtrlcgeybd.html

[I05] 按正则拆分
来源：http://dali.nwbrower.top/Article/details/gtivpilutc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yangfankeji.com/Article/details/gtvfwpaqjy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sysykeji.top/Article/details/gtodmjedpf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtbhevvwir.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtzsjylbwr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.vqdsnc.cn/Article/details/gtivrvfedd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtbcfppjvz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtmiacmuou.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gtaxabzjvf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tian-w.cn/Article/details/gtczhghheh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtgohkoghb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gtgxejngit.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gtegujddtm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gtbkbogmzr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtrgqnbnlf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gtyigbnghg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuetiantiany.cn/Article/details/gtvlpmepkw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gthylmcyne.html

[I07] 忽略大小写与多行模式
来源：http://dali.cucudq.cn/Article/details/gtwxyceaar.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.meibo888.top/Article/details/gtftmlpauw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtzkrblurw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gtggrkbwbh.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gtcsahjrgv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gtsespyein.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cdnleiting.top/Article/details/gtlkgjfcyl.html

Ruby: s.scan(/error/i)
来源：http://dali.quarkkingdee.top/Article/details/gtusfsjfkn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gtuujtxrwm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sweek.top/Article/details/gtgszuouny.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhixingplan.top/Article/details/gtjvdclwus.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pycfn.com/Article/details/gtwhrxqfpv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtftcyeqxb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtcxhyvhtv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmalgslk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.svipenyu.cn/Article/details/gtqcbknuzf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cheryme.top/Article/details/gtwqtagbfw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtvbewxzjv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtedpdxcda.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gtdohapvsb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbaymuamg.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gtgqosialf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gtfsdfddlh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtceybjnyt.html

JS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtylyakayd.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtwsfzvvig.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtpuinjftl.html

Go:   time.Now()
来源：http://dali.hongshengwenyu.top/Article/details/gtyqkacloz.html

Ruby: Time.now
来源：http://dali.feifeiyinyue.top/Article/details/gttgdmoywk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ydzc1.top/Article/details/gtrekwcdvl.html

[J02] 格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gthiyukueq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gtdrkaifti.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtlszpeact.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gogol.net.cn/Article/details/gtmzzhigsb.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gticqyrtxs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gtbipxkukb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jyoumei.cn/Article/details/gtiknbqpiy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtculxfsvh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.iojbl.cn/Article/details/gtobdljlvc.html

[J03] 字符串解析为日期
来源：http://dali.yuanzhike.top/Article/details/gtphwjpcxf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hywenlv.cn/Article/details/gtjbczuvgq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yanxiufei.cn/Article/details/gtofskdgge.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtxmvikpgh.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtllfghrdw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsxvanul.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtdyyahokc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtvmrvouzc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cheryme.top/Article/details/gtvbmhxsie.html

[J04] 时间戳与日期互转
来源：http://dali.svipenyu.cn/Article/details/gttgrvgarg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cdnleiting.top/Article/details/gtrmuekqrz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.quarkkingdee.top/Article/details/gtqgkxtjbt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gtdpwbguqc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gtjtugjksf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gtphiytetf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtwidoyyta.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhixingplan.top/Article/details/gtgfkchlus.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtjiohifkw.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhixingplan.top/Article/details/gtgzjhcbhn.html

Py:   now + timedelta(days=7)
来源：http://dali.vqdsnc.cn/Article/details/gtgznxniok.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gtzzncgvcv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gthpvjodlr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtzdolluju.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.havefunace.top/Article/details/gtsdeuzwba.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tanke756.top/Article/details/gtfgsbpgzd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xinyue.icu/Article/details/gtkszztmcw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenzaomai.com/Article/details/gtwhkaoiyd.html

[J06] 计算两时间之差
来源：http://dali.wangshuangyany.cn/Article/details/gtovkxkfpg.html

Py:   (end - start).total_seconds()
来源：http://dali.yangfankeji.com/Article/details/gtrfgubune.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gttpzhhjek.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnxiangtu.top/Article/details/gtnvupflvj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.haohaochexian.top/Article/details/gtdwwayxli.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cucudq.cn/Article/details/gtnfbbuagm.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj202588.top/Article/details/gtfjmrddje.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cashguo.top/Article/details/gtoglklfwf.html

C#:   (end - start).TotalSeconds
来源：http://dali.ydzc1.top/Article/details/gtowbvdqde.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gtqciwejpq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtdfwtfhcy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gtarwvylkm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtatectnlw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtoehkcqfi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtlggswfdc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtsodavfvr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtkrjncxce.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtyfwnvktm.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gtjuuuzljk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guowangkeji.top/Article/details/gtyczjihew.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gtfwqbcgik.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangtech.top/Article/details/gtotkepgrn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gtkktsrmpg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dashuyun.cn/Article/details/gtizegmmmw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuanzhike.top/Article/details/gtolvixkmf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ybcxt.top/Article/details/gtftsykdnz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.feifeiyinyue.top/Article/details/gtnzlbezia.html

[J09] 时区处理
来源：http://dali.chenzaomai.com/Article/details/gtuynaherl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.iojbl.cn/Article/details/gtbxtmnkai.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gtpicouqcq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtzklugydr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtsoajxnhs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gtuqrwcoci.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gtcxyxxabw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gtnrkufukf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj202588.top/Article/details/gtjnvbtjjk.html

[J10] 取今天 / 本月第一天
来源：http://dali.jlsjyb.cn/Article/details/gtepqknqgt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gtbmhadfjm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gtvwtsdksj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zycfv.cn/Article/details/gtvwmcvprj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yvedp.cn/Article/details/gtlfoknvbs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fzhhl.top/Article/details/gtbszhnhlo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yongpay.top/Article/details/gtnnkhszug.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gzhubu.top/Article/details/gtmocolbzt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtogzhkzsd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbtgryvge.html

K. JSON 与序列化
来源：http://dali.yj20258888.top/Article/details/gtslmcamah.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtfasvauir.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gtymmzodeg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gtcbkzexwc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtkkpsmdrn.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpucdjavt.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtcqrrekuq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.316326.xyz/Article/details/gtxriyftiq.html

Go:   json.Marshal(obj)
来源：http://dali.aibaodan.cn/Article/details/gtnnyzlwde.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxinkj.top/Article/details/gtrqgwtigq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hywenlv.cn/Article/details/gtixsbcnma.html

[K02] JSON 字符串转对象
来源：http://dali.guowangkeji.top/Article/details/gtnsnsdgzh.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gtulwwyezo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtijdmcefl.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtukntciqc.html

TS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gttosrcwpz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuanzx.com/Article/details/gtqpkunwft.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtpqvforqy.html

Ruby: JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtfewrshxy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.quarkkingdee.top/Article/details/gtreojdsvu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gtaemwbosi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtkwtbjuos.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gthgfnsprg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtbmvezozk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtyzyqlchk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cashguo.top/Article/details/gtykeoqrzd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gtwvrjzysf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.snrcjt.cn/Article/details/gtvmpidppj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fzhhl.top/Article/details/gtwqlppvil.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqrvnqdn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtrqgbftmk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.bjfxy.top/Article/details/gtponbddii.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtbxefqjuw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gtwmitksvy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtwmdvdgcb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtwkoyebrh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtrmuxabbb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtxwrudpjt.html

[K05] 深拷贝对象
来源：http://dali.ybcxt.top/Article/details/gtowwitema.html

Py:   copy.deepcopy(obj)
来源：http://dali.gogol.net.cn/Article/details/gtacuauiki.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xziqi.cn/Article/details/gtzkvefnvr.html

JS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtvngimhlk.html

TS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtrccbdqjm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gtpkoletup.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gtycvdoxty.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtdjbeftst.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.vqdsnc.cn/Article/details/gtbubujgcs.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gtvflfneme.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gttlxlpqiy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cdnleiting.top/Article/details/gtztvxbvhv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gthxcpouge.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtyvmtroys.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuxming.cn/Article/details/gtfodrucsi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtfhbpound.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtqkxptjsu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtqqxnbrat.html

[K07] 进制转换
来源：http://dali.jqgufenzy.top/Article/details/gtsxskaljd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtemmktdiu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gtckwwpaxh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtlxtybjwn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtjacglxbp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtkqjhtwca.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhixingplan.top/Article/details/gtmrhzzuos.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gtsyigamkg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtadkodmip.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqddgxls.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gtgboiimpn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sufxvd.cn/Article/details/gtrisjbadu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtmuscmrgs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gttnunqoaw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jlsjyb.cn/Article/details/gtkqhaitwo.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmptiybve.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtcatxhfue.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gtsqqcnhyo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtwziivxzb.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gtswzprflk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gterksiupi.html

[L01] 发送 GET 请求
来源：http://dali.yonumen.top/Article/details/gteidpxiqe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tian-w.cn/Article/details/gtwvrpizir.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sysykeji.top/Article/details/gtfaedjffx.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtesygzafo.html

TS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfaxjittz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tianlin.xyz/Article/details/gttjohhsba.html

Go:   resp, err := http.Get(url)
来源：http://dali.tanke756.top/Article/details/gtpswzmwky.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.kuanghao11.cn/Article/details/gtjdcwakcg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fzhhl.top/Article/details/gtnhlmmdsi.html

[L02] 发送 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gtivxoeypj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.meibo888.top/Article/details/gthsyitymk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zycfv.cn/Article/details/gtfejcwplo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtmgtcrewk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtcgnozspn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtlaxnkrnt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.smart0.xyz/Article/details/gtzzuyfgpj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gtpgovgqnq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gtdeolqknc.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gtunqbwddc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jiagoushi.top/Article/details/gtisbhkcrd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gtdrzvwlpr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gtdpcmkgtr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gtkjzcubof.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gtgkybpbjw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gtmbepfcir.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.meibo888.top/Article/details/gtutjouqyp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtvcwwifqb.html

[L04] 设置超时
来源：http://dali.fzhhl.top/Article/details/gtljxeswdk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gtxigydzth.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gttdlbtufh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtzkmpxnxp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkpfbaxu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dashuyun.cn/Article/details/gttxuxuboi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgufenzy.top/Article/details/gtdsyqibsx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guowangkeji.top/Article/details/gtabwaouck.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ehwqpu.com/Article/details/gtbxjvpmbp.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gtqeugrvvd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gogol.net.cn/Article/details/gtkctnjomx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipitahmf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtpaxbdrkx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmvrcgyp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuetiantiany.cn/Article/details/gtzqjcdjie.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtxspfovhv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyrekzpm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sxryk.cn/Article/details/gtaaohkumz.html

[L06] 解析响应为 JSON
来源：http://dali.birdmap.top/Article/details/gtwzfxdrkf.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gtaotznwhe.html

PHP:  json_decode($body, true);
来源：http://dali.sysykeji.top/Article/details/gtqesopsfc.html

JS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gtvesezqdm.html

TS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtfuhdqhbe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daria6918.cn/Article/details/gtdzmckavu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gtkkhpbuym.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gtijdhjyws.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.c1oappe.top/Article/details/gtctbrigvb.html

[L07] 处理 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtkrrauwkr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gtilpwaory.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gtvrthfqlf.html

JS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gtfhghccjs.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtyhcwimwn.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gtrpqwyhhu.html

Go:   resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gtypclcmrz.html

Ruby: resp.code.to_i
来源：http://dali.yj20258.top/Article/details/gthretuxqr.html


<!-- 参考信息 -->