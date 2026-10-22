代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.haohaochexian.top/Article/details/gtxdtzhbsg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gtpujizawo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gtphwvscqc.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gtoydaldhr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdudljvg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtfoapvqdj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtmywpyubx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtifytntsn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.smart0.xyz/Article/details/gteuaxcvgp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gthesdemjs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtqnkrbsuz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xziqi.cn/Article/details/gtzdepnnhy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gtlvsvvfeh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtdithedqv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.haohaochexian.top/Article/details/gtpabnlobp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gtxvotpvfi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gttuttwlow.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtoftatcfk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.andypj.xyz/Article/details/gtohvbqtxi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gtlsjglgyf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtvkgfwvow.html

[I07] 忽略大小写与多行模式
来源：http://dali.0kj1m.cn/Article/details/gtnwaajljr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cqqwz.cn/Article/details/gtkbpnciun.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtjebqcows.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gtbtklpgqp.html

TS:   /error/gim
来源：http://dali.zhixingplan.top/Article/details/gtdprhkdep.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnqzz.top/Article/details/gtnbfrgwuk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aibaodan.cn/Article/details/gtazmkthvg.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gtpvcdhsbl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gtxhzrqnzk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigufen.top/Article/details/gtznsoxhxs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.c1oappe.top/Article/details/gtakpmwnag.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gttuwmkame.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtxxhjmneh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtwcsotxsb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gtoijmoceq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gtqongwtds.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gtdzslchcn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidsidcwl.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtiokvrrqh.html

J. 日期与时间
来源：http://dali.c1oappe.top/Article/details/gthwawevji.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtejdljioy.html

[J01] 获取当前时间
来源：http://dali.316326.xyz/Article/details/gtjvsgbyap.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yvedp.cn/Article/details/gtvmtdyodb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtfhscgvce.html

JS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtrotkaxix.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtxcjbdfzy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guannengcc.top/Article/details/gtmlqocorj.html

Go:   time.Now()
来源：http://dali.aizwys.cn/Article/details/gtlxroavwn.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrkpbpqa.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gtvricqbsi.html

[J02] 格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtvlmrscjv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtpiydhuvz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gtnvrlbvbf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnxiangtu.top/Article/details/gtuatavprk.html

TS:   d.toISOString()
来源：http://dali.yongpay.top/Article/details/gtsitvdiel.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangtech.top/Article/details/gtwolufjtv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj202588.top/Article/details/gtafvktapd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gtirvbrvok.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxchbpkn.html

[J03] 字符串解析为日期
来源：http://dali.cashguo.top/Article/details/gtpmnuaprh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gtsopcnglb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yongpay.top/Article/details/gtcelorthg.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtrbtbdnce.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtjaqnnkhh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtocqresyv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtbjsllive.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtfnvjpili.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zdqjudy.top/Article/details/gtyuwfwafs.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gtgfjhrhtw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gtaxpovdjn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gtyqszslac.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cdnleiting.top/Article/details/gtoeaxfsdi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gtdyuqcfft.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yongpay.top/Article/details/gtsdfybdvl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gtxlhdvyjw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gotoacloud.top/Article/details/gtrjzamtbn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nwbrower.top/Article/details/gtybkuqvmi.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gtlywpbbev.html

Py:   now + timedelta(days=7)
来源：http://dali.nwbrower.top/Article/details/gtfyrixpoa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jyoumei.cn/Article/details/gtcmiusghv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtgnhxador.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gtrwrtbbcp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gthzaefnyz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gtqcgzxhrl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gtpayxwbur.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gtjakobohx.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gtgvstjtbl.html

Py:   (end - start).total_seconds()
来源：http://dali.havefunace.top/Article/details/gtxsaapqff.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigfzy.top/Article/details/gtatpriznh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gtewahlufb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cucudq.cn/Article/details/gtrfpgzbok.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnyndwgg.html

Go:   end.Sub(start).Hours()
来源：http://dali.shzxlz.cn/Article/details/gthbfnhedp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gtqkqcyjyu.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gtgmdhojrz.html

[J07] 比较两个日期
来源：http://dali.cashguo.top/Article/details/gtppfifidg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtzpcyytqi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ppjwa.cn/Article/details/gtgrxwpadz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gtyeswdkbl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtpjmrrmcz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gzhubu.top/Article/details/gtuoryrdha.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gtbuveiprb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtukdghakb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtgaebhjfx.html

[J08] 提取年月日与星期
来源：http://dali.havefunace.top/Article/details/gtjdknhctx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangshuangyany.cn/Article/details/gtcwllsicb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.9152youxi.cn/Article/details/gtqhxnbvmt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwkqasgi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gthtugyhuc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hongshengwenyu.top/Article/details/gtfimpfgzr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.svipenyu.cn/Article/details/gttzrfxyyy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nwbrower.top/Article/details/gtvkkedtam.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gtffftfkqd.html

[J09] 时区处理
来源：http://dali.hnqzz.top/Article/details/gtgydplcpb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.0kj1m.cn/Article/details/gtwwfizmmn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ybcxt.top/Article/details/gtlgcncwuh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtbtfdetqw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gtxttfwuzi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gtntkquvlq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gtkcbkegfp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daxiang520.top/Article/details/gtnkqvivoz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dianchejie.cn/Article/details/gtfjvomxzs.html

[J10] 取今天 / 本月第一天
来源：http://dali.ppjwa.cn/Article/details/gtcofeejft.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gtqcchinlp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigufen.top/Article/details/gtdisjuxxq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yvedp.cn/Article/details/gtteiozjae.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ppjwa.cn/Article/details/gtkhkznxep.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ppjwa.cn/Article/details/gterkybwjc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gaohongyu789.top/Article/details/gtymdmokuq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ydzc1.top/Article/details/gtjxdoujxa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gtpzlhigqy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtgfakcfte.html

K. JSON 与序列化
来源：http://dali.iojbl.cn/Article/details/gtoqqzdhkw.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtlexcunkk.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258.top/Article/details/gtrtvyvxbs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtbxtbagpq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkeaxqwhh.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtoqedxyal.html

TS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtegtodhan.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tianlin.xyz/Article/details/gtoqfbajrt.html

Go:   json.Marshal(obj)
来源：http://dali.sufxvd.cn/Article/details/gtnqwqssxh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gtdkiqcdqv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gtronouthu.html

[K02] JSON 字符串转对象
来源：http://dali.havefunace.top/Article/details/gtgdfjjurb.html

Py:   json.loads(s)
来源：http://dali.dashuyun.cn/Article/details/gthzdfmeyi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.meibo888.top/Article/details/gtwjajdsgb.html

JS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtaxohiqlq.html

TS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthewtiivh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhmjjbjj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gtlmqminon.html

Ruby: JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjatocpkl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.mhx1999.top/Article/details/gtagfoffyj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.birdmap.top/Article/details/gtalfzupfv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gthnreohsf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhaatmcb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtorwgrrto.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtorolfthd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jyoumei.cn/Article/details/gtpwaayrsq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gtmbjegdhu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sufxvd.cn/Article/details/gtkbzbenxh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenjidiqi.icu/Article/details/gtosrcevgo.html

[K04] 读取 JSON 文件
来源：http://dali.c1oappe.top/Article/details/gtgfichkgr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gtphyzvnbj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgfzy.top/Article/details/gttmlkpwkx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtswdwtncs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtoolnfktd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtuzpsgcqn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtlgjvqxxn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cheryme.top/Article/details/gthezfsmfe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtiblgxvhd.html

[K05] 深拷贝对象
来源：http://dali.zhongyouzk.top/Article/details/gtwlwiojeu.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gtqsehnqfz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gtjvxqqzmf.html

JS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtrsmmspml.html

TS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtvhjvhbee.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.snrcjt.cn/Article/details/gtjsnifkoi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gtwrslkqyn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gthyscmtam.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gtpocybeke.html

[K06] 解析 URL 查询串
来源：http://dali.chenlongwang.top/Article/details/gtkexyuysa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gtozhrolcp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.haohaochexian.top/Article/details/gtktqgayxx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gtrrebywab.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtzmsfntfe.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gtzaulwvcv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdevqusmw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyxbhbxj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtncytzhlk.html

[K07] 进制转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxnythrm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtheajkovq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gtywsjpupc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gttqkawdvr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtyfhfofak.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gteggswebu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuanzx.com/Article/details/gtwpndgtbs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gogol.net.cn/Article/details/gteybkwzvb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtngqrjrca.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gthselfnvy.html

Py:   pickle.dumps(obj)
来源：http://dali.ppjwa.cn/Article/details/gtmixdbkir.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gteyowwidd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gtesdtjobx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtecwfswtu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.bjfxy.top/Article/details/gtnigncyzz.html

Go:   encoding/gob
来源：http://dali.redwolf501.top/Article/details/gtrsphobjz.html

Ruby: Marshal.dump(obj)
来源：http://dali.cqqwz.cn/Article/details/gtxgqicztf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtvdququto.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtfljztyoj.html

L. 网络请求
来源：http://dali.daxiang520.top/Article/details/gtvgxrrkjs.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtqqozjwfd.html

[L01] 发送 GET 请求
来源：http://dali.yuxming.cn/Article/details/gtakoibdot.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gtvvceeyax.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ywan-chungtsiang.top/Article/details/gtveluaqao.html

JS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtudhtnqif.html

TS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gtxrtgavlp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gtkplwqsod.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtlvwhcihp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenzaomai.com/Article/details/gtgaiotakl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cheryme.top/Article/details/gtygnyrlns.html

[L02] 发送 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gtcleziyke.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtoowvrubf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.andypj.xyz/Article/details/gtgapmeuen.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyumtxlc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtslwjtwkp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xylfe.cn/Article/details/gthibjeymz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aibaodan.cn/Article/details/gteoslnzco.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gtzkpqxxpj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xylfe.cn/Article/details/gtwbfgnfio.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gthjgvnfzh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhengqikj.top/Article/details/gtzrfrjmww.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenjidiqi.icu/Article/details/gthnyatciv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtkvyeucyi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gtauwhvfim.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gtjpzrnppg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gttbkusrjs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gtmatvgojg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtitzrlbpv.html

[L04] 设置超时
来源：http://dali.jinqigufen.top/Article/details/gthgoorcwo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxyjqwlw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yueranfly.top/Article/details/gtmuflqsoe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gtxhxnrczj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtqvvsmxjj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fengsongda.top/Article/details/gtrbjwmbkt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sweek.top/Article/details/gtstcmkrmf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gtfuqxhdmg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.bjfxy.top/Article/details/gtktviahcf.html

[L05] 上传文件（multipart）
来源：http://dali.sxryk.cn/Article/details/gtsftxytrm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gotoacloud.top/Article/details/gtsmwhplfq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gtlafiafgs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gtvutdwmhp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtpbsfkwra.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenzaomai.com/Article/details/gtqxsjoanw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuanzhike.top/Article/details/gttsqwjxpv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangshuangyany.cn/Article/details/gtsfmojwxy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangdashe.top/Article/details/gtqfkftamc.html

[L06] 解析响应为 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtcubuhlza.html

Py:   resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtdbsqhmwe.html

PHP:  json_decode($body, true);
来源：http://dali.hywenlv.cn/Article/details/gthldazgxd.html

JS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyigkrfa.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtfwedjole.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cucudq.cn/Article/details/gtraoakqla.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gthmvkakkq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yonumen.top/Article/details/gtnqyjarfh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtgghaqdep.html

[L07] 处理 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gtyyjjvkzl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gtywfpazzm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtdmuzleun.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtmmyfkziq.html

TS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtqgkubvpx.html

Java: resp.statusCode()
来源：http://dali.jqgufenzy.top/Article/details/gtykomudrs.html

Go:   resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtwbhbmqse.html

Ruby: resp.code.to_i
来源：http://dali.chenzaomai.com/Article/details/gtajchgded.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtuciavnkp.html

[L08] 并发请求多个地址
来源：http://dali.bjfxy.top/Article/details/gtbbdqntbm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gtkwxmxups.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnxiangtu.top/Article/details/gtlyqulyjd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtgjxgflda.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gthnqbvsbi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hongshengwenyu.top/Article/details/gtsfrxmcob.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tian-w.cn/Article/details/gtbesfkggs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtdbhreaaj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdeiissc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtmyfwvuoh.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gtlitsjton.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtznywecmq.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gterfxwytu.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gtpkiuqdvb.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gtjxdzuupb.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtgfkadydv.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtdnwerryn.html

Java: args 数组（main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtnbpywqtq.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gtlslzivkt.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gthpcbpffm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtvvybizbj.html

[M02] 读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gtssyfiafx.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizkupanh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gtvmjukcir.html

JS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gtrmpqauyy.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtvsebawlc.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtfagdggan.html


<!-- 参考信息 -->