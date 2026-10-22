代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcksnrnp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtvaaptjfg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gttcjepzya.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtxrworhyu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuxming.cn/Article/details/gtfmqqllxw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cheryme.top/Article/details/gtvyjvqpzx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtjcexfhhw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafrccqzd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hywenlv.cn/Article/details/gtkqfwqkpx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gttgnyuaui.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gtfeusoydy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtyxlvdnsn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gtpugprrkn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtyyorlrwj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guannengcc.top/Article/details/gtltcxngdt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ppjwa.cn/Article/details/gtbunppumh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtfgiigpgx.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjiavpbui.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gtbsbvajma.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqasscgr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pycfn.com/Article/details/gtdheawdpc.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gtxcpkkrau.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xylfe.cn/Article/details/gtuenhibnd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yanxiufei.cn/Article/details/gtjhnnigze.html

Ruby: s.scan(/error/i)
来源：http://dali.fzhhl.top/Article/details/gtkxpkqmoe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenlongwang.top/Article/details/gtdytfotpo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ehwqpu.com/Article/details/gtzodkedjs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gotoacloud.top/Article/details/gtfgjbnkxo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtvicrygbq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtwtmouldf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtenraehmz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtibdcvacl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.0kj1m.cn/Article/details/gtqjqqmmto.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.feifeiyinyue.top/Article/details/gtakczodgj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtgjwlbmez.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtgbprogxs.html

J. 日期与时间
来源：http://dali.hongshengwenyu.top/Article/details/gtstvpjlqu.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzvvzekoq.html

[J01] 获取当前时间
来源：http://dali.zhengqikj.top/Article/details/gtcllbmcbw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gtzpkufhjt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gthyyxsmfj.html

JS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtffbfqwkb.html

TS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gtxidhaauf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cucudq.cn/Article/details/gtqvnjxkxf.html

Go:   time.Now()
来源：http://dali.xuanzx.com/Article/details/gtrfboaoqx.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gtubnxujqc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.c1oappe.top/Article/details/gtgexfdbsb.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gttydykbdn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gtzdovtmaj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gthxmahsir.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shuidangran.top/Article/details/gtriwgttyr.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gtdmhzpfmf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gtzbbrqcrp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gttjcrdveg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtsjtwlgof.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gtgppioeek.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gtqabpygso.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.haohaochexian.top/Article/details/gttudsfmos.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhengqikj.top/Article/details/gtnhvivneh.html

JS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtuixbdnrr.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtwkskrvzm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtllhiblah.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtfkegossk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gttkestgvl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.birdmap.top/Article/details/gtxweramaa.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gtkrmqzqhl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtvrcxilyy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gtphoaeprw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gtlrinfygn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gtplycpyjw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nwbrower.top/Article/details/gtdjhmlxfx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gtxqgoxjxh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenlongwang.top/Article/details/gtdtngzwex.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gotoacloud.top/Article/details/gtuqmqkgwm.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnqzz.top/Article/details/gtniiwnvej.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gtwjikbdts.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tanke756.top/Article/details/gtphtunwyy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gtceekyqwr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gtqlybsoyy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtbhgjvbph.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gtenngsgyw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shangyingyoupin.top/Article/details/gtxxmbqosd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj202588.top/Article/details/gtllbcdfyy.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gtadfpfyec.html

Py:   (end - start).total_seconds()
来源：http://dali.smart0.xyz/Article/details/gtfeawwavn.html

PHP:  $end->diff($start)->days;
来源：http://dali.xziqi.cn/Article/details/gtxvnhzzgj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gtoikfygzk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guowangkeji.top/Article/details/gtueinoeqq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.kuanghao11.cn/Article/details/gtdgkedxij.html

Go:   end.Sub(start).Hours()
来源：http://dali.hammf.cn/Article/details/gtnrmjtcbg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gtovdnkpbt.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gtwwtbwuuu.html

[J07] 比较两个日期
来源：http://dali.dashuyun.cn/Article/details/gtntewwxce.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtehbtnjyx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gtqvaxgsru.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtypetijnj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gtkrlduchy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hammf.cn/Article/details/gtdaswtzde.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gttdqvzgyk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtlnnflail.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtcrmttkct.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gtnintqncf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.smart0.xyz/Article/details/gtqnahajsl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gtofencqpo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.vqdsnc.cn/Article/details/gtkcvirnqq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ivvv.top/Article/details/gtoozkofly.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj202588.top/Article/details/gthvnwulcw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sufxvd.cn/Article/details/gtllhnynmn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gtjyifzadr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pycfn.com/Article/details/gtgimkwxok.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gtuxpgekzm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gtnzxltvkl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shangyingyoupin.top/Article/details/gtxfyavvxe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gtjnxmqyfo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gthomudazt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gthinwolaj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cucudq.cn/Article/details/gtxuknntxc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xziqi.cn/Article/details/gtnlqaaqzg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gtlmvehhay.html

[J10] 取今天 / 本月第一天
来源：http://dali.hfpthk.cn/Article/details/gtqbifoqqo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigufen.top/Article/details/gtljbgoyci.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gtmtgfozct.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtjcnrnxqx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tianlin.xyz/Article/details/gtanpduvup.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.smart0.xyz/Article/details/gtcjuhzmzc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gttxemqnhu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.316326.xyz/Article/details/gtpzscdqdp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcbuozcf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtiwggqnja.html

K. JSON 与序列化
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsxgvebb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtlttcxhvs.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gtlkdpmqhw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtywxsygtk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtiwqcveuk.html

JS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtmkbkwaqw.html

TS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtayybcsbc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.andypj.xyz/Article/details/gtvzuhjlow.html

Go:   json.Marshal(obj)
来源：http://dali.zdqjudy.top/Article/details/gtdwxjwehi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuanzhike.top/Article/details/gtcrqakvcd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tian-w.cn/Article/details/gtmfcwbhze.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtuyfrgjhf.html

Py:   json.loads(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkvhlivs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ivvv.top/Article/details/gtdubxaqws.html

JS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gthzrzqpug.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtwzqwwkit.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pycfn.com/Article/details/gttxalfphu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gtmvyidtag.html

Ruby: JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabkbaodb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gthtsnckvl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxuanxn.top/Article/details/gtdzlrprwr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtejhkubig.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtultpszxg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtvcxowvid.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gtkgwcpsoo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.0kj1m.cn/Article/details/gtjlssutow.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.birdmap.top/Article/details/gtgciolviu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shzxlz.cn/Article/details/gtyikjwqpx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhoulong.xyz/Article/details/gtfdsidcgn.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gtclygvdjj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gtplguzsdm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tianlin.xyz/Article/details/gttmvqxaik.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gtnbbshwim.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gtzzvavezn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtxiafzpak.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtxowspdtw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtajbvidtg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtebtpxelq.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gtnjuoutbi.html

Py:   copy.deepcopy(obj)
来源：http://dali.xinyue.icu/Article/details/gtfouoklfg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnqzz.top/Article/details/gtpvsbdfjq.html

JS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gtxcaxinjz.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtguypyjni.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gtlgnuaelr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigufen.top/Article/details/gtkignhlbl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gtyopjkluh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tianlin.xyz/Article/details/gtggobacaf.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gtndnmicml.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtgpyyxtqw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsbjzchy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtmtizohoh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gttrihsinn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gtgkgajcvg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtueakwkce.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtbvcbgrsj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtbrogotat.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gtokvpqziq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtqmyxrdhx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangdashe.top/Article/details/gtqnciljfs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtrvcnhqpe.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtpcxvcwrt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtcirnxsqv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxfzlefi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gotoacloud.top/Article/details/gtuedtrpku.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtdczurzwc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daria6918.cn/Article/details/gtgqrgzixi.html

Py:   pickle.dumps(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtrtoyttir.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tianlin.xyz/Article/details/gthqztmddw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gtjxlyvdqq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtwcgnmduy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cqqwz.cn/Article/details/gtcbldnuse.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gtdhxwmmsx.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gtnqczefdc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtvmhlbpii.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvlbvuqkl.html

L. 网络请求
来源：http://dali.yanxiufei.cn/Article/details/gtwsgcbgex.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyjslpdy.html

[L01] 发送 GET 请求
来源：http://dali.daxiang520.top/Article/details/gtcoiymfzv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cucudq.cn/Article/details/gtlwvhtkgr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fzhhl.top/Article/details/gtdmekihyt.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtmnjbyfba.html

TS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gtngzmseoy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.meibo888.top/Article/details/gtclxxbauj.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gtucqqmvdz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gtxqpsxohz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gtpncxnwpg.html

[L02] 发送 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtmzdsbbph.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gtqpmadkme.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cdnleiting.top/Article/details/gtonpgzmot.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtqmjomftr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gtgninyibe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gttawvicof.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gtfevwpkkx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cheryme.top/Article/details/gtgmselxvp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnxiangtu.top/Article/details/gtexmsihmj.html

[L03] 设置自定义请求头
来源：http://dali.yj202588.top/Article/details/gtkkjoulga.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gtiwedghls.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cheryme.top/Article/details/gtstbgqoru.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtpzwjepnt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gthhmplbwe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pycfn.com/Article/details/gtsqdkhwvn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtpzgqixyc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ppjwa.cn/Article/details/gtihdjvpbb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gtrexfgsmy.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gttzjmsmww.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nwbrower.top/Article/details/gtrtwenmqs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hysaishi.cn/Article/details/gtqcqutxuz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtcqvdfihx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtttugvinz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tianlin.xyz/Article/details/gtwdnjzggx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gtnciyfvvp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fzhhl.top/Article/details/gtriqistcm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shuidangran.top/Article/details/gtlqncnprj.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gtllwhfolm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gtdfeklhxz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuxming.cn/Article/details/gtntftutkw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gtndcercdu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gtpokxajby.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.iojbl.cn/Article/details/gtflgyknhb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yvedp.cn/Article/details/gtsmhunfkn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesvcnxsi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtbddmgphc.html

[L06] 解析响应为 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtqidelbgg.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gtkglfezrj.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gtnqxhoaku.html

JS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtrjqxfivd.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtyfhdjuxz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtfmnvtnor.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gtlvttywav.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gogol.net.cn/Article/details/gtggnmftwd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xylfe.cn/Article/details/gtxnkchfgd.html

[L07] 处理 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtvpywxtrn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gttueanhej.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.birdmap.top/Article/details/gtrxidkpaj.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtympyfxjk.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtxxjjhypg.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmaodslfj.html

Go:   resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtgpznpwaa.html

Ruby: resp.code.to_i
来源：http://dali.sweek.top/Article/details/gtavjrbrts.html

C#:   (int)resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gtmujyitzh.html

[L08] 并发请求多个地址
来源：http://dali.zdqjudy.top/Article/details/gtlyvdoupt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gtfrknqffd.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gtfszigacl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtdortwczt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gthalkykxo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhixingplan.top/Article/details/gtzvsivimo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gtojtjmiig.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtntrryzjr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gtsyswbsev.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbvcsklzm.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gtefjnvnjg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjklvzufa.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gtoniypzjm.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gthrejuubt.html

PHP:  $argv;  $argc;
来源：http://dali.316326.xyz/Article/details/gtxppzkqgk.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtivejugsg.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtvzbptgef.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtdpfzpwcy.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtrhziqgim.html

Ruby: ARGV
来源：http://dali.jinqigfzy.top/Article/details/gtvqfymqxz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtllftdvtb.html

[M02] 读取环境变量
来源：http://dali.yueranfly.top/Article/details/gthpgkngru.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gtmwdrdvmo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtetzqemuh.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtrcjnttdw.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtynpmcjdr.html

Java: System.getenv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtouwvjdzn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtowasjsbj.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gtpbdrfyih.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtzgxrbdwj.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gtorxsqerg.html


<!-- 参考信息 -->