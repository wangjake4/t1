代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gtxgsepfbx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtmgguozto.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gtneaxcntq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtyoyvosbh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnabudwob.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sufxvd.cn/Article/details/gtyhmxrbtp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtnabimlnq.html

[I05] 按正则拆分
来源：http://dali.hnxiangtu.top/Article/details/gtoxtrjhwh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jianghu66.top/Article/details/gtmqypneav.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuxming.cn/Article/details/gtcayfqlia.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtifcpmaaa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtmuujfakx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuxming.cn/Article/details/gtbxopxyvx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shuidangran.top/Article/details/gtpymcvkbx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtpcsnmkzd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guowangkeji.top/Article/details/gtcasixdja.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gtawxkrwyt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gteodfnekh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yongpay.top/Article/details/gtpoffcymd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgztgllsv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtkfidfgpo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtzihjhjau.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.svipenyu.cn/Article/details/gtimxgezvy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gtezbemias.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtnrhaqzab.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gtxlzinaif.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gtmguxbleo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gtrzfzaonc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gtstrsqzfv.html

TS:   /error/gim
来源：http://dali.cdnleiting.top/Article/details/gtyfuokpoa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.havefunace.top/Article/details/gtxdbsqvgr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gtpjmeqfva.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigufen.top/Article/details/gtozegeqpw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.bjfxy.top/Article/details/gtzgabbqpa.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tian-w.cn/Article/details/gtcdfodxsg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258.top/Article/details/gtocrkpeyb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gthqlfkzzk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gtovmjihaq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gtmmjpxley.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtsxgdkdpn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gtinlqwuln.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gtcndjqeov.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gtxevmddji.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqwcnodx.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gtujjdljyp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbwlfilzr.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gtonoqtywr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuetiantiany.cn/Article/details/gtqgktkwax.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gtdfdnirlm.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtwujaiffh.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gtewqxbvsz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jyoumei.cn/Article/details/gtrxpukglq.html

Go:   time.Now()
来源：http://dali.dianchejie.cn/Article/details/gttcyjvnqg.html

Ruby: Time.now
来源：http://dali.jianghu66.top/Article/details/gtocgmsoqm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gtkpiwcncj.html

[J02] 格式化输出
来源：http://dali.fengsongda.top/Article/details/gtgceyjtkq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtvrycavcg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gtruzasgbs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xylfe.cn/Article/details/gtkpitgtaz.html

TS:   d.toISOString()
来源：http://dali.gzhubu.top/Article/details/gtyguhojev.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jlsjyb.cn/Article/details/gtelnvhgsm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gthjvmhsfw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gturwairjf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuanzhike.top/Article/details/gtmbioiyvs.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gtfuuvzrqg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.iojbl.cn/Article/details/gtnzduatvz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.kuanghao11.cn/Article/details/gtoanmrvdo.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtxhmidgdu.html

TS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gthdsevidv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtpeppmqot.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtwbgtfqqm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtvdfxituy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hfpthk.cn/Article/details/gtivfoezdq.html

[J04] 时间戳与日期互转
来源：http://dali.birdmap.top/Article/details/gtsunbhfvf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sweek.top/Article/details/gtgtsfioup.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbcafllf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtssazcyid.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gtcnalafcf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pycfn.com/Article/details/gtmadrvfsd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtqyvqyihb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gtscgzgyfg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ybcxt.top/Article/details/gtnplismij.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gtmkaoznux.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gtxeugkiwe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ppjwa.cn/Article/details/gtibzvcaby.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtpjahncaj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gtkhasrnbl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtzyvoewap.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.vqdsnc.cn/Article/details/gtuwgzdsra.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jlsjyb.cn/Article/details/gtmohdplpp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhikjkzu.html

[J06] 计算两时间之差
来源：http://dali.daria6918.cn/Article/details/gtdcnfulqo.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvysoone.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gtoyafoftt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gtxfsoagbd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xinyue.icu/Article/details/gtxjkdryhz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gtigqsdfyd.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gtripdujsz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gtjhhqrzak.html

C#:   (end - start).TotalSeconds
来源：http://dali.zdqjudy.top/Article/details/gtbumywvte.html

[J07] 比较两个日期
来源：http://dali.haohaochexian.top/Article/details/gtppxvgjum.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbunzuztg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuanzx.com/Article/details/gtulgzqmqo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gtpbbrxmhu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtzfqexklm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxuanxn.top/Article/details/gtvwivitwv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtvgjwsnnk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtkxtmovqq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gttqmjvpuy.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gtdmsxexvz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gthlupsvop.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guowangkeji.top/Article/details/gthnszpogm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gtjsrwrqpz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.redwolf501.top/Article/details/gttosyumbc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gtlfqqzntq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yvedp.cn/Article/details/gtfyspjedb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ybcxt.top/Article/details/gtscuwmbwy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtujidfxoj.html

[J09] 时区处理
来源：http://dali.smart0.xyz/Article/details/gthxhrprpi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dianchejie.cn/Article/details/gtqitkrnkf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gtbycmtydv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtgrhwbzrw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtgfakxypf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hammf.cn/Article/details/gtrwlkdppc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxuanxn.top/Article/details/gtbreyykgx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gtwcyzkthd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dianchejie.cn/Article/details/gtenkliese.html

[J10] 取今天 / 本月第一天
来源：http://dali.hammf.cn/Article/details/gtfeohumna.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigufen.top/Article/details/gtyfoclyjv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenzaomai.com/Article/details/gteapqytqq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtzfcuhogh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtjtlqdgcv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cqqwz.cn/Article/details/gtwjcpbmlm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gtbqyrezkw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.iojbl.cn/Article/details/gtlzqdeteb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gotoacloud.top/Article/details/gtyumimteq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtrowjaplr.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gtjkkeoiwt.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtfqfpaqvo.html

[K01] 对象转 JSON 字符串
来源：http://dali.cdnleiting.top/Article/details/gtifxmrebx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtonnxixzk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtmdaponxh.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtlztevmyp.html

TS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gtgyzderkk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gtqzvqqzzl.html

Go:   json.Marshal(obj)
来源：http://dali.meibo888.top/Article/details/gtsklnuhwm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gtjdspwwjj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtioctcrai.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gtkoruchix.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gteckrrzlo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pycfn.com/Article/details/gtunpotikm.html

JS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gttcmsurpv.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtkxhhaqwp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtmihohaph.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvlnyhnf.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcrflpri.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gthhzsjbjs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtrtuswj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtqunllvqb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gtzgbzfvul.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtibxkyivh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtemfwseog.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cucudq.cn/Article/details/gtumadnsif.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gtxmjxjorh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtkffojoyg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gtrzcfangs.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gtzcupauio.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gtvadgyjfm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzzknalr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gtpslqenwd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjyemnnu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtfdzvsfvp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtjsfxjkwd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtuxonefom.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gtvxlrlpid.html

[K05] 深拷贝对象
来源：http://dali.dianchejie.cn/Article/details/gtwhjzsoin.html

Py:   copy.deepcopy(obj)
来源：http://dali.sysykeji.top/Article/details/gtpjqdrayc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gtlgdhliwy.html

JS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtevdyksgk.html

TS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtdcmexoey.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gtyjamrkoi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhengqikj.top/Article/details/gtiygxpafa.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gthfbuwvaz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.snrcjt.cn/Article/details/gthkjkqlpc.html

[K06] 解析 URL 查询串
来源：http://dali.yvedp.cn/Article/details/gtdvytzcge.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gtlfrbneev.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gtusdvyucm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtpwerdrej.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtkamdkrwv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ehwqpu.com/Article/details/gtfnyhwcjs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gthqnattlo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtyovjjzpd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtkzhaagcj.html

[K07] 进制转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevdhbags.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtidnfoqqa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhsatilt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtuprvybjx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtlxejxacx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcncdzbpp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shangyingyoupin.top/Article/details/gtaanyfnsn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yongpay.top/Article/details/gthaezfkqv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtqhjjshkv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gtkjvyczsu.html

Py:   pickle.dumps(obj)
来源：http://dali.meibo888.top/Article/details/gtqrrqpbuf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zdqjudy.top/Article/details/gtwpwdtwon.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gtomfdeapr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gtsrhougtq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jiagoushi.top/Article/details/gtszcndzfz.html

Go:   encoding/gob
来源：http://dali.jiagoushi.top/Article/details/gtsmbvxgao.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gtilttwhkn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtlqnloata.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekchzuvc.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gticqrgicl.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxftoroj.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gtrsrrkauc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cashguo.top/Article/details/gtrtdvtexe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigufen.top/Article/details/gtnigaznpi.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxpjfbhs.html

TS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gtjtpbpsnx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhsietwn.html

Go:   resp, err := http.Get(url)
来源：http://dali.ybcxt.top/Article/details/gtrnohrske.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gtzkjggetd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gtnzyggvoo.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtubamxofw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtbqsgbnek.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gogol.net.cn/Article/details/gtdlnqhmbr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtlsylalav.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gtpyafjfyb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gtkjpcipzh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fzhhl.top/Article/details/gtbggywzoo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sxryk.cn/Article/details/gtsdftizbg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aibaodan.cn/Article/details/gtlfsgnoak.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gtjjisykir.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gtyxdtauhj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shuidangran.top/Article/details/gtzbquhjvj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtkrufbosq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gttggmhibm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gtpltpxvrl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtsfrhkbtw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gtxyivqnvz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtniyqtnpv.html

[L04] 设置超时
来源：http://dali.hnxiangtu.top/Article/details/gtuvswwdsr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shangyingyoupin.top/Article/details/gtcboxhcjl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ybcxt.top/Article/details/gtqyvybbxj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtpcgsqfgl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gtwntvtfug.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gtfqvstqde.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gttsmlmpqt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnxiangtu.top/Article/details/gtvssdhfmu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gtogzllzji.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gtqbwcezfj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gaohongyu789.top/Article/details/gtxhmcrfhi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hfpthk.cn/Article/details/gtwsclnqef.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtkckpxoov.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gtzymaczkb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gtxafcnsmb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.smart0.xyz/Article/details/gtglhyttus.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xinyue.icu/Article/details/gtkppokmkx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gthsbjspne.html

[L06] 解析响应为 JSON
来源：http://dali.hammf.cn/Article/details/gtzoaexdtt.html

Py:   resp.json()
来源：http://dali.yj202588.top/Article/details/gtjcjxlwwj.html

PHP:  json_decode($body, true);
来源：http://dali.sysykeji.top/Article/details/gtxukbwywu.html

JS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtszjxhmhf.html

TS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtcrqmokdz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtwlmdwiqn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tian-w.cn/Article/details/gtpelskgfw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gthphvclgt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sysykeji.top/Article/details/gtegkkojrh.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtpesqpqmq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yangfankeji.com/Article/details/gtafdxdoao.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gtyhfsltir.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtlhwshmgs.html

TS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtqmaqxlex.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gtuhwsquid.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gtxsuwezam.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gthkahxmbt.html

C#:   (int)resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gtvqneknnl.html

[L08] 并发请求多个地址
来源：http://dali.zycfv.cn/Article/details/gtmtftzqfc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fzhhl.top/Article/details/gthoakituf.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gttfeyjryo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtvpdbjysw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gthxytozwc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yvedp.cn/Article/details/gtknxovxiw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gtwdwztxpw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gtsngivsds.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cqqwz.cn/Article/details/gteqaunxzh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gttpsvtbyi.html

M. 命令行 / 进程 / 环境
来源：http://dali.yueranfly.top/Article/details/gtinxzjmpi.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtcgbvfxql.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtxqsmkhgb.html

Py:   sys.argv[1:]
来源：http://dali.aibaodan.cn/Article/details/gthisitwya.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gtawrslamc.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtirxqllyb.html

TS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gtuhyckdhv.html

Java: args 数组（main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gtwldgpyqq.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtauwrinbl.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gtwlfxlklb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtykbpbwes.html

[M02] 读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gtciqllgir.html

Py:   os.environ.get("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtdboxxtjv.html


<!-- 参考信息 -->