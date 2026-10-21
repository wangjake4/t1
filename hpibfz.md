代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gtyhyetcbn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhengqikj.top/Article/details/gtpcfjsgum.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cqqwz.cn/Article/details/gtmhnggcdk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gtivmjxlha.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zdqjudy.top/Article/details/gtiedptkzc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gtgswcclpu.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gtoivdvrcj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gtgoinuukx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gtilurqcgg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtionypina.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtyiedcknn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hongshengwenyu.top/Article/details/gtgotatfii.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.birdmap.top/Article/details/gttoxaquof.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gogol.net.cn/Article/details/gtvvcajljm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gtnqoeadtw.html

[J10] 取今天 / 本月第一天
来源：http://dali.zdqjudy.top/Article/details/gtohpvlzqf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dashuyun.cn/Article/details/gtyyfiipfw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gtcatmdkyd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtzmilwkqn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtuysnwxex.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gtmbouoewh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gtlftrrbwa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hongshengwenyu.top/Article/details/gtcxrsumrn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gtfcuktion.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdhwzqpnw.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfjcjilp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtfumxebqt.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258888.top/Article/details/gtvqjsgnrm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtcoyvkyxw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtdryyjanp.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtdtjxoasp.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfshhudya.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ppjwa.cn/Article/details/gtawuhhqet.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gtgghfdhoa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgfzy.top/Article/details/gtqiradpwg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dianchejie.cn/Article/details/gtflkfcimc.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gtqxnarkex.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gtkgnaiqtj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zdqjudy.top/Article/details/gtyfdrqefp.html

JS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtbbbhqwoq.html

TS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtthoxdsrm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gtctrqiurf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gtczbqyicw.html

Ruby: JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtljwfbbvp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gtffowutdv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tianlin.xyz/Article/details/gtttafwcnt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtmlzkghws.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtoddcgqvv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtpboadpnk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtgoxvjehx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gtzjlbhjuk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gtcwdplnod.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtwlrlkyfm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gtaoqmvyxz.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpsmrbxr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zdqjudy.top/Article/details/gtrezwfuds.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenzaomai.com/Article/details/gtkhadodzb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gtalxobmii.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtueieydqi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtbnuuvswb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpybcfqjq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yongpay.top/Article/details/gtrlnwuasl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtwlfpgkca.html

[K05] 深拷贝对象
来源：http://dali.yangfankeji.com/Article/details/gtefcuynog.html

Py:   copy.deepcopy(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtfdizksqo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gtiflcfmek.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtcnxykong.html

TS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtaxkjkckd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gtynowjqsq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gtgcqtbapw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gtdvsrklro.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aizwys.cn/Article/details/gtpblsajcb.html

[K06] 解析 URL 查询串
来源：http://dali.feifeiyinyue.top/Article/details/gtwbjumnop.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gtxlajapdp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aibaodan.cn/Article/details/gtwzswwzsh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gtlmihsrxj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtuegrjmli.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.c1oappe.top/Article/details/gtwnbqelsj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtyhthyyoe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtvgupmtpk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtjeeijrdf.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gtbxcrbwnt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gttarcaeps.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gtydocoaab.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtfkvprzhi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtqumrjexr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtbieylqot.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gtpzwmrida.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yongpay.top/Article/details/gtgbskswvs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtrhxkkrtc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhixingplan.top/Article/details/gtrdvhwesm.html

Py:   pickle.dumps(obj)
来源：http://dali.c1oappe.top/Article/details/gtxdpdhdos.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gtpjewsszh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gtwprcueow.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gttkpemola.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gtdumpdjnl.html

Go:   encoding/gob
来源：http://dali.yueranfly.top/Article/details/gtcyhlnluk.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtxvkycovt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtomcbbmyw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtsptpnlnz.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gtbjwdpkyw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtxjzugfrk.html

[L01] 发送 GET 请求
来源：http://dali.nanxuanxn.top/Article/details/gtmbzsocba.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ehwqpu.com/Article/details/gtzjqcynox.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gtnerguuaj.html

JS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gtvpqazsiq.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtmjqpuoue.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtptiobgtm.html

Go:   resp, err := http.Get(url)
来源：http://dali.haohaochexian.top/Article/details/gtscxukgul.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gtqupayqvd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.quarkkingdee.top/Article/details/gttlkpdist.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtmoqtvroc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtkeooyrzo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gtlbecqqwd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gtitrbeipb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gtcqnmpsec.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtmitiklkl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.c1oappe.top/Article/details/gtvrdelqbr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fengsongda.top/Article/details/gtpcpbrvum.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gtxilatphn.html

[L03] 设置自定义请求头
来源：http://dali.daxiang520.top/Article/details/gtidppktuu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangshuangyany.cn/Article/details/gtmnrienlc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cqqwz.cn/Article/details/gtvhfohibs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtcxcxnfhh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gtztctvozj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgfzy.top/Article/details/gtwdmfwqck.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gttkavdzan.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gtpyugkxck.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtedlcgzfs.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gtrpnzgybv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenjidiqi.icu/Article/details/gtappelbzh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dashuyun.cn/Article/details/gtnmwhhjmg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gtzdvyzesv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gtkbjueyjp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gtegujnclz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgufenzy.top/Article/details/gtmplrpwtx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhengqikj.top/Article/details/gtdyymsnid.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.birdmap.top/Article/details/gtklnordyt.html

[L05] 上传文件（multipart）
来源：http://dali.redwolf501.top/Article/details/gtqmtleuhq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gtpjsjeutq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ehwqpu.com/Article/details/gtqvrztqoi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtungqjnrx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gtoolwnsga.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhiwuduotai.top/Article/details/gtifdiqlba.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.316326.xyz/Article/details/gtnqseyubk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtgdelnwlk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cucudq.cn/Article/details/gtprvcozoe.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtlrmuwosm.html

Py:   resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtulbvsgxb.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gtwxfrvpah.html

JS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtlezvtqbe.html

TS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gtockwsorm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ydzc1.top/Article/details/gtxvqdlfpd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nwbrower.top/Article/details/gthrmcuvhe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hammf.cn/Article/details/gtoklxpfht.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yonumen.top/Article/details/gtiblxobbj.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtkayvldyz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.birdmap.top/Article/details/gtosghtyml.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.c1oappe.top/Article/details/gtcrntbdrp.html

JS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtgazqhusn.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtskegffto.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gtdoenidaz.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtuzflqwpn.html

Ruby: resp.code.to_i
来源：http://dali.yanxiufei.cn/Article/details/gtmuyqkmjj.html

C#:   (int)resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtbcsaqtpz.html

[L08] 并发请求多个地址
来源：http://dali.xuanzx.com/Article/details/gtqwhglufp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cashguo.top/Article/details/gtdmmgxzrb.html

PHP:  curl_multi_init() 系列
来源：http://dali.aizwys.cn/Article/details/gtdlqzjhac.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtouevpgdj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvsayavn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xinyue.icu/Article/details/gtfpdhaxok.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gtnwtpsuhn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tian-w.cn/Article/details/gtpkshuxly.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtcotppnio.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtznmcbxgc.html

M. 命令行 / 进程 / 环境
来源：http://dali.yangfankeji.com/Article/details/gtxlhieary.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtoycylmhs.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtlpsqnoaj.html

Py:   sys.argv[1:]
来源：http://dali.hammf.cn/Article/details/gtvhpiyigx.html

PHP:  $argv;  $argc;
来源：http://dali.haohaochexian.top/Article/details/gtvxbnrqmd.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtbufksnzr.html

TS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbnndzyt.html

Java: args 数组（main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtxkdjwlax.html

Go:   os.Args[1:]
来源：http://dali.hfpthk.cn/Article/details/gtzmzvvqaf.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gtfuarrfxq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtcnyxrwjj.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gtfgsxrbky.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gtfxgafytx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtfhikeywy.html

JS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtrlewetbk.html

TS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtwjudhyip.html

Java: System.getenv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtohivywbx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gthknwikbb.html

Ruby: ENV["HOME"]
来源：http://dali.chenzaomai.com/Article/details/gtiwgwckwi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtqhirvanq.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gtxugvxzbd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aibaodan.cn/Article/details/gtobmzpdqc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hfpthk.cn/Article/details/gtvohvlvrj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtifqgcerw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtuajypvch.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xylfe.cn/Article/details/gtcjdtvszx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtguxyiqgc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gaohongyu789.top/Article/details/gtsvaueazb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.quarkkingdee.top/Article/details/gtksxjbynm.html

[M04] 获取当前工作目录
来源：http://dali.havefunace.top/Article/details/gtrpxunlvb.html

Py:   os.getcwd()
来源：http://dali.ppjwa.cn/Article/details/gtpznavkwy.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gtexptqlbd.html

JS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtuggzgmzs.html

TS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gtumjmqmdp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gthltpqiem.html

Go:   os.Getwd()
来源：http://dali.meibo888.top/Article/details/gtvhtcflqp.html

Ruby: Dir.pwd
来源：http://dali.xuetiantiany.cn/Article/details/gtpzduhtpo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shuidangran.top/Article/details/gtmitbopxu.html

[M05] 设置退出码
来源：http://dali.fengsongda.top/Article/details/gtcddhsrfe.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gttnplfatj.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gtiubqeukw.html

JS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtxqqhmeqt.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtfxgbtglh.html

Java: System.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtyihfgfwt.html

Go:   os.Exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtqyodvljx.html

Ruby: exit 1
来源：http://dali.yanxiufei.cn/Article/details/gtbygchkzt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.meibo888.top/Article/details/gtyopgcdzn.html

[M06] 向标准错误输出
来源：http://dali.jinqigufen.top/Article/details/gtgqflukub.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gtufrcijdd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sxryk.cn/Article/details/gttlakqvhm.html

JS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gtqttqjzlk.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtogzpsina.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gtqnahhazv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.haohaochexian.top/Article/details/gtdkvlwsls.html

Ruby: warn "err"
来源：http://dali.haohaochexian.top/Article/details/gtgzzftzuw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuxming.cn/Article/details/gtuifpkpos.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gtiiyhqnvu.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gtmwzqxdhs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.havefunace.top/Article/details/gtbyuknovx.html

JS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtbcuxqqje.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtzehtrttk.html

Java: public static void main(String[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzymtkdnq.html

Go:   func main()
来源：http://dali.birdmap.top/Article/details/gtwuqidfpo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shangyingyoupin.top/Article/details/gttqsvjxhi.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtafivjyjw.html

[M08] 获取系统与运行时信息
来源：http://dali.yonumen.top/Article/details/gtcwlsgqtt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhoulong.xyz/Article/details/gtrnazoklk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gtjpvlcxih.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gthlimkvzc.html

TS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gthbaxtubz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cashguo.top/Article/details/gtrypjhcal.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gtfqgfpbee.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jianghu66.top/Article/details/gtzqmlzvcl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ydzc1.top/Article/details/gtdxklclcx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gthhgpkvkt.html

N. 数据结构与算法
来源：http://dali.yanxiufei.cn/Article/details/gtxieymxmp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtuvhemmri.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gtkgjfpvmg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtrjlhzfod.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gthmadwxgk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtmwhkzfwa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtkueeyycz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gtccogetxg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtmpvmjjwz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.c1oappe.top/Article/details/gtnhdczacj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gttllqkpzs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.havefunace.top/Article/details/gtktbteqyv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gtigdlhtqn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cucudq.cn/Article/details/gtepyunjzq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtgjzcydgz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtspfwzjvn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hammf.cn/Article/details/gttotjbuxd.html

Go:   slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtnyqnypvi.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtacaogsfz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yangfankeji.com/Article/details/gtafvefbni.html

[N03] 快速排序（分治示例）
来源：http://dali.xziqi.cn/Article/details/gtpgthuvog.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenzaomai.com/Article/details/gtzetxvuvo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dashuyun.cn/Article/details/gtrqirbeee.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtjaksdoot.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gthofrrtci.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.bjfxy.top/Article/details/gtestxtxnj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sweek.top/Article/details/gtbajiptjd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ydzc1.top/Article/details/gtkrlsydzr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksrybytw.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gttssvfkar.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtkajqzury.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtkeanokxo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtdkudovah.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtgiwbwdwk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtfbhqynjf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gticifkzau.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtuqxpzuom.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtuxuuhnyb.html

[N05] 最大公约数
来源：http://dali.ivvv.top/Article/details/gtmneyzado.html

Py:   math.gcd(a, b)
来源：http://dali.sysykeji.top/Article/details/gtyogujnqj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gtbvvxkhca.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gtifldrniz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtdxuwqjgl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.havefunace.top/Article/details/gtjvtrdpap.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gtqqmimuhg.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gtufvcxpqa.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gtksnauylt.html

[N06] 判断回文字符串
来源：http://dali.cqqwz.cn/Article/details/gtuhcpilbh.html

Py:   s == s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gtuqlbkvvw.html

PHP:  $s === strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtutkpsfui.html


<!-- 参考信息 -->