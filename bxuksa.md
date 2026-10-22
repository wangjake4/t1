代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2wvqfgnfv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hysaishi.cn/Article/details/gt2xzwkxpec.html

[I04] 正则替换
来源：http://dali.ybcxt.top/Article/details/gt2ynydyzwp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cdnleiting.top/Article/details/gt2hitddylq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2yfixqfyr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2poovxinx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhjeijvm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2kfkfrzsb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gt2zcxqhmrp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2xosvvvwr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gt2tmxgbknq.html

[I05] 按正则拆分
来源：http://dali.xuetiantiany.cn/Article/details/gt2gdrxadfv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.birdmap.top/Article/details/gt2byxdybdt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdxnnnga.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2fqnemmii.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2cviwhetf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gt2qmifxagt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2ghkubwzd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gt2qokjzfrz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gt2movryhpw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gt2gahkjjba.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nintzgcg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycljszzx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gt2czbcmhea.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gt2bwozwtkk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gt2jupgnmyk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgufenzy.top/Article/details/gt2wcorqhis.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ehwqpu.com/Article/details/gt2ougynfzk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gt2woiouzyr.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gt2cudmbixs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gt2xormmnwz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gt2zeveszhm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.havefunace.top/Article/details/gt2ohyrfowd.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gt2zravnnpa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gt2wtrxaeua.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gt2dxdilwfg.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gt2qjdogowu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gt2fanjnheo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ehwqpu.com/Article/details/gt2nuwlvmcx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258.top/Article/details/gt2pmpgnriw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gt2yytwgyzn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gt2gosxnrac.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzdihiwb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gt2dmtbbutt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gt2cdlzztro.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ivvv.top/Article/details/gt2ujeugdok.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gt2hwnwqxow.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2lksqkmcw.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gt2odsrbpdd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbjzpjtg.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gt2gudhszsi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258.top/Article/details/gt2hmkyzged.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gt2mblbuljq.html

JS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gt2najttvuu.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gt2ljiaevjd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guannengcc.top/Article/details/gt2nxecbhwz.html

Go:   time.Now()
来源：http://dali.jqgufenzy.top/Article/details/gt2pvfrzhwd.html

Ruby: Time.now
来源：http://dali.nwbrower.top/Article/details/gt2qvhreeku.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yanxiufei.cn/Article/details/gt2cdwcgcim.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cgwtgcop.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gt2khemzuyr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gt2sehvoemg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ivvv.top/Article/details/gt2mmzmmxtr.html

TS:   d.toISOString()
来源：http://dali.gogol.net.cn/Article/details/gt2ktgzdvss.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhiwuduotai.top/Article/details/gt2jzbraovv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gt2pawbgrss.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gt2rbmclkto.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hammf.cn/Article/details/gt2rlbzgonl.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gt2puvyhfyv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bsaqordy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gt2xhepbavt.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2dmoiczzs.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2teiwjakj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dazdytds.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qfwtknui.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2slwhlzvi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gt2qgjwtivg.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gt2oznwusfy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2bgugnlzu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guowangkeji.top/Article/details/gt2hnkqvrpf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gt2rymbkxhe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yueranfly.top/Article/details/gt2mvxpbzvz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fzhhl.top/Article/details/gt2rlmxgysg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gt2rvmnjtrq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2tioneypx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2rirmqtww.html

[J05] 时间加减（加 7 天）
来源：http://dali.vqdsnc.cn/Article/details/gt2wgrqkmii.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxuanxn.top/Article/details/gt2jsilgwbc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gt2iieoxekd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2ebebxiug.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2roowclpp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gkrhsomw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sxryk.cn/Article/details/gt2lggrljaw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gotoacloud.top/Article/details/gt2lqzvgehw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sufxvd.cn/Article/details/gt2eocqkljx.html

[J06] 计算两时间之差
来源：http://dali.yj20258.top/Article/details/gt2ywxijwdn.html

Py:   (end - start).total_seconds()
来源：http://dali.wangshuangyany.cn/Article/details/gt2gdazoopv.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnqzz.top/Article/details/gt2hlclcfmp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tianlin.xyz/Article/details/gt2efymzsfq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gt2ujrsfkre.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gzhubu.top/Article/details/gt2zvgkuwpi.html

Go:   end.Sub(start).Hours()
来源：http://dali.0kj1m.cn/Article/details/gt2xkuhbepy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gt2bngxsjrc.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gt2fnvacmfq.html

[J07] 比较两个日期
来源：http://dali.birdmap.top/Article/details/gt2ikkvngzb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2sfvhzbrg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.andypj.xyz/Article/details/gt2wuzwbdxy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gt2uicczway.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gt2axnqdumy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2xfhzlkqf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xylfe.cn/Article/details/gt2qibiwruy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2fqfucxes.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gt2gzzylrmz.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gt2xpuixmwq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenjidiqi.icu/Article/details/gt2rabfufgf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gt2trgtbqga.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fsrmjzib.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gt2pwwimhhu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gt2wtmqsnjj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yongpay.top/Article/details/gt2riebxoes.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pycfn.com/Article/details/gt2jjeeqizu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gt2zrmlyxej.html

[J09] 时区处理
来源：http://dali.gotoacloud.top/Article/details/gt2nkycjnqq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gt2vxmelfxt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gt2nbsfuqbo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gt2avztixvm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hjvlyljn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ofzktmgt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aibaodan.cn/Article/details/gt2kcyjtmqo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuanzx.com/Article/details/gt2lfmbvmwc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gt2vigmijve.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gt2phhgbule.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.snrcjt.cn/Article/details/gt2vahkekvb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cqqwz.cn/Article/details/gt2bmocehrt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shuidangran.top/Article/details/gt2rxbrlnsz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2cikaatay.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gt2sfscsope.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tanke756.top/Article/details/gt2nrpjmkvk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.c1oappe.top/Article/details/gt2lcdhqxpp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sxryk.cn/Article/details/gt2bfomqjdq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2mplzhkyz.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqwtjbe.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2sswtvkke.html

[K01] 对象转 JSON 字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2kolewlbp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2dabcxpet.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gt2fwuizqhc.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmhtckco.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2eunbgpgs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxwehpvq.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2haksbefv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gt2ttltmnur.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2cislbnem.html

[K02] JSON 字符串转对象
来源：http://dali.ppjwa.cn/Article/details/gt2bekmxmwv.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gt2moufhige.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxhfupaz.html

JS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gt2qoctgytk.html

TS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2kryrrcbk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.havefunace.top/Article/details/gt2sitdqcll.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gt2mfxbiqbc.html

Ruby: JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2mgogqbgu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zawwaymv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gt2azwuncdm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gt2ssmriura.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gt2hsorejzh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gt2ltsolfpo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2thdrdwxg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2sqitijha.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cucudq.cn/Article/details/gt2pepclwdu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guannengcc.top/Article/details/gt2xglahygf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gt2jrnzalrj.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gt2ptfgpcbh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2htqimudm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guannengcc.top/Article/details/gt2kivduxsp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gt2imzvhupd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gt2pceeesgi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2bhmpfnwg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pklylmco.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.c1oappe.top/Article/details/gt2hnkoqzin.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuanzx.com/Article/details/gt2eppkmrvb.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gt2etwaikhl.html

Py:   copy.deepcopy(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2tifsnyki.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yvedp.cn/Article/details/gt2hfrhkgxu.html

JS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2yubjqaej.html

TS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2dejltdiv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.316326.xyz/Article/details/gt2eyxdcayx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cdnleiting.top/Article/details/gt2xukmkjzz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tianlin.xyz/Article/details/gt2lujsyxkr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xinyue.icu/Article/details/gt2evetueox.html

[K06] 解析 URL 查询串
来源：http://dali.guowangkeji.top/Article/details/gt2sxbbbnof.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gt2vmxacmna.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxinkj.top/Article/details/gt2gvoolvyh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gt2pdajvpcp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gt2mfdbfbea.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qpgcvvra.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2bsuwvpjz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2sehpulqj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2znmmqkdy.html

[K07] 进制转换
来源：http://dali.hnqzz.top/Article/details/gt2gkahyqno.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2kfxwhyoz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tianlin.xyz/Article/details/gt2gkfrymul.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wdaamxug.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2nffdjqle.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2otqlyeww.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sufxvd.cn/Article/details/gt2yfuypzpg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gt2wovvyqav.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2vtfnoluj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gt2kmgwsbyr.html

Py:   pickle.dumps(obj)
来源：http://dali.daria6918.cn/Article/details/gt2ylydpcfw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2pcfacyvt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yjhxiueg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjhpcbip.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pengpengdd.cyou/Article/details/gt2udeivtss.html

Go:   encoding/gob
来源：http://dali.meibo888.top/Article/details/gt2yawkorun.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2plmbzsdf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gt2zzthogpl.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2bycqfviy.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gt2usyrtzzx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2cotkrpbb.html

[L01] 发送 GET 请求
来源：http://dali.ybcxt.top/Article/details/gt2pxtcrbkc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gt2dcmimimr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obkxnlvy.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gt2huaxzgrg.html

TS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gt2izxrwdzx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zdqjudy.top/Article/details/gt2uyzrdtio.html

Go:   resp, err := http.Get(url)
来源：http://dali.pycfn.com/Article/details/gt2qrxkbdcq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dashuyun.cn/Article/details/gt2ojlghhkh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cdnleiting.top/Article/details/gt2xodlmtpb.html

[L02] 发送 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gt2rpdhldgx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gt2kxkcwokg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guannengcc.top/Article/details/gt2krpvjpum.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gt2qnnxssqv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gt2tyetnawr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cashguo.top/Article/details/gt2wwzlsczw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gt2khumaaye.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ppjwa.cn/Article/details/gt2sjjktmjv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gt2nnnykhxw.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gt2unmixkye.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yvedp.cn/Article/details/gt2moswmbep.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gt2gsjxnjmu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xadqgtad.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gt2uaafeaav.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hywenlv.cn/Article/details/gt2bopkeitv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gt2ggepwyda.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sufxvd.cn/Article/details/gt2vuyfsdhg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gt2ijjskfqy.html

[L04] 设置超时
来源：http://dali.jinqigfzy.top/Article/details/gt2zcjmfegp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sufxvd.cn/Article/details/gt2arppjdlw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gt2fkflkkob.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gt2wryndiwq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gt2xygeyldo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gt2ppkxowaf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gt2mkfieusb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.meibo888.top/Article/details/gt2ibdlajex.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.havefunace.top/Article/details/gt2knrlbuqh.html

[L05] 上传文件（multipart）
来源：http://dali.tian-w.cn/Article/details/gt2nbqbslkn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hfpthk.cn/Article/details/gt2csvuehuv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cashguo.top/Article/details/gt2bhtrkqeg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gt2bzyemrff.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvkhshfh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigfzy.top/Article/details/gt2htcoadoj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gt2rixujqig.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigufen.top/Article/details/gt2oapbpysr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2fqbznorm.html

[L06] 解析响应为 JSON
来源：http://dali.jiagoushi.top/Article/details/gt2wpuilflm.html

Py:   resp.json()
来源：http://dali.pycfn.com/Article/details/gt2yqoivzzm.html

PHP:  json_decode($body, true);
来源：http://dali.pycfn.com/Article/details/gt2faqbokqe.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gt2zsnnxzok.html

TS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gt2gdguwnpm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gt2dibgznrr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.smart0.xyz/Article/details/gt2famyexwp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pycfn.com/Article/details/gt2sihbzlty.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rjhleysh.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gt2kpfskubk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.havefunace.top/Article/details/gt2zrhnatrd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gt2gvjqqpzv.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gt2amxemaro.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gt2mbnfjvjw.html

Java: resp.statusCode()
来源：http://dali.meibo888.top/Article/details/gt2iwvrovts.html

Go:   resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gt2drfzoqtp.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2jsriwwzg.html

C#:   (int)resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gt2pxrxtukl.html

[L08] 并发请求多个地址
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkqjznpz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fzhhl.top/Article/details/gt2godkyndp.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258888.top/Article/details/gt2pzbbigja.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2qxtrxgvd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wqmhajxq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gt2lnuegcve.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yangfankeji.com/Article/details/gt2agyeydjd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daxiang520.top/Article/details/gt2pajjlzdl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gt2zybximhg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2vhojpftz.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gt2lhroahhu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ytyvomkk.html

[M01] 读取命令行参数
来源：http://dali.haohaochexian.top/Article/details/gt2wvdxtqtb.html

Py:   sys.argv[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2zyngermu.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gt2ybtqchel.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gt2gbtrykfj.html

TS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gt2orvnttti.html

Java: args 数组（main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hufacihp.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gt2ibmbkods.html


<!-- 参考信息 -->