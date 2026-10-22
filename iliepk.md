代发 wailian999

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gt2tfipkouf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj202588.top/Article/details/gt2jafzmkcp.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gt2rpyhzclg.html

TS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gt2thheclad.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gt2elzujflf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jianghu66.top/Article/details/gt2knjemtoz.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sipfohpg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gt2fxdphpck.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gt2ksqegyfh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gt2bgoctbeg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gt2xgrtyftr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gt2vsilfwco.html

TS:   s.match(/\d+/g)
来源：http://dali.sysykeji.top/Article/details/gt2sjpbqvlg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2zaozzsza.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gt2wmqlagil.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gt2tdtnxczc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2ruyimnbg.html

[I03] 提取捕获分组
来源：http://dali.cashguo.top/Article/details/gt2oagsgxtg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gt2remmmmzl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2owjivbwv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2dwiozewo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2qnvzwdvs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.quarkkingdee.top/Article/details/gt2trbytmpt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gt2xnnqoxyn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gt2trtdzmte.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gt2sqrpsoto.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gt2aciridul.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.haohaochexian.top/Article/details/gt2hnyfyoel.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gt2hfzfmfna.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2onbaqzdg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvchtdfv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.meibo888.top/Article/details/gt2nffcxpsv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gt2eqanjbly.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2dvwqlwog.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gt2wvwrbeee.html

[I05] 按正则拆分
来源：http://dali.zhongyouzk.top/Article/details/gt2ufudwzhu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cblhmsvu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2tlikldgy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gt2wuyugmcm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gt2xqrrhsvx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gogol.net.cn/Article/details/gt2hofyhyxl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2eqiufkio.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2usowjbex.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dashuyun.cn/Article/details/gt2taypzxbu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.iojbl.cn/Article/details/gt2zyyumbdr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gt2gtuwhknz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ffjhbqtk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gt2iwgzalzz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gt2akcdvcun.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gt2cabvhtoh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.c1oappe.top/Article/details/gt2bqexxxqz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cqqwz.cn/Article/details/gt2ncoynjbi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gt2pgkmqppj.html

[I07] 忽略大小写与多行模式
来源：http://dali.gotoacloud.top/Article/details/gt2rmlmpmzm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gaohongyu789.top/Article/details/gt2bhjzitxc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gt2qxjinsfh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gt2oobltmns.html

TS:   /error/gim
来源：http://dali.sweek.top/Article/details/gt2jwesnseb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxiikkrr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.smart0.xyz/Article/details/gt2gpauozjp.html

Ruby: s.scan(/error/i)
来源：http://dali.hnxiangtu.top/Article/details/gt2hpisyqda.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gt2wzmcebef.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sweek.top/Article/details/gt2xivjjfjq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sysykeji.top/Article/details/gt2mvbrbvhg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gt2vnvryqpj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gt2qzaftorh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gt2voweslsl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gt2rvijcaow.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tianlin.xyz/Article/details/gt2dlwwfkur.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgsatzip.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gt2yhzhqfgp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2ksbrrxpr.html

J. 日期与时间
来源：http://dali.tanke756.top/Article/details/gt2baxjoquf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2quhrmnpe.html

[J01] 获取当前时间
来源：http://dali.tanke756.top/Article/details/gt2zdwotcem.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dbbxpfgz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gt2sjclbymg.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2ubeayywo.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gt2xxoxkbcx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xylfe.cn/Article/details/gt2fxixkvis.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gt2xddszdau.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gt2idgqfuxw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ydzc1.top/Article/details/gt2zioqaank.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vcoywbme.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gt2txnqxasj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gt2fzrbvguo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yvedp.cn/Article/details/gt2dezvexwx.html

TS:   d.toISOString()
来源：http://dali.hnxiangtu.top/Article/details/gt2brmsmhut.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhongyouzk.top/Article/details/gt2pvmytkyi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2tljjmkth.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gt2lrefropk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gotoacloud.top/Article/details/gt2bdeqyebr.html

[J03] 字符串解析为日期
来源：http://dali.xuanzx.com/Article/details/gt2uesxfouf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gt2jbzszhvg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gt2uhzcggsh.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2ncrptlmu.html

TS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2iwabnzlo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ykxivkzn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2elxjptbn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2icbslifl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gt2kvxckefq.html

[J04] 时间戳与日期互转
来源：http://dali.xylfe.cn/Article/details/gt2igyzdzca.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gt2tjowtfsa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sxryk.cn/Article/details/gt2yucxrlez.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxinkj.top/Article/details/gt2lxkysuii.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gt2eyfkkqyi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nwbrower.top/Article/details/gt2pjubblxq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gt2vbrkhgwg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gt2jjxxvshl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gt2eteszlda.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhongyouzk.top/Article/details/gt2tqhkhptv.html

Py:   now + timedelta(days=7)
来源：http://dali.aizwys.cn/Article/details/gt2auwyaapc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gt2butizbce.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2fygotdoi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gt2stbcwfdj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gt2bzmckmir.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gt2cudadhqx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nwbrower.top/Article/details/gt2tajfdmhk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gt2znqodklg.html

[J06] 计算两时间之差
来源：http://dali.guannengcc.top/Article/details/gt2tikxfdpw.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigfzy.top/Article/details/gt2oziugcoj.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gt2avkuytuc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenzaomai.com/Article/details/gt2uplrhjju.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhongyouzk.top/Article/details/gt2yewxjfih.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnxiangtu.top/Article/details/gt2lnblfyxo.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gt2kosdrdel.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gt2jauveeql.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuxming.cn/Article/details/gt2wwdrvxdw.html

[J07] 比较两个日期
来源：http://dali.quarkkingdee.top/Article/details/gt2odgkbknz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2dgeiqgfy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gt2kmwnhmpd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gt2yqtnobrt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gt2sicethab.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ydzc1.top/Article/details/gt2yxzkrhjo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gt2ekbgdirx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2hrdgaldw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gt2qrkhqtob.html

[J08] 提取年月日与星期
来源：http://dali.yj202588.top/Article/details/gt2tuzeuaka.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gaohongyu789.top/Article/details/gt2jplpmmrg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigufen.top/Article/details/gt2gqfoxyqf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ybcxt.top/Article/details/gt2iulglabl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.redwolf501.top/Article/details/gt2uuuywzxz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gaohongyu789.top/Article/details/gt2qlbzhmlc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gt2czmenrfa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gt2vysuufsk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.haohaochexian.top/Article/details/gt2wotmcqlz.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gt2rqtaueac.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gt2kmzxxdwu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gt2qusjlhpv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gt2kpaokqag.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gt2volwgujn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxuanxn.top/Article/details/gt2vftlggqf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gt2nkyuufpz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gt2qnhhliuc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xziqi.cn/Article/details/gt2bpkpikyi.html

[J10] 取今天 / 本月第一天
来源：http://dali.hywenlv.cn/Article/details/gt2mxvfjbzt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gt2ofpcztdj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.haohaochexian.top/Article/details/gt2slupubmp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ikmnnmng.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hammf.cn/Article/details/gt2bvmsfawp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sweek.top/Article/details/gt2jnwjeiul.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gt2rvbnbknk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gt2jjvalzgv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2orgyuzvz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2gfoheyhf.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gt2lmpqyift.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwyrltgt.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gt2lsygsctx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gt2ychyhnvg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gt2klishawi.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2dmeddfdw.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2xhidlqvx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258.top/Article/details/gt2zxqvvbar.html

Go:   json.Marshal(obj)
来源：http://dali.cheryme.top/Article/details/gt2suhknifi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenlongwang.top/Article/details/gt2ubrnfvns.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2acrrjwth.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gt2vjuxzkws.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gt2ceyupzxj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gt2werekxny.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2tlyoepts.html

TS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gt2zrwtclor.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pzxngnzx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gt2jzaxaisd.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2jhllahwv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgfzy.top/Article/details/gt2lnizqcyy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqgjlsxc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gt2xwddvrwr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gt2achhwgce.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2alohvasb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2cxkhvrdr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2bkxcerbn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gt2emvasxvj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gt2ivxlaxci.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gt2cbwrvwza.html

[K04] 读取 JSON 文件
来源：http://dali.yongpay.top/Article/details/gt2kdzbtltw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hywenlv.cn/Article/details/gt2mivfdqxv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gt2mcutojqq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2dubmmrbp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gt2lbkxxglo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gt2jecgybus.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gt2plbdzybk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gt2hlaculmf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tanke756.top/Article/details/gt2gwvmoeaa.html

[K05] 深拷贝对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gblgqcud.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gt2tnfwsbfn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gt2czqanlmh.html

JS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2cvxxqano.html

TS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gt2ryurikto.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gt2qtwptcts.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gt2xxlpopxv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gt2gmdibyyh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenzaomai.com/Article/details/gt2golufihq.html

[K06] 解析 URL 查询串
来源：http://dali.pycfn.com/Article/details/gt2zgjqnpss.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gt2mimbszxg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhengqikj.top/Article/details/gt2oreublbx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gt2itevbnbs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gt2axzkvnmn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gt2tamfkcgj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gt2hkuptmvh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2tmacdgyt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gt2xkfbhrvi.html

[K07] 进制转换
来源：http://dali.yanxiufei.cn/Article/details/gt2nxeaqivc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2wcpwgbcw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gt2nrxvisvn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2zsgrigqi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2qpyypisd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2dxqkmuzc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gt2kfpieccg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yueranfly.top/Article/details/gt2fsebzkky.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zfusndxi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cheryme.top/Article/details/gt2srxqyvll.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gt2dtwyppag.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2owlunros.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gt2feqpwabq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gt2dghncixr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shuidangran.top/Article/details/gt2mdtthrre.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gt2iybvurve.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tgzrmkgp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdpnttgj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2pfdkgnnu.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gt2afupqqlu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2aplhoemh.html

[L01] 发送 GET 请求
来源：http://dali.dianchejie.cn/Article/details/gt2qflmfpkp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gt2bbikhpxn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tanke756.top/Article/details/gt2kxpxjaea.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gt2wnyjdnla.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gt2obyuhrqq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gt2mrecdngz.html

Go:   resp, err := http.Get(url)
来源：http://dali.gzhubu.top/Article/details/gt2ktlqhrfp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuanzx.com/Article/details/gt2yyysxsgc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jianghu66.top/Article/details/gt2svjckzqr.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2oazukrig.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shuidangran.top/Article/details/gt2rdzzalgg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnqzz.top/Article/details/gt2jcrvnchv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gt2ktvzgoyf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gt2enomissh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aizwys.cn/Article/details/gt2rdzgxasr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gogol.net.cn/Article/details/gt2nfzhvqvl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhiwuduotai.top/Article/details/gt2klfpyodv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.mhx1999.top/Article/details/gt2uuyzzvrv.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gt2hncvdvoh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fengsongda.top/Article/details/gt2uomcwxat.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gt2vdixbdvj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gt2xkmpwjvf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gt2kslhxpvp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aizwys.cn/Article/details/gt2tljaevef.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhgymdkh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gt2szcuumdo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gt2fhafwtob.html

[L04] 设置超时
来源：http://dali.kuanghao11.cn/Article/details/gt2diqjtcgt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ppjwa.cn/Article/details/gt2jofiqeli.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gt2qbbnugij.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gt2ubzsrwlp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gt2otzrogie.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cucudq.cn/Article/details/gt2pwhnwmub.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzdfnerh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuxming.cn/Article/details/gt2epfyvnra.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgufenzy.top/Article/details/gt2ulhgumnh.html

[L05] 上传文件（multipart）
来源：http://dali.cheryme.top/Article/details/gt2oupueszr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gt2eofxkuxr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.andypj.xyz/Article/details/gt2dcwsbwwf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gt2ejoxybuz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gt2apiiuqyz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gt2zblsacja.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ppjwa.cn/Article/details/gt2sofvtiaw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daxiang520.top/Article/details/gt2fqxscozf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2xajbstyt.html

[L06] 解析响应为 JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2kycapybd.html

Py:   resp.json()
来源：http://dali.guannengcc.top/Article/details/gt2wmriejyv.html

PHP:  json_decode($body, true);
来源：http://dali.zycfv.cn/Article/details/gt2zxdpbcsa.html

JS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2pxqjmvaq.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2mhnuthyw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2ewyhkgcv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gaohongyu789.top/Article/details/gt2flhrlnlo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gt2ldarhjcz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guannengcc.top/Article/details/gt2vjxrebma.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gt2vtmlvxxv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxuanxn.top/Article/details/gt2rboayxxs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gt2htycxuzv.html

JS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gt2trcthqoz.html


<!-- 参考信息 -->