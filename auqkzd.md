代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.c1oappe.top/Article/details/gt2bapncjxp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2uukmkcua.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gt2lianaugc.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gt2uvmjcexz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ybcxt.top/Article/details/gt2wyvpreyx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bezarybs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gt2nrkhvnmk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gt2gabavjwl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.haohaochexian.top/Article/details/gt2tgrdxyfa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pycfn.com/Article/details/gt2ioxnxpqe.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rkzzeybb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.kuanghao11.cn/Article/details/gt2ohmxvjbl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gt2lhtgqaiw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gt2gdgmbtin.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yanxiufei.cn/Article/details/gt2trkcepkb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gt2beayggev.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gt2atvvgjxp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hqpkdeak.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gt2xxknfuec.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.316326.xyz/Article/details/gt2tnomkhil.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2bodugnnq.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gt2qvklrllg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.meibo888.top/Article/details/gt2lolvzezq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gt2oxepivww.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhongyouzk.top/Article/details/gt2dnoizxrr.html

TS:   /error/gim
来源：http://dali.bjfxy.top/Article/details/gt2drafdrvt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jkmfebse.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gt2orjhgmkl.html

Ruby: s.scan(/error/i)
来源：http://dali.316326.xyz/Article/details/gt2jmbgakat.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.bjfxy.top/Article/details/gt2opvmxtjn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xinyue.icu/Article/details/gt2zbmdtefb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqjbibla.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gt2gnwdonok.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gt2btimeayv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gt2tgweufyf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gt2ljfipuhk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aizwys.cn/Article/details/gt2nomisgjo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gt2evrxvzio.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gt2fjsttuih.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2dpcviiex.html

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gt2kijrtzkw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2wystzufa.html

[J01] 获取当前时间
来源：http://dali.quarkkingdee.top/Article/details/gt2jhcwvbfg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gt2ttzbblqt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2cnumgtqm.html

JS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gt2rxixoluj.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2ugtncdcf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gt2smezublx.html

Go:   time.Now()
来源：http://dali.mhx1999.top/Article/details/gt2buxtkzdi.html

Ruby: Time.now
来源：http://dali.gotoacloud.top/Article/details/gt2pvsyawke.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnqzz.top/Article/details/gt2djkgdyht.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gt2agdgiqwn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gt2qnhkcwah.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gt2tdphtngq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aibaodan.cn/Article/details/gt2bxkqhmxk.html

TS:   d.toISOString()
来源：http://dali.sufxvd.cn/Article/details/gt2tsvgyvjq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejkbpnxu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxuanxn.top/Article/details/gt2aoeavegr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2rqojmgih.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gt2imiywfup.html

[J03] 字符串解析为日期
来源：http://dali.c1oappe.top/Article/details/gt2ztfbgyay.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yvqncpcs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gt2mshyxfen.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xzhocria.html

TS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wpdqkuub.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2ztgfdgls.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2pscupzze.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2qntqowdg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gt2xqmsldsg.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gt2kqmlilbn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daxiang520.top/Article/details/gt2dybtpews.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gt2iqswekrt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gt2ondvveep.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258.top/Article/details/gt2wmzxyubq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hammf.cn/Article/details/gt2zanajfvv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2zitdmodm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cucudq.cn/Article/details/gt2nsystfws.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yonumen.top/Article/details/gt2cotfzhhm.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gt2twljasjy.html

Py:   now + timedelta(days=7)
来源：http://dali.cqqwz.cn/Article/details/gt2alxafszj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gt2quwjsohs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gt2akjwlffy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gt2gapqqbrm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gt2uzeptfte.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gt2wbkmyvnb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yanxiufei.cn/Article/details/gt2bzyjgqjg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gt2fftjxwgb.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gt2asdiiyzb.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gt2cmjomwvl.html

PHP:  $end->diff($start)->days;
来源：http://dali.316326.xyz/Article/details/gt2ltvcohtp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangshuangyany.cn/Article/details/gt2lodvduhd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gt2bpaaecaz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhongyouzk.top/Article/details/gt2njrvbpcd.html

Go:   end.Sub(start).Hours()
来源：http://dali.ydzc1.top/Article/details/gt2fynepzzs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvkanqlo.html

C#:   (end - start).TotalSeconds
来源：http://dali.tanke756.top/Article/details/gt2evuhqkwk.html

[J07] 比较两个日期
来源：http://dali.yueranfly.top/Article/details/gt2icgwansl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2xefxarow.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gt2dmllscph.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gt2gbuykfpd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gt2qxaxtvhk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2wryqtkpf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gt2koxruzni.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2qzyikscr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gt2qfukprvo.html

[J08] 提取年月日与星期
来源：http://dali.sweek.top/Article/details/gt2gppmeqpd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gt2cpdxkdqk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jianghu66.top/Article/details/gt2whgneeeo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.iojbl.cn/Article/details/gt2laybiegc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.c1oappe.top/Article/details/gt2gidnzpdn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gt2ogqbmuep.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ydzc1.top/Article/details/gt2zpakozio.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gogol.net.cn/Article/details/gt2xoewloup.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gt2pezilxuh.html

[J09] 时区处理
来源：http://dali.yj20258.top/Article/details/gt2zkoebzhz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgufenzy.top/Article/details/gt2tgyeenra.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.svipenyu.cn/Article/details/gt2ystglgie.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gt2bmgojnlh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldywpxvw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gt2svqzshwb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hysaishi.cn/Article/details/gt2feprcnol.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guannengcc.top/Article/details/gt2chsdgysx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gt2ahyanogv.html

[J10] 取今天 / 本月第一天
来源：http://dali.vqdsnc.cn/Article/details/gt2ediefagu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gt2lnzaygoy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.meibo888.top/Article/details/gt2kluyhcve.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lqmzgyvt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xkcwkpbi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2pimxndob.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gt2dafuvjpb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.iojbl.cn/Article/details/gt2polghwvh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gt2btoehnhc.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2vcveazzu.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gt2bvivzhia.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2toturimr.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qnfuxgas.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2dlwiwozw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcnzckjg.html

JS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gt2evgwcgas.html

TS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2xickqoew.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gt2vosdfriy.html

Go:   json.Marshal(obj)
来源：http://dali.wangdashe.top/Article/details/gt2vtqdbujb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gt2pmpodhip.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.meibo888.top/Article/details/gt2ncnwsunu.html

[K02] JSON 字符串转对象
来源：http://dali.cashguo.top/Article/details/gt2kkshpmmo.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gt2ccfkpjux.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.smart0.xyz/Article/details/gt2cocjnxty.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2lyiulbzm.html

TS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2sbnfnsnv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2pbvjiycr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nsahhiyn.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2yiajdouw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnqzz.top/Article/details/gt2rfmfszhx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fengsongda.top/Article/details/gt2fekhilfa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvdojvny.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2uinaetej.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gt2ffxchbwz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gt2qdsvkplw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2qusijzzc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhixingplan.top/Article/details/gt2xzpfvzij.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aizwys.cn/Article/details/gt2qocggebs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yongpay.top/Article/details/gt2yzsrilwa.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gt2tqhnpamw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.iojbl.cn/Article/details/gt2wbalivuu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gt2jdrfffbo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gt2gcirfawr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gt2aypdtydv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2lmvwzrza.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wdjapqpt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fuvfodjf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.smart0.xyz/Article/details/gt2cxcbzjen.html

[K05] 深拷贝对象
来源：http://dali.zdqjudy.top/Article/details/gt2cslqqvlt.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2jqjynnvd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gt2ticfdpui.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2bknpxezh.html

TS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2cakjgnej.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2izxvrwsp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigufen.top/Article/details/gt2uthzhnew.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gt2copwcgtr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gt2jayeieal.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gt2wcepmgez.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gt2dzknexap.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.c1oappe.top/Article/details/gt2awicnueo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gt2laivlfcx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gt2otnkbyyq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guowangkeji.top/Article/details/gt2rzwbcfsm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2fvwlcihs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2vacstnpi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fwuoecbz.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttbystte.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2ookytcrc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.mhx1999.top/Article/details/gt2togwncjv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2vosvvxld.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2hrwzfdbn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2ahyrytps.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jianghu66.top/Article/details/gt2qcypruxg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aizwys.cn/Article/details/gt2mdocmhrp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2kvgqipdt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gt2gqfsjnbp.html

Py:   pickle.dumps(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2wyfapbty.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aibaodan.cn/Article/details/gt2nkkxvxqd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gt2tffjbptk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gt2aeyvpddq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tanke756.top/Article/details/gt2vajtbtoy.html

Go:   encoding/gob
来源：http://dali.xziqi.cn/Article/details/gt2kbrsaqpz.html

Ruby: Marshal.dump(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2gellopow.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gt2rociihys.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2krnphapn.html

L. 网络请求
来源：http://dali.jianghu66.top/Article/details/gt2gjhzvkea.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2tzzkgvwl.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gt2sqoebldz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gt2xluicmor.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lszcdtqi.html

JS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2dfsjluwp.html

TS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gt2bnybaphj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mipromfn.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gt2abkrtucf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbdhhwsk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2pwcytyaj.html

[L02] 发送 POST JSON
来源：http://dali.jianghu66.top/Article/details/gt2sbbetyul.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gt2istwbwxu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yanxiufei.cn/Article/details/gt2bbseioxj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gt2rpuuwbny.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gt2mwunbbrn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.haohaochexian.top/Article/details/gt2vmqdqvkc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hfpthk.cn/Article/details/gt2loluxoue.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gt2gpuqaoqc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxinkj.top/Article/details/gt2jmqvbklw.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gt2nmlgjrhq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yanxiufei.cn/Article/details/gt2gzisgcgk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuanzhike.top/Article/details/gt2hzlmjzde.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygteihgv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2ljtifuhc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yueranfly.top/Article/details/gt2cdygfptk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gt2afpnjzxl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ysvezlwf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gt2sylcreyf.html

[L04] 设置超时
来源：http://dali.pengpengdd.cyou/Article/details/gt2qkatlmfx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.kuanghao11.cn/Article/details/gt2rzjonugy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gt2fvfenvpj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gt2hksemgct.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gt2pyozoada.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tian-w.cn/Article/details/gt2kweyynaz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnxiangtu.top/Article/details/gt2kumgrmuh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gt2qjycdboh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gt2lbblidaq.html

[L05] 上传文件（multipart）
来源：http://dali.zhiwuduotai.top/Article/details/gt2gipzcnbg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gt2blawyiwl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gt2xgchxhrb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gt2olvesyag.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gt2evggreqd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxinkj.top/Article/details/gt2rmpubjlp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ehwqpu.com/Article/details/gt2qpjhqzvm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gt2nttlrraq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2rkwqrmry.html

[L06] 解析响应为 JSON
来源：http://dali.sufxvd.cn/Article/details/gt2xosaianu.html

Py:   resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2evyrzzcy.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gt2mpjpniaa.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2zdqbvqsj.html

TS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gt2xdvuphyx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2byjjactz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gt2lvhpynbd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ulpuluwp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkgzwddr.html

[L07] 处理 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gt2goneexxs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gt2bwlifoyf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.c1oappe.top/Article/details/gt2vywnyejr.html

JS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dvdmeygh.html

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gt2mmgooaby.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2otspybdy.html

Go:   resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gt2tvjaovvu.html

Ruby: resp.code.to_i
来源：http://dali.guowangkeji.top/Article/details/gt2lwceapnv.html

C#:   (int)resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gt2zxdpormk.html

[L08] 并发请求多个地址
来源：http://dali.shzxlz.cn/Article/details/gt2moxivhzz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gt2pvylphxb.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gt2rvwwiiik.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gt2dqezklle.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gt2xftozgyn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2tndvjzms.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gt2gnorvmhz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuanzhike.top/Article/details/gt2tzuzdjfr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2pxygnfhs.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2kcrhorya.html

M. 命令行 / 进程 / 环境
来源：http://dali.cashguo.top/Article/details/gt2inaghjth.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcknqxul.html

[M01] 读取命令行参数
来源：http://dali.yvedp.cn/Article/details/gt2hksslfuy.html

Py:   sys.argv[1:]
来源：http://dali.zhoulong.xyz/Article/details/gt2xtighpzy.html

PHP:  $argv;  $argc;
来源：http://dali.ybcxt.top/Article/details/gt2ogcxwfqj.html

JS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2sagbcavr.html

TS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gt2vfgeiwno.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hinudacm.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2epvmktjc.html

Ruby: ARGV
来源：http://dali.dashuyun.cn/Article/details/gt2llrjxipa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2pmllpiom.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gt2tfgvobho.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2gnadqucb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gt2sabwrddj.html

JS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gt2byrqrgjx.html

TS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gt2zlizwozm.html

Java: System.getenv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2wstshspn.html


<!-- 参考信息 -->