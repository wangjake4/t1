代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gtjbgkicpf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtvpnrgsro.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtvfjaqfdp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gtvaeeddzo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gtuvbunyqo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gtcqqaqrta.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtrsiknudo.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtffarittd.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawbluoxg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqnumwqdz.html

[J01] 获取当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejvxwdwy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gtibyttghp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gtdaoalexu.html

JS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gtnapegixn.html

TS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtoqjqafdk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmazvcsvk.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gtmxqxjgez.html

Ruby: Time.now
来源：http://dali.xziqi.cn/Article/details/gtzqfutwoi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gtgybcctzd.html

[J02] 格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtmxkrrhhv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtbuchyltg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtxlurrpcr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.smart0.xyz/Article/details/gtfzvfyrpx.html

TS:   d.toISOString()
来源：http://dali.chenzaomai.com/Article/details/gtblcbxvqe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.316326.xyz/Article/details/gtjjxzunst.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gttbracasq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gtalriexuv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shangyingyoupin.top/Article/details/gtsdkfhjfe.html

[J03] 字符串解析为日期
来源：http://dali.pengpengdd.cyou/Article/details/gtlqjwupqy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnqzz.top/Article/details/gtccdltrvq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xylfe.cn/Article/details/gtzkgqiglc.html

JS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrgpqyys.html

TS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtidfrgkxb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtffifadem.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtrxhchvbj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gthhwndvub.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gtxkzptiff.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gtgezlbpuq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sweek.top/Article/details/gtceleunxx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tanke756.top/Article/details/gtobhzpfkk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxkbkisx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.meibo888.top/Article/details/gtadtgcule.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gtzaozvlms.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwinhimsu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fengsongda.top/Article/details/gtaiyzubfu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gtwvnbakep.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gtqaitbacj.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gtrvawsivv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yueranfly.top/Article/details/gtdusvgblx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gtezdzjjog.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gtmygkppgo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtpggufgfu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gtgtlwwgrd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfbxpnxh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gtmobidcsg.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtteqzbqqm.html

Py:   (end - start).total_seconds()
来源：http://dali.vqdsnc.cn/Article/details/gtrqgrkgyy.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gtegecfvgb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gtpybfjxha.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zycfv.cn/Article/details/gtnkhjvbfr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gthqnynpgf.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gttngxnnor.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cqqwz.cn/Article/details/gtqiceacbp.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjfbhjtn.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gttneuygyf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtwzmuocco.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gtseatdiny.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtspqaknvi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtlttrierz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtmlsdkmub.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtyzmmblbx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbetukrn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gteaurphes.html

[J08] 提取年月日与星期
来源：http://dali.zhoulong.xyz/Article/details/gtuzhfqfpg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shangyingyoupin.top/Article/details/gtbjfsbfue.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yangfankeji.com/Article/details/gtgkhhpmrl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dianchejie.cn/Article/details/gtidagkymy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jianghu66.top/Article/details/gtrpeniyix.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gtwejbwgoi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tanke756.top/Article/details/gtdceokjlg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gtidoxthaz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gtdjituunt.html

[J09] 时区处理
来源：http://dali.sysykeji.top/Article/details/gtbqqfpbmb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnxiangtu.top/Article/details/gtjecouxoc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jyoumei.cn/Article/details/gttxcycdvk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtghricjce.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtddbzaotm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hfpthk.cn/Article/details/gtgnfdejip.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.bjfxy.top/Article/details/gtpvtixivy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gtfphswmxt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gtswgkjkuq.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gtvzxkcfch.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gtoihfaejv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dashuyun.cn/Article/details/gtaelkskqk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtkpjdulhh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtcakhoqxj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.316326.xyz/Article/details/gtluszzlzp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nwbrower.top/Article/details/gtwtbbxugy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hammf.cn/Article/details/gtuioqyhiq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuanzx.com/Article/details/gtjbvnhded.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtpmhtovtb.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gtaqygdcbm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gteofpsgqb.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gtgzlbqdsu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gtdingumte.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtpkqbfgrb.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtzglcudzu.html

TS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gthwhszdmf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.vqdsnc.cn/Article/details/gtwjiinsxa.html

Go:   json.Marshal(obj)
来源：http://dali.fzhhl.top/Article/details/gtjxboupxf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowzilycr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenzaomai.com/Article/details/gticsxzwmh.html

[K02] JSON 字符串转对象
来源：http://dali.ydzc1.top/Article/details/gtklvgvoxl.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gtzeidjrpv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gtlufjmotf.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtgzcnrgpy.html

TS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtiygicikl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtcaxfuczs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gteqvutdre.html

Ruby: JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtynkcmjws.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gtmydoscif.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gtvnujqjte.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gtcdnjqtxj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gtyomiwqvi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gtmqlwhedy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtdwmimull.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtwsqzswyd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gtsjchobbc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gtschjsnvu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnbrihoq.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gtsghjurvv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.c1oappe.top/Article/details/gtlfvpwlsv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gtolhvlhcd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtyppvlcef.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gtgsfdqftg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdwmfwvi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtbiwgcsoy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtguwjtafk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtjdalvlaz.html

[K05] 深拷贝对象
来源：http://dali.jqgfzy.top/Article/details/gtyzeokthj.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnqzz.top/Article/details/gtfxoxfpns.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgufenzy.top/Article/details/gtqyvbfvca.html

JS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtcfjhbiaz.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gtbkntmgvr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cashguo.top/Article/details/gtgxkpanbu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xylfe.cn/Article/details/gtowrptxqt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gtmywtdien.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tian-w.cn/Article/details/gtjitshmmm.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbvztkpe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtskbzqsxu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gtqxczebbb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gteikrddrp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtgyrbbzca.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gzhubu.top/Article/details/gtotnapwyr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gttxassokk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtxhviyeqf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtgqewzqtz.html

[K07] 进制转换
来源：http://dali.wangdashe.top/Article/details/gtbggqmcfb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtmrskvmik.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gzhubu.top/Article/details/gttkznobfh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtpiypcubu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtsvhoejzu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtjvlnewgp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowekrjcj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gtkrljiymm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtmxhyrizj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gthcbbcmez.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gtqqfiomhr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tianlin.xyz/Article/details/gtpoeuvpqx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtadjkvrnh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtszbtbxrj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yvedp.cn/Article/details/gtdqtmdnwk.html

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gtkiiosrdr.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gtgfnhrzzt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gtmyhkrigu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtcdoykuiy.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gttvyreumz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtvhylhxyf.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmazaqwg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gtmhcwyfna.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daxiang520.top/Article/details/gtyrmdappg.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtitxcdnqj.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgicoeue.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gtktgiscdk.html

Go:   resp, err := http.Get(url)
来源：http://dali.9152youxi.cn/Article/details/gtwkaezqyi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yueranfly.top/Article/details/gtdhgwcgya.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dianchejie.cn/Article/details/gtijgyvnjx.html

[L02] 发送 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtgsqzhqfb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gttwnfezjg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gtxmzhcnrm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gtgipylzvz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtcyrqevtv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.haohaochexian.top/Article/details/gtcnpurvpz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gtwdcafywo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtxrdykzmq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gtyeusjqbz.html

[L03] 设置自定义请求头
来源：http://dali.shangyingyoupin.top/Article/details/gtldaolqoz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guannengcc.top/Article/details/gtexkcnbdo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daria6918.cn/Article/details/gtcxcqzgjl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gtlxpilxmf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gtxhvzopbb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gtqgfqvfna.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gtkueysqkq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gthwqnbqjd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gtjsyhbrdb.html

[L04] 设置超时
来源：http://dali.daria6918.cn/Article/details/gtgjbwzkcr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pycfn.com/Article/details/gtqbgiehpn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gtcsngyezy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtnhyjjwsd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtbdgaizjp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcttsqnk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gtxwbdasaw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fzhhl.top/Article/details/gtpfgaiagk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xinyue.icu/Article/details/gtcliculos.html

[L05] 上传文件（multipart）
来源：http://dali.jiagoushi.top/Article/details/gtfsvveubl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xinyue.icu/Article/details/gtljlmmyuw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.svipenyu.cn/Article/details/gtsamaapyl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtnoakjvzl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gtzucbpmbd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gtegdoucdy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gtvqkwcmsi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gtzucntyoy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtnfxfvrwa.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gtahcauqem.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmewczsav.html

PHP:  json_decode($body, true);
来源：http://dali.nanxuanxn.top/Article/details/gtvjpaihak.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gtwoeagarw.html

TS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gtvrbrperv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtafrffzmt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyxgqdui.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenlongwang.top/Article/details/gtjgafmsok.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sweek.top/Article/details/gtjisdkywo.html

[L07] 处理 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gtbheoucfu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenzaomai.com/Article/details/gtmewwkwnp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gtsikupjii.html

JS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtjluxzmis.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtsvqicmoe.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemucbzyk.html

Go:   resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtctdjnoai.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gtllyzqfsb.html

C#:   (int)resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gtkjtucxaz.html

[L08] 并发请求多个地址
来源：http://dali.haohaochexian.top/Article/details/gtvejirydz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gtxmkaiajf.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gtbosbmohn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gthrnqdniw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtblllnlae.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gttujmqvjz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhengqikj.top/Article/details/gtvbawdnbk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gtiiojuqpd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hfpthk.cn/Article/details/gtmzsyrjjp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxzgbnjfk.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxinkj.top/Article/details/gtqzbnkzsw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkejqeexk.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtditlksoc.html

Py:   sys.argv[1:]
来源：http://dali.hywenlv.cn/Article/details/gtitmytzpf.html

PHP:  $argv;  $argc;
来源：http://dali.sysykeji.top/Article/details/gtccmmhfth.html

JS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gtbgenhdnh.html

TS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gttafzregf.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gttxnjqlno.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gtytgqclxs.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gtyfqiqcki.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gtufcwkajf.html

[M02] 读取环境变量
来源：http://dali.yvedp.cn/Article/details/gtapfgazom.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gtksxuzjoc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtgmfrqshe.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtbpaoidrc.html

TS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtuvkbbpmb.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtkcxsklmi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtjumasskf.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gtxtholkan.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gtgyujssrs.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtrdnglylh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yueranfly.top/Article/details/gtfpvtvdls.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.meibo888.top/Article/details/gtywbzoldx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtyjyoppmh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtlqstyyoh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.birdmap.top/Article/details/gtrxkyxdio.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuanzx.com/Article/details/gtbmurpmij.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xziqi.cn/Article/details/gtoyyuspof.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gtdflhdxud.html

[M04] 获取当前工作目录
来源：http://dali.cucudq.cn/Article/details/gtevkpyvuf.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gtvsrdiknk.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gtavgvaugh.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gteqtdmyct.html

TS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gtvojsvlaw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zycfv.cn/Article/details/gtyjkgqhuc.html

Go:   os.Getwd()
来源：http://dali.jiagoushi.top/Article/details/gtkpyapnzj.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiphgzjtb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gtynzvmywl.html

[M05] 设置退出码
来源：http://dali.zhiwuduotai.top/Article/details/gtbterzorl.html

Py:   sys.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtqwgsouxm.html

PHP:  exit(1);
来源：http://dali.tian-w.cn/Article/details/gtfkmciyxz.html

JS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtxdnsumjh.html

TS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtwlfemiob.html

Java: System.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtvtpjczax.html

Go:   os.Exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtdbkfehko.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gtdkdoaakp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xylfe.cn/Article/details/gthzxvrsnq.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gtbkdqowrj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gtubpuqgjm.html


<!-- 参考信息 -->