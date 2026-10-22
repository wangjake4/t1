代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtnbkteayx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gtruauqvmz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtkomprxpe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthisdhfif.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gtugecqvup.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gtkeetrtoy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gtvmjfqbhn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthhpezlgj.html

J. 日期与时间
来源：http://dali.jlsjyb.cn/Article/details/gteomktomw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtuibkwyjf.html

[J01] 获取当前时间
来源：http://dali.mhx1999.top/Article/details/gtnvnrkyrh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgufenzy.top/Article/details/gtxxozjibm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gtnzcprxjr.html

JS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtpeiijyyn.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvibyyqe.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtomvlfuup.html

Go:   time.Now()
来源：http://dali.iojbl.cn/Article/details/gtgzoucqog.html

Ruby: Time.now
来源：http://dali.ivvv.top/Article/details/gtbjqhdkum.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnxiangtu.top/Article/details/gtxguodsbd.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gtoesvuwmq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtkckkikoz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtdazymbza.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gteyaeqpvf.html

TS:   d.toISOString()
来源：http://dali.smart0.xyz/Article/details/gtjjhcikeo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhongyouzk.top/Article/details/gtkzyoijvl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenzaomai.com/Article/details/gtumbkwicj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtnnxyfojd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gtsqcbfbcz.html

[J03] 字符串解析为日期
来源：http://dali.hammf.cn/Article/details/gtogcfjqbu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jianghu66.top/Article/details/gtqzxqxefq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ehwqpu.com/Article/details/gtdrifnxrs.html

JS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtctrrjery.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtywsewung.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtbkxvnnxg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtqymhayfx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gthfjkevyf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtlmebhotx.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gtufruoapy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xylfe.cn/Article/details/gtaivodgig.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xylfe.cn/Article/details/gtnvvmaeed.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hammf.cn/Article/details/gtzofrexly.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aizwys.cn/Article/details/gttugjqflo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gtqmdrljgo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtwcxfiytr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtrxcpjjgc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gtsktgbdsh.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gtruxqacbl.html

Py:   now + timedelta(days=7)
来源：http://dali.cdnleiting.top/Article/details/gtxyexwrak.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnxiangtu.top/Article/details/gtxiqcsdgb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gtmjiejlau.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gteenddbxc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gtbihunuvi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.iojbl.cn/Article/details/gtsxjnwqxa.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gtotszopan.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gtgotuzfpm.html

[J06] 计算两时间之差
来源：http://dali.yanxiufei.cn/Article/details/gtpjzcukjx.html

Py:   (end - start).total_seconds()
来源：http://dali.ydzc1.top/Article/details/gtknrcoooq.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gtrwfqzbgn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hongshengwenyu.top/Article/details/gtcpkedeuk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgqdfoqe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gtwaqtvuig.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlimjhfw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.redwolf501.top/Article/details/gtkpsifomw.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsqdeiyd.html

[J07] 比较两个日期
来源：http://dali.sufxvd.cn/Article/details/gtuosdwwny.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtahelgjyu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangdashe.top/Article/details/gtmtgkxpgw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkhmogui.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtrmccxzvg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtuqigoeth.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxuanxn.top/Article/details/gtuvenhezx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gttdqrrfpi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtjyiatrvd.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gtaaaldtll.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gttothlhog.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.9152youxi.cn/Article/details/gtuykymkex.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.birdmap.top/Article/details/gtoqbgbosi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ehwqpu.com/Article/details/gtjecgizme.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzlcpkzt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gtomjrnhmx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gtsgwifctq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gtmagbjdbq.html

[J09] 时区处理
来源：http://dali.chenlongwang.top/Article/details/gtzzhjkbgh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gtcfqxeclv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhongyouzk.top/Article/details/gtazzcualh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnivoenwa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtjandeqyh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daria6918.cn/Article/details/gtqpydhpyh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinghuilouyu.cn/Article/details/gttuupdddh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gtonbzisuf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gtgznwpyaw.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gtwuepdloh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.316326.xyz/Article/details/gtgonxhyep.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhoulong.xyz/Article/details/gtjpajhyee.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtnwhphdtp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gtkcwgybqa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gtbssoczby.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenzaomai.com/Article/details/gtanhyvsfq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jlsjyb.cn/Article/details/gtwdoyoukp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gtvemmuefk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtlamisged.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gtvicmxgvw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gthdybvoqp.html

[K01] 对象转 JSON 字符串
来源：http://dali.gogol.net.cn/Article/details/gtjcajvsmk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtjatrepty.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtfagorihp.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtpcfvecel.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtpuivpzqa.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gtmmqxggdd.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gtfjfgsupu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgufenzy.top/Article/details/gtdgyldvcl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj202588.top/Article/details/gtdcxvgvvg.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gtvkrcsabe.html

Py:   json.loads(s)
来源：http://dali.hnxiangtu.top/Article/details/gtnyxgvmlo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fzhhl.top/Article/details/gtacrtvmfa.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtushbujqr.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtmlbdhhix.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yueranfly.top/Article/details/gthsgffpgu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gthdazzivm.html

Ruby: JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtdsukwrnr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yanxiufei.cn/Article/details/gtuqbazcxs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gtnwfmrvwg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtdgdxxvgg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtdsaveqro.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtwvxjnpxa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtjxdyukqo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xylfe.cn/Article/details/gthpecllvr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gtipzzisvu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yongpay.top/Article/details/gtyigaqvrp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvizwsbk.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gtzgcepfxa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.0kj1m.cn/Article/details/gtupeejzbp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigufen.top/Article/details/gtoeepqaer.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtsdnixzme.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtqtwttgsz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtksskeefr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtxitlueqs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gtqdovggus.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtefegjyjw.html

[K05] 深拷贝对象
来源：http://dali.zhiwuduotai.top/Article/details/gtpofnnrlr.html

Py:   copy.deepcopy(obj)
来源：http://dali.ehwqpu.com/Article/details/gtogtnwgjc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gogol.net.cn/Article/details/gtasbyqaxm.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtovdwxxnl.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtpofgnqvb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nwbrower.top/Article/details/gtlyzffzsa.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gttcprbmyv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gtxssqgtif.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangshuangyany.cn/Article/details/gtrdpqrudy.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gtvfnotuvs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ydzc1.top/Article/details/gtbumuskir.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shzxlz.cn/Article/details/gtnqlwhdha.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gtwqcmfese.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gtobrowjwk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gtrrbepaqd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtwdswnnex.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtwabsvdbl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtydvseewv.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gtgfkshaop.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtsznyojpp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gtnrgztssj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtfilmfsdo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtawschcxs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtubxywtoq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gtjbszlxfs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gtjedyadyi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtnbsbsbet.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jlsjyb.cn/Article/details/gterezioba.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtftlnyglu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnxiangtu.top/Article/details/gtojjzyxge.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtjgkamqay.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdjiuuyd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gtqtpsiovv.html

Go:   encoding/gob
来源：http://dali.jlsjyb.cn/Article/details/gtikcjdhor.html

Ruby: Marshal.dump(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtermjygfn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtupayehxt.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtfufhskua.html

L. 网络请求
来源：http://dali.cucudq.cn/Article/details/gttaxyljwk.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtasyvpdds.html

[L01] 发送 GET 请求
来源：http://dali.jqgufenzy.top/Article/details/gtrokilvoq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gtjmbdeufk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gtbuubjtxr.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gthqouxxwr.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gtuijdkaab.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gtdmibzvit.html

Go:   resp, err := http.Get(url)
来源：http://dali.shzxlz.cn/Article/details/gtraskkljr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ehwqpu.com/Article/details/gteprooinm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gtfxveoamm.html

[L02] 发送 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gthpiflpzr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gtxycjunqo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gtaokvqpmo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gtzttfaugl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtiojagmwc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dianchejie.cn/Article/details/gtjkrfamcm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.c1oappe.top/Article/details/gtfzcojzmi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daxiang520.top/Article/details/gtwnlhutob.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gogol.net.cn/Article/details/gtrppdtntq.html

[L03] 设置自定义请求头
来源：http://dali.tanke756.top/Article/details/gteackuwkj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yonumen.top/Article/details/gtnpgyifqk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.bjfxy.top/Article/details/gtudihsulz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtijewrnsd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtvrfrheea.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.snrcjt.cn/Article/details/gtiidbxgql.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gtljrrhhae.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhengqikj.top/Article/details/gtqpdotzzo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtgpzhxgvb.html

[L04] 设置超时
来源：http://dali.shuidangran.top/Article/details/gtaecwksnr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yvedp.cn/Article/details/gthgfstsbc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258.top/Article/details/gtkrwjkpan.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gtssqbbkca.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtccbmvwhj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gtcjrdxtvs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgufenzy.top/Article/details/gtjkmbvldq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gtufvffdys.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zdqjudy.top/Article/details/gtmssgsxtk.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtflijhocz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jyoumei.cn/Article/details/gtacolgaob.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hysaishi.cn/Article/details/gtuqonttpb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gtgqyhwjas.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtwtnekcze.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumsgqyiy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqxbtpwc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gtleyeimjp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj202588.top/Article/details/gtimvqlzra.html

[L06] 解析响应为 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlsvvkrg.html

Py:   resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtneumxyup.html

PHP:  json_decode($body, true);
来源：http://dali.jlsjyb.cn/Article/details/gtgpoigxbc.html

JS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gtymcnzdpy.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtuvpkwdhp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtfdgocber.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxinkj.top/Article/details/gtqmihkvmi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yongpay.top/Article/details/gtqbkzkcqm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.meibo888.top/Article/details/gtiejmrcpq.html

[L07] 处理 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtzsqqbzxt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.iojbl.cn/Article/details/gtbejixxpf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yueranfly.top/Article/details/gtrfrwgvlq.html

JS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtgwsaopli.html

TS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gtrqhkwnck.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gtuqlwngcu.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtuicbztem.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gttxxcxrtr.html

C#:   (int)resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtaibbqyre.html

[L08] 并发请求多个地址
来源：http://dali.cdnleiting.top/Article/details/gtydjoaigz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gtvdxwvjip.html

PHP:  curl_multi_init() 系列
来源：http://dali.nwbrower.top/Article/details/gtuirxqhxc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtxdqgpoij.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtamiqvfsm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gtwfhbhhbs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldmcfger.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gttrctskss.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtfwgkyqgc.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtjuvvxrrk.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gtvfvwudun.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtgafztoce.html

[M01] 读取命令行参数
来源：http://dali.haohaochexian.top/Article/details/gtulxswiuf.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gtrowemsod.html

PHP:  $argv;  $argc;
来源：http://dali.dianchejie.cn/Article/details/gthpmcixmc.html

JS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtddtolpda.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtqfmsvsos.html

Java: args 数组（main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gtbesgiosh.html

Go:   os.Args[1:]
来源：http://dali.tanke756.top/Article/details/gtledjziza.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gtigzdcpqj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gtqvhlrpgy.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gtmbsvkauq.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdgogtyl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gtmgnpbmkm.html

JS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gthpkttfjz.html

TS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtvnwywxjt.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjffudah.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtipbqcuwo.html

Ruby: ENV["HOME"]
来源：http://dali.nanxuanxn.top/Article/details/gtncgmfprr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gtsgiocszd.html

[M03] 执行外部命令
来源：http://dali.zhongyouzk.top/Article/details/gtmdpojcic.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gtiojrbepl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cucudq.cn/Article/details/gtperghjkj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtmjzxvdux.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtmtwgxdxo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gtfxpbtwaq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.mhx1999.top/Article/details/gtzmfqmbmq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.vqdsnc.cn/Article/details/gtjwfyoelj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gtnsbagubu.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gtlspeoqgi.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gtlgdrzctg.html

PHP:  getcwd();
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfluqyrg.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtpesheaxo.html

TS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtwjvckfmu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nwbrower.top/Article/details/gtcqqdztpm.html

Go:   os.Getwd()
来源：http://dali.sysykeji.top/Article/details/gtkqwpcnsz.html

Ruby: Dir.pwd
来源：http://dali.birdmap.top/Article/details/gtqsrapnaj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjtxbhjk.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gtgmuhbnjl.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gtagtubxbx.html

PHP:  exit(1);
来源：http://dali.zhoulong.xyz/Article/details/gtqiqcvxmb.html

JS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwityplp.html

TS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqybujqg.html

Java: System.exit(1)
来源：http://dali.tanke756.top/Article/details/gtsnfunycy.html

Go:   os.Exit(1)
来源：http://dali.sxryk.cn/Article/details/gtxubazjje.html

Ruby: exit 1
来源：http://dali.gaohongyu789.top/Article/details/gtygpnptfi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gtuvwxlohj.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gtvsisjpbx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gtutvnngso.html


<!-- 参考信息 -->