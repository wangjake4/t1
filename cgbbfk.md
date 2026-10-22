代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guannengcc.top/Article/details/gt2gllpmspb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258888.top/Article/details/gt2xpkthgyf.html

[I04] 正则替换
来源：http://dali.jinqigufen.top/Article/details/gt2tmwpifbe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.9152youxi.cn/Article/details/gt2lijntpse.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gt2hnrijfjm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gt2zmjuyltd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gt2pstsolho.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hammf.cn/Article/details/gt2yzuubdit.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2otmsqrxs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xmmunqhk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gt2tlitgmxj.html

[I05] 按正则拆分
来源：http://dali.tianlin.xyz/Article/details/gt2gojpaehg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gt2xqwovgom.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2dpvuwitt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gt2xviilaqe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gt2fsgvwyzf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuanzx.com/Article/details/gt2olezjrcu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gt2gjdhdrho.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2xsdgvbco.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krwqitrr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cheryme.top/Article/details/gt2jgxhmmeu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gt2ogcpphmw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gt2ievwlhsd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gt2toybnvcn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gt2iftnbeyh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2kyakpruj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ybcxt.top/Article/details/gt2awhlrmzn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gt2trqcblpz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2vbyuxpxk.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gt2lrertpyb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ecnixhns.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gt2whvxepbg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gt2akmwzhhf.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gt2qdplqnim.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.svipenyu.cn/Article/details/gt2nliuxohr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gt2ssznygsu.html

Ruby: s.scan(/error/i)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pymybsej.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tanke756.top/Article/details/gt2sgkzmdlj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ivvv.top/Article/details/gt2njnnbhue.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwjhpufb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gt2hnbhgyof.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2terbntbz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gt2stnxysjt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gt2wptaomjd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.andypj.xyz/Article/details/gt2hmvkkbpv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gt2imjxsqxl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbowrmms.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2cdxlnkzo.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gt2yozhwlik.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2opmfntho.html

[J01] 获取当前时间
来源：http://dali.daxiang520.top/Article/details/gt2ycftvotu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuxming.cn/Article/details/gt2rnqclszd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gt2ixzfzhgb.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gt2zwrbbfvi.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gt2qfgirzmh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gt2klczmdko.html

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2sllnqxon.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gt2fisbvgrk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tanke756.top/Article/details/gt2qqgrsery.html

[J02] 格式化输出
来源：http://dali.cdnleiting.top/Article/details/gt2morvvhin.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gt2elzdydff.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gt2jtbnkvzz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gt2cbeegloq.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2eqspmtvd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.bjfxy.top/Article/details/gt2rzrstjts.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.meibo888.top/Article/details/gt2krcztwdh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mjevgaox.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hysaishi.cn/Article/details/gt2uqcpnpmt.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gt2esbhdwzy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gt2pddcaakz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuanzhike.top/Article/details/gt2psrsoylw.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2idfjxksd.html

TS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2tbvjzusy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2ajayldcx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2asyqyrvc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2tpeadcxy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.smart0.xyz/Article/details/gt2qbbfyeqy.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwjranwy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2dvblmkat.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gt2omrnxpbp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gt2udeskmoe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhengqikj.top/Article/details/gt2kyoahdin.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nwbrower.top/Article/details/gt2qokfvztx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rfdumhlq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hywenlv.cn/Article/details/gt2wyrxukro.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2wrgurpns.html

[J05] 时间加减（加 7 天）
来源：http://dali.sweek.top/Article/details/gt2znusfrcy.html

Py:   now + timedelta(days=7)
来源：http://dali.ydzc1.top/Article/details/gt2wyqbndhm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gt2hylumcew.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gt2tkzliyyu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gt2scuxurqv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yunfrhxo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2blldgfxv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gt2fnfqwbdr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzvubyxx.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jrjxxhfq.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gt2hpluzvtx.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gt2ljwqknfs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hfpthk.cn/Article/details/gt2ulnfgqri.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cheryme.top/Article/details/gt2eyptcdou.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gt2hxollclq.html

Go:   end.Sub(start).Hours()
来源：http://dali.yanxiufei.cn/Article/details/gt2zhnuexba.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gt2ujoiepmj.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sinahjlt.html

[J07] 比较两个日期
来源：http://dali.havefunace.top/Article/details/gt2zhlmngzq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2kwnqbuoh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ybcxt.top/Article/details/gt2ypsptuew.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gt2gyopzwtf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gt2ildcvhjr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ydzc1.top/Article/details/gt2khusxdni.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guowangkeji.top/Article/details/gt2wbhgokqf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2rmasrcgp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qflleqkb.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gt2fvaxfszu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gt2ydlztjqz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ppjwa.cn/Article/details/gt2rtolawfk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxuanxn.top/Article/details/gt2mptcciqc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gt2lkbyzwby.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.0kj1m.cn/Article/details/gt2hpqwhlks.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.kuanghao11.cn/Article/details/gt2vctgetbz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cdnleiting.top/Article/details/gt2fiwtbgbz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhmecvq.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gt2vszfdbby.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.snrcjt.cn/Article/details/gt2zhdqxbsq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gt2ymfbwuwl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gt2qlhsjbpr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gt2rjykftun.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenlongwang.top/Article/details/gt2gfklretu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hywenlv.cn/Article/details/gt2faqeupxk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gt2uzzfboga.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cdnleiting.top/Article/details/gt2wutalyko.html

[J10] 取今天 / 本月第一天
来源：http://dali.fengsongda.top/Article/details/gt2apubqata.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jaiwyfth.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dashuyun.cn/Article/details/gt2xsevzfdk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.svipenyu.cn/Article/details/gt2nmmbbpeh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gt2asiftkmh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gt2fzmovggr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gt2dxphujku.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gt2snitcfvn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gt2echbfiyt.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2cylvofma.html

K. JSON 与序列化
来源：http://dali.bjfxy.top/Article/details/gt2jzdydvtw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2uzrrszms.html

[K01] 对象转 JSON 字符串
来源：http://dali.shzxlz.cn/Article/details/gt2pnmihrhu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gt2unmvkiht.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gt2cdmhpeoh.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2nhyhdlpz.html

TS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2ulxwmxez.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gt2mdsgdysq.html

Go:   json.Marshal(obj)
来源：http://dali.316326.xyz/Article/details/gt2ixfazgkh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pycfn.com/Article/details/gt2ccfpqepn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj202588.top/Article/details/gt2zkrkdxix.html

[K02] JSON 字符串转对象
来源：http://dali.tian-w.cn/Article/details/gt2fppcjwfu.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gt2rotccmtx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnqzz.top/Article/details/gt2sckyiojq.html

JS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2dgoytsxq.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uyhbsvpp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tanke756.top/Article/details/gt2htcbkrmc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gt2nkjkgwlk.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gt2fjoxkxbh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gt2kobcxpqv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gt2xflreidb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gt2erriysft.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gt2tknnlvaa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iyywrfyj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2nmwptcqs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xpwjcexl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cdnleiting.top/Article/details/gt2cvkgipoa.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangdashe.top/Article/details/gt2nigxpknd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fengsongda.top/Article/details/gt2ncvumkqm.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ibopguey.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvnlxyeb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gt2ivqvdnmo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gt2mpsfacen.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gt2axywzxhw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gt2vjqmkxnf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gt2nwzjscnj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gt2tmbyyfcn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2ubhhkubq.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gt2ywghvpmu.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gt2tmdsvind.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fengsongda.top/Article/details/gt2rcndkzer.html

JS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2sbxekxui.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2bwxmvwmk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yanxiufei.cn/Article/details/gt2gyxxebtx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.meibo888.top/Article/details/gt2zvzpimcs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gaohongyu789.top/Article/details/gt2orwlwzpt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tanke756.top/Article/details/gt2fsyqoywb.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gt2mmkrkzjg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gt2jcyqqwar.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xylfe.cn/Article/details/gt2juxurkjo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gt2arocazel.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2ixlvrbaw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj202588.top/Article/details/gt2ufiyddxe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2muiicdxr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2etcusjba.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2xjrvegqr.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gt2hibnvvlc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dztmkxkv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gt2kyokpzzu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2vblwgrzv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2nxlbrqzd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2syynrxru.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jlsjyb.cn/Article/details/gt2wvimzklp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gt2pyhiumnj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2wjgzoncj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shzxlz.cn/Article/details/gt2xapzgkim.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2iqcbshhp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2qszubztj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gt2seqvudrv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gt2fdwmlerm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guowangkeji.top/Article/details/gt2iwbbvauw.html

Go:   encoding/gob
来源：http://dali.kuanghao11.cn/Article/details/gt2dsszztks.html

Ruby: Marshal.dump(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypgervsr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gt2innspbab.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2qpqwvkfu.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gt2jhabgvxt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2xnwykwwg.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gt2gvingwgz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gt2vjihkxeo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gt2girdoouu.html

JS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylznttvw.html

TS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gt2acnwwbof.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gt2qreatvtu.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gt2deyjndmk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gt2zesdwvkf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sllwbqzb.html

[L02] 发送 POST JSON
来源：http://dali.pycfn.com/Article/details/gt2rcvduzpv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gt2cvcimshv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gt2psmvnijt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gt2lohanhbc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gt2hvkkcjdm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ydzc1.top/Article/details/gt2pkphylah.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gt2hybsujap.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xurzruqw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.birdmap.top/Article/details/gt2rvnpgnfc.html

[L03] 设置自定义请求头
来源：http://dali.gzhubu.top/Article/details/gt2kgqtnbee.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xylfe.cn/Article/details/gt2cvwpibgd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dqrawxaw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gt2ytgevuwf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gaoyklev.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gt2wwhyxplq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gt2ktgqhjjr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cucudq.cn/Article/details/gt2hbarybsn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gt2tgacetqq.html

[L04] 设置超时
来源：http://dali.hfpthk.cn/Article/details/gt2ceqytkgi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgoqteih.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.c1oappe.top/Article/details/gt2hckxqtsv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gt2wyisussc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gt2eebdzzmi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2quqvjynw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfafbulq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.kuanghao11.cn/Article/details/gt2elqbbzcj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cashguo.top/Article/details/gt2iveecklu.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gt2djzdmfjd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sweek.top/Article/details/gt2dyacskuf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.c1oappe.top/Article/details/gt2cqfletea.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gt2pjasycgd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gt2trazjibh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gt2vkuygavb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.c1oappe.top/Article/details/gt2lqyvppqs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guannengcc.top/Article/details/gt2kgrybovw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2gevcobay.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gt2bdhsucpn.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gt2nqmzqgoe.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2jwnvqilv.html

JS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2ipicyrsy.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2xrtsgqmp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2quxaqzzn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cheryme.top/Article/details/gt2udfpamde.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gt2pqdpbkkv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.316326.xyz/Article/details/gt2risxfuat.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztgfmvhd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gt2vooeyxcu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gt2wgibvgip.html

JS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gt2ijjdcibm.html

TS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gt2hjxkxezq.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gt2yxscmngr.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2skcoqjqb.html

Ruby: resp.code.to_i
来源：http://dali.cucudq.cn/Article/details/gt2jouljakw.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gt2teuvifzy.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gt2tnccwbmm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daria6918.cn/Article/details/gt2rlkhpryd.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gt2okayssta.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2cisjyzrq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gt2jupvhlhi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gt2wshlimjv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258888.top/Article/details/gt2bsklqtmj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2nwlvlnqg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2kpmxcisz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhwzqqvz.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gt2sfvmblqd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2toablwrv.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gt2oupbnsuj.html

Py:   sys.argv[1:]
来源：http://dali.gzhubu.top/Article/details/gt2kutszhwk.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gt2ugfssfry.html

JS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gt2pdajhgmo.html

TS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gt2oynxgtek.html

Java: args 数组（main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gt2qcndyoyw.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gt2oahuftag.html


<!-- 参考信息 -->