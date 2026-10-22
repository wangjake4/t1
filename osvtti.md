代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gt2khimfwdq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gt2hpuqcwtn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2zwpnengt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2ztxtbiie.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gt2gezlftmi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hywenlv.cn/Article/details/gt2aqhacssg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gt2lyudfcyl.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2lceergpj.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzpaovcx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ttnoahtf.html

[J01] 获取当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gt2clsmlckh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.mhx1999.top/Article/details/gt2obiaunab.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gt2zbguijff.html

JS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gt2yqnixaig.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gt2yxgmscxr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258.top/Article/details/gt2djubyszn.html

Go:   time.Now()
来源：http://dali.smart0.xyz/Article/details/gt2rxjagrng.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gt2njstxrwn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gt2ruyshaph.html

[J02] 格式化输出
来源：http://dali.wangdashe.top/Article/details/gt2tnsiboxe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gt2rebyvoot.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gt2mrdrniwt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.haohaochexian.top/Article/details/gt2cbknooww.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gt2nrvgnmjg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuetiantiany.cn/Article/details/gt2wbowegaz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zycfv.cn/Article/details/gt2jpahaolf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gt2nwqzmpgh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuxming.cn/Article/details/gt2xdexqqex.html

[J03] 字符串解析为日期
来源：http://dali.tian-w.cn/Article/details/gt2wohlrqyf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.meibo888.top/Article/details/gt2qdqifsop.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slsmwqul.html

JS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2nainbtaz.html

TS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2vexqpzlj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2xgzxnljy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2ppcusehf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2ebgxqfan.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gt2qcthqbbz.html

[J04] 时间戳与日期互转
来源：http://dali.kuanghao11.cn/Article/details/gt2mvwlscvm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2vzckeocl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gt2rtaofykn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gt2frgissze.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gt2xagzbioq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2rbjkqhmn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gt2ggsfartn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2czsukwog.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2ibrgnrwh.html

[J05] 时间加减（加 7 天）
来源：http://dali.hfpthk.cn/Article/details/gt2cdsyaosz.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gt2pmshggae.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gt2ahtwwrnw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mvhaxqlp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gt2oawknrkd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2oaqkctic.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zdqjudy.top/Article/details/gt2wngsfymw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gt2dpdoopdz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gt2wftccvcs.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gt2iyscyxgy.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kelmwppb.html

PHP:  $end->diff($start)->days;
来源：http://dali.xylfe.cn/Article/details/gt2creiimdb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ecquansi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yongpay.top/Article/details/gt2aglchpqz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ydzc1.top/Article/details/gt2moskhlpt.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gt2dorbuczi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gt2zflrlqcg.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgfzy.top/Article/details/gt2fsyzrlip.html

[J07] 比较两个日期
来源：http://dali.cqqwz.cn/Article/details/gt2xrxohihf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2bflqxyxp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.kuanghao11.cn/Article/details/gt2isenkera.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gt2pvhposjp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbnielmg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gt2wvesfspm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2rhocfzmh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bsslcspi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gt2qhgdcpdh.html

[J08] 提取年月日与星期
来源：http://dali.jyoumei.cn/Article/details/gt2btlhwniq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuetiantiany.cn/Article/details/gt2sozkfjia.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gogol.net.cn/Article/details/gt2yhpfdpgh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.9152youxi.cn/Article/details/gt2unlfltpg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.feifeiyinyue.top/Article/details/gt2skgsaitb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.0kj1m.cn/Article/details/gt2gzosgupx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhbeoykt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnxiangtu.top/Article/details/gt2prbsfjbx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yvedp.cn/Article/details/gt2yqilhgrz.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gt2uuvqjcjc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gt2oogfakna.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gt2aluihyrp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gt2ifmddfwe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gt2xxkxqqpc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gt2yfqzeeax.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gt2oxhklivy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gt2cmjjvjay.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gt2mzegyamz.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgfzy.top/Article/details/gt2muvkrrku.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gaohongyu789.top/Article/details/gt2kckegcij.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.iojbl.cn/Article/details/gt2bwtbkdei.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gt2hloxympt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.bjfxy.top/Article/details/gt2qhncrlum.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gt2xsgfhflu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.havefunace.top/Article/details/gt2eroihqjf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gt2avcjlbot.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2najxrlcx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2otsbwsug.html

K. JSON 与序列化
来源：http://dali.xylfe.cn/Article/details/gt2qvgznmyl.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2lvwrusdo.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gt2zaurchpg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gt2jskjtbnj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gt2wdlgjztj.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2hvhkxbdo.html

TS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gt2wkrxscjq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmslwguu.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2yhmjipxv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gt2jzniuwwl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2rpxmnqtw.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigufen.top/Article/details/gt2jnvaulxm.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mewgpipy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxinkj.top/Article/details/gt2iipzvxcl.html

JS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lkrhhxse.html

TS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2qyjatcmi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2zunqdssp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gt2rngsnenl.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2pozjtwej.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gt2ffxdzmgg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.mhx1999.top/Article/details/gt2wdinagrf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjavipkv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gt2kbqdukeh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gt2rdtayipf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2nqwiqewj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2xwksqqgg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tian-w.cn/Article/details/gt2xasbnjrx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuxming.cn/Article/details/gt2afmzlmnp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yvedp.cn/Article/details/gt2hchcwkws.html

[K04] 读取 JSON 文件
来源：http://dali.zhengqikj.top/Article/details/gt2wwskxncz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gt2icjhcpft.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gt2kagknfoo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gt2xhnlfhfn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2nlroqhbb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gt2slapgglz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lanbrlnl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2lpgfcyqb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ejgozciq.html

[K05] 深拷贝对象
来源：http://dali.zhongyouzk.top/Article/details/gt2voanpfgm.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gt2ciqzeysp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.9152youxi.cn/Article/details/gt2mvzowbwy.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2jekwxkdj.html

TS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2ennyemgn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gt2hvqfhcdj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhixingplan.top/Article/details/gt2sfdnzeww.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hammf.cn/Article/details/gt2ejjmrviq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ganixzqh.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gt2lajyybde.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gt2bbthrgze.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gmnedlqn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2ayixpzgf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gt2eikcfoba.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gt2mxqwinfc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gt2shxmdzpo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2xrqsdkfr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gt2ilkbivjj.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnonjtpb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2mwkwuekq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gt2xyaalfob.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2vvjsvaas.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2eubzkbbv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2btfyjasg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dtvnyicq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pycfn.com/Article/details/gt2gmfpohhz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2pajjiahh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhengqikj.top/Article/details/gt2awbvifhg.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gt2fegxxihy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2noqidueu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2humitllm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gt2pienjntm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxrsfwzj.html

Go:   encoding/gob
来源：http://dali.zdqjudy.top/Article/details/gt2xubewmqm.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2obxciwus.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gt2ctzfqsnx.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2hzrraifm.html

L. 网络请求
来源：http://dali.cucudq.cn/Article/details/gt2tmzfbevk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2khgcewsd.html

[L01] 发送 GET 请求
来源：http://dali.xuanzx.com/Article/details/gt2ukhylqrb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpswaqx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tanke756.top/Article/details/gt2jlnvbzho.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2egpfsmag.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iedkmyai.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gt2dnpdrgpu.html

Go:   resp, err := http.Get(url)
来源：http://dali.gotoacloud.top/Article/details/gt2tfuzhjqu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sxryk.cn/Article/details/gt2ymvhbddc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sysykeji.top/Article/details/gt2pjdbjvvy.html

[L02] 发送 POST JSON
来源：http://dali.yvedp.cn/Article/details/gt2qdhpsqby.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gt2qaufplem.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gt2toqtaunu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2yruhrmwf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gt2fexcuzns.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.9152youxi.cn/Article/details/gt2thlezfye.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqrsqjlq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shzxlz.cn/Article/details/gt2zorajtll.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hammf.cn/Article/details/gt2ddnbaoph.html

[L03] 设置自定义请求头
来源：http://dali.vqdsnc.cn/Article/details/gt2gooexzqm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhzbunsq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aizwys.cn/Article/details/gt2cpajrwmh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gt2oapxmwxn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gt2hfjsywrf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gt2lbkkkhcm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gt2zgywhkvv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258888.top/Article/details/gt2alhmvbnb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gt2vbooquyg.html

[L04] 设置超时
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjcfoknt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xylfe.cn/Article/details/gt2guzikvwe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tgveqzic.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gt2zdxceyvq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2idqgyovg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xritfagk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gt2rtdscdkw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gt2sijemenp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gt2mlflsjoh.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvlycugr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhoulong.xyz/Article/details/gt2cquiamrz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnqzz.top/Article/details/gt2wonaahqn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gt2kbdgyvbk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gt2yjrtjgxa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iyvrjejy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenlongwang.top/Article/details/gt2akvncjil.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gt2gsexmszh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2bpocvesd.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigufen.top/Article/details/gt2aetahhqx.html

Py:   resp.json()
来源：http://dali.pycfn.com/Article/details/gt2duprozcn.html

PHP:  json_decode($body, true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2snppodyr.html

JS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gt2ubdxondg.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wbliuodc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cheryme.top/Article/details/gt2kkqukgfp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gogol.net.cn/Article/details/gt2hgqovqmy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jyoumei.cn/Article/details/gt2xsfwpwuw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zdqjudy.top/Article/details/gt2uvsysdga.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gt2yzejeqaq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.birdmap.top/Article/details/gt2buywgcah.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvdycqjm.html

JS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2equvktdw.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gt2tympygwj.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gt2rxwjxiac.html

Go:   resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gt2grobjtju.html

Ruby: resp.code.to_i
来源：http://dali.mhx1999.top/Article/details/gt2mpvevztg.html

C#:   (int)resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gt2pkavtbwg.html

[L08] 并发请求多个地址
来源：http://dali.xziqi.cn/Article/details/gt2kchcxlsu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dacgikuf.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gt2zytxmmyy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ganrufmx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gt2gspcccqb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hywenlv.cn/Article/details/gt2xaiumieh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.iojbl.cn/Article/details/gt2qnvvzyao.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2bguoezio.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gt2vnbtmzsy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2deqehnhe.html

M. 命令行 / 进程 / 环境
来源：http://dali.yongpay.top/Article/details/gt2stzokufq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2xdlfwrkw.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gt2yxhjgkev.html

Py:   sys.argv[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2yxhbmjnm.html

PHP:  $argv;  $argc;
来源：http://dali.cheryme.top/Article/details/gt2agnpasot.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gt2rnzlxtfj.html

TS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gt2pmpqyuej.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gt2bcujfzgt.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhgpvjph.html

Ruby: ARGV
来源：http://dali.ybcxt.top/Article/details/gt2fqlwmcnv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gt2jcyfldap.html

[M02] 读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gt2anieylxp.html

Py:   os.environ.get("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2nedfuvak.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gt2alwksugf.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gt2xhkcbltn.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gt2rdhkzbpy.html

Java: System.getenv("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2unvgzxum.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gt2rdzmyela.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigfzy.top/Article/details/gt2bmnhrvna.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nuyqumye.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2plwxoogv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.kuanghao11.cn/Article/details/gt2fysrmbjk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gt2xjbtmtgt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gt2zroesmyu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gt2fmzgxljg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangdashe.top/Article/details/gt2ubfblqyq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.vqdsnc.cn/Article/details/gt2lbcrguos.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gt2dzakyrbv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gt2vcxwwsuw.html

[M04] 获取当前工作目录
来源：http://dali.yanxiufei.cn/Article/details/gt2jbdgwbbw.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gt2durwihtw.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdzhrtlu.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gt2royvkthr.html

TS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gt2kvycmzkw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gt2beimldip.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2xinzolld.html

Ruby: Dir.pwd
来源：http://dali.chenlongwang.top/Article/details/gt2jwdywoee.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhongyouzk.top/Article/details/gt2ztbgcppa.html

[M05] 设置退出码
来源：http://dali.shzxlz.cn/Article/details/gt2ijhpjlrb.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2ssrkfbgi.html

PHP:  exit(1);
来源：http://dali.316326.xyz/Article/details/gt2jspjvywm.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2ahfnigxc.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2znvjrxbp.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2kgiripyl.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdzyuqu.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gt2jjofribt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gt2gztkzpsk.html

[M06] 向标准错误输出
来源：http://dali.dashuyun.cn/Article/details/gt2krmoltxn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gt2syeryawf.html


<!-- 参考信息 -->