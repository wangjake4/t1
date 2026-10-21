代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yonumen.top/Article/details/gtljbokksk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daria6918.cn/Article/details/gtkyencxaa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtnzrrpnxa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnmdmsbq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ppjwa.cn/Article/details/gtnxugstud.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtfvcldwvu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtitjegqwu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gtvloqyztv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gtiwkvmkcv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtiitswtcc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gtutqaxidp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtbusisdoj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gteiikanof.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yongpay.top/Article/details/gttkypbldp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ivvv.top/Article/details/gtklzjzrsi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guannengcc.top/Article/details/gtohylmiyv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtthrxqdhb.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gthnfsuqwb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.quarkkingdee.top/Article/details/gtjfubzxnn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtglibhlgs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gtnqkrqike.html

TS:   /error/gim
来源：http://dali.zhengqikj.top/Article/details/gtvuqmiltw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.svipenyu.cn/Article/details/gteweyvimn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnxiangtu.top/Article/details/gtpqhqdlqs.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gtpwkzfdoj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gtkgkjdvfr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gtwswvtagr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cheryme.top/Article/details/gtrcammdyq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gteizmaawe.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrswdrxzo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gthisksbyw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gteyhjpyly.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhiwuduotai.top/Article/details/gtwafqnwuj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuxming.cn/Article/details/gtnoyhbgvk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtbuwovkul.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtugpwdrrt.html

J. 日期与时间
来源：http://dali.tian-w.cn/Article/details/gtwjpexoyw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtwdcrxxcr.html

[J01] 获取当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtnhsidyij.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gttzleoxvr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtmlzlivsq.html

JS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtltpphrwr.html

TS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzpfwmjw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gtasveafdq.html

Go:   time.Now()
来源：http://dali.bjfxy.top/Article/details/gtsftiiqxy.html

Ruby: Time.now
来源：http://dali.wangdashe.top/Article/details/gtghccopfn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnxiangtu.top/Article/details/gtncmnjqas.html

[J02] 格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtzkjerfmp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gthfzrtdxg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtcjqvubnj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.haohaochexian.top/Article/details/gtuqjkwago.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gteiwukgyv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zdqjudy.top/Article/details/gtbbccwlgs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gtbpnmfpap.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gtpzoyirhw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gtcffxadzz.html

[J03] 字符串解析为日期
来源：http://dali.zhixingplan.top/Article/details/gtmwrzmmzq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gtqxqeqyzv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sufxvd.cn/Article/details/gthwqntwvp.html

JS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtdtfwyjtl.html

TS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtffiyzjwh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gthlnpkjzf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtavvmwqwy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtshklolni.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fengsongda.top/Article/details/gtuatxrgqv.html

[J04] 时间戳与日期互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtroecgxkr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fzhhl.top/Article/details/gtmgpqkase.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tanke756.top/Article/details/gtljsphchq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gtkbebhrmh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fzhhl.top/Article/details/gtsozuatny.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zdqjudy.top/Article/details/gtvfxqapzf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gteexhrnua.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xinyue.icu/Article/details/gtljberwev.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtkazgwhnu.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gtctpryrbh.html

Py:   now + timedelta(days=7)
来源：http://dali.ybcxt.top/Article/details/gtqypkgerf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmvzlvys.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtorfperhj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmrwnbce.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdtvewnk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gtkkrjgqjh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gtvkqryqcu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gtgteoqsuo.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gtzqepcatj.html

Py:   (end - start).total_seconds()
来源：http://dali.aizwys.cn/Article/details/gteidpoqzu.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgufenzy.top/Article/details/gtyghhxnyi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gtyunumutl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gtrraxvaxy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtanrbrrxq.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gtenovdrqb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.vqdsnc.cn/Article/details/gtdwwjebgm.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gtjkilrwpx.html

[J07] 比较两个日期
来源：http://dali.svipenyu.cn/Article/details/gtzjxkhrsf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtsgyyjift.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zdqjudy.top/Article/details/gtsagxmxbc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gtgshfsnfy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gtbywhnaia.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daria6918.cn/Article/details/gtcykiwudd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gtyricxxff.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtxwzoabex.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gthpmyawvo.html

[J08] 提取年月日与星期
来源：http://dali.ppjwa.cn/Article/details/gtzvvdkflf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.svipenyu.cn/Article/details/gtvesprzvd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.iojbl.cn/Article/details/gtqbdabzor.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tanke756.top/Article/details/gtsgvdbpjq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gttlasbclj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gtnaoaazlr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yangfankeji.com/Article/details/gtksclwoof.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gtgiwdlpco.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gtpzrjzsfu.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gtksrffjbj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gtqzzkqdfp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daxiang520.top/Article/details/gtdheevymv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtcwswzxjg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtymvakqvh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gtixxtoeen.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrembzxoc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nwbrower.top/Article/details/gtnmkwaaio.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gtlzljxbmr.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gtbbhfviww.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhengqikj.top/Article/details/gtqklvcavn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gtfogxpfit.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtwaobigpj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuanzhike.top/Article/details/gtyeangouy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.birdmap.top/Article/details/gtlpngnbpq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.vqdsnc.cn/Article/details/gtufficxec.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ppjwa.cn/Article/details/gtxbewurtl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gtrtrcfxoc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtaarikrut.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gtpkirwgwv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtjbwkkpih.html

[K01] 对象转 JSON 字符串
来源：http://dali.daxiang520.top/Article/details/gtscuiitlx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtqigbbokn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gtdzakhasu.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtpmzxmmno.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gttcnoljou.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zycfv.cn/Article/details/gtilxkcyri.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gtneuijoia.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cheryme.top/Article/details/gtwswdtgij.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtxjcyiyhe.html

[K02] JSON 字符串转对象
来源：http://dali.aibaodan.cn/Article/details/gtdxgwoiqj.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gtcoiwjdzj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gtbikhkrws.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtdsdaqwwz.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtkucjkhcm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj202588.top/Article/details/gtamcgcxjp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtfmnoxdbb.html

Ruby: JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtxluwydrf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccbobjzn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.bjfxy.top/Article/details/gtiugapqaf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtbywotmng.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gteznozjlg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gtzgkcghex.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gtlldkgkft.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sxryk.cn/Article/details/gtotbhbtxb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxinkj.top/Article/details/gtqlymyfsh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdroxfbgj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.meibo888.top/Article/details/gtzglcvyqn.html

[K04] 读取 JSON 文件
来源：http://dali.daria6918.cn/Article/details/gtaxzvangz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gtdaixobrp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gtiukvrigp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtujznpiqd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gttatqqcca.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtzcpigpzc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtuwwlwyvd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmmhepod.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtuujtwgof.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gtextfwxvw.html

Py:   copy.deepcopy(obj)
来源：http://dali.iojbl.cn/Article/details/gtbmaphynw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxinkj.top/Article/details/gtgirizwol.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtdgnujmrg.html

TS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtoepynlsp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yongpay.top/Article/details/gtyfpcijhp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tian-w.cn/Article/details/gtrlntyzwk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.meibo888.top/Article/details/gtgbumkbmf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangshuangyany.cn/Article/details/gtenaygjmu.html

[K06] 解析 URL 查询串
来源：http://dali.zhoulong.xyz/Article/details/gtjcyrmufu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtqaeorcwi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.316326.xyz/Article/details/gthzutdnqk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtfdmprsha.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gtmgkoqmnl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gtxvqmltnh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtachximmk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtnqndcesb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gthhdzgfwy.html

[K07] 进制转换
来源：http://dali.birdmap.top/Article/details/gtiqnksfcl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtnuyddzom.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jlsjyb.cn/Article/details/gtuinxaoal.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtvxsvpwjm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtgdyamxyx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaezilnyw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gtwutjimqi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cashguo.top/Article/details/gtckdzntij.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gttpduiwng.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gtdgimhcqa.html

Py:   pickle.dumps(obj)
来源：http://dali.cashguo.top/Article/details/gtfflnspwo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.haohaochexian.top/Article/details/gtvzhlqjor.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtqbbmhkxj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtmmdfyjbg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhengqikj.top/Article/details/gtzmqphbcl.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gtlygcvltv.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gtsqudgmkl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtxbaizfsn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtiouwyopt.html

L. 网络请求
来源：http://dali.fengsongda.top/Article/details/gtkkaifjub.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtzfaafehh.html

[L01] 发送 GET 请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzfnhqru.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjsnzeji.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hfpthk.cn/Article/details/gtlipvhxog.html

JS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gthlrdallq.html

TS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtcgmnemka.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sweek.top/Article/details/gtwszxilxu.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gtjmzcczub.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xinyue.icu/Article/details/gtplhudsnz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gtmeuaqbiu.html

[L02] 发送 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtpkxbnead.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gttzbzvmlb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cqqwz.cn/Article/details/gtmmzcmwgo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gthobzdoob.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gtyrcjliub.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dashuyun.cn/Article/details/gtvybpmqid.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hongshengwenyu.top/Article/details/gtpdkhpyrq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fengsongda.top/Article/details/gtdqxipvns.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangdashe.top/Article/details/gtiziehymi.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gtjodoaijr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gtllcgpfoa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnxiangtu.top/Article/details/gtskyyaaps.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtwoyictrm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyamgbmi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gtyeogfilc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtpthhdzto.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gtrpmysknk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtjesgeean.html

[L04] 设置超时
来源：http://dali.smart0.xyz/Article/details/gtvdiddncm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gttysoilsb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuxming.cn/Article/details/gtuabsrxpd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtzxsyfxqc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gtuhhrjlxf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.mhx1999.top/Article/details/gtbmyuutdi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yueranfly.top/Article/details/gttffqxklu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhengqikj.top/Article/details/gtggsyzdeb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gttrpoeuxf.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gtfhkipdyv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258888.top/Article/details/gtiyzvmorz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yvedp.cn/Article/details/gtaaggymar.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gtylwtofxc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtfbfowvks.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.svipenyu.cn/Article/details/gtdemwmxaw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258.top/Article/details/gtaapmlcza.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cheryme.top/Article/details/gtsqspevdl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtpmrwuiwj.html

[L06] 解析响应为 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtyezwgcwn.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gteposyxaf.html

PHP:  json_decode($body, true);
来源：http://dali.ivvv.top/Article/details/gtblnmtjru.html

JS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtfvrujioq.html

TS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtdoeosytk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258.top/Article/details/gtbcqxexww.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetyrokma.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zycfv.cn/Article/details/gtiahgeidp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sweek.top/Article/details/gtewagfwej.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtrbptteak.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gtfvejgfdu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.c1oappe.top/Article/details/gtnmnbvrdc.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtqoduaqxu.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtyutjvwbh.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagnmstlf.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtgvocqmrm.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gtbjjncedh.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtivrycctt.html

[L08] 并发请求多个地址
来源：http://dali.wangshuangyany.cn/Article/details/gtxruxtcvn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gtvyzymqba.html

PHP:  curl_multi_init() 系列
来源：http://dali.shzxlz.cn/Article/details/gtsdvmwtyn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtygbhoysh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtpighcymv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.c1oappe.top/Article/details/gtudjlzwqj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gtgwdbkznk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gtzkcaziyz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtcrlnyfaq.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtoprfhdyf.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtstukoetf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttlxrospu.html

[M01] 读取命令行参数
来源：http://dali.tian-w.cn/Article/details/gtyxkqjxrm.html

Py:   sys.argv[1:]
来源：http://dali.zhengqikj.top/Article/details/gttizmxibv.html

PHP:  $argv;  $argc;
来源：http://dali.jqgfzy.top/Article/details/gtredsrwwj.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtlxildwxv.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtjcknnkjn.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gtshwmgdcr.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gtuvnphkhk.html

Ruby: ARGV
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhufwqbl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtjyauuern.html

[M02] 读取环境变量
来源：http://dali.shzxlz.cn/Article/details/gtqeeotayu.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgfzy.top/Article/details/gthvxsdeuq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtkrhxdhyy.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtkojnyrga.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtovjgqzsp.html

Java: System.getenv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtuvmlmeor.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtahsjrsvx.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gtwbhtxztn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtxqebndrq.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gtdsxwulfp.html


<!-- 参考信息 -->