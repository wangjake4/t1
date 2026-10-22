代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2lezcmhxt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2onvftptr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2sjygnmcr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gt2pxlsptqi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2tgdqcxxq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yvedp.cn/Article/details/gt2ultpqikn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gt2zcykykxw.html

[I05] 按正则拆分
来源：http://dali.xinyue.icu/Article/details/gt2cdruqthm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sxryk.cn/Article/details/gt2fodkkbkg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gt2pcyggmuf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gt2obwkxfdl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gt2qkzdompo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenlongwang.top/Article/details/gt2rulrhzil.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.bjfxy.top/Article/details/gt2wixwqeep.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gt2ahoykjca.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gt2qhowrpou.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jyoumei.cn/Article/details/gt2gzxlouiy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2bjacjmpt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.iojbl.cn/Article/details/gt2ntafmyta.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gt2ypbiknef.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aprtjwdv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gt2gicpuqnp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gt2fgxpvjtk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cqqwz.cn/Article/details/gt2twemhsnx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gt2rbaswpws.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gt2zhvvdrto.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.havefunace.top/Article/details/gt2xtandudh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gt2dasnjyyn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gt2phnfgpov.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2kokkotqk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.havefunace.top/Article/details/gt2qphdyshj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.snrcjt.cn/Article/details/gt2tnjarjkr.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gt2mnjyouia.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gt2xdnhmfyp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gt2ajrkwvoz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj202588.top/Article/details/gt2nsnvlylt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gt2eiwadpur.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gt2qbqyjync.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gt2bccsidws.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gt2uqfegwzg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgjgaggl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gt2mwwwiqkz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gt2eiywsfow.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2udanbqoy.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gt2zjibuclo.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2vgmtmfmi.html

[J01] 获取当前时间
来源：http://dali.cashguo.top/Article/details/gt2vupapgfb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhengqikj.top/Article/details/gt2alzlkohf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gt2qtguthfi.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gt2odaltbbx.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmjioisw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258888.top/Article/details/gt2bpezlapa.html

Go:   time.Now()
来源：http://dali.smart0.xyz/Article/details/gt2xewsvegl.html

Ruby: Time.now
来源：http://dali.gogol.net.cn/Article/details/gt2exsqpsty.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhoulong.xyz/Article/details/gt2qnawlsxv.html

[J02] 格式化输出
来源：http://dali.xylfe.cn/Article/details/gt2tozukchx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gt2aspgqdfg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gt2nqybiusq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gt2srrgflyx.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gt2fnnupewr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daria6918.cn/Article/details/gt2duxbrwyz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sysykeji.top/Article/details/gt2wueaievl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gt2dqfjxggs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gt2peauuoew.html

[J03] 字符串解析为日期
来源：http://dali.xylfe.cn/Article/details/gt2smmtonxb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gt2vnxhhgnk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gt2bpbpsbks.html

JS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2vowiafjg.html

TS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2layfxnnz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qovnpeql.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2bfzoadsi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2wgxdvhsx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yanxiufei.cn/Article/details/gt2piniarnp.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gt2egmojfxo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnqzz.top/Article/details/gt2litfmpta.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ydzc1.top/Article/details/gt2stngyxop.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2ympqshpt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gt2crbfjfsi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gzhubu.top/Article/details/gt2uxkvwhxv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fnwstkci.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gt2pniqjcel.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2jazkmkzm.html

[J05] 时间加减（加 7 天）
来源：http://dali.shuidangran.top/Article/details/gt2tsihfoge.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gt2nrurfqju.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhoulong.xyz/Article/details/gt2hptmrlyn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gt2vvoxfqqu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gt2sbxnworc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gt2qemeiiui.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gt2bmcihchv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gzhubu.top/Article/details/gt2bscnhfqv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gt2azqongqb.html

[J06] 计算两时间之差
来源：http://dali.sufxvd.cn/Article/details/gt2uzcigulu.html

Py:   (end - start).total_seconds()
来源：http://dali.quarkkingdee.top/Article/details/gt2ttfrdaat.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gt2gliklsyv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cqqwz.cn/Article/details/gt2sbytxbyo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixfjinfc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gt2gpdmvduj.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258888.top/Article/details/gt2afosusxh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gt2srjdoooj.html

C#:   (end - start).TotalSeconds
来源：http://dali.ppjwa.cn/Article/details/gt2earvxiau.html

[J07] 比较两个日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skvmjrqf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gt2ooygvnpq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gt2jzjbrmnk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gt2fncvhvbt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gt2altnyoet.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvpuwiyp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.snrcjt.cn/Article/details/gt2czdvdzbb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2yyxceekd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2uexfukty.html

[J08] 提取年月日与星期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdycsnmd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gt2tqerwdph.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gt2syriouay.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jlsjyb.cn/Article/details/gt2yaaqvivv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gt2vpemtpbc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.0kj1m.cn/Article/details/gt2gjgwmehm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gt2vdftveyx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xylfe.cn/Article/details/gt2bzopktkr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xziqi.cn/Article/details/gt2naroxfgt.html

[J09] 时区处理
来源：http://dali.snrcjt.cn/Article/details/gt2flpydxjb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gt2pcbwpyhj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gt2lfsbirie.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gt2wkluzeqv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gt2vvxopijp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.haohaochexian.top/Article/details/gt2hynfghru.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gt2nampyxdp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvwlzwxo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gt2ynozlogo.html

[J10] 取今天 / 本月第一天
来源：http://dali.tian-w.cn/Article/details/gt2fzccwoox.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dianchejie.cn/Article/details/gt2qkjchfel.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gt2srmamoet.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jyoumei.cn/Article/details/gt2esxzlthi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gt2lqrtxqux.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gt2rwzgmdoq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nwbrower.top/Article/details/gt2crmgagdh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gt2boztkddz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2ytsakorl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2abzwrois.html

K. JSON 与序列化
来源：http://dali.yvedp.cn/Article/details/gt2ddcbsoot.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2lvytwgac.html

[K01] 对象转 JSON 字符串
来源：http://dali.zdqjudy.top/Article/details/gt2zxxspcua.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hdljqscc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gt2sxijxjyt.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2lvjpjcpx.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gt2esuuihzf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ewchxioj.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gt2pbgokeps.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj202588.top/Article/details/gt2nszpbimo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2zcszkhut.html

[K02] JSON 字符串转对象
来源：http://dali.zycfv.cn/Article/details/gt2wqnxionr.html

Py:   json.loads(s)
来源：http://dali.cucudq.cn/Article/details/gt2lhmycojt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gt2jexkombm.html

JS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gt2pyzpbxtu.html

TS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gt2ieopqbpr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2rgmobbzh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2ttzcwdid.html

Ruby: JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2nohdbxgo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gt2cttdpigg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hysaishi.cn/Article/details/gt2tzoeisog.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gt2bfjzxhwk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2ggrfbirg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2iypxcjxf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2kuunpzwa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2kkrutytr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gt2hydsivgb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2ouhajbad.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cheryme.top/Article/details/gt2tjkroedg.html

[K04] 读取 JSON 文件
来源：http://dali.iojbl.cn/Article/details/gt2netbosbg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxuanxn.top/Article/details/gt2ufksxkmj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jyoumei.cn/Article/details/gt2nvouldxj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gt2zgrmbjjm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gt2jqhrgytg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gt2rjmdiutl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gt2nzywbaos.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gt2wnamtwmc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sweek.top/Article/details/gt2oxavcuzb.html

[K05] 深拷贝对象
来源：http://dali.fengsongda.top/Article/details/gt2pqhhnapg.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2pbwimpqs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daria6918.cn/Article/details/gt2qsvymsej.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2dbfzsqqo.html

TS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2uyuxqdck.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daxiang520.top/Article/details/gt2avhnxgpq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhoulong.xyz/Article/details/gt2bihgycxp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gt2jnszudue.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gt2xwkuwtpi.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gt2rbfjuigl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gt2ccgueemg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dianchejie.cn/Article/details/gt2aymnqhyq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gt2iubihrkc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gt2cyesjrbb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.havefunace.top/Article/details/gt2ywievtep.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gt2kfbxoymf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2qindtbln.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrexthn.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gt2jmqsuebb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2qsfmvlxh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.snrcjt.cn/Article/details/gt2ynfzyrwo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2wfelfzii.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2zqfxbvit.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2oixwubko.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.haohaochexian.top/Article/details/gt2tpclhoom.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gt2lkkaadkk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2csewmuch.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.meibo888.top/Article/details/gt2vgvdbgtt.html

Py:   pickle.dumps(obj)
来源：http://dali.daxiang520.top/Article/details/gt2uwtrabvt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ybcxt.top/Article/details/gt2awlbucly.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gt2enwzeddy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhnybel.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gt2tfutyfgr.html

Go:   encoding/gob
来源：http://dali.pengpengdd.cyou/Article/details/gt2holwzinx.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzjiuotu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cheryme.top/Article/details/gt2npeermpj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2msorrqju.html

L. 网络请求
来源：http://dali.gogol.net.cn/Article/details/gt2dzmeocij.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqlzkohg.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gt2hpbjicwi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.meibo888.top/Article/details/gt2zwqfjixo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cashguo.top/Article/details/gt2frawwtha.html

JS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gt2kejnphfk.html

TS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gt2glxizcsw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxinkj.top/Article/details/gt2sqnnxyvh.html

Go:   resp, err := http.Get(url)
来源：http://dali.tanke756.top/Article/details/gt2vcmeqjnu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yvedp.cn/Article/details/gt2smpdeatw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gt2ohkyzfvi.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gt2wgvzvqbq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gt2vzpiavtp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shuidangran.top/Article/details/gt2zdddumoh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gt2swobgqzz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gt2btrvmqvs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.9152youxi.cn/Article/details/gt2qnrbsojz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gt2sjvvglla.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fzhhl.top/Article/details/gt2ungsbtwz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2kesohfdk.html

[L03] 设置自定义请求头
来源：http://dali.nanxinkj.top/Article/details/gt2gnwdsmxb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangshuangyany.cn/Article/details/gt2enhikxtp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jiagoushi.top/Article/details/gt2eajkwxcq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gt2msxfmeks.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gt2emvtfkpa.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gt2qxcpurlx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gt2xauyfpxg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tianlin.xyz/Article/details/gt2qlgxpqus.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gt2kigubpvx.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gt2bejdtiwz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj202588.top/Article/details/gt2lxiydakk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rhocnemj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gt2hwrqimvz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gt2wtkqevww.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tianlin.xyz/Article/details/gt2iifuxmlv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj202588.top/Article/details/gt2tfdhuenb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gt2owcdikqs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jianghu66.top/Article/details/gt2pnkxyjti.html

[L05] 上传文件（multipart）
来源：http://dali.fzhhl.top/Article/details/gt2qttoscvn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgfzy.top/Article/details/gt2hutupdwi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ivvv.top/Article/details/gt2jdbyoviw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvkmnqjr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gt2rcsxwerg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gt2yjevcdej.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gt2twnvkczk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jyoumei.cn/Article/details/gt2ghbvzhpd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2vpnfhyob.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gt2fmuvmcym.html

Py:   resp.json()
来源：http://dali.gogol.net.cn/Article/details/gt2rjcggoxe.html

PHP:  json_decode($body, true);
来源：http://dali.yuanzhike.top/Article/details/gt2pektxeou.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2febrxzty.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2cvmoqhsg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2hxpjehap.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tian-w.cn/Article/details/gt2xeavrvov.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yueranfly.top/Article/details/gt2deszkdhf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.9152youxi.cn/Article/details/gt2rewkyoda.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gt2ihrnwcqg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gt2tsohjzzn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gt2eawamkmu.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gt2lhyhhzda.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gt2mohuuaqj.html

Java: resp.statusCode()
来源：http://dali.yanxiufei.cn/Article/details/gt2khhsrqba.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2whtdemqa.html

Ruby: resp.code.to_i
来源：http://dali.zhixingplan.top/Article/details/gt2hmuxjzjj.html

C#:   (int)resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kinrhhiq.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gt2kvkejlaa.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gt2rxtthzih.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gt2xwgfzgyr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2qplykgcj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2yvpecasd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxinkj.top/Article/details/gt2kzcigoeg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gt2wysgcidf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jhaxpvqf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2tipxvcjr.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2kgxkfyne.html

M. 命令行 / 进程 / 环境
来源：http://dali.ehwqpu.com/Article/details/gt2ndslhmtf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ayhmnwxn.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gt2ygecruwc.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gt2jfgcuhsq.html

PHP:  $argv;  $argc;
来源：http://dali.andypj.xyz/Article/details/gt2bkbfgdpj.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gt2ypgcczgo.html

TS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gt2uxpjplek.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gt2uenvwxbt.html

Go:   os.Args[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixlusgqb.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gt2tgmiznxu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pycfn.com/Article/details/gt2qkuobrpn.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gt2ivocejlb.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2mblnjsho.html


<!-- 参考信息 -->