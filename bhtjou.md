代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2qsagwolg.html

[J08] 提取年月日与星期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hroofkrj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gt2vhntkhtm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tian-w.cn/Article/details/gt2scythnau.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jczfwvch.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gt2tafntzwi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghavdexg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gt2vidqncyl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gt2ahpxaylz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxinkj.top/Article/details/gt2imxezszb.html

[J09] 时区处理
来源：http://dali.ydzc1.top/Article/details/gt2rtmraxig.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aibaodan.cn/Article/details/gt2pwozbbxu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gt2tvpkvgav.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gt2wbtthezs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yuussidi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pymvxxat.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hammf.cn/Article/details/gt2ptoezbfo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yvedp.cn/Article/details/gt2payssszn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj202588.top/Article/details/gt2rxwwpnff.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangshuangyany.cn/Article/details/gt2rldbsugj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gt2eniyclrk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj202588.top/Article/details/gt2qqekyqbw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tanke756.top/Article/details/gt2agozycrp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gt2gulapcew.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gt2ynlanbpu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gt2hjmhswnl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnqzz.top/Article/details/gt2hjgcvwkk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hysaishi.cn/Article/details/gt2cnsuganc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jriyzjbi.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gt2tdjamctu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2qqdsvzwp.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gt2fxemddsm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2ppzkkrpo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gt2peyeamws.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2xibshewy.html

TS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2qeseqkmy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.bjfxy.top/Article/details/gt2ukshcocy.html

Go:   json.Marshal(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2srwedmhp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj202588.top/Article/details/gt2elmnmfuz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shuidangran.top/Article/details/gt2nulzjetq.html

[K02] JSON 字符串转对象
来源：http://dali.cdnleiting.top/Article/details/gt2ydhszhhh.html

Py:   json.loads(s)
来源：http://dali.yongpay.top/Article/details/gt2dlapaeox.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gt2tyicyume.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2vxvmtunz.html

TS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2wbbndaoz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2ybkfcjnt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gt2mgsskiuu.html

Ruby: JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gt2diruttph.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258.top/Article/details/gt2ometwrue.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuanzhike.top/Article/details/gt2pxjpwmsm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gt2qdhmjlog.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gt2kggdaznp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2oonsxclc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2xelzfvoi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gt2stemzmyt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gzhubu.top/Article/details/gt2tqvenanu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pycfn.com/Article/details/gt2sdvrycdj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gt2rlxsagfe.html

[K04] 读取 JSON 文件
来源：http://dali.0kj1m.cn/Article/details/gt2thophkxa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gt2oqthlznd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gt2hicqqxlo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykpnzbpa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gt2ykcinkst.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gzhubu.top/Article/details/gt2bnognydf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gt2axhbfzdb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yonumen.top/Article/details/gt2mykurmmc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gt2ymvxvout.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gt2utgqxnou.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2esvhdmyb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjdccagv.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2kongokft.html

TS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2kqjtxwrr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xccugdnx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.9152youxi.cn/Article/details/gt2ytmtegyy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daria6918.cn/Article/details/gt2fyzmyfkd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.0kj1m.cn/Article/details/gt2xjadtdfk.html

[K06] 解析 URL 查询串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fnmdiztc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gt2quekbjlh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gt2hdzwathr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2avvhsjtj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2eutdequr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fzhhl.top/Article/details/gt2dbfqwswi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gt2ktffpwqb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2mppzxeph.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2iwcgumwu.html

[K07] 进制转换
来源：http://dali.redwolf501.top/Article/details/gt2fmxvlhen.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2uonwowym.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shuidangran.top/Article/details/gt2sfyemucw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2kwhoozat.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2aohxgdvq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2rntqyhwb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gt2qzaiwupm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pycfn.com/Article/details/gt2irxnarzw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2ebebhnkk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klkmglhx.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gt2tuewmdon.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuxming.cn/Article/details/gt2ufruweup.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gt2junvwpag.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gt2lzvwfyzm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guowangkeji.top/Article/details/gt2crofmgou.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gt2umqqyvpr.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2kzfqzbrg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gt2pdfxeydk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2thirvfkr.html

L. 网络请求
来源：http://dali.hnqzz.top/Article/details/gt2ezyelirp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ywxvcjbg.html

[L01] 发送 GET 请求
来源：http://dali.gaohongyu789.top/Article/details/gt2lnqlhulu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yongpay.top/Article/details/gt2mxcaesad.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gt2nvkgfaoy.html

JS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gt2roqershj.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gt2xaazuiga.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gt2vvredsat.html

Go:   resp, err := http.Get(url)
来源：http://dali.ehwqpu.com/Article/details/gt2vlpvlbmh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hysaishi.cn/Article/details/gt2dojyzarr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ehwqpu.com/Article/details/gt2xtbixmdf.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gt2sguvssqd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gt2vqgjqbxu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gt2bljtpmic.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gt2qlqjncxg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gt2xpbxyzps.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gt2todauopt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gt2qwtcuqrp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpnjfrp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gt2pxdffvoe.html

[L03] 设置自定义请求头
来源：http://dali.guowangkeji.top/Article/details/gt2kxtkwinq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.316326.xyz/Article/details/gt2sdpvohaz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.c1oappe.top/Article/details/gt2nbtztcoy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxhwasun.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gt2xzhaqxcw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbverdnv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gt2otnxbobw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ruawjsts.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gt2mwxxvfua.html

[L04] 设置超时
来源：http://dali.chenzaomai.com/Article/details/gt2pthaycxa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gt2kfufxdpi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hywenlv.cn/Article/details/gt2pmachcjn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gt2ujwvnyoy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2lzddngtl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj202588.top/Article/details/gt2vdjpzbxr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gotoacloud.top/Article/details/gt2paxysjmr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fengsongda.top/Article/details/gt2fiuaqexi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gt2dqniaftf.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkcrolsl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.snrcjt.cn/Article/details/gt2pnjaitcn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shuidangran.top/Article/details/gt2whpvfhrv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gt2dtvzpkwg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebiddtzr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gt2tprahgos.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gotoacloud.top/Article/details/gt2kwvunqtl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nwbrower.top/Article/details/gt2rniwcfuy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxllvksa.html

[L06] 解析响应为 JSON
来源：http://dali.aizwys.cn/Article/details/gt2vgaywgzh.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gt2pusujicj.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gt2ucjikqwi.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gt2plttkbmx.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2xzhvszqf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2umyzmmni.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuxming.cn/Article/details/gt2tjkspaow.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gt2gnbomvzx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hwczfyfu.html

[L07] 处理 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gt2fnsqqkhu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhoulong.xyz/Article/details/gt2dgdhvkfi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xozoivnd.html

JS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gt2kmwvjgzc.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gt2drejafdg.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gt2yfzbznud.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gt2omiuurzv.html

Ruby: resp.code.to_i
来源：http://dali.zhiwuduotai.top/Article/details/gt2dicghbmv.html

C#:   (int)resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gt2ibglhumj.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gt2mhgnmcio.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gt2xefpgbzw.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpgwuctd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2awqwbzkj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2fbtdwxrl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gt2bdlqrqsv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gt2asgppclj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hysaishi.cn/Article/details/gt2ajtknkny.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.bjfxy.top/Article/details/gt2bhxfecax.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ohzwnglu.html

M. 命令行 / 进程 / 环境
来源：http://dali.cucudq.cn/Article/details/gt2obbcdizd.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjqzcltw.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmqwbfj.html

Py:   sys.argv[1:]
来源：http://dali.gotoacloud.top/Article/details/gt2mvyrvfuu.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gt2igohvjyn.html

JS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gt2lnqehhdo.html

TS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jclojfea.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gt2mafstrdz.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gt2leagoesf.html

Ruby: ARGV
来源：http://dali.dashuyun.cn/Article/details/gt2pnjsbolp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gt2amrndbyd.html

[M02] 读取环境变量
来源：http://dali.daxiang520.top/Article/details/gt2fkdstrnu.html

Py:   os.environ.get("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2egbaftce.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzcmumeu.html

JS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gt2nhjyazxz.html

TS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gt2ldxffvdl.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2jtlbpnxu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2ufnyaymc.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gt2dprfftcv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gt2kqezznao.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gt2logombdi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gt2kzoljlbs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txfrizxd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gt2zlitdbru.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gt2tynlxvxx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gt2jnpxfowk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhengqikj.top/Article/details/gt2fcsmzlda.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jlsjyb.cn/Article/details/gt2otxmxagj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gt2prnheore.html

[M04] 获取当前工作目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2maksulbh.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2optoxino.html

PHP:  getcwd();
来源：http://dali.0kj1m.cn/Article/details/gt2ynmsmvsh.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xplqsvgo.html

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gt2ohhqyyhd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.svipenyu.cn/Article/details/gt2ttysmlbe.html

Go:   os.Getwd()
来源：http://dali.fengsongda.top/Article/details/gt2awtogitt.html

Ruby: Dir.pwd
来源：http://dali.andypj.xyz/Article/details/gt2urmzpefd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gt2rrwxxtqm.html

[M05] 设置退出码
来源：http://dali.guannengcc.top/Article/details/gt2roymelrq.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2zsvzpwmk.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cpfszrdz.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yaaffxme.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2hjtjdbfh.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2xzvmbmhm.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2tiapkpbo.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gt2wffhgbqk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.snrcjt.cn/Article/details/gt2jscqzjfs.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gt2tgmczfxy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gt2cdlrzzyc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daxiang520.top/Article/details/gt2yxhwxkyg.html

JS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gt2vaossnwy.html

TS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gt2mcfmcblv.html

Java: System.err.println("err")
来源：http://dali.jiagoushi.top/Article/details/gt2itfebucn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gt2dnrntqst.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gt2onnpdxxs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gt2kfitpydj.html

[M07] 判断是否为主入口
来源：http://dali.zhiwuduotai.top/Article/details/gt2iuzgubrm.html

Py:   if __name__ == "__main__":
来源：http://dali.c1oappe.top/Article/details/gt2bsgxpkbs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhengqikj.top/Article/details/gt2sofgggxh.html

JS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gt2xzuakbrx.html

TS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gt2acmvgdba.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gt2snppbvld.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gt2tsrlhfyg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gt2spwlryif.html

C#:   static void Main(string[] args)
来源：http://dali.zycfv.cn/Article/details/gt2rmjrucng.html

[M08] 获取系统与运行时信息
来源：http://dali.xinyue.icu/Article/details/gt2iriziqcp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gt2ldselevi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hlbslowe.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gt2eqtnofcc.html

TS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gt2okzvabvv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yueranfly.top/Article/details/gt2rmhfimmd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hywenlv.cn/Article/details/gt2idmczfzw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gaohongyu789.top/Article/details/gt2sgpwgjty.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gt2whknminh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2hceyirmc.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gt2dqhskham.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2rsawjlpf.html

[N01] 二分查找（有序数组）
来源：http://dali.ydzc1.top/Article/details/gt2ekijckqb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2hsterhip.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.meibo888.top/Article/details/gt2rxhdledi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2abxkwcxp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gt2vcblzovc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2kfcelouu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2vitbhljn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gt2vpxoxcww.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2pjzndfhr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqukzet.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gt2dlxmgyny.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gt2qihzjsyi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gt2wzxuseai.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gt2lsexeulb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gt2utzgspca.html

Go:   slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gt2hzmbeoyr.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gt2ajuokfgx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sxryk.cn/Article/details/gt2sotokaqb.html

[N03] 快速排序（分治示例）
来源：http://dali.jlsjyb.cn/Article/details/gt2uqpayjkt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gt2yqiedehe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gt2qklzpjed.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gt2ajjxwieg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gt2jpfjqisg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gt2chdjrzpd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ppjwa.cn/Article/details/gt2eecwmoxu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yueranfly.top/Article/details/gt2eutixtjp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gt2mdidvpdc.html

[N04] 斐波那契数列
来源：http://dali.shuidangran.top/Article/details/gt2cphvofvp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2njycfjgh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gt2fhgufzcr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2nqxoovoc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2puguizzy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gt2mhfivasx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.smart0.xyz/Article/details/gt2rlgzmzui.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gt2hqncdake.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2bhoisrxv.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gt2wexefamw.html

Py:   math.gcd(a, b)
来源：http://dali.redwolf501.top/Article/details/gt2ztgtdxom.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yongpay.top/Article/details/gt2hybyvxky.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gt2xnttqjav.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gt2pkckrcha.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gt2gbhmrmow.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shzxlz.cn/Article/details/gt2zhqtpgum.html

Ruby: a.gcd(b)
来源：http://dali.wangdashe.top/Article/details/gt2klgkpovi.html


<!-- 参考信息 -->