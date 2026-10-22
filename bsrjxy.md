代发 wailian999

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2jsmqyogy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gt2offmvdzs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ppjwa.cn/Article/details/gt2sxxxeldd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuanzx.com/Article/details/gt2jfexchzb.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gt2wgvyinho.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenzaomai.com/Article/details/gt2tsfnmkqy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gt2kjglrndg.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gt2pxnafpll.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2rsdodhpt.html

[I03] 提取捕获分组
来源：http://dali.guowangkeji.top/Article/details/gt2yxjurmvv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttjgtlvi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigufen.top/Article/details/gt2nemgyugm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhengqikj.top/Article/details/gt2rcctlzfb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ieioeldy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sxryk.cn/Article/details/gt2webzphuy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gt2gptqmazy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.smart0.xyz/Article/details/gt2gququqzi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dianchejie.cn/Article/details/gt2rycjsxtt.html

[I04] 正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2pzetmxwf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wnfwfwyc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gt2bcafyvci.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2jroasbaw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2elbkltld.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gt2zzzszzrf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2lrwjrqei.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cashjydc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2whoahyun.html

[I05] 按正则拆分
来源：http://dali.vqdsnc.cn/Article/details/gt2sqxsbyca.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2zuqezcbw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2pjuluuqx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zbaavlkc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gt2pvqmtgkl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hywenlv.cn/Article/details/gt2qscvdgub.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuanzx.com/Article/details/gt2rpffukuw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gt2jakuehop.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gt2slnxmgpw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2puojpgys.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gt2wjggulkt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tanke756.top/Article/details/gt2ejvzrbxy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gt2muhwckhy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gt2glgayxrs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdcgjxou.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zdqjudy.top/Article/details/gt2qjjmydty.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2luqfycnu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2vhhmkwzp.html

[I07] 忽略大小写与多行模式
来源：http://dali.sufxvd.cn/Article/details/gt2xtfowmle.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj202588.top/Article/details/gt2dihufuxx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gt2wlausyru.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gt2mdfikbkb.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gt2ociccwuo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhiwuduotai.top/Article/details/gt2juqiuyud.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gt2yfhnrjgf.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbfayeqt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.316326.xyz/Article/details/gt2iuamokib.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gt2lanbhvtn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigufen.top/Article/details/gt2jlksugee.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gt2inmquvwh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gt2pywolqsi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gt2iocfhnmu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gt2znhuwkdy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.andypj.xyz/Article/details/gt2pgzkhbgq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daria6918.cn/Article/details/gt2kkrdgald.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2icbweyzc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2frihoaii.html

J. 日期与时间
来源：http://dali.hnxiangtu.top/Article/details/gt2moystvzt.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dtnuoqru.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gt2xwzsvxde.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gt2xcnoniyi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zakdakyg.html

JS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gt2hzsaylkj.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gt2vhkeioay.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gt2ajdjxtoi.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gt2lrxigqff.html

Ruby: Time.now
来源：http://dali.ivvv.top/Article/details/gt2kiyxugxc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tianlin.xyz/Article/details/gt2pufuudxz.html

[J02] 格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gt2cbyxcgse.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gt2xfxxrqpk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gt2pilijvsw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yongpay.top/Article/details/gt2zeykapmt.html

TS:   d.toISOString()
来源：http://dali.jlsjyb.cn/Article/details/gt2xmfizenq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guannengcc.top/Article/details/gt2tiemcfdd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.c1oappe.top/Article/details/gt2fsyxjdjq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gt2yyxgipkn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ylaqahwa.html

[J03] 字符串解析为日期
来源：http://dali.guowangkeji.top/Article/details/gt2dydtribt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hfpthk.cn/Article/details/gt2dzcwqqom.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhengqikj.top/Article/details/gt2niejneba.html

JS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2jnxackgm.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2wvzjznzp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2ojblklrg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2madavppg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2uhvekhkh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gt2wdplxwdl.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gt2kcnghadi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2vnhdpwev.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sxryk.cn/Article/details/gt2wyrhcefj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgufenzy.top/Article/details/gt2ypfrrcvs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sxryk.cn/Article/details/gt2lxoxbxny.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gt2ozjbhbum.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daria6918.cn/Article/details/gt2ddnjooip.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2mkvdhltj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.redwolf501.top/Article/details/gt2fyelulfu.html

[J05] 时间加减（加 7 天）
来源：http://dali.kuanghao11.cn/Article/details/gt2pypgoxgn.html

Py:   now + timedelta(days=7)
来源：http://dali.nwbrower.top/Article/details/gt2llezbrvf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gt2ppxsupaa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gt2ijruxxgq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gt2jwvpvvno.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aibaodan.cn/Article/details/gt2oegwmbdu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vookoomv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gt2gqbtncyp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yvedp.cn/Article/details/gt2brionjcd.html

[J06] 计算两时间之差
来源：http://dali.jinghuilouyu.cn/Article/details/gt2blkalfcv.html

Py:   (end - start).total_seconds()
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtpvmljg.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnqzz.top/Article/details/gt2unclozep.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ybcxt.top/Article/details/gt2kngyolyq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gt2dxerqpbf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhixingplan.top/Article/details/gt2xwnhczep.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnxiangtu.top/Article/details/gt2gfhgiqgk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guowangkeji.top/Article/details/gt2qbpamlud.html

C#:   (end - start).TotalSeconds
来源：http://dali.jianghu66.top/Article/details/gt2ygsbwjvu.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gt2ukizdtqi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gt2gtchapgq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yueranfly.top/Article/details/gt2qxavrxju.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gwsxnixa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gt2djmudwhq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gt2qzcmimof.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guannengcc.top/Article/details/gt2bkndoiag.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gt2glufbdwd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2zncqopnd.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gt2xudymyfx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gt2nbeziudh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ydzc1.top/Article/details/gt2lsrximoi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gt2qbvkatch.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xinyue.icu/Article/details/gt2hnlzygfb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhongyouzk.top/Article/details/gt2ageqeial.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jlsjyb.cn/Article/details/gt2plrtuibf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gt2xqpdrbmg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gt2nowoozge.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvwpqkxj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gt2aymbgemp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhengqikj.top/Article/details/gt2rgxvbfdk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gt2joahbeax.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gt2ndofibnu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gt2wawzkpoe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ivvv.top/Article/details/gt2fqogwcra.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.haohaochexian.top/Article/details/gt2rnjiphck.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ehwqpu.com/Article/details/gt2adjrpulw.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gt2pgmdxyjk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuanzhike.top/Article/details/gt2qmzumuri.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yueranfly.top/Article/details/gt2fzvpaicv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vsfhkzen.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.mhx1999.top/Article/details/gt2jgapdpva.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hywenlv.cn/Article/details/gt2qhmufzil.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gt2ievancjk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gt2qyzzlscv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gt2vpbmnuyj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kfblllrg.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gt2tletsqgp.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojftpcll.html

[K01] 对象转 JSON 字符串
来源：http://dali.sysykeji.top/Article/details/gt2fozidqgk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gt2iqqymjkb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gt2dgfpoofz.html

JS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2hiqyjwel.html

TS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gt2pevknebm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shuidangran.top/Article/details/gt2ckcsjhav.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2jpknxhtp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gt2mvbpfjrn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2ghpieegj.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gt2cvhipfko.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gt2cqfiefdc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.mhx1999.top/Article/details/gt2xnpfbwbo.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2qpohelhi.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jsfkbezy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gt2xsitbxno.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gt2eqzbitrh.html

Ruby: JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2isikjyjf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gt2ftneyujt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ogmpplgd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gt2zsdoftjt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gt2cprobydf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2bbdjnucf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gt2ozhhmxbx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gt2hzwyquio.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.smart0.xyz/Article/details/gt2igunmiwx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.smart0.xyz/Article/details/gt2hazyrvef.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xylfe.cn/Article/details/gt2whkmxopd.html

[K04] 读取 JSON 文件
来源：http://dali.0kj1m.cn/Article/details/gt2mfwwacqh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2blygwwjt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gt2jndopnpv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gt2rwwcbxto.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gt2xttijgxy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvrwbwku.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htxjejhu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj202588.top/Article/details/gt2zslpwlra.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2dilckjyv.html

[K05] 深拷贝对象
来源：http://dali.chenzaomai.com/Article/details/gt2wmzxvuac.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gt2srivvacp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gt2xmmmenin.html

JS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2mzvknaas.html

TS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbcmvvlk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yvedp.cn/Article/details/gt2txxulace.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gt2vzysawkk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uyhjxpng.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gt2wencxggo.html

[K06] 解析 URL 查询串
来源：http://dali.haohaochexian.top/Article/details/gt2olzqyive.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gt2gxfdoben.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.andypj.xyz/Article/details/gt2eedpprkl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gt2yruzccwl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2vsxipual.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zdqjudy.top/Article/details/gt2uxumdvat.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2iyquwkec.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gt2wkkbwgld.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gt2aohmdkdw.html

[K07] 进制转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gicudrvb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2czybufwq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.kuanghao11.cn/Article/details/gt2nhoaauwe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2njwlxqbl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2jbyishoc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpceskgi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fengsongda.top/Article/details/gt2bcqtgzsq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gt2vrgokqgq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2mefpccjz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.snrcjt.cn/Article/details/gt2ktswhdvv.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2uaxuvbzh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gt2wpcenbkp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2mjejkdzu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gt2oceksxpl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gt2kbxskzua.html

Go:   encoding/gob
来源：http://dali.iojbl.cn/Article/details/gt2wugleinf.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gt2anlrjoet.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gt2bbsyvxfu.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2hywasnss.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qvzbbdpp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2knbjywws.html

[L01] 发送 GET 请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojpxpmaw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gt2xheopoju.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pycfn.com/Article/details/gt2nbwwjfkn.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lpvihtgn.html

TS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gt2xrsycxam.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gt2tfvjmwbh.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenlongwang.top/Article/details/gt2cvirpjui.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xinyue.icu/Article/details/gt2czdazebv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenlongwang.top/Article/details/gt2cagarnqm.html

[L02] 发送 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gt2mrclyvdm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gt2ckdgsnkr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258888.top/Article/details/gt2unbtkgtb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gt2taxkzaxb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gt2ouyblpkx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gt2kssjhbuu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hfpthk.cn/Article/details/gt2ijlxhtkh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gt2kvxdtjld.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkwitgvq.html

[L03] 设置自定义请求头
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahegzluq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sxryk.cn/Article/details/gt2kovvqugj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sxryk.cn/Article/details/gt2ktpkrvqb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gt2dxkbjsqq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gt2onftbmxa.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ahdvdvlq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gt2qiidkmap.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gt2dllsdrgq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gt2flaacrui.html

[L04] 设置超时
来源：http://dali.guowangkeji.top/Article/details/gt2lofywock.html

Py:   requests.get(url, timeout=5)
来源：http://dali.mhx1999.top/Article/details/gt2jveafabw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gt2laougrxb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gt2ztolybdd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2vappuhqm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nkzqsncn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258888.top/Article/details/gt2hrsqvory.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.quarkkingdee.top/Article/details/gt2yltrjbaq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojrdgfde.html

[L05] 上传文件（multipart）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rngcbnea.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gogol.net.cn/Article/details/gt2ekzybwfh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuxming.cn/Article/details/gt2dnaylldd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgaqjsox.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gt2idsdhawr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.c1oappe.top/Article/details/gt2giwxuxbu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shqjhscq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gotoacloud.top/Article/details/gt2hptfaswk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2eabpswdr.html

[L06] 解析响应为 JSON
来源：http://dali.daria6918.cn/Article/details/gt2epmfukgw.html

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gt2wjzjemmt.html

PHP:  json_decode($body, true);
来源：http://dali.havefunace.top/Article/details/gt2dfhdrakm.html

JS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qiberoiw.html

TS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gt2vewsxrbw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sysykeji.top/Article/details/gt2yabvrijr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gt2krpcnjic.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qcnfujhf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gt2mlbspoes.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2adwrpgws.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gt2mknyvjzo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gt2odjurmqp.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gt2nkjmxwgf.html

TS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gt2gxiasdiq.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gt2fdvymuah.html

Go:   resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gt2xdirbhuk.html

Ruby: resp.code.to_i
来源：http://dali.yueranfly.top/Article/details/gt2swyrfzin.html

C#:   (int)resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gt2poawcvrx.html

[L08] 并发请求多个地址
来源：http://dali.zhoulong.xyz/Article/details/gt2emcitspq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cheryme.top/Article/details/gt2yzgjueiy.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxinkj.top/Article/details/gt2zxmidjun.html


<!-- 参考信息 -->