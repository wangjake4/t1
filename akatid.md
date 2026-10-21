代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gtwhkvvizi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtzcjnyqzt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangshuangyany.cn/Article/details/gtpclafsqi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gttqoyjwwm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gtfhuhlsvv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtyfqhzbos.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.andypj.xyz/Article/details/gtczzunnhr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gtryhgcibw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtlayunvbk.html

[I07] 忽略大小写与多行模式
来源：http://dali.ydzc1.top/Article/details/gtahsjslnz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.c1oappe.top/Article/details/gtyuzizmgb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtrjcnhexn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuxming.cn/Article/details/gtopfixzza.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gtgocirzmj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gtojvqevha.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cqqwz.cn/Article/details/gtonelyora.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gttitmnjzs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gttvhbirkf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gtxcjeiwzz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gtqsoqdfbs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtmkaslvky.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gthpfdqfim.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtpvhdwueo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gtcjgsubsr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gtcthfkjzq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cucudq.cn/Article/details/gtsfqfhihe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtdyhvueaq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdvvbixdh.html

J. 日期与时间
来源：http://dali.daria6918.cn/Article/details/gtlzggknuz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtcyvperri.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gtmwnpsklx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gtizmmjddw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtvyxuzngy.html

JS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gtynhwboun.html

TS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtmhahgeex.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuxming.cn/Article/details/gtknasvzcz.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gtfunqqqxa.html

Ruby: Time.now
来源：http://dali.zhiwuduotai.top/Article/details/gtfrdwlqdv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gtylbfuzdc.html

[J02] 格式化输出
来源：http://dali.haohaochexian.top/Article/details/gtrhewscxg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtddlnxykj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gtnukvspjj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gtvxhphylm.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gthbivwypi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gtewidmgvl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pycfn.com/Article/details/gtqmoakhqc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtsymjmrjx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj202588.top/Article/details/gtsztixlro.html

[J03] 字符串解析为日期
来源：http://dali.jinqigufen.top/Article/details/gtejnsohee.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pengpengdd.cyou/Article/details/gtjrprlbpk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hfpthk.cn/Article/details/gtcffmwyxt.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtrunrrtts.html

TS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtquogeate.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtvvyshdij.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtmkgnsmtu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gthenilvnz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gtshsfncnh.html

[J04] 时间戳与日期互转
来源：http://dali.jianghu66.top/Article/details/gtndrjikjo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gtqxzfraxd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sufxvd.cn/Article/details/gtsncjxrxq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.0kj1m.cn/Article/details/gtqzedyria.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gtaxpzxusy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daxiang520.top/Article/details/gtejceugml.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtflbmxltf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.0kj1m.cn/Article/details/gttxvxbosq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtpduepqua.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gthjjvymxd.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gtimjyyazh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sufxvd.cn/Article/details/gttvvdrgmd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtonihveef.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gtjktjktyu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gtuozyopve.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yanxiufei.cn/Article/details/gtuoljjtdk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gtyuwmmcsi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gtrvvmjgnv.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gtsgfbcmjc.html

Py:   (end - start).total_seconds()
来源：http://dali.yangfankeji.com/Article/details/gtzbabwpiw.html

PHP:  $end->diff($start)->days;
来源：http://dali.hammf.cn/Article/details/gtaopkpqov.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gtqnmxvruh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gtsflvmjhz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gtkfbosaae.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gtrxhbjtxz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hfpthk.cn/Article/details/gtotnyryty.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevetacap.html

[J07] 比较两个日期
来源：http://dali.haohaochexian.top/Article/details/gtvuiolftu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtwwezhzxw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.bjfxy.top/Article/details/gthkombnuf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtvsocdhqb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtayiyvrzj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hammf.cn/Article/details/gtgqeeudau.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.c1oappe.top/Article/details/gtjuopyryk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtuonifcig.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtlehgyjfx.html

[J08] 提取年月日与星期
来源：http://dali.svipenyu.cn/Article/details/gtwvmqbxuj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.quarkkingdee.top/Article/details/gtmjliclsn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkwiupgb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gtpqlfsdbf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gtzanqckhp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.redwolf501.top/Article/details/gtaxksypxh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gtlrnxnqrh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hfpthk.cn/Article/details/gtomjmmnwg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gtazdtiyor.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gttqwdvcbw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gtoglsdabn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gtcfqdkrtw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtxcuqoomy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtfdkfwdlv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.redwolf501.top/Article/details/gtwssbkayz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pengpengdd.cyou/Article/details/gtsldjvdaw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxiumnyh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.andypj.xyz/Article/details/gtznxfompr.html

[J10] 取今天 / 本月第一天
来源：http://dali.jiagoushi.top/Article/details/gtmnkzcihr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.bjfxy.top/Article/details/gtqyvbjscc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtseddjqtu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shzxlz.cn/Article/details/gtwpckfpfg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gtqeoexete.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsberpncc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyovcrhn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pengpengdd.cyou/Article/details/gtutqfilov.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gtteiflfzx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwhoidztr.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gtvwourwus.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzvjybfjz.html

[K01] 对象转 JSON 字符串
来源：http://dali.ehwqpu.com/Article/details/gtzyvvsgmn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gtlvfbgguf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtvqbjcpiy.html

JS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtnshqckgl.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtrcheomhy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gtlifdqinw.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigufen.top/Article/details/gtzxsrkemc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sxryk.cn/Article/details/gtwmxfcojv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenzaomai.com/Article/details/gtyfktvfca.html

[K02] JSON 字符串转对象
来源：http://dali.yuxming.cn/Article/details/gtjrvoudot.html

Py:   json.loads(s)
来源：http://dali.tianlin.xyz/Article/details/gtgilhqrdj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gtbuyfmbwa.html

JS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtwfatinvj.html

TS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuogrtauh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtyzqslcfu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtsiitsllp.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtrdhjalcx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuanzx.com/Article/details/gtniciohpn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cashguo.top/Article/details/gtdfesoaam.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gtxaqcibub.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtculymcop.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtlxwogbdo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gtgkytziab.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gtctvcdswi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gthjnlicqo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtheqtysuf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.snrcjt.cn/Article/details/gtylplivfx.html

[K04] 读取 JSON 文件
来源：http://dali.jyoumei.cn/Article/details/gttkaretja.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gtxzkppgje.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gtzzadizee.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtsyvkenla.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtgsixtjvc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtccugwmby.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtynfetlas.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtekdtwkub.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtbspswxfe.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gtkqocvjcx.html

Py:   copy.deepcopy(obj)
来源：http://dali.gotoacloud.top/Article/details/gtnbglokdh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenzaomai.com/Article/details/gtpssznffm.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtkpmebznm.html

TS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gtlrqcrohi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gaohongyu789.top/Article/details/gtenffuukq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tian-w.cn/Article/details/gtovoydszf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yvedp.cn/Article/details/gtmnlhzhpk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangtech.top/Article/details/gttjgkxvna.html

[K06] 解析 URL 查询串
来源：http://dali.guowangkeji.top/Article/details/gtjwdcorrc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtfsqsucyu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gtcueakwux.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtjcxedtdg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gthudoewzp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gotoacloud.top/Article/details/gtfnbxrgsw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtawfcptrx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtszpjodxs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtvuxhsqti.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gtyffoxtgy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtzpowmnkt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gtvbjqgrtr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtprpebqlv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtutthtkbx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtbwhthdxx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gtdamdhugt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cqqwz.cn/Article/details/gteetpoiah.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtmyeoogmj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tian-w.cn/Article/details/gtkqbohrpe.html

Py:   pickle.dumps(obj)
来源：http://dali.daxiang520.top/Article/details/gtesnkiryw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sxryk.cn/Article/details/gttmzgpgwg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gtfmpweolc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtfqxolooj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gtlzykwttk.html

Go:   encoding/gob
来源：http://dali.smart0.xyz/Article/details/gtbyfggavy.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenlongwang.top/Article/details/gteyrfdlfo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtuvzjeazm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtskdlvmpt.html

L. 网络请求
来源：http://dali.wangshuangyany.cn/Article/details/gtndwkvpsj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdymmebyj.html

[L01] 发送 GET 请求
来源：http://dali.jqgufenzy.top/Article/details/gtqwrlfxgs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gtzezhxnww.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuanzx.com/Article/details/gtyvukokkf.html

JS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtlfszvdof.html

TS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gtznudcrmu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gtdjxmymvp.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gtphwmlazh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpridbba.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guowangkeji.top/Article/details/gthbpjjxbg.html

[L02] 发送 POST JSON
来源：http://dali.birdmap.top/Article/details/gtzxywamto.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtwfkhuyim.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gtkqwxapuw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gtgtxbfmug.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtzckulwej.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gtlwhxwhgr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gtdfjrxiln.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhengqikj.top/Article/details/gtphizpwhp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jyoumei.cn/Article/details/gtsqrutimx.html

[L03] 设置自定义请求头
来源：http://dali.haohaochexian.top/Article/details/gtgltdmrcr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yangfankeji.com/Article/details/gtwdbepnat.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gtvlzzjndr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtbregerum.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtompjmwvm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gtwfsmhvlo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjpchtiu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jyoumei.cn/Article/details/gtyadedyzc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtrgpkmdvg.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gtsxjucita.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pycfn.com/Article/details/gtlomtmhwq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yangfankeji.com/Article/details/gtsfexvvsu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtimvpfqrt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gtjvrmpqlj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cheryme.top/Article/details/gtvrksscmc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gtrahzzmst.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gtljdpsjiw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtfyweixnk.html

[L05] 上传文件（multipart）
来源：http://dali.fzhhl.top/Article/details/gtpdqrfmup.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.redwolf501.top/Article/details/gtlggfzzuc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sufxvd.cn/Article/details/gthirgqchf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtfbxbezzj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gtwspszvzl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gtvrqsgoku.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ppjwa.cn/Article/details/gtwzyswaxo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jyoumei.cn/Article/details/gtelcxtqxh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fzhhl.top/Article/details/gttvdkykdy.html

[L06] 解析响应为 JSON
来源：http://dali.xylfe.cn/Article/details/gtzhgzhhuw.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gthqkauijv.html

PHP:  json_decode($body, true);
来源：http://dali.daria6918.cn/Article/details/gtwjmcgewd.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtxouggolw.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtdjidsmoc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gttnolptrw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.birdmap.top/Article/details/gtkikjmscx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gteripsiuq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gtxpehnvse.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtxiwzcsqj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ybcxt.top/Article/details/gthfqvdvkp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gtwawbsxaf.html

JS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtilspladd.html

TS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gthqvcvxqd.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gtnlkjtfpm.html

Go:   resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gtxmvrmpjs.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gtbfnotzjh.html

C#:   (int)resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gthyauwczw.html

[L08] 并发请求多个地址
来源：http://dali.feifeiyinyue.top/Article/details/gtuaohcxkz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cheryme.top/Article/details/gtmcoxytjv.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gtvsaaccvw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtxogjomai.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtfrmhjfzc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gtijhmrdxu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daria6918.cn/Article/details/gtcuubarrc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuqfpxzp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxeryusg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtudgymkcd.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gtntqkukfz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtdmsgbgzy.html

[M01] 读取命令行参数
来源：http://dali.daxiang520.top/Article/details/gtqesbcdek.html

Py:   sys.argv[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtqxxexquh.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gtpedewchv.html

JS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gttuxtnxzy.html

TS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtfsfhcnob.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtubvuqmeg.html

Go:   os.Args[1:]
来源：http://dali.tian-w.cn/Article/details/gtudoxnawg.html

Ruby: ARGV
来源：http://dali.nanxuanxn.top/Article/details/gtyiitdnoe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtfolwhanq.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtnckymcrg.html

Py:   os.environ.get("HOME")
来源：http://dali.andypj.xyz/Article/details/gtmjxbllpz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.meibo888.top/Article/details/gtbpeoxgon.html

JS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gtohfeobrt.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gtnrxlopea.html

Java: System.getenv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtgthhfvwb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtgrbydlzf.html

Ruby: ENV["HOME"]
来源：http://dali.ivvv.top/Article/details/gtnhlqlrur.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gtlktetjxl.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gttzrdpyav.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gtzlnsuedv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gthsknigqi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gtmoametne.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtrvotbftz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gtbcsqclcs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsikkilb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gotoacloud.top/Article/details/gtinmconmf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigufen.top/Article/details/gtzwbnxkrt.html


<!-- 参考信息 -->