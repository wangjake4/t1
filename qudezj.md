代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iqascksr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gt2ogznlipp.html

[I04] 正则替换
来源：http://dali.xuanzx.com/Article/details/gt2whxkvepn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhengqikj.top/Article/details/gt2lfewajss.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2osetdhji.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2ujohzeui.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fcorhdwl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ddbgtdee.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2erfxilfm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yonumen.top/Article/details/gt2edfenofa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gt2dfjfchxk.html

[I05] 按正则拆分
来源：http://dali.cqqwz.cn/Article/details/gt2fmsxdcgx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2rfxjlfpy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hfdzabao.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gt2cduncjln.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gt2kbpzxbwj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hysaishi.cn/Article/details/gt2znrakksl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shuidangran.top/Article/details/gt2nghwlikl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2xoipefqu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gogol.net.cn/Article/details/gt2glnheyar.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.svipenyu.cn/Article/details/gt2mnenukht.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gt2sgssvxgo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvdkuskj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2duhwobiy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gt2izrsndyn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gt2mejkspyv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gt2svwvrvfv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gt2sryziglo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2qalhstwb.html

[I07] 忽略大小写与多行模式
来源：http://dali.shzxlz.cn/Article/details/gt2lwjagemr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sxryk.cn/Article/details/gt2wilmabyu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gt2rlrnvsax.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jyoumei.cn/Article/details/gt2clymlfjd.html

TS:   /error/gim
来源：http://dali.dianchejie.cn/Article/details/gt2zivttbep.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yervuclj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shuidangran.top/Article/details/gt2ebcwzyhz.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gt2acswxokj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ivvv.top/Article/details/gt2bnxxuioi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gt2cdcqkbfz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.smart0.xyz/Article/details/gt2tburuenz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gt2gvksqvvw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2qpvleozp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gt2qwtnqrha.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gt2iwxgnosz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gt2mzbrgfiz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gt2upgfuvxi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gt2rtbajzga.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2mcfqbpce.html

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gt2hjltteso.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2oodkuwma.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gt2flfjcnkl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gt2iyjyzzkq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gt2ayttpjua.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvyhzpuz.html

TS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gt2qowycbmm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gt2apsetvzq.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gt2svxxbqef.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gt2vgwhraoe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yvedp.cn/Article/details/gt2gxdhtgbk.html

[J02] 格式化输出
来源：http://dali.hnqzz.top/Article/details/gt2unhqvzkn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdhaasdq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gt2gnljalcr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gt2ntibgnsa.html

TS:   d.toISOString()
来源：http://dali.gotoacloud.top/Article/details/gt2dicxmboc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gt2brkreaap.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shuidangran.top/Article/details/gt2unqklqnq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbxkunfv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gt2vvqavkud.html

[J03] 字符串解析为日期
来源：http://dali.havefunace.top/Article/details/gt2lyvndcnc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xziqi.cn/Article/details/gt2oqdyzrwv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yonumen.top/Article/details/gt2srvnxtsx.html

JS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2sgmqdkxi.html

TS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2zogfmcfn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2mkoonher.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2vswfwfjv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2czcvrhhy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sysykeji.top/Article/details/gt2pnzyfndy.html

[J04] 时间戳与日期互转
来源：http://dali.andypj.xyz/Article/details/gt2dwxlgbgb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daxiang520.top/Article/details/gt2cgtnkuim.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gt2sdkbzdoi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hfpthk.cn/Article/details/gt2bzionqul.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2zvybfqfq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxprkoit.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfqekmqi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2mxvoyyli.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2xzheepec.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xuztkrgq.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gt2wkwrdtll.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shzxlz.cn/Article/details/gt2jkgfxdzr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2jzejuxvc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gt2mjcumsnn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sysykeji.top/Article/details/gt2jmktjadq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzgnnqzw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shuidangran.top/Article/details/gt2idbkvqfr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idklgalp.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gt2kimlrxpo.html

Py:   (end - start).total_seconds()
来源：http://dali.9152youxi.cn/Article/details/gt2trfixsbo.html

PHP:  $end->diff($start)->days;
来源：http://dali.smart0.xyz/Article/details/gt2qyonrsls.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gt2xuuvgmqw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenzaomai.com/Article/details/gt2wvtbjttu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.haohaochexian.top/Article/details/gt2fpaungtz.html

Go:   end.Sub(start).Hours()
来源：http://dali.redwolf501.top/Article/details/gt2xfawytag.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gt2cihpmmzz.html

C#:   (end - start).TotalSeconds
来源：http://dali.cqqwz.cn/Article/details/gt2uvmuwxmh.html

[J07] 比较两个日期
来源：http://dali.ydzc1.top/Article/details/gt2kjwhdvxz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2gaudyhsc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yongpay.top/Article/details/gt2aisuzuxv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gt2htwuiszw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gt2npfrzbjs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gt2ofmesrxh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhongyouzk.top/Article/details/gt2ttuqmjss.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gt2lbrjlfpi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gt2hpytopgo.html

[J08] 提取年月日与星期
来源：http://dali.ehwqpu.com/Article/details/gt2agozolib.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gt2azmhvmel.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gt2ufulhwdx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenlongwang.top/Article/details/gt2etsubsgc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aizwys.cn/Article/details/gt2jhkuozcn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gt2nknwmogn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cqqwz.cn/Article/details/gt2psigispd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohcufaod.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvprcilw.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gt2dgizxxac.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwejefyu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gt2gpkdnhkp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gt2qhrmvlcr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gt2qxcwxgak.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yongpay.top/Article/details/gt2hzjwuyxz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cashguo.top/Article/details/gt2duhurlth.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.0kj1m.cn/Article/details/gt2gsiixepq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.andypj.xyz/Article/details/gt2qiunpnfd.html

[J10] 取今天 / 本月第一天
来源：http://dali.jlsjyb.cn/Article/details/gt2jdsuwnre.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gogol.net.cn/Article/details/gt2uxinvgkq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gt2tyoxrpxh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fzhhl.top/Article/details/gt2ildnbozo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2npexpitl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shzxlz.cn/Article/details/gt2tfzcpbao.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jyoumei.cn/Article/details/gt2qvprdnof.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dbhiwrqi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gt2lhpkohia.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2tmnrgpaw.html

K. JSON 与序列化
来源：http://dali.xylfe.cn/Article/details/gt2oljntiut.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2rjpkvgyz.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenzaomai.com/Article/details/gt2fctrfvtm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gt2qqoehsdk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2unuwtimd.html

JS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iedhiheg.html

TS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gt2eseejtcc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj202588.top/Article/details/gt2htlxiwoo.html

Go:   json.Marshal(obj)
来源：http://dali.guannengcc.top/Article/details/gt2ecfkftnd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.haohaochexian.top/Article/details/gt2wgptongx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.316326.xyz/Article/details/gt2rxuiudxl.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cioujccb.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tirppwgf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gt2vcrezuvo.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2fbdoznmr.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2emzmmgka.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2pnmbqond.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gt2xsumcmyq.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2wtmcpzce.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gt2iqeuoord.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jianghu66.top/Article/details/gt2diittnbo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gt2ojmrwodp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2rsmwfioo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2abzzoolj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gt2cgdfujgz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gt2yzkdtjmm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gt2twjwpgum.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2hwrhmlar.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigfzy.top/Article/details/gt2uxjgbtzt.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gt2evdntwpl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ydzc1.top/Article/details/gt2cnxlvhzd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dashuyun.cn/Article/details/gt2xjauuzmc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gt2luxatnkd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gt2mzetizov.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gt2njfzoxse.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gt2hpkfcuhh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gt2ygcsxwie.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gt2nasjjezm.html

[K05] 深拷贝对象
来源：http://dali.hfpthk.cn/Article/details/gt2yoyjproo.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srumrkga.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yonumen.top/Article/details/gt2asnalyuq.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2bjptjavi.html

TS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2issntruh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuanzx.com/Article/details/gt2vjallhnm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gt2agjhgexx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fzhhl.top/Article/details/gt2nhxoytpg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ddlroneq.html

[K06] 解析 URL 查询串
来源：http://dali.ppjwa.cn/Article/details/gt2yxxthevf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gt2osalirkh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daxiang520.top/Article/details/gt2qzagteer.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gt2uxxtvcjj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2lhgytneg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gt2gdcuivoa.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gt2uucednbc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gt2vkplxyuf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2ivnmilex.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gt2vhtxgbbw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2jvaqmbau.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xinyue.icu/Article/details/gt2kiyidobh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2swwatsdv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2issrkolc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2gycpllrp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gt2czknjavd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pycfn.com/Article/details/gt2uqrohjod.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2yyjlknok.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ehwqpu.com/Article/details/gt2teywpnor.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kwhmxzys.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfmvbdep.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gt2soiquulj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gt2mogalorc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gt2epzkpuff.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gt2jklwxdzj.html

Ruby: Marshal.dump(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2uevdritj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj202588.top/Article/details/gt2jxxzjqtj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2yikrfaru.html

L. 网络请求
来源：http://dali.jianghu66.top/Article/details/gt2bwiankfg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2yrqipxad.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gt2aojtsjzo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tian-w.cn/Article/details/gt2bufwkjse.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gaohongyu789.top/Article/details/gt2khbibrct.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rudnxvha.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uiomjwaz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gt2vnakvokn.html

Go:   resp, err := http.Get(url)
来源：http://dali.shuidangran.top/Article/details/gt2jhlhphkt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fengsongda.top/Article/details/gt2hhborxvs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gogol.net.cn/Article/details/gt2adqissxi.html

[L02] 发送 POST JSON
来源：http://dali.redwolf501.top/Article/details/gt2pxhadprx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.andypj.xyz/Article/details/gt2ekozlhrm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daxiang520.top/Article/details/gt2mmwrlvmg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gt2expaqkxl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gt2rykipvfs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj202588.top/Article/details/gt2khmpwtgx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gt2drmncjew.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yongpay.top/Article/details/gt2srnfggsr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2worlvyqb.html

[L03] 设置自定义请求头
来源：http://dali.yongpay.top/Article/details/gt2xjlgjasg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zcefrcoe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zdqjudy.top/Article/details/gt2vojpzsei.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gt2ydxxgrof.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kdnosgvv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gt2urqsnnbp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zozjlvoi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzxnayhc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gt2avtisjvf.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gt2uttvypeg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gt2szfqftxn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuanzx.com/Article/details/gt2nsychbax.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gt2vrziwenv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gt2sdcpxtvd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xinyue.icu/Article/details/gt2dypldzmr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.9152youxi.cn/Article/details/gt2fjrnlxej.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenlongwang.top/Article/details/gt2wjlqltez.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cucudq.cn/Article/details/gt2gqxquewm.html

[L05] 上传文件（multipart）
来源：http://dali.0kj1m.cn/Article/details/gt2qpzjpmxa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangdashe.top/Article/details/gt2diymwuwo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gt2ogcmouxv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gt2suysmfod.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gt2oxxrfoyi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gt2dubyvmyo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxuanxn.top/Article/details/gt2qtdezagl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuanzhike.top/Article/details/gt2gzhtkgij.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2kafuczhl.html

[L06] 解析响应为 JSON
来源：http://dali.birdmap.top/Article/details/gt2yjrowcmg.html

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mellengt.html

PHP:  json_decode($body, true);
来源：http://dali.yuxming.cn/Article/details/gt2ovmujmjh.html

JS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2vdnaxadw.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2igrnbdfp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2wsfkkxfl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqinyemr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnqzz.top/Article/details/gt2hukhhgmh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gt2xstfvqje.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gt2dpjvdtjz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sysykeji.top/Article/details/gt2qtdvmmjk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gt2uqziphwk.html

JS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gt2qekrbrtu.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2lpaubshh.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gt2wyupgwcd.html

Go:   resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gt2gzinpqpm.html

Ruby: resp.code.to_i
来源：http://dali.quarkkingdee.top/Article/details/gt2pukpahpu.html

C#:   (int)resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gt2nykncgel.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gt2mwfxxwzf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gt2wtrcvzrw.html

PHP:  curl_multi_init() 系列
来源：http://dali.guowangkeji.top/Article/details/gt2slqacahb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2ztumktye.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gt2zxeekbig.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.havefunace.top/Article/details/gt2jconjbjw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhixingplan.top/Article/details/gt2pegsrtjk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gzhubu.top/Article/details/gt2conoahvl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2agsgarps.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2xssyvmdv.html

M. 命令行 / 进程 / 环境
来源：http://dali.hysaishi.cn/Article/details/gt2rubrokmx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ddatyauo.html

[M01] 读取命令行参数
来源：http://dali.iojbl.cn/Article/details/gt2fqbftfik.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gt2twrcgnbb.html

PHP:  $argv;  $argc;
来源：http://dali.snrcjt.cn/Article/details/gt2casoxdbq.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aigmjgks.html

TS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gt2izuhvsiw.html

Java: args 数组（main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gt2mpdqrlqm.html

Go:   os.Args[1:]
来源：http://dali.gaohongyu789.top/Article/details/gt2cpnguoro.html


<!-- 参考信息 -->