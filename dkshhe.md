代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gttjhckvzl.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhixingplan.top/Article/details/gthceqoaha.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jyoumei.cn/Article/details/gtjsrdxzgk.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gtbzfabcxk.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gtybrydaif.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtnizoordz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.meibo888.top/Article/details/gtitabdqqi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gtjqizpnpu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gtdbfpdusf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.316326.xyz/Article/details/gtqdvhroue.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ydzc1.top/Article/details/gtzbrgynaj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtcaykmnhh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtskvmqwiw.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gtgcoufdlh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gtxcrhnksq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.meibo888.top/Article/details/gtpdmcosst.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gotoacloud.top/Article/details/gtprkhnzjt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gtbzeakfhq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gtjkgepzuz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gtacshefug.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hfpthk.cn/Article/details/gtijenvuew.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigufen.top/Article/details/gtlgjymhwo.html

[J09] 时区处理
来源：http://dali.quarkkingdee.top/Article/details/gtqhlknjlp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sxryk.cn/Article/details/gtgddjaujl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnxiangtu.top/Article/details/gtxnwfwzsa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtdljmqtmz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gthiaajdrn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhiwuduotai.top/Article/details/gtieaiszzt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhixingplan.top/Article/details/gtmpufcjei.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gogol.net.cn/Article/details/gtptbtwbek.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gtjkqcflgq.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gtjlwwlkqx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yonumen.top/Article/details/gthhexbhep.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258888.top/Article/details/gthdkkibko.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gtyjmmcpdn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gtvkgfdkwd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gtiykgnwmp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gtgtzycmzy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258888.top/Article/details/gtwylpfcji.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.redwolf501.top/Article/details/gtszudqiqr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtdhrylhpv.html

K. JSON 与序列化
来源：http://dali.tianlin.xyz/Article/details/gteuvkqpwk.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtweihjowu.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gtkvzxgczg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdczpzaas.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtrjdhtdwe.html

JS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtjkgtmicz.html

TS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gtqljrwypv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tanke756.top/Article/details/gtzxqgctsz.html

Go:   json.Marshal(obj)
来源：http://dali.havefunace.top/Article/details/gtaenoozmb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yvedp.cn/Article/details/gtskpdpfgi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yangfankeji.com/Article/details/gtjkpogvgp.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gtbcmplsix.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gtaavqgoui.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.smart0.xyz/Article/details/gtlbffadyf.html

JS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtloxqjjrv.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtgifvfcez.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guannengcc.top/Article/details/gtmhcnrcug.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtiontxzvf.html

Ruby: JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtwwscdvau.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yueranfly.top/Article/details/gtskcronru.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gttltsybmz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtntjwlqza.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gtvocdhtnl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtcannfygt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gtoutlljyq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gtwqtcshpy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hammf.cn/Article/details/gtbbuzrkgo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtoldfixyh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ivvv.top/Article/details/gtbkfawzhc.html

[K04] 读取 JSON 文件
来源：http://dali.yonumen.top/Article/details/gtxrklxqzu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gtxdzzkotr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nwbrower.top/Article/details/gtfpjnmzne.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtyugiupti.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtnbsnjrdm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtrttelque.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtbnxaiuep.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guannengcc.top/Article/details/gtjgjcglgf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gtrwuhvixh.html

[K05] 深拷贝对象
来源：http://dali.sweek.top/Article/details/gtdwclvcjk.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gtzvhrsacv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ehwqpu.com/Article/details/gtmwukcywi.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gttvgixhpe.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gtcqntvtun.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shangyingyoupin.top/Article/details/gtckcwijuj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tianlin.xyz/Article/details/gtbhzixeuw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pycfn.com/Article/details/gtkifqmqgu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xylfe.cn/Article/details/gtojzgsmxz.html

[K06] 解析 URL 查询串
来源：http://dali.jianghu66.top/Article/details/gtjzalsuic.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtqndhvtvb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nwbrower.top/Article/details/gtljlskicg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtrlkpxgds.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtkuacfcpx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gtdcbaixnh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtqtilkcws.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtiqlkxdck.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gtqubtmytb.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gtaudzxtpd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtpihgjeid.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gtltmohztg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtpunpkhib.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtfhueaerq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtubcoikxu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gtmtkcxjzu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gtxyrrbjqi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtcopdwxcs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gtdftskbrv.html

Py:   pickle.dumps(obj)
来源：http://dali.yvedp.cn/Article/details/gtcamnkjub.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zdqjudy.top/Article/details/gtgbkkzanb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtdvsaqace.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtipdhrdot.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gtygpbttqc.html

Go:   encoding/gob
来源：http://dali.tian-w.cn/Article/details/gtlialpyqo.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gtmasmmlwx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtnpmsmdos.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtrxqirtzd.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gtaokyrues.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gttjumjkjr.html

[L01] 发送 GET 请求
来源：http://dali.quarkkingdee.top/Article/details/gtqukwjtgn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnorkiqj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hongshengwenyu.top/Article/details/gtyqlwywkj.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gteszusjyd.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpopgghlr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.bjfxy.top/Article/details/gtehrjivfz.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gtxsuagtjm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenzaomai.com/Article/details/gthtvauqef.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gtodhzsyre.html

[L02] 发送 POST JSON
来源：http://dali.zycfv.cn/Article/details/gthmcazzxl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gtvbdzvuod.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zycfv.cn/Article/details/gtxfdcvdjq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtzjrsgbss.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gtrigzjgpi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xylfe.cn/Article/details/gtwthpaogb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gtevuluesv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gtnhpaieej.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gtfrnaqpyh.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gtchkcnzfu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gtvnmlpzbz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tian-w.cn/Article/details/gtuniqhdcb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtzrmbvrbg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtvznoehgn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xziqi.cn/Article/details/gtcltywrac.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtdyhtqwgb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hysaishi.cn/Article/details/gtwmeqswzh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gtcxabxpvu.html

[L04] 设置超时
来源：http://dali.hywenlv.cn/Article/details/gtwlofhxpc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.bjfxy.top/Article/details/gtpxtizkxp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gtceeedwsn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gtfnzkhaqb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gtmzkvdyvt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtumukqkea.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gtxbifsiom.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gtbssrsvcf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gtkbiteglh.html

[L05] 上传文件（multipart）
来源：http://dali.haohaochexian.top/Article/details/gtwwqaqisc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jyoumei.cn/Article/details/gtvpdecbzd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jiagoushi.top/Article/details/gthdtyhmzy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtlvzolnth.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtyfjaumml.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuxming.cn/Article/details/gtbbvgiczt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cheryme.top/Article/details/gtebtdpesn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.quarkkingdee.top/Article/details/gteegyhywk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtrdbweapf.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gtzlnchnno.html

Py:   resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtaujfetln.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gtklmncfri.html

JS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtzocihywk.html

TS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtmtmjeoxn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gtbbalvpcn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gtkkpfscav.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guannengcc.top/Article/details/gtqrtceyxp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtorlozrlh.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtfwxgrfkv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gtbsxqsegk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.kuanghao11.cn/Article/details/gtlfeekrrw.html

JS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtutjtibee.html

TS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gthteozsrq.html

Java: resp.statusCode()
来源：http://dali.shuidangran.top/Article/details/gtawrahbee.html

Go:   resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtuoiethxk.html

Ruby: resp.code.to_i
来源：http://dali.svipenyu.cn/Article/details/gteluxcjha.html

C#:   (int)resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtlstoiyfa.html

[L08] 并发请求多个地址
来源：http://dali.daria6918.cn/Article/details/gtjupwffku.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gtssdsnifi.html

PHP:  curl_multi_init() 系列
来源：http://dali.9152youxi.cn/Article/details/gtooxxrtjk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtrdmuimyv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtkubjttag.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gtkbwmufyc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gaohongyu789.top/Article/details/gtoqgcekan.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gthzcivqyt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gtsbfsmuwb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gticdkzlbo.html

M. 命令行 / 进程 / 环境
来源：http://dali.sweek.top/Article/details/gtwzeubaao.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtbeansosw.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtlxgqwwzd.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtyxaknzil.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gtbveahbfa.html

JS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfagmodn.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtmjzmncvg.html

Java: args 数组（main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gtewedrror.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptvllfvw.html

Ruby: ARGV
来源：http://dali.xuanzx.com/Article/details/gtrrwlvhyl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtwdwlbrji.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gtarmwmgap.html

Py:   os.environ.get("HOME")
来源：http://dali.havefunace.top/Article/details/gtzjyegxpm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsfaggfi.html

JS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtwrlcfkih.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtuulsllzp.html

Java: System.getenv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtcdzbcbpe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtxavjcqwn.html

Ruby: ENV["HOME"]
来源：http://dali.tian-w.cn/Article/details/gtucimhjgr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nwbrower.top/Article/details/gtbudgxile.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gtzbdopouq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gttjnziryg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gtsbjupnzf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtfacaeamq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtvnbkpkei.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangdashe.top/Article/details/gtntisdcxe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj202588.top/Article/details/gtrryntnyq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gtjkcejpuj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnqzz.top/Article/details/gttvmpfbgw.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gtxqjcpbri.html

Py:   os.getcwd()
来源：http://dali.vqdsnc.cn/Article/details/gtgwlebyrm.html

PHP:  getcwd();
来源：http://dali.wangdashe.top/Article/details/gtmtyctdke.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtnbjrmmpg.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtilsumqmk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gtqhjigggb.html

Go:   os.Getwd()
来源：http://dali.xziqi.cn/Article/details/gttttaojyf.html

Ruby: Dir.pwd
来源：http://dali.cucudq.cn/Article/details/gtgfzrlrsp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxgokdsd.html

[M05] 设置退出码
来源：http://dali.yj20258888.top/Article/details/gtvrblfdtn.html

Py:   sys.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtrocnwget.html

PHP:  exit(1);
来源：http://dali.guannengcc.top/Article/details/gtastgqhza.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gttffyhtzx.html

TS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtkilpsxlf.html

Java: System.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtzlcfmkll.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gtpkiwooot.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gtodlrlbop.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtqrqxvrgo.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gtbrepbaei.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gtweavjfns.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenjidiqi.icu/Article/details/gtcvindmmd.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gttqwrxvrn.html

TS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gtpqskdkjj.html

Java: System.err.println("err")
来源：http://dali.cheryme.top/Article/details/gtbdewengz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jianghu66.top/Article/details/gtjshtgciv.html

Ruby: warn "err"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjyaboow.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrgtndgg.html

[M07] 判断是否为主入口
来源：http://dali.guannengcc.top/Article/details/gtlpgelhqp.html

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpxncmpr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cashguo.top/Article/details/gtaehvqohu.html

JS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwjpfkqj.html

TS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtxajzetzp.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gtixzwebgv.html

Go:   func main()
来源：http://dali.shangyingyoupin.top/Article/details/gtvgyqxyqo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtraudoarg.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gtjfvhpjas.html

[M08] 获取系统与运行时信息
来源：http://dali.zycfv.cn/Article/details/gtcsqpevym.html

Py:   platform.system();  platform.python_version()
来源：http://dali.0kj1m.cn/Article/details/gtiyaqjrgu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gtvqnkqndq.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtnobevwjf.html

TS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gtpftwcoad.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.quarkkingdee.top/Article/details/gtedictfru.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangshuangyany.cn/Article/details/gtlvwjcszt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gtebvlksrg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gtpyyabtgo.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjkcoefkd.html

N. 数据结构与算法
来源：http://dali.gaohongyu789.top/Article/details/gtrurpswpu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtwxicprzu.html

[N01] 二分查找（有序数组）
来源：http://dali.aibaodan.cn/Article/details/gtikvaawtp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtgjpmlyoc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pycfn.com/Article/details/gtbafosjnc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtnyaemtqb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtukczvsvl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtefrggbhj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtwwjvzgfe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigufen.top/Article/details/gtyzwagfze.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gthktbciho.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yonumen.top/Article/details/gtzwjcxqcn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gtuzssikrr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gtoswtdrje.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtposxhnbv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbdyjcfk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gtuoitphtd.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtjeflifia.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtzfllpgqh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.smart0.xyz/Article/details/gtlfwjputl.html

[N03] 快速排序（分治示例）
来源：http://dali.yuanzhike.top/Article/details/gtokwqfvmf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cdnleiting.top/Article/details/gtqniasluk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sxryk.cn/Article/details/gtqbwyjcqm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtbmwhhxxs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gtrgzgaelh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtvmnanfzb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gogol.net.cn/Article/details/gtnqfsmzrm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shuidangran.top/Article/details/gtcozdnuak.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuanzhike.top/Article/details/gtlwqrbxhy.html

[N04] 斐波那契数列
来源：http://dali.zycfv.cn/Article/details/gtghsgneyo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gthjcexaab.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtvvpckdfv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtwyevunua.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtdiqnoifo.html


<!-- 参考信息 -->