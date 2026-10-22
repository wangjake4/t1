代发 wailian999

J. 日期与时间
来源：http://dali.xinyue.icu/Article/details/gt2wxycnaci.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2htphedvq.html

[J01] 获取当前时间
来源：http://dali.jinqigfzy.top/Article/details/gt2kwahtsrg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shzxlz.cn/Article/details/gt2yaiibtnt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohtbmwmp.html

JS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qmurawnr.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enphczlj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gt2afibefkf.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gt2ndphuhef.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gt2cpaggvfl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ehwqpu.com/Article/details/gt2xuvwfuuu.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cpwtkogc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gt2crknbvqv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgcueuj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258888.top/Article/details/gt2qnuvpyxh.html

TS:   d.toISOString()
来源：http://dali.pycfn.com/Article/details/gt2iixkqslb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.mhx1999.top/Article/details/gt2rmrzdlad.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tanke756.top/Article/details/gt2bimgaftc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gt2wpmbmeuz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sufxvd.cn/Article/details/gt2eykkakzt.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gt2rrkliuvr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hfpthk.cn/Article/details/gt2dugbfnjr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gt2ozeepjvn.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2tbislszx.html

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2ovrdxkcb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vvuunlyi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgqubgxi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2tyaggtrf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yueranfly.top/Article/details/gt2ijfilpjt.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gt2rlryqjmv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258.top/Article/details/gt2utvcmbyx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daria6918.cn/Article/details/gt2dkskfksg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.meibo888.top/Article/details/gt2cquuwnbr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gt2txspfnaq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258.top/Article/details/gt2vzdctlvq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2nbabvepb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gt2adyfhekt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yonumen.top/Article/details/gt2aaurfkrd.html

[J05] 时间加减（加 7 天）
来源：http://dali.fengsongda.top/Article/details/gt2sywalffa.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gt2hmjetvto.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxinkj.top/Article/details/gt2vzurafay.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gt2rfsabijl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrgwllzw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guannengcc.top/Article/details/gt2jzldpkpc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenzaomai.com/Article/details/gt2qimwwbyb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yueranfly.top/Article/details/gt2kbhnauki.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cucudq.cn/Article/details/gt2jtdhcwtr.html

[J06] 计算两时间之差
来源：http://dali.xziqi.cn/Article/details/gt2dolpxjog.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gt2dazinvgj.html

PHP:  $end->diff($start)->days;
来源：http://dali.zdqjudy.top/Article/details/gt2kdaoyelh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gt2ozkxnrxo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dianchejie.cn/Article/details/gt2ginrukru.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yvedp.cn/Article/details/gt2lgjxowjl.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gt2zxremolo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.c1oappe.top/Article/details/gt2mbnqjxqd.html

C#:   (end - start).TotalSeconds
来源：http://dali.jyoumei.cn/Article/details/gt2ulhybwkk.html

[J07] 比较两个日期
来源：http://dali.sufxvd.cn/Article/details/gt2kqitphvf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2mlogtajb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gt2mfxgzoox.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gt2ibkklphv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gt2rivwvibb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gt2yefcowou.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgufenzy.top/Article/details/gt2zxbzvvui.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gt2yhrtljww.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gt2jmsekohj.html

[J08] 提取年月日与星期
来源：http://dali.hysaishi.cn/Article/details/gt2lmzzkgoq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gt2ieydmpcd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gt2hmnnmcxu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gt2sygmjeol.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuanzx.com/Article/details/gt2uevulnos.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.0kj1m.cn/Article/details/gt2lwdatodl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yvedp.cn/Article/details/gt2vbcfntqv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gogol.net.cn/Article/details/gt2kulvphzi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.kuanghao11.cn/Article/details/gt2iuqkehla.html

[J09] 时区处理
来源：http://dali.yueranfly.top/Article/details/gt2bitmiqga.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.9152youxi.cn/Article/details/gt2rblbhrdd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cqqwz.cn/Article/details/gt2lbudgaeq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2aweaolpg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gt2fpguvlhg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pjhiqsle.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ovlzzsov.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gt2udxzzkqf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gt2lzgpljsz.html

[J10] 取今天 / 本月第一天
来源：http://dali.xziqi.cn/Article/details/gt2frtvmgbp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangdashe.top/Article/details/gt2wktwnjnn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jianghu66.top/Article/details/gt2jcoyhvaw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gt2onkwgisb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2ioxizmuv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2rwczoxrj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gt2tdaebyhm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj202588.top/Article/details/gt2plxlutbo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gzhubu.top/Article/details/gt2ueytzito.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2exzmfhck.html

K. JSON 与序列化
来源：http://dali.yj20258888.top/Article/details/gt2jzcebznk.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ompntbbh.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigufen.top/Article/details/gt2ncnbtnxm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gt2vwfyqbtd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gt2sektlfdf.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohvncpvr.html

TS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2dkveeepb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gt2efcvzerq.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gt2yoangjpg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gt2cxoznsim.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gt2jwpwxqhf.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gt2dzrrsfav.html

Py:   json.loads(s)
来源：http://dali.sxryk.cn/Article/details/gt2nozedknq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gt2sqyrcrgd.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2bmktioxp.html

TS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2rcgajhei.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gt2wdaoeswh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gt2rhfgdtdu.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2fhpjzlsp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jyoumei.cn/Article/details/gt2ocdewwwj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gt2jvqgepdh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gt2vzcujlky.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tjmhyrsv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2rwmdilkb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2yzlyuxtu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.birdmap.top/Article/details/gt2aevhryjq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gt2vtrgqvua.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guannengcc.top/Article/details/gt2akahrbwy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gt2hxuqjcyh.html

[K04] 读取 JSON 文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2kzhjcmxc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xptmyznn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.havefunace.top/Article/details/gt2yexvumid.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gt2srjqtjcm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iauowire.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gt2qtgtiocn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2asmnboie.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2feokzrgg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gt2tumkcjie.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gt2zwfkflce.html

Py:   copy.deepcopy(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2igscqwds.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gt2irqcepet.html

JS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2coodqtif.html

TS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2pfohzlot.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daria6918.cn/Article/details/gt2sbrlnsis.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ydzc1.top/Article/details/gt2sgbjafcg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258.top/Article/details/gt2utugtdlw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhoulong.xyz/Article/details/gt2qcxhzggv.html

[K06] 解析 URL 查询串
来源：http://dali.ivvv.top/Article/details/gt2budrevax.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gt2deelosza.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sysykeji.top/Article/details/gt2wtthlcqm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2fqwkkadl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gt2aaamxtrt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.andypj.xyz/Article/details/gt2kyzkczqe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2lachusab.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2fweszpty.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2zycpnkat.html

[K07] 进制转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2etyeasce.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2iegwtehv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sweek.top/Article/details/gt2zgngflap.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oixfarek.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2coefojot.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2ztvyggld.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gt2tjqrczww.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aibaodan.cn/Article/details/gt2asodubfo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2kttkovqf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gt2vrvwvzzm.html

Py:   pickle.dumps(obj)
来源：http://dali.redwolf501.top/Article/details/gt2gfccqvjg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuanzx.com/Article/details/gt2jvkgthnb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gt2vfcrcirx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gt2izazuqfu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sufxvd.cn/Article/details/gt2gnezkdsx.html

Go:   encoding/gob
来源：http://dali.yonumen.top/Article/details/gt2efsnhrbj.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbdocvqm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gt2elywnjlj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ptztemrj.html

L. 网络请求
来源：http://dali.jqgfzy.top/Article/details/gt2wbuqdpxw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2xulgzcsf.html

[L01] 发送 GET 请求
来源：http://dali.zhixingplan.top/Article/details/gt2zrwzdjnx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigfzy.top/Article/details/gt2xtzsafri.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ehwqpu.com/Article/details/gt2bfepkubh.html

JS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gt2tfyylnpn.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gt2qqxbpydu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fzhhl.top/Article/details/gt2ybrfgapb.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gt2melxoteh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yonumen.top/Article/details/gt2neyllwgy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jkirdwbo.html

[L02] 发送 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gt2lmzfejfl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gt2dfhiooud.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhongyouzk.top/Article/details/gt2hrmkguxt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gt2sdvjdckk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gt2rpcnyaqv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nwbrower.top/Article/details/gt2ruczylei.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258.top/Article/details/gt2fkgieqey.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gt2chozxyum.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.9152youxi.cn/Article/details/gt2eqdpxxgx.html

[L03] 设置自定义请求头
来源：http://dali.smart0.xyz/Article/details/gt2wbiibuis.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tanke756.top/Article/details/gt2ytuayuts.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tian-w.cn/Article/details/gt2rbrjrkmb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gt2msftcjti.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gt2zzcgbfwd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cqqwz.cn/Article/details/gt2ewykkdvb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gt2qjnkfvbu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.feifeiyinyue.top/Article/details/gt2kljqzjoc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gt2bcgedufu.html

[L04] 设置超时
来源：http://dali.shangyingyoupin.top/Article/details/gt2lnneyrvc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gt2uievsfoz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gt2izgqtrce.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gt2gdnzzala.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gt2kyisewwz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgufenzy.top/Article/details/gt2unruuvuq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlnuscbt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daxiang520.top/Article/details/gt2idwfvuct.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gt2bdwxwqyn.html

[L05] 上传文件（multipart）
来源：http://dali.jianghu66.top/Article/details/gt2rtnplbar.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tanke756.top/Article/details/gt2uozagxgh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yvedp.cn/Article/details/gt2xtuylalv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gt2wvoaxcyo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gt2hzzjpvca.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gt2rbhxcadn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ivvv.top/Article/details/gt2tnrhifpe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdqpbcog.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2cfafekpc.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gt2zecyidon.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gt2llyxjrfv.html

PHP:  json_decode($body, true);
来源：http://dali.gzhubu.top/Article/details/gt2ngwqufay.html

JS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2oobcdrsw.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2ipotdgxe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2fljaufdj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gt2bacxjvrh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fzhhl.top/Article/details/gt2vreaccrj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gt2llqfwyft.html

[L07] 处理 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gt2ngckslhn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuanzx.com/Article/details/gt2uktmygei.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gt2ybbtiahs.html

JS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gt2tsjhkjvp.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gt2fxzmrheq.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gt2rupkygjm.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtohrtv.html

Ruby: resp.code.to_i
来源：http://dali.ivvv.top/Article/details/gt2diijlusn.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gt2ebzpkwgd.html

[L08] 并发请求多个地址
来源：http://dali.yanxiufei.cn/Article/details/gt2cvdfalnv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hysaishi.cn/Article/details/gt2laebfwlv.html

PHP:  curl_multi_init() 系列
来源：http://dali.c1oappe.top/Article/details/gt2kofgpvvn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gt2nnxwxomb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2fjriypon.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gt2zjdovaci.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yasyuhlz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hfpthk.cn/Article/details/gt2nhfgakny.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gt2tzqapbta.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ttrpigon.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qblsauqy.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2qojnrlgd.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gt2cxihozqz.html

Py:   sys.argv[1:]
来源：http://dali.gzhubu.top/Article/details/gt2nkizgbuv.html

PHP:  $argv;  $argc;
来源：http://dali.jqgfzy.top/Article/details/gt2pqxtcwqz.html

JS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gt2ytidmeyw.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gt2oekwckdf.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gt2aidtdrea.html

Go:   os.Args[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2lleienkc.html

Ruby: ARGV
来源：http://dali.aibaodan.cn/Article/details/gt2hxysxjez.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmyumlah.html

[M02] 读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfmihhid.html

Py:   os.environ.get("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzzimvvm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gt2lrugvdrw.html

JS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gt2xbcdbldt.html

TS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gt2jickhhac.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2njjfklww.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2qswxmffa.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gt2jcgogjwo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2abilprcz.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gt2xyhnbewc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sufxvd.cn/Article/details/gt2kigxuzsi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.kuanghao11.cn/Article/details/gt2bhvnstpv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gt2kgkbteyq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gt2dqbxdqdx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.andypj.xyz/Article/details/gt2ervquats.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jianghu66.top/Article/details/gt2jtpmarqj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dashuyun.cn/Article/details/gt2rgmeipys.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gt2wjwlqyzh.html

[M04] 获取当前工作目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2otgxhcrc.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2rpyuddpo.html

PHP:  getcwd();
来源：http://dali.yj202588.top/Article/details/gt2rtzzqjxk.html

JS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gt2uliodivs.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tmrgapip.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gt2zbvcbzxz.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gt2pxdocgks.html

Ruby: Dir.pwd
来源：http://dali.jinqigfzy.top/Article/details/gt2pqjqdbgj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dashuyun.cn/Article/details/gt2jlbfnqdu.html

[M05] 设置退出码
来源：http://dali.iojbl.cn/Article/details/gt2wpoinliz.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdjtummc.html

PHP:  exit(1);
来源：http://dali.haohaochexian.top/Article/details/gt2yhjvtvna.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2koiyfbus.html

TS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2pjduunvt.html

Java: System.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qhmcuoxp.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gt2fnwcwlog.html

Ruby: exit 1
来源：http://dali.sweek.top/Article/details/gt2viieyzpy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hfpthk.cn/Article/details/gt2ryssaqej.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gt2tvzmwbkj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gt2glmdferd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhiwuduotai.top/Article/details/gt2qpivqlyo.html

JS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gt2vfaquvih.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gt2konclahd.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gt2dqrziugd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuanzx.com/Article/details/gt2qzlwissi.html

Ruby: warn "err"
来源：http://dali.sxryk.cn/Article/details/gt2cpslbexl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gt2cdcbfoqg.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gt2nmttjatg.html


<!-- 参考信息 -->