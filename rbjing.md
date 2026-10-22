代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangshuangyany.cn/Article/details/gthwwkdewv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyagabqb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtmbgkposh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtpdraqevb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gaohongyu789.top/Article/details/gttgqlekgn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtmeisyafj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtatvmsjnn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuanzx.com/Article/details/gtiukapsdp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yueranfly.top/Article/details/gtfcoudpip.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtkccdefrc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cashguo.top/Article/details/gtqdrokmlv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gtsowqqamu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gttyocnepa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtcwxpnjre.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.andypj.xyz/Article/details/gtiulmmnwy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.quarkkingdee.top/Article/details/gtqmaeanfs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtxkjvxaju.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gtjmqqycvw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gtseistrrn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gtodjlsgxg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zycfv.cn/Article/details/gttugwahxo.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gthmdhaxxa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangshuangyany.cn/Article/details/gtcustrxft.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cheryme.top/Article/details/gtbnxmtzbd.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gtmioqwrvi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dianchejie.cn/Article/details/gtfahslrae.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gzhubu.top/Article/details/gtjoekcqgg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnqzz.top/Article/details/gtmungowpl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gtaffrdvnv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtialjgnej.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gtmkbovenb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtwpmcgypw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.bjfxy.top/Article/details/gtydgykkly.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenlongwang.top/Article/details/gtvfrueqaz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtfvgayevc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtomubjewf.html

J. 日期与时间
来源：http://dali.xinyue.icu/Article/details/gtwfgzmtsk.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtofuzpjlm.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gtboxunbzg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.smart0.xyz/Article/details/gtbjxzhwai.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnykzmvgn.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtjqjrumaa.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrakrsuhw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gtrbgrgtgi.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gtlmyuxjpn.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gtedkqtrys.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gtisuhcgwp.html

[J02] 格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtadnxhpiv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gtnpjxvrpd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtztijprhl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jyoumei.cn/Article/details/gtwxxfcngn.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gtzeisjijy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnxiangtu.top/Article/details/gtctprnrkj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jianghu66.top/Article/details/gtkbalkqqb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtoiyckeuy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigufen.top/Article/details/gterqwmzfx.html

[J03] 字符串解析为日期
来源：http://dali.meibo888.top/Article/details/gtwwrmnxby.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shuidangran.top/Article/details/gtgbvtctrh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gtomnwmrdl.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtjbfixrtv.html

TS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfgbkssk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtbcgymgwc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtnmwddare.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtqzlbhdhs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.havefunace.top/Article/details/gtdobchpqr.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gthdsrwxma.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yangfankeji.com/Article/details/gtmibevnow.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.mhx1999.top/Article/details/gtfkzqdvhn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hammf.cn/Article/details/gtfwxgcupk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gtgsxqbpmq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhengqikj.top/Article/details/gtapennyoc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gtyraykpfo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gthmangfgu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guowangkeji.top/Article/details/gtlagbfnti.html

[J05] 时间加减（加 7 天）
来源：http://dali.cheryme.top/Article/details/gtvwopynkp.html

Py:   now + timedelta(days=7)
来源：http://dali.ydzc1.top/Article/details/gtsmdqzycc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xinyue.icu/Article/details/gtiekbmbvb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtvksqqbhl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtbhunmqzx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtzczagctk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtuobkkcga.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dianchejie.cn/Article/details/gtmzpnwiyx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtpdmfcvlh.html

[J06] 计算两时间之差
来源：http://dali.cdnleiting.top/Article/details/gtpkjuocte.html

Py:   (end - start).total_seconds()
来源：http://dali.havefunace.top/Article/details/gtearkqsqd.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gtjreyifzf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cashguo.top/Article/details/gtjpdzjyit.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwmdbaag.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gtslhinpno.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gtwtbrxeqt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gthpnbigks.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gtizoelmwa.html

[J07] 比较两个日期
来源：http://dali.yuanzhike.top/Article/details/gtukfntgcr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtaseqqxwl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yvedp.cn/Article/details/gtpazskhso.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtnatqpndd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gtoprcpfdp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jlsjyb.cn/Article/details/gtbbqncfws.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtljjdmaeu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtgtileiqt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtlxizfgqs.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gtawwbkpnx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cdnleiting.top/Article/details/gtfxbttbha.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gtkungbtsa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgovqskml.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gttqetwbxi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yueranfly.top/Article/details/gtcrkodwdi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoirkrqp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gtcsbgrlzk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangshuangyany.cn/Article/details/gtxarqhjiq.html

[J09] 时区处理
来源：http://dali.redwolf501.top/Article/details/gtaeufyysz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenlongwang.top/Article/details/gtfczqfzex.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sweek.top/Article/details/gtcgjvoomy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtmfedaizc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gtdqzsugtt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxjswdij.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gtahhitzqn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nwbrower.top/Article/details/gtptfekoiu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gtelsvacid.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqjwopdq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sweek.top/Article/details/gtuuhlaxtu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daria6918.cn/Article/details/gtsicxmrem.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gthiehcvsy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gtpwprfmof.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gttyklrzjc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gtxyyilccf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.bjfxy.top/Article/details/gtsffnbrfv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.c1oappe.top/Article/details/gtdyfmqfee.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqziohxks.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gtjayiqvzw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtbxakpmxm.html

[K01] 对象转 JSON 字符串
来源：http://dali.ydzc1.top/Article/details/gtumvnsidm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gtttoapfml.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzfqxoiy.html

JS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtykxrqntb.html

TS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtckydtgmi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.feifeiyinyue.top/Article/details/gtnvthquug.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gtdsfedtgy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gtxwsotcrd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jyoumei.cn/Article/details/gtrvmpkfci.html

[K02] JSON 字符串转对象
来源：http://dali.mhx1999.top/Article/details/gthxxcqcdt.html

Py:   json.loads(s)
来源：http://dali.yuanzhike.top/Article/details/gtymkchfgx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gtbukdcibf.html

JS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtttqsgyfz.html

TS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtgcvfejdq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gtemzpljos.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gtaboeqjqs.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtkxqdnrwh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.bjfxy.top/Article/details/gtvaodwqdh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gtryaleczn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gtfxbmrlby.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtytfjewna.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtkewvqmom.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtqofmibmn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtasnexgbj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gtkxvaekhm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gogol.net.cn/Article/details/gtroskaoqc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigfzy.top/Article/details/gtkoqlbmlp.html

[K04] 读取 JSON 文件
来源：http://dali.daria6918.cn/Article/details/gthcrclqqk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gtrlcxhiaw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gtfstyydjl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtanwgmcfe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtlvbevmxk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtkmayawtt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtbezgrxfi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gtgbmjswgk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtyesnmnnq.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gtycvgzeep.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuanzx.com/Article/details/gtflknwxoh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gteywspiri.html

JS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gtgjiunyez.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtwxzewzlk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.316326.xyz/Article/details/gtrwowsict.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gtsxlviukp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dianchejie.cn/Article/details/gtlbzrkmaj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xylfe.cn/Article/details/gtlryylpen.html

[K06] 解析 URL 查询串
来源：http://dali.zhengqikj.top/Article/details/gtlkyvllow.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtrzldydmy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sufxvd.cn/Article/details/gtjighuxxl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtffnrvcwo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtcqyitohq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gtsrixqbpb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtydfqbojx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtsaqnyuhz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtqwhqxgdu.html

[K07] 进制转换
来源：http://dali.jlsjyb.cn/Article/details/gtinhpfsek.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptzfhhga.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258.top/Article/details/gtpwfgmgyd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtrlhqihee.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgbldiqt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtvkjtrlll.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhixingplan.top/Article/details/gthqiraish.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hongshengwenyu.top/Article/details/gtnzqueysc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccblnshs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.c1oappe.top/Article/details/gtbskwdeei.html

Py:   pickle.dumps(obj)
来源：http://dali.andypj.xyz/Article/details/gtwnpfkcoj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgufenzy.top/Article/details/gtdneitbbe.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtjcmhicpb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtfkekefpi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pengpengdd.cyou/Article/details/gtxhkkuacq.html

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gtykebblqi.html

Ruby: Marshal.dump(obj)
来源：http://dali.tianlin.xyz/Article/details/gtunilhogp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmxdtkqa.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtfmcboaom.html

L. 网络请求
来源：http://dali.yongpay.top/Article/details/gttgtynfoc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoettrvlv.html

[L01] 发送 GET 请求
来源：http://dali.jinghuilouyu.cn/Article/details/gteuoicjli.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrrukhyc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gtxndnkvti.html

JS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gtsehxesde.html

TS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gtacgnstxs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guowangkeji.top/Article/details/gtmfxwwyjo.html

Go:   resp, err := http.Get(url)
来源：http://dali.ydzc1.top/Article/details/gtwdyxyabl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258888.top/Article/details/gtsvbkcurr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hysaishi.cn/Article/details/gtlyevkvpy.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtooirsksa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtbxlynngh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.meibo888.top/Article/details/gtjmkdrlzh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gtqiihtutj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gtbvemhudn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dianchejie.cn/Article/details/gtpqhlmkcr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yanxiufei.cn/Article/details/gttnxnwyco.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjzfpneb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gtumkbzsfn.html

[L03] 设置自定义请求头
来源：http://dali.316326.xyz/Article/details/gttvajzcjf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gtlncbznvs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sxryk.cn/Article/details/gtrfgzsdff.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtpxmqxoho.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gtvjoipmwn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fzhhl.top/Article/details/gtfybrhsre.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtdynrwoyk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aibaodan.cn/Article/details/gtvntfxijp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtgtansqkq.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkdwfplv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nwbrower.top/Article/details/gtnczzketn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gtzueldrcj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gttvdritod.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gtbmhowpey.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gogol.net.cn/Article/details/gtcisdayel.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yongpay.top/Article/details/gthxvmqpye.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigufen.top/Article/details/gttwhbbqiq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gtknlyywyk.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gtveerawhe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gtcsbupykf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gtzaggjulv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtakmsrpgo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gtbvrnrrlx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ppjwa.cn/Article/details/gtzegwmtho.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuanzx.com/Article/details/gtsjpgcdwh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xziqi.cn/Article/details/gtugasxnbw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ybcxt.top/Article/details/gtiabkwxul.html

[L06] 解析响应为 JSON
来源：http://dali.yonumen.top/Article/details/gtfaqkrwqt.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtjcakleij.html

PHP:  json_decode($body, true);
来源：http://dali.redwolf501.top/Article/details/gtojwijsei.html

JS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtbfxedykw.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gtxuwjlsrv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258.top/Article/details/gtddpkpjku.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dashuyun.cn/Article/details/gtnfpvxhkc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.quarkkingdee.top/Article/details/gtmvsdphqc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj202588.top/Article/details/gtfxstdwkg.html

[L07] 处理 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtimbzkxfi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.andypj.xyz/Article/details/gtmxylnzzn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jianghu66.top/Article/details/gtottzuzyb.html

JS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtkmdjsosf.html

TS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtygslzcjy.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gtfwwnpuqp.html

Go:   resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtocrzvced.html

Ruby: resp.code.to_i
来源：http://dali.yanxiufei.cn/Article/details/gtxaxnvsux.html

C#:   (int)resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtltqinymd.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gtbetcsejs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shzxlz.cn/Article/details/gtfjyadqwn.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gtafrzsksv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtymcysxle.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtcvfwsbbp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gtoylzdkpe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenjidiqi.icu/Article/details/gtsqhiyfuz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gtwgwunjtc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gthwcbaegw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtywfhqnmn.html

M. 命令行 / 进程 / 环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxctqocm.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtswlevgis.html

[M01] 读取命令行参数
来源：http://dali.zycfv.cn/Article/details/gtdxicwcrv.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gtipjiklrh.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gtafjpnpln.html

JS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gtwiskrqdf.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtylynhppm.html

Java: args 数组（main 方法参数）
来源：http://dali.cheryme.top/Article/details/gtduqmgrbm.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gtzeoryhnd.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gtjmnymbbj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtyfrzxswf.html

[M02] 读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gtquhoitsf.html

Py:   os.environ.get("HOME")
来源：http://dali.jiagoushi.top/Article/details/gthbwtmcdn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtvdjarqxl.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtimhyxfys.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gttumvqcur.html

Java: System.getenv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtwbbzmvwm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtoblgvmac.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gthdkxjlmt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtomkoqtvo.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gtjzifrmun.html


<!-- 参考信息 -->