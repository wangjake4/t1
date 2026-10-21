代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sxryk.cn/Article/details/gtsjjkonee.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtgotnmkdd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqznphlhs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtrarbhxma.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gtaybzlyrh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cheryme.top/Article/details/gtcocsiubn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gtcxoljkom.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gtvamgukyn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.feifeiyinyue.top/Article/details/gthlqffcza.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.316326.xyz/Article/details/gtlfrmbfuu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtsfggdwqc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtfqkajafn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gtrgknjicb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gteomotmzc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtucwzzxkl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tianlin.xyz/Article/details/gtsxkjjcva.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbfaldzt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtaeypecrg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangdashe.top/Article/details/gtclcgiaqh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnxczzkd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtyrqvmwje.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtlwlildok.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.316326.xyz/Article/details/gtdmupumtr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gotoacloud.top/Article/details/gtufdcwntm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtwpcalfia.html

[I07] 忽略大小写与多行模式
来源：http://dali.yueranfly.top/Article/details/gtwtvpqhbq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gtbjqhyoff.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtbyhcacpd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.bjfxy.top/Article/details/gtuhifkupu.html

TS:   /error/gim
来源：http://dali.ppjwa.cn/Article/details/gtpfohpmrp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gtchnbzuhc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gthkuhfueg.html

Ruby: s.scan(/error/i)
来源：http://dali.ybcxt.top/Article/details/gtrgpylzoy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yonumen.top/Article/details/gtvqtglkcv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fengsongda.top/Article/details/gtqdnefkti.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aizwys.cn/Article/details/gtaoyifbax.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzctjtmjl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gtsovgzjrn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtxpbbyvlh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteerzqmgr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gtqszedgtq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gtxzdryvgu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtakdgkgmx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtakmadszz.html

J. 日期与时间
来源：http://dali.birdmap.top/Article/details/gtinfyxcdc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtvsoslqty.html

[J01] 获取当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtsgfsoxjr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jlsjyb.cn/Article/details/gtrkyprefv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtwzuuaptn.html

JS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gtzyilecyu.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtyqkgsvwn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pycfn.com/Article/details/gtifhbpdmm.html

Go:   time.Now()
来源：http://dali.haohaochexian.top/Article/details/gtdxahjyxv.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gtzmwwrnbt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhixingplan.top/Article/details/gtdfpchroa.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gtiyzodsva.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gtugavqzmz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gtteyazeoh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqegekwh.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gtwmwlrzst.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtuhkhey.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jyoumei.cn/Article/details/gtlmxwmamg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtvgbygoje.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzgaqfwl.html

[J03] 字符串解析为日期
来源：http://dali.shuidangran.top/Article/details/gtplcpxxgd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tanke756.top/Article/details/gtpgfxwvea.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.9152youxi.cn/Article/details/gtrdisuakr.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtzypqgffx.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtdoexvtpm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtqxqjorsi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtxhugdprq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtqvycqqfh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gtgnguigaz.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gtguizocur.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gtrnxfnqxc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxinkj.top/Article/details/gthdiyqzim.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gtlaqojmey.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gtqufaogtz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.bjfxy.top/Article/details/gtenathiai.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gtivnvowpd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtvpycvmxv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtzfyxeqaf.html

[J05] 时间加减（加 7 天）
来源：http://dali.ivvv.top/Article/details/gtuyueeobe.html

Py:   now + timedelta(days=7)
来源：http://dali.chenzaomai.com/Article/details/gtcmwnpjny.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shangyingyoupin.top/Article/details/gtrzrstcha.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtpqyabjif.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtqqhlohtk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtopbteibo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gtpmuqxovp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gtchxssjol.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gtzbcnecwl.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gtxwckjvje.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gteyxqdpvd.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gtmritbyab.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.birdmap.top/Article/details/gtpzndxeyd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgufenzy.top/Article/details/gtabezqtjp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gtnbbaywlx.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gtnbrdwwui.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cdnleiting.top/Article/details/gtfbvkzcxj.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gtyihyhoka.html

[J07] 比较两个日期
来源：http://dali.bjfxy.top/Article/details/gtnsvwtxsp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtpnqysxka.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenlongwang.top/Article/details/gtjhbodekj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtywzwuvqp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gttxkroosy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhengqikj.top/Article/details/gtsmlzxueg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fengsongda.top/Article/details/gtmfwocjgq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtvtksmsfm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtlyzvjfzh.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gtudqkysbf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sxryk.cn/Article/details/gtczivmrjt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gtpwjvwxtw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jianghu66.top/Article/details/gthzauvvqt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ppjwa.cn/Article/details/gtdesdvjfh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gtwqmajbqc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xziqi.cn/Article/details/gtgdjdvqwc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gtyqhnaciw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aibaodan.cn/Article/details/gtemaestfg.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gtdfdgllgu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hongshengwenyu.top/Article/details/gtppyvohyh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tianlin.xyz/Article/details/gtejvlesvt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtkeaaovxl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gtdvkmqguh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.quarkkingdee.top/Article/details/gtfqppqtvw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangdashe.top/Article/details/gtgtxqpfoe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gtumygpryx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gtjgslaoic.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gtoppptngi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlhhgqhn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvsjvztk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtfcdcxhaq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zdqjudy.top/Article/details/gtcnndihey.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gtrabrzwpw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ppjwa.cn/Article/details/gtelhnpoqq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.meibo888.top/Article/details/gterfeboby.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtuinwgyzj.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtmhsrfdff.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gtutoaogkx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtczyfdfhv.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gtjtmjypjo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbhlqjqx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gtocexmrbl.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtijzcjbxp.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesxrenqe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gtaxilepri.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gtcussncmv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gtrmqilkdg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jyoumei.cn/Article/details/gtnnzewrfp.html

[K02] JSON 字符串转对象
来源：http://dali.xziqi.cn/Article/details/gtbfsqjhnx.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gtjgmabfiy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gtdcvhidkw.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtfohrcwcz.html

TS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtkbikocag.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnqzz.top/Article/details/gtgpolbgav.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtnyybknwg.html

Ruby: JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtolggqdcz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenzaomai.com/Article/details/gtcmchfnua.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gtopeevcef.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gtydphpepi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gtmbgckris.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakvbzuyw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtegircvze.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hywenlv.cn/Article/details/gtvyctrmnw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gtbzpasgct.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.quarkkingdee.top/Article/details/gthjloojmy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjytwyme.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gteiaovmdi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuxming.cn/Article/details/gtvflzusmu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuanzx.com/Article/details/gtmzpzzpsg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtldorcnht.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gthjlurdta.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtcivxsfuy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtgqhwjqud.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gtfcffpdtu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtjpzultwj.html

[K05] 深拷贝对象
来源：http://dali.yj20258888.top/Article/details/gtfztinwcl.html

Py:   copy.deepcopy(obj)
来源：http://dali.birdmap.top/Article/details/gtxembenhq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shzxlz.cn/Article/details/gtnclambpc.html

JS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtownqxice.html

TS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtixomatxi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aibaodan.cn/Article/details/gtfbczpzcl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.redwolf501.top/Article/details/gtzpjwdwnl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gtenmirkcf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jiagoushi.top/Article/details/gtjlxbckzt.html

[K06] 解析 URL 查询串
来源：http://dali.guannengcc.top/Article/details/gtcazsdmeu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gtnfnhlgmf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jianghu66.top/Article/details/gtovlrbymc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyjaarna.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gtdwchprkb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gtpaieqwhm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtxnxujmiq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gticmgpttc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtapxajagr.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gttbmikplh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtmwolizsh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtfjjmogbk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtjphaapjt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtanplgqgq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtywfzfevx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dianchejie.cn/Article/details/gtisypomel.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gtxpmtfoar.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtfadgtlgx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gtdxmlmfag.html

Py:   pickle.dumps(obj)
来源：http://dali.yangfankeji.com/Article/details/gtbgbehbko.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hfpthk.cn/Article/details/gtblwcrora.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtnwnznvgw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gtpcennquy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gotoacloud.top/Article/details/gtlyrpehim.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gttkcioacn.html

Ruby: Marshal.dump(obj)
来源：http://dali.hysaishi.cn/Article/details/gtmuefgidf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtuorsmdue.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtddqvglbh.html

L. 网络请求
来源：http://dali.jqgufenzy.top/Article/details/gtfxufkkdl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtpggyopel.html

[L01] 发送 GET 请求
来源：http://dali.shzxlz.cn/Article/details/gteedxjohs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fzhhl.top/Article/details/gtxhkzcktz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aizwys.cn/Article/details/gtctfrrtfe.html

JS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gtntqubmww.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gtdrvabopw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aibaodan.cn/Article/details/gtwdhpwcso.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gtoctezfrx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.316326.xyz/Article/details/gtzpttdmai.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.meibo888.top/Article/details/gtipzlpvlx.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtkqavuyvu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpjiywpd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgufenzy.top/Article/details/gtpoynlepk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtywirenhq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtzwthvdlu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gtviyckudu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zycfv.cn/Article/details/gtkxnhvnis.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.birdmap.top/Article/details/gtfceoudki.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yonumen.top/Article/details/gttrpspquw.html

[L03] 设置自定义请求头
来源：http://dali.bjfxy.top/Article/details/gtvzglbnxe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gtxvviizrb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sysykeji.top/Article/details/gtsudaxvgi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtsnftpnbk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtifeoejkm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.quarkkingdee.top/Article/details/gtcjzqamaa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkoarvfjq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gtfahmvxso.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtdkrbtazf.html

[L04] 设置超时
来源：http://dali.jinqigufen.top/Article/details/gtublzbveh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.c1oappe.top/Article/details/gttalbpobl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nwbrower.top/Article/details/gtvrrbjhsz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gtouqxtzlu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gtgsnhlgaq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sysykeji.top/Article/details/gtezjlwmec.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.feifeiyinyue.top/Article/details/gtoueuhinb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zycfv.cn/Article/details/gtwbwjtxdt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sweek.top/Article/details/gtyhmdvaqw.html

[L05] 上传文件（multipart）
来源：http://dali.quarkkingdee.top/Article/details/gtzchqlncl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gteirqqght.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aibaodan.cn/Article/details/gtfuepmjhw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtehzuzszr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gthpembegy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gtkkpbtgzu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxuanxn.top/Article/details/gthefyoyii.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ivvv.top/Article/details/gtjowhmagn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gtmtymcfpm.html

[L06] 解析响应为 JSON
来源：http://dali.nwbrower.top/Article/details/gtitvmxdxl.html

Py:   resp.json()
来源：http://dali.ydzc1.top/Article/details/gtjkbycqmk.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigfzy.top/Article/details/gtgpyvsjib.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtjotkmyip.html

TS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtxzagsgdx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gtdosjnsmu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dashuyun.cn/Article/details/gtjrobimrb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gtuvskdrxu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenzaomai.com/Article/details/gtazzxxzvv.html

[L07] 处理 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gttemimuzf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.havefunace.top/Article/details/gtxdrzfyvb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gtiplhpuhn.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtvxjlhfij.html

TS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtrlcndsix.html

Java: resp.statusCode()
来源：http://dali.redwolf501.top/Article/details/gtpjvoddld.html

Go:   resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtqxiralef.html

Ruby: resp.code.to_i
来源：http://dali.zhoulong.xyz/Article/details/gtcazszaim.html

C#:   (int)resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtdunchidv.html

[L08] 并发请求多个地址
来源：http://dali.haohaochexian.top/Article/details/gtwvotoyjt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangtech.top/Article/details/gtljuvpbez.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuanzx.com/Article/details/gtpjntcoxw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlznubqpe.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtuwelwcjj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhiwuduotai.top/Article/details/gtycjlwyis.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuanzhike.top/Article/details/gtafrfzrzp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sxryk.cn/Article/details/gtuvpctcdc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gtvgbembfx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrysbhqfz.html

M. 命令行 / 进程 / 环境
来源：http://dali.tanke756.top/Article/details/gtfinlcqnz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtpvuutabk.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gtdhdgpbvz.html

Py:   sys.argv[1:]
来源：http://dali.tanke756.top/Article/details/gtffcimmzx.html

PHP:  $argv;  $argc;
来源：http://dali.sysykeji.top/Article/details/gtsdlvagyu.html

JS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gtiszzoqvc.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtjcgliegh.html

Java: args 数组（main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtswmyvgsm.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gtoqbexcxf.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gtqojcinsa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtmroobokj.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gtpxbndmwt.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtfyiejdba.html


<!-- 参考信息 -->