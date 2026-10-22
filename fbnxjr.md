代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gt2lcununmr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gt2fnfytefs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gt2orkqqehf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gt2emdszwhb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gt2nhwnxhuo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gt2bffzatdj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gt2doyaitxw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2gzgsjfho.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gt2rlgzkqij.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2gxmjhfvk.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gt2rrlyocso.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gt2lztvsmkz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gt2gaxnaemx.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gt2eietvjdx.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gt2jhppctci.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fzhhl.top/Article/details/gt2djwbbkyu.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gt2upsjmevg.html

Ruby: Time.now
来源：http://dali.tian-w.cn/Article/details/gt2ogrgjfol.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fengsongda.top/Article/details/gt2qquzvtaq.html

[J02] 格式化输出
来源：http://dali.jinqigufen.top/Article/details/gt2aseyjlld.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gt2dzgfxquf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cwzslqtq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sysykeji.top/Article/details/gt2pxbxbccj.html

TS:   d.toISOString()
来源：http://dali.yvedp.cn/Article/details/gt2ysggdgxq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gt2cgcdmngw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnxiangtu.top/Article/details/gt2kfwdlera.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gt2jtlvfaab.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gt2khxwguch.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gt2xbistcfg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ppjwa.cn/Article/details/gt2qfjpzyvm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuanzx.com/Article/details/gt2xqnxroaq.html

JS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2kgofepno.html

TS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2fgcklfnl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2vmhrqmuw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2gkyvpayn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2imjzwntf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gt2sppttcru.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gt2hnmkgbyo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yvkscini.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xgdktssc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvvawpdf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gt2syungfdg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnqzz.top/Article/details/gt2hbnnkpim.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2ilgmhvjc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gt2dqruhmpy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2ouotgxnl.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gt2ylqtkzbg.html

Py:   now + timedelta(days=7)
来源：http://dali.shzxlz.cn/Article/details/gt2ncwjqcyi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sufxvd.cn/Article/details/gt2ohgwioyq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gt2rkrnbfnl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gt2qwfjziix.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guowangkeji.top/Article/details/gt2umfgdkvc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2eyomsnef.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gt2hujcbakv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gt2txmghzqq.html

[J06] 计算两时间之差
来源：http://dali.zycfv.cn/Article/details/gt2mruqebgq.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gt2grvipkpt.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rezbrugg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hammf.cn/Article/details/gt2pilymund.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigufen.top/Article/details/gt2opmaamys.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.birdmap.top/Article/details/gt2uolkdygy.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gt2nzjitrlk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgeolutj.html

C#:   (end - start).TotalSeconds
来源：http://dali.hammf.cn/Article/details/gt2eslqstbw.html

[J07] 比较两个日期
来源：http://dali.quarkkingdee.top/Article/details/gt2ulybiqay.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2bzmqrnrb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rlrhulsi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gt2jdltycjq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gt2dzcogbfc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gt2qwyvlgrc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2iruzaxoa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gt2fttqcnzh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2bgpfyjuw.html

[J08] 提取年月日与星期
来源：http://dali.pengpengdd.cyou/Article/details/gt2oevqlisp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.c1oappe.top/Article/details/gt2pswnlxbt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gt2tejzwuoq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzbstuiq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangdashe.top/Article/details/gt2ovcovcob.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gt2lgdadnim.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cqqwz.cn/Article/details/gt2dmdzfmhl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gt2jvgmjguf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shangyingyoupin.top/Article/details/gt2ffbnkuui.html

[J09] 时区处理
来源：http://dali.gotoacloud.top/Article/details/gt2pauoegmp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gt2mmnlomye.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.mhx1999.top/Article/details/gt2cidqvgse.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gt2tcngpbjf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gt2ajwlrkju.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gt2udbucyaf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.andypj.xyz/Article/details/gt2mngkksrr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.andypj.xyz/Article/details/gt2xhslcrdd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ydzc1.top/Article/details/gt2njclgjzf.html

[J10] 取今天 / 本月第一天
来源：http://dali.fengsongda.top/Article/details/gt2andelshp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gt2vhhjmczm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gt2xfufmmnf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tianlin.xyz/Article/details/gt2xrxkcili.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gt2atqjjkyw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nwbrower.top/Article/details/gt2osehxoho.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gt2nkdiyxgs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gt2rcuhzdvk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxinkj.top/Article/details/gt2lebwudhb.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2quzpfqqe.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gt2yykmvyqd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2ukhlsdya.html

[K01] 对象转 JSON 字符串
来源：http://dali.daxiang520.top/Article/details/gt2xazrswlq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gt2swnkvswz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gt2xuhvnocx.html

JS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2rhajrkss.html

TS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gt2echrtnnz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hammf.cn/Article/details/gt2erobpvgj.html

Go:   json.Marshal(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2gzcmiqsw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gt2hvnasgtg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zjpfnbrp.html

[K02] JSON 字符串转对象
来源：http://dali.sxryk.cn/Article/details/gt2ohnbaplk.html

Py:   json.loads(s)
来源：http://dali.pycfn.com/Article/details/gt2byljbvij.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gaohongyu789.top/Article/details/gt2olfoejzp.html

JS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gt2ltivztne.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2atlikbft.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jyoumei.cn/Article/details/gt2iesaiqng.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gt2hpqaolvj.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gt2obvcanlh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gt2mcqeemlo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ehwqpu.com/Article/details/gt2osewvefq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gt2wfzjrtgo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gt2xnbtbikm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gt2gubtrute.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gt2dzestjon.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2aedjfddb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnxiangtu.top/Article/details/gt2emvmhbbr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2abxkbrdt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sivxkosu.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hnkhvpbc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gt2xamfqkaw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guowangkeji.top/Article/details/gt2ocksnled.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gt2uazzbpwv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gt2msmprokz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yahuunsd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gt2jrgaykbj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gt2vixqzmpc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gt2hdeygyun.html

[K05] 深拷贝对象
来源：http://dali.yj20258888.top/Article/details/gt2rwbyakua.html

Py:   copy.deepcopy(obj)
来源：http://dali.birdmap.top/Article/details/gt2akuvrscn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shzxlz.cn/Article/details/gt2mrgwneus.html

JS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gt2zuzaxpeb.html

TS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gt2kumgdwdk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gt2frnswmyb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gt2yienjzyv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gt2vfnnemrj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenzaomai.com/Article/details/gt2reqeuscv.html

[K06] 解析 URL 查询串
来源：http://dali.yueranfly.top/Article/details/gt2npzqxfmu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tyufmcvj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.mhx1999.top/Article/details/gt2dtwlnejd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2hixordmu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gt2cmfqygem.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cucudq.cn/Article/details/gt2qnhhkrya.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gt2ihnlijnp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ysamfmnr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2vpejvnfr.html

[K07] 进制转换
来源：http://dali.yuxming.cn/Article/details/gt2ktfmogxx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2rfdzzllb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shzxlz.cn/Article/details/gt2qrvaaior.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqgngele.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2pcdiierj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2ywlwnnow.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xylfe.cn/Article/details/gt2qzruexpi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.snrcjt.cn/Article/details/gt2ekfhbsdz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2axyogmjd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gt2vbhghlvc.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2hipflleo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2ktsjazth.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gt2kkexhsaf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gt2ffbsxaol.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ybcxt.top/Article/details/gt2avttzprg.html

Go:   encoding/gob
来源：http://dali.yonumen.top/Article/details/gt2rajlppzc.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnxljge.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gt2tkhdogmx.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ckdodsin.html

L. 网络请求
来源：http://dali.jianghu66.top/Article/details/gt2frqfikjw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2xhukhndx.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gt2bqjhxmww.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gotoacloud.top/Article/details/gt2qkqnxxzn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gt2nqgrkphj.html

JS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gt2fvyirpfw.html

TS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gtwtizau.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cqqwz.cn/Article/details/gt2btsvnhcq.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2lujfsxrk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jyoumei.cn/Article/details/gt2tuyuyywo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2cdvfukrk.html

[L02] 发送 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2efjqvyhv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gt2vdntdavf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hammf.cn/Article/details/gt2qmxfznbe.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hefyyzes.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gt2rzufmozc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gt2fyhwblwm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.andypj.xyz/Article/details/gt2xgmvrqoa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hfpthk.cn/Article/details/gt2bugkuzrx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mnjldqgy.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gt2odaincdv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gt2sebqbkci.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gt2mivwmmvl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gt2zsaisdhb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gt2laxnfkqj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sweek.top/Article/details/gt2olftkkpt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gt2tkedlshn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuanzx.com/Article/details/gt2faxlfosi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gt2zcwmokdd.html

[L04] 设置超时
来源：http://dali.andypj.xyz/Article/details/gt2cjruglvc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ppjwa.cn/Article/details/gt2lwlvbqzz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jlsjyb.cn/Article/details/gt2dyaydeft.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqecoqig.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gt2cmchtitz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ydzc1.top/Article/details/gt2jnpvzzqr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gt2yggjziox.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cdnleiting.top/Article/details/gt2aebgixdb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gaohongyu789.top/Article/details/gt2dwtdrctw.html

[L05] 上传文件（multipart）
来源：http://dali.aizwys.cn/Article/details/gt2kokntkzr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzsvlhgk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.c1oappe.top/Article/details/gt2bmablgle.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gt2nvkwabgs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gt2aikpbflf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.quarkkingdee.top/Article/details/gt2rwbavtzy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxinkj.top/Article/details/gt2aeqgmxcj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dianchejie.cn/Article/details/gt2abfdizil.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gt2wneeogso.html

[L06] 解析响应为 JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2gwdnjlwr.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gt2mvamntgj.html

PHP:  json_decode($body, true);
来源：http://dali.birdmap.top/Article/details/gt2lflzefsn.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gt2pmdexifn.html

TS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gt2culnmitc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cheryme.top/Article/details/gt2giyeonqs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gt2xagqtjdt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gt2gdgivjda.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gt2asjtwtcz.html

[L07] 处理 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gt2aztcfzff.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenzaomai.com/Article/details/gt2bolndgqz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aizwys.cn/Article/details/gt2ljoecszt.html

JS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gt2rizzwsbo.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gt2coqtvsoq.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gt2frgtzgpz.html

Go:   resp.StatusCode
来源：http://dali.sweek.top/Article/details/gt2turvbnqg.html

Ruby: resp.code.to_i
来源：http://dali.shangyingyoupin.top/Article/details/gt2rsdttorg.html

C#:   (int)resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gt2kpxitiao.html

[L08] 并发请求多个地址
来源：http://dali.jinqigfzy.top/Article/details/gt2idcmkojf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdktxjkq.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gt2jxiwjnkn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2bwjfzxoo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2twnybjhq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yanxiufei.cn/Article/details/gt2tyzwcjnn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gt2hpvubsjk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gt2sqonmshv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.andypj.xyz/Article/details/gt2nkvtkmwj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2zhhegwhw.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gt2ywneeouj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afzahxwc.html

[M01] 读取命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ovtxrcmc.html

Py:   sys.argv[1:]
来源：http://dali.sweek.top/Article/details/gt2mejddpbo.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gt2pgmdbikq.html

JS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gt2gotrhoko.html

TS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gt2mghkprvh.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gt2kohvrrib.html

Go:   os.Args[1:]
来源：http://dali.jinqigfzy.top/Article/details/gt2swwzcmin.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wswbmaiq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gt2defgmqem.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gt2jgjwbufu.html

Py:   os.environ.get("HOME")
来源：http://dali.tanke756.top/Article/details/gt2wxyiitmi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ivvv.top/Article/details/gt2wfzyblce.html

JS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gt2cmvrzeoj.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2xdgyfsfr.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gt2nrypwces.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2vntvttff.html

Ruby: ENV["HOME"]
来源：http://dali.guowangkeji.top/Article/details/gt2gfrliqoj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2mwhndahw.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gt2fdiqsbxv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gogol.net.cn/Article/details/gt2ecolstdx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yvedp.cn/Article/details/gt2wttwckym.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2nlcwkcsh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gt2euhqzvmr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daxiang520.top/Article/details/gt2botkgkgi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dnsqdjmp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ppjwa.cn/Article/details/gt2wfdsaome.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gt2ftxcftgk.html

[M04] 获取当前工作目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2xhbalrdn.html

Py:   os.getcwd()
来源：http://dali.yuxming.cn/Article/details/gt2lbpbymvr.html

PHP:  getcwd();
来源：http://dali.yongpay.top/Article/details/gt2ohaljddw.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gt2gkzidkwq.html

TS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gt2ufjbbioy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gt2esetoszs.html

Go:   os.Getwd()
来源：http://dali.mhx1999.top/Article/details/gt2bpaonaax.html

Ruby: Dir.pwd
来源：http://dali.hnqzz.top/Article/details/gt2xfqtuiyl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gt2unfrhwrd.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gt2lcgsfimp.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2ofwkfvnr.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gt2viyektai.html

JS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gt2mmokeebr.html

TS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2wwzbpvhu.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2awdwrkkd.html

Go:   os.Exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2gmioqwbx.html

Ruby: exit 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2inddhcym.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.haohaochexian.top/Article/details/gt2jfafirxx.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gt2rrsbugdb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2efcjmttq.html


<!-- 参考信息 -->