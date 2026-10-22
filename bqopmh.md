代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2wegxnyls.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ykzjtnlv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rlxzfymu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gt2toeykxaq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigfzy.top/Article/details/gt2sdgtxbcu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfwwumgp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2alwmvedx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gt2vymfjvkr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gt2ylktyvfu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2htgwtnvc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gt2nbtpkqen.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gt2symukech.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gt2tybllfjk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2nqnohnnh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gt2vcsqmgkn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pycfn.com/Article/details/gt2kvffietk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gt2rkwitxvi.html

[I07] 忽略大小写与多行模式
来源：http://dali.gogol.net.cn/Article/details/gt2hscryiza.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gt2wpkzrnjv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gt2dizdbxuy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gt2miplfogc.html

TS:   /error/gim
来源：http://dali.nwbrower.top/Article/details/gt2txtboalm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgfzy.top/Article/details/gt2erbkpbvq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gt2authhnqm.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxinkj.top/Article/details/gt2fblkbcgi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cheryme.top/Article/details/gt2nfqrakbs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigufen.top/Article/details/gt2pcwxmuug.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenzaomai.com/Article/details/gt2mwucmfqk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gt2hkykujjm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gt2xopnxfcc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gt2skdshtea.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gt2lpxfjpyf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gt2lymmltet.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ucgwpttr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gt2efjehotj.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2niphponw.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gt2odwyzcrp.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2spyxvlug.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gt2ckwwcomg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gt2ekobicej.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gt2bxosobvn.html

JS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gt2asxmccrr.html

TS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gt2vobuuvta.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsjmjjsv.html

Go:   time.Now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2vorpgktn.html

Ruby: Time.now
来源：http://dali.shzxlz.cn/Article/details/gt2pywhnnas.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yangfankeji.com/Article/details/gt2vhjpnobs.html

[J02] 格式化输出
来源：http://dali.fengsongda.top/Article/details/gt2novichot.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gt2ktdxqaro.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gt2ueiyrqfn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gt2krzrvtgh.html

TS:   d.toISOString()
来源：http://dali.fengsongda.top/Article/details/gt2yevwrpmd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj202588.top/Article/details/gt2uckcwjax.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njgglyfp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gt2ohzkqokb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.snrcjt.cn/Article/details/gt2rznikszk.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gt2zgamdpmj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yueranfly.top/Article/details/gt2uongnjvf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2viavzstj.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2iowhcdbf.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2znexzjlr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2aieeokwk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2alafjztt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2dizsofup.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sufxvd.cn/Article/details/gt2krejvize.html

[J04] 时间戳与日期互转
来源：http://dali.snrcjt.cn/Article/details/gt2hdiiaayt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2yufbnmvp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gthnauix.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gt2ijdyhgcr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gt2woumgkjt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gt2jkxyewoo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2fcmhtbbx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ivvv.top/Article/details/gt2yadidbma.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2iobtcvkq.html

[J05] 时间加减（加 7 天）
来源：http://dali.fzhhl.top/Article/details/gt2dwhnqpdv.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gt2djpmrwue.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gt2xjfnjlwa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gt2wimzucmr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gt2gdemsisz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gt2rwzbqqmn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.birdmap.top/Article/details/gt2bzdwinmo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xinyue.icu/Article/details/gt2oqnhdlyc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gt2nipiniij.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqakddrx.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigfzy.top/Article/details/gt2tvpunipt.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dlfyuupu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tianlin.xyz/Article/details/gt2ovgsoazw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigufen.top/Article/details/gt2pnmykrau.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigfzy.top/Article/details/gt2qzzidzpy.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gt2cbipzjor.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gt2jhiwqjsb.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gt2ihecdfrh.html

[J07] 比较两个日期
来源：http://dali.zdqjudy.top/Article/details/gt2ianwhamm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2fxmabwfu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gt2spgmkycu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gt2dwwscadu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vqoxbifd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.kuanghao11.cn/Article/details/gt2rhqycjik.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qkxpqnkc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gt2jhfkubzl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gt2capixjco.html

[J08] 提取年月日与星期
来源：http://dali.yj202588.top/Article/details/gt2hncelase.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yvedp.cn/Article/details/gt2vgofaqaj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.andypj.xyz/Article/details/gt2vmwsiqfb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yanxiufei.cn/Article/details/gt2sgwasdeb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gt2ykysjcpk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenlongwang.top/Article/details/gt2onywdhkq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ehwqpu.com/Article/details/gt2ovchpbtm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.havefunace.top/Article/details/gt2jtbmeepp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daria6918.cn/Article/details/gt2yajlereb.html

[J09] 时区处理
来源：http://dali.jlsjyb.cn/Article/details/gt2jxgbqozk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hysaishi.cn/Article/details/gt2mhbxodod.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cdnleiting.top/Article/details/gt2himkpywo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gt2ctiyfmfr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gt2mmnabjjv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258888.top/Article/details/gt2hniqteqt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cashguo.top/Article/details/gt2ybajeztm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.haohaochexian.top/Article/details/gt2cawoegjc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gt2yuubuomk.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gt2eeqqzmil.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.iojbl.cn/Article/details/gt2hvtsxuil.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gt2mqgihilo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gt2xexdpbpo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2hfnysgbn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yonumen.top/Article/details/gt2fzcizuvf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqgshgle.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgufenzy.top/Article/details/gt2ymbbnpzl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuanzx.com/Article/details/gt2ivmkwvfr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2goefkamo.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gt2ibsrrpcn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltvruodq.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gt2hcluyzbe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gt2mdwbysrh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fvuqkuvx.html

JS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gt2ubvaxfoe.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gt2qyrqzzmd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ivvv.top/Article/details/gt2frtnsany.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2faczlvmg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gt2qspymrcw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvduaudw.html

[K02] JSON 字符串转对象
来源：http://dali.hnxiangtu.top/Article/details/gt2squwyogs.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gt2cjsnnrhq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ivvv.top/Article/details/gt2vqnfltzp.html

JS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gt2vqmexulc.html

TS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gt2vrconxgc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2ckbzdpfn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gt2azuqujvy.html

Ruby: JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2kwveemjl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gt2ycikqtlx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gt2mbohgqii.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gt2gnkuvijn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gt2qejraplc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gt2kmdbvdvz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qskbydvd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rmstxbla.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gt2prqyjqtx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2odkqxyxw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gt2njfldinm.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gt2qidswnnb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gt2xmhlkuqp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvkgqjst.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gt2oydsvphm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gt2trupbrlw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxgsispr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gt2flurrpjf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tian-w.cn/Article/details/gt2zexwkhin.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gt2kdcujimw.html

[K05] 深拷贝对象
来源：http://dali.gzhubu.top/Article/details/gt2cdowthrq.html

Py:   copy.deepcopy(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2pjbjkosi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ehwqpu.com/Article/details/gt2apbcvpon.html

JS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gt2qfmchyes.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkilaydx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.andypj.xyz/Article/details/gt2dqwmslio.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tian-w.cn/Article/details/gt2ebgkjbyz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dashuyun.cn/Article/details/gt2iwxznkqy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2otdxcgij.html

[K06] 解析 URL 查询串
来源：http://dali.chenlongwang.top/Article/details/gt2cjlidnoz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gt2qtvyxyzx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gt2jaisrteq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gt2ooikxzap.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gt2nzaiwkoh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gt2dihcxtky.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2lytusprz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gt2jrcqocub.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gt2bhamrpft.html

[K07] 进制转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2necmyqrf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2vbqagbmu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.0kj1m.cn/Article/details/gt2snplgaxy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2kjboyose.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2sgiudwlh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2ypakhyti.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2luujlybc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.smart0.xyz/Article/details/gt2myxwasmb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2gcuhhnix.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.meibo888.top/Article/details/gt2fgmfnuzf.html

Py:   pickle.dumps(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2bfcbxvez.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gt2tfmdvsjs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gt2mcqqqaws.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gt2twipfshj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ppjwa.cn/Article/details/gt2phssabal.html

Go:   encoding/gob
来源：http://dali.sweek.top/Article/details/gt2ydmamghb.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2gmmvytst.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gt2rkhqvxma.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2jhlbthds.html

L. 网络请求
来源：http://dali.aibaodan.cn/Article/details/gt2ybkoomqp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2mqmfyups.html

[L01] 发送 GET 请求
来源：http://dali.redwolf501.top/Article/details/gt2cwgdvcyb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.vqdsnc.cn/Article/details/gt2rzjlvsne.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hysaishi.cn/Article/details/gt2tbktxzpp.html

JS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gt2rcyubher.html

TS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2ndrwfhiu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangshuangyany.cn/Article/details/gt2mvlxbhix.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2submvbms.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhongyouzk.top/Article/details/gt2xnnkyspp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuanzx.com/Article/details/gt2xrdvmwvv.html

[L02] 发送 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gt2hyunnuos.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wcoathfd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gt2bvkwxgkt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gt2ankjhjav.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gt2ltglukzz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nwbrower.top/Article/details/gt2gpjfezen.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gt2rncewroa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gt2dyblovik.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bkxbbnsx.html

[L03] 设置自定义请求头
来源：http://dali.yongpay.top/Article/details/gt2qqxchysh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gt2fnxsiber.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jianghu66.top/Article/details/gt2nkyncsgu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gt2vjupxmnf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gt2kzmnfnue.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gt2cmrhriph.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gt2lrilhnzz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2edscqikm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gt2rfernasj.html

[L04] 设置超时
来源：http://dali.snrcjt.cn/Article/details/gt2uwjawfav.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gt2xgsntvpc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hgzfbkyv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gt2anotdzyw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gt2wcwcvhkt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhpmhizn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuanzhike.top/Article/details/gt2bcjclfqc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gt2weqlcrey.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gt2wohybaiu.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gt2aujbofaq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwueizx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangdashe.top/Article/details/gt2hshdydvd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gt2yuljxwqs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gt2itzmbtsl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pengpengdd.cyou/Article/details/gt2elufdwke.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgfzy.top/Article/details/gt2lhkshijs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2brugxicz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2ifjmdrcn.html

[L06] 解析响应为 JSON
来源：http://dali.daria6918.cn/Article/details/gt2nrvzpben.html

Py:   resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2sgiyuuwm.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gt2yomrrvwk.html

JS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbasnthc.html

TS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gt2erhrzgad.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2rjqmevrr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.316326.xyz/Article/details/gt2rwlhaejt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gt2wciyrbfa.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gt2flvauovw.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gt2llcnomjh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gt2uxtqgppg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gt2osaqztaj.html

JS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gt2mhsnuilg.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gt2alwuwvcg.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gt2hcbnicox.html

Go:   resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gt2snajpjcq.html

Ruby: resp.code.to_i
来源：http://dali.shuidangran.top/Article/details/gt2infbpgdf.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hclrclgw.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rjonttlo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gt2tuqfmezq.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gt2xnhwoskk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2ntmdfhum.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gt2rzhqkdzl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gt2abhsxmcj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlghfwk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gt2gmrevfqa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2ijmpucxj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2slbpofga.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gt2ootlisxt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2wwdwginc.html

[M01] 读取命令行参数
来源：http://dali.iojbl.cn/Article/details/gt2dfrexkun.html

Py:   sys.argv[1:]
来源：http://dali.hywenlv.cn/Article/details/gt2iwkdfgqg.html

PHP:  $argv;  $argc;
来源：http://dali.iojbl.cn/Article/details/gt2mylwxhiw.html

JS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gt2piwydjiq.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gt2oezuhbeb.html

Java: args 数组（main 方法参数）
来源：http://dali.havefunace.top/Article/details/gt2mkndemke.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2epqssnqr.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gt2sghdpupe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gt2zctfyxqa.html

[M02] 读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gt2gmxkwzzn.html

Py:   os.environ.get("HOME")
来源：http://dali.tanke756.top/Article/details/gt2bbbmpvxp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gt2zuvktovy.html

JS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gt2vswnussj.html

TS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cojeirvf.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2cvsojeea.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aizwys.cn/Article/details/gt2yxnxmgpw.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gt2owbpwuhd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pmdwtkan.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gt2ievtkrhp.html


<!-- 参考信息 -->