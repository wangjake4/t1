代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj202588.top/Article/details/gt2yenpuapd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2ycfursvo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gt2xqhlrtfj.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gt2kzxhcbvc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tanke756.top/Article/details/gt2plpgrdnn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2kvwpkjsz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gt2itdibkoq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2whvehdwr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gt2pndpkhtb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gt2vgjupvkz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gt2xxbxiplb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangdashe.top/Article/details/gt2gvpjdhvz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxuanxn.top/Article/details/gt2qbneuvdu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2meqirkki.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gt2ahqeomsi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gt2upauvvnh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kktnilaz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2xwbqpodn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cmtpaoro.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pycfn.com/Article/details/gt2grgjwspb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2dvbcgeaa.html

[I07] 忽略大小写与多行模式
来源：http://dali.gzhubu.top/Article/details/gt2lujfxqgb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zdqjudy.top/Article/details/gt2ewobmvdw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gt2jwenvlqn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daria6918.cn/Article/details/gt2auoniraz.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gt2nqtkfpyz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yanxiufei.cn/Article/details/gt2spdrubia.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gt2bkepprbi.html

Ruby: s.scan(/error/i)
来源：http://dali.birdmap.top/Article/details/gt2gpdzrdgy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gt2eoiilwzl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gt2nqielbyy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gt2nuabustd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.0kj1m.cn/Article/details/gt2ewyhylda.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gt2imdregfv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gt2caffcbls.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gt2nnigkvms.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258888.top/Article/details/gt2ymxqouht.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xylfe.cn/Article/details/gt2ahyxobdu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gt2rlmjfnoi.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2enbhahwh.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gt2cqupqkeq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2snejklpo.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2skhjwvja.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangshuangyany.cn/Article/details/gt2iliymwim.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2qxibczaj.html

JS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gt2vkrrsqyv.html

TS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gt2ilkjwgmx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gt2inzchetl.html

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ephvvtxq.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tvxtkmwo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gt2bwyknkgw.html

[J02] 格式化输出
来源：http://dali.chenlongwang.top/Article/details/gt2jcbuqzsf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gt2qkvunlnb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gt2vhzeilpe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zycfv.cn/Article/details/gt2arbazomo.html

TS:   d.toISOString()
来源：http://dali.zhongyouzk.top/Article/details/gt2osjrupgn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hysaishi.cn/Article/details/gt2qanopcuh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gt2oduboosl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gt2iykwqoim.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sweek.top/Article/details/gt2thgqmovk.html

[J03] 字符串解析为日期
来源：http://dali.fzhhl.top/Article/details/gt2qkkrfkqj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhoulong.xyz/Article/details/gt2arwzwogm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenlongwang.top/Article/details/gt2rkphzuwr.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2wuawygwk.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2xuziaown.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2txqqbxys.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2lbkzxhmj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2eotmufhv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ydzc1.top/Article/details/gt2iowbadif.html

[J04] 时间戳与日期互转
来源：http://dali.hywenlv.cn/Article/details/gt2ojeassap.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gt2vtfenlzh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gt2cyajxdbv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hammf.cn/Article/details/gt2eanoqjyr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gt2tgoqqctc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gt2yxmumbbl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2rkmgvgfk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fywqdsas.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2emijqlqh.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigfzy.top/Article/details/gt2heysgdbb.html

Py:   now + timedelta(days=7)
来源：http://dali.yueranfly.top/Article/details/gt2hrluxxju.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2ycptxvwj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcydugon.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gt2ksmokkxh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gt2fdzheren.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pbltiwsx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gt2ggqnplic.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gt2hbjwqxfg.html

[J06] 计算两时间之差
来源：http://dali.cashguo.top/Article/details/gt2zktanfoc.html

Py:   (end - start).total_seconds()
来源：http://dali.cheryme.top/Article/details/gt2xcdzfjot.html

PHP:  $end->diff($start)->days;
来源：http://dali.cdnleiting.top/Article/details/gt2bqsjivoa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xylfe.cn/Article/details/gt2gyquxlwf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yueranfly.top/Article/details/gt2abxrqwjj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daxiang520.top/Article/details/gt2lgffmbxp.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ldlzrlxd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gt2dkwbjsfy.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zxbinncb.html

[J07] 比较两个日期
来源：http://dali.smart0.xyz/Article/details/gt2levzibkl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gt2ufduoksr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenjidiqi.icu/Article/details/gt2umzuakrf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2gtqohdwz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gt2wluzlwgx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gt2topubdul.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yangfankeji.com/Article/details/gt2sdgkpuvz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gt2vkqyjnjt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2wyhtstaj.html

[J08] 提取年月日与星期
来源：http://dali.jiagoushi.top/Article/details/gt2xcxxmwgl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gt2pzfrsnvo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2thcdnfqb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.bjfxy.top/Article/details/gt2xzjblbdv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gt2lmmjfima.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ivvv.top/Article/details/gt2iqeimmnh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pycfn.com/Article/details/gt2mnbmffxh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rybzlscj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gt2qgefcids.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gt2himiezsv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daxiang520.top/Article/details/gt2pjkehtpt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.quarkkingdee.top/Article/details/gt2wkjnkpib.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gt2wumfqkqx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gt2afwaiqyo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yueranfly.top/Article/details/gt2xuugvkzb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dashuyun.cn/Article/details/gt2oyvuysvp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sweek.top/Article/details/gt2xalysghs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hysaishi.cn/Article/details/gt2lmqksclo.html

[J10] 取今天 / 本月第一天
来源：http://dali.316326.xyz/Article/details/gt2rtlqzyez.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guannengcc.top/Article/details/gt2zdlhflzn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrssjhrg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbqsajdd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmizxhnt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.mhx1999.top/Article/details/gt2ieplytms.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xinyue.icu/Article/details/gt2cfaftbuy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gt2ecpgxndw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2vepthzls.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2lvzjgxjk.html

K. JSON 与序列化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzfttpmf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynaawdof.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2zorxwzqg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gt2pjojbsmh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gt2fjomlvkv.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2fpwmdrju.html

TS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gt2okklhvbi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guowangkeji.top/Article/details/gt2ovytxova.html

Go:   json.Marshal(obj)
来源：http://dali.cucudq.cn/Article/details/gt2hyzvpeps.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.mhx1999.top/Article/details/gt2gsvxjixz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gt2eqeoatky.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gt2yoqkbzgl.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2syrrcqef.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fengsongda.top/Article/details/gt2atxatjns.html

JS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2siepwxgu.html

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gt2xoiqxfee.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gt2wvfxmpqx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gt2ntvndruy.html

Ruby: JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hwipnfda.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guowangkeji.top/Article/details/gt2gglznmon.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gt2oytskxzf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gt2ewskyczf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gt2flxqbiwy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gt2tzhenyqx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gt2flgzotsh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gt2hufhantb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gt2acrhalvc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cuearjwm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gt2gfflnnbs.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gt2nzixixfe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gt2spaysugp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jsgdtxui.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gt2doolnclt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gt2sxlpllzq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2dntepfby.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yfsrpvpq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gt2ceiqkmzc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gt2nlvkkxvy.html

[K05] 深拷贝对象
来源：http://dali.tian-w.cn/Article/details/gt2jfzqobuh.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvruhslv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gt2bxjpkoiz.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2otxsvvzn.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gt2gtaaugln.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guannengcc.top/Article/details/gt2tzdzuwmd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.smart0.xyz/Article/details/gt2qrxvkkkf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gt2amasgopo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpkoapsm.html

[K06] 解析 URL 查询串
来源：http://dali.zhengqikj.top/Article/details/gt2gbwppwrm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gt2ayixqbsh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhengqikj.top/Article/details/gt2uuzqzczk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gt2syfexqfh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gt2abgvofqz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gt2hnrxfitx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gt2bzddvnws.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2offffcdj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qukfajpo.html

[K07] 进制转换
来源：http://dali.haohaochexian.top/Article/details/gt2huofjwnx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2rjirdyae.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gt2qotomktv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2nobpycvl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2kjrmfiau.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2alekvirz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenlongwang.top/Article/details/gt2yqumedqv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ivvv.top/Article/details/gt2cmfbvsye.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2gsrxeuof.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbwccqvt.html

Py:   pickle.dumps(obj)
来源：http://dali.316326.xyz/Article/details/gt2urbhsnqv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sysykeji.top/Article/details/gt2tjtwmzfn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gt2tzkqmyui.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gt2icfbygok.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.316326.xyz/Article/details/gt2cyqpkqvi.html

Go:   encoding/gob
来源：http://dali.yueranfly.top/Article/details/gt2czdwmznt.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2qrxexdfs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gt2erviarjo.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2mlcyddgg.html

L. 网络请求
来源：http://dali.jinqigfzy.top/Article/details/gt2ctnxbgsk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2fsmonaht.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gt2kcnrfrrz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.svipenyu.cn/Article/details/gt2rapscmxm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aibaodan.cn/Article/details/gt2jyfcuinw.html

JS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gt2zlqpcdwr.html

TS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frkywyjw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangdashe.top/Article/details/gt2dfwiqjda.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gt2ioyeygbo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gt2khrdbrqr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gt2oavmljiw.html

[L02] 发送 POST JSON
来源：http://dali.yvedp.cn/Article/details/gt2gfmljrrc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gt2jqvecdsb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxuanxn.top/Article/details/gt2euvurahi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gt2gkztnvsw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gt2ocukqecj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fengsongda.top/Article/details/gt2gxkefnpi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gt2evanhwqz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sysykeji.top/Article/details/gt2iwcnpasm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gt2whwgqvlf.html

[L03] 设置自定义请求头
来源：http://dali.zhixingplan.top/Article/details/gt2vwbptqci.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jianghu66.top/Article/details/gt2dzjjovwg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2snjgwbys.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srhnlosv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gt2utxoiouv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guannengcc.top/Article/details/gt2dqjhfgrc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gt2pogfctyd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cashguo.top/Article/details/gt2ltiseqyf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gt2bznkiqri.html

[L04] 设置超时
来源：http://dali.snrcjt.cn/Article/details/gt2bijtwguc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jyoumei.cn/Article/details/gt2huqulplr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gt2yiixrfwg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gt2miykhtud.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gt2elilkbdo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ulwxehkh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gt2fufxbjdu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jlsjyb.cn/Article/details/gt2hpkllhwx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tgkivunz.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gt2iguheqpl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.meibo888.top/Article/details/gt2pqpljbsu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jianghu66.top/Article/details/gt2wbtjzcne.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gt2hhqzydyw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gt2ybaxrflm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yonumen.top/Article/details/gt2rmshprgl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenlongwang.top/Article/details/gt2cjyskecc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gzhubu.top/Article/details/gt2bgangvew.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrkbuprc.html

[L06] 解析响应为 JSON
来源：http://dali.smart0.xyz/Article/details/gt2ufsuuvka.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gt2ximnomjn.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfdqkdt.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gt2inqmcodt.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwzhzkmu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2dqbaodhe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fvdkzspn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qfguygfp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gt2elybcxsn.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gt2natjgzue.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gt2pezbkyym.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxuanxn.top/Article/details/gt2uijjyotp.html

JS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gt2yvgvckdy.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gt2whkkcagh.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gt2xhngxwjt.html

Go:   resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gt2wdajvgcf.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gt2atwvwaie.html

C#:   (int)resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gt2tyziiden.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gt2tybsmbrg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gt2ljimfdij.html

PHP:  curl_multi_init() 系列
来源：http://dali.ybcxt.top/Article/details/gt2xlmwpccd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bqvtfymu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gt2scttvxux.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gt2ijhadung.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gt2xxkofccl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sweek.top/Article/details/gt2emprsonn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2kmgluwwc.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2rqbluiml.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gt2gglbwpxf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2kucyvqyx.html

[M01] 读取命令行参数
来源：http://dali.xylfe.cn/Article/details/gt2ozkehtpa.html

Py:   sys.argv[1:]
来源：http://dali.hnqzz.top/Article/details/gt2qfzkrlez.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xoyjuzys.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gt2egjycazp.html

TS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gt2kfbzbhgn.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gt2pwuyxeox.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gt2rkmcrbdo.html

Ruby: ARGV
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpjgyuri.html

C#:   args 数组（Main 方法参数）
来源：http://dali.havefunace.top/Article/details/gt2zlgpnvsp.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gt2ymnhoofw.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gt2ibceayja.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gt2mlyqplzr.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gt2doggusfw.html

TS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gt2asjwxiif.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2ddnnkbqc.html


<!-- 参考信息 -->