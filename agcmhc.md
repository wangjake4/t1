代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gt2tannetzx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gt2whbhyrhh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gt2ajqfaeaz.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2hyrqkdlj.html

TS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2swkaolir.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2kddbacvm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2mymoufuk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2kioqmhis.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gt2uuglybwg.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmsqtuuj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gt2vxhazeaw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cucudq.cn/Article/details/gt2aqfriiiq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gt2zutllefa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gzhubu.top/Article/details/gt2ccgjjnew.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2xbsblmht.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2jhdtmdcb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2gwrcpbns.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2batkcvbn.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gt2gotxnqli.html

Py:   now + timedelta(days=7)
来源：http://dali.jlsjyb.cn/Article/details/gt2ytfxcprn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.quarkkingdee.top/Article/details/gt2svnrnyct.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gt2otmnglzr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gt2kyfdrsym.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gt2hfqrqafp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gt2tnjrkrti.html

Ruby: Time.now + 7 * 86400
来源：http://dali.mhx1999.top/Article/details/gt2tuqztdzt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dashuyun.cn/Article/details/gt2ztmgdprf.html

[J06] 计算两时间之差
来源：http://dali.jianghu66.top/Article/details/gt2xupedgbu.html

Py:   (end - start).total_seconds()
来源：http://dali.tian-w.cn/Article/details/gt2aclnudek.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhiwuduotai.top/Article/details/gt2eexzuecf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuanzx.com/Article/details/gt2palkfqex.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daria6918.cn/Article/details/gt2cldvqwdf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daria6918.cn/Article/details/gt2nkuvfqpn.html

Go:   end.Sub(start).Hours()
来源：http://dali.ivvv.top/Article/details/gt2qmqpwcet.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guowangkeji.top/Article/details/gt2retfkozd.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gt2exaokaqn.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gt2efadiiah.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gt2attudcen.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gzhubu.top/Article/details/gt2wzcmnshu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gt2rdbrrbtp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ssksfkov.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258.top/Article/details/gt2fsbvedro.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2gerptpiz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2lnnedyef.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2tlhohwoq.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxtdgerv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gt2mjalvpol.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwdrickm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.meibo888.top/Article/details/gt2hcmrosyu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gt2oppkcfvj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sxryk.cn/Article/details/gt2cetxqrnv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ybcxt.top/Article/details/gt2dynvrvmk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.mhx1999.top/Article/details/gt2qnwmkhuz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sweek.top/Article/details/gt2fqejjnhk.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gt2vfdxtfas.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ybcxt.top/Article/details/gt2ijqhfyid.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gt2zoaexynw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gt2zpalwlhl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gt2wpzxyqcp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhengqikj.top/Article/details/gt2nygblvif.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cucudq.cn/Article/details/gt2ycaepluh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gt2xiipuccb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jpzrvnvl.html

[J10] 取今天 / 本月第一天
来源：http://dali.havefunace.top/Article/details/gt2dinmhzft.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gt2tsfbtnvh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwkgulr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj202588.top/Article/details/gt2gyhlengo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ybcxt.top/Article/details/gt2ufkxamjw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gt2dftkcppt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ybcxt.top/Article/details/gt2rzuuhizj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gt2eetlkogq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gt2ymrnyvna.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2zxqycoiu.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gt2lzmzlpbc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2geknpsbm.html

[K01] 对象转 JSON 字符串
来源：http://dali.cheryme.top/Article/details/gt2ofspyxaw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gt2gllipium.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gt2zznsazmr.html

JS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gt2zwysbweb.html

TS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2drpppfcf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tian-w.cn/Article/details/gt2qwedqgsa.html

Go:   json.Marshal(obj)
来源：http://dali.xuanzx.com/Article/details/gt2fxndevbp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gt2kokrunos.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2ptpehqgx.html

[K02] JSON 字符串转对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdosrask.html

Py:   json.loads(s)
来源：http://dali.ehwqpu.com/Article/details/gt2irzhzmai.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jaunsiou.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuysqacj.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2dsiiiciz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2ukwullpp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gt2iafyzsho.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ulyzvwdm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gt2prafhyxe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hammf.cn/Article/details/gt2ftbiulnt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gt2rogmbhue.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gt2shntqqxd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gt2tdwwhhhw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2wskigmnc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2tmdahjka.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhongyouzk.top/Article/details/gt2yqndwdxo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gt2olnvwgbs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.bjfxy.top/Article/details/gt2atxuftzy.html

[K04] 读取 JSON 文件
来源：http://dali.yueranfly.top/Article/details/gt2yiipcuai.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gt2yweivrqp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gt2sehcfbxg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gt2gzwzgcyr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdwfabml.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gt2dhqrzsce.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khuojbwo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2boqfjhtg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xziqi.cn/Article/details/gt2susaysgy.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvvwnxbu.html

Py:   copy.deepcopy(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2xycyfhfu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ppjwa.cn/Article/details/gt2ifjolwcc.html

JS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gt2uectzfuz.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2uflvbcjg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sxryk.cn/Article/details/gt2xcwhrwwo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.redwolf501.top/Article/details/gt2yekeatey.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.mhx1999.top/Article/details/gt2dggduuco.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.haohaochexian.top/Article/details/gt2gtwvsnok.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2medawqcw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxrlyup.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.mhx1999.top/Article/details/gt2eovtnhft.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2bufqjopq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gt2opmntrnl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xziqi.cn/Article/details/gt2fxkqgkku.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2sxozjmzw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2yswiktid.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2ylhtdnre.html

[K07] 进制转换
来源：http://dali.cheryme.top/Article/details/gt2pfortmec.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2khytnqup.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibpqzcxm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2hyawkucq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2oledinpt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2rmqygvas.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnqzz.top/Article/details/gt2qoekktqg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gt2wiqkzpdo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2zrqamrqh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnqzz.top/Article/details/gt2gyslcrbs.html

Py:   pickle.dumps(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tfoyajqc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daria6918.cn/Article/details/gt2kzvifbub.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gt2dicbnofo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gt2zcnfnbyp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gt2rrjdrwuh.html

Go:   encoding/gob
来源：http://dali.0kj1m.cn/Article/details/gt2aaxryoub.html

Ruby: Marshal.dump(obj)
来源：http://dali.ydzc1.top/Article/details/gt2wyfvygkk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gt2bblzpial.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ncfezuuh.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gt2xbfoydhv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2xyvhozqs.html

[L01] 发送 GET 请求
来源：http://dali.zhixingplan.top/Article/details/gt2pzpqtsts.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangshuangyany.cn/Article/details/gt2jafhnmuh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.mhx1999.top/Article/details/gt2deoiidiu.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gt2ernkspqr.html

TS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gt2orhmdxrd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gt2ertavyes.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gt2cftftery.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj202588.top/Article/details/gt2fkhjdccm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gt2wddhzhnt.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gt2rxithpaa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbjpszxh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj202588.top/Article/details/gt2silnhviw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gt2ucpmhvtv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gt2wezbvghn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gt2vyrfdnbs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj202588.top/Article/details/gt2akyyerhi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gt2vnzzqvax.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ehwqpu.com/Article/details/gt2vqiknjqk.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gt2ejikipkg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gt2emgborac.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gt2ghcpptwd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gt2zmphtmzb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gt2yjzkmzoi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jyoumei.cn/Article/details/gt2fnhixfuu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gt2amrjojge.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guowangkeji.top/Article/details/gt2hviikcsm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ogayetpp.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gt2rlbiqftl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lycqkqdp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gt2jphfyaqj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gt2jgzewbsn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbhnmlc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuxming.cn/Article/details/gt2fhqbgduy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gt2eywwufpg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gt2lktsybnr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gt2pyngfuek.html

[L05] 上传文件（multipart）
来源：http://dali.cheryme.top/Article/details/gt2dygueyto.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sweek.top/Article/details/gt2ikznehqa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zfvjvkii.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gt2rhjrpenb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gt2mldinsth.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gt2lxemflub.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cheryme.top/Article/details/gt2vetcckhu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenjidiqi.icu/Article/details/gt2sravrrzk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2dtrvhhxg.html

[L06] 解析响应为 JSON
来源：http://dali.zhixingplan.top/Article/details/gt2oyjuyhcn.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dwhgfuqb.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izqzbbrs.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gt2cyoytehw.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gt2xbsygznn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xinyue.icu/Article/details/gt2rtevsion.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2icyvfzbk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gt2kayxjops.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gt2mgkigbhp.html

[L07] 处理 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gt2cmbfnbhv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gt2tyqjimct.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2wujqvtjv.html

JS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gt2ytzdntnx.html

TS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gt2ndrqqtim.html

Java: resp.statusCode()
来源：http://dali.fzhhl.top/Article/details/gt2dzkgfvbv.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gt2sairsotc.html

Ruby: resp.code.to_i
来源：http://dali.shuidangran.top/Article/details/gt2rzzbdzzx.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gt2wlabtmpy.html

[L08] 并发请求多个地址
来源：http://dali.shzxlz.cn/Article/details/gt2fkwnurtu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gt2koexjijg.html

PHP:  curl_multi_init() 系列
来源：http://dali.jianghu66.top/Article/details/gt2hlvzjawu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2vfphwrjc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gt2jyfjvymv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekitmwrt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gaohongyu789.top/Article/details/gt2xbbtwjxb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gt2jgufbwrl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gt2gbejvotv.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2zqbdxhrg.html

M. 命令行 / 进程 / 环境
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbvynwur.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2jodjgpwh.html

[M01] 读取命令行参数
来源：http://dali.chenzaomai.com/Article/details/gt2utpwviku.html

Py:   sys.argv[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2odulnksp.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtwwenei.html

JS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxugtkth.html

TS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gt2ipzbeuhq.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gt2vtnnpbgm.html

Go:   os.Args[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2nymtsqhp.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gt2svqzdvgg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gt2kldnevvx.html

[M02] 读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxniddee.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2lvmlwqqq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gt2zjkunhek.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gt2dikmpsqb.html

TS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gt2dxvebybb.html

Java: System.getenv("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2fwhoyurp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2rsotqmxm.html

Ruby: ENV["HOME"]
来源：http://dali.daria6918.cn/Article/details/gt2ljrfwkqo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2gmbhyerm.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gt2ztgqqyae.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2spsrbzqo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gt2ksqfltxr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gt2fvpldqlh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2zimfeiuu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ppjwa.cn/Article/details/gt2nudvtteq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmpzpqy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gyeogfvd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gt2ffjrjslv.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gt2hmjsdsop.html

Py:   os.getcwd()
来源：http://dali.yj202588.top/Article/details/gt2nlxoqnup.html

PHP:  getcwd();
来源：http://dali.zhoulong.xyz/Article/details/gt2pabyoizc.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gt2snzkaduk.html

TS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gt2ytsvyduf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gt2iocitphl.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2eankjqlj.html

Ruby: Dir.pwd
来源：http://dali.xziqi.cn/Article/details/gt2yemlayjs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.havefunace.top/Article/details/gt2mjaaulzl.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gt2erqavkgd.html

Py:   sys.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2wbkaqpbg.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gt2kefugwln.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2mvojqcri.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2icdmlnvi.html

Java: System.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2cxugpnrh.html

Go:   os.Exit(1)
来源：http://dali.316326.xyz/Article/details/gt2pjlhrmmp.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gt2rejkwptx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jianghu66.top/Article/details/gt2lxkfahiq.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gt2aofwufbp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gt2qbjqwkyj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxuanxn.top/Article/details/gt2yvirklws.html

JS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2xurramri.html

TS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gt2eqtxyrrl.html

Java: System.err.println("err")
来源：http://dali.sysykeji.top/Article/details/gt2axsqfvne.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuanzhike.top/Article/details/gt2vxaydcgb.html

Ruby: warn "err"
来源：http://dali.wangdashe.top/Article/details/gt2dhnvtucr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gt2nxqmlbxf.html

[M07] 判断是否为主入口
来源：http://dali.smart0.xyz/Article/details/gt2ywmxiccq.html

Py:   if __name__ == "__main__":
来源：http://dali.wangdashe.top/Article/details/gt2ufomdnqz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gt2liyzjitt.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gt2kboljwbw.html

TS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gt2cwpqujlj.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gt2hhtasfiv.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gt2dzdymaka.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fzhhl.top/Article/details/gt2volbvtxj.html

C#:   static void Main(string[] args)
来源：http://dali.dashuyun.cn/Article/details/gt2ocllpovc.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gt2evrqyhoa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gt2lhogquds.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hammf.cn/Article/details/gt2rchvhrdv.html

JS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gt2dksbhosh.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gt2uxzyaetl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.snrcjt.cn/Article/details/gt2xnteqvsj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hammf.cn/Article/details/gt2yyerbrxn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gt2gtaesadj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxuanxn.top/Article/details/gt2rbvpuxtc.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2dovelszy.html

N. 数据结构与算法
来源：http://dali.hfpthk.cn/Article/details/gt2ypliqdkf.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2zxiiwrlr.html


<!-- 参考信息 -->