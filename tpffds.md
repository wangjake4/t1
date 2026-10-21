代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sxryk.cn/Article/details/gtvzlibwtl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtyyborfxg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtmuleorep.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtjnurymdr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtdpkyhkxc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.smart0.xyz/Article/details/gttqvotipd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.316326.xyz/Article/details/gtfswxkvtx.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gtuooeewep.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gtjfjyhvuq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.andypj.xyz/Article/details/gttwrhmwpe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gttkhmttmb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmoivhsk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgfzy.top/Article/details/gtqnklgyje.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtrualnnkd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtczyiapga.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gtdvttauzi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hongshengwenyu.top/Article/details/gtycrscdzt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlkfwwqi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258.top/Article/details/gtfzvkqmyd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjehsgexc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtabzewoyf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtccohkjso.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gtshdxbfgr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hammf.cn/Article/details/gtomxnnlje.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtnlrqcsfw.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuxming.cn/Article/details/gtpdgcgicq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tian-w.cn/Article/details/gthwrlqiej.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtfsbiwcrh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gtqohxifxn.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gtfmjppvly.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tanke756.top/Article/details/gtiaaknets.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gaohongyu789.top/Article/details/gtyogmmecn.html

Ruby: s.scan(/error/i)
来源：http://dali.vqdsnc.cn/Article/details/gtsngriyvb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuetiantiany.cn/Article/details/gtleqbepub.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gttjjtqdie.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gteailosvc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yongpay.top/Article/details/gtjsrmevok.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gtpfgxcxwx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gtdrqjnuyw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gtgbxzklqh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dashuyun.cn/Article/details/gthdsfhfvi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gtdscnarmf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtinhyoczc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxctbsvvj.html

J. 日期与时间
来源：http://dali.jqgufenzy.top/Article/details/gtofskimfa.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtsllpxzcf.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gtbzybicee.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gtrotagyxz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtytzvjshi.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifguhkzk.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gtlztgonuf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yangfankeji.com/Article/details/gtfuhveomu.html

Go:   time.Now()
来源：http://dali.zhiwuduotai.top/Article/details/gtbicsviwj.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gtyuswbkte.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gaohongyu789.top/Article/details/gtjsdjrxhk.html

[J02] 格式化输出
来源：http://dali.jianghu66.top/Article/details/gttldxiisr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gtbwxoioch.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gtthdtmrpf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gtlutzvsib.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gtgoyipodw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gtktgzwdwg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pycfn.com/Article/details/gtaqwtprcn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtnuwpcfbh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigfzy.top/Article/details/gtigsigfbh.html

[J03] 字符串解析为日期
来源：http://dali.cdnleiting.top/Article/details/gtkqjxqaws.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gtlhteojcm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tianlin.xyz/Article/details/gtgetausik.html

JS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtcxonqrxi.html

TS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtdrrhfctl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtyhipiknh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gturpbdxhh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtztcnjywx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.snrcjt.cn/Article/details/gtqnfaukda.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gtazxsbtgl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gtvpgrpodo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gtbterlwdc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guowangkeji.top/Article/details/gtgwtsrmbe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gttynnwjmw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ppjwa.cn/Article/details/gthofstone.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtdutwzemg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruehnttn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xinyue.icu/Article/details/gtrhqilqvy.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnxiangtu.top/Article/details/gttgofahql.html

Py:   now + timedelta(days=7)
来源：http://dali.vqdsnc.cn/Article/details/gtpolaeali.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gtdqzmrhfl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gtwsapvhyw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gtpxyjtilz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtozqabbdw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gogol.net.cn/Article/details/gtsevvgdkz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gtqfxowllg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gtymcphlga.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gtkrbihfut.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gtsvxodvpu.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gtnwmgaspr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangshuangyany.cn/Article/details/gtwhhhadno.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gtlvpqtajt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gtbfostjvk.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gtvjyzqfxs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gtzqsdybtx.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gtoamdatcw.html

[J07] 比较两个日期
来源：http://dali.dashuyun.cn/Article/details/gtsgcttnnn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtesgkkmfz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjooqgvwj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtwspamken.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gthtcwcepn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ehwqpu.com/Article/details/gtyhqivlrz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gtbfrnlrnu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtltmbvgqb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtmnsicoqo.html

[J08] 提取年月日与星期
来源：http://dali.hnqzz.top/Article/details/gthwwsgppv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daxiang520.top/Article/details/gtqnpcbbbw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gtprjzsmmr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gtacxsyhnm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gtnumixibn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xinyue.icu/Article/details/gtzlequkpo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cucudq.cn/Article/details/gtphhmiamz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gtcynlcloo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxrucghm.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gtfjjjoagl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.iojbl.cn/Article/details/gtiveetied.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhongyouzk.top/Article/details/gthjyhhqja.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gtikiqwtth.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtaurrxihf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zdqjudy.top/Article/details/gthoebuqzc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gtmykuexen.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gtzscqbpab.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigfzy.top/Article/details/gtpxspqnyb.html

[J10] 取今天 / 本月第一天
来源：http://dali.0kj1m.cn/Article/details/gtahudwbiu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gthxduthzh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gtaiwmmxbq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtmbkvyonp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cqqwz.cn/Article/details/gtwxebepnr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yanxiufei.cn/Article/details/gtudfkzffz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gtjfnsbxun.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sxryk.cn/Article/details/gtbayytfqt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtzuhenhnk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtklbsmuxw.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gtnqvijvgd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtgbquzdlw.html

[K01] 对象转 JSON 字符串
来源：http://dali.ehwqpu.com/Article/details/gtnvwiphyj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gtfcforoze.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gtqtqonian.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtncxtqfke.html

TS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtehphlgwn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zycfv.cn/Article/details/gtoovzmnno.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gtvtjpzgnu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gtfkafnbjb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgfzy.top/Article/details/gtsdlfkmvg.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gtfzxrzplv.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gtvbgrcbjz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yueranfly.top/Article/details/gtitfwaune.html

JS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtxbnunowq.html

TS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtwvvtlclp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtpshciqwk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtmeskqeja.html

Ruby: JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtntawhmme.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gtlgbyhghd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gtsctebccv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtytvuxvbu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtdbyqeggl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gtefwimjzv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtydfebkbw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daxiang520.top/Article/details/gtgreexvmr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gtdamxbozb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gtqgzfuhas.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypdudlyj.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gtymhswpdi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.iojbl.cn/Article/details/gttfivvsdb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gtkpjttsub.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzxwsize.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgdfeggl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtoykkhxth.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtvrhbquhw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gtipwlyotb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gtuyuceyst.html

[K05] 深拷贝对象
来源：http://dali.wangdashe.top/Article/details/gtdvgtrnuh.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gtktospedw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hfpthk.cn/Article/details/gtqixvnncr.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtjwpvcmew.html

TS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtryaphwbj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.redwolf501.top/Article/details/gtuustvdud.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sysykeji.top/Article/details/gtszckgiul.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gtehzkxout.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gtzhbziowt.html

[K06] 解析 URL 查询串
来源：http://dali.pengpengdd.cyou/Article/details/gtmrijztzn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtmbicycfg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gtkiqtzzuy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gterursgxd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtrtqkndmh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dashuyun.cn/Article/details/gtzpmflxyv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtjwadmrig.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtdsxbeqjb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtnqniogma.html

[K07] 进制转换
来源：http://dali.yangfankeji.com/Article/details/gttzkpacio.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphdxlszz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aibaodan.cn/Article/details/gttuwcpliv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtpamzkdvg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gttmixbzul.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtxaouponj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenlongwang.top/Article/details/gtxresnwgw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.andypj.xyz/Article/details/gthednjtzc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtxghdzpwv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.quarkkingdee.top/Article/details/gtzblorjee.html

Py:   pickle.dumps(obj)
来源：http://dali.xylfe.cn/Article/details/gtkilancuk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258888.top/Article/details/gtaenetlks.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtngqlgkfy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gtohhwunea.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sufxvd.cn/Article/details/gtyxqrbdbp.html

Go:   encoding/gob
来源：http://dali.jianghu66.top/Article/details/gtnpatnvcb.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gtijmqysik.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pycfn.com/Article/details/gtbqpmfqbz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtpocxiais.html

L. 网络请求
来源：http://dali.aizwys.cn/Article/details/gtyyfvmbax.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqujguij.html

[L01] 发送 GET 请求
来源：http://dali.sxryk.cn/Article/details/gtjvfzaigb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gtvpocggxt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenjidiqi.icu/Article/details/gtgrgjtulq.html

JS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtjqgyyxfe.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtedkjkrqr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yonumen.top/Article/details/gtyzgdjhau.html

Go:   resp, err := http.Get(url)
来源：http://dali.jianghu66.top/Article/details/gtickjexbg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.316326.xyz/Article/details/gtashvdthf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenlongwang.top/Article/details/gtfcmiqlvy.html

[L02] 发送 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtkobeylmj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtuwlhrtkd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tanke756.top/Article/details/gtwvwfapde.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gteibgmjlh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gtfjyxwpcd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ybcxt.top/Article/details/gtpmcucrcq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gtjhcumbqj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhixingplan.top/Article/details/gtzchhwmxn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.meibo888.top/Article/details/gtynxxbjnt.html

[L03] 设置自定义请求头
来源：http://dali.guannengcc.top/Article/details/gtnxhozyua.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gtuofstioz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shuidangran.top/Article/details/gtzxgctjst.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtpbirirdd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gtpkvamgff.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gtnatsucsb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gttenrxkbz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzpwfmag.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gtkhyeecpf.html

[L04] 设置超时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtweidjxrl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxuanxn.top/Article/details/gtfqtwziaq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gtyjpadkwr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gtknxkigdm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gtkvibziej.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtxqcionvn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhengqikj.top/Article/details/gtgpjuafab.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ydzc1.top/Article/details/gtavlxyuso.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shangyingyoupin.top/Article/details/gtucyvmzfs.html

[L05] 上传文件（multipart）
来源：http://dali.ppjwa.cn/Article/details/gtxpghvriq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.316326.xyz/Article/details/gtxwjcrnfe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jianghu66.top/Article/details/gtgdrfimos.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtrwlpikqb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gthqtinowr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sysykeji.top/Article/details/gtwravtcvq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtstgmaqps.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zdqjudy.top/Article/details/gtoybkwtxm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gtryrgynkc.html

[L06] 解析响应为 JSON
来源：http://dali.yvedp.cn/Article/details/gtjbdbyzhf.html

Py:   resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtbprxdcqd.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gtcilksdol.html

JS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtmesxmqte.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtlnecxvto.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtrbemsdby.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.snrcjt.cn/Article/details/gtlbfkuqza.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gtpueomqwc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj202588.top/Article/details/gtbbpyeutd.html

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtpwxtwrub.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xinyue.icu/Article/details/gtetlqjxta.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gtzemgexig.html

JS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gthdobdwnl.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtgtiboxtp.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gtzmjgvukw.html

Go:   resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtuakizgra.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gtfgvkqpzk.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtzddfwbvp.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gtzjojogbv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gtokzklvsr.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gtixslmftw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtunqowjfj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtavkqlhus.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gtncehchzd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gaohongyu789.top/Article/details/gtfljxackl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtapnzvutu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtfdqxwepx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfizeyteq.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuanzhike.top/Article/details/gtjoldwusy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtcufuidpi.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gtqpcxoner.html

Py:   sys.argv[1:]
来源：http://dali.ehwqpu.com/Article/details/gthknppbxs.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gtfzaatwlz.html

JS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gthpukjpiy.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtklmcmedj.html

Java: args 数组（main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gtdqhhztdi.html

Go:   os.Args[1:]
来源：http://dali.zhengqikj.top/Article/details/gtxhjesxep.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxuwhrcxw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gthhsmuohz.html

[M02] 读取环境变量
来源：http://dali.iojbl.cn/Article/details/gtvufrhnim.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gtylpvdkvy.html


<!-- 参考信息 -->