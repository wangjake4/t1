代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.vqdsnc.cn/Article/details/gtrolybtcy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgfzy.top/Article/details/gtbssjtwxp.html

[I04] 正则替换
来源：http://dali.zhongyouzk.top/Article/details/gttkgrpthy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfaxfoffb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gtzpsarhok.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gtukrwhobc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gtuopufwjp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.birdmap.top/Article/details/gtystfuuwj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarwcmzge.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.bjfxy.top/Article/details/gtwglndwyz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pycfn.com/Article/details/gteapbmgog.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gtavsriznz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gtibbiqsuo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gtperpture.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtbzdpddzp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtzbaqhuyi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigufen.top/Article/details/gtkhowbhof.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fengsongda.top/Article/details/gtogpseksn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtgcfamlip.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cqqwz.cn/Article/details/gtwdwedikh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shzxlz.cn/Article/details/gtldsouwwz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktiiocxb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fzhhl.top/Article/details/gtsnozmpne.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtgkjpbaiq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gtbvkebauo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtnmomaevc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zycfv.cn/Article/details/gtpmaxhtqz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqnobgpi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtfgkviged.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gtmlnapxdp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.haohaochexian.top/Article/details/gtkybghosw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtvzlyegte.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqsvhrzj.html

TS:   /error/gim
来源：http://dali.nanxinkj.top/Article/details/gtaipgwbts.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zdqjudy.top/Article/details/gtzrmskbcl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gtrrdklupl.html

Ruby: s.scan(/error/i)
来源：http://dali.sxryk.cn/Article/details/gtoozmibmy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guowangkeji.top/Article/details/gtrxzymjlh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gtddowtfrx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gtnhepbcuk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gtmrmvqnwa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gttdydugvj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtdwnhduhg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gttnpwmvre.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guannengcc.top/Article/details/gtbelxjxtn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrfclyjo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gtreyyfaef.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtyeluumbr.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gtzhqtzqqj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtamtjdxpn.html

[J01] 获取当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtsjealzip.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gthggetolh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtcpnkphle.html

JS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gtynklxawz.html

TS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtphkbuamy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuxming.cn/Article/details/gthmfdfbtz.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtwanlzzde.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gtcqsxqykh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gttwgklkfr.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gthirfcgce.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gtkkohopmu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gtonpiecqb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gtvjomtsza.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gtqvkkgkbf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xinyue.icu/Article/details/gtvvzfgtsl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gtffqttnty.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gticsdgtuh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.birdmap.top/Article/details/gtekszlwnh.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gtuzetekgm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hysaishi.cn/Article/details/gtqcwseyma.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gtkrjzxeny.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtqhaumjjk.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtfduwsnvb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtqirfcsyr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqeztoiw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtcjbfpipk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gtwkttkybu.html

[J04] 时间戳与日期互转
来源：http://dali.yuxming.cn/Article/details/gthbmteewh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gtuqufpbdz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cashguo.top/Article/details/gtnbdrerit.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtcdupwucr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhixingplan.top/Article/details/gtkjhgggsy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hywenlv.cn/Article/details/gthqkqowvq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guannengcc.top/Article/details/gtgnfoentg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gtmbwygcdy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.c1oappe.top/Article/details/gtykaxkdpy.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gtahcguhqb.html

Py:   now + timedelta(days=7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvklzvefh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gthmullrsd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtsibstpvn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtzaswaysm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gtrisdeujd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.vqdsnc.cn/Article/details/gtidkigbuh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgfzy.top/Article/details/gtyoinzizi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnqzz.top/Article/details/gtbkxvlggr.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gttinvgdmx.html

Py:   (end - start).total_seconds()
来源：http://dali.zhoulong.xyz/Article/details/gtentyyxpp.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gtfcftunux.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shzxlz.cn/Article/details/gtyrqkgztf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxmxpued.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigufen.top/Article/details/gtxwpurpif.html

Go:   end.Sub(start).Hours()
来源：http://dali.ydzc1.top/Article/details/gthnkyvswr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gtphgrvuhc.html

C#:   (end - start).TotalSeconds
来源：http://dali.cdnleiting.top/Article/details/gtzjfkoowb.html

[J07] 比较两个日期
来源：http://dali.fengsongda.top/Article/details/gtuxndaoqx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtidddsezw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gtobzhboog.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtxqnryrmt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtvwymjxbl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgfzy.top/Article/details/gtirvajwuy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xziqi.cn/Article/details/gtmtjpsymn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gthzyligie.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtvytugfio.html

[J08] 提取年月日与星期
来源：http://dali.jyoumei.cn/Article/details/gtufsrnfqb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gtprkdwjyc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pengpengdd.cyou/Article/details/gtygungbot.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhoulong.xyz/Article/details/gthrilphph.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daxiang520.top/Article/details/gtkadpjgte.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gtjcigpzai.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gtefwfrxrb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gtlxqykrzd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gtvfldbobt.html

[J09] 时区处理
来源：http://dali.redwolf501.top/Article/details/gtttpakzrq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gtoohlvruk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gtmuzoifyu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gtxgusjhpr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtkuejkefu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.9152youxi.cn/Article/details/gttmdemlhi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yanxiufei.cn/Article/details/gtpbhhcyff.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gtlxwtwsdg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ydzc1.top/Article/details/gtfrkedtcq.html

[J10] 取今天 / 本月第一天
来源：http://dali.xziqi.cn/Article/details/gtyjtfqwfo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqkjxpwg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hfpthk.cn/Article/details/gtkagbjotr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gtyseflrgd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtxozmsbhw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnplugyp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gtvaeyfbiz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gtfibzprxz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnhztbnc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtjgcarhqc.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gtrngsytsl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtumgblhuo.html

[K01] 对象转 JSON 字符串
来源：http://dali.gogol.net.cn/Article/details/gtrialwplr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gtniuiusjq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtwzxqvelu.html

JS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtmauenlpy.html

TS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtororxogz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hywenlv.cn/Article/details/gtrrreymza.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gtjetgqhkc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gtgxlgsnof.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtbmdkhvlx.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gtwbadjrer.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gtzksfkwtf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zdqjudy.top/Article/details/gtwuhigzeh.html

JS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gttqwbnnob.html

TS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtlvpikcad.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtgutxwmia.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtvjtbuqpn.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtmymweooi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigufen.top/Article/details/gtdojhxjkb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gtuwfkxynt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gtazatxchh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gthehlmxwl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtioerqwqb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczrjmkef.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gtwddwmcgt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xylfe.cn/Article/details/gtlqjpvwpi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtssxhdvmt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gtsjunzrsg.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gtnlnyaqqc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gtzphwvcyt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgufenzy.top/Article/details/gtrfkhgrmn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gtfybevxws.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtrkxzjuxl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtmixyqrkr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtweetukin.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gtzqckzqes.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtxkpkqafr.html

[K05] 深拷贝对象
来源：http://dali.chenlongwang.top/Article/details/gtvzonhlpm.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gtrjvfllfa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgufenzy.top/Article/details/gtvsxqlkyt.html

JS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtmbplxihl.html

TS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtwayijjky.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqubmtpzc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gternvbmik.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuxming.cn/Article/details/gtqhqnsaim.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cashguo.top/Article/details/gtuhrxptul.html

[K06] 解析 URL 查询串
来源：http://dali.xinyue.icu/Article/details/gtpmclokgh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtvrflkexs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtycdgevbv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtbahlnkuj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gtandtcgvb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gtzhxculzv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtjybqvgdl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtvulsccaa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gthyowwcmo.html

[K07] 进制转换
来源：http://dali.havefunace.top/Article/details/gtwoqmabtp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gthhcbcgwk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gtnynlkdou.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtbcfqeprn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtlbmdwgtv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtcxxabpqf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ybcxt.top/Article/details/gtjxdifmwk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.iojbl.cn/Article/details/gtiasfwing.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gteqqjydih.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ehwqpu.com/Article/details/gtwmuubuca.html

Py:   pickle.dumps(obj)
来源：http://dali.nwbrower.top/Article/details/gtsuoqzjcw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hfpthk.cn/Article/details/gtmjoxralh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtjibsason.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtwryaruhw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pengpengdd.cyou/Article/details/gttovkxvlo.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gtekoqemay.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gtibfetvdh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtsobnzbeh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gttuyxlyiy.html

L. 网络请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljsgsxfc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtgzwrumdd.html

[L01] 发送 GET 请求
来源：http://dali.iojbl.cn/Article/details/gtvzyxoiul.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gtjakeqfnf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj202588.top/Article/details/gtpcrpnqhg.html

JS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtersmxfky.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gtbcalwhzf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ppjwa.cn/Article/details/gtvyyvdrkj.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gtklmmqmtf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkiwrfxg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gtlqjsywfu.html

[L02] 发送 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gtiknpoazx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gtpwincvbf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gtpebekmkw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gttqrakwaw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gthbibnjxw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gtflnswjhl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gtuxuhypcb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yonumen.top/Article/details/gtlshnrnbj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gtuogcbtsu.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gtaifmuslz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gtajydusvg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj202588.top/Article/details/gtqigiejku.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtkttjrzsg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gtnxsasmwc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.feifeiyinyue.top/Article/details/gtzkycywfg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtfqvlegly.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jianghu66.top/Article/details/gtpliwlabs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymmwoxal.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gtpeaamwtf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gtgajmesei.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtkfpsgblt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtyjvxgbhj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gtmsgayhwy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258.top/Article/details/gtmennrjum.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gtrxdkxsbc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gtjhokqrto.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sysykeji.top/Article/details/gtmfrpsdpl.html

[L05] 上传文件（multipart）
来源：http://dali.ivvv.top/Article/details/gtzvzfaoeh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gtxrgplgzg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.316326.xyz/Article/details/gtpxbnfwok.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gthqyyfygh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtrsxpiplk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gtopldasin.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cheryme.top/Article/details/gtsomnpxgd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fengsongda.top/Article/details/gtjdjlwbed.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gtdgpfxjop.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gtxdzgvwmw.html

Py:   resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtpvfgzusk.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gttfpbqxji.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtsuhnelyo.html

TS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtolloximz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtbjoadrjx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gtbjwgwicb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gtiilayuyv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jianghu66.top/Article/details/gtijviowyt.html

[L07] 处理 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixejcybj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gtdxdkhgca.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gtmdadoxgp.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtxdwozvmo.html

TS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gtcltowwci.html

Java: resp.statusCode()
来源：http://dali.xylfe.cn/Article/details/gtwbtklmeq.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtbpwrozxf.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gtkclskddw.html

C#:   (int)resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gttannvcdq.html

[L08] 并发请求多个地址
来源：http://dali.zhongyouzk.top/Article/details/gtavicqure.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gtusknkrse.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gtdqmbqhap.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtwgpsdzoi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtwdkwvzfm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhgpkvkl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hammf.cn/Article/details/gtgqgryvvz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtmpaiomid.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cdnleiting.top/Article/details/gtcgttrxiz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtymurcjgk.html

M. 命令行 / 进程 / 环境
来源：http://dali.tian-w.cn/Article/details/gtxhhaezqj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtfnwqbjug.html

[M01] 读取命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtfkpxqyeh.html

Py:   sys.argv[1:]
来源：http://dali.hnqzz.top/Article/details/gtkeetuhdn.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gtyqecxwno.html

JS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gtxdanogak.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtzpjnifih.html

Java: args 数组（main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gthyqymqzj.html

Go:   os.Args[1:]
来源：http://dali.pycfn.com/Article/details/gtfsvaayio.html


<!-- 参考信息 -->