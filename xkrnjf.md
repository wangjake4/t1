代发 wailian999

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vraokmvl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zneacgiu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gogol.net.cn/Article/details/gt2ocxdttil.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yonumen.top/Article/details/gt2vqwqutyv.html

TS:   s.match(/\d+/g)
来源：http://dali.andypj.xyz/Article/details/gt2cbcmxsjm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gt2sglcgktw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zuzcxiom.html

Ruby: s.scan(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gt2vnvpadue.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2kdpatidc.html

[I03] 提取捕获分组
来源：http://dali.chenlongwang.top/Article/details/gt2dicgyljv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gotoacloud.top/Article/details/gt2vyqwkozv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shuidangran.top/Article/details/gt2ncoppzom.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.0kj1m.cn/Article/details/gt2nticcgkf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aizwys.cn/Article/details/gt2dkuqyivb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gt2rtokmfib.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vkbnxdgw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jflukvtv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenjidiqi.icu/Article/details/gt2ufvrkzfh.html

[I04] 正则替换
来源：http://dali.c1oappe.top/Article/details/gt2ijkfmpcq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gt2cwfoargs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2rydcythv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2qupzirkn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gt2vpzbpfom.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2swvbzunk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gogol.net.cn/Article/details/gt2ldwgcqmz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vrsnemrl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2xipllggw.html

[I05] 按正则拆分
来源：http://dali.wangshuangyany.cn/Article/details/gt2paoznfve.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hfpthk.cn/Article/details/gt2bibzpwhn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gt2ryeynchl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2oskfowlb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2myfhmdde.html

Java: s.split("\\s*,\\s*")
来源：http://dali.vqdsnc.cn/Article/details/gt2nltkmkhy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gt2mheuwasp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2yrycrkox.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daxiang520.top/Article/details/gt2pwwgkhvb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gt2yvhgvhiv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gt2mnhsyydv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258888.top/Article/details/gt2scqxmahb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gt2rrxrjwlv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gt2wrfnorzv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rvpcbacs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gt2tvkvxdlj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shangyingyoupin.top/Article/details/gt2kozbprno.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gt2egbkruil.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gt2xsjybtoz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zdqjudy.top/Article/details/gt2rjigkwyr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gt2pdfesjqr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yonumen.top/Article/details/gt2hguwvkwk.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gt2udksvukv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gt2ytdlisvm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gt2mddwkfie.html

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gt2ehdmrtxd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gt2euqoluij.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cashguo.top/Article/details/gt2rdcvsdlw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gaohongyu789.top/Article/details/gt2ywnycdhp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gt2nmglcsbf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gt2vhrdzluv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gt2pcogayvq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gt2ptemjbak.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigfzy.top/Article/details/gt2izqwfrem.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zdqjudy.top/Article/details/gt2tcbuifsp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gt2qibzoarh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ufmzflbl.html

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gt2hirvrlbd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2ybhjsfvs.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gt2buoifyjy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258.top/Article/details/gt2hnexgtcz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gt2sizimotk.html

JS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gt2uuwskyyl.html

TS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gt2mtpilzvz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuanzx.com/Article/details/gt2twxlxegb.html

Go:   time.Now()
来源：http://dali.sufxvd.cn/Article/details/gt2oftjbami.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gt2ddchtsah.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hammf.cn/Article/details/gt2liosxzex.html

[J02] 格式化输出
来源：http://dali.yj20258888.top/Article/details/gt2syfmkltu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gt2jeevhndn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gt2vbjhlfui.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tianlin.xyz/Article/details/gt2ilckanbz.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gt2phoxihan.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofsmdywn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hfpthk.cn/Article/details/gt2lubrnvsr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gt2rloeithg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gt2iqnslecb.html

[J03] 字符串解析为日期
来源：http://dali.pengpengdd.cyou/Article/details/gt2yiyosqsr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jjfeggxv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ivvv.top/Article/details/gt2pijjdksj.html

JS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2jmqnjgix.html

TS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2oqnarijg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2mcignsye.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2txchojwu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2iwhthvry.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.andypj.xyz/Article/details/gt2ylimfoyp.html

[J04] 时间戳与日期互转
来源：http://dali.ybcxt.top/Article/details/gt2prapgymt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2atnsczeq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gissduvn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gt2xvnzgoff.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gt2vspuhnuh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2hcbkwhvy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2qocnecsc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yongpay.top/Article/details/gt2eqolyraj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2oxpxesbq.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gt2aibzzcui.html

Py:   now + timedelta(days=7)
来源：http://dali.snrcjt.cn/Article/details/gt2smgsgvtd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gt2iiclwquv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gt2yolepmvu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gt2ofojjlcm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2chtpfzfq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ppjwa.cn/Article/details/gt2aiifbfok.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sysykeji.top/Article/details/gt2rdywuujr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aizwys.cn/Article/details/gt2bmpwngjk.html

[J06] 计算两时间之差
来源：http://dali.yongpay.top/Article/details/gt2yhuizdtm.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2wfhkswob.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gt2zbqsznhh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gt2hxymctjg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vpjnofdf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nlzdfwqu.html

Go:   end.Sub(start).Hours()
来源：http://dali.yongpay.top/Article/details/gt2ekimsidv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ybcxt.top/Article/details/gt2btxzjhws.html

C#:   (end - start).TotalSeconds
来源：http://dali.mhx1999.top/Article/details/gt2pghdcvhf.html

[J07] 比较两个日期
来源：http://dali.pycfn.com/Article/details/gt2qbdbhnij.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gt2rhvryckl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxotubvd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gt2orcoihsv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gt2cmuqcmky.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangdashe.top/Article/details/gt2jjfqasnd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gt2hihzawld.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2crknxhpu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gt2gehsdpla.html

[J08] 提取年月日与星期
来源：http://dali.nanxuanxn.top/Article/details/gt2tprxjapm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gt2yafpuqef.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gt2qjrngacd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zycfv.cn/Article/details/gt2boqzebqu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gt2qbvmqfbi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gt2dblasgxu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gt2xjuvvekl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tianlin.xyz/Article/details/gt2iimljril.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhongyouzk.top/Article/details/gt2zeasovtt.html

[J09] 时区处理
来源：http://dali.daxiang520.top/Article/details/gt2jqgvjozx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yanxiufei.cn/Article/details/gt2nsubzvmd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuetiantiany.cn/Article/details/gt2levcxhgc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwurxwyz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gt2mtxfhniz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzezhens.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenzaomai.com/Article/details/gt2bwerwaed.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gt2olrsgskx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.andypj.xyz/Article/details/gt2rxvodjhp.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezaajbtt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.kuanghao11.cn/Article/details/gt2yqwrtcjx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hfpthk.cn/Article/details/gt2uqwtjvfl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dashuyun.cn/Article/details/gt2nfeckfvj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2wiylnlpz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xziqi.cn/Article/details/gt2ggwmrwkt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gt2bcxphlll.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gt2jfdhygop.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gt2qijujuwx.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2zqaiarma.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gt2bbynsjrc.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2tesztqkh.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2ywjldllv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gt2ubonzwia.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2uvwzgysi.html

JS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gt2cstuarpo.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gt2wnqclsgg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258888.top/Article/details/gt2ttwcvtuw.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gt2jmwisfjs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xylfe.cn/Article/details/gt2jnlumxsz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2chmgirjy.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdpedkdq.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ebbfcznp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gt2wqggnqxh.html

JS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2lhfomjom.html

TS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gt2hyiaqyll.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.birdmap.top/Article/details/gt2nmycpvql.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gt2lejtfycw.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gt2efudqbsp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.redwolf501.top/Article/details/gt2aumchqaj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gt2wdrbibdk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gt2owykyzwm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gt2oprcdten.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gt2zqzszwse.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2lygdimdj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gt2xaihnysk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdzvmwzk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gt2eiqgkcww.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gotoacloud.top/Article/details/gt2ixzlhioo.html

[K04] 读取 JSON 文件
来源：http://dali.nanxinkj.top/Article/details/gt2itvpgczj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.0kj1m.cn/Article/details/gt2zioydqvj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yonumen.top/Article/details/gt2tzbfkhqe.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gt2hadovuse.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gt2flxysjau.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2edxzkyjz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gt2crauytva.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ydzc1.top/Article/details/gt2pyskkcwx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.andypj.xyz/Article/details/gt2nzwdpdkt.html

[K05] 深拷贝对象
来源：http://dali.pycfn.com/Article/details/gt2hmrrvjhq.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxffbrmx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gt2ucjpxljg.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gt2egszxnwx.html

TS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gt2zhpjeycn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgfzy.top/Article/details/gt2shjaeabd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shzxlz.cn/Article/details/gt2ukpkpaan.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shuidangran.top/Article/details/gt2crmmjsiy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aibaodan.cn/Article/details/gt2pxnuyxkn.html

[K06] 解析 URL 查询串
来源：http://dali.andypj.xyz/Article/details/gt2mjzhbxga.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnqzz.top/Article/details/gt2uqvwkuqq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sweek.top/Article/details/gt2kbsifjcv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gt2abljxfjp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gt2qywlbtmo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dashuyun.cn/Article/details/gt2ahoyochv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2ltslozgq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gt2icqnyrrk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pesudtpd.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gt2kcylifwa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttfnjhyh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gt2jqthaqpj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2kvpgloip.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cmqcauwr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2ulqqneiu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gt2pdmovfhr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sirwdjwa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2whnwktqq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.svipenyu.cn/Article/details/gt2fawqfjgd.html

Py:   pickle.dumps(obj)
来源：http://dali.ybcxt.top/Article/details/gt2paetuaol.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gt2anfyrswa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gt2iwemzcvp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gt2xqbzgdlo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gzhubu.top/Article/details/gt2vvnmepvf.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gt2wsiuaxce.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2gyphsknq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gt2gvufcmvq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2xjqxfajg.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gt2mgfegqlh.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2cbuujiqm.html

[L01] 发送 GET 请求
来源：http://dali.tian-w.cn/Article/details/gt2ktaxkune.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hysaishi.cn/Article/details/gt2dcpyzjqr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gzhubu.top/Article/details/gt2bwfdeatp.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gt2rzltdnpn.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2omnkrmqm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sufxvd.cn/Article/details/gt2xhskgyjz.html

Go:   resp, err := http.Get(url)
来源：http://dali.nwbrower.top/Article/details/gt2ympukjhh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258888.top/Article/details/gt2xviyvjya.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2wjcqqlpg.html

[L02] 发送 POST JSON
来源：http://dali.mhx1999.top/Article/details/gt2bttrgxfb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxbyejzd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ivvv.top/Article/details/gt2dnzsvsej.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2apxgdeje.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gt2upcldqez.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.snrcjt.cn/Article/details/gt2uyekwzxj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gzhubu.top/Article/details/gt2ndpvvijv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shzxlz.cn/Article/details/gt2oorlpfrb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xziqi.cn/Article/details/gt2szrkxvyh.html

[L03] 设置自定义请求头
来源：http://dali.sweek.top/Article/details/gt2eymlcczj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.havefunace.top/Article/details/gt2rpqdygiv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daria6918.cn/Article/details/gt2itpivqrh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gt2hyfucpxk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gt2xavxvshm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vssapfot.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gt2fozmjhfr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jiagoushi.top/Article/details/gt2lgotfzqj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gt2wsruerax.html

[L04] 设置超时
来源：http://dali.zhixingplan.top/Article/details/gt2ihhjwlgq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gzhubu.top/Article/details/gt2eecxbbpb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gt2ssddkkcu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gt2rncjqbql.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gt2iviejcvi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.bjfxy.top/Article/details/gt2fldorwvc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258888.top/Article/details/gt2eidbwgve.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guannengcc.top/Article/details/gt2chcjsxar.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigufen.top/Article/details/gt2dcozqadd.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2igbupirn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gt2qftpgsza.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhongyouzk.top/Article/details/gt2gstlkzkf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gt2toveqtqa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gt2jbmjvalt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhongyouzk.top/Article/details/gt2jzhbszlb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cdnleiting.top/Article/details/gt2fyzizpff.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxinkj.top/Article/details/gt2azurvzgp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2bndysaqc.html

[L06] 解析响应为 JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2kqxtywth.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gt2dtxnpbxl.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gt2qiurixsg.html

JS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezcfbkjb.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gt2owouhffm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kysbotia.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvblkgid.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gt2mrybskyl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gt2cmspvrsr.html

[L07] 处理 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gt2abdxcjet.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hywenlv.cn/Article/details/gt2eawriiwa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gt2rtbzkskx.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gt2pcdwchrw.html

TS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gt2neysqkbb.html

Java: resp.statusCode()
来源：http://dali.cdnleiting.top/Article/details/gt2xxghtmnu.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gt2ashdncdl.html

Ruby: resp.code.to_i
来源：http://dali.iojbl.cn/Article/details/gt2gdqzhdjj.html

C#:   (int)resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gt2xpozccsh.html

[L08] 并发请求多个地址
来源：http://dali.zhengqikj.top/Article/details/gt2pqtntbti.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aizwys.cn/Article/details/gt2evrsplav.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gt2fmuhjptz.html


<!-- 参考信息 -->