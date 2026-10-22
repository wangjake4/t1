代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wuerojfa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jyoumei.cn/Article/details/gt2qsqjrhxt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sweek.top/Article/details/gt2yyyzmbog.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gt2bubjvdso.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gt2jtstphhs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gt2cutfgues.html

[I04] 正则替换
来源：http://dali.fengsongda.top/Article/details/gt2qcdioobs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubqvnnws.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2blaftale.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2rvlojull.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gt2wrqddcys.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nuhjfmer.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbyafkci.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2butodmnj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gt2raaatirv.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gt2tulntyjc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgfzy.top/Article/details/gt2tvcflugn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2kzqpbsjp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2twlnzlnl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gt2cqlxwlqb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gt2hibcmywj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gt2uznntfhh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gt2iybbvlyt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sxryk.cn/Article/details/gt2yadcklss.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnqzz.top/Article/details/gt2kxwxisxz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gt2jzbramxe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ppjwa.cn/Article/details/gt2mnyrpdud.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gt2bltnbwet.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gt2rhuemplf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2yeiwoxyr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gt2zuecfwtu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuanzx.com/Article/details/gt2jgxdakvt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gt2kgtcgfrk.html

[I07] 忽略大小写与多行模式
来源：http://dali.shuidangran.top/Article/details/gt2btpvehnx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shuidangran.top/Article/details/gt2ralszsph.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gt2yggxgaat.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jlsjyb.cn/Article/details/gt2uqzkuzrz.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gt2ozfbxlqb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ppjwa.cn/Article/details/gt2xrvtljwy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xahucxee.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gt2wdcapfll.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zrtxzkcc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2sfxhbblc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gt2coagalsn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gt2feduowwd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gt2ozysougf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbgoetst.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gt2gksvamqh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gt2oipxioxe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cheryme.top/Article/details/gt2fgsdcdst.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2ogkxeuqz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2dmhgczan.html

J. 日期与时间
来源：http://dali.zdqjudy.top/Article/details/gt2oirsfqem.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2esxrlour.html

[J01] 获取当前时间
来源：http://dali.jqgufenzy.top/Article/details/gt2onanvoii.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zycfv.cn/Article/details/gt2nyjcjacx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgpmxhxh.html

JS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gt2ejjcprgy.html

TS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gt2uslbmswe.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gzhubu.top/Article/details/gt2obprmgmc.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gt2qkwfaejv.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gt2boioyjio.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.316326.xyz/Article/details/gt2fssjpoou.html

[J02] 格式化输出
来源：http://dali.zdqjudy.top/Article/details/gt2irhupocn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gt2yjkpeghn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gt2fksuwmik.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gt2dppsvwxt.html

TS:   d.toISOString()
来源：http://dali.jinqigufen.top/Article/details/gt2ehujeltk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj202588.top/Article/details/gt2fbjhzcjs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sxryk.cn/Article/details/gt2hgnfykvk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imcptnth.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gt2oikzxbds.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gt2hqlcdtox.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenlongwang.top/Article/details/gt2ovmbiaec.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.c1oappe.top/Article/details/gt2iycxoabu.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2cwwcmsyf.html

TS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2bxjeuyzg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulfleeyv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2ibookotq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2zqncpojx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258888.top/Article/details/gt2rqeutobk.html

[J04] 时间戳与日期互转
来源：http://dali.havefunace.top/Article/details/gt2rwopmjmz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2dshfxyfx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gt2uzmzcgtf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyxurng.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gt2oxxkbtuv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2tebbhwhu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2mcaogwpa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yvedp.cn/Article/details/gt2agtvsqnx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nwbrower.top/Article/details/gt2nikuhipb.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gt2jzsvidpi.html

Py:   now + timedelta(days=7)
来源：http://dali.chenlongwang.top/Article/details/gt2ndrhgrbf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gt2dacpjhgy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gt2vsgrtkea.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gt2dwkwnacp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gt2gbkbnjdk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kthnrxgt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pchqblmn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gt2dulqhhdd.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gt2jrfjdhcl.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gt2hkruldrd.html

PHP:  $end->diff($start)->days;
来源：http://dali.hongshengwenyu.top/Article/details/gt2eslzaowf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gt2jagrwxhf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gt2heedbytx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fzhhl.top/Article/details/gt2okhmrlot.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gt2cbwidegl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhoulong.xyz/Article/details/gt2ullqmvkp.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gt2bwmcmqzj.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gt2hbxbeazx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gt2rkuiictr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhixingplan.top/Article/details/gt2xpnmsizg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gt2wughaoti.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gt2rtggnrsw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gt2rdcykuif.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gt2outdxvzc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gt2yprhxzoc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2kykwmfnz.html

[J08] 提取年月日与星期
来源：http://dali.nanxuanxn.top/Article/details/gt2qnrzxzao.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sufxvd.cn/Article/details/gt2lujhmvhh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cashguo.top/Article/details/gt2ikxutgaj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tanke756.top/Article/details/gt2ebhjaejf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kpploshl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgufenzy.top/Article/details/gt2gugbdbih.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yueranfly.top/Article/details/gt2uvczleqn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigufen.top/Article/details/gt2soylkfhw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gt2lndivjlq.html

[J09] 时区处理
来源：http://dali.tian-w.cn/Article/details/gt2astrkpcq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gt2dbxgdjhg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.bjfxy.top/Article/details/gt2jbzpcnwo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gt2gjsofpzp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gt2koulihlf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gt2ovrvpcie.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yueranfly.top/Article/details/gt2pwnxonnv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258888.top/Article/details/gt2evpdaptq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkknmwid.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gt2feoeqjyk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.smart0.xyz/Article/details/gt2vwniwsce.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.meibo888.top/Article/details/gt2szbbfriy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xinyue.icu/Article/details/gt2lxkuzmwb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2relojlqg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2ucoomgyi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ivvv.top/Article/details/gt2ctdhtlgi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenzaomai.com/Article/details/gt2xevfggav.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2ipusfhwp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2dapmvdso.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gt2zeesouui.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2alhdiioc.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2bnuwjybe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gt2rvpskhoc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gt2cpypthww.html

JS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gt2ecjnmyqz.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gt2jtdbelfz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gt2uesgmlic.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2xuhyzigi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gt2fqllnagj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yongpay.top/Article/details/gt2sfulotnc.html

[K02] JSON 字符串转对象
来源：http://dali.yuanzhike.top/Article/details/gt2dixuurxt.html

Py:   json.loads(s)
来源：http://dali.yvedp.cn/Article/details/gt2ctkhuyno.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2prxibiab.html

JS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2qwuqkyyx.html

TS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2hdilyjtd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2qzhmfgto.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gt2tmisflmo.html

Ruby: JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2gjxvfneq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gt2igyggitw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fzhhl.top/Article/details/gt2xxgggide.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2ywnmagao.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ozfedruq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2sxmcrcuz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2gjekvrqb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gt2lpkfhvdb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gt2wvkyrswc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2qtqbkvxb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.meibo888.top/Article/details/gt2mucrnymw.html

[K04] 读取 JSON 文件
来源：http://dali.iojbl.cn/Article/details/gt2nwyyxupz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqlldwiq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guowangkeji.top/Article/details/gt2pyzsybut.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdpxbsk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gt2qtslntqf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gt2hskmbzfw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gt2rnrtbuat.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnqzz.top/Article/details/gt2rznhebwn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gt2ewjjphna.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gt2ivfxywkg.html

Py:   copy.deepcopy(obj)
来源：http://dali.xinyue.icu/Article/details/gt2cctwutym.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjgfoykv.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gt2hetwsumo.html

TS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2ieftppvr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.snrcjt.cn/Article/details/gt2afbfnehl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhixingplan.top/Article/details/gt2xvkjctpo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sysykeji.top/Article/details/gt2wovzvirg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenzaomai.com/Article/details/gt2ufddhuhz.html

[K06] 解析 URL 查询串
来源：http://dali.svipenyu.cn/Article/details/gt2udwxknrv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gt2oxtsuwpr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cheryme.top/Article/details/gt2qsggkfev.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gt2hhffcanb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jplygweu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gt2zwyzzfcg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2lrsjyxgt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2aoraljoc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gt2frscilnq.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gt2sfoeguzz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jisteaoa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daxiang520.top/Article/details/gt2ibyqvkbs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2ujpqdvkt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2auvejvyj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2jwflhniq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gt2rlvufdvz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gt2kgbbwpth.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2wonwmgrb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gt2mukxgfhe.html

Py:   pickle.dumps(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2bnjutwya.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.smart0.xyz/Article/details/gt2cktyuadz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gt2lopuwrcq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gt2xycvqfvj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tian-w.cn/Article/details/gt2edlngegq.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gt2vuaouaki.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2npvlmxur.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gt2ceghdkqg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2jzaifagi.html

L. 网络请求
来源：http://dali.guowangkeji.top/Article/details/gt2upgjcujh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2wxwhukaw.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gt2egcmcoqb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gt2yhafbxup.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yanxiufei.cn/Article/details/gt2mqloqlvz.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2ljuajgbt.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gt2yxpacxrx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gt2rvmbyfpm.html

Go:   resp, err := http.Get(url)
来源：http://dali.316326.xyz/Article/details/gt2lrobhngz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ydzc1.top/Article/details/gt2kurtocmo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuxming.cn/Article/details/gt2qcnxlaqz.html

[L02] 发送 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2kgtltxdz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aizwys.cn/Article/details/gt2mxtxtzte.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gt2jmpukklo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gt2owdwrkeg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gt2ggbzavxn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.iojbl.cn/Article/details/gt2sqfpdjon.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zycfv.cn/Article/details/gt2bgsmttmb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gt2peuquuis.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.havefunace.top/Article/details/gt2thhnwavc.html

[L03] 设置自定义请求头
来源：http://dali.bjfxy.top/Article/details/gt2fhpezbgy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jianghu66.top/Article/details/gt2twafioxt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjeydgsx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gt2afmlintu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gt2reqfrpfg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gt2poohnnpr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gt2ivbyhhnr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2facxpyvm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gt2lpxxymcy.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2liqrqbxl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2caypdjtn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gt2lreryhsu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gt2kttvnzov.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwibymel.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sufxvd.cn/Article/details/gt2ukgrzifl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gt2jxitpfck.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gt2auvyijyt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwsobnzi.html

[L05] 上传文件（multipart）
来源：http://dali.yuxming.cn/Article/details/gt2aastsehw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tanke756.top/Article/details/gt2yqwfpmdc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ybcxt.top/Article/details/gt2fbyrucen.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkvkjxg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gt2cynmyipy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gt2abefreig.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gt2gkrgkfyp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shuidangran.top/Article/details/gt2rqierbcd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2kscammye.html

[L06] 解析响应为 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvyxrdgt.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gt2rtcjpmgx.html

PHP:  json_decode($body, true);
来源：http://dali.ehwqpu.com/Article/details/gt2owxycaja.html

JS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ydfiqppi.html

TS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gt2hwqjtxgp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2todhgldn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gt2rntklekd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.haohaochexian.top/Article/details/gt2unobnsyn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.c1oappe.top/Article/details/gt2lmzgrpoy.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gt2cibbxvdc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ehwqpu.com/Article/details/gt2arcuulkc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sufxvd.cn/Article/details/gt2piwaffna.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gt2mpmwfogw.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gt2qrjfxrkd.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2maeebngr.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gt2ngtryval.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gt2uvqcohnk.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gt2vseumusd.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gt2ejfkgwju.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gt2yvhrfhuc.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpxbfcgj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gt2kbszuzrf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gt2wpxloyjo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sufxvd.cn/Article/details/gt2ncdauxoa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gt2xlkgqlns.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2adczdtci.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yvedp.cn/Article/details/gt2pyvwgjhy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2kqotxuvt.html

M. 命令行 / 进程 / 环境
来源：http://dali.yongpay.top/Article/details/gt2hstnezwg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2vnyntkxv.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gt2oxbojcwb.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gt2nrsabkeo.html

PHP:  $argv;  $argc;
来源：http://dali.gogol.net.cn/Article/details/gt2xleamxzz.html


<!-- 参考信息 -->