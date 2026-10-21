代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenzaomai.com/Article/details/gtxnhuawif.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.birdmap.top/Article/details/gtszswvqim.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtyvtzrzqj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtndbswctm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlogpnrsp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtubybqnsp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtdyocjujn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xylfe.cn/Article/details/gtajyodyun.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nwbrower.top/Article/details/gtapkqxjuv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtkjlponvm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gtewmbqvtw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gtbsyjjkmf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtbzpjdybe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtdpwmjhze.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ybcxt.top/Article/details/gtqqmvpevf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gtiermkwnu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtmnxrkuix.html

[I07] 忽略大小写与多行模式
来源：http://dali.yongpay.top/Article/details/gtpyolusvm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sweek.top/Article/details/gtwxdrkjgp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gtvzndketd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pycfn.com/Article/details/gtrnmpoxsv.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gtgyroracr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gtzulvgodc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuetiantiany.cn/Article/details/gtjgliuhsz.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gtyuupfjcv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gtexlnlnfu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ydzc1.top/Article/details/gtvsmigfef.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.meibo888.top/Article/details/gthxldtlkp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtwalmjnyu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtpmvqsshv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gtmioknhyd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gtfacruaex.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cdnleiting.top/Article/details/gtrllsgpns.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gtzvqdkgsp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gthzvhddji.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtyeukegbp.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gtvkzfwxje.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtmaeewkox.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gtgnuyegcz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fzhhl.top/Article/details/gtpjqdqvqq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gtvhrythje.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gteszpaeop.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtairnaclo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtslggddjh.html

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsrtxitf.html

Ruby: Time.now
来源：http://dali.jqgfzy.top/Article/details/gtmtmwcimw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fengsongda.top/Article/details/gtxqmqayeu.html

[J02] 格式化输出
来源：http://dali.yongpay.top/Article/details/gtlbxtwoyv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtxwoubhzz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gtdrjkpwey.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yangfankeji.com/Article/details/gtwgxblhrd.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gtugttzuwh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gtxsmhocry.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxmwlcej.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gtthpvfggj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnqzz.top/Article/details/gtuupfkjum.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gtvzetqewn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gtjtypknvx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhengqikj.top/Article/details/gtesdfpudz.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtpgpqtczf.html

TS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtqdeomngf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtidfvmwzj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtsvfgxcpe.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthflcuclh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gtgptqgrpx.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gtbgfkrqzz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyssikvll.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gtuwnhmqeh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtaxmmuqle.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yueranfly.top/Article/details/gtxlrphadq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xinyue.icu/Article/details/gtvxhwyhhn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtyenkvftl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtolavmfqj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dianchejie.cn/Article/details/gtedjiahhn.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gtbpbtfrgy.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gtchfmrhrc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gtpsjvvaij.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gtezohibcj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtmuqfmlnh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gthmvklyur.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gtgqiwfufn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabztxfwq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jiagoushi.top/Article/details/gtpjdnkxeq.html

[J06] 计算两时间之差
来源：http://dali.jianghu66.top/Article/details/gtaujtvwdl.html

Py:   (end - start).total_seconds()
来源：http://dali.cheryme.top/Article/details/gtjcrvoohs.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gthidyzzfz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gtxcjnnkwc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gtitohsklx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj202588.top/Article/details/gtkqemhxfk.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gtbvncukpa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yueranfly.top/Article/details/gthbwpblhh.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gtukfdlett.html

[J07] 比较两个日期
来源：http://dali.fengsongda.top/Article/details/gtizwmvoim.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtbgogefuq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hysaishi.cn/Article/details/gtpusdbowt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtprelecvf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtowcdmlit.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gthokyvucr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtubbypvtz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtnxmhestc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtsakacfsa.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangtech.top/Article/details/gthaexxozk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfolbcmtu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gtziuehwzw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jiagoushi.top/Article/details/gtroafratg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.redwolf501.top/Article/details/gtjaddcqfr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.snrcjt.cn/Article/details/gtgmbhthwi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhengqikj.top/Article/details/gtitdyuexp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphlccmkw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gtflvvqwjx.html

[J09] 时区处理
来源：http://dali.meibo888.top/Article/details/gtrmqsddcn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tianlin.xyz/Article/details/gtaufbbthq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zycfv.cn/Article/details/gtgejuorwm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gtatbcnneb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtkyxrxncg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gtfbmufpmh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ybcxt.top/Article/details/gthlxusjeu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtponekabq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cucudq.cn/Article/details/gtjmnpayku.html

[J10] 取今天 / 本月第一天
来源：http://dali.ppjwa.cn/Article/details/gtiykxblsr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gtuauznriv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gtidtkacdr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtjfpcstvv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.svipenyu.cn/Article/details/gtqyfoqkpw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gtwetqtwhu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gtdkiisxgj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gtskpepwdt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gtpyhkwjtl.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtahpqjfey.html

K. JSON 与序列化
来源：http://dali.daria6918.cn/Article/details/gtyniqqxdc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtdfraeukc.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gtgbfbfqxd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gtxxhqahqm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtrywihahq.html

JS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqidaspra.html

TS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtyblkcyqa.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuanzhike.top/Article/details/gtmgqjfcdo.html

Go:   json.Marshal(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtlfqlpmqw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gtvvcdfoim.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtafxorelp.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljmqrowq.html

Py:   json.loads(s)
来源：http://dali.sxryk.cn/Article/details/gtwzitrpet.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.meibo888.top/Article/details/gtkflpfwoh.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtraqevsst.html

TS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtjvovelim.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtiultwmmt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gtnmjpsmjq.html

Ruby: JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtcmgpgadc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zdqjudy.top/Article/details/gtjcrlcgst.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gtvkahbxkh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtytwwstde.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtjvfatcqu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gtqaplxzwc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtjecuklws.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sxryk.cn/Article/details/gtcqgnwpyu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gtrbcuydfi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigufen.top/Article/details/gtywaxedoq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gzhubu.top/Article/details/gtzzgyyvfd.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gtvwlddvvr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xylfe.cn/Article/details/gtxaxzijsg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gtegincxcc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtshtzdlmk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gtexpdtdut.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtwjrvumhn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdoqywupe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtldbfgubc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtkxlmmdgm.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gtyvqztcwa.html

Py:   copy.deepcopy(obj)
来源：http://dali.havefunace.top/Article/details/gtnewascpa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daria6918.cn/Article/details/gtnesqfyqo.html

JS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gthjlmoscq.html

TS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtccskodrc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gtentfcolo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gtktdiynjx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjzbgnig.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjjwlyha.html

[K06] 解析 URL 查询串
来源：http://dali.gzhubu.top/Article/details/gtangmgmqn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gtuwuhauip.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgufenzy.top/Article/details/gtswugvcfp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtalyqrdqb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtwufmjbrr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xinyue.icu/Article/details/gtqdorimes.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gttyxlmmeq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtupqqtyyo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtigkdgsuw.html

[K07] 进制转换
来源：http://dali.yongpay.top/Article/details/gtektrjool.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtsopruvpq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jlsjyb.cn/Article/details/gtvbrzfube.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtpebmqbov.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtkvhalukt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtpfvddnuw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gtqkhdeuwp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yueranfly.top/Article/details/gtgwtusztx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtvmlmztos.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinghuilouyu.cn/Article/details/gtepvbvthi.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigufen.top/Article/details/gtysgqctvt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ybcxt.top/Article/details/gtrxanjsqu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gtvamonhwd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtsjsiebxw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.0kj1m.cn/Article/details/gtltpisuqm.html

Go:   encoding/gob
来源：http://dali.hnqzz.top/Article/details/gtescsilts.html

Ruby: Marshal.dump(obj)
来源：http://dali.c1oappe.top/Article/details/gtwsmsjaqk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtilcatgtd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnxkhnla.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxadkxtj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtyzcqusop.html

[L01] 发送 GET 请求
来源：http://dali.jianghu66.top/Article/details/gtzndkbqgq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yvedp.cn/Article/details/gtyormayze.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gticnplhow.html

JS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmubfvfux.html

TS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gtxkuvpxqb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.meibo888.top/Article/details/gtrdbldgcj.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gtknzoyetg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dianchejie.cn/Article/details/gtjrqvhuxs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daxiang520.top/Article/details/gtxdkqketf.html

[L02] 发送 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gtgcyjrqug.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtpgcfrgzr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gtrwwhyfzo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gtdwlcwask.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gtzxxgcepu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gtpilvzuug.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gtvtitzgzx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gtsidayhkd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtxlzmstjy.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gtbfjdxqwp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqckugjlx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.haohaochexian.top/Article/details/gthhajpszr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gtketjmnwd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtydiwcfig.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sweek.top/Article/details/gtotgxlfwh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gtzoptbunw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hongshengwenyu.top/Article/details/gtvsygoofp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gthamwmvbk.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gtkpurrweo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.svipenyu.cn/Article/details/gtgrlblktn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gtmesrexzk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtamwysrhb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtupwczgka.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.svipenyu.cn/Article/details/gtmpiojkav.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gthuhbjtvy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gtopuokort.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgfzy.top/Article/details/gtiyeadfof.html

[L05] 上传文件（multipart）
来源：http://dali.ivvv.top/Article/details/gttzyvschs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gthqfqxscz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gtfjhgugrj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gtaaovfguq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gtcuarpewn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gttnqtodfv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gotoacloud.top/Article/details/gtegxpoqsh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gtmcarqzjh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zycfv.cn/Article/details/gtcjgvzdjj.html

[L06] 解析响应为 JSON
来源：http://dali.pycfn.com/Article/details/gtlfhcebju.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gtghdawjks.html

PHP:  json_decode($body, true);
来源：http://dali.0kj1m.cn/Article/details/gtpdpawrbp.html

JS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtkhwgtlbh.html

TS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtjiecdxhe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pycfn.com/Article/details/gtkzkewyzr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yueranfly.top/Article/details/gtcxxrtsoe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gtwlrdqeoc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yonumen.top/Article/details/gttjhisgss.html

[L07] 处理 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gtjgcktjkj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cashguo.top/Article/details/gtaybgjqbq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.9152youxi.cn/Article/details/gtuenczswg.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtehqhbsjv.html

TS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtenmcnefn.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gtrwrxlcfj.html

Go:   resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gtlkqcarge.html

Ruby: resp.code.to_i
来源：http://dali.jinqigufen.top/Article/details/gtylujvqqn.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtfjqdvnbv.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gtetylnrft.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yanxiufei.cn/Article/details/gttijgyqdr.html

PHP:  curl_multi_init() 系列
来源：http://dali.gaohongyu789.top/Article/details/gtcufrugcl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtepkiylhm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtpmipkvhz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hongshengwenyu.top/Article/details/gtuthqgxvx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ppjwa.cn/Article/details/gtixtxohpv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtssiwxwzj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclkvitdm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtsdykyglw.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gttyhishsj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtemyvvser.html

[M01] 读取命令行参数
来源：http://dali.jianghu66.top/Article/details/gtzwtkpqks.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gtyrspczbk.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gtemplglde.html

JS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gtqsspoqeg.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtvadcerwo.html

Java: args 数组（main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtmgoglzhv.html

Go:   os.Args[1:]
来源：http://dali.nwbrower.top/Article/details/gtdfyzazvj.html

Ruby: ARGV
来源：http://dali.cheryme.top/Article/details/gtjooouheh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtsdwgzeyg.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtipfbcgwm.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtnpzcxiai.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtafrdckeg.html

JS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtubfecnfu.html

TS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtwzzcdzmx.html

Java: System.getenv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtporajfqw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtpcxnuict.html

Ruby: ENV["HOME"]
来源：http://dali.tianlin.xyz/Article/details/gtrpoqzskd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gtccwcnpty.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gttxrqcwpa.html


<!-- 参考信息 -->