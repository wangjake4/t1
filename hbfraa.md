代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.andypj.xyz/Article/details/gthchqbkhx.html

[J04] 时间戳与日期互转
来源：http://dali.fzhhl.top/Article/details/gticwsziuw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gtkgrrkxdv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gtumixrosw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gtyrrvmhcm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtqoqballf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gtvcpgmkxb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.0kj1m.cn/Article/details/gtvmtbcnvb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gtsjwarxct.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnfsrgty.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gtesfgcdwb.html

Py:   now + timedelta(days=7)
来源：http://dali.yueranfly.top/Article/details/gteyqtsuic.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gtidknsjey.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtcqxyvxom.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gtjupopwes.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtvnjscomb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gttijmqvjd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gtmdacekpm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gtvvdlfyvt.html

[J06] 计算两时间之差
来源：http://dali.vqdsnc.cn/Article/details/gtaicjlhzv.html

Py:   (end - start).total_seconds()
来源：http://dali.nwbrower.top/Article/details/gttwnrzbxq.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gteiqcjfvz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfcbewjz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.316326.xyz/Article/details/gttnhyuavv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.9152youxi.cn/Article/details/gtgvnoirdx.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinghuilouyu.cn/Article/details/gthcipfrjk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gtaqqisfzd.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangdashe.top/Article/details/gtkiiyivhb.html

[J07] 比较两个日期
来源：http://dali.snrcjt.cn/Article/details/gttincpjsn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtiwmctyfs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gttjrvillr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmmoosqq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gtuszvsmef.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jiagoushi.top/Article/details/gtphyhlubt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gttdhevpwe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtjdgrcuol.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtrxbwnkuj.html

[J08] 提取年月日与星期
来源：http://dali.haohaochexian.top/Article/details/gthbepvtho.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gthcxtuewt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fengsongda.top/Article/details/gtxuzinmad.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gtnpxehvjz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gteikfnket.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jyoumei.cn/Article/details/gtsclbscav.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gtgalzankd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gtttxxiddj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gtsqldqowa.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gtogriserq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gogol.net.cn/Article/details/gtoqqwxbrf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gtqsxuvvlc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gtpjumbppo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtsmtwyhdd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gtmyoamena.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nwbrower.top/Article/details/gttijcpvbu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gtesqqiwzj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zycfv.cn/Article/details/gtkkuaylsu.html

[J10] 取今天 / 本月第一天
来源：http://dali.shuidangran.top/Article/details/gtdyokdcln.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.andypj.xyz/Article/details/gtnclqdwqh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yonumen.top/Article/details/gtbxflhowh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.andypj.xyz/Article/details/gtqvzjidey.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtmmrajaih.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gtnyppcjcm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gtblekgfie.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zdqjudy.top/Article/details/gtyrpngzip.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtszayaccm.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtorrdqckw.html

K. JSON 与序列化
来源：http://dali.nanxinkj.top/Article/details/gtbptirsfe.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtoxbnsamw.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtwpanwxmn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gtjlommhrf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuebbquze.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtaqtlnnrk.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtsowctqve.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtkmobuluj.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gtjngofzja.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258.top/Article/details/gtijqrkeai.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gthghylofk.html

[K02] JSON 字符串转对象
来源：http://dali.hysaishi.cn/Article/details/gtjpgxewnc.html

Py:   json.loads(s)
来源：http://dali.jlsjyb.cn/Article/details/gtyjpsafmw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gtkswlekgu.html

JS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtvqafosma.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtzyzybfqf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pycfn.com/Article/details/gtlvfjnrrv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtdbnwukxz.html

Ruby: JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtxxzfpimq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gtmqehxrwv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ydzc1.top/Article/details/gtdduuhwnn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gtpvjjdvsk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtpooemaju.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwhvigqa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gtdihgxvbk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gtsdaksdda.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pengpengdd.cyou/Article/details/gtpyrsqmhf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gtedrmicrb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuetiantiany.cn/Article/details/gtwlfngwcg.html

[K04] 读取 JSON 文件
来源：http://dali.tianlin.xyz/Article/details/gtzbrldepx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsmadxzb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhcmwrab.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtljfauvoh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtpcdcrlhc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gtdeuzdwxf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtybjapxxo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnzaeoer.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gtzuapgedb.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gtswocnfcg.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdajxgwi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gtlykofgnk.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtsxbgcoux.html

TS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtqgrnwjgv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.havefunace.top/Article/details/gtbixnlzca.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhiwuduotai.top/Article/details/gtgniwwabl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtzqytptvj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyaizdac.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gtandixazg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gtgbkdwqkf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gtlkyoiago.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtmabwojbo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtkzwflsta.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gzhubu.top/Article/details/gtftbjptqv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtknyjtjun.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gttaseufqr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtopmthiah.html

[K07] 进制转换
来源：http://dali.cucudq.cn/Article/details/gtkgnrcmcf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtqbjlmlag.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenzaomai.com/Article/details/gtaglcicwi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtkibgwwsy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtsjwchfop.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtowlrnabe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dianchejie.cn/Article/details/gtgfjbuwpi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gtmrawgzcd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtfnzjgibv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gtqaidquul.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtmrtrnmgk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gtdlmthmvw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gtkemoptpn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gtrnlnzwdk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.smart0.xyz/Article/details/gtneqhhsvl.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gtvifxinwl.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gtgcilvoll.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gtkrcyxcij.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvhtzqzij.html

L. 网络请求
来源：http://dali.shuidangran.top/Article/details/gtvhdponnq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtsveialxa.html

[L01] 发送 GET 请求
来源：http://dali.dashuyun.cn/Article/details/gtzwtihuth.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.iojbl.cn/Article/details/gtbjrpdyme.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenlongwang.top/Article/details/gtqrgpfebx.html

JS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtfgdgntmv.html

TS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqbujhmw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.smart0.xyz/Article/details/gtqcvioiat.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwddtzfky.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cheryme.top/Article/details/gtrftatmfr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlwvgfgh.html

[L02] 发送 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gtsjlrddvh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtkpdvvbjr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.kuanghao11.cn/Article/details/gtalnewexg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtymhpxtmz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtlsdkntwf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gtuvemthji.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gtrnnvuoqk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenlongwang.top/Article/details/gtnvbvwbaf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gttycefttq.html

[L03] 设置自定义请求头
来源：http://dali.gaohongyu789.top/Article/details/gtpmsdxfzy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigfzy.top/Article/details/gtsprhmgao.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gthfqxvhax.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gtpsjztgau.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gtmlohekto.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gtjgypjlut.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gttjceerca.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yueranfly.top/Article/details/gtblrgshqc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtgsgegubu.html

[L04] 设置超时
来源：http://dali.pengpengdd.cyou/Article/details/gtkgwfmvly.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guannengcc.top/Article/details/gtutxviurn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gthlgyfqvj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtfyeihyxk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtgxqtbcbp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gtbmepnsst.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yvedp.cn/Article/details/gtxqwaadtv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yanxiufei.cn/Article/details/gtjzhccnkf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangdashe.top/Article/details/gtjvdtjmws.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gtwmbvfqdj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258888.top/Article/details/gtevrbzpjd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jlsjyb.cn/Article/details/gtsksqbjal.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtdaoweein.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gtobeltgpu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gtfgnrizql.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.smart0.xyz/Article/details/gtnpvttpzz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sufxvd.cn/Article/details/gtytwrfcqo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gthxoekulv.html

[L06] 解析响应为 JSON
来源：http://dali.smart0.xyz/Article/details/gtrtqivujy.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gtscvwdzew.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gtkivjszcc.html

JS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtbkxjhptp.html

TS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtnxeappai.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtblhtaobz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhiwuduotai.top/Article/details/gtvgwoywcy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gtridzuynb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cdnleiting.top/Article/details/gtddrciwuh.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtiubdylky.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gtwpmktcwz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gtuoksvdyj.html

JS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtbmcjeyts.html

TS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gtutjdkmeg.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gtuozsawta.html

Go:   resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gtuwbapcae.html

Ruby: resp.code.to_i
来源：http://dali.zhoulong.xyz/Article/details/gtgwgkpplh.html

C#:   (int)resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gthnnwlidx.html

[L08] 并发请求多个地址
来源：http://dali.316326.xyz/Article/details/gtqefxosev.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hfpthk.cn/Article/details/gtajjguvvl.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gtdkvthrxs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgzywxmi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtbknpxeow.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gtyhipkzev.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daxiang520.top/Article/details/gtsxzoxrft.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gtmjlkmkql.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sufxvd.cn/Article/details/gtkvsjfcdk.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtrcbgzykd.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gtdpfemgau.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmsyvebyq.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtlvuvqvuq.html

Py:   sys.argv[1:]
来源：http://dali.sysykeji.top/Article/details/gtdojvauni.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gtfocbnchi.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtotztkcaw.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtbzarwogb.html

Java: args 数组（main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtmkzbunnb.html

Go:   os.Args[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtcoqajymv.html

Ruby: ARGV
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvylxmwa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtqgsdfixv.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gtoerptlje.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gteultytox.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtcicvttlw.html

JS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gtxatcfzej.html

TS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gtwlietwdh.html

Java: System.getenv("HOME")
来源：http://dali.fzhhl.top/Article/details/gthwsglzow.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtgpiuwiqr.html

Ruby: ENV["HOME"]
来源：http://dali.daria6918.cn/Article/details/gtrdkflhjg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtbluyccjb.html

[M03] 执行外部命令
来源：http://dali.gzhubu.top/Article/details/gtjzwppwgv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gtwxbnfomu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cqqwz.cn/Article/details/gtyjobzeln.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gtaqsoryku.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gtlfeplerc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuxming.cn/Article/details/gthtcviayb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yangfankeji.com/Article/details/gtbxhapmys.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gaohongyu789.top/Article/details/gtjrmywhsk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jiagoushi.top/Article/details/gtetdowdeh.html

[M04] 获取当前工作目录
来源：http://dali.quarkkingdee.top/Article/details/gtmycshjxm.html

Py:   os.getcwd()
来源：http://dali.9152youxi.cn/Article/details/gthxztwrcn.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraorqdbe.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtmonfkqut.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtwyuoojtd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dashuyun.cn/Article/details/gtkyntrmas.html

Go:   os.Getwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtqnfdtjkk.html

Ruby: Dir.pwd
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrjqxloh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.316326.xyz/Article/details/gtnjhufbwl.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gteqnfbivh.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtssshejdb.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gtcdviaxbd.html

JS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtlabqezbi.html

TS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtpxvttmug.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gthxoankov.html

Go:   os.Exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtxocuahco.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtlehamxle.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xinyue.icu/Article/details/gtqkvnyvzv.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gtcmxtfpee.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gtxcdymgim.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigufen.top/Article/details/gtzwokigsm.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gtjkicldeb.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gtoijjpxrx.html

Java: System.err.println("err")
来源：http://dali.aibaodan.cn/Article/details/gtuastclrb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cdnleiting.top/Article/details/gttkmxqsfr.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gtbdubafxc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hfpthk.cn/Article/details/gtaurgzlcu.html

[M07] 判断是否为主入口
来源：http://dali.ehwqpu.com/Article/details/gtazqirfqc.html

Py:   if __name__ == "__main__":
来源：http://dali.redwolf501.top/Article/details/gtkwkfxbsh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gtvahdccow.html

JS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gtaogixreg.html

TS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtmxazlxjo.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gtukmqlpvy.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gtqmmzcklh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.snrcjt.cn/Article/details/gtctlxillp.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gtmyikcmnz.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gtizjwlcuz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.meibo888.top/Article/details/gtoejiuibh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gzhubu.top/Article/details/gtaqaajnhk.html

JS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gtibbccfir.html

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtwtrdkncx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nwbrower.top/Article/details/gttwbevioo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cheryme.top/Article/details/gtdfheenlf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gtwtwquklb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gtuplspyec.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqupbuzz.html

N. 数据结构与算法
来源：http://dali.jinqigfzy.top/Article/details/gtincxudno.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtihugpgvf.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gtzclzxlxo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtzjefnetx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtqiaypvli.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtddlnckbn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtteegfqmc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtksummluk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtujvctdxb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gtnrrlhwdd.html


<!-- 参考信息 -->