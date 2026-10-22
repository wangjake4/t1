代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ppjwa.cn/Article/details/gt2uqwyuqwq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2wqgiixrm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gt2vvhytawi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zhfglyyv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gt2jxbmhmrl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gt2hfgdbkee.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gt2wbggimmc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gt2issmqeaq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhiwuduotai.top/Article/details/gt2howmnyor.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2beyefohh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgufenzy.top/Article/details/gt2opcqyrgm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gt2gaimhydr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gt2yhmilars.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gt2mkgvlhcm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgufenzy.top/Article/details/gt2hngvonka.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2shvgjhhp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2gyulrqoo.html

[I07] 忽略大小写与多行模式
来源：http://dali.dianchejie.cn/Article/details/gt2hpuzcbot.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gt2ifwpvjii.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ivvv.top/Article/details/gt2kfdmrbus.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gt2obnajtip.html

TS:   /error/gim
来源：http://dali.zhiwuduotai.top/Article/details/gt2vqxeeazi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.smart0.xyz/Article/details/gt2nmxflrre.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gt2ajszicqq.html

Ruby: s.scan(/error/i)
来源：http://dali.pycfn.com/Article/details/gt2krsimjiw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hysaishi.cn/Article/details/gt2trnutoqf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gt2gbrwibiw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fzhhl.top/Article/details/gt2xwivkutu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oxmnwzsx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gt2rlcjspwf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrmozcq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gt2yvqroipl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyexhuf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gt2oqdgzxzx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gt2pgqimtmm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2zpibqafm.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2clngbnhm.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2hjishvax.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxernubz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gt2klnsnqfb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gt2tfetaxnu.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2trfjpsms.html

TS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gt2hdznqsdt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2riqhsfal.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gt2erxmrvkb.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gt2ebrdbpxq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yongpay.top/Article/details/gt2znqahyaq.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rllqyxia.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gt2fjimwsao.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gt2jqzxinic.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gt2fszyzxkg.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gt2ywnricxk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gt2vhgzcwga.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shuidangran.top/Article/details/gt2yupefwdo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gt2hjbckdbz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dianchejie.cn/Article/details/gt2vvqisfbo.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gt2hrkgnabu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gt2hneiajzf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuetiantiany.cn/Article/details/gt2qadjxgiq.html

JS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2brxgfgyi.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2wjnevrtx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2cmcslpao.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2lwqfqwuf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2iqzrcgys.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.mhx1999.top/Article/details/gt2rfprebqv.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gt2irnapeew.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2xhwcwfrs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shuidangran.top/Article/details/gt2qwcoziyv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gt2unpcilqo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2okqzohxe.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkpskgxz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gt2xlwcyhdt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gt2pktnqksk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2pbvjdzhk.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdvbadj.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gt2mbrwcmwf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gt2upylwkod.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2njmkkjai.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gt2urnrnikj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ydhlvlxj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yueranfly.top/Article/details/gt2vwdbilhr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.316326.xyz/Article/details/gt2roriqrjw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgjlrbbf.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gt2uouulwpl.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gt2pvaepzml.html

PHP:  $end->diff($start)->days;
来源：http://dali.jyoumei.cn/Article/details/gt2drxznqiu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dashuyun.cn/Article/details/gt2azhbmvmu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.vqdsnc.cn/Article/details/gt2rhhwrbtl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gt2qcvjdhdv.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gt2whyukias.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hongshengwenyu.top/Article/details/gt2wepwxuup.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gt2wrocplar.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gt2gsgsncnx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gt2ozihjlzb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ivvv.top/Article/details/gt2gvnmfewi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gt2baqygfat.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gt2miscbnqm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gt2wuwwmvnf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jiagoushi.top/Article/details/gt2cokvqaak.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2sotuaahv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gt2pbacvfpm.html

[J08] 提取年月日与星期
来源：http://dali.yueranfly.top/Article/details/gt2appkedih.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gt2rtebivfm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gt2bexbdbfe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gt2wsagzsqf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ruunxfql.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigufen.top/Article/details/gt2izvdqvca.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hywenlv.cn/Article/details/gt2ythvlsxi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gt2svhckxdq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.haohaochexian.top/Article/details/gt2mtlcaxux.html

[J09] 时区处理
来源：http://dali.gaohongyu789.top/Article/details/gt2boyijkne.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yangfankeji.com/Article/details/gt2xgahocsk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj202588.top/Article/details/gt2igkpjkxk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gt2ynrnjqvy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ilscbfrf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2urhewbev.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daxiang520.top/Article/details/gt2jikkawkp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgfzy.top/Article/details/gt2nkdxubcg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gt2gbtprwih.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gt2yhxmffyi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iskkghqp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nihzheke.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sxryk.cn/Article/details/gt2hbcshhxi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kbzrfqbl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tanke756.top/Article/details/gt2qugcelox.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258.top/Article/details/gt2xyndlaor.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuanzx.com/Article/details/gt2euoyvftv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gt2gomvvzbh.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2uufxsrez.html

K. JSON 与序列化
来源：http://dali.cashguo.top/Article/details/gt2snfurulw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ccpynfbv.html

[K01] 对象转 JSON 字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2utydchlu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gt2shuhjgww.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2pqmeksgi.html

JS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jojdbada.html

TS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2dvkofpcq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuanzx.com/Article/details/gt2qsfollsl.html

Go:   json.Marshal(obj)
来源：http://dali.316326.xyz/Article/details/gt2ygqyhugs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytjesmgb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2coaqmyyr.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gt2nlsiplnz.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gt2lirgenpu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shuidangran.top/Article/details/gt2ojrjnjwe.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gt2yhsiwjbx.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2iamnonzw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2hvdsjmgp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dqqyfrfk.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gt2iddgkxsn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangdashe.top/Article/details/gt2rqtgbius.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tianlin.xyz/Article/details/gt2zidkgvgp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gt2lncbywml.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gt2esofgpae.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gt2iobshykg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2etspduoy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2qrxpwqoz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gt2uclcdwat.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gt2tnvkojsn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gt2zpghykiq.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gt2tuhpssey.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gt2eluirodt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guannengcc.top/Article/details/gt2xrxjvtfq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2cqeiakgi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2kenkcwxu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2zyhavpup.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gt2alaamgwp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gt2dkikwjrr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gt2kpknwwqh.html

[K05] 深拷贝对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2swnscseb.html

Py:   copy.deepcopy(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2bpjmtxlx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gt2wfhhatop.html

JS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2ddfkhrca.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2frdvgoyx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigfzy.top/Article/details/gt2mqvkjoys.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejziwygb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gt2vybthvus.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gt2uuieqsla.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gt2nbmgpshu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gzhubu.top/Article/details/gt2ibfnuvbd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dashuyun.cn/Article/details/gt2gzqunldf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gt2hpquenxk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gt2cpkqamev.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gt2aunmjadz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2ocacmaze.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2axquqriy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gt2dostmjwn.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gt2iljsxngz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2ziytptlv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gt2wjvpwfyr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mslddrwf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2jqzpjtmy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2foibueqo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gt2txpojkdm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgufenzy.top/Article/details/gt2vpqylmwz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2euczlqra.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gt2lwmvurwv.html

Py:   pickle.dumps(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2iszhmxid.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ybcxt.top/Article/details/gt2euzskjgy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2genaddhb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gt2fyczhdbf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gt2oaiovkvx.html

Go:   encoding/gob
来源：http://dali.vqdsnc.cn/Article/details/gt2sfxqsrxz.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2vioruxlc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gt2icliebwk.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2lgpjeynw.html

L. 网络请求
来源：http://dali.iojbl.cn/Article/details/gt2dzovgkzx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2rrnrqkvd.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gt2mdgqyztw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oaolhpxa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hfpthk.cn/Article/details/gt2mniimodq.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gt2vzjheljk.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tsqhnfuj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2guhywvgu.html

Go:   resp, err := http.Get(url)
来源：http://dali.c1oappe.top/Article/details/gt2darbvuhd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gt2dsmsjdex.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dccsqzmx.html

[L02] 发送 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2jezwwxgb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daria6918.cn/Article/details/gt2awyntxnk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gt2ubxyyasr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gt2bkitmbsa.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gt2eqyuiihy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dianchejie.cn/Article/details/gt2jicchghu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gt2rtdhfwwf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258.top/Article/details/gt2gbosdgyd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gt2jrwhwcfj.html

[L03] 设置自定义请求头
来源：http://dali.yueranfly.top/Article/details/gt2cjukcwgm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.meibo888.top/Article/details/gt2aocaazlw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2rvshmshw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gt2agpzkzyp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gt2dahfjohs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnqzz.top/Article/details/gt2flbanhhh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gt2gbxdkoaw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aizwys.cn/Article/details/gt2ggpmxcdj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gt2dpmzarhb.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gt2ldyxryfv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gt2nsnmehmq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yueranfly.top/Article/details/gt2ykcteedl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gt2jpphxzsk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gt2xxdblyda.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pycfn.com/Article/details/gt2teytzcbu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gt2slbakiar.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.havefunace.top/Article/details/gt2bhanjugk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangdashe.top/Article/details/gt2suzoowia.html

[L05] 上传文件（multipart）
来源：http://dali.tianlin.xyz/Article/details/gt2futwttgd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guowangkeji.top/Article/details/gt2whpvacsl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jiagoushi.top/Article/details/gt2egvoryut.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gt2hgubezux.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gt2ukluwhyb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gt2xngkavwj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gt2shspmnsq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258888.top/Article/details/gt2lgihktcw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkxfjnw.html

[L06] 解析响应为 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2thiedkih.html

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gt2janrbvtn.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gt2mgfwsfui.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2ddkakuvv.html

TS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gt2ujgphwox.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2atgctkcf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gt2xsoanluh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigufen.top/Article/details/gt2ielywzey.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gt2tzsubgwx.html

[L07] 处理 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gt2qimavcqm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2julxgzrd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gzhubu.top/Article/details/gt2xywhwfzy.html

JS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gt2ofakgmdz.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gt2leezblir.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gt2agfygvks.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gt2bmohsgxv.html

Ruby: resp.code.to_i
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uygsoezt.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gt2pgsnkoid.html

[L08] 并发请求多个地址
来源：http://dali.hywenlv.cn/Article/details/gt2iklfinic.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gt2tuuredbq.html

PHP:  curl_multi_init() 系列
来源：http://dali.iojbl.cn/Article/details/gt2eyezoljq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2keablmds.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gt2uuepmohk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gt2nlkybqlk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gt2gvkmktwz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gt2nzhmpkir.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.redwolf501.top/Article/details/gt2wzoistsg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2wdcwpqrw.html

M. 命令行 / 进程 / 环境
来源：http://dali.gogol.net.cn/Article/details/gt2qfhqmlyn.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ytkvhnsb.html

[M01] 读取命令行参数
来源：http://dali.yuxming.cn/Article/details/gt2wjtnjctu.html

Py:   sys.argv[1:]
来源：http://dali.shuidangran.top/Article/details/gt2fwdbbsbe.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gt2tkouujqj.html

JS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gt2swrceuds.html

TS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gt2gwewwinv.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2amnupark.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gt2lwvynurh.html

Ruby: ARGV
来源：http://dali.daria6918.cn/Article/details/gt2nrsnziur.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjspvwyf.html

[M02] 读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gt2jreqvjso.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2yxncluyo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gt2yrzlmdyz.html

JS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gt2nvbtzekt.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2vtlzlhda.html

Java: System.getenv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2pmdlkgyv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2wvypfjgg.html

Ruby: ENV["HOME"]
来源：http://dali.jiagoushi.top/Article/details/gt2umtevbsk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2fpiyihib.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gt2uledxbfv.html


<!-- 参考信息 -->