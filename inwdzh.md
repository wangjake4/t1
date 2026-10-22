代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aizwys.cn/Article/details/gt2agbmssqq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2iwopaaij.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwyrnyh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2qnmwvjgx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bnqpjztx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gt2tfwmvlfo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gt2sxexzsnn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gt2uoeqonsj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.mhx1999.top/Article/details/gt2qjakkwzt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gt2sygdzgpt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtryfizk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqljgcew.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gt2yntcnwjb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ncgpasxt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.smart0.xyz/Article/details/gt2kwlkzqdh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shangyingyoupin.top/Article/details/gt2rwdfeqkq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gt2twaueddc.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gt2iskfwfgi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gt2dvbtghjj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gt2mfuaiocw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.0kj1m.cn/Article/details/gt2obboshve.html

TS:   /error/gim
来源：http://dali.yj20258888.top/Article/details/gt2txoxctus.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenzaomai.com/Article/details/gt2xwqhctkk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.smart0.xyz/Article/details/gt2tsuupwch.html

Ruby: s.scan(/error/i)
来源：http://dali.xinyue.icu/Article/details/gt2hmeidtnr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.snrcjt.cn/Article/details/gt2cgceuqvc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xziqi.cn/Article/details/gt2gxvkmeuj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cucudq.cn/Article/details/gt2ymderudf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gt2jbkudlxs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gt2hcsrisuj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gt2bqyznsxh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gt2bepvrxbi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gt2vlooobxe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gt2qlfllnxb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gt2wjwfbznm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxtzjevo.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gt2zoflgpat.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ddzjxyxf.html

[J01] 获取当前时间
来源：http://dali.aizwys.cn/Article/details/gt2yzjzybro.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gt2ecexgdko.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gt2autegziv.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gt2gfvnzdfn.html

TS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gt2wuljtsoa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2rsibsnhy.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gt2ormgbihd.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gt2ixocrohu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ehwqpu.com/Article/details/gt2csjowjbl.html

[J02] 格式化输出
来源：http://dali.shuidangran.top/Article/details/gt2tjhyqval.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gt2vxnpnxie.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gt2lfnnxcil.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ppjwa.cn/Article/details/gt2ildctsnx.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gt2lqcrbrlg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gt2flrceckz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj202588.top/Article/details/gt2qgrxiykr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gt2mdcikuav.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrthyzej.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gt2tavbyxjh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnxiangtu.top/Article/details/gt2lwpwzaww.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnwrtqht.html

JS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2nrigmhxo.html

TS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2ufhwbufx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2rbompxdj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2mrclnulu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2hkyiokma.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sysykeji.top/Article/details/gt2dbaoomyu.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gt2rpdxrisu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2bydhmduw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cheryme.top/Article/details/gt2juccuwgi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.meibo888.top/Article/details/gt2grdbzpom.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangdashe.top/Article/details/gt2dkgxnwge.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fengsongda.top/Article/details/gt2dakyxqiu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykavwmmj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2hrpkviaj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pycfn.com/Article/details/gt2fdfqagrq.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhixingplan.top/Article/details/gt2hehcgdph.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gt2vidgvmoy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gt2qcevcyhy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gt2nwijbhkz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zzhuwpfa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sweek.top/Article/details/gt2micctjeh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gt2fgauzgfn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gt2zjvrkqrc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gt2wesjlule.html

[J06] 计算两时间之差
来源：http://dali.xuetiantiany.cn/Article/details/gt2xkpfjnmo.html

Py:   (end - start).total_seconds()
来源：http://dali.cucudq.cn/Article/details/gt2riyvhkzj.html

PHP:  $end->diff($start)->days;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nttmmvhr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.svipenyu.cn/Article/details/gt2fcsykcxv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ydzc1.top/Article/details/gt2unezlhzc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gt2pghdcwua.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gt2wipkovbn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jyoumei.cn/Article/details/gt2qixvtgmy.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gt2jscqtwlk.html

[J07] 比较两个日期
来源：http://dali.jianghu66.top/Article/details/gt2kxsjbuni.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gt2konoyixn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cashguo.top/Article/details/gt2hzxqpkjt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gt2qaiwiayi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gt2sqvhqsdg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gaohongyu789.top/Article/details/gt2ungmaulm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gt2tllyxnnn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2vltdplpq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2vfysorlc.html

[J08] 提取年月日与星期
来源：http://dali.xuanzx.com/Article/details/gt2bxtaluru.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj202588.top/Article/details/gt2hvbcdxlk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.meibo888.top/Article/details/gt2ypfuivpr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hongshengwenyu.top/Article/details/gt2eefxidtr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gt2msgyihmu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2edzfvixn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xylfe.cn/Article/details/gt2zfjvkzpq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigufen.top/Article/details/gt2olgphkhs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxinkj.top/Article/details/gt2ujvwngxp.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gt2blphbcgs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rpjdxwcv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukvvuypt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gt2sijecdet.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gt2mzgmkkco.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gt2kotgffnv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzlthozm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gt2nmsnwjdn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gt2vmacptzl.html

[J10] 取今天 / 本月第一天
来源：http://dali.sysykeji.top/Article/details/gt2xrngqiad.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hywenlv.cn/Article/details/gt2qaetupla.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gt2sfatmksz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuanzhike.top/Article/details/gt2etjqmcwx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gt2gwdahlip.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gt2zbmjulys.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gogol.net.cn/Article/details/gt2fhjsiyjl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nwbrower.top/Article/details/gt2hyiuzrsp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gt2jnbafluu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ljppkekr.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gt2smohedne.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2fbmbpdkv.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gt2hqhcnbyh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gt2enqnqyou.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gt2bdxbvmjm.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2qcibdqfl.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qiplhhys.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.birdmap.top/Article/details/gt2fqbtibfx.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gt2mdpfazeb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gt2saffdiuc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkcgjtmo.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gt2kjlfrbzh.html

Py:   json.loads(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qipnitlv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gt2nbbfqltt.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivwpqmzy.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wytwhwbs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nwbrower.top/Article/details/gt2sefqstan.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hnauohts.html

Ruby: JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cejbbhhm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hfpthk.cn/Article/details/gt2hstejbug.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pycfn.com/Article/details/gt2lxryqgod.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gt2atuplqng.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xopwecyk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2kcyuifim.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2evmdaazq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sdjmxefd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zdqjudy.top/Article/details/gt2oqqczslg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2goozdvvc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rgtwcmyw.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gt2lfopwwmk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gt2vqeicllc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shzxlz.cn/Article/details/gt2cebqyryh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gt2okruedzm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gt2scyrblgg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ybcxt.top/Article/details/gt2dktdfugr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kojeunst.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvcnnhbb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pycfn.com/Article/details/gt2qxzwaocx.html

[K05] 深拷贝对象
来源：http://dali.xylfe.cn/Article/details/gt2bhbxtdja.html

Py:   copy.deepcopy(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2wkkbfutr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwwkqtnl.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mnkkgtjg.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gt2wxemrido.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gt2fdhkkqko.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gt2pbvbayll.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cashguo.top/Article/details/gt2otanypvr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuanzx.com/Article/details/gt2szrfdoql.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gt2tlmdyenz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aizwys.cn/Article/details/gt2gldpbbyc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgufenzy.top/Article/details/gt2yfpwewwi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gt2wulcsnvq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtrjpggk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sysykeji.top/Article/details/gt2bucpizet.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gt2gmanxxko.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2voivydmx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gt2uldqtodo.html

[K07] 进制转换
来源：http://dali.yj20258888.top/Article/details/gt2wphhnapu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2uowlbokc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmshdnug.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2qqdlezhu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsyzzuqb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2lkstaaxy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gt2bdzlanug.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.kuanghao11.cn/Article/details/gt2xzkoehmd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gt2uhiycyhm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gt2beqokooe.html

Py:   pickle.dumps(obj)
来源：http://dali.xuanzx.com/Article/details/gt2reuhidax.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gt2rubjcohx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gt2cbuzxpko.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gt2ugnydgwq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gzhubu.top/Article/details/gt2suhlbunt.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gt2lfxoemsg.html

Ruby: Marshal.dump(obj)
来源：http://dali.fengsongda.top/Article/details/gt2dbfpqffo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gt2tucqxkev.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2rqtstmrq.html

L. 网络请求
来源：http://dali.kuanghao11.cn/Article/details/gt2pyjqcxii.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kwfaktbo.html

[L01] 发送 GET 请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cuwbhmpq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gt2hlhbssrf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tian-w.cn/Article/details/gt2aqaznysz.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gt2wsqslckb.html

TS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2ydafislh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gt2erkxkecx.html

Go:   resp, err := http.Get(url)
来源：http://dali.yvedp.cn/Article/details/gt2stbkzlin.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gt2ajfhmzhn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gt2pbalumdk.html

[L02] 发送 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2kjewonzi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gt2nkucfaeu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yvedp.cn/Article/details/gt2rbwwvlgi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gt2fimspxjk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xdnuzedb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.meibo888.top/Article/details/gt2pnlbqtln.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xziqi.cn/Article/details/gt2uxhfgjlb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cdnleiting.top/Article/details/gt2ndnkqiui.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daxiang520.top/Article/details/gt2cbvayozn.html

[L03] 设置自定义请求头
来源：http://dali.yueranfly.top/Article/details/gt2yhtjfjnh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guannengcc.top/Article/details/gt2rqxqwsuq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj202588.top/Article/details/gt2zvtktmtn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gt2ltsfnnpc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gt2yyxgcuem.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqowgdga.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gt2esmtwhxq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jlsjyb.cn/Article/details/gt2jffxhylo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gt2tlokejci.html

[L04] 设置超时
来源：http://dali.ybcxt.top/Article/details/gt2cciugdzg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.meibo888.top/Article/details/gt2ocbgmsmg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gt2imlfgvbo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2cxloozkw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gt2xizugbcf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gt2dvigypbi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gt2desgoxcb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gt2zvwyatgz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gt2dthzjkhu.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258.top/Article/details/gt2rhbpfiha.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gogol.net.cn/Article/details/gt2ocbsogcr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gt2meblrqta.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2uxitkmue.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gt2hcilsyra.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuxming.cn/Article/details/gt2wjzfhknd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.meibo888.top/Article/details/gt2aifxblkz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jlsjyb.cn/Article/details/gt2vdbcyfcl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2gjuqhubs.html

[L06] 解析响应为 JSON
来源：http://dali.cucudq.cn/Article/details/gt2izczkdyw.html

Py:   resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2nfaboeuk.html

PHP:  json_decode($body, true);
来源：http://dali.nwbrower.top/Article/details/gt2vfnvctbg.html

JS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gt2yclgxbxu.html

TS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2lthqyinj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bexsoyfn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bvwgjqnd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gt2uwitbclm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gt2zwqbjemg.html

[L07] 处理 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gt2qztbfwbx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenzaomai.com/Article/details/gt2ehzkrnbz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gwadxbab.html

JS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gt2hdcasrqp.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gt2wgivxukf.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2esvlgwpd.html

Go:   resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gt2bmtwpixr.html

Ruby: resp.code.to_i
来源：http://dali.sxryk.cn/Article/details/gt2anstusdh.html

C#:   (int)resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gt2awlginft.html

[L08] 并发请求多个地址
来源：http://dali.daria6918.cn/Article/details/gt2xyrccfue.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzkcgren.html

PHP:  curl_multi_init() 系列
来源：http://dali.mhx1999.top/Article/details/gt2jfpozsyc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gt2fotrgljs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2akaqhkfj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gt2dxdlsqva.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zdqjudy.top/Article/details/gt2rwekbtir.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gt2cruabrsg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bncmmmtq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ledmhpea.html

M. 命令行 / 进程 / 环境
来源：http://dali.shzxlz.cn/Article/details/gt2nhodwtwb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2crrshnpb.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gt2qydfobon.html

Py:   sys.argv[1:]
来源：http://dali.zhongyouzk.top/Article/details/gt2xveoocpa.html

PHP:  $argv;  $argc;
来源：http://dali.haohaochexian.top/Article/details/gt2jgfugits.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gt2cuwefuaf.html

TS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gt2pxmtlvjo.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gt2lzdqqleu.html

Go:   os.Args[1:]
来源：http://dali.chenlongwang.top/Article/details/gt2kpnfcexk.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gt2axdypzwi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2sejaogrp.html

[M02] 读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gt2dqomlver.html

Py:   os.environ.get("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2gmngwhyu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gt2hauxgwjr.html

JS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gt2ygtseedz.html

TS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gt2ocfflmsg.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2pxttwkla.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2nnduovaq.html

Ruby: ENV["HOME"]
来源：http://dali.zhixingplan.top/Article/details/gt2wqgpkwfl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2cshskylj.html

[M03] 执行外部命令
来源：http://dali.zhengqikj.top/Article/details/gt2vrlbnsry.html


<!-- 参考信息 -->