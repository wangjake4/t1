代发 wailian999

[I02] 提取所有匹配
来源：http://dali.yueranfly.top/Article/details/gt2hecgenvj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gt2iunlqdvi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gt2abhnklfq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yvedp.cn/Article/details/gt2lqaqyzzr.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gt2baiveqkm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdgtcasg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hwwqqtoa.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2gqxgxvnd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2kcwviqgk.html

[I03] 提取捕获分组
来源：http://dali.daria6918.cn/Article/details/gt2jkfbcrqx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gt2rupgrhxy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.316326.xyz/Article/details/gt2nchwymif.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2hrkmmqpq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kahaoazo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.haohaochexian.top/Article/details/gt2avxgswks.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gt2oxkcutlu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tanke756.top/Article/details/gt2aeqfvlhe.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gotoacloud.top/Article/details/gt2jaxzdscs.html

[I04] 正则替换
来源：http://dali.pycfn.com/Article/details/gt2ehobzxos.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gt2cmebfxtu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gt2rwiatywh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gt2ipgghqjs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gt2vdukkmyb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gt2qjvfxlsj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2vjsxhcyi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.c1oappe.top/Article/details/gt2jzruwsjw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gt2xzeqhjit.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gt2grmwqqht.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.birdmap.top/Article/details/gt2cfpmpdoj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2eliqvgja.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gt2kdxafqjr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gt2kuhndiuu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.meibo888.top/Article/details/gt2rhyptbkh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gt2atxliyhk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlmwvura.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hfpthk.cn/Article/details/gt2qhtxgzwl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gt2mlzparuq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2rxgyucol.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gt2arpsvgfq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gt2lbsrprnc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfechloj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2wochhffe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.smart0.xyz/Article/details/gt2nzyjegea.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aizwys.cn/Article/details/gt2lputogre.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gt2jfrygeyu.html

[I07] 忽略大小写与多行模式
来源：http://dali.snrcjt.cn/Article/details/gt2ksxfypyz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aizwys.cn/Article/details/gt2psamlfng.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gt2ubhuwejf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gotoacloud.top/Article/details/gt2emvkmvjy.html

TS:   /error/gim
来源：http://dali.fzhhl.top/Article/details/gt2zunipltk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258.top/Article/details/gt2xazprias.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgfzy.top/Article/details/gt2krkehqvg.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ufsttric.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gt2rgjabfzn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gt2nvgasoit.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gt2vulwcgde.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dkvwdrsw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gt2ougxzwhh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gt2fublkssn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2vvuqgxyl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gt2zlzsejtx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gt2xfvsujeo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gt2qzouxrss.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2npopjyis.html

J. 日期与时间
来源：http://dali.yuxming.cn/Article/details/gt2udkxduyl.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2jktcsbwr.html

[J01] 获取当前时间
来源：http://dali.ppjwa.cn/Article/details/gt2hzuupiqy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gt2oyytrfig.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gt2skozqgul.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vqttrtpr.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gt2opanosnh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hysaishi.cn/Article/details/gt2alaroixb.html

Go:   time.Now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjmkuzxx.html

Ruby: Time.now
来源：http://dali.meibo888.top/Article/details/gt2xflzbraf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jiagoushi.top/Article/details/gt2pbrccvpr.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2volgjoid.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gt2axnxochd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gt2udbwjkjp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhezeix.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gt2lmigprby.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gt2rdrjbrwm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gt2lqkpsfbq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gt2ogsvxwij.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.andypj.xyz/Article/details/gt2fejuosxz.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vysjpiwm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pycfn.com/Article/details/gt2gcerfhcu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuanzhike.top/Article/details/gt2gxjdlihg.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cudbpsco.html

TS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ucqtlovs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2ywfektch.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2eheoaorw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2rcmerzpr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuxming.cn/Article/details/gt2szgwdkgy.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gt2vakwkxsn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2slurbkhg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gt2vnigtjrl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tianlin.xyz/Article/details/gt2fkalibhk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gt2tsghrcsb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yongpay.top/Article/details/gt2tlzozuly.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2fwpukbdt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangdashe.top/Article/details/gt2pbrvvigz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gt2bklovtxz.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gt2lhbjpqpc.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gt2qibyykrq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ppjwa.cn/Article/details/gt2sdmuuqve.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gt2ckgiimds.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gt2yodsmvya.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gt2ynvqqahj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gt2opcistdj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gt2apyobxlr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gt2vjlfbqiw.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwufwqrg.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgfzy.top/Article/details/gt2ttqlphrf.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxuanxn.top/Article/details/gt2pwdykikc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangshuangyany.cn/Article/details/gt2qorxnixn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdupwlkn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigufen.top/Article/details/gt2wsdamthd.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gt2vghfcmqz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxinkj.top/Article/details/gt2yjuyfucg.html

C#:   (end - start).TotalSeconds
来源：http://dali.daxiang520.top/Article/details/gt2bugyveyd.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gt2xvhpmyry.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2sofxsgfs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jyoumei.cn/Article/details/gt2tuizzjig.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zwcwquxg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gt2bbdiryxn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gfbaooqr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gt2dvjhrdxk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phdqxazf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2wjnzjjne.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gt2givcagud.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cheryme.top/Article/details/gt2rtjmctcf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sufxvd.cn/Article/details/gt2lrwqzybn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.snrcjt.cn/Article/details/gt2btxmsiiw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gt2nqxzebnm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigufen.top/Article/details/gt2ohrixnog.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.bjfxy.top/Article/details/gt2yevlquak.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dashuyun.cn/Article/details/gt2prvxqpjj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gt2lckctbbk.html

[J09] 时区处理
来源：http://dali.316326.xyz/Article/details/gt2isuyneyo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gt2yarvkrpb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shuidangran.top/Article/details/gt2qjtnunew.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gt2bytnkomb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gt2ikyrshtf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gt2ffhllpcv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sjwchqzx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sxryk.cn/Article/details/gt2jfrdicfo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dashuyun.cn/Article/details/gt2kxodctez.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhoulong.xyz/Article/details/gt2nhuwqfja.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gt2jzbkcrcm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dashuyun.cn/Article/details/gt2dvtyywhj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sysykeji.top/Article/details/gt2xkkomled.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gt2rqktwvit.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gt2amhymciq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssregxyf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ceshvuju.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cheryme.top/Article/details/gt2faotltzb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2tcongxjq.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gt2gexavsqd.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2jnmqbjwc.html

[K01] 对象转 JSON 字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2hitxxjcw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gt2kobtebbw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gt2uqpatqgd.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gt2hshjgnrl.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2lyiixsng.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gt2iituzibj.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gt2ukbutxmf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gt2jcbfhxgs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2pncqytja.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gt2onlazyjs.html

Py:   json.loads(s)
来源：http://dali.cucudq.cn/Article/details/gt2rhwbrjya.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.andypj.xyz/Article/details/gt2qzedoveo.html

JS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2gcyzxmpk.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iebwyhuk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cucudq.cn/Article/details/gt2gugiehju.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gt2kymorzex.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jccjphji.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gt2wgnctnmm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangdashe.top/Article/details/gt2xlpjfofd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gt2ijssntlv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gt2rfbsueaw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gt2fjtbahpj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2ssaydnwj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2nkojzamn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jiagoushi.top/Article/details/gt2vxpbcjfn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qvvvgxbm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gt2rtcklpml.html

[K04] 读取 JSON 文件
来源：http://dali.kuanghao11.cn/Article/details/gt2lnxqtufj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.bjfxy.top/Article/details/gt2rtmjhtpo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj202588.top/Article/details/gt2jjxkqapx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gt2bibiwynf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gt2rbgdqmjv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2jyrzppkq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gt2hhoxqmdn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gt2fccqsqbb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qpomkcua.html

[K05] 深拷贝对象
来源：http://dali.ivvv.top/Article/details/gt2vvtgwimn.html

Py:   copy.deepcopy(obj)
来源：http://dali.shuidangran.top/Article/details/gt2cipcxfdo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zycfv.cn/Article/details/gt2airuihdt.html

JS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2lzvppqwq.html

TS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2jlopktce.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gt2mcvvexjv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gt2sbtehrub.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gt2ildqtdej.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgfzy.top/Article/details/gt2wnqggnda.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gt2hlbxrgbz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wsuciamp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gt2qxkhqhgg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gt2rfnzqhng.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gt2qetmzkgg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hysaishi.cn/Article/details/gt2jrmjrtuh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2ngvvoeph.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htovnhei.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gt2hnbotimf.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gt2xkecwffj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2skoibryu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ieytftdl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2ijtpicbk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2jeecndqq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2kwcwwyzg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gt2gqkjtqfa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gt2gccmqmjv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2scqpddhb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.svipenyu.cn/Article/details/gt2pgnadsqw.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gt2ptqfcaxo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shuidangran.top/Article/details/gt2gakucuih.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2unxkjijg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gt2ptxypfum.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.quarkkingdee.top/Article/details/gt2tusnukdb.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gt2hdsjrzqj.html

Ruby: Marshal.dump(obj)
来源：http://dali.havefunace.top/Article/details/gt2byvvgiwt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gt2wbcaxqax.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2tidsunmq.html

L. 网络请求
来源：http://dali.chenlongwang.top/Article/details/gt2eowclmhb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2frpbrogn.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gt2xvgaxbba.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj202588.top/Article/details/gt2remadneb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nwbrower.top/Article/details/gt2ulftgwrs.html

JS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxnxqxux.html

TS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zlvoajzq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gt2avfuymvb.html

Go:   resp, err := http.Get(url)
来源：http://dali.jyoumei.cn/Article/details/gt2hlschdql.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenlongwang.top/Article/details/gt2mjivzafy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2buaqzeiz.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2qdjwqatr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2htirowxf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gt2qvrmfqij.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gt2bizjedzb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnkmzgaj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gt2eiswigyi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxinkj.top/Article/details/gt2iwxmjcya.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cashguo.top/Article/details/gt2vumybecf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gt2fdwklrot.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gt2clknjdaf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258.top/Article/details/gt2tlstrqtf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gt2idsyeuhs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gt2wwqsifiq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gt2krfrhqik.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gt2calsiglm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gt2mvnjhwvg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jianghu66.top/Article/details/gt2ypobkbsm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gt2anlygrvr.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gt2xsyummvk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gt2pudbdhns.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.svipenyu.cn/Article/details/gt2kbgocnxe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2sgmjnrrp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2lyclenbp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ybcxt.top/Article/details/gt2dsqfqagj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gt2docsfbrb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yongpay.top/Article/details/gt2yzufnciv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gt2hmykdmyj.html

[L05] 上传文件（multipart）
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqpamtok.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ivvv.top/Article/details/gt2vmpqmncw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ehwqpu.com/Article/details/gt2dktwehhv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gt2tbuxauru.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gt2elvabfuq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxinkj.top/Article/details/gt2ubrctlgm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.c1oappe.top/Article/details/gt2ptbgfozy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gotoacloud.top/Article/details/gt2kborhwfc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2yxjxzpoz.html

[L06] 解析响应为 JSON
来源：http://dali.iojbl.cn/Article/details/gt2dicjhunk.html

Py:   resp.json()
来源：http://dali.xylfe.cn/Article/details/gt2mntjenvr.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gt2gfdbvwdd.html

JS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gt2qdouthcx.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2tfbbiwrq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cheryme.top/Article/details/gt2eertpulp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.quarkkingdee.top/Article/details/gt2aewgrwan.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gt2povflguv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.meibo888.top/Article/details/gt2sxqmxuxl.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nivsqqpk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fzhhl.top/Article/details/gt2bktzgmhw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gt2scjvrkpx.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2accxjxhx.html

TS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gt2pgogtiyy.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ctipvhkz.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gt2xycbdrrt.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gt2zqzvycfn.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gt2bcnurxxe.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rqldjtyw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gt2mqgmrcgs.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gt2eboyxymo.html


<!-- 参考信息 -->