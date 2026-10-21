代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtgxxqvjgr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.redwolf501.top/Article/details/gtpchoxtwb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.kuanghao11.cn/Article/details/gtnsakvbnc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gteoyhnkpk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtpnsbzvnf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gtvciabeeq.html

[I04] 正则替换
来源：http://dali.cheryme.top/Article/details/gtgmypoxbn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.haohaochexian.top/Article/details/gteixgrhtp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gtkpwgsikb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gttefqklut.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtdtqbhgaf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtkmcppvaz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ehwqpu.com/Article/details/gtcckibljr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gttssuwyom.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gtcjsivbqq.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gtbdmiulce.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfpxtuey.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.havefunace.top/Article/details/gtrdsiyzaq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtcnhxrvkz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtneteqqwt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gtynytaryb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtqzblqrlr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtiphsofxl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gtdnwputpr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gtfheudqgp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtdjsinldo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gtjuqzqecs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gtzelkgpoh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtuputtqwc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtxggzuewc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gaohongyu789.top/Article/details/gtelxvsriy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gtanlmcvrx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtmwlqberz.html

[I07] 忽略大小写与多行模式
来源：http://dali.daxiang520.top/Article/details/gtbkuxmqex.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gtukgvdnga.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtlwkwgedt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sweek.top/Article/details/gtwszcpkkd.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gtbhgfkcjx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zdqjudy.top/Article/details/gthwakyatv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.kuanghao11.cn/Article/details/gtswvfzoxi.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gtohifvict.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hfpthk.cn/Article/details/gthgvdnfjy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhoulong.xyz/Article/details/gtzvyybmrm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ehwqpu.com/Article/details/gtdptyyxnc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtfwyqhpkg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gtdbagtedx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtxbcaxloq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gtlosizlfp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgufenzy.top/Article/details/gttxcswpfo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gtwxxpvpwq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gtrfpdykaj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtynhpqpxw.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gtoubvqchm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtitsbqzhb.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gtsopaqtxi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gtkehmnojn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtouyonttm.html

JS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gtnylmohrx.html

TS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gtgdfyzrxk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gthztdthsp.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gthitnjhqc.html

Ruby: Time.now
来源：http://dali.xuanzx.com/Article/details/gtcofncjhf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cqqwz.cn/Article/details/gtqgabylsu.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gtceajebhe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtgzefrpmb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gtrqpwjcgl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gtaypismwk.html

TS:   d.toISOString()
来源：http://dali.cheryme.top/Article/details/gtrndwrusn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gotoacloud.top/Article/details/gtniorwoia.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigufen.top/Article/details/gtodcovmlb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtuewldahs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gtdimwynoc.html

[J03] 字符串解析为日期
来源：http://dali.cdnleiting.top/Article/details/gtwqqbheaf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xziqi.cn/Article/details/gtjknwwttd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gtzfwwvney.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtqsgjbhfi.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtawyubmhd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gttpotmptc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtdocccuom.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtzncecwbk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gtwhzjolfo.html

[J04] 时间戳与日期互转
来源：http://dali.gotoacloud.top/Article/details/gttkxqequo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtbxcupnth.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gtoieyfjkl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cashguo.top/Article/details/gtfdgmavcz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gtpocziwmm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shzxlz.cn/Article/details/gtncrffwtc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jianghu66.top/Article/details/gtwdmdzegm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfzfrigc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtrcprqjcy.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhoulong.xyz/Article/details/gtoilfjggm.html

Py:   now + timedelta(days=7)
来源：http://dali.sxryk.cn/Article/details/gtejfxldco.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aibaodan.cn/Article/details/gtgtapfzov.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gtsxyynhow.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtttpsxnln.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtfjnxskra.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gotoacloud.top/Article/details/gtsqqnquto.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnprxolqt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tian-w.cn/Article/details/gtbyfbncto.html

[J06] 计算两时间之差
来源：http://dali.jianghu66.top/Article/details/gtyskmdaci.html

Py:   (end - start).total_seconds()
来源：http://dali.snrcjt.cn/Article/details/gtslsyclzl.html

PHP:  $end->diff($start)->days;
来源：http://dali.cdnleiting.top/Article/details/gtgzsrfijj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gtzlufpxeb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.9152youxi.cn/Article/details/gtyjqkorox.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gtifwplavp.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gtvngwyplp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gtlimqgwbq.html

C#:   (end - start).TotalSeconds
来源：http://dali.tianlin.xyz/Article/details/gtrvmebytx.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gtpqwxipin.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtbwcedlgb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangshuangyany.cn/Article/details/gtnsrmuzus.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtaquiitgq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtktatdkyi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtnyephcha.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplamqasr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtfpuxguhk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtwftymfdw.html

[J08] 提取年月日与星期
来源：http://dali.sufxvd.cn/Article/details/gtdmpmrsum.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuanzx.com/Article/details/gthmycqntj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gtjblqjqfy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cucudq.cn/Article/details/gttjbfruzd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guowangkeji.top/Article/details/gtlnxsozub.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gaohongyu789.top/Article/details/gtlgrsnsjh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gtaqvwbhxt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gtpospvbqj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gaohongyu789.top/Article/details/gtocxrqizw.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gtobumdjve.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gtycwtipqt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.bjfxy.top/Article/details/gtopczhtcp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtzbfsojfh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdumzxrk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gtyiogadyb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gtmpxtnevb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.feifeiyinyue.top/Article/details/gtxuoajjff.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gtwmijhxrl.html

[J10] 取今天 / 本月第一天
来源：http://dali.hysaishi.cn/Article/details/gttxpjagmf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guowangkeji.top/Article/details/gtoibfrrle.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gtkcbfqcsu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtkhpprozd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gtgewcvfzm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gtrzzwllub.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gtxmchaqho.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jyoumei.cn/Article/details/gticgewfdo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dianchejie.cn/Article/details/gteyqymaws.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtpdcgxoey.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gtyujlznjg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtrqbrvwhz.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gtxppefhqw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gtpnnlhubw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxhqihou.html

JS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtlcvjibys.html

TS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gtajjgpsln.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gtssbvszea.html

Go:   json.Marshal(obj)
来源：http://dali.jyoumei.cn/Article/details/gtyrekjusi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gtqlczqqiy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ehwqpu.com/Article/details/gtjgseuefr.html

[K02] JSON 字符串转对象
来源：http://dali.tanke756.top/Article/details/gtuchravmv.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gtzucvhyhq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daxiang520.top/Article/details/gtvegmvjpj.html

JS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtmkecefbb.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gthyfchuok.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtfzejumgl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtosnjzcmj.html

Ruby: JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtftmuleip.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gtbrvwnxyv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gtvrhfprsy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gtvmqcvtso.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtqkpuvinc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtsqrbbcmn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtschkhvpz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gttswkhxtd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gtawblnbek.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gttyteohcq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtugpjysyd.html

[K04] 读取 JSON 文件
来源：http://dali.hfpthk.cn/Article/details/gteowamnvb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aibaodan.cn/Article/details/gthyvqrfbs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gteasyxgqx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtjqhwhiff.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkjsdifr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsyknjotw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gtruamshfl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sweek.top/Article/details/gtgvulxiub.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtzwzaftmd.html

[K05] 深拷贝对象
来源：http://dali.snrcjt.cn/Article/details/gtoxjecure.html

Py:   copy.deepcopy(obj)
来源：http://dali.hywenlv.cn/Article/details/gtcnpookqx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hfpthk.cn/Article/details/gtmcmxqqht.html

JS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtgivjnnog.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtbeimjtcy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigfzy.top/Article/details/gtulqdexrg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnxiangtu.top/Article/details/gtcomiunza.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dianchejie.cn/Article/details/gtiempxxtq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dashuyun.cn/Article/details/gtaimtgkvk.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gtktwhymcl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gtadgfrqvp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhiwuduotai.top/Article/details/gtwmwvvrcl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gtkmnhnatd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtwhkiuwdd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.snrcjt.cn/Article/details/gtlqnkbeqz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtohgadnhi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtgbfnmieu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtxnhuownp.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gtehdhdkbo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwxlpzsq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gtdovdjbvx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtqiizdfsd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygqidgbv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtqlfpwptz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhiwuduotai.top/Article/details/gtkzwfsxxg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shzxlz.cn/Article/details/gtlxshzdqu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtdcwmzwsp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gtgdasjlvk.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gtkurvwbvv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gtqwtvgzjl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gtflzvzwyi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmixqpftg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sufxvd.cn/Article/details/gtvwotlcok.html

Go:   encoding/gob
来源：http://dali.9152youxi.cn/Article/details/gtsbncnafg.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gtfgvpwajv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkxgapnl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtnxgivitz.html

L. 网络请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxeuukzfz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvalhfwxr.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gtiagmcydk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigufen.top/Article/details/gtsrvnzfaj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gtxsyouzqr.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtqyqsqnlx.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtcxsvlqgk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yangfankeji.com/Article/details/gtzorpuucl.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gtzeiofwpx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuxming.cn/Article/details/gttdafkkcr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.bjfxy.top/Article/details/gtbapshuwf.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtftuwdjic.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtoosnuhhg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zdqjudy.top/Article/details/gtbhulkezh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gtjmdwddtd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gtteuqvvws.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gtzmgazoou.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gtmpugpvqv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jyoumei.cn/Article/details/gtutzepsvm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fzhhl.top/Article/details/gtlusxpgxo.html

[L03] 设置自定义请求头
来源：http://dali.sysykeji.top/Article/details/gtafcsahoe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gtvzqlpqao.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhengqikj.top/Article/details/gtxpnupeyb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtiudfbdjs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gthbguefwb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuanzx.com/Article/details/gtiaoxvydf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtvbsrylkq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gtkgusjmqa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtlrutqsaq.html

[L04] 设置超时
来源：http://dali.havefunace.top/Article/details/gtnolwmgxv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cqqwz.cn/Article/details/gtutjcmmdu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gttthlpwnm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gtgaswfccm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtouxltcul.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gtaqhlebqh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gtjjclmitc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhiwuduotai.top/Article/details/gtbklnjlxq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gtrxnanpyf.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigfzy.top/Article/details/gtrbatxxkk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daxiang520.top/Article/details/gtixteneeu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtytfljgqn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gtjkycuchx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gtmhofaovi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuanzx.com/Article/details/gtydnhtyos.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gtgspovjds.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.iojbl.cn/Article/details/gtuaylxamr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sysykeji.top/Article/details/gtcidgcoyg.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gtjhvjnosk.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtgtqectpd.html

PHP:  json_decode($body, true);
来源：http://dali.hnxiangtu.top/Article/details/gtiilegvvx.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gttletlzyb.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtobmaigcf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gtptohbqgr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.feifeiyinyue.top/Article/details/gtdltptcwr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gtnszcjacg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj202588.top/Article/details/gttkqsmpyg.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtdnrzwvlh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gtuzoellbg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.birdmap.top/Article/details/gtiznodywo.html

JS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtbeqnsxxl.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtedfdgrgx.html

Java: resp.statusCode()
来源：http://dali.haohaochexian.top/Article/details/gtgpscezlp.html

Go:   resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtkzsnyqpr.html

Ruby: resp.code.to_i
来源：http://dali.xuetiantiany.cn/Article/details/gtxatcqfmx.html

C#:   (int)resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtpzafwbrz.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gtrmqnhdvo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gtfywsycsb.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnqzz.top/Article/details/gtngajvmtb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowndyrjj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtwgycqyim.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtoriwmeee.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gtmpqlvksd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gtpqkfiywi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtqowwmzwz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtkugkrtod.html

M. 命令行 / 进程 / 环境
来源：http://dali.tanke756.top/Article/details/gtfdwxcinv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtnwkldurk.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtmmqicnfb.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gtlrfhpfrx.html

PHP:  $argv;  $argc;
来源：http://dali.tian-w.cn/Article/details/gtkliihpho.html


<!-- 参考信息 -->