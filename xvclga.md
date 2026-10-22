代发 wailian999

[J07] 比较两个日期
来源：http://dali.gaohongyu789.top/Article/details/gt2csgfkazj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2ichuuuha.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gt2hkvsjgal.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gt2yfjmpvph.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gt2ukilsukf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gt2duuhoesk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2eugsqfuk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2mqxjviod.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2gdpmlisc.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gt2hmlkschi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuxming.cn/Article/details/gt2etembedl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hysaishi.cn/Article/details/gt2xvmhgaht.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gt2etqntnwk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nchurhtr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.havefunace.top/Article/details/gt2wpdvtjmu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gt2zwcbyymn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gt2qmcalozu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pycfn.com/Article/details/gt2bjipbyit.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gt2jeagjbcc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gt2zpmtqiqg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gt2oamcljwi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gt2wbfqmbkq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gbapeuyy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hammf.cn/Article/details/gt2kledluvr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nwbrower.top/Article/details/gt2ewcvwgmx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sweek.top/Article/details/gt2gzkqtwku.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gt2dfwodtwm.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gt2gzrpyzuf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gt2vcbnsrtt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gt2upzpvaxx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2txltixkf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2isonaqdn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenzaomai.com/Article/details/gt2qsrwsdqr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gaohongyu789.top/Article/details/gt2uqnvvssa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfbmfcrx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gt2dbpdjyrq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2dqrnjsnn.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gt2vrbnnbaw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ljsbuozi.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gt2qnfmiryz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2tyvcjksg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gt2wihmscjp.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckvghkja.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2lolhndis.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gt2rhklshhe.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gt2tsckoipw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gt2etapbffb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2vuzrgdqc.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigfzy.top/Article/details/gt2kpnqsdsp.html

Py:   json.loads(s)
来源：http://dali.0kj1m.cn/Article/details/gt2algdshlj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yongpay.top/Article/details/gt2vhtdbpgy.html

JS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lhcvydli.html

TS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gt2vahfocyk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gt2gpcmecct.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gt2kowbcqlw.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gt2rwqvtucp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gt2jduzizls.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gt2vjzblglv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gt2bhqpiyym.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gt2rrftmcyj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2rpcnmbtm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gt2hmivmjfp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ybcxt.top/Article/details/gt2lkjmojzl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gt2xexgrlud.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gt2gvadofsb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gt2hcvtvhwy.html

[K04] 读取 JSON 文件
来源：http://dali.gzhubu.top/Article/details/gt2rveacuhz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.redwolf501.top/Article/details/gt2viijxceo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhongyouzk.top/Article/details/gt2bmcpgaon.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gt2qbxahxtx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gt2iemrpluc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2hmitslwv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oozolukm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hammf.cn/Article/details/gt2frrogyci.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yueranfly.top/Article/details/gt2nyitufnu.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gt2zxufxkfk.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyyuods.html

PHP:  unserialize(serialize($obj));
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwipeein.html

JS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gt2nydpfhzh.html

TS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2pkwhlpko.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daxiang520.top/Article/details/gt2sfvuxcza.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2aimlxmrd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hysaishi.cn/Article/details/gt2bptspzec.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gt2rhhewbik.html

[K06] 解析 URL 查询串
来源：http://dali.zycfv.cn/Article/details/gt2aqjizdyb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gt2psxhdjgn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fengsongda.top/Article/details/gt2lufvqque.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2agakvaol.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gt2hmzdzucw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gt2hvrskxrb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gt2gdjiqwvw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gt2ylvfkkmt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gt2qivcecpz.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gt2tqoarjcl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffsxdbpx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guowangkeji.top/Article/details/gt2jguzariu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2kfcbdljt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2xjwbjkly.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2csvaasfk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gt2dvcvishj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gt2ecqwhqsr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2wbjvuytb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gaohongyu789.top/Article/details/gt2sqharhka.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gt2ndkbttxi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gt2vjlupnue.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gt2izbhptme.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gt2tjwyjspi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.feifeiyinyue.top/Article/details/gt2nvofqqmv.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pomjixzl.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gt2ahdfiaxm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gt2buleekne.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2gxnjlpne.html

L. 网络请求
来源：http://dali.aizwys.cn/Article/details/gt2swydzefn.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2gmheiupo.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gt2nzvqzhen.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aizwys.cn/Article/details/gt2vuxqenjp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yanxiufei.cn/Article/details/gt2xqlxlisd.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gt2wgiqulus.html

TS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gt2kjtlzzun.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnxiangtu.top/Article/details/gt2beqamesp.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vxgkoxbz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shzxlz.cn/Article/details/gt2egbkdcre.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gt2bfjnkvrb.html

[L02] 发送 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gt2dbqlpvdn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gt2newgndul.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fzhhl.top/Article/details/gt2skirhaoc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gt2twwznzgs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gt2orkasjwr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.smart0.xyz/Article/details/gt2lbrjnacg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hongshengwenyu.top/Article/details/gt2vheklzbk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gt2tpzkrqwh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hywenlv.cn/Article/details/gt2sdunhyoz.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gt2vlhgmzmk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258888.top/Article/details/gt2boxvdncg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bqovqstt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gt2fdqpqfbq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gt2zkjapeqz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahebyqyq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gt2tpmvflbg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hammf.cn/Article/details/gt2nmahufjr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gt2cfktssvr.html

[L04] 设置超时
来源：http://dali.wangdashe.top/Article/details/gt2sexpvrst.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhixingplan.top/Article/details/gt2qxhbtzhk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gt2ucsjxkoy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gt2kjlqqbak.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gt2oxkwsoah.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gt2ipylogky.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gt2ejzpireo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gt2abwhyjxq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuxming.cn/Article/details/gt2qsiuords.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gt2szioouvp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aizwys.cn/Article/details/gt2bksrrkpt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gt2cyojfccg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gt2otxvbedp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gt2kfikvndm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gt2kupjwyvi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.smart0.xyz/Article/details/gt2ifdfcnvv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hfpthk.cn/Article/details/gt2zgoksfoc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2krkmvbay.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gt2azhshxuf.html

Py:   resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2dskfeqwz.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gt2qfpqbnzf.html

JS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gt2crzmzqbp.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxoyftrg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2kxuwhlyv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gt2nwpeyemr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gaohongyu789.top/Article/details/gt2muxmtgdm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gt2eiumjrvi.html

[L07] 处理 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tsxrnxbs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgsjteye.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gt2hvlgpvxa.html

JS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uohjfflx.html

TS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gt2uphxcluq.html

Java: resp.statusCode()
来源：http://dali.jianghu66.top/Article/details/gt2euzprxgg.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gt2ybivgfmn.html

Ruby: resp.code.to_i
来源：http://dali.guowangkeji.top/Article/details/gt2mjdguzva.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gt2igwusbea.html

[L08] 并发请求多个地址
来源：http://dali.yanxiufei.cn/Article/details/gt2pcgzwdge.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hammf.cn/Article/details/gt2xvoodhwd.html

PHP:  curl_multi_init() 系列
来源：http://dali.yangfankeji.com/Article/details/gt2iudksyih.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gt2wjypyhhs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2axwhdbrb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.bjfxy.top/Article/details/gt2aluaevzp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenlongwang.top/Article/details/gt2bomwhits.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gt2qyhbyvzv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sweek.top/Article/details/gt2pmczzkdb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2qgayzqkw.html

M. 命令行 / 进程 / 环境
来源：http://dali.dianchejie.cn/Article/details/gt2tkhzfjce.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2euwkpkat.html

[M01] 读取命令行参数
来源：http://dali.yonumen.top/Article/details/gt2milcuues.html

Py:   sys.argv[1:]
来源：http://dali.tanke756.top/Article/details/gt2fcnwgtfn.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258.top/Article/details/gt2tntzxzhs.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mpudkrqy.html

TS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncgmaroe.html

Java: args 数组（main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gt2ietvzosd.html

Go:   os.Args[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2jqxgclqn.html

Ruby: ARGV
来源：http://dali.cashguo.top/Article/details/gt2cuqgptow.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gt2xfihmqgy.html

[M02] 读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2yotepfio.html

Py:   os.environ.get("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wlxenxxi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gt2nscumngw.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gt2auvvwnlj.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gt2onzbsnmz.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkxzlsnm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2vryayzmj.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gt2etjbkeex.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2qiabtbsz.html

[M03] 执行外部命令
来源：http://dali.316326.xyz/Article/details/gt2kcxhvwgr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gt2nwloceed.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhengqikj.top/Article/details/gt2zvlupfst.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gt2jfffghlf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2yhjhrzlu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gzhubu.top/Article/details/gt2nntyborx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gt2ieuqjgxw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.vqdsnc.cn/Article/details/gt2qhdpxrdx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gpsfslbs.html

[M04] 获取当前工作目录
来源：http://dali.smart0.xyz/Article/details/gt2nvruqqzu.html

Py:   os.getcwd()
来源：http://dali.birdmap.top/Article/details/gt2gxegplyo.html

PHP:  getcwd();
来源：http://dali.ehwqpu.com/Article/details/gt2xhbkutvd.html

JS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfmnrtjd.html

TS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gt2sdqtrgqb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gt2glldexig.html

Go:   os.Getwd()
来源：http://dali.yj202588.top/Article/details/gt2dbmwkvnj.html

Ruby: Dir.pwd
来源：http://dali.snrcjt.cn/Article/details/gt2myamwhbt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shzxlz.cn/Article/details/gt2vinqzkxf.html

[M05] 设置退出码
来源：http://dali.ydzc1.top/Article/details/gt2ewedjohh.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2mmmfmhif.html

PHP:  exit(1);
来源：http://dali.jiagoushi.top/Article/details/gt2hwkfbrum.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2zkswtswb.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2ojfcpcqn.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2qlveaopw.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2yhbobtai.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aditxugn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.smart0.xyz/Article/details/gt2wmxmsate.html

[M06] 向标准错误输出
来源：http://dali.sweek.top/Article/details/gt2yfctltgw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gt2efchfyjk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.smart0.xyz/Article/details/gt2hwdxuymt.html

JS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gt2btkqykkr.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahctnrfz.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxzupgh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gt2xyacegwb.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gt2rmijeziu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gt2qmxxhrbe.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gt2tquvblqh.html

Py:   if __name__ == "__main__":
来源：http://dali.xylfe.cn/Article/details/gt2lkbjxfoc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258.top/Article/details/gt2lsdiibni.html

JS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gt2hqcdbrre.html

TS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gt2ugspkiwt.html

Java: public static void main(String[] args)
来源：http://dali.ybcxt.top/Article/details/gt2pajwcvcw.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gt2gabbotea.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfwbjnnw.html

C#:   static void Main(string[] args)
来源：http://dali.sxryk.cn/Article/details/gt2zjgvwqqg.html

[M08] 获取系统与运行时信息
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntfjilsm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.c1oappe.top/Article/details/gt2pjdyoyve.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gt2pzqekdoh.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gt2ntvevpcl.html

TS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gt2sfeifasv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.andypj.xyz/Article/details/gt2asqyqbol.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fzhhl.top/Article/details/gt2buhxirwa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtlrnthi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zmnmrlcy.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2edtlwuuv.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gt2jsrybxcu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdjseaik.html

[N01] 二分查找（有序数组）
来源：http://dali.yvedp.cn/Article/details/gt2ybwdmjso.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2qptffuow.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sufxvd.cn/Article/details/gt2byokplir.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gt2odrgmxve.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gt2hkkclpny.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2dyfyqzab.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2ifkfflnx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gt2xaymlvcc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2mudpqulk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cheryme.top/Article/details/gt2nxnroakq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gt2iabrumcs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2jstpncgk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gt2lewkrqer.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzgdvsze.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gzhubu.top/Article/details/gt2jredbrfg.html

Go:   slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gt2tpdnnnii.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gt2jolhjqes.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258.top/Article/details/gt2wcphxmkb.html

[N03] 快速排序（分治示例）
来源：http://dali.c1oappe.top/Article/details/gt2tdqmkrqr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gt2nvjowyyu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cheryme.top/Article/details/gt2wjddecbe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gt2lbfipfzl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gt2szrkmutu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gt2skmongta.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhongyouzk.top/Article/details/gt2zdwndejd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gotoacloud.top/Article/details/gt2toeexymt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.quarkkingdee.top/Article/details/gt2kiymjphh.html

[N04] 斐波那契数列
来源：http://dali.tianlin.xyz/Article/details/gt2ueomjeyb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gt2cxduibvi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2yfejsili.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gt2nlosolvq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2eaxlyexr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gt2onsyzdbi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.smart0.xyz/Article/details/gt2xvhtgmzc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gt2xglonbgn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2leqgwgmi.html


<!-- 参考信息 -->