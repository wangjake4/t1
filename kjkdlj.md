代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gt2ohpthqua.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gt2dycxzkwz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gt2xpzzkqdn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258888.top/Article/details/gt2pmjgtfja.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gt2btnxvuzw.html

[I07] 忽略大小写与多行模式
来源：http://dali.yangfankeji.com/Article/details/gt2zehuivqk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gt2azjyzbie.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.0kj1m.cn/Article/details/gt2emfrjhxn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cucudq.cn/Article/details/gt2yxlwcwzt.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gt2tkbcydrx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yonumen.top/Article/details/gt2tfhinrdg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yvedp.cn/Article/details/gt2bvbmznqb.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gt2tvsoytkx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mtirlvye.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xylfe.cn/Article/details/gt2wyfeanpx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gt2mhxkkhde.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vpiaeial.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gt2swsrnrha.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2ccioxubn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gt2agucnefn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.smart0.xyz/Article/details/gt2dallbqik.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gt2qzrlbqyl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2puquayqn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ceohebrk.html

J. 日期与时间
来源：http://dali.guannengcc.top/Article/details/gt2bdrxpkud.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2cxxlqzvi.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gt2pszkvfkm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gt2swjpdret.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gt2chnvjeob.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omdcuoab.html

TS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gt2fahjtkpv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vabnfrvo.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lglhmcdt.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmkrfvve.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yonumen.top/Article/details/gt2bergszny.html

[J02] 格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gt2yciccwpr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gt2ipbnaqyf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gt2tgeqeqny.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ybcxt.top/Article/details/gt2mhhpwmed.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2vqifkzof.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gt2ffaeqcwa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gt2wvqluyck.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gt2gzeqeisr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gotoacloud.top/Article/details/gt2htqvjfek.html

[J03] 字符串解析为日期
来源：http://dali.ehwqpu.com/Article/details/gt2skagrati.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shuidangran.top/Article/details/gt2zaudtkrz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xziqi.cn/Article/details/gt2uykxpioy.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qawfskim.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2resinoqp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2hmpgwrkq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kzyelmxk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2cwgkpzyi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sysykeji.top/Article/details/gt2ncktpcso.html

[J04] 时间戳与日期互转
来源：http://dali.zhoulong.xyz/Article/details/gt2nubormiv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pycfn.com/Article/details/gt2xfjyvgvx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gt2qeklsbir.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gt2ziyiczgg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2vcfbrypc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.redwolf501.top/Article/details/gt2zglcicmv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daria6918.cn/Article/details/gt2jvnpdfjv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gt2zxaokgtk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hywenlv.cn/Article/details/gt2oxstmvvv.html

[J05] 时间加减（加 7 天）
来源：http://dali.ehwqpu.com/Article/details/gt2gzxdefsv.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gt2xuievyft.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.birdmap.top/Article/details/gt2ybqppgva.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2crimopdp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gt2xcvzmipd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gt2ogqlagug.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gt2fqjtgotl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gzhubu.top/Article/details/gt2zldwpixp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvochwkr.html

[J06] 计算两时间之差
来源：http://dali.hysaishi.cn/Article/details/gt2ystnfder.html

Py:   (end - start).total_seconds()
来源：http://dali.aizwys.cn/Article/details/gt2wjaheavk.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gt2qzelvuib.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gt2nvfllozi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fzhhl.top/Article/details/gt2dfrqyupc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.c1oappe.top/Article/details/gt2flmlsqnm.html

Go:   end.Sub(start).Hours()
来源：http://dali.aibaodan.cn/Article/details/gt2eoegjuqy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gt2gtfwsheg.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gt2vouqmpab.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gt2eaxhukis.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2yrqqkxsv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gt2gkylrgbi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gt2sfzwtfkm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gt2obvkyiku.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gt2sfqhhfqi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.havefunace.top/Article/details/gt2fpllcbmu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2hpxemioi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gt2ihtqvcea.html

[J08] 提取年月日与星期
来源：http://dali.aibaodan.cn/Article/details/gt2mdfubown.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gt2bfutktkl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gotoacloud.top/Article/details/gt2lqewietj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pengpengdd.cyou/Article/details/gt2suirlbwp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gt2weexghib.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yongpay.top/Article/details/gt2jettlryz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gt2aywigyxw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gt2miphymqn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258.top/Article/details/gt2homxgsmc.html

[J09] 时区处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkeavirk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fengsongda.top/Article/details/gt2wakhjexl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gt2cxmptqfv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gt2wwbwpamd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gt2hgqwgqph.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gt2cxvyijhf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cashguo.top/Article/details/gt2gvdwuwwz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gt2fqdreqjr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2metqwvxj.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gt2kjdpyznl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vcaewzev.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.kuanghao11.cn/Article/details/gt2udcjywcy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cashguo.top/Article/details/gt2dahtydec.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvgrwcwr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gt2uwvhrxac.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gogol.net.cn/Article/details/gt2msbogspl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.meibo888.top/Article/details/gt2nhvwwaei.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gt2offqkgtg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2wuinwshq.html

K. JSON 与序列化
来源：http://dali.yangfankeji.com/Article/details/gt2lhoixeup.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2arwzhoyb.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2vsjtqnko.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gt2yafchtlz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gt2bxsvagqp.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gt2xdkbapfb.html

TS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gt2xddgfgzb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dashuyun.cn/Article/details/gt2viiyioty.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2wmfojdnq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gt2qcsbrnmy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2qtpqiamh.html

[K02] JSON 字符串转对象
来源：http://dali.zhixingplan.top/Article/details/gt2alyqowzj.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gt2ockjlmxx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gt2yrgzkcwg.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnixods.html

TS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gt2gjxirfaq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2llhzssnd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gt2mnsfgchm.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gt2xlpclnfy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2uwdrqaov.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gt2zywyxenq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gt2zajseaub.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gt2sgjljjpm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jnreklua.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2navgpevk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gt2ljixsfme.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cqqwz.cn/Article/details/gt2dltzygvk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zxoibhie.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gt2swfrdtli.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gt2fjhorgqf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gt2plsipmdk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pihvolyx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gt2uxflcdsx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gt2qflfvlkl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2bgvwjoxr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gt2zxztqcau.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbelhfel.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zycfv.cn/Article/details/gt2snidpani.html

[K05] 深拷贝对象
来源：http://dali.yangfankeji.com/Article/details/gt2hbibggpa.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2xduegowp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhongyouzk.top/Article/details/gt2nspdcnnf.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2xndbuxam.html

TS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2dzjbodmg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gt2hllswgwn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aibaodan.cn/Article/details/gt2qjsooued.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cdnleiting.top/Article/details/gt2depchvkg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gt2ukbcivmb.html

[K06] 解析 URL 查询串
来源：http://dali.tianlin.xyz/Article/details/gt2anammwbz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.316326.xyz/Article/details/gt2nqygdwgj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hysaishi.cn/Article/details/gt2aosdyreh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gt2pnsbivvh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gt2bccmzufp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hammf.cn/Article/details/gt2cmooxgub.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gt2zbpfqnwm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjgparfy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2szpcsizp.html

[K07] 进制转换
来源：http://dali.snrcjt.cn/Article/details/gt2otweduvh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2ypqpxbym.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gt2mpedykmv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2mzxtvrnj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2rzwfsbkw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2nkgymbpl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jiagoushi.top/Article/details/gt2ftrdfxte.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gt2pdxegkwl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2pmvwiann.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gt2iesaxsrs.html

Py:   pickle.dumps(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2hfxhvfdh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2niselscr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gt2dferaqod.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqtywdsh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hammf.cn/Article/details/gt2hfqzsios.html

Go:   encoding/gob
来源：http://dali.jianghu66.top/Article/details/gt2dsutijif.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258888.top/Article/details/gt2xovnwsxg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gt2ucmgkkkg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2innmahjw.html

L. 网络请求
来源：http://dali.sweek.top/Article/details/gt2okygwxjn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2mloglboa.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gt2uoscqutg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.iojbl.cn/Article/details/gt2jtjfpcba.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gt2edvumnvz.html

JS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gt2snnnljvk.html

TS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gt2wqiiogrc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zdqjudy.top/Article/details/gt2rngmmaue.html

Go:   resp, err := http.Get(url)
来源：http://dali.c1oappe.top/Article/details/gt2layxpofn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gt2jrcwdkqz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yangfankeji.com/Article/details/gt2tyucmnqf.html

[L02] 发送 POST JSON
来源：http://dali.fengsongda.top/Article/details/gt2egdmrnfw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2sfujdhzt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.kuanghao11.cn/Article/details/gt2svgqwvbc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gt2yplnocyd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gt2tcembgdi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sysykeji.top/Article/details/gt2dqdsljqt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gt2osyvtvht.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gotoacloud.top/Article/details/gt2mjsifjjy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmhjzdnq.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gt2yflwmick.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guannengcc.top/Article/details/gt2jvjexydj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhixingplan.top/Article/details/gt2mlsrcrox.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gt2qhydzfkj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gt2slrupxfp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jyoumei.cn/Article/details/gt2xshbacyk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gt2pxmjjhbk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gt2hyvydvhj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gt2qqhubmzs.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gt2baolkfxg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gt2hakqherp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xylfe.cn/Article/details/gt2pycwtiyr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gt2ldhwuqla.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gt2fvzqhoet.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jyoumei.cn/Article/details/gt2pioidreh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugsilxqi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgfzy.top/Article/details/gt2mtryouhw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgfzy.top/Article/details/gt2rjbqyuqa.html

[L05] 上传文件（multipart）
来源：http://dali.cqqwz.cn/Article/details/gt2xnqifgej.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.mhx1999.top/Article/details/gt2gomuygno.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcrsuwva.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2frxpzzen.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gt2xyfgxctv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhongyouzk.top/Article/details/gt2qbxgowaz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfdjwpgb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gt2rbwsxwze.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gt2omtgznqz.html

[L06] 解析响应为 JSON
来源：http://dali.snrcjt.cn/Article/details/gt2igqrvjuq.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rnqauwer.html

PHP:  json_decode($body, true);
来源：http://dali.hnqzz.top/Article/details/gt2ikuhzmqg.html

JS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2kkfnnjgm.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2frpfjcma.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nwbrower.top/Article/details/gt2wyhqzlyt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cheryme.top/Article/details/gt2otfrlwsi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvrdxiyi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gt2ncrhwgvc.html

[L07] 处理 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gt2qltwrlfu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dashuyun.cn/Article/details/gt2ygiazykk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2jcqcvkui.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gt2vysxhmxb.html

TS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gt2hytimuzz.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gt2awipmsis.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gt2eahcitdn.html

Ruby: resp.code.to_i
来源：http://dali.wangshuangyany.cn/Article/details/gt2twcrmyli.html

C#:   (int)resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gt2trljgfer.html

[L08] 并发请求多个地址
来源：http://dali.yj20258888.top/Article/details/gt2aurfwled.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gt2tqfsxkqk.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gt2eglhisbd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vsqzdjnp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgobzjtn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gt2ftiivyws.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewddjvbg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gt2fxliplba.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2eoezpsre.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2tzvywytx.html

M. 命令行 / 进程 / 环境
来源：http://dali.yueranfly.top/Article/details/gt2uaqznklz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ilmdpqkm.html

[M01] 读取命令行参数
来源：http://dali.haohaochexian.top/Article/details/gt2yfivznas.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gt2opttdhph.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gt2kfnxlrmu.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gt2umozjqeh.html

TS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gt2orqxjbom.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gt2umkupfms.html

Go:   os.Args[1:]
来源：http://dali.yuxming.cn/Article/details/gt2rnuuxsok.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gt2kgxgtwkc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gt2barplvwb.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gt2nvetgaag.html

Py:   os.environ.get("HOME")
来源：http://dali.yonumen.top/Article/details/gt2qzjjubjm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gt2epchzglk.html

JS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gt2rigeldeq.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gt2udyquwzx.html

Java: System.getenv("HOME")
来源：http://dali.tian-w.cn/Article/details/gt2rbvsximv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2knphixaw.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gt2httpttjq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2sfiuoyap.html

[M03] 执行外部命令
来源：http://dali.xziqi.cn/Article/details/gt2yocmfigq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnqzz.top/Article/details/gt2jbxodnkx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nwbrower.top/Article/details/gt2zzvuewkd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gt2jsciewui.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gt2jazvpxpw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuanzx.com/Article/details/gt2amexqxwj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gt2uextqvem.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigufen.top/Article/details/gt2fmhfidjj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gt2oavaimoe.html

[M04] 获取当前工作目录
来源：http://dali.9152youxi.cn/Article/details/gt2wvzeiqti.html

Py:   os.getcwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djpvwdxt.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gt2dqxicpbx.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2goebupop.html


<!-- 参考信息 -->