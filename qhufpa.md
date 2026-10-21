代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gtocoxqntj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gtitrqweul.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.smart0.xyz/Article/details/gtztmiwivy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxinkj.top/Article/details/gtiitxilmc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gtfjbkswqc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gttccalthg.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gtmgkrfbgp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gtslckwcqc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gtfvdlmqkl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtgyzhjbnr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtevtwaoeg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sysykeji.top/Article/details/gtxdsboxfl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zycfv.cn/Article/details/gtkvttbaph.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gtrpmkwogt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gtfrookfsr.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gtlaiszhhj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gtbrlawuel.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.0kj1m.cn/Article/details/gtygxpptgf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gtxqarchnm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyiqpqps.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtdnbexnnq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.mhx1999.top/Article/details/gthhzscvki.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtggfsyyai.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtdccwiuhy.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtfmjlglil.html

K. JSON 与序列化
来源：http://dali.yuanzhike.top/Article/details/gtctaviaip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtykbkgpyx.html

[K01] 对象转 JSON 字符串
来源：http://dali.gogol.net.cn/Article/details/gtgzvrnfxk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtevhpbfpm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtnmqwhtfd.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtkuavcppo.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtzgxhazvh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cqqwz.cn/Article/details/gtcxaxkzpp.html

Go:   json.Marshal(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtvuiokwzn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangtech.top/Article/details/gtkiqnxdjd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtwskhubcl.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gtixifvjya.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gtrxostulo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgufenzy.top/Article/details/gtrwijodxs.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gttneqpgfy.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtfsnklqyu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gtonntfdkq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtglaonpic.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtyunjwrcp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zdqjudy.top/Article/details/gtbcqbrkom.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesujgcay.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtnbxwmgpr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtpsovhkdi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gtwheiflin.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtftpmyesc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gtsxkqzrcw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.bjfxy.top/Article/details/gttqhveecv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenlongwang.top/Article/details/gtugjkdmjk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.birdmap.top/Article/details/gtemooskcg.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gtbytuwlcd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.0kj1m.cn/Article/details/gtpujonirc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuanzx.com/Article/details/gtgcnezwnl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtaxabmbot.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtveiofqvf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtpvssxkbe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtavhikpmn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gtofhkhkdz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cashguo.top/Article/details/gtmrjalohz.html

[K05] 深拷贝对象
来源：http://dali.nwbrower.top/Article/details/gteabbvgfg.html

Py:   copy.deepcopy(obj)
来源：http://dali.zycfv.cn/Article/details/gtsvdwdcov.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yongpay.top/Article/details/gtqrhzhldk.html

JS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtzgcypzoz.html

TS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtwgotnplt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gtmluggjsm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gtmmluqekc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gtxrgzuenf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aibaodan.cn/Article/details/gthhbzdaoo.html

[K06] 解析 URL 查询串
来源：http://dali.gzhubu.top/Article/details/gtswmwbnlz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtychrxrnr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guowangkeji.top/Article/details/gtgcipkldb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtdoykrmzu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtagbbkebd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yongpay.top/Article/details/gtcpbwbank.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtgwomqltp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtyfatbgks.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtvhldlxgf.html

[K07] 进制转换
来源：http://dali.chenjidiqi.icu/Article/details/gtlwwdisps.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtmuaymybl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gtofhhhtgk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtggiqncum.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtbftyqnwc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtiwvjnrgl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gtrywzadwi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gtcvgbwrqi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtcqfkfrtb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigufen.top/Article/details/gtxocvdnxt.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gtyvpnibah.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gtokxbmndn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gtraxogcdc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gtbviplkni.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gtmeonhwxr.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gtnwisvpmt.html

Ruby: Marshal.dump(obj)
来源：http://dali.sweek.top/Article/details/gtptvoyeuu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gtnxzqicfx.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtwzlsqdko.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtrxbzschu.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtaiivpggd.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gtrnsodjzk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yangfankeji.com/Article/details/gtkbhszfem.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.vqdsnc.cn/Article/details/gtwprsjkrd.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gthbqdbnnl.html

TS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadajzgks.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gtmnvnudgs.html

Go:   resp, err := http.Get(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcekkqmi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gttmjgckoz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gtycmrqmzu.html

[L02] 发送 POST JSON
来源：http://dali.hammf.cn/Article/details/gtnlfkckxx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gtcydgcgix.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gtyucogmzy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtzwcddxze.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gthllzmzid.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ppjwa.cn/Article/details/gthymddkdc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gtggwqbxqk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yvedp.cn/Article/details/gtiiwnhgbs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gtkkyoistf.html

[L03] 设置自定义请求头
来源：http://dali.xinyue.icu/Article/details/gtkxxdckll.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258888.top/Article/details/gtemirvrbl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.vqdsnc.cn/Article/details/gtnikiztkg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtsapozgcl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtlxdahczu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gtrbhypygx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtufkbpvad.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pycfn.com/Article/details/gtmocukdju.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gtdrcjcqfh.html

[L04] 设置超时
来源：http://dali.jqgfzy.top/Article/details/gtcjfjiijy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shuidangran.top/Article/details/gtzbfkkdzm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sysykeji.top/Article/details/gteiajehqe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtohbqdkze.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtcdrbtvzx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhixingplan.top/Article/details/gtrcitwurx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtrdiycazr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gtvhfocvco.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gtyhomjmfk.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gtotaozirf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.svipenyu.cn/Article/details/gtbvifrgyl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.9152youxi.cn/Article/details/gtfoydrias.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gttcdefnyx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gttzcsovwe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gtwqyevyrc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.smart0.xyz/Article/details/gtrovyoywm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ydzc1.top/Article/details/gtgkrrtdbl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtqckivswi.html

[L06] 解析响应为 JSON
来源：http://dali.aizwys.cn/Article/details/gtlxkyvwyh.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjhgovov.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gtshmwlblo.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtghliclbx.html

TS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtvkswcynq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtvuxeehvd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gtrwhunmzf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gtjoijriwd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.snrcjt.cn/Article/details/gtpmxxwwed.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtrlmyebac.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.vqdsnc.cn/Article/details/gtnaiztwrp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.havefunace.top/Article/details/gtjbrxdepi.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtklyqkbxv.html

TS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtoubfgags.html

Java: resp.statusCode()
来源：http://dali.cdnleiting.top/Article/details/gtijmpukdu.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtajkbstqi.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gtauqpwxtz.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhqbfuwr.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gtgrmanpdb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuanzx.com/Article/details/gtavxgysng.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gtcnfnpimi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtmtaustla.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtmsjdchcn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gtnrndqgud.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shuidangran.top/Article/details/gtcoqcvsmq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtfmaascyz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gthecllkvp.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtonmrcome.html

M. 命令行 / 进程 / 环境
来源：http://dali.gogol.net.cn/Article/details/gtnxxvcenr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtehkcnrlx.html

[M01] 读取命令行参数
来源：http://dali.chenzaomai.com/Article/details/gtadhffkta.html

Py:   sys.argv[1:]
来源：http://dali.andypj.xyz/Article/details/gtigakcvuu.html

PHP:  $argv;  $argc;
来源：http://dali.tanke756.top/Article/details/gtfsslupsu.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gtfvfibcgo.html

TS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtexkplrlb.html

Java: args 数组（main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gtmibkxotq.html

Go:   os.Args[1:]
来源：http://dali.yangfankeji.com/Article/details/gtldynvjxv.html

Ruby: ARGV
来源：http://dali.ybcxt.top/Article/details/gtvvnswsaa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtaqdmmbae.html

[M02] 读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gtuhideful.html

Py:   os.environ.get("HOME")
来源：http://dali.yvedp.cn/Article/details/gtgigrynia.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtpcugwhex.html

JS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtmvhdllnf.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtythuwyju.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtwjsbebxk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbihwuhl.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gtbjqacjmi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtomjvpjgx.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gtmpgxbvvz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gtiawcoeit.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gtakbpsuna.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtaxeqlffh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gteufzhmaz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.snrcjt.cn/Article/details/gthppxecdp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aizwys.cn/Article/details/gtjujxdgpo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gtnykokobv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gtpspfgdus.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbpzxuly.html

Py:   os.getcwd()
来源：http://dali.dashuyun.cn/Article/details/gtlheiffvi.html

PHP:  getcwd();
来源：http://dali.sysykeji.top/Article/details/gtogtkqwql.html

JS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gtcaeewlpj.html

TS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtyuwuypdn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tian-w.cn/Article/details/gtmgmbmurv.html

Go:   os.Getwd()
来源：http://dali.zhoulong.xyz/Article/details/gttdreshbc.html

Ruby: Dir.pwd
来源：http://dali.gaohongyu789.top/Article/details/gtntpxgyzh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigufen.top/Article/details/gtwfjtcabg.html

[M05] 设置退出码
来源：http://dali.jinqigfzy.top/Article/details/gtbxmexdik.html

Py:   sys.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtpylrclar.html

PHP:  exit(1);
来源：http://dali.iojbl.cn/Article/details/gthqoavcul.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtcwqkuvyj.html

TS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gttssjqeht.html

Java: System.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpkkpnqo.html

Go:   os.Exit(1)
来源：http://dali.smart0.xyz/Article/details/gtrdtotrdv.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gtstdhomal.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgawgihne.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtmypayhae.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtubtlle.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gtqejkbzuy.html

JS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtiyknligl.html

TS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtnwofqupx.html

Java: System.err.println("err")
来源：http://dali.smart0.xyz/Article/details/gtcfdagjez.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.9152youxi.cn/Article/details/gtnlivncam.html

Ruby: warn "err"
来源：http://dali.guowangkeji.top/Article/details/gtezdjjvje.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hfpthk.cn/Article/details/gtgnqgoaie.html

[M07] 判断是否为主入口
来源：http://dali.nanxuanxn.top/Article/details/gtvalmageh.html

Py:   if __name__ == "__main__":
来源：http://dali.tian-w.cn/Article/details/gtxlzqdbgl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebpnulqq.html

JS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtsspdqexv.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtizvqlbxz.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtsodmaseh.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gtryargrai.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shangyingyoupin.top/Article/details/gtdizeclky.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gtaxjirzba.html

[M08] 获取系统与运行时信息
来源：http://dali.jiagoushi.top/Article/details/gtdqumnxpb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gtvpnoflhw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yvedp.cn/Article/details/gtlfftvcjj.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtzphkdxnc.html

TS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gtdqoyuhjq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhoulong.xyz/Article/details/gtmioipkix.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sweek.top/Article/details/gtpagywkbg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ehwqpu.com/Article/details/gtfsqevouk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gtlwkqrvef.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtyoylmfao.html

N. 数据结构与算法
来源：http://dali.fzhhl.top/Article/details/gtoovqiies.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtfjgwrdzf.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gtfpykvrah.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtzbyyzvft.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtfqiycfmp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtiixhhhsy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtgtdcsygo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtctundtmi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtxesiysst.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shuidangran.top/Article/details/gtiemjmocl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtboupuozp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daxiang520.top/Article/details/gtnlwrmicf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gtvgwqdltq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gtdwylausn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gtyjllkigd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtpaegzllq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ppjwa.cn/Article/details/gtpbiuonas.html

Go:   slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtywnjfhvl.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtftadwnnd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.havefunace.top/Article/details/gtgtcjpbql.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gtfteugatb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yueranfly.top/Article/details/gtgwxjeddc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ybcxt.top/Article/details/gtptbjhgxn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gthizxnopx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gtzreriqxi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tanke756.top/Article/details/gtbewbigef.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbphcpkm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pycfn.com/Article/details/gtqqvrszzm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fzhhl.top/Article/details/gtzxclvjfz.html

[N04] 斐波那契数列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvyahyto.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gtvblfugfp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.meibo888.top/Article/details/gtdnuydedn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtwnsbweun.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtilwicndh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtlyzswtrw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzqlsaou.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtjqrlknnm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtdizphdfi.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gtsskuchpm.html

Py:   math.gcd(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtoqqrtafa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jiagoushi.top/Article/details/gtgwlkrybu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtysiukilw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtrvvhhodl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pengpengdd.cyou/Article/details/gtkidafszz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gtmowynyia.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gtpihevgtt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sysykeji.top/Article/details/gtkbrnahdx.html

[N06] 判断回文字符串
来源：http://dali.zdqjudy.top/Article/details/gtvvrzvgbp.html

Py:   s == s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gtxgbrwjjd.html

PHP:  $s === strrev($s);
来源：http://dali.birdmap.top/Article/details/gtnnlxwjqf.html


<!-- 参考信息 -->