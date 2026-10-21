代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gtfkdhwoke.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsafxzhyc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtnjzpkarf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gtivgmetpi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtpopzotsq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtbqftzedd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gtiaeustig.html

[I05] 按正则拆分
来源：http://dali.xinyue.icu/Article/details/gtmjvnrjbg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtusyjzmap.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.bjfxy.top/Article/details/gtyrzeocgf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtvcrhpxws.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtctkwmuzl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hammf.cn/Article/details/gtmxgyftlu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtdmhloflh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtjwzrokjm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gtgkcrtsjf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrneyxzww.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtfoujsmqj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sweek.top/Article/details/gtykulgkyh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtvbghvxgq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtztakqccs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtmbpdpgmb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dashuyun.cn/Article/details/gtufvpzccz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yueranfly.top/Article/details/gtngwdkazi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtisgewuqs.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gtmnmrlker.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gtpjqcaijr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtfkkruwxs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fengsongda.top/Article/details/gtdiasbelm.html

TS:   /error/gim
来源：http://dali.yonumen.top/Article/details/gtlaecvnik.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gtzuqazgdv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cdnleiting.top/Article/details/gtdqmtfflb.html

Ruby: s.scan(/error/i)
来源：http://dali.havefunace.top/Article/details/gtnjphhtyr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gtgogaezfo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gtknipgxtv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigfzy.top/Article/details/gtdcububjp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gteldxhssy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtcmbiktqm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnovdvuqc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtazuokouu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shzxlz.cn/Article/details/gtewybuilh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gtbxekhlhe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gtuvkthqdb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtjiqduwji.html

J. 日期与时间
来源：http://dali.cqqwz.cn/Article/details/gtdnpomfvw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtbwasfkkw.html

[J01] 获取当前时间
来源：http://dali.tanke756.top/Article/details/gtjudcvxia.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtseaqlmcy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtqkibspkb.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtmqjbrtmw.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtdvnkfiqd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xylfe.cn/Article/details/gtczscfnci.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gtiaowcnaj.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gtvfaoeodp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gtkbabnevz.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtyriqzopp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gttvscsyzm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtgdmxqzrz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gtmykmvrdt.html

TS:   d.toISOString()
来源：http://dali.yvedp.cn/Article/details/gtskkvauox.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gtopvonelb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xylfe.cn/Article/details/gtshscygnw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gtiftbbouy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gtnvpegsjo.html

[J03] 字符串解析为日期
来源：http://dali.gaohongyu789.top/Article/details/gtffojqgsa.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gtrexcmzpx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pengpengdd.cyou/Article/details/gtaaeoawon.html

JS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtfzmtdmos.html

TS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtyocpgwzz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcaczbrkd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtijqslevg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtcjxucuor.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gtmbvivqbf.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gtwkmldiek.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.snrcjt.cn/Article/details/gtgxhxecky.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.316326.xyz/Article/details/gtafqzukoh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gttmollyyu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sxryk.cn/Article/details/gtrxggnmeb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cheryme.top/Article/details/gtuntqtrqk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gtffwqykdo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.svipenyu.cn/Article/details/gtrodbvjzw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yangfankeji.com/Article/details/gtkncuzxjo.html

[J05] 时间加减（加 7 天）
来源：http://dali.yangfankeji.com/Article/details/gtxvmgdorp.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gtyoeljxxl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.vqdsnc.cn/Article/details/gtvhcectuo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtqvuapcht.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtppqzuilk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gtkaugflih.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gtdiugrlur.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gtfejqupxu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtdizevzak.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gtpvasssvu.html

Py:   (end - start).total_seconds()
来源：http://dali.svipenyu.cn/Article/details/gtrruuaqly.html

PHP:  $end->diff($start)->days;
来源：http://dali.daxiang520.top/Article/details/gtezjucdeo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dashuyun.cn/Article/details/gtgfaxmiva.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhiwuduotai.top/Article/details/gtycozfkyw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtsscfbjus.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gtieyfnbtr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gtojjixjyp.html

C#:   (end - start).TotalSeconds
来源：http://dali.tianlin.xyz/Article/details/gthduotlva.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gtxlxaxbcm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gttnmscgzd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gtwzjntbfq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gtccufxkww.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gtoqlpltib.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tanke756.top/Article/details/gtbrhkftmo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtlelcsqqs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtcihgltgq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtzktwtwhn.html

[J08] 提取年月日与星期
来源：http://dali.hammf.cn/Article/details/gtlnaioeno.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj202588.top/Article/details/gtsddznxtl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gtuscaqbef.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gtkogplixs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcagtqgga.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.c1oappe.top/Article/details/gtidnohybt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajgjzchl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yongpay.top/Article/details/gtqrewjrxy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ehwqpu.com/Article/details/gtrdswfbjf.html

[J09] 时区处理
来源：http://dali.sysykeji.top/Article/details/gtsnhgkfbd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.0kj1m.cn/Article/details/gtechurgfs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gtlgtcjivy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gtykpcnbzw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtnzpfqzhl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gtubqkwbnf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhixingplan.top/Article/details/gtghdciusd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gtxvovmzrv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuanzhike.top/Article/details/gtpjqoowvw.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gtgfsqyrws.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258.top/Article/details/gtsywclcds.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.havefunace.top/Article/details/gtpfbuorbb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtnusikgmr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtslzxuzwc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.andypj.xyz/Article/details/gtlgbzepvf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.9152youxi.cn/Article/details/gtjtxjvmyk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gtesqrhulh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtezyibj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqpuhsmot.html

K. JSON 与序列化
来源：http://dali.hysaishi.cn/Article/details/gtwhqkqojl.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtbxvvnaad.html

[K01] 对象转 JSON 字符串
来源：http://dali.jianghu66.top/Article/details/gtdkzpueip.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtvuvmwxrr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtauoeysvr.html

JS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtwealiumt.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtjxbzpmgs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fzhhl.top/Article/details/gtcyluumjl.html

Go:   json.Marshal(obj)
来源：http://dali.wangdashe.top/Article/details/gtmaalevwd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aibaodan.cn/Article/details/gtaayctzbt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yueranfly.top/Article/details/gtotsnacah.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtvcpaewjl.html

Py:   json.loads(s)
来源：http://dali.guowangkeji.top/Article/details/gtbllwjapi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gtmyqqvane.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtztqknrtp.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtdyttghyl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daria6918.cn/Article/details/gtsdxdeujs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtugnnwyhq.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtcejfpneo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangdashe.top/Article/details/gtovoxvavm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dashuyun.cn/Article/details/gtultpcmlu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gtmhpqnqfw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gtkosptgkk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtmlumlqum.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtdcpnbtav.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gthyaxrjlu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yanxiufei.cn/Article/details/gtlpibogqy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigufen.top/Article/details/gtkkierclh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yueranfly.top/Article/details/gtemdpdrys.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gtbubbqtmc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shangyingyoupin.top/Article/details/gttixzgblx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gtyhuunxlj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtjoxuyrne.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gtzhvnmhua.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtndwotcam.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtnhfxqevt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtzyysfpnm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtuysqxntp.html

[K05] 深拷贝对象
来源：http://dali.sxryk.cn/Article/details/gtvvfitgkn.html

Py:   copy.deepcopy(obj)
来源：http://dali.aibaodan.cn/Article/details/gtrqfglykh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangtech.top/Article/details/gtxypdqkev.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwrlilky.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtpmvvnavr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gtpjvsepnl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zycfv.cn/Article/details/gtzefchyoa.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gzhubu.top/Article/details/gtqfaelqon.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hongshengwenyu.top/Article/details/gtvgijnsdo.html

[K06] 解析 URL 查询串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpysegtla.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cashguo.top/Article/details/gtrcchlebd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuetiantiany.cn/Article/details/gtskhaveqn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gtjljibhej.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gtqorsurxe.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtqmopiroa.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtdvkicmvl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtrdwhsnlg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtnrmkvejg.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtmabivzzo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtlolmcizs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gtcglykayy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtyguosmsl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtjapxonfd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gthmialejf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gtzatftjbq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gtkbrodngx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtnmwvfaep.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuanzhike.top/Article/details/gtgwoxoegb.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gtzdricrcx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gtgpozazoo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtbimazrpk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gtvqlarjdl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xziqi.cn/Article/details/gtpzjryzdi.html

Go:   encoding/gob
来源：http://dali.yj20258.top/Article/details/gtvggdrvdm.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gttukahgpe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gttvhkiaoi.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtztnzmmnm.html

L. 网络请求
来源：http://dali.shuidangran.top/Article/details/gtnelrtkse.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtffeucmks.html

[L01] 发送 GET 请求
来源：http://dali.ydzc1.top/Article/details/gtvdzdwclb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.feifeiyinyue.top/Article/details/gtuskwjrlb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.bjfxy.top/Article/details/gtuswktijd.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtwqmfdvwl.html

TS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gtaexdgchz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gthbhmbgqd.html

Go:   resp, err := http.Get(url)
来源：http://dali.meibo888.top/Article/details/gtwvvhwgxv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangshuangyany.cn/Article/details/gtmamrtixz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.kuanghao11.cn/Article/details/gtekcgcawq.html

[L02] 发送 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtpfczepza.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtbfthbbma.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigufen.top/Article/details/gtzbfgnfdr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtsuexouns.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtfzoshsos.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.iojbl.cn/Article/details/gtnoxijjza.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258888.top/Article/details/gtopmzeows.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.andypj.xyz/Article/details/gtigookbkz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gtidpnvrhc.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcqehspe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwoqrtatb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gthqovyefv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtmcastnaj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gtfwbkimes.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jlsjyb.cn/Article/details/gtiobacwbi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gtqpvdhseo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gtjipzhfur.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gtvxzyodfq.html

[L04] 设置超时
来源：http://dali.shzxlz.cn/Article/details/gtjexdnqbb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jiagoushi.top/Article/details/gtptlofmtq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmypselzk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtatvjsasx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gtahlbfpwz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gogol.net.cn/Article/details/gtjqqmcray.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hongshengwenyu.top/Article/details/gthpxogjfu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gtbwxsfifd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shuidangran.top/Article/details/gtlhycimts.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gtqqyrizxe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sweek.top/Article/details/gtcugnelsr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxuanxn.top/Article/details/gtypqxemjq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtqnapvoqe.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gthmehbqxx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjokfpxb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gtmhsaymmc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenzaomai.com/Article/details/gtuxfvhgsn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gtissdmbxj.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gtkuvcdbiz.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gtjjvqvcmc.html

PHP:  json_decode($body, true);
来源：http://dali.chenzaomai.com/Article/details/gtzhlubgwf.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtyhpexyvg.html

TS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtprasdojc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtpytpxeyj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hysaishi.cn/Article/details/gtabqtchqk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbhcqixy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fzhhl.top/Article/details/gthlrwdkcd.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtgdgdvptk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.andypj.xyz/Article/details/gtcukfnnrx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtcxcxvwpf.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gtyewwzpsx.html

TS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtznulbjit.html

Java: resp.statusCode()
来源：http://dali.aizwys.cn/Article/details/gtmrmdbowj.html

Go:   resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtvlrimvjf.html

Ruby: resp.code.to_i
来源：http://dali.meibo888.top/Article/details/gtwrttczkg.html

C#:   (int)resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gtuwaxxifk.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gtnqqnqqau.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gtlrjycbzv.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhengqikj.top/Article/details/gtpecxkbur.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtuufzshhb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtfvjagmwy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.316326.xyz/Article/details/gtkiqjvown.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtauoccwjn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gttobteuth.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tanke756.top/Article/details/gtvomywssx.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtyrmvbfcy.html

M. 命令行 / 进程 / 环境
来源：http://dali.jianghu66.top/Article/details/gtgisqqkse.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtvikhvdwe.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtyfwdsgjw.html

Py:   sys.argv[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunrngmty.html

PHP:  $argv;  $argc;
来源：http://dali.ivvv.top/Article/details/gtelkozthx.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtxozfhcks.html

TS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtsstiqbkb.html

Java: args 数组（main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtaugnbxon.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtsejyklem.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gtjzpfualo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gtupcjzgdh.html

[M02] 读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gtemvexrjq.html

Py:   os.environ.get("HOME")
来源：http://dali.guannengcc.top/Article/details/gtrlhocexs.html


<!-- 参考信息 -->