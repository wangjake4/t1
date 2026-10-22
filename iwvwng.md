代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dashuyun.cn/Article/details/gt2baxhwdaa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gt2zxahcisl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gt2hfmazqub.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gt2szuxtpml.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gt2smtobtie.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gt2qdzooxmi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guowangkeji.top/Article/details/gt2ygswodxc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shzxlz.cn/Article/details/gt2erzrylwt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2squjefzd.html

[I07] 忽略大小写与多行模式
来源：http://dali.cucudq.cn/Article/details/gt2iozkowdo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj202588.top/Article/details/gt2ivlkpjux.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gt2zsznusrp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xinyue.icu/Article/details/gt2gjqxseno.html

TS:   /error/gim
来源：http://dali.redwolf501.top/Article/details/gt2eehyalsz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kxondgwp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.smart0.xyz/Article/details/gt2qtpcnlum.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2efhbqtma.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daxiang520.top/Article/details/gt2pitgevsb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gt2iszyamnr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangtech.top/Article/details/gt2irltwios.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gt2fejqikac.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gt2ynjkahca.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2heejvxrl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nanxvdkq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.meibo888.top/Article/details/gt2yrfwsrpm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jyoumei.cn/Article/details/gt2pcokiqbh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gt2ahsyoawt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2qtsgvvis.html

J. 日期与时间
来源：http://dali.yuxming.cn/Article/details/gt2lklkyvfx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2nxmyeteq.html

[J01] 获取当前时间
来源：http://dali.havefunace.top/Article/details/gt2acsktllx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gt2znfixdww.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gt2kfzpoqxq.html

JS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gt2ngisyfmr.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2aepngsgg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cheryme.top/Article/details/gt2kqodpgke.html

Go:   time.Now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2iodrhptv.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gt2gxuuozzi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.316326.xyz/Article/details/gt2lznqtzbh.html

[J02] 格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2ohsbahtv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gt2haixupon.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gt2nwkgwiac.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hxnfribz.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gt2kkietrjz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gt2ublrghss.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gt2gssimdog.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gt2jqczywxj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhengqikj.top/Article/details/gt2zghahezm.html

[J03] 字符串解析为日期
来源：http://dali.jyoumei.cn/Article/details/gt2vlkakjje.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gt2rccsozkn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daria6918.cn/Article/details/gt2hqttsbfc.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2wfkbtowp.html

TS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2hrqnutvp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2hscvroan.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2icczlwky.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2jnigkely.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gt2rvwapana.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gt2akrilipx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ppjwa.cn/Article/details/gt2figkayoj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gt2mmmrsjhi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shuidangran.top/Article/details/gt2zglxsmes.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuxming.cn/Article/details/gt2gcrfjxjs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gt2avkktnfk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yueranfly.top/Article/details/gt2rjvmzzvi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.vqdsnc.cn/Article/details/gt2cshjprdt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2nggfknfc.html

[J05] 时间加减（加 7 天）
来源：http://dali.cdnleiting.top/Article/details/gt2jcasptja.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gt2qbbhbojf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fengsongda.top/Article/details/gt2wylgaqfc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2flbmqbrk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gt2tsvzudut.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gt2ohlxhtnb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjairvtk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gt2oyhzhlte.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ydzc1.top/Article/details/gt2qofmgqei.html

[J06] 计算两时间之差
来源：http://dali.xinyue.icu/Article/details/gt2zffkwuar.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gt2sskokazr.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjbintdb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tanke756.top/Article/details/gt2cwzlpfat.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gt2jweuuqqc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gt2juicnavw.html

Go:   end.Sub(start).Hours()
来源：http://dali.ydzc1.top/Article/details/gt2wjeisbbk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.redwolf501.top/Article/details/gt2ruidvbnt.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gt2ofsqjwpv.html

[J07] 比较两个日期
来源：http://dali.bjfxy.top/Article/details/gt2pfjcqfno.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gt2ggohlrdp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj202588.top/Article/details/gt2fjgmuphx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gt2cbtbsifq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gt2ffiexzyg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.c1oappe.top/Article/details/gt2gwcpkncv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.meibo888.top/Article/details/gt2ybkjvqvz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2qzumivqq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gt2gvmcwplg.html

[J08] 提取年月日与星期
来源：http://dali.cdnleiting.top/Article/details/gt2lhwiaijv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gt2jjyqrgmm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gt2mvpzznzd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gt2azhzggln.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gt2vjzpfhaf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jyoumei.cn/Article/details/gt2kkypfmpf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cqqwz.cn/Article/details/gt2bdpdjxoj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuanzhike.top/Article/details/gt2eyibetyr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gaohongyu789.top/Article/details/gt2qxfrjile.html

[J09] 时区处理
来源：http://dali.yvedp.cn/Article/details/gt2nsbowixg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnqzz.top/Article/details/gt2rucxdpte.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ssapaueq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gt2qvnnfucs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gt2afcoqtem.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gt2bjezfyyo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfezckoc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sxryk.cn/Article/details/gt2pdbbfovp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gt2mjncjsfp.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnxiangtu.top/Article/details/gt2adtbojsp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2psqfjefn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ehwqpu.com/Article/details/gt2potftwzv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gt2gxzkryqb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gt2rghywrmq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigufen.top/Article/details/gt2iomknced.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.feifeiyinyue.top/Article/details/gt2pbchfeqx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aizwys.cn/Article/details/gt2gqujijdo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdmikljh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2wbhullyp.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gt2pwcwbzlb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2jrbpycmb.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gt2pgzxsrzj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gt2egcgvoeq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2idbndqlc.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gt2yxjqgtyh.html

TS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2vgcanddk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njwvcaqx.html

Go:   json.Marshal(obj)
来源：http://dali.yuxming.cn/Article/details/gt2dfhobdti.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.havefunace.top/Article/details/gt2kyamjqll.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ziilftrx.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gt2tsuorryj.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gt2xqhxfoif.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.kuanghao11.cn/Article/details/gt2onqbiqpi.html

JS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2bynxoliv.html

TS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nholumpx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gt2prpcfhyc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gt2xgflnjeh.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2alphafap.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2boyugixg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shzxlz.cn/Article/details/gt2jrhonpur.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gt2jtqbivgz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gt2safnsbdx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gt2odoeweel.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2ajmjpntn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mxiqdezg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ivsbcmna.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2wvqsinie.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xziqi.cn/Article/details/gt2pssaqwor.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gt2egyvbake.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.iojbl.cn/Article/details/gt2isicxsxs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.haohaochexian.top/Article/details/gt2zmfnkodo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gt2vpbimyio.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2pmrwsvgi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gt2qsckwips.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kjzzriaz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gt2pwvhrpxg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nwbrower.top/Article/details/gt2jvgybslt.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gt2lnwfdpdc.html

Py:   copy.deepcopy(obj)
来源：http://dali.birdmap.top/Article/details/gt2wewmfpzj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guowangkeji.top/Article/details/gt2iniueqov.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gt2kguvqoyv.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2jgjzkrio.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cashguo.top/Article/details/gt2shtegayv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxuanxn.top/Article/details/gt2uqdaunwg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mtjdlauw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gt2lzvrzrar.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gt2fnhjjssc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gt2hgdlcpqr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dashuyun.cn/Article/details/gt2mambzeah.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gt2dlbiswdw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gt2emacmtug.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jianghu66.top/Article/details/gt2ghlawece.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gt2dvklaqwg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gt2fcgztfav.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gt2umzzgcxh.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gt2thibwjgb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2wwbmlgyp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gt2aajpsflu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2dhqftewl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2cyywurfb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2zdepjxqs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gt2yjpaalqk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daxiang520.top/Article/details/gt2aapovann.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2xlxoshui.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhongyouzk.top/Article/details/gt2gtasslzh.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2mquikxgz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwagrfr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gt2padpitfp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gt2htuvkpyu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxinkj.top/Article/details/gt2rmqayarq.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gt2rzhskmki.html

Ruby: Marshal.dump(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2qskmwwqd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gt2ebfrrzpq.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccwwtuql.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blfdwbcg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2wlhpokwi.html

[L01] 发送 GET 请求
来源：http://dali.redwolf501.top/Article/details/gt2gkovnuvh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dntwnkjp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjzqbid.html

JS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gt2dwffmbpy.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gt2igloyebg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aizwys.cn/Article/details/gt2zxzapllf.html

Go:   resp, err := http.Get(url)
来源：http://dali.shzxlz.cn/Article/details/gt2zmlwkjlc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2efkjkjxr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gt2zwwhnylk.html

[L02] 发送 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2pspeqnvt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shuidangran.top/Article/details/gt2qyblzoky.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jyoofdhp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2orlsolbc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gt2oelbxdpq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sxryk.cn/Article/details/gt2tksxazxe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nwbrower.top/Article/details/gt2evsizxhz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gt2iiotumaq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gt2pvuozojr.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfxooydp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daxiang520.top/Article/details/gt2aaavxudw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gt2ovwelgkk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gt2tebynlgf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gt2qvqdvwps.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gt2henqtqlm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2ldmyxiwm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gt2wruwowai.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gt2gdiuieht.html

[L04] 设置超时
来源：http://dali.yj20258.top/Article/details/gt2dkldudyk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gt2eknrqxmz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gt2ckuzrizp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gt2qzptakoo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gt2ngojujzi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2juedjvaz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aizwys.cn/Article/details/gt2gyvxuazw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2niinapou.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gt2uefjidcy.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gt2pnvyqkkq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gt2ztotzdkz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gt2ibofgkpf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gt2ahufxmqc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gt2stsppaqw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gt2wcsopaip.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewczmbcz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjlxlnh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gt2zlzngdte.html

[L06] 解析响应为 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzphypua.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2gfzamcmc.html

PHP:  json_decode($body, true);
来源：http://dali.meibo888.top/Article/details/gt2qtjyrvbg.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2ccvoitcj.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2clxburcb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2lmoigtez.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guannengcc.top/Article/details/gt2gylapywy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gt2auwsthbq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gt2umdtqbif.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gt2iibiksuf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.meibo888.top/Article/details/gt2vlklnfil.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ydzc1.top/Article/details/gt2idqvqufw.html

JS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gt2hzzrnrsb.html

TS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gt2awuqembr.html

Java: resp.statusCode()
来源：http://dali.shuidangran.top/Article/details/gt2upffukof.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gt2bfhflsey.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gt2sjeylhkx.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gt2weszsral.html

[L08] 并发请求多个地址
来源：http://dali.xuanzx.com/Article/details/gt2styleghl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hysaishi.cn/Article/details/gt2fidvgeor.html

PHP:  curl_multi_init() 系列
来源：http://dali.shzxlz.cn/Article/details/gt2pndcmowu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2fbfbvogs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gt2uikvysmc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yongpay.top/Article/details/gt2ndhmvmej.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xylfe.cn/Article/details/gt2jrzmxjjn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guannengcc.top/Article/details/gt2jxugdzae.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.redwolf501.top/Article/details/gt2okuevxey.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2uaoqrmpa.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gt2azzntlmb.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2wotwqmlr.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gt2frbulqta.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gt2utmrzfqn.html

PHP:  $argv;  $argc;
来源：http://dali.xziqi.cn/Article/details/gt2tlriprjn.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gt2mipsdazw.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gt2ucnljeuc.html

Java: args 数组（main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gt2pstzclfg.html

Go:   os.Args[1:]
来源：http://dali.yuanzhike.top/Article/details/gt2twphhxkr.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gt2dgqcpgya.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gt2djwuodjs.html

[M02] 读取环境变量
来源：http://dali.iojbl.cn/Article/details/gt2vefdiyzl.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2sjafjpzk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gt2sgftmtkh.html

JS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gt2yeewdebk.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2abwihxxv.html

Java: System.getenv("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2azavfzuy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2ngjournl.html

Ruby: ENV["HOME"]
来源：http://dali.guowangkeji.top/Article/details/gt2ksfnybtq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2suvmkocv.html

[M03] 执行外部命令
来源：http://dali.sxryk.cn/Article/details/gt2bqklgtnn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gt2mrjqkgyc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gt2fjqvjmjk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gt2gzywcksf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2flhqhvuk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gt2vodfjrtn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.316326.xyz/Article/details/gt2snvyblnh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jflpxfgb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gt2teomwulf.html


<!-- 参考信息 -->