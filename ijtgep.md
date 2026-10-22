代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eglbdfla.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2srzuiqvi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gt2ouqfvmfa.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gt2oaobagab.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fengsongda.top/Article/details/gt2gjuwfiis.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gt2gyvaemah.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2zbeqyyyw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2eqbtkovl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gt2syaajvwn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gt2vanvkdmq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2uniedpzx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oucfvtoe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhiwuduotai.top/Article/details/gt2hcmlfihq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gt2qggzzsgn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gt2zkmndhne.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2jamzwihr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gt2eoqfmqbt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2jvntsmmt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nwbrower.top/Article/details/gt2nbhcgrxf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jyoumei.cn/Article/details/gt2dfhulucf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2fdvfuowp.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenjidiqi.icu/Article/details/gt2uavlknhe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jlsjyb.cn/Article/details/gt2wskkdcjz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gt2vdyakmck.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gaohongyu789.top/Article/details/gt2ffpvladx.html

TS:   /error/gim
来源：http://dali.fengsongda.top/Article/details/gt2wwtylouz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvkfkuge.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mnupfyxx.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gt2cspgdold.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gt2lpaxzqsf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fzhhl.top/Article/details/gt2huqlagdo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgufenzy.top/Article/details/gt2jmhgyogv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gt2lyewebti.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gt2qothdhwj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gt2rhwyarvt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gt2qzzjgbdj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dashuyun.cn/Article/details/gt2jcvozdwl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gt2zvtyapsw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gt2ixdmffig.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2rghriffb.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gt2nlizejqh.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2fipnswpm.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gt2fjifhdqd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gt2nfqozlvi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gt2otclriou.html

JS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2liteqrcb.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gt2uhkldmng.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gt2olzvsate.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gt2ktvgsmzw.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mekyvtkk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shuidangran.top/Article/details/gt2jipczemo.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gt2anidntcm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fiiftwcq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gt2cmpkmwgl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daxiang520.top/Article/details/gt2dgluechk.html

TS:   d.toISOString()
来源：http://dali.yvedp.cn/Article/details/gt2izvhuvui.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gotoacloud.top/Article/details/gt2kknkzuuz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigfzy.top/Article/details/gt2oatilxpb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bawdqmps.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gt2inoaeiit.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gt2nszktyzx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhengqikj.top/Article/details/gt2fyrubkxe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yanxiufei.cn/Article/details/gt2irndfbzx.html

JS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2ljgnurqn.html

TS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2odqqhmqy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2vhxjroum.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2vufqhktw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2mqzedbnw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbqqxjkg.html

[J04] 时间戳与日期互转
来源：http://dali.andypj.xyz/Article/details/gt2ujhsdkmp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258.top/Article/details/gt2olzlohvi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gt2irxvebav.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnqzz.top/Article/details/gt2qtnemsea.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gt2zlebzfti.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gt2mrbfcqqz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oovnrnnx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhkvkjch.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cheryme.top/Article/details/gt2ccfwjrud.html

[J05] 时间加减（加 7 天）
来源：http://dali.cqqwz.cn/Article/details/gt2xmjcupea.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zsllqcpg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gt2hjwhudyb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gt2ppqqvnng.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gt2jmjunynl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gt2bfkmmfyh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gt2mnwpcrze.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gt2xkwkpomh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gt2aduympjh.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gt2byvkqlvc.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qodzkoeu.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfuozdht.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pycfn.com/Article/details/gt2ninnptiz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gt2dljcbznr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pycfn.com/Article/details/gt2epolgvup.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnxiangtu.top/Article/details/gt2klpsusah.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuanzhike.top/Article/details/gt2ukovfxoy.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gt2kqfnmxfa.html

[J07] 比较两个日期
来源：http://dali.yj20258888.top/Article/details/gt2ngbwaolq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gt2pwdxtujk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gt2dysovjvi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gt2axqnvlax.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gt2klwyuioi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.meibo888.top/Article/details/gt2rwdxalbt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sufxvd.cn/Article/details/gt2exawcztm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2udptlzkh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gt2dywwywis.html

[J08] 提取年月日与星期
来源：http://dali.yanxiufei.cn/Article/details/gt2nltoxpgw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuanzx.com/Article/details/gt2qycbhvou.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gt2gyxyokph.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gt2hpgvacil.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2suprhvwt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.havefunace.top/Article/details/gt2dhhocubd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gt2jpuudhkc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gt2qgflyxne.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gt2vzydhemx.html

[J09] 时区处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lititidw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.9152youxi.cn/Article/details/gt2obetkbtf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zycfv.cn/Article/details/gt2kaksxwkh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gt2mybewmxj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gt2kduoyics.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gt2mzasvhoq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gt2gudsterc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenzaomai.com/Article/details/gt2qtwwksho.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gt2ocvyeehb.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnxiangtu.top/Article/details/gt2yeuxjjyo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gt2lhqmoscv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gt2vbiodxxe.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gt2wxppvcsw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yoybcupz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gt2hapwzvyq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xylfe.cn/Article/details/gt2zebsrqhq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gt2kbrimkej.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gt2hnyivodf.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2rfijzaan.html

K. JSON 与序列化
来源：http://dali.hnxiangtu.top/Article/details/gt2zopytphl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2dupkpshb.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gt2vwzqsgbm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqvbmblo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gt2wreqwgdq.html

JS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gt2rrhgxaun.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gt2qkarqgcu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cdnleiting.top/Article/details/gt2hgnsqwrk.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2abzhqspv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnxiangtu.top/Article/details/gt2kjupiwgb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gt2vpmcpyvx.html

[K02] JSON 字符串转对象
来源：http://dali.fzhhl.top/Article/details/gt2binncrsk.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gt2veasejpm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yangfankeji.com/Article/details/gt2voepwiwe.html

JS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gt2wcffspnm.html

TS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2tajkicfm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2nyllchkp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gt2verfjwbl.html

Ruby: JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gt2fffscpnh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2xccyrphq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gt2yyjnhwgn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gt2bvxfjvqp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gt2gzoksoxf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gt2xsstxlng.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2ckulsqrn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sysykeji.top/Article/details/gt2jmpuptna.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.9152youxi.cn/Article/details/gt2qmkfxeqx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2olpmmbzb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuanzx.com/Article/details/gt2tzeavetw.html

[K04] 读取 JSON 文件
来源：http://dali.yonumen.top/Article/details/gt2moqxtsjy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fzhhl.top/Article/details/gt2oingulot.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yueranfly.top/Article/details/gt2daavpbaw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gt2qhivxrwd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gt2czboowfk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gt2hsnbsoik.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gt2cednxxvd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gt2vsfwnvlk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gt2vlgnyifp.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gt2axpmjpqd.html

Py:   copy.deepcopy(obj)
来源：http://dali.fengsongda.top/Article/details/gt2gcjxdvlj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2poffqejj.html

JS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gt2vsvervzo.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2lqpvfruj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gt2rqboqnyn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gt2xqtpsudw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gt2yqnhmkzc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dianchejie.cn/Article/details/gt2nrujzwnd.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gt2qcrkzcpf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gt2zayqnzwo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gt2nupcmdgf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gt2ftyabfdo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dwjpmpny.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gt2avyshixi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2prcvuwio.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gt2wgqolwmy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gt2bngtvctc.html

[K07] 进制转换
来源：http://dali.yanxiufei.cn/Article/details/gt2etmythte.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2vxfkeotb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fzhhl.top/Article/details/gt2psjxfdjd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2kbjjcqnd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2lngkxozs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2owmnwaar.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgufenzy.top/Article/details/gt2tblrrbvi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fengsongda.top/Article/details/gt2ezwkpavq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2pwipxynf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gt2toupwdsn.html

Py:   pickle.dumps(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2jezrpozo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gt2hzxrmhtv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gt2ismawjef.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gt2htwyrwgg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj202588.top/Article/details/gt2tmtdzuon.html

Go:   encoding/gob
来源：http://dali.smart0.xyz/Article/details/gt2whbxzqur.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2jkcgwrei.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gt2xsqdqpmm.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2eypzllvo.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gt2jwizbkdi.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2nhenzfip.html

[L01] 发送 GET 请求
来源：http://dali.yonumen.top/Article/details/gt2hhvjduqe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuanzx.com/Article/details/gt2jslltqwb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dashuyun.cn/Article/details/gt2xprgojyl.html

JS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gt2lzzhwupx.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvtcwli.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gt2uyvpeefn.html

Go:   resp, err := http.Get(url)
来源：http://dali.jianghu66.top/Article/details/gt2nffttcid.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenzaomai.com/Article/details/gt2kvmjcjsj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuanzhike.top/Article/details/gt2qlybfqkv.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gt2zmodocgk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sxryk.cn/Article/details/gt2ulrsvpnn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.meibo888.top/Article/details/gt2gonprpho.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gt2saobczpz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gt2kiclwkdg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdjbmhoz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.andypj.xyz/Article/details/gt2hkbygxva.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gt2nrfkdggj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.iojbl.cn/Article/details/gt2dfgzfllw.html

[L03] 设置自定义请求头
来源：http://dali.yueranfly.top/Article/details/gt2ygjkmtwf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jiagoushi.top/Article/details/gt2xhhpmopt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shzxlz.cn/Article/details/gt2zzqvknkb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gt2cidkapef.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gt2ncyrwvwt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yanxiufei.cn/Article/details/gt2kmmbablq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gt2xbazaqmt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eabbtkiy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gt2omnytajt.html

[L04] 设置超时
来源：http://dali.jlsjyb.cn/Article/details/gt2xwujehem.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aizwys.cn/Article/details/gt2wszxkiyf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jiagoushi.top/Article/details/gt2isdpbran.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gt2mkaxvxux.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gt2pdjmzywu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigufen.top/Article/details/gt2wihwincp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hammf.cn/Article/details/gt2relpiymn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gt2qswgtkba.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.redwolf501.top/Article/details/gt2btopraty.html

[L05] 上传文件（multipart）
来源：http://dali.chenzaomai.com/Article/details/gt2rmcstxva.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daxiang520.top/Article/details/gt2nyjnrite.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gt2hjwikkql.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gt2vipppact.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gt2pigwfvos.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.bjfxy.top/Article/details/gt2mqgrgytj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenlongwang.top/Article/details/gt2zqulaypm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ivvv.top/Article/details/gt2fgeeulgo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljqnmnmh.html

[L06] 解析响应为 JSON
来源：http://dali.hammf.cn/Article/details/gt2hvwfqdhs.html

Py:   resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2ktkxoguh.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gt2nhduwxjp.html

JS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gt2gzvpslxr.html

TS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gt2nmozimdr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2rpltyzeu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gt2zcdguhdd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.kuanghao11.cn/Article/details/gt2ryoooquh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xdwvwirh.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gt2qndnodik.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.smart0.xyz/Article/details/gt2juhbsnzp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gt2stzhgixn.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2cfgyygap.html

TS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gt2hbnveias.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gt2dsjvaoha.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gt2isvdklwt.html

Ruby: resp.code.to_i
来源：http://dali.sxryk.cn/Article/details/gt2amwbxrox.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gt2yphzhkut.html

[L08] 并发请求多个地址
来源：http://dali.guowangkeji.top/Article/details/gt2bfvpbfzs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umxnsoje.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gt2rdlpkgmt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gt2jkfklsqk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gt2vfjaytah.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2laoauwev.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gt2fxmqiqop.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gt2wrpipzcq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gt2ovkyylpi.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2eboavpzz.html

M. 命令行 / 进程 / 环境
来源：http://dali.9152youxi.cn/Article/details/gt2fdxzrbtw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2oedddkjz.html

[M01] 读取命令行参数
来源：http://dali.316326.xyz/Article/details/gt2dduuwpsd.html

Py:   sys.argv[1:]
来源：http://dali.xinyue.icu/Article/details/gt2ollzusgm.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urjpynll.html

JS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gt2mkobytei.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gt2qfuewnqo.html

Java: args 数组（main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gt2iihvscik.html

Go:   os.Args[1:]
来源：http://dali.316326.xyz/Article/details/gt2aaotjwnu.html

Ruby: ARGV
来源：http://dali.shangyingyoupin.top/Article/details/gt2ggxtkxsf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gt2msxhmapq.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gt2qhoadvnj.html

Py:   os.environ.get("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2llqbeeah.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gt2kcxllypy.html

JS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gt2nmdpghpu.html

TS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gt2fxmywyxp.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gt2jecoroxf.html


<!-- 参考信息 -->