代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cucudq.cn/Article/details/gt2htnuxyio.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sysykeji.top/Article/details/gt2mfijrocu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gt2wpvyblii.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aibaodan.cn/Article/details/gt2wkjrjfsg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2pspguzvj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.haohaochexian.top/Article/details/gt2jkxaqjcp.html

[I04] 正则替换
来源：http://dali.zhoulong.xyz/Article/details/gt2geetpjbv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gt2gcybciyd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gt2ulhikqcv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2qoqduadj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2utycwdim.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gt2avfplkpq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.meibo888.top/Article/details/gt2uegiavmc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2hlxdyyrx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gt2wilvwswh.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gt2qcxcbgdn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gt2ofbgpdjb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gt2ycdjskvp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gt2zilnlevd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2fsndhbdv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuxming.cn/Article/details/gt2qjougwcg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gt2nwgvnxfz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqxrzuxw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gt2jrxryzsv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yvedp.cn/Article/details/gt2akoacqse.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2mtppmrrc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zdqjudy.top/Article/details/gt2ypezsgfs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gt2tlsnznha.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gt2itavbqll.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gt2emtzdjgi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.smart0.xyz/Article/details/gt2rwyaxryx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daria6918.cn/Article/details/gt2gyrdcsan.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gt2utnnuyzx.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhmkoode.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ovmgospu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gt2chtsgzno.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.kuanghao11.cn/Article/details/gt2oddkdpfv.html

TS:   /error/gim
来源：http://dali.jianghu66.top/Article/details/gt2hpdiwkfi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guannengcc.top/Article/details/gt2ipsyjmyy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shuidangran.top/Article/details/gt2auexgvmo.html

Ruby: s.scan(/error/i)
来源：http://dali.hnxiangtu.top/Article/details/gt2ybaetspb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aibaodan.cn/Article/details/gt2ukrimgjt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gt2dglygmcw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gt2xnoeasue.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gt2levjsqkk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gt2jskrtfwa.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gt2erdcpduw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gt2wovjpsga.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gt2fvzhkxvy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.mhx1999.top/Article/details/gt2abmtnqfh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gt2zgqyswbp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2nbxelecl.html

J. 日期与时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2decleqjq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2dybgcrwf.html

[J01] 获取当前时间
来源：http://dali.cqqwz.cn/Article/details/gt2imqiorlq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gt2kxcqjifm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gt2aooilrkd.html

JS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gt2rwwzqjdm.html

TS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gt2vabzmwum.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gt2jwhvofri.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gt2dwpbjtlk.html

Ruby: Time.now
来源：http://dali.vqdsnc.cn/Article/details/gt2sljvyqhe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sufxvd.cn/Article/details/gt2vrherkpt.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gt2nozmxysr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2xpqxitoh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gt2mvonjoob.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sxryk.cn/Article/details/gt2rrtofmnh.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gt2tzgoopbh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gzhubu.top/Article/details/gt2bczszpbt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxnugsmr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gt2mbwvihur.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gt2nspfhrsy.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gt2aqzlwdlm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ikcrfjps.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guannengcc.top/Article/details/gt2zeglijol.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2toovbiyr.html

TS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jdrhvuit.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2afbjtwtn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2yhfwbbqb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2vsaybocm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xinyue.icu/Article/details/gt2zgqwdokb.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gt2igkrtqja.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cashguo.top/Article/details/gt2nerrkbbq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gt2thzeuvqe.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daxiang520.top/Article/details/gt2dllnqbxh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yonumen.top/Article/details/gt2yxynnptl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jiagoushi.top/Article/details/gt2scgjbwtx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gt2ereqyfez.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuanzx.com/Article/details/gt2kuucdinc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gt2ygkttydg.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gt2qzobmznm.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ktdthmlv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gt2unewsnzz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2lywmhjqh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gt2jbuohozk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gt2zhfixprw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gzhubu.top/Article/details/gt2shulhgkr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.kuanghao11.cn/Article/details/gt2bniqddot.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgfzy.top/Article/details/gt2ocgqcnrn.html

[J06] 计算两时间之差
来源：http://dali.guowangkeji.top/Article/details/gt2jwrvqvkf.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gt2wutetggy.html

PHP:  $end->diff($start)->days;
来源：http://dali.xylfe.cn/Article/details/gt2yzdcpuzv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guannengcc.top/Article/details/gt2yyhioqns.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yangfankeji.com/Article/details/gt2suzmimbq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cashguo.top/Article/details/gt2errnwsit.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gt2vwidpihs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gt2xrrirdwy.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gt2atliqqsk.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gt2asikstgo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gt2quvooult.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gt2vdkkimvb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gt2nhucmbai.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gt2wagjxhtj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gt2vwlemvwf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cdnleiting.top/Article/details/gt2hvdvnehv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gt2nzrfihgk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2hfirzbsj.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gt2mwwwmolh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.smart0.xyz/Article/details/gt2vclaeybr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gt2vgrxdhlf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zycfv.cn/Article/details/gt2hhmpftrt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gt2omdxbaaq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gt2xleoxgum.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.svipenyu.cn/Article/details/gt2tvtmlbyn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gt2vihuaddg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gt2cqwxpymo.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pggheacf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xylfe.cn/Article/details/gt2sklxcxxs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gt2krzfjdti.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gt2ntqzaniz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2lbbejjrt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gt2rpmnrrey.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gt2bkcmzdpk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2owjzxxis.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xylfe.cn/Article/details/gt2akfcwcqm.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdwpeano.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guowangkeji.top/Article/details/gt2crjsopkn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pycfn.com/Article/details/gt2wuxjrihv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gogol.net.cn/Article/details/gt2ggqwrefx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yongpay.top/Article/details/gt2vlijmfwr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gt2qpmscfhw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guannengcc.top/Article/details/gt2fbsfvtlv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shzxlz.cn/Article/details/gt2qwnxavse.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rsvalkht.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2qwtrhflf.html

K. JSON 与序列化
来源：http://dali.pycfn.com/Article/details/gt2teiipwmv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iyzjfpzh.html

[K01] 对象转 JSON 字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2crcojyhf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2denztjku.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gt2kbspiyqw.html

JS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gt2hjajqcoe.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2oyuirhej.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gt2qfeztvhw.html

Go:   json.Marshal(obj)
来源：http://dali.wangdashe.top/Article/details/gt2rdxmkhex.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gt2wabstcen.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2aisobljh.html

[K02] JSON 字符串转对象
来源：http://dali.nanxinkj.top/Article/details/gt2kiiyeizx.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gt2hnxhjhjk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuanzhike.top/Article/details/gt2mtnifoii.html

JS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gt2ishmsiha.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qvwyrhjf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gt2labfyanq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gt2ftgfqphf.html

Ruby: JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gt2qmavkzcv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gt2frgakors.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aibaodan.cn/Article/details/gt2igsbshql.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gkgsblbg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gt2nufqlytd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gt2nkgsptdk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iwncykki.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vcrivdvb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yueranfly.top/Article/details/gt2yksicmjj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2zkxeglcu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvibjbjj.html

[K04] 读取 JSON 文件
来源：http://dali.yuanzhike.top/Article/details/gt2kujwmddi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxinkj.top/Article/details/gt2viendbvv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgfzy.top/Article/details/gt2nhyivzlz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gt2jvlhbfnh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gt2efrarwbh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gt2pgofjhpr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gt2kffzuuiw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2otddsbat.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gt2yucwyxzi.html

[K05] 深拷贝对象
来源：http://dali.zhixingplan.top/Article/details/gt2lqjjrbdd.html

Py:   copy.deepcopy(obj)
来源：http://dali.zycfv.cn/Article/details/gt2bfceybiv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yvedp.cn/Article/details/gt2bwxkgltw.html

JS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2mqsdqoii.html

TS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2vykmjzpn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgufenzy.top/Article/details/gt2ohdtfjfe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj202588.top/Article/details/gt2ofemaiwx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.meibo888.top/Article/details/gt2uypxaniu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gt2fdjlrktx.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gt2svarblov.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gt2bogqoeuy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gt2hzfqoism.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gt2waflwwvl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gt2hgbotgtt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.haohaochexian.top/Article/details/gt2zaanmyoh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2ixhkiutn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xlaexqut.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gt2amqxtqly.html

[K07] 进制转换
来源：http://dali.guannengcc.top/Article/details/gt2lollmfou.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2qhgfenbn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shzxlz.cn/Article/details/gt2wlwphdlr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2iepwuoro.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2tmibuvoa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hesoyunp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gt2cuflqviz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iuetjoqw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2bjwhezcf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hywenlv.cn/Article/details/gt2wklexafx.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gt2mwehvoam.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gt2jsjpyszk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gt2gnjigmfb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gt2durjethu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gt2xakewqyd.html

Go:   encoding/gob
来源：http://dali.zhongyouzk.top/Article/details/gt2kzdkqclk.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvujbrdr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gt2dznozcrh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2gejxpchv.html

L. 网络请求
来源：http://dali.quarkkingdee.top/Article/details/gt2wxavqaly.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2plwynqsy.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gt2gvcfvisc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gt2ezqldkod.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yangfankeji.com/Article/details/gt2rmteyvje.html

JS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gt2wkhjhqmp.html

TS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gt2rjnqasfa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gt2wbigpmnz.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gt2vfixsrix.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgufenzy.top/Article/details/gt2ujpmjekl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gt2uifsffwj.html

[L02] 发送 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2iuwddqop.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grnmycbz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yueranfly.top/Article/details/gt2fcocrrxi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gt2peolufbl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gt2nfiydbol.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ybcxt.top/Article/details/gt2viidgbue.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gt2xspfjfmv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gt2edniqxhv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jyoumei.cn/Article/details/gt2lwutcpav.html

[L03] 设置自定义请求头
来源：http://dali.nanxuanxn.top/Article/details/gt2qaqriiev.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hecndnqb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cqqwz.cn/Article/details/gt2bevitgmy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vozgcljt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gt2uvgkfuzr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxuanxn.top/Article/details/gt2fnkerbbw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gt2xqxkztmn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnxiangtu.top/Article/details/gt2fofyzils.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gt2cxprevng.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gt2miquefrv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cashguo.top/Article/details/gt2mwqlrnkr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gt2sujjxwwo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gt2hwutcnfh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2cbfhhriv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gt2ocwxnzrp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gt2eciecxvg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gt2lnqzfrnp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gt2rtvdmgme.html

[L05] 上传文件（multipart）
来源：http://dali.wangdashe.top/Article/details/gt2mzutvfcd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nwbrower.top/Article/details/gt2pyyshbmz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gt2upjthtnp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gt2vthiyuoz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gt2sxiiclpp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cucudq.cn/Article/details/gt2lbrjbnar.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2robzwqdj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xinyue.icu/Article/details/gt2qwcrxpun.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2rjnsaqbi.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gt2tajcrjrh.html

Py:   resp.json()
来源：http://dali.hywenlv.cn/Article/details/gt2yojcjplq.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gt2vdnvzibt.html

JS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlnotflp.html

TS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zdmdfncz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xinyue.icu/Article/details/gt2hldwebau.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nfizrokl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gzhubu.top/Article/details/gt2wtncgkeh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hywenlv.cn/Article/details/gt2bvkuyyle.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gt2nhipspcm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gt2lmjdzjez.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gt2vbyykpfe.html

JS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gt2oaemugvs.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jewnhazh.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gt2hpcvayhm.html

Go:   resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2cporltjo.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gt2gkscmtun.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2vevtrizs.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gt2etcaqcac.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.316326.xyz/Article/details/gt2nnndromy.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lgmbedvj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2xwfiqcnc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qiytzeuu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gt2kxpeufdj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.316326.xyz/Article/details/gt2xjidwknr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gogol.net.cn/Article/details/gt2qatqqrzi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daria6918.cn/Article/details/gt2bcpwwujh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2jseiokwm.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258888.top/Article/details/gt2fwmmtukk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2hpuxkver.html

[M01] 读取命令行参数
来源：http://dali.zycfv.cn/Article/details/gt2rdxkfzoz.html

Py:   sys.argv[1:]
来源：http://dali.fzhhl.top/Article/details/gt2ldbcjkgb.html

PHP:  $argv;  $argc;
来源：http://dali.dashuyun.cn/Article/details/gt2idfubdwc.html


<!-- 参考信息 -->