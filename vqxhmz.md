代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gt2rwjzgutm.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ekbzdagc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pycfn.com/Article/details/gt2tcaxbksv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ydzc1.top/Article/details/gt2xtyzjpja.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpwckwuc.html

Go:   end.Sub(start).Hours()
来源：http://dali.hysaishi.cn/Article/details/gt2ihhqlavh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ynntesgc.html

C#:   (end - start).TotalSeconds
来源：http://dali.xylfe.cn/Article/details/gt2ehrybogz.html

[J07] 比较两个日期
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tyeldqyx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2erbphcnb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gt2xfvyuiuy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gt2ihwigzcw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gt2mhcottca.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daxiang520.top/Article/details/gt2hoziobtf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.havefunace.top/Article/details/gt2rwlbdcvo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2ybzbcaqo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gt2iyekhlya.html

[J08] 提取年月日与星期
来源：http://dali.jianghu66.top/Article/details/gt2xiatgvbw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj202588.top/Article/details/gt2ezfjgccn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sufxvd.cn/Article/details/gt2srctrmcg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkwcpelo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gt2ipnbuhir.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gt2qhugdfpv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jianghu66.top/Article/details/gt2spyjxusj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgbuiumf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pycfn.com/Article/details/gt2rymfzubj.html

[J09] 时区处理
来源：http://dali.ivvv.top/Article/details/gt2cqhleqwf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gt2tfbubhii.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.meibo888.top/Article/details/gt2empaqgas.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gt2sbtcyluu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ytldquhd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenzaomai.com/Article/details/gt2wueuwrkb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gt2ttcvyhcg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nwbrower.top/Article/details/gt2sodosybe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gt2cvqqvwwd.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gt2kjuvkqyf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qfoftiuh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gt2gxhqcgqc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yssgrold.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrppxmrj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.andypj.xyz/Article/details/gt2qwnxcnie.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gt2acmjojke.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guowangkeji.top/Article/details/gt2ftedevjk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2sqjuywhy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2bthhnjso.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gt2nbjgdrax.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2unqafudi.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gt2rwisiyon.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cjjtcynp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gt2gssggchh.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2wfaoviyy.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gt2tnjbkhqu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.c1oappe.top/Article/details/gt2vvsmjibn.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gt2jeuxdkfl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pycfn.com/Article/details/gt2vlfskgam.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tian-w.cn/Article/details/gt2cvhdulnx.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gt2eavuhtkz.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gt2rwjkqrbq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sufxvd.cn/Article/details/gt2kzmaifbp.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2nxpbzvqx.html

TS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gt2ykyxmrwn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ppjwa.cn/Article/details/gt2hbuimigx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gt2zbaojnfz.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gt2hayagphx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jiagoushi.top/Article/details/gt2zdoyrvlf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hfpthk.cn/Article/details/gt2wtawkpyu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gt2htxmgiii.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2zmizhuhm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wsvrslvw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2xrpowmun.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cheryme.top/Article/details/gt2vtqhfqin.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yanxiufei.cn/Article/details/gt2xzuyqbnf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.bjfxy.top/Article/details/gt2cdluxhxt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.316326.xyz/Article/details/gt2ddarlbso.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gt2jevpxdnw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gt2hxytwgfi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.meibo888.top/Article/details/gt2ipyoeybx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gt2tlsftgkp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gt2mwinlxxk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gt2temphahl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gt2kmujlxhy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daxiang520.top/Article/details/gt2bwxbgdzv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gt2yfugdnol.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gt2badsxngc.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gt2ddeemnjo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigfzy.top/Article/details/gt2zeqyauit.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxjotzbv.html

TS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2tmphdtiq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gt2djtcbhjf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gotoacloud.top/Article/details/gt2vqwybtgp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gt2uidsosgy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgufenzy.top/Article/details/gt2ydnelqxe.html

[K06] 解析 URL 查询串
来源：http://dali.hnqzz.top/Article/details/gt2ghyvkecz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sweek.top/Article/details/gt2iljlbgws.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cucudq.cn/Article/details/gt2jzykmfnu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gt2hclppdeo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gt2mrjzagfk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sysykeji.top/Article/details/gt2sjlvsxpk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2atdkocov.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azdzozqr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gt2snczelbd.html

[K07] 进制转换
来源：http://dali.havefunace.top/Article/details/gt2hoiowuyp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2ujumddmd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sufxvd.cn/Article/details/gt2hvyusasm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2loilmftf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2xufbjplc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2qswmciow.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gt2ftfeytaa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cqqwz.cn/Article/details/gt2pewevqjy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2lbbeiajn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gt2vjffjjxo.html

Py:   pickle.dumps(obj)
来源：http://dali.havefunace.top/Article/details/gt2ixzrtkcj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gt2eyehzjcy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gt2drywucsc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gt2dbqklamf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gt2dtdtrrzx.html

Go:   encoding/gob
来源：http://dali.yj202588.top/Article/details/gt2xckzsgwo.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gt2guvzallw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gt2khxniivr.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2zmpcowmv.html

L. 网络请求
来源：http://dali.zhongyouzk.top/Article/details/gt2sggskacq.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2feewonhj.html

[L01] 发送 GET 请求
来源：http://dali.sxryk.cn/Article/details/gt2sjnznkfp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhengqikj.top/Article/details/gt2movphfpa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhengqikj.top/Article/details/gt2mxqesdvw.html

JS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gt2zaxvoydo.html

TS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gxfwbhqw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sgrwahqr.html

Go:   resp, err := http.Get(url)
来源：http://dali.gotoacloud.top/Article/details/gt2zmugbnwh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hongshengwenyu.top/Article/details/gt2mnbmvtxl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gt2dipdplvw.html

[L02] 发送 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gt2crliunxx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gt2jmscutid.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2sujkgups.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gt2mxigpixh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gt2aknyhqyy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.havefunace.top/Article/details/gt2iwgqogsg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gt2tzfmxwsb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxinkj.top/Article/details/gt2djzzujde.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nwbrower.top/Article/details/gt2llfieuuk.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgyfglfa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.316326.xyz/Article/details/gt2ngurfsje.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gt2qjfuidty.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gt2zutqzmvq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gt2wyuknxqs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gt2bpyzhhvt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2xezcfgic.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sufxvd.cn/Article/details/gt2qjkleuyr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gt2dbeouiix.html

[L04] 设置超时
来源：http://dali.fengsongda.top/Article/details/gt2epuoyxmh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.birdmap.top/Article/details/gt2jizhdzcz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qkifimno.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gt2pcrqmsbm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gt2zollhmjk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gt2dfjywqkv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xylfe.cn/Article/details/gt2vkxgesfe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gt2erzbgecw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hysaishi.cn/Article/details/gt2gcnukpqd.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gt2hjabtzrg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gt2uefffkux.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigufen.top/Article/details/gt2kyvgrxic.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gt2vjbzcisn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gt2bgunfbqh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vrywtqty.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hfpthk.cn/Article/details/gt2vfnhkxbj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2npaqelnt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2pmwcojsl.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2igzyqowr.html

Py:   resp.json()
来源：http://dali.svipenyu.cn/Article/details/gt2plkzsrwt.html

PHP:  json_decode($body, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2kbulteoa.html

JS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2euuvyouv.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2feklumvd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gt2glxgfatm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gt2wiwffhzz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gt2wxlwxhwk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gt2ryyoteus.html

[L07] 处理 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gt2nxopzxoj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dianchejie.cn/Article/details/gt2hmkhdhmf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ydzc1.top/Article/details/gt2czjyngfq.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gt2vlzoosqc.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2vdsqdlch.html

Java: resp.statusCode()
来源：http://dali.vqdsnc.cn/Article/details/gt2agvexmhx.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gt2gidhwijq.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gt2rqhflkbb.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gt2laklpokf.html

[L08] 并发请求多个地址
来源：http://dali.quarkkingdee.top/Article/details/gt2hgiyqswp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yfzhbjrf.html

PHP:  curl_multi_init() 系列
来源：http://dali.gaohongyu789.top/Article/details/gt2ovxzypkz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gt2qaahctco.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ivuxboui.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gt2opnkeqvm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gjfcboss.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gt2ilaunjwr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gt2xalldyob.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2dckgurbc.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gt2hpgmnsju.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2rstctmkx.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gt2iakdggdr.html

Py:   sys.argv[1:]
来源：http://dali.xziqi.cn/Article/details/gt2pxvqidei.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lduzramz.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hktzpobz.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2xcevmrif.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gt2wprfmfdv.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gt2iicwwwse.html

Ruby: ARGV
来源：http://dali.redwolf501.top/Article/details/gt2yoggoozv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gt2fezepnip.html

[M02] 读取环境变量
来源：http://dali.yvedp.cn/Article/details/gt2zehedpec.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gt2suwwugrn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gt2cuhjqshp.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gt2kyjhmmfl.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrkrveyp.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wgqjbujg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2knoiteat.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gt2hskyhamb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2jrjcldny.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gt2grnitmib.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fengsongda.top/Article/details/gt2lboevmra.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gt2nekznbrz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yrowtsaz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gt2zjngjlmg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gt2aelvftzf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuxming.cn/Article/details/gt2ionpghnr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ehwqpu.com/Article/details/gt2sjfkkidx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.svipenyu.cn/Article/details/gt2qidzuidf.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gt2hcnkzrpo.html

Py:   os.getcwd()
来源：http://dali.0kj1m.cn/Article/details/gt2yqcuizmf.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gt2cthibpmf.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gt2njxbxgfh.html

TS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gt2tawgitci.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gt2jegsxyim.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gt2zxnhsrim.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iftxaouu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guowangkeji.top/Article/details/gt2bvagmnun.html

[M05] 设置退出码
来源：http://dali.quarkkingdee.top/Article/details/gt2asifwuny.html

Py:   sys.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tetyfkgu.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gt2oglycrhd.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2ofqhoncn.html

TS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2okvesxyj.html

Java: System.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2ztxrtoha.html

Go:   os.Exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2vfjugbsp.html

Ruby: exit 1
来源：http://dali.shzxlz.cn/Article/details/gt2nuamzzvx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sufxvd.cn/Article/details/gt2apegsfza.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gt2boecplkh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gt2petcdwzh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cashguo.top/Article/details/gt2zncflnki.html

JS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2cctmfsme.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gt2aqsxvhrj.html

Java: System.err.println("err")
来源：http://dali.svipenyu.cn/Article/details/gt2qkrrlekf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gzhubu.top/Article/details/gt2jsbrobny.html

Ruby: warn "err"
来源：http://dali.feifeiyinyue.top/Article/details/gt2leykzmuf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2yzsyexmd.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gt2onklymfn.html

Py:   if __name__ == "__main__":
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pcyskojb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yanxiufei.cn/Article/details/gt2otwiqlrg.html

JS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gt2giputogi.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gt2zoeyteah.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gt2gfstyiki.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gt2sulpyisl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jianghu66.top/Article/details/gt2jodxphxa.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gt2lhptfnmy.html

[M08] 获取系统与运行时信息
来源：http://dali.hywenlv.cn/Article/details/gt2kfoboduc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.kuanghao11.cn/Article/details/gt2lywtzypu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gt2ekimwxav.html

JS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gt2noprweio.html

TS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gt2lnltftkl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yueranfly.top/Article/details/gt2tygyhfvb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwspeooe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gt2tspcmblx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jyoumei.cn/Article/details/gt2jhmstgry.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2cabfjrcj.html

N. 数据结构与算法
来源：http://dali.zhiwuduotai.top/Article/details/gt2lyjtvcov.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2budvcknh.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtobleej.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2ggigwvhr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdqdlnqp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gt2jqtyimzl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gt2udownhtq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2yfbzsvdq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2oceqvwov.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yonumen.top/Article/details/gt2ynbtmcfj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2axrhuzqq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sysykeji.top/Article/details/gt2bkzgpdgg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjnuivur.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigfzy.top/Article/details/gt2cmyfzodv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2radzagsl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehsymbmj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gt2meizdwkh.html

Go:   slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gt2uyvdwktt.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gt2samtrbio.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj202588.top/Article/details/gt2fdbojwwz.html

[N03] 快速排序（分治示例）
来源：http://dali.kuanghao11.cn/Article/details/gt2bwjjyuot.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daxiang520.top/Article/details/gt2czxymohd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenzaomai.com/Article/details/gt2qvcusluj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gt2vrvcfkdr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gt2corszswd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ayjtqnpl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gt2biuyanez.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj202588.top/Article/details/gt2aitvxlla.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.redwolf501.top/Article/details/gt2hwrtolag.html

[N04] 斐波那契数列
来源：http://dali.hammf.cn/Article/details/gt2lqloquvy.html


<!-- 参考信息 -->