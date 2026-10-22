代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gt2jiqacnva.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnqzz.top/Article/details/gt2eavjzxjp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2gxbqddfp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gt2ewgoembe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gt2lbpbibge.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gt2vhnqsjcr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xziqi.cn/Article/details/gt2xionwrct.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gt2qgwyuthi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gt2fgnwnvet.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gt2tfzqhfnr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gt2qafxmzrg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhongyouzk.top/Article/details/gt2yasaftly.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhcmzjld.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gt2qtwkufya.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.snrcjt.cn/Article/details/gt2hdgcqljd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gt2mkfpqjvb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yvedp.cn/Article/details/gt2ckbleqge.html

TS:   /error/gim
来源：http://dali.ppjwa.cn/Article/details/gt2mxzbfbvy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.andypj.xyz/Article/details/gt2uoggaygl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gt2kunodiwv.html

Ruby: s.scan(/error/i)
来源：http://dali.chenlongwang.top/Article/details/gt2mojzjphn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258888.top/Article/details/gt2imthmjcf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tianlin.xyz/Article/details/gt2rdipvreg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gt2tjyjrnsx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gt2nlxsyzxr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gt2ytzvcwsc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gt2hrdtknnu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gt2hjbohbvy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dianchejie.cn/Article/details/gt2yqleekhd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.vqdsnc.cn/Article/details/gt2fjcjnosp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gt2pqwblyvh.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2omzkewzd.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gt2xanybmeg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2byonhvaw.html

[J01] 获取当前时间
来源：http://dali.xuanzx.com/Article/details/gt2krszsnew.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gt2jvogdkyq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gt2gmrttegv.html

JS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gt2smywgwoi.html

TS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2fhqaeuvh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gt2ilzumfex.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzstjtsv.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmlrniqr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxuanxn.top/Article/details/gt2avzwqhfi.html

[J02] 格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzrjkfdg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gt2qzzjkkvm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gt2nvhszbfp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.haohaochexian.top/Article/details/gt2zklavomm.html

TS:   d.toISOString()
来源：http://dali.ppjwa.cn/Article/details/gt2yapctvxy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gt2seyedped.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gt2wedhlyzs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gt2ikgrjrae.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gt2hrhtoyae.html

[J03] 字符串解析为日期
来源：http://dali.yj20258888.top/Article/details/gt2gyizfgqt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.0kj1m.cn/Article/details/gt2eihsczaa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.9152youxi.cn/Article/details/gt2kilifjke.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2zocnaopz.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2zgzaxjsw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2svzhvscv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2arnujjvz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2atsezrin.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gt2xvxbibfx.html

[J04] 时间戳与日期互转
来源：http://dali.jianghu66.top/Article/details/gt2nhsxyjzj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2yqxbiaej.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2masoumjw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gt2ghfuspam.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhongyouzk.top/Article/details/gt2idfdchww.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2ufhxwzkf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2qutetqhv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gt2bjjyveiw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yvedp.cn/Article/details/gt2gpmrhuxa.html

[J05] 时间加减（加 7 天）
来源：http://dali.xylfe.cn/Article/details/gt2uzztzonu.html

Py:   now + timedelta(days=7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dnsenkye.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.birdmap.top/Article/details/gt2gotnjbza.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ytvgagqa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2hexkwlei.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtwiyotn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2wjkfthyj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuetiantiany.cn/Article/details/gt2wbbzhccp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gotoacloud.top/Article/details/gt2yefrtsej.html

[J06] 计算两时间之差
来源：http://dali.yongpay.top/Article/details/gt2vtfxmuxf.html

Py:   (end - start).total_seconds()
来源：http://dali.daxiang520.top/Article/details/gt2yucacqdy.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj202588.top/Article/details/gt2rrpzbvsf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jianghu66.top/Article/details/gt2swqovcvv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gt2qjevmpnb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yongpay.top/Article/details/gt2epkfrdkh.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gt2dlsmjzyh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gt2wfkdqrrl.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gt2ikjqmyqm.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ppqdekel.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2waseffpl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sufxvd.cn/Article/details/gt2plgqbjjh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gt2vppwpgfg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lrbrmjzp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dianchejie.cn/Article/details/gt2xikkvukp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2lycesngd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2ozmhtyzf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2gqbvgmkt.html

[J08] 提取年月日与星期
来源：http://dali.zhongyouzk.top/Article/details/gt2jkeprfvl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghjewwpt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.316326.xyz/Article/details/gt2ldugollu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ybcxt.top/Article/details/gt2loybvixd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gt2gpbqqtlm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gt2oexmndwm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gt2wsgbyqbe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sweek.top/Article/details/gt2fkrjlwwx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenjidiqi.icu/Article/details/gt2pafgxmjo.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gt2piglmqus.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xinyue.icu/Article/details/gt2mehcgyyy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hfpthk.cn/Article/details/gt2ikulxzjw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gt2fkghqesn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjmyldul.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cdnleiting.top/Article/details/gt2lkpantuz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gt2vsdxvmkh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sufxvd.cn/Article/details/gt2monuvhnu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gt2tpjrzycv.html

[J10] 取今天 / 本月第一天
来源：http://dali.yangfankeji.com/Article/details/gt2nkuluxap.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shuidangran.top/Article/details/gt2yledixns.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jyoumei.cn/Article/details/gt2cvhznnfs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.svipenyu.cn/Article/details/gt2uoixjiyu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjjhunbe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cqqwz.cn/Article/details/gt2phuxqzgp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cashguo.top/Article/details/gt2mqteeybb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yanxiufei.cn/Article/details/gt2ejcrskej.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.meibo888.top/Article/details/gt2jdqiibsq.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2xvyrocuh.html

K. JSON 与序列化
来源：http://dali.zhengqikj.top/Article/details/gt2lhcjsxed.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2hchxugek.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj202588.top/Article/details/gt2rjgaiccs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gt2upnfpdvq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gt2cnbbayvm.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gt2jrbmemsq.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2jlzbtusx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gt2ajagqdmk.html

Go:   json.Marshal(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxumonig.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgmomeru.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ydzc1.top/Article/details/gt2ozpschaa.html

[K02] JSON 字符串转对象
来源：http://dali.xziqi.cn/Article/details/gt2tacauwmh.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2utpkegjl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2aoawriep.html

JS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2gikvnbdq.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2ufuofvhl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzvxaoyl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gt2scguhwfm.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2jshisiqe.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gt2pvupioaa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gt2zuuqzxkj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gt2lqzmwnks.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gt2blydwwgr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2zwvyjmmj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gt2nihqqwdb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangdashe.top/Article/details/gt2jftpykis.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gt2usohymzz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gt2yffsdblz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sufxvd.cn/Article/details/gt2mfafkyvr.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqcangtd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daxiang520.top/Article/details/gt2hrddfroj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gt2xrqdxivx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ixtcckui.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2pvliwkkw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ydzc1.top/Article/details/gt2pxkgztlo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gt2btdnbhpf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvjsryza.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqqhfjqt.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gt2mnotvwkj.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tognmhhu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gt2noveofoo.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uikqpumd.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cleaqvnl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnthijeq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gt2ccifkytq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aibaodan.cn/Article/details/gt2pohnbgnz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tianlin.xyz/Article/details/gt2toxeedwx.html

[K06] 解析 URL 查询串
来源：http://dali.yanxiufei.cn/Article/details/gt2nuqnstvh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gt2ujnhsvoj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.meibo888.top/Article/details/gt2pngmqhks.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2patjuxyi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdgpfvdi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gt2crxacctc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2omripara.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gt2bqiuuisb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gt2unwivnjm.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gt2utkgsspm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2wqbfgika.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gt2ocejlhxf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2spvorocf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2bbmomvmd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2basggwxu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gt2nxnuaezw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258.top/Article/details/gt2xftxpyxg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gt2qezfmnwj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gt2rztyfclb.html

Py:   pickle.dumps(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2svoyskve.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gt2avehceyq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gt2xeptmkqu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gt2tbvaqmjw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.0kj1m.cn/Article/details/gt2tcltgxtd.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdjrkyar.html

Ruby: Marshal.dump(obj)
来源：http://dali.316326.xyz/Article/details/gt2nqzdhets.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2ktszjjzu.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2rnzaykxg.html

L. 网络请求
来源：http://dali.shzxlz.cn/Article/details/gt2frzsbubq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2pgtncerf.html

[L01] 发送 GET 请求
来源：http://dali.sweek.top/Article/details/gt2atgefcfa.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xuphfemi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhengqikj.top/Article/details/gt2ozcahttt.html

JS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2ltwajqgk.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gt2dsvktcdy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfckogk.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2kjydvpci.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hongshengwenyu.top/Article/details/gt2esckwnxr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangdashe.top/Article/details/gt2elbdhtjy.html

[L02] 发送 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gt2oqzgjzvt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gt2hsyzzwfr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hongshengwenyu.top/Article/details/gt2anewzuqn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gt2azshtzvu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gt2kdmetbzy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenlongwang.top/Article/details/gt2qbcrwbsh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gzhubu.top/Article/details/gt2ynehmgrl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxplkwqn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ydzc1.top/Article/details/gt2yibkknjj.html

[L03] 设置自定义请求头
来源：http://dali.ydzc1.top/Article/details/gt2lvmukelj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gt2oakypfyh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxinkj.top/Article/details/gt2fcqylahc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gt2qpxclwnj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gt2vyyyuase.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gt2gaosrupx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gt2kexinomf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzpucqwu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gt2azlgngvw.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gt2qvfhkrhb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yvedp.cn/Article/details/gt2jtwfvldb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jiagoushi.top/Article/details/gt2jofhfkuq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gt2ayomavsb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djchcslc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tanke756.top/Article/details/gt2higwfuii.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guowangkeji.top/Article/details/gt2bsmluhij.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ppjwa.cn/Article/details/gt2yscvlhsp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ivvv.top/Article/details/gt2mjxmzyqd.html

[L05] 上传文件（multipart）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2epxgvyae.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gt2vfcwnutn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sxryk.cn/Article/details/gt2uikiuvwr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gt2qmqhtsdq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gt2yywiyjef.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangdashe.top/Article/details/gt2chqbhhzi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2czllcdxr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gt2jabimncd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2cepwfodf.html

[L06] 解析响应为 JSON
来源：http://dali.zycfv.cn/Article/details/gt2owlgpkxu.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2kczkesxh.html

PHP:  json_decode($body, true);
来源：http://dali.gaohongyu789.top/Article/details/gt2snzjgmgd.html

JS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gt2xdtonnvl.html

TS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2skjelrmw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyqqftp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangdashe.top/Article/details/gt2yrrhstuz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cdnleiting.top/Article/details/gt2kurnxpdl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jianghu66.top/Article/details/gt2uzwpqbks.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gt2jtehmsfn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258.top/Article/details/gt2lroeydke.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2pzzmhpwc.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gt2ljkxefqg.html

TS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gt2ilpmegbh.html

Java: resp.statusCode()
来源：http://dali.yuxming.cn/Article/details/gt2dyjsqimj.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gt2bqwjbmlq.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gt2onxrpvmq.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gt2mugdzqft.html

[L08] 并发请求多个地址
来源：http://dali.sufxvd.cn/Article/details/gt2uomcreys.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gt2zkdozajb.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenzaomai.com/Article/details/gt2dlhdebhq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gt2rylbbjzn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxagijaw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gt2hqojggxt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ybcxt.top/Article/details/gt2ncyfhkdi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xinyue.icu/Article/details/gt2yrebnzaa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.smart0.xyz/Article/details/gt2wemfwhui.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2jokremkm.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gt2khfrmgil.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2akglnqbj.html

[M01] 读取命令行参数
来源：http://dali.pycfn.com/Article/details/gt2wpsayevp.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2nlinmiga.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gt2ekqzxmiw.html

JS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gt2dwceyqil.html

TS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gt2vcpwvvft.html

Java: args 数组（main 方法参数）
来源：http://dali.yj202588.top/Article/details/gt2gfxtxkni.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gt2hhtdywvn.html

Ruby: ARGV
来源：http://dali.fzhhl.top/Article/details/gt2skttdfwr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gt2zmfmuvcq.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gt2leaqqssd.html

Py:   os.environ.get("HOME")
来源：http://dali.yangfankeji.com/Article/details/gt2qsqbsmsz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gt2ffxmmiva.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gt2jantjmda.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gt2enqbqijf.html

Java: System.getenv("HOME")
来源：http://dali.tanke756.top/Article/details/gt2dvgqozza.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2bkgqqdmb.html

Ruby: ENV["HOME"]
来源：http://dali.xziqi.cn/Article/details/gt2odxbiejs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2zbnjwiqn.html

[M03] 执行外部命令
来源：http://dali.cqqwz.cn/Article/details/gt2zkhnheay.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gt2fyifzatx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gt2efckcrst.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gt2ntrwmybb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vdqhrqfi.html


<!-- 参考信息 -->