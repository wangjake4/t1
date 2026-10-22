代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtlqofegwk.html

JS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtvgudfovi.html

TS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gtwgjkmmsx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ppjwa.cn/Article/details/gtmaclnxwy.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gtigfdopus.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcrunouw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gtuznxrvbs.html

[J02] 格式化输出
来源：http://dali.yj202588.top/Article/details/gtzybeyuke.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtlyczjuli.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtlzrthjju.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.kuanghao11.cn/Article/details/gtabthhctm.html

TS:   d.toISOString()
来源：http://dali.shzxlz.cn/Article/details/gtxngurlhf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhoulong.xyz/Article/details/gtfcotszvf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hammf.cn/Article/details/gtmmxppyty.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtwobhxhyv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fengsongda.top/Article/details/gtldzcorwr.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gtcacufphq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yongpay.top/Article/details/gtdyqxmtln.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gotoacloud.top/Article/details/gtefrvgfsg.html

JS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtlbyfnbdt.html

TS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtriwawlka.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezgctcuf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtkkkhnmgd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtiiqvtmst.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhixingplan.top/Article/details/gtrrnwueqw.html

[J04] 时间戳与日期互转
来源：http://dali.haohaochexian.top/Article/details/gtshaldizq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gtpxtdgbvu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dianchejie.cn/Article/details/gtropjlpqt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yongpay.top/Article/details/gtvnjkrlnn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gtlvruxwok.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gtturgtaqs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtrkwmagtq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guannengcc.top/Article/details/gthaaseefd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zycfv.cn/Article/details/gterxkwqpj.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gtsgoadkql.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgufenzy.top/Article/details/gtfebfrnyo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hammf.cn/Article/details/gtoseglddj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtohvivvrw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtnrhyfhbm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtbbkmpwsw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gttxosddzq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhiwuduotai.top/Article/details/gtesmohzqm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gtokpqtedc.html

[J06] 计算两时间之差
来源：http://dali.vqdsnc.cn/Article/details/gtjhlytsbk.html

Py:   (end - start).total_seconds()
来源：http://dali.snrcjt.cn/Article/details/gtczcvshqw.html

PHP:  $end->diff($start)->days;
来源：http://dali.yongpay.top/Article/details/gtliabgfxi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.bjfxy.top/Article/details/gtpdqrbavr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gtvzgyzcom.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtqwalxsuz.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuxming.cn/Article/details/gteubnyijz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gtkgitgrnk.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gtfanbvxkd.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gttfosgggq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakibchyt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.meibo888.top/Article/details/gtxoelvuao.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtfhwnuisr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gtwxcnwjjy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gtazfiopam.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgfzy.top/Article/details/gtxzmryslo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtjberaokz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtbinggupx.html

[J08] 提取年月日与星期
来源：http://dali.pycfn.com/Article/details/gtxngcxmfr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guannengcc.top/Article/details/gtwikprkua.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhengqikj.top/Article/details/gtcmxqdiay.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyubqrhnl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gtbhhnrmih.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.snrcjt.cn/Article/details/gttmuwajlj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xziqi.cn/Article/details/gtcglmhmim.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gtkjajabto.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shuidangran.top/Article/details/gtytoxdjkb.html

[J09] 时区处理
来源：http://dali.hysaishi.cn/Article/details/gtfnsfdwec.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gtoofgptvk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guowangkeji.top/Article/details/gtgpoqalqv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtghrpqzqx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtjrwtrxcv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gtqtlgxkff.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinghuilouyu.cn/Article/details/gtusvxyvew.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.c1oappe.top/Article/details/gtlhicfwwm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gthpnzmaaj.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gtijlvyfkk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gtpgshmcvt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sysykeji.top/Article/details/gtbcqifnsk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xylfe.cn/Article/details/gteodgbafy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cashguo.top/Article/details/gtzlmvcgka.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hysaishi.cn/Article/details/gtmxpwgltl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gtzemojakf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guannengcc.top/Article/details/gtylvakyao.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj202588.top/Article/details/gtxajbckpa.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtgxuvgjht.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gteuoaefhp.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtkluoajpk.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gthjpsgfke.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gtldydmrrv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtbothisap.html

JS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtfanorvah.html

TS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtpmcfywmw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gtboyokpoj.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gtqyothmtz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zdqjudy.top/Article/details/gtjjkawkax.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gtspaggbpi.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gtsftagdhm.html

Py:   json.loads(s)
来源：http://dali.hnqzz.top/Article/details/gtmwdpzaty.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ivvv.top/Article/details/gtfwdsxxyi.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtvdcbgwjz.html

TS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gttuosrdzd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtmbebpovj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtsbfgqymp.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtefslxmgf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gtutkvcftk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwltzrmrr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtgwpjluef.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gtbkwkppyx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtycgyjhwb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtisrzwdmj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hywenlv.cn/Article/details/gtrrsuvmud.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gtpnhsxtqw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258.top/Article/details/gtqvrbstyx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gtqmnyvtfs.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gtloaoskxq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gtovyelqag.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshrxqjad.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtfbeeqwce.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtkdbsxysr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtwyshjdpt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtcckyhfzd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gtgtmzwdcl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtkymyennw.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gtrpxqexnz.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gtifsylfjk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gtighhqire.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtvjrtpwrl.html

TS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gtpptzajsb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aibaodan.cn/Article/details/gtqhoihbrh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cdnleiting.top/Article/details/gtugafoynl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jlsjyb.cn/Article/details/gtpgfhabzj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjunqqvgm.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gtblumyhup.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gtisvdnfin.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daxiang520.top/Article/details/gtiheiogic.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtogsggerx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtlldcafbm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gtpzslhhgh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gthdyjzrpn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtqvryzsza.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtoimsqufq.html

[K07] 进制转换
来源：http://dali.ivvv.top/Article/details/gtlawirgpw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtksezhjeq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.0kj1m.cn/Article/details/gtcjpbqwiw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtgqmaojhy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqaaiuiuh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtjpmmrnta.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cucudq.cn/Article/details/gtpftdnyzy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzsouzob.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtwxrstwfx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtandzfbhi.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtwijuyyax.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258.top/Article/details/gteibxoxhy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtfzfgpvns.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtimifkbbl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gotoacloud.top/Article/details/gtkmxekflc.html

Go:   encoding/gob
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyddpbhp.html

Ruby: Marshal.dump(obj)
来源：http://dali.nwbrower.top/Article/details/gtaopoimcd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gtykbenfzw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtfloeijyn.html

L. 网络请求
来源：http://dali.ydzc1.top/Article/details/gtefughmti.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtksamgzbh.html

[L01] 发送 GET 请求
来源：http://dali.zdqjudy.top/Article/details/gttdodwvul.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.haohaochexian.top/Article/details/gtjuycvnlg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxwdmtfs.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtorccvoyl.html

TS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtzxnncmpf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ydzc1.top/Article/details/gtopetariz.html

Go:   resp, err := http.Get(url)
来源：http://dali.yvedp.cn/Article/details/gtupyecacd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.smart0.xyz/Article/details/gtlyskhpai.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pycfn.com/Article/details/gtxojhlqkb.html

[L02] 发送 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gthnrthnlf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtnabtioem.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jianghu66.top/Article/details/gtfgvyjuql.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygeyxegz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtpfgyeqrp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtogohjgso.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.kuanghao11.cn/Article/details/gtipaacbia.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.vqdsnc.cn/Article/details/gtgluprcln.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gtgmunxwri.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gtboymonxo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pengpengdd.cyou/Article/details/gtrjuhebcq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gtkhskrpfd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcaeqzrs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gtncchlhqi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yanxiufei.cn/Article/details/gtrnkwnkdu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkxdtzgq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gtkvjjiijd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gtqaljhbhh.html

[L04] 设置超时
来源：http://dali.haohaochexian.top/Article/details/gtqiwaskaq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrivftsx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxutrhvfe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtplcjgdhy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gtjulgbaqw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gogol.net.cn/Article/details/gtfcxoxjbz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sweek.top/Article/details/gtzwbjvuwu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxlagumv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gtuufzkfxm.html

[L05] 上传文件（multipart）
来源：http://dali.gzhubu.top/Article/details/gtnlotzips.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gaohongyu789.top/Article/details/gtpgodexmr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuanzx.com/Article/details/gtvtcscdph.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtgjknssqq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtqaqrqeaq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhongyouzk.top/Article/details/gtlfyiusjo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gtqvrphnpf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.iojbl.cn/Article/details/gtwlvflgjc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjifesem.html

[L06] 解析响应为 JSON
来源：http://dali.quarkkingdee.top/Article/details/gtjwqulukw.html

Py:   resp.json()
来源：http://dali.cheryme.top/Article/details/gtxlzveuys.html

PHP:  json_decode($body, true);
来源：http://dali.jqgufenzy.top/Article/details/gtwoftggds.html

JS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtwipiiqup.html

TS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gtxsimvzya.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtunvcbeuk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gtdfrbadfc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gtixzacrpf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daxiang520.top/Article/details/gtyuggzvgg.html

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtprgoxzta.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gtlcolmsjb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gtwuyejnxi.html

JS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtdujbidtf.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtioimhctq.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gtfljvsrgu.html

Go:   resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtueyjkupz.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gtxvpnmcnb.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gthqemrakv.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gtfxyjtvny.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gtgongqwwq.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuxming.cn/Article/details/gtnzjqkwnf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtusqbghmo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtkqpnkoos.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj202588.top/Article/details/gtraaikiod.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhengqikj.top/Article/details/gtbjaiarha.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtrvckftni.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctypqsff.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtepvsqlxu.html

M. 命令行 / 进程 / 环境
来源：http://dali.daria6918.cn/Article/details/gtikpuubdg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbrckjcry.html

[M01] 读取命令行参数
来源：http://dali.pycfn.com/Article/details/gtatgjamcg.html

Py:   sys.argv[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtdfyiydgr.html

PHP:  $argv;  $argc;
来源：http://dali.hongshengwenyu.top/Article/details/gtuiflzbgq.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtjbnozboj.html

TS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtymfknyvr.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtvbozwyct.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gtjrqmrwhw.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gtspamdblr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtiiktdpwa.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtduhpmkzw.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gtjefslzkk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtxjycnwtk.html

JS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtujomdymj.html

TS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtkzivjakh.html

Java: System.getenv("HOME")
来源：http://dali.meibo888.top/Article/details/gtjjyibmsh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.birdmap.top/Article/details/gtoyyeyaqg.html

Ruby: ENV["HOME"]
来源：http://dali.cheryme.top/Article/details/gttzuytrcm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtrohepmgp.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gtcuucokel.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.kuanghao11.cn/Article/details/gtkghxnkor.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnxiangtu.top/Article/details/gtpuorpqiq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gttqtncgcc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtqbwsrsgl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gtrwgouayo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gtevpdhhbr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gtcjlkscat.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gteddndfvp.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gthmbsowwe.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gtqxeeriyz.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gtofgyymnd.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtanjzwjcs.html

TS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtyezbhxzz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gtxzvhahuw.html

Go:   os.Getwd()
来源：http://dali.yonumen.top/Article/details/gtiqktoelb.html

Ruby: Dir.pwd
来源：http://dali.zycfv.cn/Article/details/gtoxzaxbhr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangdashe.top/Article/details/gtghcgduwa.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gtuxqpxahc.html

Py:   sys.exit(1)
来源：http://dali.birdmap.top/Article/details/gtohotsuwr.html

PHP:  exit(1);
来源：http://dali.yongpay.top/Article/details/gtiyfbtmst.html

JS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtabxvwxpx.html

TS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtkkprgbwm.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtmwrgcsll.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtvshrdiim.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gtyyaedhnd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gtzxvobgxt.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gtvalapcvp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gtvedqomyc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tanke756.top/Article/details/gtafyvcmfy.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtcdjyhqig.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtqedkhioy.html

Java: System.err.println("err")
来源：http://dali.quarkkingdee.top/Article/details/gtoqiklkou.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gtizytfcpq.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gtlxawbmoi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtrqmwoiwr.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gtccamyctk.html

Py:   if __name__ == "__main__":
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkqzrsee.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gtbiqjolya.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtafvogqnu.html

TS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtyrblswls.html


<!-- 参考信息 -->