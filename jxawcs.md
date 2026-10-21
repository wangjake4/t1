代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtckrqfioa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtpbyvdqsi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj202588.top/Article/details/gtzggwgjit.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.mhx1999.top/Article/details/gttnkktgbw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtxqhmagbb.html

[I07] 忽略大小写与多行模式
来源：http://dali.ppjwa.cn/Article/details/gtfsrrykjk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sweek.top/Article/details/gtzayjmbel.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gtisxsibgm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhengqikj.top/Article/details/gtjldrzucj.html

TS:   /error/gim
来源：http://dali.cdnleiting.top/Article/details/gtmizoejlo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gticqursje.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdexuiphu.html

Ruby: s.scan(/error/i)
来源：http://dali.sweek.top/Article/details/gtaiwsrmwj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.meibo888.top/Article/details/gtrqjlehep.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pycfn.com/Article/details/gtgvzvqypk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.redwolf501.top/Article/details/gtyiuteerf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtyirbdbiu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtvfctkcqx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gtyyzvccia.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gthdzwvfwy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gthygzhrdz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gotoacloud.top/Article/details/gtyenuncnp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtmchvhnnx.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gttgrxjqzj.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gtxhknfruq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtafmscmbg.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtpnxvrxys.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsffhsrnd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gthxxsbrwa.html

JS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gtmnjlloyu.html

TS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtcyfmqbvt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.kuanghao11.cn/Article/details/gtlatqkxza.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gtgathpxsf.html

Ruby: Time.now
来源：http://dali.cheryme.top/Article/details/gtxxwfprhz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gtfjrjzjuz.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtczjwaujl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtlsiklygi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtbajygaqd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gtnyukslop.html

TS:   d.toISOString()
来源：http://dali.chenzaomai.com/Article/details/gtritoifqp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgufenzy.top/Article/details/gtdztzvbpr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gotoacloud.top/Article/details/gtsfdkypgw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gtlahcilol.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gtmkmatsuz.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gtxetipdys.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.0kj1m.cn/Article/details/gtqtshrgxc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gzhubu.top/Article/details/gtlaiqnnio.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtvgqipyrq.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtspgtlchh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gthvymwerd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtrexvxsvt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtikhskofh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.c1oappe.top/Article/details/gtdcqcdeee.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gtljvesrfg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gtmeuctgmc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ehwqpu.com/Article/details/gtpaklwozq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gtlbwinufs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gtropfxoie.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yueranfly.top/Article/details/gtcmbytsck.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gogol.net.cn/Article/details/gtdmzkjamo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jyoumei.cn/Article/details/gtkthhffqe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dianchejie.cn/Article/details/gteyjdcyjd.html

[J05] 时间加减（加 7 天）
来源：http://dali.ybcxt.top/Article/details/gtssgkilbv.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gtttpxshkq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aizwys.cn/Article/details/gtzaaztwkg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptzjaddg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gtvxlbayth.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gturowgmwp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtoezvdorz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangtech.top/Article/details/gtegyphhid.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtjkkwqovk.html

[J06] 计算两时间之差
来源：http://dali.zycfv.cn/Article/details/gttrlbqjbd.html

Py:   (end - start).total_seconds()
来源：http://dali.jyoumei.cn/Article/details/gtdrlmkcxf.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gtnqpjdqkk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.smart0.xyz/Article/details/gtvjkacqbq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gttmgilkox.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gtizltbmag.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvxgmulx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cashguo.top/Article/details/gtvoqricrb.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gtrpaouhhp.html

[J07] 比较两个日期
来源：http://dali.nanxinkj.top/Article/details/gtkdqmoboc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gtzdscfvhb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gtljeddfvr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtouryegqt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtxfdfhiqs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.quarkkingdee.top/Article/details/gtgppvfftz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.quarkkingdee.top/Article/details/gteggwrukt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtzfvlnunj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtanzpqhin.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gtswdqqtsf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gtxwfjzali.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258.top/Article/details/gtnsnkavbm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gtxrcvwiib.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnxiangtu.top/Article/details/gtsenfhaur.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xziqi.cn/Article/details/gtmbacjuhb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gtjyfyivty.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangdashe.top/Article/details/gttwmbljnc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hysaishi.cn/Article/details/gtontuhkkr.html

[J09] 时区处理
来源：http://dali.shangyingyoupin.top/Article/details/gtswiwqrpe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gtvjsmeqee.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.316326.xyz/Article/details/gtsauafuqd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtsxtgrwth.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtprsbqpfb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tian-w.cn/Article/details/gtzzsjibut.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlktjdsbc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gtfytabafb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gtlonfugnh.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgizgscly.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnqzz.top/Article/details/gtpentfrbj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sufxvd.cn/Article/details/gtrqgunhdm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xziqi.cn/Article/details/gtfsdkucgh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tian-w.cn/Article/details/gtmwcegqim.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuanzx.com/Article/details/gtokuwesmm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnxiangtu.top/Article/details/gtohajprhd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gtwufgqlym.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gtqvitezkm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtceugmlsc.html

K. JSON 与序列化
来源：http://dali.9152youxi.cn/Article/details/gtsnnickfy.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtylyxmxaz.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gtddmrqfgu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gteabyszhj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtxpiixrpr.html

JS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtrwusjbhg.html

TS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gtrzxzciuh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gtsjflistw.html

Go:   json.Marshal(obj)
来源：http://dali.zdqjudy.top/Article/details/gtcvxaxmte.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shangyingyoupin.top/Article/details/gtcffugaiz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gtxwiwixtu.html

[K02] JSON 字符串转对象
来源：http://dali.9152youxi.cn/Article/details/gtrdbywxsm.html

Py:   json.loads(s)
来源：http://dali.chenlongwang.top/Article/details/gtdemhtziz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gtqpcqekad.html

JS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtxsvsfxgn.html

TS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtcfktzaej.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtcxjrfmwq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gtvckteuxv.html

Ruby: JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtxtsrmast.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cucudq.cn/Article/details/gtshykfqeh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gtyvcjpeqx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gtcdxubhwi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gtkqoyrgwo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtftqzxlix.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gtzdihajja.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljxyarvm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hysaishi.cn/Article/details/gtvlkqumqk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cucudq.cn/Article/details/gtewcnlpad.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gtppdymmpe.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gtxvotloeg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gtjjwjltkr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gtmvmtfbiq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtstjwxmtu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtcvduxxsb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gtveohgjoo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtkfewowtr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtskljrhht.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtjymhbfyl.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gtqmsevsgd.html

Py:   copy.deepcopy(obj)
来源：http://dali.aibaodan.cn/Article/details/gtgbamfley.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yvedp.cn/Article/details/gtumesorta.html

JS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtdpvmmbqv.html

TS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrdehlqs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yongpay.top/Article/details/gtpztlxsrp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gtzsopaqwt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yongpay.top/Article/details/gtqutlagga.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hammf.cn/Article/details/gtvybxouky.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gtylfclors.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gttpwykqch.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gtlssnemit.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtjjceskdj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtklwbrpbk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hysaishi.cn/Article/details/gtsebwjtzc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtvaswqmic.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtgrtykfjn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtyolzqdxy.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gthhtdhdqa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtdadwhfdf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gthozdctsh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtkefilnsb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtlpuwhsfe.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtohgtkfzp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenjidiqi.icu/Article/details/gtgueotdua.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtqioqvzff.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtovhanpfv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigfzy.top/Article/details/gtnilgyirq.html

Py:   pickle.dumps(obj)
来源：http://dali.yongpay.top/Article/details/gtizvsludi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhengqikj.top/Article/details/gtankgtxtr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtgkculvji.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gtebsaqjei.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jianghu66.top/Article/details/gtgwylqjbc.html

Go:   encoding/gob
来源：http://dali.smart0.xyz/Article/details/gtycjpvfuf.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gthvsdeysj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gthuttdnch.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtsialxgfh.html

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gtasohsvbx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtkeuurvjr.html

[L01] 发送 GET 请求
来源：http://dali.zhoulong.xyz/Article/details/gtumzfhgbq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gttettzfee.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnqzz.top/Article/details/gtnfgyrgyi.html

JS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtrcuyyxup.html

TS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtuhkwhdsa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.smart0.xyz/Article/details/gtveccfpau.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gtpiqqoyxe.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.birdmap.top/Article/details/gtrcymayxc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258888.top/Article/details/gttaxbupsx.html

[L02] 发送 POST JSON
来源：http://dali.sxryk.cn/Article/details/gtgovzjszz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtmgvvxxpa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gotoacloud.top/Article/details/gtkwvfyxjr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gtehgtdcqc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvrkonur.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.mhx1999.top/Article/details/gtbcfajwrg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gtdlbwkidd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jianghu66.top/Article/details/gthnujdzgj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngkpqxbn.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gthjqgsmxo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gtzruewafv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gtlalzhwjj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gtpmroqrwz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtrfrzwxtw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.birdmap.top/Article/details/gtkqwyfjxf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gtmslxaymo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhoulong.xyz/Article/details/gtsonjirjh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gtocgcfafo.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gtuhowyxja.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gtdhxjncgj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkprtdwdz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvqdcipx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtanjpzyrm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtptebtwsx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daria6918.cn/Article/details/gtlxrxrgjv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtixlexnpp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gtdrgijooq.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigufen.top/Article/details/gtypunhtfy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gogol.net.cn/Article/details/gtmkpnpzkf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenjidiqi.icu/Article/details/gtkehzaeef.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gtmbhywbxo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtbwimrdbu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ybcxt.top/Article/details/gtgkvuzuwf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yongpay.top/Article/details/gtqwfsecro.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gttpxoyjdr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gttynvkwxb.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gtpxesfywk.html

Py:   resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtpmgfuchm.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnuusrph.html

JS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtosnzcqec.html

TS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gtgdipekfq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtkyjvmbeu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhiwuduotai.top/Article/details/gtthgdxpzp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zdqjudy.top/Article/details/gtltcjszry.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tian-w.cn/Article/details/gtmpzsagof.html

[L07] 处理 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gtdrcjytla.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gtyuxggcbl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gzhubu.top/Article/details/gttetnzlws.html

JS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtmibjohyh.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gtsbyjbfua.html

Java: resp.statusCode()
来源：http://dali.tian-w.cn/Article/details/gthngqzlfg.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcrwfjde.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslevvpte.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gtafdcuebb.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gtrwwsbipl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tian-w.cn/Article/details/gtujtedhtg.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gtkqwrnovo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtkfonjrqf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gttjelwgvo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hongshengwenyu.top/Article/details/gtpaclepfv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenjidiqi.icu/Article/details/gtvqiauejs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtigulojnb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtrmfmwcnb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtufjmywxw.html

M. 命令行 / 进程 / 环境
来源：http://dali.ybcxt.top/Article/details/gtwrwgtrln.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtjperpdnl.html

[M01] 读取命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtfupaynhp.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtvgpnkspm.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gtdmkmpyti.html

JS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtkxcnusje.html

TS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gtsbzznynz.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gtcjcnagvx.html

Go:   os.Args[1:]
来源：http://dali.cucudq.cn/Article/details/gtqapsabpq.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gtaqqszsgp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtaibqdevg.html

[M02] 读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtdiqjxzuh.html

Py:   os.environ.get("HOME")
来源：http://dali.smart0.xyz/Article/details/gtkqoowtas.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtqovigcoj.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtjzwymmwe.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtnweeszmn.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtmqrfevnt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwvzghuk.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gtosfcnirx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gtrpocnnvb.html

[M03] 执行外部命令
来源：http://dali.hnqzz.top/Article/details/gtluljanvw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtyvgdbv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gtsieeqefz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtnvspxlpq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gtctkbsppv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sxryk.cn/Article/details/gtctqbunuw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ehwqpu.com/Article/details/gtbyxoslwn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.svipenyu.cn/Article/details/gtkwfylufe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gttzysllvk.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gtymvgwmpb.html

Py:   os.getcwd()
来源：http://dali.hywenlv.cn/Article/details/gtlehwvrpa.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gtziykircr.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtowpmxzdc.html


<!-- 参考信息 -->