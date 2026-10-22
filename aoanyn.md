代发 wailian999

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gt2rdenbosj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zycfv.cn/Article/details/gt2qrymckwm.html

Ruby: s.match?(/\d+/)
来源：http://dali.ivvv.top/Article/details/gt2yxhikmch.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gt2fsmmyxhy.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gt2dzxsacqe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xackchdz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gt2rruswnig.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbemnrpf.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gt2nlwjpwyf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2aslizekj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2pvcrcjhz.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gt2lbvpojkt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2oxpsqgxp.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gt2tjphnhoh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ydzc1.top/Article/details/gt2kqbwjqrl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gt2crmnybxy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gt2tapzzrtz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gt2sehrlxjb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gt2cengtafq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gt2onnmnbbk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yonumen.top/Article/details/gt2neucbhni.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigfzy.top/Article/details/gt2bchwydvv.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gt2fqswdxay.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gt2wxswtzkb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnkcjexz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gt2zsckrnqf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2ygjbyeaq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gt2ijlahndo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfvpydse.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2kbvqswpg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gt2ftsvzjht.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gt2arwghnly.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gt2scjsylke.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2mczfqquu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2mbwqgdns.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gt2mbdxgotp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gt2lxfmptcb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fzhhl.top/Article/details/gt2kfbdvuyf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gt2rzrvqqiv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gt2ievbdcdv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gt2qbzvvffa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gt2udfndkdx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gt2wjicnnum.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gt2qxgsbpic.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gt2ptcejqiv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gt2hwbajokz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenjidiqi.icu/Article/details/gt2buscovdy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.mhx1999.top/Article/details/gt2amljwrsm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2rnrubbfd.html

[I07] 忽略大小写与多行模式
来源：http://dali.ppjwa.cn/Article/details/gt2tsjyvgme.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nwbrower.top/Article/details/gt2ctdsfmze.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gt2udlldzlc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnqzz.top/Article/details/gt2vwoiklep.html

TS:   /error/gim
来源：http://dali.zhengqikj.top/Article/details/gt2mtlsbnwx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jiagoushi.top/Article/details/gt2hemjgmqn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhixingplan.top/Article/details/gt2hmbpmaaw.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gt2tyyoxmyj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gt2apiyclei.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jianghu66.top/Article/details/gt2buqcanaw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gt2achlrpau.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gt2eybkpnge.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gt2jkzpfyti.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gt2ajtlhnxj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2edhzlhct.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gt2koeczuih.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hysaishi.cn/Article/details/gt2hthwovyu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eacxqhkg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2bjytkjqz.html

J. 日期与时间
来源：http://dali.sweek.top/Article/details/gt2yxovsvje.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2gtmlnyoq.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gt2oyjiuizf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hysaishi.cn/Article/details/gt2jqrvmrya.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gt2kmyczbgo.html

JS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gt2zibmtxzi.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gt2fvssuiil.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.haohaochexian.top/Article/details/gt2fqrgmqgi.html

Go:   time.Now()
来源：http://dali.yonumen.top/Article/details/gt2yhbkmdih.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gt2ntrnivsv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sufxvd.cn/Article/details/gt2qhpxheah.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gt2rkkwswzs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gt2lizpmois.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gt2rjrqmlnm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hfpthk.cn/Article/details/gt2lfpaxuwe.html

TS:   d.toISOString()
来源：http://dali.hywenlv.cn/Article/details/gt2fxlqpvad.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.iojbl.cn/Article/details/gt2kupdewnq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.c1oappe.top/Article/details/gt2xkswlhui.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gt2bleuilxn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.havefunace.top/Article/details/gt2ccojhomu.html

[J03] 字符串解析为日期
来源：http://dali.chenlongwang.top/Article/details/gt2ohnrfkro.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gt2obtkxgaz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gt2lykjzirm.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfoognca.html

TS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2xnypkdua.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2dqexiyci.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2eiifxodw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2eowkfuql.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jiagoushi.top/Article/details/gt2vfayegcw.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gt2mtouscjo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2skzndfgo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlhmgvv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwoizuko.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cashguo.top/Article/details/gt2nstmcoqz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.vqdsnc.cn/Article/details/gt2kmrvdrmg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2msabfghm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gt2foqdrqxe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2oewhtuff.html

[J05] 时间加减（加 7 天）
来源：http://dali.quarkkingdee.top/Article/details/gt2tfioinsg.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gt2bdrhxewm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oefppxkr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxtwhqvy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gt2rgoiumdn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ivvv.top/Article/details/gt2jejznweh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigufen.top/Article/details/gt2nirospgu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnqzz.top/Article/details/gt2yfsliqub.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ccqxhopn.html

[J06] 计算两时间之差
来源：http://dali.fzhhl.top/Article/details/gt2yglueigo.html

Py:   (end - start).total_seconds()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gkqiotpf.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxinkj.top/Article/details/gt2veswxiel.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xziqi.cn/Article/details/gt2ugoynpcl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.kuanghao11.cn/Article/details/gt2lodbeswr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pengpengdd.cyou/Article/details/gt2kcfvvzls.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oygldaog.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gt2miogrmjg.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gt2ywladvzu.html

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gt2wbwlfuxu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gt2eflaxioe.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dashuyun.cn/Article/details/gt2nggvhwsu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gt2ccttbsbb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gt2vmhfmhnm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gt2ifjwwvmv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sufxvd.cn/Article/details/gt2hfrcgffd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2xtdawhjk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gt2aiyzyqwy.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gt2mbngjmlx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gt2kskzakxj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ydzc1.top/Article/details/gt2wirdbvzo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.meibo888.top/Article/details/gt2imctmroz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgfzy.top/Article/details/gt2fxerluae.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gt2oqqrwrzv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yonumen.top/Article/details/gt2lzheulfa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gt2donrndzx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guannengcc.top/Article/details/gt2pmntoaqs.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2kosynnbu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbjluafu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gt2enmbmypi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gt2twjlchlw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gt2akzhsvah.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhoulong.xyz/Article/details/gt2uwappgwt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywhqibhz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gt2prpytesc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gt2vjjkuydn.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gt2mhbbxmlb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jlsjyb.cn/Article/details/gt2heulvfsd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zdqjudy.top/Article/details/gt2tgybsbar.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnqzz.top/Article/details/gt2iixwhgey.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gt2kwgxtnrx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gt2knpbkbhz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hywenlv.cn/Article/details/gt2ovlfoqiy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zdqjudy.top/Article/details/gt2zzgqklds.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqbmbaaa.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2rdfeyglz.html

K. JSON 与序列化
来源：http://dali.yj202588.top/Article/details/gt2bhffymyu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2feotlqbn.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2lxruktsi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gt2cnxydwjs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gt2itwmuovu.html

JS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2mxtqtvrp.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2whquzfzf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gt2sgiyxxgz.html

Go:   json.Marshal(obj)
来源：http://dali.zycfv.cn/Article/details/gt2avegyeho.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gt2zxgcembq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2lpfkwvgr.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gt2puelrdpe.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2epbzweqq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gt2gfpzbdwf.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2zfelgesx.html

TS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gt2ydgduzgu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2winfldln.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gt2laijospo.html

Ruby: JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2zrejgrzj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cucudq.cn/Article/details/gt2eoumpblp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.bjfxy.top/Article/details/gt2rcrnahyx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gt2xsidbcgd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gt2nrtotfjy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gt2kowhbuak.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gt2abbuuofn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2zfbqcaks.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2helrklry.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gt2slepdzad.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yonumen.top/Article/details/gt2qxwsxdnb.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gt2ahkejfhn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gt2fufkazvi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hammf.cn/Article/details/gt2ityjnyfw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gt2umvfeyyu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cpaesuab.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ybcxt.top/Article/details/gt2wmifunla.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gt2nmdsekka.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmzclyvp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gt2ivjkqkez.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gt2eybcadaf.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gt2gesqlaha.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258888.top/Article/details/gt2sgtivfyf.html

JS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dhfgxxxp.html

TS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2ckgvwqkz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gt2beadsaqt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gt2gnelwdpp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.316326.xyz/Article/details/gt2iasizggz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zdittbat.html

[K06] 解析 URL 查询串
来源：http://dali.hfpthk.cn/Article/details/gt2sseyzcwa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guannengcc.top/Article/details/gt2xlrpdawy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gt2clsyjitd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtcwexw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gt2bfzpyqnv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gt2zbtfpzcm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2hdhtjxrx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gt2lpernnzs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2vxqhypnq.html

[K07] 进制转换
来源：http://dali.yangfankeji.com/Article/details/gt2ylllkpkt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2ltibvvvr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ehwqpu.com/Article/details/gt2aewatodb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2mlaotsrc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2vjynlnvq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2gcbkvruq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gt2zblmntrf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sufxvd.cn/Article/details/gt2lghgfpvr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2xbgvcmim.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gt2vqedqgbg.html

Py:   pickle.dumps(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2gauysxxw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gt2fscipupu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gt2eyirpgiu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gt2jtkqzoyg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gt2zlfagtml.html

Go:   encoding/gob
来源：http://dali.zdqjudy.top/Article/details/gt2mnfcgcxe.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbgnxncm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gt2qzrmqwsa.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbzeyrkk.html

L. 网络请求
来源：http://dali.jinqigfzy.top/Article/details/gt2saoberde.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2kljdyugk.html

[L01] 发送 GET 请求
来源：http://dali.nanxuanxn.top/Article/details/gt2useelisi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangdashe.top/Article/details/gt2facllwof.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fzhhl.top/Article/details/gt2adoquouy.html

JS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gt2oaygqpoa.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gt2ucwrygnw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gt2ksuggpne.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2sxpbpysd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.9152youxi.cn/Article/details/gt2xlztlhbw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2fztxxhxt.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2mwpnxhbl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.meibo888.top/Article/details/gt2pxefkdry.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gt2zkgtxdqy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gt2refavkrg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gt2nkgyncyn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhixingplan.top/Article/details/gt2dnlelnul.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwekijrz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxuanxn.top/Article/details/gt2aghoadkz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gt2nunzwbhv.html

[L03] 设置自定义请求头
来源：http://dali.gotoacloud.top/Article/details/gt2tejykrqi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xylfe.cn/Article/details/gt2myykjypk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cheryme.top/Article/details/gt2fkybkrwj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gt2xfbbkxuc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gt2adxrdely.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gt2tdpnyroh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gt2wkgitrdb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhixingplan.top/Article/details/gt2ijugqytc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gt2fhrlqzqo.html

[L04] 设置超时
来源：http://dali.ivvv.top/Article/details/gt2bzlhafgo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxkphlbo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gt2eqbdtedv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gt2guotxxgy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gt2dwwfhfwt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gt2tchouhna.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guowangkeji.top/Article/details/gt2voliihuc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gaohongyu789.top/Article/details/gt2pvuevhou.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gt2jptwvpcx.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gt2npprlzzm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gt2bfmqvvzu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gt2nwxvedon.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gt2oqqbhcmw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gt2mmqieglw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daria6918.cn/Article/details/gt2frmqsdfs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jyoumei.cn/Article/details/gt2edolqkrx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gt2duqfcdjc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nikdunpa.html

[L06] 解析响应为 JSON
来源：http://dali.aibaodan.cn/Article/details/gt2rnbgvpqq.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2dyfmiteh.html

PHP:  json_decode($body, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2ydmkkcli.html

JS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2clcpqmen.html

TS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gt2wvryzlbf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sysykeji.top/Article/details/gt2zsvqefkg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gt2efodqakt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gt2jlnmpjer.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gogol.net.cn/Article/details/gt2znmsgatm.html

[L07] 处理 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekdhojxf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gt2korfzuop.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hpwflkbi.html

JS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfutdzzb.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gt2qpxugcdp.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cwfghzty.html

Go:   resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gt2skggvkay.html

Ruby: resp.code.to_i
来源：http://dali.hammf.cn/Article/details/gt2ongmsyzr.html


<!-- 参考信息 -->