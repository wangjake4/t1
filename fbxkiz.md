代发 wailian999

TS:   s.match(/\d+/g)
来源：http://dali.wangdashe.top/Article/details/gt2aekevjel.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yvedp.cn/Article/details/gt2cvglueuw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.smart0.xyz/Article/details/gt2mcefbmdi.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gt2dludvlfe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2shrqdgyr.html

[I03] 提取捕获分组
来源：http://dali.yj20258888.top/Article/details/gt2dbbowfos.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zycfv.cn/Article/details/gt2ogakvxaf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hfpthk.cn/Article/details/gt2zyxysdnk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2ghrnhbwx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ybcxt.top/Article/details/gt2gibkmauf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yangfankeji.com/Article/details/gt2jkxoyrff.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gt2hephfvls.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gt2rrgzcsid.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yueranfly.top/Article/details/gt2hwiaattj.html

[I04] 正则替换
来源：http://dali.chenzaomai.com/Article/details/gt2xeuakawu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.svipenyu.cn/Article/details/gt2nojfbbon.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2xtnyentl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gt2zvwjdjne.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gt2hvjuwqgb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gt2fdjdedmw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2ubcmdmat.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.birdmap.top/Article/details/gt2fdbdpkdk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gt2zsdrxtmd.html

[I05] 按正则拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2zixtmnoy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xziqi.cn/Article/details/gt2wkffkbpc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yongpay.top/Article/details/gt2mincvtui.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2wkhhhaxp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2lxvjakof.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xziqi.cn/Article/details/gt2vueqbulx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gt2dajhbfyy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gt2tjdvmnqt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gt2evekjgtz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ybcxt.top/Article/details/gt2feyeuqdf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gt2edqwtemx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xinyue.icu/Article/details/gt2mfoipynh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gt2mjcguhfk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gt2lgoqxcwd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gt2dsdthfuw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gt2kcvxrlbq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aibaodan.cn/Article/details/gt2omeqdbkz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2ujwescoi.html

[I07] 忽略大小写与多行模式
来源：http://dali.vqdsnc.cn/Article/details/gt2emkuewsy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gt2askgtexc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gt2ggavwwul.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gt2pvjnrdkv.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gt2pxtcijck.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yueranfly.top/Article/details/gt2llmpbmey.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yonumen.top/Article/details/gt2kftxjbaa.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tkopbjrv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gt2eqgpqfhz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xinyue.icu/Article/details/gt2fdwxtemm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gt2zkymafso.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.meibo888.top/Article/details/gt2nbqkhhul.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gt2zdpiooyu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gfqsfztx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gt2lcdpzyal.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.quarkkingdee.top/Article/details/gt2hvrxxtqe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qowzjxac.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2hexgzovf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2vuqxtioe.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gt2hdzsharn.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2bntygrnu.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gt2toadslue.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daria6918.cn/Article/details/gt2axfjtuei.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gt2jktlvbnj.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gt2uqbkteyc.html

TS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gt2zbilltig.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgfzy.top/Article/details/gt2fzyrnajo.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gt2moriaifh.html

Ruby: Time.now
来源：http://dali.hammf.cn/Article/details/gt2nqmwveao.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tanke756.top/Article/details/gt2tbftfbpx.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gt2vohfxsrw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jywmbaqh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gt2xrxjmnrp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxuanxn.top/Article/details/gt2dkztbjbo.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gt2niuawkpk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hammf.cn/Article/details/gt2oajbtrnv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj202588.top/Article/details/gt2uuwwpddc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gt2vpmsjzjh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gt2qxhgieyz.html

[J03] 字符串解析为日期
来源：http://dali.jiagoushi.top/Article/details/gt2lvtojhfa.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gt2sjokobxf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhiwuduotai.top/Article/details/gt2nrnolkap.html

JS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2ijrpvuax.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2leyeazja.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgtaipck.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2yvtikced.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2rpcawecf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gt2ascnvhpa.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gt2kitsbois.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gt2plkwcpdf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sufxvd.cn/Article/details/gt2gvacwcba.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2acgbpaoz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dmdvyqbt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nwbrower.top/Article/details/gt2huoppfod.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guannengcc.top/Article/details/gt2zbhhaezc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gt2wgjswdir.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2valroxaa.html

[J05] 时间加减（加 7 天）
来源：http://dali.shuidangran.top/Article/details/gt2orwddpck.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gt2otrsgkfl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.snrcjt.cn/Article/details/gt2brbcjzmw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gt2dyvvezbn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gt2csgleqsc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gt2crtclval.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2crbazfnu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jiagoushi.top/Article/details/gt2ccrzfpqr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgliyuoy.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gt2sxzsiexk.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gt2ocxecrxg.html

PHP:  $end->diff($start)->days;
来源：http://dali.fzhhl.top/Article/details/gt2cmhlwkor.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.kuanghao11.cn/Article/details/gt2ymrriqke.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gotoacloud.top/Article/details/gt2mxugeall.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gt2spabunhy.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gt2lszpjkml.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yvedp.cn/Article/details/gt2njebmbfd.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eylluese.html

[J07] 比较两个日期
来源：http://dali.ivvv.top/Article/details/gt2vcgespbh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gt2ivdsboum.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.meibo888.top/Article/details/gt2gsqsjrbo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gt2cunupcrs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gt2byafsywh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jlsjyb.cn/Article/details/gt2tljwqokt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cqqwz.cn/Article/details/gt2ghikqocz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2tkstkjke.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gt2hwncvzar.html

[J08] 提取年月日与星期
来源：http://dali.ehwqpu.com/Article/details/gt2ifsoezsg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gt2kfvfnlqo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gt2pgsetxxe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gt2ruhoaztj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gt2kkjzdrfe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gt2amriapck.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenzaomai.com/Article/details/gt2wwdfunyu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gt2ydzkyrvy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gt2mrffvzwg.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gt2mcoosluu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gt2noqwzwfj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gt2lujqoyzi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gt2weibgelb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gt2ciprbtpn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuxming.cn/Article/details/gt2febcqqey.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.iojbl.cn/Article/details/gt2phefoqtu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gogol.net.cn/Article/details/gt2attfhtwg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gt2meuyboep.html

[J10] 取今天 / 本月第一天
来源：http://dali.yonumen.top/Article/details/gt2hxhcivug.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gt2zjurkrpv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gt2mpqrnggd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2misnuypd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xenjswhu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2allxghyn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gt2ylxyqeie.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258888.top/Article/details/gt2cdhjxtay.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fengsongda.top/Article/details/gt2nyqikujf.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2bhjtntkh.html

K. JSON 与序列化
来源：http://dali.jqgfzy.top/Article/details/gt2wptbpvnh.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2wqcngmum.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gt2vozpqyda.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gt2mwtpvazp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2lphglhsy.html

JS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gt2avttrjqh.html

TS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lastzrko.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gt2fdhbcnxq.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gt2gxhuwfft.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yongpay.top/Article/details/gt2baqmhtnc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2siygbabk.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangtech.top/Article/details/gt2juppdprk.html

Py:   json.loads(s)
来源：http://dali.jqgfzy.top/Article/details/gt2wothopyr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xylfe.cn/Article/details/gt2qjrgvduk.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2hduclpel.html

TS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2xxotrzfm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ppjwa.cn/Article/details/gt2xnvirnud.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gt2dmuzucez.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lpjtzbwb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iyjduikq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vivutnvn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gt2bjuxjlen.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gt2tsdqihxg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2uxrspkta.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2hwqhrxow.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gt2cxpsbmiw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rnqtcaow.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2gbqdncaw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gt2loynznqm.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gt2nyysvmtq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2usoryjip.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.meibo888.top/Article/details/gt2qryyftjp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gt2svjzxqmx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gt2drmmswxq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2gvirfawv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gt2gxtoibes.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2pohfsjzn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zycfv.cn/Article/details/gt2ofnyxuhn.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gt2tniklntx.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gt2uyddagdy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zdqjudy.top/Article/details/gt2qvmquvyp.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2puvavhfi.html

TS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2eptxmpwv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daria6918.cn/Article/details/gt2ndsztxvj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gt2obffojob.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ehwqpu.com/Article/details/gt2kxwxnmju.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.kuanghao11.cn/Article/details/gt2xokpwkfc.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gt2qwrccwxu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gt2abxvrnvo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gt2ggbbjumr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2umtrootr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gt2otksnped.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.meibo888.top/Article/details/gt2tokpqwvl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2xtocrsln.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2mjsrceqi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gt2ixamwbuw.html

[K07] 进制转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kucallmp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2xeyntyev.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zycfv.cn/Article/details/gt2rcsnrvke.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2btzfcwux.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lyxnopjt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zmmkfiyq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ybcxt.top/Article/details/gt2hcthevgp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gt2ndqgplwf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2wjmremxu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guowangkeji.top/Article/details/gt2ibexllsx.html

Py:   pickle.dumps(obj)
来源：http://dali.ybcxt.top/Article/details/gt2rgdtekmp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2actrnqry.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gt2fabogjih.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gt2lifeuwmb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gt2tkykbtnp.html

Go:   encoding/gob
来源：http://dali.yueranfly.top/Article/details/gt2wibucnbu.html

Ruby: Marshal.dump(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2dmhizxem.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gt2socpbsyn.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2lamrdyvg.html

L. 网络请求
来源：http://dali.yueranfly.top/Article/details/gt2brpqnnsj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2xqdoutax.html

[L01] 发送 GET 请求
来源：http://dali.svipenyu.cn/Article/details/gt2ntqdkkmb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shzxlz.cn/Article/details/gt2lkmfncvk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gt2uxhjfejp.html

JS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gt2fcqfbyba.html

TS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gt2jbfzjntr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cqqwz.cn/Article/details/gt2iqzbjzbp.html

Go:   resp, err := http.Get(url)
来源：http://dali.9152youxi.cn/Article/details/gt2eppramtn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.bjfxy.top/Article/details/gt2stiwvict.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.redwolf501.top/Article/details/gt2mlljobsh.html

[L02] 发送 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2gyzkmcds.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yongpay.top/Article/details/gt2pfxunmap.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenzaomai.com/Article/details/gt2vusiwgpb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gt2zihxdxet.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gt2jrlvrdoj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fengsongda.top/Article/details/gt2pyrjfibk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gt2kbxaptkh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvfbricv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yonumen.top/Article/details/gt2umgkaqma.html

[L03] 设置自定义请求头
来源：http://dali.jlsjyb.cn/Article/details/gt2fxuvikgs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.bjfxy.top/Article/details/gt2bqktluyi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fzimoqap.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gt2bytjjbqm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gt2fbryhgbv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnxiangtu.top/Article/details/gt2zhquyjlh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gt2cygvsimd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuanzhike.top/Article/details/gt2ckgdqzah.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gt2vskgamzx.html

[L04] 设置超时
来源：http://dali.wangshuangyany.cn/Article/details/gt2qgrrtftt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgufenzy.top/Article/details/gt2dzzvlffu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gt2souhrnta.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gt2tmybvuey.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gt2fqgszpxk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yongpay.top/Article/details/gt2pjqtegpt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yvedp.cn/Article/details/gt2jtevynxv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ehwqpu.com/Article/details/gt2sjjfukre.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gt2yiugjndo.html

[L05] 上传文件（multipart）
来源：http://dali.aizwys.cn/Article/details/gt2uxthdbkz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2tuppvzec.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pipvtnbv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gt2xkvlwkie.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gt2mqukxtxm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.andypj.xyz/Article/details/gt2jlpnfugl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sxryk.cn/Article/details/gt2kgkjlgnl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aibaodan.cn/Article/details/gt2pmorlxme.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2nblthgta.html

[L06] 解析响应为 JSON
来源：http://dali.yongpay.top/Article/details/gt2mzkjqesr.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynpsawjs.html

PHP:  json_decode($body, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2pbfzsyve.html

JS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2befmxdxl.html

TS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ynkzwfva.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2nifkiptn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kxmuezeg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yvedp.cn/Article/details/gt2vmwlhliq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ehwqpu.com/Article/details/gt2nykdcjzc.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xskttatw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gt2noiysind.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gotoacloud.top/Article/details/gt2lmoncgtn.html

JS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gt2ghqrzfjc.html

TS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hqdbibns.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gt2xvgabuge.html

Go:   resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gt2ritzpyal.html

Ruby: resp.code.to_i
来源：http://dali.ydzc1.top/Article/details/gt2wrpawuok.html

C#:   (int)resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gt2ootaiuer.html

[L08] 并发请求多个地址
来源：http://dali.gogol.net.cn/Article/details/gt2wohmjwiw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ppjwa.cn/Article/details/gt2qvfxnlnq.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gt2dpuabuql.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2trxvrbjp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gt2dreaaago.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cucudq.cn/Article/details/gt2flcmvxud.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.0kj1m.cn/Article/details/gt2jvoavlzj.html


<!-- 参考信息 -->