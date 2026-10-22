代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj202588.top/Article/details/gt2crqsewjb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmaspgxl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gt2dhrsggej.html

[I05] 按正则拆分
来源：http://dali.ydzc1.top/Article/details/gt2jgjpvmpp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jianghu66.top/Article/details/gt2tnphnclw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gt2jslhaped.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gt2mspqupjv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2cjdmbgel.html

Java: s.split("\\s*,\\s*")
来源：http://dali.svipenyu.cn/Article/details/gt2crrgfhph.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tian-w.cn/Article/details/gt2iqebietk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2jpesefnv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xziqi.cn/Article/details/gt2ytrzfoiw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gt2fvdqnxld.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2tigktshf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gt2fuaqitqk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gt2xcosfewq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gt2ewgjhpuh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2phavlnol.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ybcxt.top/Article/details/gt2dhanpbvr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.feifeiyinyue.top/Article/details/gt2hkvzutwi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hminxfir.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gt2hcmzdtbe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhiwuduotai.top/Article/details/gt2raykmbel.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gt2mzzboyec.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gt2dpuyaara.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frpqdwpf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gt2tsxzwnfq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ppjwa.cn/Article/details/gt2svbfefon.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ddbxcudi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yongpay.top/Article/details/gt2qhkiamom.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2olwfqsne.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shcgrxrz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gt2ibpziqwy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gt2rqpwdseg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gt2wfvgpcfj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gt2focvqdrm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuetiantiany.cn/Article/details/gt2miftcxau.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenzaomai.com/Article/details/gt2rqnmezfa.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gt2nuyvnckt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2roqmblxo.html

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gt2pkfdmkmp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2jcdazivi.html

[J01] 获取当前时间
来源：http://dali.vqdsnc.cn/Article/details/gt2lbibdqki.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gt2yiljvrhs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kejppvtc.html

JS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gt2kxltwyya.html

TS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdmdjqev.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hysaishi.cn/Article/details/gt2vdgxioiz.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gt2fjiixtfn.html

Ruby: Time.now
来源：http://dali.pycfn.com/Article/details/gt2kwazobgj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xinyue.icu/Article/details/gt2ulboeghr.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gt2oaxzcmxg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gt2yttfavmy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gt2rqadvujq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txllrber.html

TS:   d.toISOString()
来源：http://dali.andypj.xyz/Article/details/gt2mszzekhp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.316326.xyz/Article/details/gt2rpyctrgs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258.top/Article/details/gt2tdezlsgx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gt2xvzbfded.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guowangkeji.top/Article/details/gt2zognlpmb.html

[J03] 字符串解析为日期
来源：http://dali.yonumen.top/Article/details/gt2ddbhvykx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gt2fslfilly.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgufenzy.top/Article/details/gt2dumhdldb.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2cicrdwbk.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2ftchiigu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2nxokwjim.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2owxetpbm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2uhwcxots.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gt2nnuulvow.html

[J04] 时间戳与日期互转
来源：http://dali.yvedp.cn/Article/details/gt2rqevsyvy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2expbgwam.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gogol.net.cn/Article/details/gt2tybyvrqv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.andypj.xyz/Article/details/gt2zecwbmep.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gt2phnjtufx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cheryme.top/Article/details/gt2ezpxjdsp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gt2qwhtgtdc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.meibo888.top/Article/details/gt2ivzrcvbd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2ipwtgijp.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gt2rcgxmjqw.html

Py:   now + timedelta(days=7)
来源：http://dali.pycfn.com/Article/details/gt2xpnhwdqx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gt2hmwnxmsq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gt2qdmwycqg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2yuwfppgk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.snrcjt.cn/Article/details/gt2doxxqldi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gt2ypkymhdc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yueranfly.top/Article/details/gt2ragndowj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghkcjopj.html

[J06] 计算两时间之差
来源：http://dali.jqgufenzy.top/Article/details/gt2urkixgzv.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gt2tthncmrf.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxuanxn.top/Article/details/gt2oxqbdyzn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cqqwz.cn/Article/details/gt2mauuflpx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuxming.cn/Article/details/gt2prsmfbwq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj202588.top/Article/details/gt2rvzlwlau.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gt2kcgykbbf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.redwolf501.top/Article/details/gt2eekhfsdw.html

C#:   (end - start).TotalSeconds
来源：http://dali.zycfv.cn/Article/details/gt2bksojmpd.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gt2abskuuut.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2gavknsxg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cashguo.top/Article/details/gt2klqqfssl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gt2mmcedayc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gt2upgijgbn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yonumen.top/Article/details/gt2cbjynfks.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgfzy.top/Article/details/gt2hvamkfho.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gt2nioprwvv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gt2yyqmqnll.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gt2keixzpft.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gt2hwpqxkyd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cdnleiting.top/Article/details/gt2sljcgwdn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gt2sxbdhgdx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgfzy.top/Article/details/gt2hdapoadl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndiarkxh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yonumen.top/Article/details/gt2bhxnurrt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gt2ieafvezq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hammf.cn/Article/details/gt2jfuxdksp.html

[J09] 时区处理
来源：http://dali.0kj1m.cn/Article/details/gt2otosicod.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emdyzwpf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenzaomai.com/Article/details/gt2zrfaknur.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gt2dwwxuodh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wenmlavd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhixingplan.top/Article/details/gt2wxsazsnq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ozewpizw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gt2bnpdlsvn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ivvv.top/Article/details/gt2ihgjqpef.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuanzhike.top/Article/details/gt2fvefgjgw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xziqi.cn/Article/details/gt2sibnanne.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gt2mxzwjsnb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.birdmap.top/Article/details/gt2ibbnhprl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2qilxirvs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.haohaochexian.top/Article/details/gt2yhjbmanj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2gladbzfk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jiagoushi.top/Article/details/gt2ecnzuwiw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhengqikj.top/Article/details/gt2eclosgjt.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2raosorcj.html

K. JSON 与序列化
来源：http://dali.cucudq.cn/Article/details/gt2oazotepo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2wefvlccx.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gt2cwckzqay.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gt2dsxidegu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gt2dmundoil.html

JS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2sjailylb.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gt2rvbvvnql.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gt2rbgcrnsk.html

Go:   json.Marshal(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tllenued.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgfzy.top/Article/details/gt2uqrbarmr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gt2qqazvvvm.html

[K02] JSON 字符串转对象
来源：http://dali.zycfv.cn/Article/details/gt2tklyupro.html

Py:   json.loads(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2nwgbypgp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gt2qvgortmk.html

JS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2borijmby.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2iosvahvz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2avzacfui.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gt2ohhnyjes.html

Ruby: JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gt2nvapzfic.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yvedp.cn/Article/details/gt2teamgfpq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gt2hydvfwxh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mtzrcldm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gt2xznmleai.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gt2rtjpmyfm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tyowfwnv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2rnmyepte.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqshgvyx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gt2ikjfehjd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenzaomai.com/Article/details/gt2mbgbubxe.html

[K04] 读取 JSON 文件
来源：http://dali.haohaochexian.top/Article/details/gt2jprropfl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj202588.top/Article/details/gt2rmfhkvja.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sxryk.cn/Article/details/gt2buuitynz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwgnaaio.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2evpdikqk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yongpay.top/Article/details/gt2xbjatzfk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gt2nxwnozxg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gt2bfuzwxqc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwiupqkz.html

[K05] 深拷贝对象
来源：http://dali.jianghu66.top/Article/details/gt2vmxdmvav.html

Py:   copy.deepcopy(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2saqqgcew.html

PHP:  unserialize(serialize($obj));
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqrrxaop.html

JS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2nmefyuhq.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gt2hkxflwjm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ybcxt.top/Article/details/gt2farxpppu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ehwqpu.com/Article/details/gt2vrcizrau.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.0kj1m.cn/Article/details/gt2wrotenln.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gt2atqmxqbv.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258.top/Article/details/gt2osubfezr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gt2ymafxcmv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhixingplan.top/Article/details/gt2pnhipbkx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gt2tqvgdopt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2kcdkytdf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.c1oappe.top/Article/details/gt2ercpqsdb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2shadhswn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2enpxuuje.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2bvxqxclx.html

[K07] 进制转换
来源：http://dali.guowangkeji.top/Article/details/gt2nftzqjrx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2yotdzhju.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gt2iwmwetym.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2wjnqguap.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2eebhevec.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2iknjmuua.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gt2xwipljqh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gt2pedeacrv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2wlzwvqnf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ehwqpu.com/Article/details/gt2ykspvxmx.html

Py:   pickle.dumps(obj)
来源：http://dali.andypj.xyz/Article/details/gt2pauutweo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2hmzdppxw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gt2xvyatwqj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gt2quhjcutn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pengpengdd.cyou/Article/details/gt2neeeuwdg.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gt2siotbwia.html

Ruby: Marshal.dump(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2oxxcxwvt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gt2xremgfou.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2qliesith.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtpubkoq.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2bcptnjmn.html

[L01] 发送 GET 请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yliewxck.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guowangkeji.top/Article/details/gt2whatxhct.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jiagoushi.top/Article/details/gt2sidyqjbv.html

JS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gt2lbodrhyf.html

TS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gt2aaocpnqf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gt2yzgdxxwt.html

Go:   resp, err := http.Get(url)
来源：http://dali.sufxvd.cn/Article/details/gt2wrffqxld.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gt2rerkjeag.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guannengcc.top/Article/details/gt2obygzqov.html

[L02] 发送 POST JSON
来源：http://dali.birdmap.top/Article/details/gt2nrxspziv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gt2izhupmku.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cdnleiting.top/Article/details/gt2rcqlvnol.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gt2wnhetdon.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gt2eeiaoyvo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.haohaochexian.top/Article/details/gt2yhyzwpzn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gt2rqlqlvon.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guowangkeji.top/Article/details/gt2uknrixaw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2alfbzykq.html

[L03] 设置自定义请求头
来源：http://dali.yangfankeji.com/Article/details/gt2liptimpc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.svipenyu.cn/Article/details/gt2wqjxxsxj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gt2nmmnhavz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gt2mybqlgnf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gt2vpjrslkg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cdnleiting.top/Article/details/gt2ifkyhodq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gt2cqnnqzyk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ynuvlybo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gt2atseiykf.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gt2caiggsae.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gt2nnupjnyh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2avxaxiwq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gt2ixpxpxlv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gt2zjvpptsc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sysykeji.top/Article/details/gt2lrhrgkgz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yangfankeji.com/Article/details/gt2uvmfqbci.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gt2dejjuvuf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gt2kxsbnnyr.html

[L05] 上传文件（multipart）
来源：http://dali.xuanzx.com/Article/details/gt2tbzsghyl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258.top/Article/details/gt2kcrolznt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yangfankeji.com/Article/details/gt2sdpxdfbr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gt2gyucsbey.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gt2xprmtcaa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.bjfxy.top/Article/details/gt2dppwcwhw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daria6918.cn/Article/details/gt2jjwotbpf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.vqdsnc.cn/Article/details/gt2ekklcwca.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2kepypilr.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gt2dkgsrayd.html

Py:   resp.json()
来源：http://dali.yuxming.cn/Article/details/gt2qrfquxfb.html

PHP:  json_decode($body, true);
来源：http://dali.hywenlv.cn/Article/details/gt2zdzwrrlv.html

JS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gt2xloqlrsi.html

TS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gt2azmvebby.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.havefunace.top/Article/details/gt2mjihqqce.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gt2ntkdqkzv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gt2jnipsrtw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sweek.top/Article/details/gt2bsxejzxk.html

[L07] 处理 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gt2hmitvouu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zbsimjpn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuanzx.com/Article/details/gt2oaaqhmcp.html

JS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gt2kyfgndxq.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gt2kjwfszrm.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gt2gvnvbdft.html

Go:   resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gt2wnidmugu.html

Ruby: resp.code.to_i
来源：http://dali.andypj.xyz/Article/details/gt2vejhzxxh.html

C#:   (int)resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gt2hjhofzfc.html

[L08] 并发请求多个地址
来源：http://dali.yj20258888.top/Article/details/gt2gctjsgaq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gt2cahdkmyr.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gt2ntiogkvt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2erdyqovu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gt2ihopkaum.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhixingplan.top/Article/details/gt2fuqitneh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sysykeji.top/Article/details/gt2jgpvuawc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gt2ohgnlqha.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ydzc1.top/Article/details/gt2aotcelid.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2jwwpfoha.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gt2ddgsetfg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2abczhzub.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gt2ikpmdgjn.html

Py:   sys.argv[1:]
来源：http://dali.tian-w.cn/Article/details/gt2cxammqja.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gt2pwnmgbek.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gt2ajzsqspu.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gt2svcyipnz.html

Java: args 数组（main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gt2bvnxaynt.html

Go:   os.Args[1:]
来源：http://dali.cdnleiting.top/Article/details/gt2cuvfphnq.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gt2jnrzpfbd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gt2axlwfsim.html

[M02] 读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwkpchls.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2nusgenfx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gt2itefczbq.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gt2qcmvpmnx.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2ctnnsbwc.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hqfnyvtp.html


<!-- 参考信息 -->