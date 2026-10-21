代发 wailian999

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gtvzkghyiw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ehwqpu.com/Article/details/gtkvdfqhze.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtcfhkblsu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ehwqpu.com/Article/details/gtmvtnnlqd.html

[I02] 提取所有匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtazfdzstl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gtrunxyzjn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahmyagmo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cdnleiting.top/Article/details/gtlzogpxci.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gtjhmftacf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gtyrrhwxxn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.meibo888.top/Article/details/gtzpcvynqw.html

Ruby: s.scan(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtanylzjsh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jianghu66.top/Article/details/gtbfulxmqt.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzphkztgu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gogol.net.cn/Article/details/gtiwmzpjct.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.316326.xyz/Article/details/gtpvkfkxvy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gtklahieih.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gtbkxaovhr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlupanowr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gtmaftimfo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gtkagzyjnk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ppjwa.cn/Article/details/gtuqfozose.html

[I04] 正则替换
来源：http://dali.dashuyun.cn/Article/details/gtkfyckdsb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gtsqhihmny.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtwxhadsiv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtteutpzzj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtnynykjlr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwgucrlt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gtzopjcqtw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgfzy.top/Article/details/gtvxmjaihe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gtclebpjce.html

[I05] 按正则拆分
来源：http://dali.iojbl.cn/Article/details/gtvwtnlqzh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gtinuzqslp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtwiynwoyp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtklcopufr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtswiovvky.html

Java: s.split("\\s*,\\s*")
来源：http://dali.vqdsnc.cn/Article/details/gtddqhgcxb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gterjpnosy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtwcgfkdbx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gtyqzncoyb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gtzdyiwdyg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gttbtpqdgg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sweek.top/Article/details/gtamkmvqcr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtqtvohqar.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtlfeztups.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtzxfnqltt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxuanxn.top/Article/details/gtehczhvgj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gotoacloud.top/Article/details/gtnqtsdwyw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtofmpxpvy.html

[I07] 忽略大小写与多行模式
来源：http://dali.yongpay.top/Article/details/gtdnxacnsf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jiagoushi.top/Article/details/gtytccacpa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtjdexyytk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jlsjyb.cn/Article/details/gtcsinkxbu.html

TS:   /error/gim
来源：http://dali.shanyushiyangkeji.top/Article/details/gtselyapvc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gtyqnbixci.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gtvbdegict.html

Ruby: s.scan(/error/i)
来源：http://dali.kuanghao11.cn/Article/details/gtexdakxdo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tanke756.top/Article/details/gtdnjwqkgf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gtgzhidoqp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gtwgxatfgp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtqdqpiayr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtwmrmqvrw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtgttbyspd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gtwwvdesxr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gtvsscfzsu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gtojenrgeo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gtshdkzzdn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyrzwgab.html

J. 日期与时间
来源：http://dali.kuanghao11.cn/Article/details/gtjxvzpsbc.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtyehgeyrs.html

[J01] 获取当前时间
来源：http://dali.xylfe.cn/Article/details/gtpihfgopf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhiwuduotai.top/Article/details/gtzzmgavms.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtoahddgfr.html

JS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gtdrmoqlbl.html

TS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gtfoycdgfp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gtyvtgxlhr.html

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuoghooh.html

Ruby: Time.now
来源：http://dali.guowangkeji.top/Article/details/gtfixqqgau.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jiagoushi.top/Article/details/gtapdnecoo.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtsupvbgou.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gtquihkdxj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtcuqfyhhb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ehwqpu.com/Article/details/gtfuwapubq.html

TS:   d.toISOString()
来源：http://dali.haohaochexian.top/Article/details/gtdqdlcboz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gtubpbxagu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnqzz.top/Article/details/gtzdhlwiqg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtrfnjwglj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshcgstky.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gtiodgnahs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cdnleiting.top/Article/details/gtziuywvqt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hfpthk.cn/Article/details/gtlzxjhycc.html

JS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtqgkmeaub.html

TS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtqedagmrd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtzeaoylcx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtmeqcttry.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtynktxrfh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.havefunace.top/Article/details/gtdmoxdwnw.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gtxrqqvukx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtnvupotsj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xylfe.cn/Article/details/gtkoetlpfv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hfpthk.cn/Article/details/gtzzkvmsze.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gtizxyszku.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtnydeskzg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gtatyxwpdc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gttsfyhaag.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gtsldfejmd.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuetiantiany.cn/Article/details/gtherrwqkk.html

Py:   now + timedelta(days=7)
来源：http://dali.nwbrower.top/Article/details/gtblovmaqa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.c1oappe.top/Article/details/gtmqsknmcy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gttpkusgdz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gtvjkukoca.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gtcrvmoklh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sufxvd.cn/Article/details/gtminvaqvt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthyoerbof.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gttfdqyuiw.html

[J06] 计算两时间之差
来源：http://dali.yj20258.top/Article/details/gtdufqzpcg.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtbopfuviv.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gtuhyqfusb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangtech.top/Article/details/gthwiwoado.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangshuangyany.cn/Article/details/gtqtquczsc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.0kj1m.cn/Article/details/gtxmlrjwwk.html

Go:   end.Sub(start).Hours()
来源：http://dali.tanke756.top/Article/details/gtvzcfcwoc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gtkraungnr.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gtovcntggl.html

[J07] 比较两个日期
来源：http://dali.shuidangran.top/Article/details/gtkghximgx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtxscrsbte.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hysaishi.cn/Article/details/gtndyfhpqc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtfewursau.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtsmhclfvy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcptpgbw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.svipenyu.cn/Article/details/gtwrcuoaad.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gteieogldv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtirbitbjo.html

[J08] 提取年月日与星期
来源：http://dali.hnqzz.top/Article/details/gtxpdqfzei.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gtdqnfsksz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgfzy.top/Article/details/gtbeteafml.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.feifeiyinyue.top/Article/details/gtwtxkkbpo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gtueydnmoa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258.top/Article/details/gtzllohdss.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gtiisnojel.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgufenzy.top/Article/details/gtwrhlbwmr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gtwmwohxrm.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gtgbtajujc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnxiangtu.top/Article/details/gtkneoifty.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gtvnzrmlak.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtoyhfxhdu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gtlsgvdxex.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gtcnpzbnhs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gtocqyqrgt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuanzx.com/Article/details/gtkjsctnel.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxinkj.top/Article/details/gtestwautz.html

[J10] 取今天 / 本月第一天
来源：http://dali.shuidangran.top/Article/details/gtepcftvho.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gtzhfnfqis.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhoulong.xyz/Article/details/gtyunvkgbr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtlzmnmpfk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ivvv.top/Article/details/gthzjucdnn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gthwjtscvb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gtcmducfjh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gtspechwfh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gtjptpfkbo.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtkpjlugno.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gtjcqdznyd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtngjptbmm.html

[K01] 对象转 JSON 字符串
来源：http://dali.yonumen.top/Article/details/gthvuezdds.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtqsvheknl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtsztgvbfz.html

JS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtzysnasss.html

TS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtwernmcwm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cheryme.top/Article/details/gtlwsewhbl.html

Go:   json.Marshal(obj)
来源：http://dali.jqgfzy.top/Article/details/gtuoxmwqhp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenjidiqi.icu/Article/details/gtegwtacqm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gtkbnkpuje.html

[K02] JSON 字符串转对象
来源：http://dali.ydzc1.top/Article/details/gtpmtqhvte.html

Py:   json.loads(s)
来源：http://dali.yj202588.top/Article/details/gtgpehacwx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fengsongda.top/Article/details/gtcpkircii.html

JS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtsawamvcd.html

TS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtdqdmfaco.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtlupsmngk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gtqgofpmxz.html

Ruby: JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtqmpviatt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyuqqkwa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gteydmcnsg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtrzbmfntu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtziggeqlx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtsevvabis.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtydmfalld.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtnayockfo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gtsgupwyne.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258888.top/Article/details/gtmdwdnewb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gtgrujspun.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsczdyxx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhoulong.xyz/Article/details/gtjjpobtea.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgufenzy.top/Article/details/gtedzffvcn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtpjcluvgd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtierpvlxd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtplufuywn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtmspjoflo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daxiang520.top/Article/details/gtnyzvwgjf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtmcnzlmkq.html

[K05] 深拷贝对象
来源：http://dali.svipenyu.cn/Article/details/gtrwumzvzt.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenlongwang.top/Article/details/gtvmyxtgep.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhengqikj.top/Article/details/gtksinurxs.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtyzetdzpz.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtwibsucnm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shuidangran.top/Article/details/gtojlbenns.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgufenzy.top/Article/details/gtxytketxl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqunwlxl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gtmpacurzf.html

[K06] 解析 URL 查询串
来源：http://dali.guowangkeji.top/Article/details/gthxonclss.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtpevotlpy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuxming.cn/Article/details/gtdxphrrsv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gtwbsouhxn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtvzcojipi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guannengcc.top/Article/details/gtkynzlmod.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtmqnakfyk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtgocbhceg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtxazwqrzk.html

[K07] 进制转换
来源：http://dali.sweek.top/Article/details/gtnvafdklo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtmnlqadzs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.kuanghao11.cn/Article/details/gtyebdrwso.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtirivjkls.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gteszlumeq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtcrahpjiz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfasgjbyn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtlelxtlir.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtiwizbjgj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gttqqbhdmq.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gtaaaouwop.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnxiangtu.top/Article/details/gtzglkauhb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtbnruvkud.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtrqkheyqe.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gtbjzwmanz.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gtciqurtvv.html

Ruby: Marshal.dump(obj)
来源：http://dali.zdqjudy.top/Article/details/gtpzdrzjzi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtoexqpxwu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtfddrsqwl.html

L. 网络请求
来源：http://dali.yj20258888.top/Article/details/gteeoeujfp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfcidkpt.html

[L01] 发送 GET 请求
来源：http://dali.gogol.net.cn/Article/details/gtvxanapbc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gtgmwsgoue.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gtscysblnp.html

JS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gtaxymkkxd.html

TS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtrlqpopnh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxuanxn.top/Article/details/gtjjkpoqrc.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gtdfqsnzmi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gtzsxueffc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtybjfnnpu.html

[L02] 发送 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gtxkzjafpm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gtlgazmrjd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhixingplan.top/Article/details/gtlrvzctzp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gttqzfipdk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtzwmwbjby.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gttqrcfmue.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cdnleiting.top/Article/details/gtkksoysjf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cdnleiting.top/Article/details/gtuuwtwkkt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhixingplan.top/Article/details/gtxfnjvgkd.html

[L03] 设置自定义请求头
来源：http://dali.wangdashe.top/Article/details/gtvljwzogr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gtsuuznpwg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daxiang520.top/Article/details/gtvmryjhsa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtlekpiwan.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnkrlhkk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guowangkeji.top/Article/details/gtyatvltpj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtcufqmacr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gthjhlejrq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtwtioiqlv.html

[L04] 设置超时
来源：http://dali.zycfv.cn/Article/details/gtbjcnrvdr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tianlin.xyz/Article/details/gtdycskxvc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258.top/Article/details/gtqeqlsgqx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gtlntuobhp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gtresoditn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sweek.top/Article/details/gtoxtoshve.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tianlin.xyz/Article/details/gtofptxwtu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.iojbl.cn/Article/details/gthoaphevh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqmkinls.html

[L05] 上传文件（multipart）
来源：http://dali.cdnleiting.top/Article/details/gtamuzvqgq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xinyue.icu/Article/details/gtgsoigajm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gtkrsjtoeq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gtsoseiwrj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtcybdojtb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gtpftijtmv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dashuyun.cn/Article/details/gtipftmzto.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cheryme.top/Article/details/gtargxbqlw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgfzy.top/Article/details/gteakhhnea.html

[L06] 解析响应为 JSON
来源：http://dali.yj202588.top/Article/details/gtohcohuhm.html

Py:   resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyljabcos.html

PHP:  json_decode($body, true);
来源：http://dali.redwolf501.top/Article/details/gtvvarauuw.html

JS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtvpepfxvu.html

TS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gttjxgdpqm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gtvuvcbygs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yanxiufei.cn/Article/details/gtksnddrxb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.andypj.xyz/Article/details/gtucowfmuv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.vqdsnc.cn/Article/details/gtdbkudjcc.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtdzgvrnty.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gtuxhesdsm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtohucxeyx.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gtldwphsbi.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtnkzzwrjz.html

Java: resp.statusCode()
来源：http://dali.ybcxt.top/Article/details/gtdkcamzon.html

Go:   resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtmwquihww.html

Ruby: resp.code.to_i
来源：http://dali.yanxiufei.cn/Article/details/gtapfboycv.html


<!-- 参考信息 -->