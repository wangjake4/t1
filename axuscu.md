代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sweek.top/Article/details/gt2vusvejqp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.redwolf501.top/Article/details/gt2kmeqrhcv.html

[I04] 正则替换
来源：http://dali.kuanghao11.cn/Article/details/gt2gjyaedzz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2elqbudoe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gt2xhethgul.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2dommfdfg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2lylqrtoa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2nidgcqoe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigufen.top/Article/details/gt2oprrlcpu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2ndwevzdp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gt2imzxnesl.html

[I05] 按正则拆分
来源：http://dali.chenzaomai.com/Article/details/gt2dxtsytux.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnqzz.top/Article/details/gt2rihwjwkc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2rcxxipdu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gt2koamiqeb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qikxvwzp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gt2vonmlaxv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cheryme.top/Article/details/gt2gkhdaasv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gt2qbludpnb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gt2ldjamekf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gt2twloixca.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2niubmihs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gt2mclfcxiq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gt2fzetzgks.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gt2kdypacqv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gt2wyyzdkrm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guowangkeji.top/Article/details/gt2btqhiccc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2spfxyymf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2ylbbmtjr.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdxitmrg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gt2ekeidiip.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gt2gqpocitx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangshuangyany.cn/Article/details/gt2entdukvk.html

TS:   /error/gim
来源：http://dali.svipenyu.cn/Article/details/gt2bfzbilsr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.snrcjt.cn/Article/details/gt2dydkttpr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.smart0.xyz/Article/details/gt2umlatdwi.html

Ruby: s.scan(/error/i)
来源：http://dali.pycfn.com/Article/details/gt2cjxvwwdj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gt2fdqzswzq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258888.top/Article/details/gt2pliyrbkc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jianghu66.top/Article/details/gt2iwvbsmml.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gt2cbsdaict.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gt2iuwtsibi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gt2ipdzbzix.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gt2alsqosnz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.c1oappe.top/Article/details/gt2jqhwjrwn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sysykeji.top/Article/details/gt2hvjtyqbk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gt2yjoppvhb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2aalhzfzw.html

J. 日期与时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2joytktfc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2rfvjphar.html

[J01] 获取当前时间
来源：http://dali.tianlin.xyz/Article/details/gt2qpjbnsea.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccajhkwd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gt2rcdhwdte.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gt2siopesgf.html

TS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gt2dowrzycb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.havefunace.top/Article/details/gt2uiutunef.html

Go:   time.Now()
来源：http://dali.jlsjyb.cn/Article/details/gt2ospvpqsi.html

Ruby: Time.now
来源：http://dali.yanxiufei.cn/Article/details/gt2jewwuzfz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dxyvmzlt.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gt2iodaziuo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzrdbfyx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gt2mgortxvr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sufxvd.cn/Article/details/gt2txxklgow.html

TS:   d.toISOString()
来源：http://dali.xinyue.icu/Article/details/gt2djrcqgyg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gotoacloud.top/Article/details/gt2podbyoxt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gt2ueluwppt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gt2muekaiev.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sufxvd.cn/Article/details/gt2wbexmhjg.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gt2evbacoom.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sweek.top/Article/details/gt2dztltyih.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2grheoxdm.html

JS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2ylvwagld.html

TS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2zfqtbkpp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2vzjdicol.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2rjdfjpos.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2msnkpmiy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gt2yinhaaxm.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gt2cobrtlem.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymagdpsp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dianchejie.cn/Article/details/gt2rkymtgro.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gt2xortvzop.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.birdmap.top/Article/details/gt2caklyzuj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2ldlsvpvc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gt2ykxauoka.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258888.top/Article/details/gt2huogvmmh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2anaafexv.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gt2fgcbnogs.html

Py:   now + timedelta(days=7)
来源：http://dali.vqdsnc.cn/Article/details/gt2alruebdd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhengqikj.top/Article/details/gt2mdkfzher.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gt2pemzkmrh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gt2hlhmaeot.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ppjwa.cn/Article/details/gt2siytursf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xitjglhu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuetiantiany.cn/Article/details/gt2mnskjjtc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gt2qtmnijxg.html

[J06] 计算两时间之差
来源：http://dali.snrcjt.cn/Article/details/gt2oeptynin.html

Py:   (end - start).total_seconds()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ilipcibx.html

PHP:  $end->diff($start)->days;
来源：http://dali.dianchejie.cn/Article/details/gt2zdhoifzn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gt2uiqevqoa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gogol.net.cn/Article/details/gt2nvoxgpga.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gt2pmhwtqru.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gt2iargyrmg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258888.top/Article/details/gt2xlhccoep.html

C#:   (end - start).TotalSeconds
来源：http://dali.andypj.xyz/Article/details/gt2uobytcul.html

[J07] 比较两个日期
来源：http://dali.yueranfly.top/Article/details/gt2vergogrg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tdvnvums.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cheryme.top/Article/details/gt2eqadhqpz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gt2xooivdnw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gt2zzggggat.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xjxyhddj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cqqwz.cn/Article/details/gt2gukbtbib.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gt2toqjvawf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gt2hthpqwcw.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gt2hvuqwdgr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guannengcc.top/Article/details/gt2lmxrrzxv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuxming.cn/Article/details/gt2qiwvfkmp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.redwolf501.top/Article/details/gt2grugqxhe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jyoumei.cn/Article/details/gt2sobczfvq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvjrhofj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gt2txvavsbs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.redwolf501.top/Article/details/gt2jizveexb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xziqi.cn/Article/details/gt2ppfyyvjo.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gt2philczcx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yueranfly.top/Article/details/gt2qbcpiyct.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fengsongda.top/Article/details/gt2uslvtiyo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gt2efdcymyd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gt2zzvubwoh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tian-w.cn/Article/details/gt2ahgowetp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.havefunace.top/Article/details/gt2offmdcap.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.mhx1999.top/Article/details/gt2ucmfkvxa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.kuanghao11.cn/Article/details/gt2dntrmwby.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqielcsb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gt2reexppiw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gt2lqtebmoe.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2wiyqelgz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2cvckiagc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gt2gzxpncqv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gt2inqiqmqn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gt2dazqmrdq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ppjwa.cn/Article/details/gt2rcqstrej.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2eeyvjvel.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gt2cvwvnusi.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ujmlrorf.html

[K01] 对象转 JSON 字符串
来源：http://dali.gzhubu.top/Article/details/gt2iwhsjsiy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gt2zempzwuk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gt2ereiriem.html

JS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtjigkbi.html

TS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gt2hynukyqp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hywenlv.cn/Article/details/gt2hzgajqpi.html

Go:   json.Marshal(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2upvhwfnr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tanke756.top/Article/details/gt2tssdbqty.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2eahdwlsa.html

[K02] JSON 字符串转对象
来源：http://dali.vqdsnc.cn/Article/details/gt2doyjwbps.html

Py:   json.loads(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qyicrvfz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yongpay.top/Article/details/gt2vfkacolc.html

JS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2esmemiyg.html

TS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2tjjtcfgg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2devhceld.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gt2ucaumwho.html

Ruby: JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2tjdowqmc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gt2jxoudlyi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjoztfsj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gt2nihlngvq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnuyeyzb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwtwpiif.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2borqpdcu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.iojbl.cn/Article/details/gt2gqfsgyvi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zchbsoqw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2uqbjbnub.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gt2ljxgcgsq.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gt2iunvhpll.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2naufcxkk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.andypj.xyz/Article/details/gt2sgklowfj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zrsgeeyx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gt2gfmxzosn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2yswgihol.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gt2ezuqvvln.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yongpay.top/Article/details/gt2dgxteito.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tian-w.cn/Article/details/gt2susjqsgi.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gt2itlzyoqp.html

Py:   copy.deepcopy(obj)
来源：http://dali.xziqi.cn/Article/details/gt2iqjcjxbo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gt2hhbxomir.html

JS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2oisdrwgk.html

TS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2zxevbtbi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.316326.xyz/Article/details/gt2klxuammz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gt2ovfwpfmr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xylfe.cn/Article/details/gt2nftnlksd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ybcxt.top/Article/details/gt2lvjdgolu.html

[K06] 解析 URL 查询串
来源：http://dali.vqdsnc.cn/Article/details/gt2pqmspdfv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbxijybf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fzhhl.top/Article/details/gt2invysrua.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gt2xohircpo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gt2lrsawrqq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cashguo.top/Article/details/gt2zbfkdvnz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2osvtlrxi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2bgyjowuf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gt2pmpiwefw.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwwzypa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2nxkhhxeh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.havefunace.top/Article/details/gt2caukvnyp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2tzawtioj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2kifrmewa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2lvagbeej.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnxiangtu.top/Article/details/gt2wpymphgd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2udmynejs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2rxjxafcr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.quarkkingdee.top/Article/details/gt2upyzyeij.html

Py:   pickle.dumps(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2lydnhutk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ybcxt.top/Article/details/gt2rajrcirn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gt2dkjfkexx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2xqpxyofi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.smart0.xyz/Article/details/gt2nivquemj.html

Go:   encoding/gob
来源：http://dali.yj20258.top/Article/details/gt2nchrorsl.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gt2qccdltoz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gt2nrvkpqih.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2migzrqrq.html

L. 网络请求
来源：http://dali.yj20258888.top/Article/details/gt2yhuiptfd.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwmcegqf.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gt2iacnjlyu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.havefunace.top/Article/details/gt2roieerga.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.iojbl.cn/Article/details/gt2fiovuejt.html

JS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gt2tahnqeag.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmbqvmya.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gt2mbojrwog.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gt2uthlbnqd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj202588.top/Article/details/gt2urqxzfae.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigufen.top/Article/details/gt2coodaiak.html

[L02] 发送 POST JSON
来源：http://dali.yj20258.top/Article/details/gt2nwjjqqhn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gt2cugkictd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.andypj.xyz/Article/details/gt2wsfjcpwy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gt2qybtglfg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gt2rcqortcd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangdashe.top/Article/details/gt2kkalojhj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gt2apxobrib.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtlwwce.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shzxlz.cn/Article/details/gt2piccklll.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2mkeqixeq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhoulong.xyz/Article/details/gt2bezlnvbh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffanklyn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gt2yfbovrya.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gt2tweffekq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.haohaochexian.top/Article/details/gt2dkflopbv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gt2eqxdvyuc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cqqwz.cn/Article/details/gt2hbmlymzq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gt2zgfkojhs.html

[L04] 设置超时
来源：http://dali.nwbrower.top/Article/details/gt2ipreejdb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.andypj.xyz/Article/details/gt2uwbabiuk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gt2stfvbaya.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gt2kggpndmf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gt2brmbjfao.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.svipenyu.cn/Article/details/gt2skvfqfvy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfirovug.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgfzy.top/Article/details/gt2gobbqsxj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.vqdsnc.cn/Article/details/gt2supdrhgg.html

[L05] 上传文件（multipart）
来源：http://dali.cheryme.top/Article/details/gt2edraxoyi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ssylivsd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gt2zvjkzsfm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gt2pqckossf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gt2qnifivvc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gt2lcktizqq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gt2jpgytjfr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.0kj1m.cn/Article/details/gt2ohbfzxfy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gt2somxolcp.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gt2jhdgisxz.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2drgvgqis.html

PHP:  json_decode($body, true);
来源：http://dali.sufxvd.cn/Article/details/gt2rpqpkadn.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2aqcgokpb.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2apgkypoy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.andypj.xyz/Article/details/gt2akfgcxzi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gt2frhebxvf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gogol.net.cn/Article/details/gt2vosvavdo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gt2lhjmgpak.html

[L07] 处理 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrtktviz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ppjwa.cn/Article/details/gt2rqxoafuo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gt2znlzdsto.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjerjjfi.html

TS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gt2amobesqg.html

Java: resp.statusCode()
来源：http://dali.meibo888.top/Article/details/gt2hibqyhrj.html

Go:   resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gt2zojdxeeg.html

Ruby: resp.code.to_i
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqgfuljg.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gt2sejptzil.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gt2vzxehobl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fzhhl.top/Article/details/gt2tlagtofh.html

PHP:  curl_multi_init() 系列
来源：http://dali.hywenlv.cn/Article/details/gt2jmfavbcr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2vcteikoe.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gt2pqgtvqfp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cucudq.cn/Article/details/gt2zgmtmzva.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pycfn.com/Article/details/gt2oeqzipjz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ivvv.top/Article/details/gt2pwhqzvqu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gt2ishozsex.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2gcpejpcu.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gt2gaixyxxm.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2dlfrojdb.html

[M01] 读取命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gt2umfyrjxm.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gt2peucwher.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gt2mrfikgfd.html

JS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gt2zpmvwusz.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gt2eanmamwb.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gt2wydhzlwo.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2awwpibee.html


<!-- 参考信息 -->