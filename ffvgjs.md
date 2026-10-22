代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.smart0.xyz/Article/details/gt2diyiamdp.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gt2wrhwrzcp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nlmspowd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gt2sduxkkyw.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gt2tysgrtkn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aibaodan.cn/Article/details/gt2ywrbyjvu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gt2ckrayraa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fzhhl.top/Article/details/gt2fzfnarks.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gt2jgupasfb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gt2rpgdmjxa.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yvrbzpyr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gt2miypudmt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhengqikj.top/Article/details/gt2fgdtjnxa.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tanke756.top/Article/details/gt2xxsinrsi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gt2mhmpbwro.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2zoimnykj.html

J. 日期与时间
来源：http://dali.aibaodan.cn/Article/details/gt2fgktwcbu.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2pmkuyati.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gt2vkysufeh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuanzhike.top/Article/details/gt2tpruzzlc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2wzdoarit.html

JS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gt2qcfmblmf.html

TS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gt2izfyjhjx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hywenlv.cn/Article/details/gt2dvplhlht.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gt2xqsmgdcw.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gt2pllsloxq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sweek.top/Article/details/gt2ytbdjrix.html

[J02] 格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gt2yzyvksxq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgzpdry.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gt2kaivebfh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenjidiqi.icu/Article/details/gt2sowbsqao.html

TS:   d.toISOString()
来源：http://dali.nanxinkj.top/Article/details/gt2eplnvajw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gt2micwrsjm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gt2jxqkhfsf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gt2mivyhssp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hywenlv.cn/Article/details/gt2yllgpyrf.html

[J03] 字符串解析为日期
来源：http://dali.nwbrower.top/Article/details/gt2cgnycdlq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.quarkkingdee.top/Article/details/gt2djzyuikv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gt2xgsvdcmi.html

JS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2izbgnevn.html

TS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2ewfgdlak.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2gxewmzjd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2vsqntexn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2dtortrxo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fzhhl.top/Article/details/gt2npognzuh.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gt2bqcpuqiu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gt2ohcittcg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gt2odashpqv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cuomvrqt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zdqjudy.top/Article/details/gt2forzjfvo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2zwdwgyvh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2ivwfclpf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gt2ibuqhxbg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2ywsgfjfb.html

[J05] 时间加减（加 7 天）
来源：http://dali.hywenlv.cn/Article/details/gt2lsdlppuj.html

Py:   now + timedelta(days=7)
来源：http://dali.havefunace.top/Article/details/gt2giunnitl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jyoumei.cn/Article/details/gt2odkwdxey.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2acifjeve.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gt2eorhivib.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gt2lhlnhqxi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daria6918.cn/Article/details/gt2kippvvoi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jiagoushi.top/Article/details/gt2qljqgptw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfqzvub.html

[J06] 计算两时间之差
来源：http://dali.gaohongyu789.top/Article/details/gt2okbbqagf.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gt2hbbnwenx.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gt2hvsmvfzl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangdashe.top/Article/details/gt2emqptlbq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gt2tkompwqr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cucudq.cn/Article/details/gt2waxtnagg.html

Go:   end.Sub(start).Hours()
来源：http://dali.daria6918.cn/Article/details/gt2yizoxcih.html

Ruby: end - start                 # 返回秒数
来源：http://dali.redwolf501.top/Article/details/gt2nsydchzj.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2chowulkc.html

[J07] 比较两个日期
来源：http://dali.guannengcc.top/Article/details/gt2hmidhzmx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2jnpghppy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgufenzy.top/Article/details/gt2btbijdwf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gt2edjpvddg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gt2uqlbqweo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbqykdjv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gt2gawpsdhl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2bcqguyfp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gt2kpotcrmw.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gt2tkgkokxx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gt2arhqbvru.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gt2jbizbywn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dljemxzn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gt2cpfzuqnk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xylfe.cn/Article/details/gt2tmhiovpp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhvwdrsv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.redwolf501.top/Article/details/gt2teoflnzg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.smart0.xyz/Article/details/gt2qabbrerf.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gt2fbfajggy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dashuyun.cn/Article/details/gt2oarsxhfp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gt2vfnbxwmm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gt2sdtpjlzi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gt2pkdkwntt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.smart0.xyz/Article/details/gt2ugraoaij.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnxiangtu.top/Article/details/gt2haoradre.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipbwvvab.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gt2mzgqkmzx.html

[J10] 取今天 / 本月第一天
来源：http://dali.tanke756.top/Article/details/gt2epxammsi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gt2rmkmbghi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gt2kbfxtkqq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gt2othenswt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmejllhk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ybcxt.top/Article/details/gt2ixrqlrpp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gt2sguxttcs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnqzz.top/Article/details/gt2zkzkssxr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gt2psyawhpt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2lroknqxj.html

K. JSON 与序列化
来源：http://dali.hywenlv.cn/Article/details/gt2mshqpxdp.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2gdcofrld.html

[K01] 对象转 JSON 字符串
来源：http://dali.ydzc1.top/Article/details/gt2btlokbik.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gt2jqwxfovn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2jggslesh.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2xdcvbxck.html

TS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fdnnmuoy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daxiang520.top/Article/details/gt2jdtzqvak.html

Go:   json.Marshal(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2bwjcreta.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gaohongyu789.top/Article/details/gt2vxsofkjh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gt2llwwccsx.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gt2cvtbilbb.html

Py:   json.loads(s)
来源：http://dali.gzhubu.top/Article/details/gt2jbfrzpot.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hammf.cn/Article/details/gt2xkazyfap.html

JS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gt2xqrebyip.html

TS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gt2uwdijsqe.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxvfpjpa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvicwekv.html

Ruby: JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2bhxemtyf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uejuqqaz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gt2pracmsgh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gucvywvs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gt2kspvjoav.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gt2acfowukd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2urrlfwvk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gt2ndrbdfjr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.svipenyu.cn/Article/details/gt2bvugswan.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gt2yzhusjok.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenzaomai.com/Article/details/gt2kpaekylw.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gt2qxssrywi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gt2wwyupsoy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cdnleiting.top/Article/details/gt2bbyheged.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mddmyfgu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2ctlnxdxa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gt2ewddsevf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gt2pibzmcfa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gt2vnmggyfq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2qrkdmwra.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gt2vssewoib.html

Py:   copy.deepcopy(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2wlilyadt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yonumen.top/Article/details/gt2riyigice.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2rvieqflb.html

TS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2lfzgufce.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftnpumxi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zdqjudy.top/Article/details/gt2eextiduy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gt2wubzgdsb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gt2nhajylup.html

[K06] 解析 URL 查询串
来源：http://dali.yuanzhike.top/Article/details/gt2tajmnnyw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gt2qcgyoius.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2irzlbnhn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2jqcazbtt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gt2xyxrfere.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tpgoyhbo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gt2kgzrfvsz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2zrxgsglv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2kfxuehye.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2udoinock.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2adzvjntd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aibaodan.cn/Article/details/gt2wacwepxp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2asyperiq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2osyrthwa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2njchomjr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.feifeiyinyue.top/Article/details/gt2owcqokeh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hmniwikn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2okehrqqo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhengqikj.top/Article/details/gt2mgkwfkiw.html

Py:   pickle.dumps(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2haqffima.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fzhhl.top/Article/details/gt2qaqbbrrd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gt2nuxxnazk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2euseoxvj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gt2knijqfbc.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmtxlove.html

Ruby: Marshal.dump(obj)
来源：http://dali.ydzc1.top/Article/details/gt2ozynnljw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.birdmap.top/Article/details/gt2vyxmaaca.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2jgfyinnh.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gt2gljsvpke.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2phtehvyl.html

[L01] 发送 GET 请求
来源：http://dali.meibo888.top/Article/details/gt2wtcuyywj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuanzx.com/Article/details/gt2kiopabgi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gzhubu.top/Article/details/gt2opbbjian.html

JS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gt2vixmllwb.html

TS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gt2osaiyhin.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj202588.top/Article/details/gt2lwtxyzfx.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2bmrmqrew.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sysykeji.top/Article/details/gt2gdgnbern.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.meibo888.top/Article/details/gt2cweacjpg.html

[L02] 发送 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gt2pzmydwai.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gt2wxcmhixe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tianlin.xyz/Article/details/gt2fktaggqc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gt2wzyfvxhp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gt2wpvetsvt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gt2gntmpzxt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2szoxpdhx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fengsongda.top/Article/details/gt2gprwkapn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigufen.top/Article/details/gt2dwbhbnad.html

[L03] 设置自定义请求头
来源：http://dali.xinyue.icu/Article/details/gt2szdczpin.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gt2vmmoztvv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigufen.top/Article/details/gt2votrsbif.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gt2qziupbnm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gt2yuomncum.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sufxvd.cn/Article/details/gt2zzdrvjzd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gt2updltwxc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fengsongda.top/Article/details/gt2wzogxafo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gt2dznabuyb.html

[L04] 设置超时
来源：http://dali.9152youxi.cn/Article/details/gt2mqsosugw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gt2sgpovnvu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnqzz.top/Article/details/gt2uudfzvdy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gt2ghaqhbrx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gt2ycalawkr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gt2yqoutuka.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shzxlz.cn/Article/details/gt2mtfjrbmx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.snrcjt.cn/Article/details/gt2ysaxqfaj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gt2whlidmgs.html

[L05] 上传文件（multipart）
来源：http://dali.ehwqpu.com/Article/details/gt2sjruvryb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmuzeesr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sxryk.cn/Article/details/gt2ktqjbrnr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gt2fvrljbrx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gt2jjgnimob.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gt2omphkdyi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctjsvxmb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gt2niayxiwu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ecmafchm.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gt2whfzeawi.html

Py:   resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2mwgeqbdk.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gt2eotxswdl.html

JS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ssxfeanm.html

TS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gt2sgrbqdxw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gt2dnouvqla.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shzxlz.cn/Article/details/gt2myzoqabh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nwbrower.top/Article/details/gt2epfbgvfo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shuidangran.top/Article/details/gt2gymhdtgv.html

[L07] 处理 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gt2hxfgldji.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gt2ebpcmwyw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hfpthk.cn/Article/details/gt2ypasfzvk.html

JS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gt2dkcladdf.html

TS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gt2jahtnenr.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfaicoav.html

Go:   resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gt2ogztxrur.html

Ruby: resp.code.to_i
来源：http://dali.meibo888.top/Article/details/gt2mzsmcnji.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gt2oymydxvk.html

[L08] 并发请求多个地址
来源：http://dali.yj20258888.top/Article/details/gt2ywxtjoig.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gt2sowvwnza.html

PHP:  curl_multi_init() 系列
来源：http://dali.xylfe.cn/Article/details/gt2yhlbpcux.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gt2wicweeuo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gt2bvpnfqod.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shzxlz.cn/Article/details/gt2xyfvbpbp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zdqjudy.top/Article/details/gt2egrxfgss.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gt2wmfvmgor.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mxsfjoee.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ldooojxn.html

M. 命令行 / 进程 / 环境
来源：http://dali.tanke756.top/Article/details/gt2ggmejkrj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2nfhfceiz.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gt2fcmwzevt.html

Py:   sys.argv[1:]
来源：http://dali.hysaishi.cn/Article/details/gt2pllqdprn.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gt2uauxoqlg.html

JS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tstuqjdb.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehkqokra.html

Java: args 数组（main 方法参数）
来源：http://dali.cheryme.top/Article/details/gt2kyudkupl.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2jfuazcfx.html

Ruby: ARGV
来源：http://dali.jiagoushi.top/Article/details/gt2nomchaoy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gt2bpyycpxw.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gt2dmhjqrhi.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2edjxmeox.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gt2trjxilgn.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ltreqqdt.html

TS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gt2agfmmfbn.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2rfvjtqaq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2ktxsbzzm.html

Ruby: ENV["HOME"]
来源：http://dali.tian-w.cn/Article/details/gt2omcxaywh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2avpgexwv.html

[M03] 执行外部命令
来源：http://dali.xinyue.icu/Article/details/gt2djqkfvww.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yongpay.top/Article/details/gt2gvgqtxvq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gt2gfytbifa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2fvibktnr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxjkfpfo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ehwqpu.com/Article/details/gt2xjwwyphh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gt2vghdywgg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gt2rgxyerxt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gt2ejtwitby.html

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gt2ficgnfse.html

Py:   os.getcwd()
来源：http://dali.jqgfzy.top/Article/details/gt2nrngpjft.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gt2uyfglnfu.html

JS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gt2qjfkzofm.html

TS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gt2wvnqnush.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gzhubu.top/Article/details/gt2dqcykmqk.html

Go:   os.Getwd()
来源：http://dali.shuidangran.top/Article/details/gt2zqvxhbat.html

Ruby: Dir.pwd
来源：http://dali.feifeiyinyue.top/Article/details/gt2hvmpqwhg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shzxlz.cn/Article/details/gt2zsudirod.html

[M05] 设置退出码
来源：http://dali.hysaishi.cn/Article/details/gt2jqvfudoo.html

Py:   sys.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2nsdrqqko.html

PHP:  exit(1);
来源：http://dali.hywenlv.cn/Article/details/gt2clnponem.html


<!-- 参考信息 -->