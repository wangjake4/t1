代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xbzjmjog.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gt2adiywxql.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.snrcjt.cn/Article/details/gt2xgoaespi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gt2echqvfqo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gt2osewgjsd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gt2efvxzgnw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258888.top/Article/details/gt2kboyheyk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cashguo.top/Article/details/gt2pzbdidnp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2ejelntxb.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gt2udtqbpoh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gt2rztbdkmt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gt2hkydducl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gt2evdxhzbt.html

TS:   /error/gim
来源：http://dali.fzhhl.top/Article/details/gt2fvciiqjv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gt2xdruaqjg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.quarkkingdee.top/Article/details/gt2jhhrkzjh.html

Ruby: s.scan(/error/i)
来源：http://dali.wangdashe.top/Article/details/gt2zqryznfm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shzxlz.cn/Article/details/gt2rtzmnjcg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gt2ojqxnput.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gt2cwfubhgw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gt2savjyftc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gt2cdtezyba.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gt2jieorvle.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gt2bhgvugmw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gt2tswmlpoi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gt2ldogrbrz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbiybfgo.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2pftadlzd.html

J. 日期与时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2qypikmii.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2kcrgqxme.html

[J01] 获取当前时间
来源：http://dali.yanxiufei.cn/Article/details/gt2omheabty.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzjlzjqa.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gt2skvokriq.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adfdvhzr.html

TS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gt2yzblhxsc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gt2oblgzwaw.html

Go:   time.Now()
来源：http://dali.316326.xyz/Article/details/gt2pqzjtjet.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gt2qfhhfldh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gt2aptuevnl.html

[J02] 格式化输出
来源：http://dali.zhixingplan.top/Article/details/gt2nuxjpmfu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gt2cbxrcxwi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gt2qdoyvplz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gjejnrbx.html

TS:   d.toISOString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrrrqtxd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gt2nvvmmlcb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.meibo888.top/Article/details/gt2slwuecjw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gt2dmyvkwdq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gt2irxagmmr.html

[J03] 字符串解析为日期
来源：http://dali.zhixingplan.top/Article/details/gt2qnlohgub.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.andypj.xyz/Article/details/gt2uxwwlcen.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gt2dzfhawrj.html

JS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2ozmnoflc.html

TS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2qcqpfbnh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqmjmnbm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2oxxvrwne.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2nttqxrym.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.9152youxi.cn/Article/details/gt2mlbvoalc.html

[J04] 时间戳与日期互转
来源：http://dali.jlsjyb.cn/Article/details/gt2xrrvsxsz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2mbcvztqx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gt2lpydhdvn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fztsnbcw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gt2zlhxitbu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvjjjdgd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ngnqttfn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.redwolf501.top/Article/details/gt2yxvmrigq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptgfrsbn.html

[J05] 时间加减（加 7 天）
来源：http://dali.sxryk.cn/Article/details/gt2rpedpycu.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gt2fricltpa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yueranfly.top/Article/details/gt2vdbdwkth.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gt2vyjsaufr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gt2skamhjri.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigufen.top/Article/details/gt2uwxkzwco.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cashguo.top/Article/details/gt2xzlejluk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hywenlv.cn/Article/details/gt2syylogzk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gt2jarkhdao.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gt2chpeeyhc.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ehyrefef.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuanzx.com/Article/details/gt2hnafuueh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj202588.top/Article/details/gt2ugvxchdb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tanke756.top/Article/details/gt2pthokbdv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2asjaezou.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gt2jmwnfleh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tianlin.xyz/Article/details/gt2uztucrke.html

C#:   (end - start).TotalSeconds
来源：http://dali.shuidangran.top/Article/details/gt2dmkhucxv.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gt2cunaoyon.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2tziwsquv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.haohaochexian.top/Article/details/gt2xcntlqmz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqwieqrn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gt2awwljdax.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gt2pvsnflcg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2auaogvpr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2kscxdiid.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2wfhqnquv.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gt2ypnrkprt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gt2pwwlvldl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangshuangyany.cn/Article/details/gt2hscjoctm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hfpthk.cn/Article/details/gt2rpxebitd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gt2qsvadday.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gt2rzsujofp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gt2zctbdvcu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nwbrower.top/Article/details/gt2tvghhpai.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zycfv.cn/Article/details/gt2seynupvf.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gt2vnoxkrdz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gogol.net.cn/Article/details/gt2ugtnuotg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhengqikj.top/Article/details/gt2rmuobbvn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gt2lbpjobmd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gt2ensnputw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfmwckky.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yanxiufei.cn/Article/details/gt2yoijfcgh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gt2pgtmlhcc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gt2opssuhnj.html

[J10] 取今天 / 本月第一天
来源：http://dali.aibaodan.cn/Article/details/gt2nsyhhqpq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hfpthk.cn/Article/details/gt2vkvwqslw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenzaomai.com/Article/details/gt2tcltmpjw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gt2gykfkkvp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.birdmap.top/Article/details/gt2lfayfzlr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gt2zqfnywqy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zdqjudy.top/Article/details/gt2ayjeufpd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cucudq.cn/Article/details/gt2zlmhakhm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gt2gfxqqsup.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcjilxbg.html

K. JSON 与序列化
来源：http://dali.sysykeji.top/Article/details/gt2dnkdppna.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2zjrttpiq.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgfzy.top/Article/details/gt2clehgeap.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gt2klwqpbfv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhwsutxr.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2iigoktwo.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gt2nifkknju.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gt2kkernowj.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2zpjqgbaa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gt2fhwrffjw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ivvv.top/Article/details/gt2nqrijsgo.html

[K02] JSON 字符串转对象
来源：http://dali.kuanghao11.cn/Article/details/gt2rauibskk.html

Py:   json.loads(s)
来源：http://dali.yongpay.top/Article/details/gt2fhzncuvh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gt2gqzfoqbw.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nxhpceth.html

TS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2mapuwbih.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2qpttsdjq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gt2iayxelbw.html

Ruby: JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2irbcnmrq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ehwqpu.com/Article/details/gt2sufyqpbz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gt2yldyashr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bxxzbmtm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gt2edkemaqw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gt2csusmbhw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gt2yxbklecx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xevoirld.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tanke756.top/Article/details/gt2ufwzkjvf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2tvakisrf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gt2xoahncfp.html

[K04] 读取 JSON 文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2dsvwjevb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnafpls.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhengqikj.top/Article/details/gt2nlzrafcb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gt2ezlowozc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gt2llxcxygz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258.top/Article/details/gt2igquimar.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gt2qnsjogyt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ybcxt.top/Article/details/gt2vrqiwmte.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gt2jsctegww.html

[K05] 深拷贝对象
来源：http://dali.nwbrower.top/Article/details/gt2fzpxwubk.html

Py:   copy.deepcopy(obj)
来源：http://dali.yueranfly.top/Article/details/gt2xexvsior.html

PHP:  unserialize(serialize($obj));
来源：http://dali.vqdsnc.cn/Article/details/gt2bbplkifz.html

JS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2rhfqxefc.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2uppbnsnc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cheryme.top/Article/details/gt2avrauxmz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gt2wgjtcfek.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gt2qfpmcpwk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenzaomai.com/Article/details/gt2zveoryue.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvleget.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2lfjkfahz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gt2djbyzqve.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gt2cpmellxf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2zsmpciyl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gt2wxgoznuo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gt2srxlvatp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gt2oczyitjh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqnrmbkz.html

[K07] 进制转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2kfhwaugz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2wfaklcrv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gt2yygzpniv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2iwkoirrv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2lmjvtwff.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2jjigotrz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sufxvd.cn/Article/details/gt2mnzffsid.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gt2zifexsoy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2sktvcame.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gt2evmdtzio.html

Py:   pickle.dumps(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2eekgdxno.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gt2vrtybrat.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gt2glrexsbg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmpjtxjc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.0kj1m.cn/Article/details/gt2rtujnyme.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gt2vcmdekoa.html

Ruby: Marshal.dump(obj)
来源：http://dali.yvedp.cn/Article/details/gt2zyotsbpe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gt2riyaxizl.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnhotjbh.html

L. 网络请求
来源：http://dali.mhx1999.top/Article/details/gt2zjtjgkhr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2oyfvayey.html

[L01] 发送 GET 请求
来源：http://dali.sufxvd.cn/Article/details/gt2hhweadbc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nwbrower.top/Article/details/gt2trdqohwb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gt2lmzsqaxh.html

JS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gt2rebnponw.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gt2slrjuihz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gt2wwcxoaqv.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gt2nhlqnffc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gt2mzarviwp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qvajvpnw.html

[L02] 发送 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxjcvims.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gt2gqplsmut.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2laysojbr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gt2tffkihnt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gt2qmpwbdsl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigfzy.top/Article/details/gt2jmitexmt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ydzc1.top/Article/details/gt2fohbggix.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.iojbl.cn/Article/details/gt2hgaktxta.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gt2zgsmtywp.html

[L03] 设置自定义请求头
来源：http://dali.316326.xyz/Article/details/gt2dioeimly.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gt2xwlkulrx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.havefunace.top/Article/details/gt2ekhtkenv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gt2njwfnacn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gt2lozszade.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gt2slmjshhg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gt2dfdtaili.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jiagoushi.top/Article/details/gt2fzolchit.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gt2sksxfleo.html

[L04] 设置超时
来源：http://dali.nwbrower.top/Article/details/gt2nixlqkrp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shuidangran.top/Article/details/gt2tpfmfuct.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.andypj.xyz/Article/details/gt2htdhpbjh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gt2nywimsbk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aajxqrnn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gt2fctafdpn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.redwolf501.top/Article/details/gt2ucnkazcj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gt2hjpfvyvz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gt2lbyhchgx.html

[L05] 上传文件（multipart）
来源：http://dali.kuanghao11.cn/Article/details/gt2bxwafoqr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aibaodan.cn/Article/details/gt2julgkfex.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gt2dolwujmj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gt2cehtpxuf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gt2ewwpqsyw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.feifeiyinyue.top/Article/details/gt2iwzjzxpp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gt2klybgdli.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gt2wzvmorxi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2bgvvfwjp.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ryenjeyx.html

Py:   resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gt2jpisumhn.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gt2ofxtbakp.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2wuhvjlej.html

TS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gt2fffictln.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2cbufjlgi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gt2igqtbewg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gt2wfxivnaw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gt2ftlxwfkp.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdmygnzo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hywenlv.cn/Article/details/gt2kovuxitc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gt2zekkbsgx.html

JS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gt2qgwafdqy.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkmcelyl.html

Java: resp.statusCode()
来源：http://dali.yanxiufei.cn/Article/details/gt2wjnhefkw.html

Go:   resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gt2rpapsslg.html

Ruby: resp.code.to_i
来源：http://dali.xuanzx.com/Article/details/gt2swfencuk.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gt2hqbysnyh.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gt2vhzmxxym.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2zhphoxaj.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuliefmn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2kosspvpm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2vgerffvh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yanxiufei.cn/Article/details/gt2xbwbreay.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ppjwa.cn/Article/details/gt2ehxfniha.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shuidangran.top/Article/details/gt2ilyjhaxh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yueranfly.top/Article/details/gt2qrrdfmxz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2nkfaxauk.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhoulong.xyz/Article/details/gt2ctyajbyq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2hfsavcai.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gt2ilppjvet.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gt2fuqlsbld.html

PHP:  $argv;  $argc;
来源：http://dali.fengsongda.top/Article/details/gt2mjgmmern.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gt2pgqzrnri.html

TS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gt2fyuskexk.html

Java: args 数组（main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2twexfaar.html

Go:   os.Args[1:]
来源：http://dali.fzhhl.top/Article/details/gt2fdbldmfj.html

Ruby: ARGV
来源：http://dali.yangfankeji.com/Article/details/gt2hcrgyvhl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gt2yebqxtrl.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gt2aawptvwp.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2qehnjeoy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2ocvgojpi.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gt2lcwfyjuy.html

TS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gt2qsduswhs.html

Java: System.getenv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2sjgyhadz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2tuptfhin.html

Ruby: ENV["HOME"]
来源：http://dali.xylfe.cn/Article/details/gt2gnoksfsr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2nrkoeosx.html

[M03] 执行外部命令
来源：http://dali.cashguo.top/Article/details/gt2zsiapzaj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gt2giznixqc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gt2qvskebaj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gt2wqeygjmi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gt2cbcdtupd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yongpay.top/Article/details/gt2gmrkymiy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258.top/Article/details/gt2imwwkkyo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.andypj.xyz/Article/details/gt2kwcfgidx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gt2kuacmdwz.html


<!-- 参考信息 -->