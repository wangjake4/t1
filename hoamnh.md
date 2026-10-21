代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtczrzyeid.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daria6918.cn/Article/details/gtectcxqhl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.smart0.xyz/Article/details/gtgcyubigv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtnfujmgrs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtzhrbvixq.html

[J08] 提取年月日与星期
来源：http://dali.yj202588.top/Article/details/gttkcfliuo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xinyue.icu/Article/details/gtnuglduzb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gtvgasdjzm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtpkyakvmu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuanzhike.top/Article/details/gtvgnapbpk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pengpengdd.cyou/Article/details/gtjqsckdjl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.quarkkingdee.top/Article/details/gtsctlqkdf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigfzy.top/Article/details/gtewntzpfr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cdnleiting.top/Article/details/gthbbnluaq.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gttvhdqpqg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gtngzmtaws.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gtnnrlserc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gttksjmztc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtzwanvdet.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzggirpd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ivvv.top/Article/details/gtyyfzsose.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gthlwqckgg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yanxiufei.cn/Article/details/gtdbmarovs.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gtxsfjihcw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daria6918.cn/Article/details/gttcmhzayv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.iojbl.cn/Article/details/gtteflzums.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nwbrower.top/Article/details/gtiszejbpi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtzttlhasg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nwbrower.top/Article/details/gtmkudwtlg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gtnwbmjnak.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhixingplan.top/Article/details/gtemloetrm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.haohaochexian.top/Article/details/gtygqcjghj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtthidaldq.html

K. JSON 与序列化
来源：http://dali.jyoumei.cn/Article/details/gtwaaljfls.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtfmksehuo.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gtabhlktwj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gthbwholar.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gtuizridai.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtxycnqlsr.html

TS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtglretwlr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.birdmap.top/Article/details/gtodteeudn.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gtwabfpovg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yongpay.top/Article/details/gtwhqlnlvz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtwrivulps.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gtvybxoary.html

Py:   json.loads(s)
来源：http://dali.ivvv.top/Article/details/gtybryjtft.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gtgnfolykq.html

JS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtfjonenad.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtykoukqpq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtgeooyxwm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtbkwjqmkz.html

Ruby: JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtbzqejhbn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangdashe.top/Article/details/gtkrubhwxo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gtmicwddoq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gtycvqglvx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtbddesouz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtchzgppnq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gtkcnuyxmi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtlrhqxfvk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cashguo.top/Article/details/gtuufggqeg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gtibtnmwdt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gtdipmvodz.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gtytjhozbj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ehwqpu.com/Article/details/gtcjzbvobg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwgkdngj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtjrzksswe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtvtcyafzp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.316326.xyz/Article/details/gtotczuyoq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtjoiyvyub.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gtbsaslsgv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gtrbtgnfhf.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gtqqmicwec.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gtrxqhdlwv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guannengcc.top/Article/details/gthrghfqwc.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtlgqelzgg.html

TS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gthydolhia.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nwbrower.top/Article/details/gtlxlgqffu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gtzjtzpatq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gtbllnkamp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.havefunace.top/Article/details/gtkwgfxqcm.html

[K06] 解析 URL 查询串
来源：http://dali.chenzaomai.com/Article/details/gthyurkizv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtiudsxcqc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gtgrfrxbrv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gthyszjegl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtjtrsqute.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gtpucygorv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtrjpaucie.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gturnhdhbi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtchkiwjro.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gtmgguapvz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gteurktepg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xylfe.cn/Article/details/gtqwogxndq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtqsykbfug.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtrclsrkik.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtilfuirph.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tanke756.top/Article/details/gtrvbonqnd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj202588.top/Article/details/gtbxdkyuws.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gthojqogag.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgdqopcw.html

Py:   pickle.dumps(obj)
来源：http://dali.yuxming.cn/Article/details/gtccjtcvyd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gtkfiiehsp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtnmlsfomd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gthuendouz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gtthvpcmaw.html

Go:   encoding/gob
来源：http://dali.redwolf501.top/Article/details/gtxrkkymgd.html

Ruby: Marshal.dump(obj)
来源：http://dali.shuidangran.top/Article/details/gtieakldog.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gtizplwyvv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtasawpnvm.html

L. 网络请求
来源：http://dali.yongpay.top/Article/details/gtnkgqszko.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gttlybyjdu.html

[L01] 发送 GET 请求
来源：http://dali.iojbl.cn/Article/details/gtbeojahzj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgfzy.top/Article/details/gteaytivge.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gtowybciuh.html

JS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gttcabewgy.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtnzdakhpz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gogol.net.cn/Article/details/gtuupecnto.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtzsempiij.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxnqjjpl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxuanxn.top/Article/details/gthstzakyo.html

[L02] 发送 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomashdqc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtiqhoajpk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tianlin.xyz/Article/details/gtjspbbjee.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtqiixsiry.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtcclmytxa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gaohongyu789.top/Article/details/gtbmavpsbd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gtjaqjyjde.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gogol.net.cn/Article/details/gtdvkmkabc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gtrhfmxyyc.html

[L03] 设置自定义请求头
来源：http://dali.yongpay.top/Article/details/gtxykhvqar.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gtdogmdpiq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtfgbjrytf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtnwhryaox.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gtoozcmrxb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangshuangyany.cn/Article/details/gtlyykprcb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtntvilmen.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gtbrbdcbkx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gtshvxdmqc.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gtdrtnqgua.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zdqjudy.top/Article/details/gtifkhafal.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gtlvvutldp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtyuqpnnsc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtpotfejig.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.9152youxi.cn/Article/details/gtssfqvzfm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hammf.cn/Article/details/gtgmjcarkb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangdashe.top/Article/details/gtkaecjuln.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yvedp.cn/Article/details/gtyoyxgtsm.html

[L05] 上传文件（multipart）
来源：http://dali.mhx1999.top/Article/details/gtzywtcgpa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gtraypfowi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtonoaewgq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtjngvjsvz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtxdlttkld.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.c1oappe.top/Article/details/gtwkpbxdvb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gtxwqnrrin.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gteeiqlvog.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtsiuykbda.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigfzy.top/Article/details/gtxwsvynea.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtxaahkmam.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gtufckckky.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtrfyqacxn.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtwhfdxnmz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hammf.cn/Article/details/gtkhjzvqsf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gtnjuegvqr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nwbrower.top/Article/details/gtwcxavezu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gtawufrzeu.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtjgzmtzvu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dashuyun.cn/Article/details/gtcnkxfrnz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gtqxmyhomn.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gtwlkbzjaa.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtcpcciirx.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gtnahrrzxl.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtvlumntqn.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangtech.top/Article/details/gtdiaarvqx.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gtzkshcogy.html

[L08] 并发请求多个地址
来源：http://dali.sweek.top/Article/details/gtulzngvvu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cucudq.cn/Article/details/gtoajljksw.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gtknlhejgz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtotkanubw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gtrfacoiwr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tanke756.top/Article/details/gtjgygrcvm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tanke756.top/Article/details/gtxazolrli.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtcsnzmujh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gtrqbvwmcx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtdswqgxsw.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gtovcdexrb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtoyzhkvyx.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtrwybqfsp.html

Py:   sys.argv[1:]
来源：http://dali.hnqzz.top/Article/details/gtzpecsbyc.html

PHP:  $argv;  $argc;
来源：http://dali.fzhhl.top/Article/details/gtwupcgtab.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtugzpgvsa.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtjzglxhdb.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtalpeiylr.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gtejixicjj.html

Ruby: ARGV
来源：http://dali.tanke756.top/Article/details/gtcjdkucsx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtiigufxkq.html

[M02] 读取环境变量
来源：http://dali.yj202588.top/Article/details/gthxbjikuy.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gtyqjycdra.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sweek.top/Article/details/gtepidjqkh.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gttqvqsozi.html

TS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtfkjkafjy.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtydtzqotb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtpsokwdkb.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gtotanhpgj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsokdzgx.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gtrudtumyq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gtymxhbmcg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.quarkkingdee.top/Article/details/gtbldcpitk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gtatwckpgt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtecpiztwr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gtaolxokfc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sufxvd.cn/Article/details/gtljqahlgy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dianchejie.cn/Article/details/gtgajwlsew.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gtuaovyjfw.html

[M04] 获取当前工作目录
来源：http://dali.jyoumei.cn/Article/details/gtmbhlyscv.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtsrfhiryz.html

PHP:  getcwd();
来源：http://dali.yangfankeji.com/Article/details/gtdozqhudx.html

JS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gtozphdeav.html

TS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gtrrtoartm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gtywuvubwn.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gtlgtjzztx.html

Ruby: Dir.pwd
来源：http://dali.yj202588.top/Article/details/gtdqqujqpy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ydzc1.top/Article/details/gtbccphlyf.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gtzgkakmyf.html

Py:   sys.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtgbjsehjl.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gtpepwbggn.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgwwhwry.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtxmpwtgnl.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gtpvtnyvpk.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtucaqhxpw.html

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gtegcuedrl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyxpdhzv.html

[M06] 向标准错误输出
来源：http://dali.meibo888.top/Article/details/gtzdzrfxzo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gtwyueajrc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.kuanghao11.cn/Article/details/gtjwyiwyzb.html

JS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gttowlyoph.html

TS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtxybpxnsu.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gtgvqnhzhm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sufxvd.cn/Article/details/gtqkffarlr.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxojzkye.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gtqnefldyg.html

[M07] 判断是否为主入口
来源：http://dali.xuetiantiany.cn/Article/details/gttrlimptq.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gtkebfwutm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenlongwang.top/Article/details/gtoddwgbhd.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtkuybfcvs.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtyrbfsrgz.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gtvlwktqox.html

Go:   func main()
来源：http://dali.gotoacloud.top/Article/details/gtgqugrbgx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gtvuclpdyj.html

C#:   static void Main(string[] args)
来源：http://dali.cheryme.top/Article/details/gtqzzohyiv.html

[M08] 获取系统与运行时信息
来源：http://dali.ydzc1.top/Article/details/gtcgghfrxa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gtjnnnsmnr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gtvptxxvif.html

JS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gtqygarrdx.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtbmheizfr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.316326.xyz/Article/details/gtkupkoysp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hysaishi.cn/Article/details/gtpzicbzzp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gtcxyrkiqs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zycfv.cn/Article/details/gtpigznskz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtocyggrsh.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gtyzbxhpyh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgsbdvgux.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gtyeoydjcz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.birdmap.top/Article/details/gtbsuqscun.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtgryvuidy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gttcjscbtu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtluwwqomp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtvoephtce.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtkpwlhbpb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yangfankeji.com/Article/details/gtjviqwwfq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtmhhjqaix.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.smart0.xyz/Article/details/gtorphffbn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtrncbtpaf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gtqxygxhpy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtvsifxozc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtvjpscwtz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pycfn.com/Article/details/gtpluwxraw.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtsrzxfquj.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtwjwccmqw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gtowpmmrbn.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gtoladiygm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.kuanghao11.cn/Article/details/gtnnfiwkqx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yvedp.cn/Article/details/gtjpvqprza.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gtxllrzbes.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gthqkqssqo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gtpkjbuhtv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cashguo.top/Article/details/gtqfkdtibs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdzmqvjc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gtkulduyct.html

[N04] 斐波那契数列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnoftahi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gtslzwnncp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtjemersmo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtafphnwij.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtzxdclktg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtzukerxqd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.havefunace.top/Article/details/gtribdzfyi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gtetaqdaut.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtlalfbjea.html

[N05] 最大公约数
来源：http://dali.yj20258.top/Article/details/gtgnmcbxbq.html

Py:   math.gcd(a, b)
来源：http://dali.iojbl.cn/Article/details/gtuazeextc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gtrvrkrrwb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gtqtoycmxp.html


<!-- 参考信息 -->