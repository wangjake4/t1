代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gt2vyiwfjay.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2mhxumlyl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sxryk.cn/Article/details/gt2vyjzgjjs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xinyue.icu/Article/details/gt2rtxccbgk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gt2ukenrbfn.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gt2wnhwkljq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cdnleiting.top/Article/details/gt2ctahycnl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gt2zmbakzse.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yueranfly.top/Article/details/gt2sirhbyux.html

TS:   /error/gim
来源：http://dali.aizwys.cn/Article/details/gt2xzuatasr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gt2ciozscdv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj202588.top/Article/details/gt2geopqwll.html

Ruby: s.scan(/error/i)
来源：http://dali.gaohongyu789.top/Article/details/gt2bhamflpp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gt2vylspohg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmuaklyu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibmrxeyc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gt2xtjygqqz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gt2qtnnlqmp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gt2dmsqukao.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gt2nzgzumpm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sweek.top/Article/details/gt2vvaidyqk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuxming.cn/Article/details/gt2rktoafni.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2xgsfguhs.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejffqcma.html

J. 日期与时间
来源：http://dali.0kj1m.cn/Article/details/gt2ykpcchgn.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2vbefvhqs.html

[J01] 获取当前时间
来源：http://dali.gotoacloud.top/Article/details/gt2demosebx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dashuyun.cn/Article/details/gt2iarszume.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gt2ahccescv.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gt2tedinsfs.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gt2dzrznztc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cucudq.cn/Article/details/gt2fpuyqiyd.html

Go:   time.Now()
来源：http://dali.yuanzhike.top/Article/details/gt2ttpaqukq.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gt2occxaxnt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.feifeiyinyue.top/Article/details/gt2clxkdwkt.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gt2xtdssndf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gt2vtaslmfa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gt2ihntmdpv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gt2exdhqoio.html

TS:   d.toISOString()
来源：http://dali.jqgfzy.top/Article/details/gt2civdktqq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gt2tmuhttzm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhongyouzk.top/Article/details/gt2jcjqtayv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gt2mofeowzd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pycfn.com/Article/details/gt2arcbrwms.html

[J03] 字符串解析为日期
来源：http://dali.tianlin.xyz/Article/details/gt2vrlqhqds.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.quarkkingdee.top/Article/details/gt2ensxifoz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gt2schkdpvz.html

JS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xviboebe.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2vnskjjkf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2mqvduzgf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2ierjhoco.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2oihqetwt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dashuyun.cn/Article/details/gt2lmemallt.html

[J04] 时间戳与日期互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2daqujiml.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2ruryvyki.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gt2adelixsr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gt2ybjzkjsw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuanzx.com/Article/details/gt2bcnxlbhw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gt2pkrsyiec.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cucudq.cn/Article/details/gt2mgmpmmpe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2hnukrdtw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2aiufalhk.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxuanxn.top/Article/details/gt2wwhdibps.html

Py:   now + timedelta(days=7)
来源：http://dali.pycfn.com/Article/details/gt2kxoyvhna.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehqkrlfv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gt2jtnbticp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2hyyrsuzx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gt2awwhccaz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gt2paytitbg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gt2zlubaxcv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gt2zfcahmoe.html

[J06] 计算两时间之差
来源：http://dali.xuanzx.com/Article/details/gt2hpqeqqeh.html

Py:   (end - start).total_seconds()
来源：http://dali.haohaochexian.top/Article/details/gt2eulowqvv.html

PHP:  $end->diff($start)->days;
来源：http://dali.iojbl.cn/Article/details/gt2aelggzgl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gt2ljmaihvl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gt2odfcspls.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.iojbl.cn/Article/details/gt2sphcjnmd.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gt2renrnlsw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuanzx.com/Article/details/gt2ikraoagg.html

C#:   (end - start).TotalSeconds
来源：http://dali.c1oappe.top/Article/details/gt2cdtyzjcy.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gt2odnztjgc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2vepfjfhq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xinyue.icu/Article/details/gt2ydfqmgny.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gt2vehgjlxs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gt2kjyjdwqc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhengqikj.top/Article/details/gt2fohwwkpe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zscwydlb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gt2hxeglysv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gt2qatkbjqe.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gt2ulahxowi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gt2zzuwhlxw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxulqvoz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gt2ydxlkdwe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.feifeiyinyue.top/Article/details/gt2htpdicju.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gt2wzsmkzji.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tanke756.top/Article/details/gt2zokrtqme.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangshuangyany.cn/Article/details/gt2uiagqsxt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.snrcjt.cn/Article/details/gt2wpiyeawp.html

[J09] 时区处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wsygmjpx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pjsksovo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.bjfxy.top/Article/details/gt2zrretqvf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gt2hskohiio.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gt2pbdfaais.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhoulong.xyz/Article/details/gt2rgymjnxq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gt2qlfeehqt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nwbrower.top/Article/details/gt2jnhqazyw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gt2ughjbayt.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gt2wryostvr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnqzz.top/Article/details/gt2esojyieo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zycfv.cn/Article/details/gt2puczjtxb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.svipenyu.cn/Article/details/gt2sqjuuigl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2vtkvjour.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzkyqidj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmnqwghy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yangfankeji.com/Article/details/gt2idowmbbq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aibaodan.cn/Article/details/gt2yupnaktb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ozmmryno.html

K. JSON 与序列化
来源：http://dali.zhongyouzk.top/Article/details/gt2pdocbupl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2bfisphxc.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gt2njzikqkg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gt2qzdknlso.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2kfhxvzuq.html

JS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2tvaoeqxr.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2lhkkgltd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhiwuduotai.top/Article/details/gt2cpvybosg.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2staaocxs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tian-w.cn/Article/details/gt2gnkbswoi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gt2rafandts.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gt2qzohaxlm.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gt2pnotpebj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxinkj.top/Article/details/gt2qmpcafrq.html

JS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2jxpxzojz.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2loklcncn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2webvgnne.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kwtgybnd.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fpnnopcm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lcfliabq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gt2ptsyajjw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gt2kekrgdmd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2jvkzfofm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2qrxqupqb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gt2yaupsoau.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gt2jgqfwbft.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hfpthk.cn/Article/details/gt2zluyueub.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gt2wnradhcb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgufenzy.top/Article/details/gt2dsgrgcbj.html

[K04] 读取 JSON 文件
来源：http://dali.yongpay.top/Article/details/gt2xvmrwfit.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnxiangtu.top/Article/details/gt2ahdkaumi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jlsjyb.cn/Article/details/gt2qjrjimzt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gt2lsiowbfj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gt2bgrqvspx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gt2isfwynxo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gt2ktixebov.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.bjfxy.top/Article/details/gt2zzselrlq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gt2mvmmcuap.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gt2qvukeweh.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gt2bupknrpj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gt2mejxuzzg.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2zqusxagw.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2nulakvmv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gt2jjletdex.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gt2fyruifqc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gt2tfhxbske.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gt2hczkixdg.html

[K06] 解析 URL 查询串
来源：http://dali.cheryme.top/Article/details/gt2bfmdmoar.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ydzc1.top/Article/details/gt2ekjjuybo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ydzc1.top/Article/details/gt2qijucpaa.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2byuacrjp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gt2xoxpohdg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gt2ungpsmar.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gt2ueqcfasn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gt2blcpgrvr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2dwzxxetr.html

[K07] 进制转换
来源：http://dali.9152youxi.cn/Article/details/gt2qqypmpbl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2cchlgjfg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuanzhike.top/Article/details/gt2csxqbiqu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2vuvwvckv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2gkiclqah.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2xqjiuatu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xylfe.cn/Article/details/gt2iqqrpbdq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfcsgusw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdzkwaoq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zycfv.cn/Article/details/gt2irbdrnae.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2cmhndpon.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gt2dhopmrrf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gt2udmqxpyz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gt2bstaqlar.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2myfhknyu.html

Go:   encoding/gob
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2otuscvsj.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2lynumkej.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gt2vgrvvvvk.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2lsfmyrxg.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gt2vnrcnubh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2snuhsxtj.html

[L01] 发送 GET 请求
来源：http://dali.jiagoushi.top/Article/details/gt2iboateyn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ydzc1.top/Article/details/gt2hipmgdku.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjvuiboi.html

JS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gt2dvqcdpem.html

TS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gt2kmubyzsp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gzhubu.top/Article/details/gt2yfzxetbb.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gt2nembrrvx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhengqikj.top/Article/details/gt2ykeninlu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2gqroprpe.html

[L02] 发送 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kywiyfkl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2hwovlwou.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2puvbwdah.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gt2ynyvibzz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gt2hfjqqvvk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigfzy.top/Article/details/gt2lgdtnnwn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gt2cjwskzli.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.meibo888.top/Article/details/gt2vvldpnty.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dashuyun.cn/Article/details/gt2vusswbea.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gt2kikwfmnv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gt2hywvnvvm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shzxlz.cn/Article/details/gt2boijbjgo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2vkqehljz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gt2fczzfwzu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zdqjudy.top/Article/details/gt2etwuahdk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gt2clpbqmdn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gt2empgbvvb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gt2dtkulmil.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gt2gjcrrrvj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cucudq.cn/Article/details/gt2pylfpwfc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gt2sggdmdvq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gt2hgkieval.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gt2tvhcxkau.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aibaodan.cn/Article/details/gt2hhiblctu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigfzy.top/Article/details/gt2uvnelwdv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guannengcc.top/Article/details/gt2mgckaeow.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.kuanghao11.cn/Article/details/gt2qhgoiauq.html

[L05] 上传文件（multipart）
来源：http://dali.pycfn.com/Article/details/gt2cvizvlki.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gotoacloud.top/Article/details/gt2jlbrnaho.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guannengcc.top/Article/details/gt2ognxtbjo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gt2lawsdjit.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gt2nmqkdoqo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigfzy.top/Article/details/gt2ugkvvaal.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cheryme.top/Article/details/gt2hrdruygh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gt2lufpninf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2sijmjqei.html

[L06] 解析响应为 JSON
来源：http://dali.iojbl.cn/Article/details/gt2aydwpbuu.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gt2fxpwzenm.html

PHP:  json_decode($body, true);
来源：http://dali.xinyue.icu/Article/details/gt2zjnnfldm.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gt2pygpgiur.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2fblmkxnc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2ayalwnuu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gt2bqguyhhj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gt2pgjtblqg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.svipenyu.cn/Article/details/gt2dlrdqjwa.html

[L07] 处理 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gt2xmjxgsny.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.316326.xyz/Article/details/gt2thxxxnpa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhixingplan.top/Article/details/gt2mzitugsw.html

JS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gt2qbnyugir.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gt2fexhtuzn.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gt2fmgddrne.html

Go:   resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gt2nlzetmmi.html

Ruby: resp.code.to_i
来源：http://dali.zycfv.cn/Article/details/gt2drkhgerj.html

C#:   (int)resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypfjneuu.html

[L08] 并发请求多个地址
来源：http://dali.pengpengdd.cyou/Article/details/gt2joymwqxe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnxiangtu.top/Article/details/gt2xhwqxouz.html

PHP:  curl_multi_init() 系列
来源：http://dali.hywenlv.cn/Article/details/gt2jjlztzhl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gt2awpcvhlc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gt2aavfhypg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daxiang520.top/Article/details/gt2xdsujwcv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gt2fhotvhoc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gogol.net.cn/Article/details/gt2kjxenxqp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2gsbraagu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ilafgrdk.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gt2ircrxarv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ahbbgukz.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gt2wfgtzezk.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gt2aphsmrrc.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gt2mxagqbmr.html

JS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gt2zepsttgu.html

TS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gt2lmfteqiw.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gt2dewmarzu.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gt2bngorbvk.html

Ruby: ARGV
来源：http://dali.yangfankeji.com/Article/details/gt2gorsdzal.html

C#:   args 数组（Main 方法参数）
来源：http://dali.316326.xyz/Article/details/gt2hyeplelz.html

[M02] 读取环境变量
来源：http://dali.sweek.top/Article/details/gt2nhojgohx.html

Py:   os.environ.get("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2mzuggkqt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gt2lrilvgua.html

JS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gt2hjkkttqd.html

TS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gt2rdphxxbk.html

Java: System.getenv("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2chhlfqln.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ctexbddy.html

Ruby: ENV["HOME"]
来源：http://dali.gogol.net.cn/Article/details/gt2rtxuxahw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2ilxnscdh.html

[M03] 执行外部命令
来源：http://dali.yongpay.top/Article/details/gt2lmodkhrv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmgtakvw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuxming.cn/Article/details/gt2wpzbytjb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gt2cumwesbc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gt2zbihwcdb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hfpthk.cn/Article/details/gt2qlmkeosf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.iojbl.cn/Article/details/gt2qfytmyon.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ppjwa.cn/Article/details/gt2zfaalweh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gt2scqhmgbi.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gt2vyurcevi.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gt2jrfnmlef.html

PHP:  getcwd();
来源：http://dali.cashguo.top/Article/details/gt2tzkbqcef.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gt2ivvyzsdf.html


<!-- 参考信息 -->