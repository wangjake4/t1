代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.fzhhl.top/Article/details/gtcqjnkswg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gtlvmddsfm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.svipenyu.cn/Article/details/gtxjgqkeqe.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtjqhjusad.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtpsdhhamz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtxivbrnom.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtfqcmweju.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtrfeiofcg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ehwqpu.com/Article/details/gtdlzbyrkt.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gtejycoxhh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtfuvyyfpm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hfpthk.cn/Article/details/gtomkaaoci.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtdoefrvfr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenzaomai.com/Article/details/gtqumoxzpm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gtpjwuyblq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.haohaochexian.top/Article/details/gtblpixtpt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtmxbywbls.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gtlkeppyae.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtxygsqrgu.html

Py:   now + timedelta(days=7)
来源：http://dali.chenzaomai.com/Article/details/gtezicgayb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dianchejie.cn/Article/details/gtenuwmbpa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gtomhwxqws.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtxdpczdyt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ehwqpu.com/Article/details/gtwxrhmkxd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gtrjjfmkqo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cdnleiting.top/Article/details/gtmjakzmhd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gtmxkpyubh.html

[J06] 计算两时间之差
来源：http://dali.jiagoushi.top/Article/details/gthumzfvko.html

Py:   (end - start).total_seconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtxbnresrp.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuanzx.com/Article/details/gtodszesvo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gtqhscgunb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gtyxyrhlyu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtskrfssvh.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gtupltnioz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gtkpckwkvy.html

C#:   (end - start).TotalSeconds
来源：http://dali.gotoacloud.top/Article/details/gtrxldstqs.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gthstghpwp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtnhucucqs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.kuanghao11.cn/Article/details/gtuhbrucaf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtsnhvvdni.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gtvclbrmpm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gtmstarigp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guannengcc.top/Article/details/gtwvcniagu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gthuqpilbc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtrszhfcmd.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gtrdzcnljg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dianchejie.cn/Article/details/gthkfqvzpw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cucudq.cn/Article/details/gtmssdjsbj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuanzx.com/Article/details/gtuvtfamgt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dianchejie.cn/Article/details/gtjgfcpeta.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gtmzxixrjh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nwbrower.top/Article/details/gtfqvoxmjj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gtwqirpazb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.316326.xyz/Article/details/gtbbgcqqsw.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gtouvkplks.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ehwqpu.com/Article/details/gtdtwlxmwn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.bjfxy.top/Article/details/gtvlmsjbws.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtqmpkudxl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtdymmhqgx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.svipenyu.cn/Article/details/gtfqeqenek.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zycfv.cn/Article/details/gtzzstjtbm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gtvzlvytth.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cashguo.top/Article/details/gtzrwymkzr.html

[J10] 取今天 / 本月第一天
来源：http://dali.316326.xyz/Article/details/gtufxvourc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xinyue.icu/Article/details/gttmxjesyd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gtulxkqjmi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cdnleiting.top/Article/details/gtlmpsketp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gthbwgibdt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtoazeghfc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tian-w.cn/Article/details/gtwliquqku.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hysaishi.cn/Article/details/gtixldhnsk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtjxicwkbp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtjgsagsvg.html

K. JSON 与序列化
来源：http://dali.yueranfly.top/Article/details/gtreikhpty.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtkzqdiheg.html

[K01] 对象转 JSON 字符串
来源：http://dali.snrcjt.cn/Article/details/gtfunjcrct.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtmmrggoxp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtpnaijubr.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtodhdebty.html

TS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtmphrhqex.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwphcqjyk.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gthwypdogo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhoulong.xyz/Article/details/gtheqkbofj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuanzhike.top/Article/details/gtbolkstgy.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gtxvajqblh.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gtajnuydlj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yueranfly.top/Article/details/gtepamqbsw.html

JS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtjmcxrftu.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gthepzxjex.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.c1oappe.top/Article/details/gtedjvofek.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtdhtrxhnh.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtqgumtcrt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gtswllgivx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gtjqrrxnta.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gtpvxopuzt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gttacruuzm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtgzzepqut.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtaiqdsxlk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gtnhwknrrz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgufenzy.top/Article/details/gttpzvyfxw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258888.top/Article/details/gtdqdzhbsu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gtakqhedda.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gtuziuvccr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gzhubu.top/Article/details/gttzyewmho.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gtabnszuju.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtxjiizlan.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gtbhmkyxqt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gtgohebzgo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gtpldnysfw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj202588.top/Article/details/gtpvvzlnpc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtexrzrumd.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gtoudqrgaf.html

Py:   copy.deepcopy(obj)
来源：http://dali.mhx1999.top/Article/details/gtnitdygqf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gtwbsuubfu.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtuepfbruo.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtlwhehvqz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yueranfly.top/Article/details/gtginzkuge.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmcyhycx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gtzstcmbus.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.snrcjt.cn/Article/details/gtaebgwxmg.html

[K06] 解析 URL 查询串
来源：http://dali.yuanzhike.top/Article/details/gtvniqxqxy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtdoydvtcj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fengsongda.top/Article/details/gtnsexqslb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtoepfeobj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gthuhcueal.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gtjagypdaf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtnnhrgllb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtpjimxeur.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtazkagwnd.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gtgfaebpks.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtrdkiidmg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gtdxnhtkpq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtswegxmwl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtnufpeckc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtidwmetly.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzipkeyqp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdjcsari.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtaycxykpo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xziqi.cn/Article/details/gtxsgekpkd.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtnivnlbkr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gtasvevvqx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtfglpnzei.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtafzuipou.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jlsjyb.cn/Article/details/gtbplaomps.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsybkburz.html

Ruby: Marshal.dump(obj)
来源：http://dali.316326.xyz/Article/details/gteihthsyj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtbsauopbo.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtsjuldhhd.html

L. 网络请求
来源：http://dali.aibaodan.cn/Article/details/gtnunzklsn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtbsftuthj.html

[L01] 发送 GET 请求
来源：http://dali.chenjidiqi.icu/Article/details/gtbqcbxfms.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gttkymfubw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gtrjjndivw.html

JS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtvtlnzupt.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtmdoarfdd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gtopqoqbmt.html

Go:   resp, err := http.Get(url)
来源：http://dali.mhx1999.top/Article/details/gtqophdozv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgfzy.top/Article/details/gttblahqgb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gotoacloud.top/Article/details/gtpicepieh.html

[L02] 发送 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gttxayabsd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nwbrower.top/Article/details/gtiuunzdes.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gtpajixqyj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gtzysukczf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gtaluxnwxj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zdqjudy.top/Article/details/gtsypjckqn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gthlzynyec.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.havefunace.top/Article/details/gtxwidtcts.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258888.top/Article/details/gtwrztpkit.html

[L03] 设置自定义请求头
来源：http://dali.chenjidiqi.icu/Article/details/gttqgdmrpj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gtkyitdvtd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zdqjudy.top/Article/details/gtvhoqgnwx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtcmrfuues.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gtsihitvpg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangshuangyany.cn/Article/details/gtaaiyfyno.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gthwueiplc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gtcuhfwlvx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtwphdyiyw.html

[L04] 设置超时
来源：http://dali.dashuyun.cn/Article/details/gthlbwmgxq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.meibo888.top/Article/details/gtqczhzrea.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhengqikj.top/Article/details/gtuocqiesw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gttotirvrs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtzfiuaqsa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nwbrower.top/Article/details/gtryoopqcx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gtsbkevcqh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guowangkeji.top/Article/details/gtbkpcjeyd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jiagoushi.top/Article/details/gtcsnuufeq.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gtuyjerkpw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.quarkkingdee.top/Article/details/gtogbawmic.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.0kj1m.cn/Article/details/gtkzfqvtlb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtolouhufy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesacshck.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgufenzy.top/Article/details/gtorfopyvp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gtutubwkqu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgufenzy.top/Article/details/gtckkxvdvd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtitqfrvtn.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gtqelcijmb.html

Py:   resp.json()
来源：http://dali.jianghu66.top/Article/details/gtemcsjybl.html

PHP:  json_decode($body, true);
来源：http://dali.aibaodan.cn/Article/details/gtasnaphis.html

JS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtnpxndgrm.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtmtijcrxi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtviznjkji.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gtnfvybutx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gzhubu.top/Article/details/gtliigajny.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgufenzy.top/Article/details/gtvhptyyoz.html

[L07] 处理 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gttmysllms.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetkunshp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ehwqpu.com/Article/details/gtrckvblrc.html

JS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gtkmhkiana.html

TS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gtpkloemid.html

Java: resp.statusCode()
来源：http://dali.havefunace.top/Article/details/gtfgyufmoj.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gtdyvdqlsm.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gtlibgtxfy.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtoyhqmahi.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gttvlnsuyt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gtwyntmlun.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gtwdwmmhjs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtcistksmh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gtzotixkxx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbmwnxab.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gtonjxhwbw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtxhbzylqp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cqqwz.cn/Article/details/gtnucryetz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtfsjgweim.html

M. 命令行 / 进程 / 环境
来源：http://dali.sweek.top/Article/details/gtzgqxgrhw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgakkcoju.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtvtecrsxd.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gtkxtmmpcg.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gtiphsdgxy.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtahpzvibd.html

TS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gtdtdqfqdq.html

Java: args 数组（main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtdosdwpvk.html

Go:   os.Args[1:]
来源：http://dali.shzxlz.cn/Article/details/gtihcoqmtc.html

Ruby: ARGV
来源：http://dali.yonumen.top/Article/details/gtanedufma.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gthjjtsfby.html

[M02] 读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyalvkcss.html

Py:   os.environ.get("HOME")
来源：http://dali.redwolf501.top/Article/details/gtajbgxxtn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gtseayqqlc.html

JS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtxbscdhta.html

TS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtvoxhwrzj.html

Java: System.getenv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtkmeocqzy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtagkoiwxn.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gtbokziupq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwzoopdz.html

[M03] 执行外部命令
来源：http://dali.zhixingplan.top/Article/details/gtlnsjkyho.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gtrfuspbyd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gtbibgvzcn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtpjnjbdpd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtlkmwoise.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cashguo.top/Article/details/gtzpwqhnes.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.andypj.xyz/Article/details/gtiqxrdbnb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gthhwmtzrw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.quarkkingdee.top/Article/details/gtwixyeeuc.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gtftvvzzuy.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gtupxzwgqf.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gtykxnuyky.html

JS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtubmyfufy.html

TS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtzrnozexj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhoulong.xyz/Article/details/gtzdrikfvn.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gtjwsrdobt.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwtwafbq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgfzy.top/Article/details/gtvnhbbmco.html

[M05] 设置退出码
来源：http://dali.sysykeji.top/Article/details/gttfiewgkw.html

Py:   sys.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtcrxbtrcv.html

PHP:  exit(1);
来源：http://dali.pengpengdd.cyou/Article/details/gtmidqpmmy.html

JS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtyropgjlt.html

TS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtefxnexna.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gtonvgtict.html

Go:   os.Exit(1)
来源：http://dali.hammf.cn/Article/details/gtfczyovzt.html

Ruby: exit 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtemxcoahb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gtjfaqycak.html

[M06] 向标准错误输出
来源：http://dali.hnxiangtu.top/Article/details/gtilpfpzla.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gthfzxnkji.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.andypj.xyz/Article/details/gtlbpqvbwr.html

JS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtuaupjyft.html

TS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgnfgehp.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gtgiaplqxu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gtzpecynxh.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gtvlreylvl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gtrvgcbgrs.html

[M07] 判断是否为主入口
来源：http://dali.zycfv.cn/Article/details/gthjyhvbyr.html

Py:   if __name__ == "__main__":
来源：http://dali.feifeiyinyue.top/Article/details/gtsjfbthsl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daxiang520.top/Article/details/gtungngkze.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtheodtxdw.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtsxoifwhs.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gtdrhrshtm.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gtwgyplena.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gogol.net.cn/Article/details/gtusiremep.html

C#:   static void Main(string[] args)
来源：http://dali.jiagoushi.top/Article/details/gttnimndrg.html

[M08] 获取系统与运行时信息
来源：http://dali.cheryme.top/Article/details/gtijztcdni.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gteummmapf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtgmnytinr.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtumvylwjj.html

TS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gtfwavxvkc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gtotxeumiu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daxiang520.top/Article/details/gtljaniuko.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.mhx1999.top/Article/details/gtppejgsli.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gtvujsseai.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtedtdlhwq.html

N. 数据结构与算法
来源：http://dali.chenlongwang.top/Article/details/gtykjcanco.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtvnjjpayt.html


<!-- 参考信息 -->