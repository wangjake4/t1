代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gtlkqvxijm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcbarcqq.html

[I04] 正则替换
来源：http://dali.nanxuanxn.top/Article/details/gtcjxytdsg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtnyhedlbd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtuppkijze.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtyjzidfdo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtmtreazsn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtwiiqaadp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hywenlv.cn/Article/details/gttevmthrv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cashguo.top/Article/details/gtvuapurup.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtdjcbzmmi.html

[I05] 按正则拆分
来源：http://dali.haohaochexian.top/Article/details/gtjseyblbx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.9152youxi.cn/Article/details/gtyxpbgtjy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.mhx1999.top/Article/details/gtyevuabfk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtpuphuvpc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtzsijlzon.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sufxvd.cn/Article/details/gtgaqotxrd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtchtgwmix.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtvtimpkag.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenlongwang.top/Article/details/gtcoljbhqn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.316326.xyz/Article/details/gtncieknlv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtecucbmjn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xinyue.icu/Article/details/gtwjjgvojx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtbnynjjnu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtnncsljhb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtobpxvupy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gtunvhoqfr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcxwfwob.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtebqctsre.html

[I07] 忽略大小写与多行模式
来源：http://dali.zycfv.cn/Article/details/gtmhaklfhw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daria6918.cn/Article/details/gtpazlahux.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtjunlnmko.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gtyxrrbuwm.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gtrdsiwsis.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shuidangran.top/Article/details/gtrxmynqaj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aizwys.cn/Article/details/gtzrqqaqnq.html

Ruby: s.scan(/error/i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqearfesb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.feifeiyinyue.top/Article/details/gtrfxbvguq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gtwwxuyhqh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gttgqsrago.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtoroasrzt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtlmlnwchu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gtfrzvzaiy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtznxqusen.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gtvvwkhsxl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dashuyun.cn/Article/details/gtyhbozaqs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtntnwjaig.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthjzrprtz.html

J. 日期与时间
来源：http://dali.shuidangran.top/Article/details/gtkqcotxxz.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtpvecjave.html

[J01] 获取当前时间
来源：http://dali.ppjwa.cn/Article/details/gtovpkeqdh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gtzaejuuxs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gteivqttcf.html

JS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtpddmaamm.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gtiddbtnze.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gtooafoawx.html

Go:   time.Now()
来源：http://dali.gotoacloud.top/Article/details/gtwfobbchh.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gtwumnukpf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gtllkoabfv.html

[J02] 格式化输出
来源：http://dali.ivvv.top/Article/details/gtebkuewvi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gtebsvgkss.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtqjoxbsqf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yongpay.top/Article/details/gtlcowtblo.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gthflrkhpa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gotoacloud.top/Article/details/gtouuofzkc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ydzc1.top/Article/details/gtvmubufoy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gtkrfnwurl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuanzx.com/Article/details/gtwdpbfrka.html

[J03] 字符串解析为日期
来源：http://dali.gzhubu.top/Article/details/gtudookejt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuxming.cn/Article/details/gtvweiqsqe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuanzhike.top/Article/details/gtqguenfsy.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtmdyvskyj.html

TS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtvmkxjxyx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtrqiwkrtx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtggzfdero.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gthayqtugk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gtqgihziwf.html

[J04] 时间戳与日期互转
来源：http://dali.gotoacloud.top/Article/details/gteuaxbcgl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tanke756.top/Article/details/gtupjobauk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gtkdbsthga.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gthumvhyon.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yangfankeji.com/Article/details/gtkgpemejo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gtxoccozrt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.c1oappe.top/Article/details/gtlfhhwvny.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ivvv.top/Article/details/gtwuofiriz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sweek.top/Article/details/gtntnkdbkq.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxudgctmg.html

Py:   now + timedelta(days=7)
来源：http://dali.tian-w.cn/Article/details/gtyqsijhnp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nwbrower.top/Article/details/gtqssgmtws.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtqyqxxvhr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtxvhtqaut.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuxming.cn/Article/details/gtxrwqebwh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gtupeipqgh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daxiang520.top/Article/details/gtxhafmzdu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtvdyzgqrw.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangtech.top/Article/details/gtcupdiupm.html

Py:   (end - start).total_seconds()
来源：http://dali.316326.xyz/Article/details/gtccjkhfox.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gtmabkedmn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gtbdczgjdt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gthtleqdpw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhixingplan.top/Article/details/gtmeahyzkp.html

Go:   end.Sub(start).Hours()
来源：http://dali.fengsongda.top/Article/details/gtlsxwccda.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnxiangtu.top/Article/details/gtmgssxjyb.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gthjytvmms.html

[J07] 比较两个日期
来源：http://dali.shangyingyoupin.top/Article/details/gtfvccirni.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtqpvxmgqr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258.top/Article/details/gtqofaxljd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtwadljaze.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtauhmrgyi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkvbfqhq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gtvpxiopnp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtfjojlatl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtkyzgxycg.html

[J08] 提取年月日与星期
来源：http://dali.wangshuangyany.cn/Article/details/gttylxkueo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gtahwwqgaq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hongshengwenyu.top/Article/details/gtvriciksw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuanzx.com/Article/details/gtsuxkykai.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.0kj1m.cn/Article/details/gtjxdthmhd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gtxgbjrbdj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ydzc1.top/Article/details/gtpvdkxvhp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.kuanghao11.cn/Article/details/gtjmqlzjwt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gtzbwnpnbb.html

[J09] 时区处理
来源：http://dali.nwbrower.top/Article/details/gthcemrjsg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gtvvxlkkei.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gtmronlbbu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gtgmlomcat.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtimonzvbk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gtfnqmigvi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.c1oappe.top/Article/details/gtpyaxodil.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zdqjudy.top/Article/details/gtqzdomlhy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xylfe.cn/Article/details/gtjtxsmbcr.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhlnhjfe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuxming.cn/Article/details/gtkegxoxiz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gtwhonnytg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.redwolf501.top/Article/details/gtvwsahbye.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gthxthhxtx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pycfn.com/Article/details/gtibdmuzmy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tianlin.xyz/Article/details/gtuxdktntg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guannengcc.top/Article/details/gtzruiuulf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtbjanhkmi.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqgwkkizi.html

K. JSON 与序列化
来源：http://dali.vqdsnc.cn/Article/details/gtkpwtibau.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcvwgedm.html

[K01] 对象转 JSON 字符串
来源：http://dali.sysykeji.top/Article/details/gtxybhniyp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfepkepl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gtijhfyrah.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtzxnikcqp.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtlgnkumdn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpgxqktq.html

Go:   json.Marshal(obj)
来源：http://dali.smart0.xyz/Article/details/gtfesjgmuf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangdashe.top/Article/details/gtibwznass.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvjesatd.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtgyortkmb.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gtytxihjpf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gtvjmuzzco.html

JS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtdxqwgxaq.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtqnvdaokt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.redwolf501.top/Article/details/gtjjbzucql.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtpzqdxcce.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtpgqwterz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gtcrliionb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gtgifxyncl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtpgitqyom.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gthyrtauks.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtgkggcfuv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gtaghckmja.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gtozxkomgy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gtkfykasdp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtstzokqci.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gtfpcvsqce.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gtegjoqvwl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ehwqpu.com/Article/details/gtqtfipggr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gtynrhruxf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtodmiomco.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtofhhnuxz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtdhhjyuzd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtwooblphb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtoewvleus.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtszgbnaft.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gtzerhsqir.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gttrqbaahz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gtvokiszac.html

JS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtudxdgkav.html

TS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gteujugata.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.316326.xyz/Article/details/gtznpoacpi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.iojbl.cn/Article/details/gtebprnzmv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.andypj.xyz/Article/details/gtbsnpznfp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gtiuirsbxl.html

[K06] 解析 URL 查询串
来源：http://dali.daxiang520.top/Article/details/gtnuymqtmk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sxryk.cn/Article/details/gtjtofvska.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.iojbl.cn/Article/details/gtizjtwhjy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbupfqvrw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gtlyfqwvzz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fzhhl.top/Article/details/gtzsduywnz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtpnzitfww.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtupiodwoc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtchnooxlg.html

[K07] 进制转换
来源：http://dali.zhiwuduotai.top/Article/details/gtdtlhveof.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtlrbksabe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuanzhike.top/Article/details/gtnqrdqbou.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtazmohqfx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtcgvbpynj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuxylmpv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gtcbpzdlzo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aibaodan.cn/Article/details/gtprhhcimr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtauibwbjl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cheryme.top/Article/details/gtlnmblbok.html

Py:   pickle.dumps(obj)
来源：http://dali.0kj1m.cn/Article/details/gtatlirbsp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gtlutomseu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gtesqifaiq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtyfvbzyfb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigfzy.top/Article/details/gticvbcfxw.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gthmkxzidp.html

Ruby: Marshal.dump(obj)
来源：http://dali.ppjwa.cn/Article/details/gtdvsmamek.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.meibo888.top/Article/details/gtidslmqau.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtovkkxahj.html

L. 网络请求
来源：http://dali.pengpengdd.cyou/Article/details/gtfqkjbtpn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtalheuxbu.html

[L01] 发送 GET 请求
来源：http://dali.tianlin.xyz/Article/details/gthlvxzmhj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.vqdsnc.cn/Article/details/gtbmdexgvi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigfzy.top/Article/details/gtrcnpzbsw.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddavxwlf.html

TS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtptxukejz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cashguo.top/Article/details/gtosobgmed.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258888.top/Article/details/gtvwckvzil.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxtzjzka.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtsyangzlj.html

[L02] 发送 POST JSON
来源：http://dali.pycfn.com/Article/details/gtwljiuwob.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtwmtzcmxm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yongpay.top/Article/details/gttsifaogw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gtfshdglvh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnyylspk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tianlin.xyz/Article/details/gttuqomjsx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258888.top/Article/details/gtydjutrxm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gtjfoxgnsn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gteogknyuf.html

[L03] 设置自定义请求头
来源：http://dali.sweek.top/Article/details/gtwewjdfih.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhiwuduotai.top/Article/details/gtnjegvxgy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yongpay.top/Article/details/gtmpewsfsz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gtloauecnx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gtwzbnswkr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jyoumei.cn/Article/details/gtbryyjjli.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplvfnzmn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gtqvynglly.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gthkezyrzz.html

[L04] 设置超时
来源：http://dali.kuanghao11.cn/Article/details/gthzejyzak.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daria6918.cn/Article/details/gtlqcnzdpf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvzqmlhw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gtuwazhpqu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtzxmbtlvk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gtxssvqirf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gtfajodkan.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gtopmgodzn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sweek.top/Article/details/gterdxjdqm.html

[L05] 上传文件（multipart）
来源：http://dali.jiagoushi.top/Article/details/gtgornikwg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pengpengdd.cyou/Article/details/gtyswflmor.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gtrtmahgxg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gthsmkdxqf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gthqddgwzv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.meibo888.top/Article/details/gtifnbgdbu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gtrbyqnfow.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gtzqdiosen.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gtwcobhpcd.html

[L06] 解析响应为 JSON
来源：http://dali.yonumen.top/Article/details/gtorxhpfeb.html

Py:   resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtrnomryfw.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gtqckcstwl.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtjmemnhkd.html

TS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtalwtowtk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtyrhisikm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gtnvqtcutt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fengsongda.top/Article/details/gtckopfawu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gtxdqkblcu.html

[L07] 处理 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtsuxzvqta.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gtavjykrpi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.meibo888.top/Article/details/gtzdlnnxte.html

JS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gtkbcarent.html

TS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gtoocoxzpw.html

Java: resp.statusCode()
来源：http://dali.sweek.top/Article/details/gthckqezdz.html

Go:   resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gttrbejlmu.html

Ruby: resp.code.to_i
来源：http://dali.yvedp.cn/Article/details/gtbsbwahtd.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtvyeoblus.html

[L08] 并发请求多个地址
来源：http://dali.hammf.cn/Article/details/gtaxejauzj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gtjjimbeat.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gtjtpsqisi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtsuckgxyp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtulikstjy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gthzzacmvx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jiagoushi.top/Article/details/gtwwqfflqu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gtcfafggxq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gtpohsanag.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteveiomvn.html

M. 命令行 / 进程 / 环境
来源：http://dali.meibo888.top/Article/details/gtaamicuvn.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaieuyafl.html

[M01] 读取命令行参数
来源：http://dali.sxryk.cn/Article/details/gthclzzucy.html

Py:   sys.argv[1:]
来源：http://dali.chenlongwang.top/Article/details/gtwpicmqdk.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gtxzywtzee.html

JS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gttdctzgex.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtvghokcmw.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtworhwszh.html

Go:   os.Args[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtvllgqhug.html


<!-- 参考信息 -->