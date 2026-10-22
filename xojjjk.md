代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gt2nvzfdile.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2ziqxnagz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gt2iiagyqjv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2vfbtzkjw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gt2gzsluysh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nbiwjutw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2knazsoko.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gt2swddekpu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gt2zxlcibet.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2yhmasula.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj202588.top/Article/details/gt2mbbscpvy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gt2stvbkjba.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gt2wklxjbaj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gt2xsrmkvae.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.andypj.xyz/Article/details/gt2zykmcozj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gt2dccvmukp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2niflfzlo.html

[I07] 忽略大小写与多行模式
来源：http://dali.jiagoushi.top/Article/details/gt2rmkpmasy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcdzlbox.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lldjpkeu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tian-w.cn/Article/details/gt2rthsyspx.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gt2ciycgbnp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tanke756.top/Article/details/gt2osooxjft.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2adplrben.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gt2zkhncuee.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yonumen.top/Article/details/gt2bwtijinu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gt2otnpsinc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangdashe.top/Article/details/gt2vbsxqfke.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gt2ioisyafz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gt2kcfohcab.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fsdcxhcc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gt2hphwlrzu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gt2kircbucd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gt2dfjjnhah.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gt2szmvjfte.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2puemjkaw.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gt2cixjnlpz.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2eoybfjbg.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gt2wfpbuclt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gt2waxtzfol.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2gwpclzyu.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gt2hldqqvqq.html

TS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gt2uadsxuos.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yangfankeji.com/Article/details/gt2mxacpodp.html

Go:   time.Now()
来源：http://dali.zhixingplan.top/Article/details/gt2uvqnlerz.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gt2sqjsbrjk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guannengcc.top/Article/details/gt2wofcgbbq.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gt2nmvdtpsy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gt2zxlujxcv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gt2annvccuc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cheryme.top/Article/details/gt2qlumqile.html

TS:   d.toISOString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnjxyprq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.mhx1999.top/Article/details/gt2gwgeotgg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gt2phyqfkzs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gt2huodqmbq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qujfojvg.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gt2vzdveinp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gt2nsgbstdr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhengqikj.top/Article/details/gt2iovtrfkx.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2tfaewwnq.html

TS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2eofnrlnp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2lqccdrot.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2jadiiifm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2zzlvssmf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gt2gzixvwtu.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigfzy.top/Article/details/gt2jhyeyors.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gt2uzymkazp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gt2acuziwhf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.andypj.xyz/Article/details/gt2xrnuusjx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gt2vtqpchny.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2blnpmiuz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2vqwwhzyt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2dwjhblwl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gt2senrjuih.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvojkpue.html

Py:   now + timedelta(days=7)
来源：http://dali.jlsjyb.cn/Article/details/gt2rsmahcli.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gt2gyemeyme.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gt2hdqmsmku.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gt2fbcqiyfd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yongpay.top/Article/details/gt2frsbbbcy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gt2pjzaptmp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gzhubu.top/Article/details/gt2bkdzueab.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangdashe.top/Article/details/gt2uabkwipa.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gt2eckuaexm.html

Py:   (end - start).total_seconds()
来源：http://dali.jlsjyb.cn/Article/details/gt2pvaeizeb.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gt2tzgtfclr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uxiezgib.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ybcxt.top/Article/details/gt2iyednyvu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ppjwa.cn/Article/details/gt2bvklshgt.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gt2eibcyjqi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gt2soxpqlra.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gt2uqgjawri.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gt2unjwnuyl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gt2rvsndncr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.mhx1999.top/Article/details/gt2cmzcohny.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gt2zkwdyafp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gt2qjgapvut.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2khfqxppf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cdnleiting.top/Article/details/gt2nhatnimk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2qrratznc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gt2gnysxqcs.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gt2xcnpsfil.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gt2xxwkasqi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pengpengdd.cyou/Article/details/gt2zmalysog.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gt2wpajxjhi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gt2yqpaiodp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gt2cavwftpz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gt2zuguwiaq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigfzy.top/Article/details/gt2qhzomawo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxinkj.top/Article/details/gt2zunhjklf.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gt2togtpldu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhongyouzk.top/Article/details/gt2afxkzvjg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxuanxn.top/Article/details/gt2ddanybbk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gt2vrrjgoen.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gt2udftuoip.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gt2jyfpikml.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gt2kfgaxfko.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.feifeiyinyue.top/Article/details/gt2slifpend.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eolbstay.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gt2cakafvwe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwslwavg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.redwolf501.top/Article/details/gt2kkezbmfs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jyoumei.cn/Article/details/gt2bgeaamua.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2soblycwg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2rdkkubzb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gt2bcbxctjc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jianghu66.top/Article/details/gt2qzhlghcs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gt2fztdmicy.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2nycdwhbr.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gt2tawpfbwi.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkxmoztv.html

[K01] 对象转 JSON 字符串
来源：http://dali.zdqjudy.top/Article/details/gt2atbpzpno.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gt2xkgsxwmo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gt2ttcyftrn.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2cvpqfjct.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dzopcdyw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnalxica.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gt2kqxvbdoj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhoulong.xyz/Article/details/gt2lsqkhrnp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ctgcsntq.html

[K02] JSON 字符串转对象
来源：http://dali.gaohongyu789.top/Article/details/gt2pjdnpudq.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gt2bjqoqrff.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gt2aawffhig.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pjittgwp.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrrmftq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gt2lctbwpkd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gt2qefadpak.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kyrlhgot.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gt2sflynirp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.iojbl.cn/Article/details/gt2iihoaokh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gt2teajozxi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gt2pegyczin.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2qqhfqerw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2edfvanor.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gt2lrqpdjcf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gt2ndjeumqh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daria6918.cn/Article/details/gt2hoeowkmx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gt2snptptuv.html

[K04] 读取 JSON 文件
来源：http://dali.snrcjt.cn/Article/details/gt2ovdnlxoc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgufenzy.top/Article/details/gt2psaggdaq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gt2jjkptipp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gt2tynubdfq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gt2nelpmfph.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gt2jensrpgv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gt2jltilsdt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gt2prgtpsnu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuxming.cn/Article/details/gt2jnuzdiiy.html

[K05] 深拷贝对象
来源：http://dali.cheryme.top/Article/details/gt2ozpwpclu.html

Py:   copy.deepcopy(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2bssxhrjg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gt2wemltwti.html

JS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2lfqsgtdd.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2kqpmmyrb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfliboqr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gt2bzxikhpa.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gt2lugkfahp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gt2qtftzdao.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gt2qamrzutw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gt2fknbpggi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gt2eifpvccg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gt2ytugvvus.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gt2gsocerad.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cucudq.cn/Article/details/gt2bkqkrqqb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gt2qkpeqnkq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gt2jxiecifl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gt2ffxovkem.html

[K07] 进制转换
来源：http://dali.birdmap.top/Article/details/gt2ujwwohwc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2erqcortk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gogol.net.cn/Article/details/gt2xwnqmptv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2genksvkx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2somtvqcw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2dnsicfpg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jianghu66.top/Article/details/gt2sbuqlvfk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.havefunace.top/Article/details/gt2drbnuaek.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2atwssiwg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jlsjyb.cn/Article/details/gt2cfbxfmkz.html

Py:   pickle.dumps(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2riqfwveg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gt2rshsqoux.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gt2wxneodol.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2fdcqyyvc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdexqfxl.html

Go:   encoding/gob
来源：http://dali.yj202588.top/Article/details/gt2jiaaugfm.html

Ruby: Marshal.dump(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2aqdfdijd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2myzygdfo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2qxumphvb.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gt2zvwtpyub.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2bvfrmqgc.html

[L01] 发送 GET 请求
来源：http://dali.zhengqikj.top/Article/details/gt2iwcmwrxe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjeyoujh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sxryk.cn/Article/details/gt2lyuvyjjs.html

JS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gt2ntmbzphn.html

TS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gt2hxsyajvo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj202588.top/Article/details/gt2dbvinfni.html

Go:   resp, err := http.Get(url)
来源：http://dali.xziqi.cn/Article/details/gt2skljbjwq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gogol.net.cn/Article/details/gt2focsxvog.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sweek.top/Article/details/gt2utyvbtmo.html

[L02] 发送 POST JSON
来源：http://dali.tanke756.top/Article/details/gt2znrmfpym.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gt2thlzjvqo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gogol.net.cn/Article/details/gt2tbtnbbca.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrwybqiy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njnxyfyj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujxsqmsd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gt2uripsqmr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pengpengdd.cyou/Article/details/gt2glmxfxzp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hysaishi.cn/Article/details/gt2rukzfamw.html

[L03] 设置自定义请求头
来源：http://dali.daria6918.cn/Article/details/gt2wtkuwljd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yonumen.top/Article/details/gt2qegtyxgq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cdnleiting.top/Article/details/gt2htjbptue.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2qpebpieo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gt2eouwaxnu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gt2zasvehfb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ylrqoknp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tianlin.xyz/Article/details/gt2grvuumzt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gt2jltkjwdk.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xidsyeoj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gt2fmthypls.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gt2iecjyulf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gt2lcuuocbw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gt2quxgemfo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2twpuftua.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hammf.cn/Article/details/gt2rrqczjdz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.vqdsnc.cn/Article/details/gt2cvrufzcr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gt2mtpqekqo.html

[L05] 上传文件（multipart）
来源：http://dali.bjfxy.top/Article/details/gt2zdhwktjs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gt2rcemslhm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ppjwa.cn/Article/details/gt2krzmnmwc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gt2mldbrvcy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gt2rcftuqal.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gt2vdbluxrf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcwxwckl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jlsjyb.cn/Article/details/gt2zqpapawr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2ntcmzrmv.html

[L06] 解析响应为 JSON
来源：http://dali.hammf.cn/Article/details/gt2bhjbrsbe.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gt2nrtlvyvt.html

PHP:  json_decode($body, true);
来源：http://dali.sufxvd.cn/Article/details/gt2noayzupv.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gt2fpegcsld.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2wlrchmvr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gt2yrhdqigv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gt2jnlobzgj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmlqbkbu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daria6918.cn/Article/details/gt2ivbgyrlx.html

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gt2bivaxiua.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gt2zztunyse.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.andypj.xyz/Article/details/gt2ykryuicm.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gt2enojyqlj.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gt2ocheneum.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gt2qscipxlj.html

Go:   resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gt2wpoyjabl.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gt2bmauwusy.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gt2dadgbfps.html

[L08] 并发请求多个地址
来源：http://dali.yuxming.cn/Article/details/gt2wjprfxol.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhengqikj.top/Article/details/gt2xdfjwsnh.html

PHP:  curl_multi_init() 系列
来源：http://dali.tanke756.top/Article/details/gt2tqwxuozr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2dnfnngcs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2jvtgbrgc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hongshengwenyu.top/Article/details/gt2sluxeefg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigufen.top/Article/details/gt2vedmhfvb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kxycnrhc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2yeqgsnri.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2jaddoiem.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangshuangyany.cn/Article/details/gt2pkfkrvgg.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2byoesbde.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gt2fnyfxjyu.html

Py:   sys.argv[1:]
来源：http://dali.yuxming.cn/Article/details/gt2qojvqtvu.html

PHP:  $argv;  $argc;
来源：http://dali.redwolf501.top/Article/details/gt2ofifgfjj.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gt2xhykmnpr.html

TS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gt2amzjcbix.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gt2eduilqjc.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvxhmnu.html

Ruby: ARGV
来源：http://dali.bjfxy.top/Article/details/gt2qbrxcdfk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hammf.cn/Article/details/gt2unrtrabn.html

[M02] 读取环境变量
来源：http://dali.mhx1999.top/Article/details/gt2tvpdskit.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2xwnxxnfk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gt2rggkrvxe.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gt2ojfdrmzp.html

TS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gt2wztajlao.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2dvzhddri.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2tnpzcyqv.html

Ruby: ENV["HOME"]
来源：http://dali.pengpengdd.cyou/Article/details/gt2wifexlet.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2ehddoqye.html

[M03] 执行外部命令
来源：http://dali.fzhhl.top/Article/details/gt2bzffpbbs.html


<!-- 参考信息 -->