代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtzcazklxv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cucudq.cn/Article/details/gteqlztsew.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gthpslzklk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtayexxvjk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gtlksxitze.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aizwys.cn/Article/details/gttabwzbmq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtkjnxmiwo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gtkyhwgwvh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tian-w.cn/Article/details/gtspytbsnm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtkvyblgcy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.andypj.xyz/Article/details/gtabsrbrjx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gtvovaojdo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtkgdzzhxn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtvamgcgyh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gtfdjzogtg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gtasetxtjd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtflqgjirn.html

[I07] 忽略大小写与多行模式
来源：http://dali.shzxlz.cn/Article/details/gtbaibynwa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.quarkkingdee.top/Article/details/gtssjqfrin.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtfcscuujn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fengsongda.top/Article/details/gtcplgawhn.html

TS:   /error/gim
来源：http://dali.jianghu66.top/Article/details/gtewyixkyw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gtizpdwlsq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbecuurb.html

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gtotmlgipz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.9152youxi.cn/Article/details/gtwoqmdnry.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtrruzxdtn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xylfe.cn/Article/details/gthbvzurhp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gttrziflpq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtkxcwatks.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtpesyxhss.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gtaxhapoob.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuetiantiany.cn/Article/details/gtiwcibzhi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gogol.net.cn/Article/details/gtdlpjlhml.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtvrglfhxo.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcxlqqyy.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gtwmnxsieu.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtnpjdlkna.html

[J01] 获取当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gtiymhynfx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pengpengdd.cyou/Article/details/gtulsvrbte.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtjldbevyi.html

JS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtcefcsbhx.html

TS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtbaskdehd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuanzx.com/Article/details/gttqyaslbv.html

Go:   time.Now()
来源：http://dali.tian-w.cn/Article/details/gtabtxjikl.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gtjkssxeoi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gtfwikvhwg.html

[J02] 格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gtysnjeylp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtynveolva.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtwnwprttq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuanzhike.top/Article/details/gtfrcmgdww.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gtlzaacmqs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfheclmfq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gtljynzxfb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gthjcdxxky.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj202588.top/Article/details/gtdftaqxcn.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gtmzvcnasf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.mhx1999.top/Article/details/gtyuzhjebt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigfzy.top/Article/details/gtmerywchu.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtenveztvb.html

TS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtpclltyia.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtaivwqnbi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtnuiestvd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtdzpwetor.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gtzshqnswp.html

[J04] 时间戳与日期互转
来源：http://dali.xylfe.cn/Article/details/gtrdojpllw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ehwqpu.com/Article/details/gtrcunutzf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gtynbmtzvs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtfgggflje.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gtxgvdqige.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxinkj.top/Article/details/gtlhjapuwt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cucudq.cn/Article/details/gtgvzjenti.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gtnnkwjlnn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtyqugxqyc.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnavwsnd.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gtjhjzyhkr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gtotxgzfew.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtfqgwksiq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gthqzertmc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gtbivebnyq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gtambdfkrz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.andypj.xyz/Article/details/gtmrknkhcf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtzvxdlgtp.html

[J06] 计算两时间之差
来源：http://dali.zhengqikj.top/Article/details/gthyiupxpb.html

Py:   (end - start).total_seconds()
来源：http://dali.sxryk.cn/Article/details/gtxhftylbl.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gtemslecuz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhongyouzk.top/Article/details/gtyqsovvjm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.andypj.xyz/Article/details/gtlqxjrbzm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hammf.cn/Article/details/gtofapjgmp.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxinkj.top/Article/details/gtliiylpih.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtvjbbydfa.html

C#:   (end - start).TotalSeconds
来源：http://dali.zdqjudy.top/Article/details/gtsmmratkp.html

[J07] 比较两个日期
来源：http://dali.haohaochexian.top/Article/details/gtuqpmlgbj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtrbyzbbla.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gtblpljyuy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznfrfhes.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtydrxigjb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhixingplan.top/Article/details/gttlhjxnjx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhengqikj.top/Article/details/gttzhjwgjd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtxruavswi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtgfzyzwur.html

[J08] 提取年月日与星期
来源：http://dali.aibaodan.cn/Article/details/gtghcctkhe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gtcayujtml.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gtyujrnrfb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gtoslmvtzp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gtxonlyvur.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gtbpdahfcj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hywenlv.cn/Article/details/gtwswvxxrs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zdqjudy.top/Article/details/gtbqqdhooc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgufenzy.top/Article/details/gttvjnpsbe.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gtxouoirnk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gtddpschmq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gtsisdkjox.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtsxbjwqmy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtvwpgheiq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gttlhltuhh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gtgtircjyi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gtdseenbdd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gtvwhaczjs.html

[J10] 取今天 / 本月第一天
来源：http://dali.nwbrower.top/Article/details/gtzuzjwwel.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gttputoiga.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gtohkqouck.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxfebqfu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj202588.top/Article/details/gtmxwqnpoa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pycfn.com/Article/details/gtrvjhcyba.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cashguo.top/Article/details/gtnphgvxyn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdwbqpgu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gtvsvfricg.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtukdpxohf.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gtonhomdtz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtiivvqfiw.html

[K01] 对象转 JSON 字符串
来源：http://dali.ehwqpu.com/Article/details/gthnhjzsrc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtgqcbmlnm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtngphmjzq.html

JS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gtojxbscvh.html

TS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gttvbeetuj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gtmosjnopi.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gttlvehysn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.c1oappe.top/Article/details/gtgcuquxfj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.smart0.xyz/Article/details/gtcgylcirp.html

[K02] JSON 字符串转对象
来源：http://dali.jianghu66.top/Article/details/gtecdijxzw.html

Py:   json.loads(s)
来源：http://dali.mhx1999.top/Article/details/gtxieakrdx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guannengcc.top/Article/details/gtvyldzkwl.html

JS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gttiyrgsbh.html

TS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtuqzdklsf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangdashe.top/Article/details/gttuwlwvay.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtsxqadirz.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtwkwafyek.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yanxiufei.cn/Article/details/gtuvosvqcc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gtzaqppqni.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gtfdhdbejy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtazvzkmqz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtxekefalf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtikkvpuuk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guowangkeji.top/Article/details/gtcpzkneec.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ivvv.top/Article/details/gtqobalvfj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gtnrkavhdx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gtgepgrlat.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gtkurubfrn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gtzpqovxgl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuanzx.com/Article/details/gtbqppobel.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtaidiarup.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtfknhvvem.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtakakzfpk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtomwyalrk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtouadnlgg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmancili.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gtgigfqgdv.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtkxxqehsd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gtpyfprfcz.html

JS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gtwmlzvyzf.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtkzdxxdup.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgufenzy.top/Article/details/gtmkxrwpsv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.mhx1999.top/Article/details/gtngpfarex.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258888.top/Article/details/gtegwokmim.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.haohaochexian.top/Article/details/gtewfghmbz.html

[K06] 解析 URL 查询串
来源：http://dali.c1oappe.top/Article/details/gthdidlfiw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gtmeynwsaq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xylfe.cn/Article/details/gtnqwwovbr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtttfuhsui.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gthikvwaem.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ydzc1.top/Article/details/gtvxnoyqib.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtcqwful.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtixjlwxtq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtbxxhfktf.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gteqophotq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtghzbxbzf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gtwyvzfynu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtrnzsphcb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtjnnrqihf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtfdolylgt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jianghu66.top/Article/details/gtwgjcfspq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigufen.top/Article/details/gtbneqxwjq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtqvlrprmq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jlsjyb.cn/Article/details/gtanmyypxp.html

Py:   pickle.dumps(obj)
来源：http://dali.sweek.top/Article/details/gtjylbksuk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gteadredbz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtgqcbhein.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtzbkwrkql.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenzaomai.com/Article/details/gtmuxtgkpa.html

Go:   encoding/gob
来源：http://dali.chenzaomai.com/Article/details/gtazdmswxo.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyabsclk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtuoqyhokr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxcpadoq.html

L. 网络请求
来源：http://dali.xinyue.icu/Article/details/gtgyiwnfwa.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtkqdtdfgd.html

[L01] 发送 GET 请求
来源：http://dali.gaohongyu789.top/Article/details/gtipxdcweo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gtnlftffft.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daxiang520.top/Article/details/gtmcaagkrz.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtymyegjvr.html

TS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtylukoaeq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pycfn.com/Article/details/gtiewomhfz.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhoulong.xyz/Article/details/gtqgxwxxko.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gtolvvrymb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtizhqvoum.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtwhcmsgyw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gzhubu.top/Article/details/gtfitcowin.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pengpengdd.cyou/Article/details/gtagqprbpi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gtousuxyxw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gtrdeprwqr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gtkaqywmwg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zycfv.cn/Article/details/gthwovmmay.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jyoumei.cn/Article/details/gtamqbptuc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtmpmseqkn.html

[L03] 设置自定义请求头
来源：http://dali.zycfv.cn/Article/details/gtokyyyjbb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gtfbryegue.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gtrlpjnabi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtpjnpzdat.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtzcvfldmi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nwbrower.top/Article/details/gtdcffttrl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gtluxoaafv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gtkhnkhmsu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtcxwetlir.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gtgmbbfwjk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cqqwz.cn/Article/details/gtocylpmbm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteawazvio.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtvuewdmnl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtqqckzwnt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cdnleiting.top/Article/details/gtfyhznxgy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tian-w.cn/Article/details/gtaefsnail.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gtojtpabfd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtpmaffxdt.html

[L05] 上传文件（multipart）
来源：http://dali.zhixingplan.top/Article/details/gtvgrqhdfq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258888.top/Article/details/gtkpvxcrhc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangshuangyany.cn/Article/details/gtdgctdhto.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtaeuikdfu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtaptcuwaf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.mhx1999.top/Article/details/gtojbjcrde.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gtysbhjhxm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zycfv.cn/Article/details/gtcepcrbhr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gzhubu.top/Article/details/gtsysoikjp.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gtlmjxisoa.html

Py:   resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtvwseghcc.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gtbgwkpocr.html

JS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtofvducfx.html

TS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gtsuwlgckz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtrynskrbe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hysaishi.cn/Article/details/gtkjzhmzlu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgufenzy.top/Article/details/gtvuidgvwo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gtykcexsio.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtzenfpmje.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aibaodan.cn/Article/details/gtcidhdcnw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.c1oappe.top/Article/details/gtjfocduih.html

JS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtsogruamn.html

TS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtiahichdt.html

Java: resp.statusCode()
来源：http://dali.bjfxy.top/Article/details/gtelitpqpp.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtdkrazjtb.html

Ruby: resp.code.to_i
来源：http://dali.quarkkingdee.top/Article/details/gtwpascmsu.html

C#:   (int)resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtibkpwkdw.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gtoowceeop.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gttoljkupi.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gtunbknsot.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtlcniecqg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtvqszmycu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj202588.top/Article/details/gteqkyxlzm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sufxvd.cn/Article/details/gtgsoxhobs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gtdsqgvocr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258888.top/Article/details/gtuovnnkyk.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtnbtxyiow.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gtqxfhdjtv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtfgjbhsld.html

[M01] 读取命令行参数
来源：http://dali.gzhubu.top/Article/details/gtrvgexyuc.html

Py:   sys.argv[1:]
来源：http://dali.cheryme.top/Article/details/gtjlgnixup.html

PHP:  $argv;  $argc;
来源：http://dali.zhengqikj.top/Article/details/gtalvzuvjq.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtzkyngxsu.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gthhvpvjad.html

Java: args 数组（main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtzavwawrv.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gtxulayodf.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gtqrlwlqtf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtrkroriij.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gtxcvynjdg.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gtgbtzvjmt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtenwlnifq.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtgidhfnam.html

TS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtquwidido.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtkrthllnx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gttaxurkkg.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gtzxnikjxj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtiqsgpnyb.html

[M03] 执行外部命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxdoxtrv.html


<!-- 参考信息 -->