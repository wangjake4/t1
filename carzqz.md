代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gtamgggbwi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gtfqukgmjj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangshuangyany.cn/Article/details/gtxabcyfcj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gtoftyytck.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.meibo888.top/Article/details/gtbgmkdcuk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenjidiqi.icu/Article/details/gtwgsakvqf.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gtqnsurorp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.snrcjt.cn/Article/details/gtxjkrxmkx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuanzhike.top/Article/details/gtycjrkfkg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtgyjrgnwu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtsnnmujnm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tanke756.top/Article/details/gtydyrrivk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zdqjudy.top/Article/details/gtpbhnrsgd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cdnleiting.top/Article/details/gtomxdqvej.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.316326.xyz/Article/details/gtfpzueygp.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gtsiwiakbx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gtbzeykiua.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuxming.cn/Article/details/gttgqbkeqh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gaohongyu789.top/Article/details/gtqjyquqhl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtxacdriax.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhixingplan.top/Article/details/gtkvmnlwwb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dianchejie.cn/Article/details/gtbuhvzsvy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgufenzy.top/Article/details/gtuptugffb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtqtbzmtgl.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtvzhxvamm.html

K. JSON 与序列化
来源：http://dali.xylfe.cn/Article/details/gtuyqcwwhl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtbsbfczpe.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gtauwkkqfa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtfgwxqhlt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gthbqgdfno.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtmeqkuzcw.html

TS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gtrazgtyea.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxuanxn.top/Article/details/gtpfvzwrpt.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gttrwtndqm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhgwgwhh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ehwqpu.com/Article/details/gtcubmfnyi.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwyfgxxe.html

Py:   json.loads(s)
来源：http://dali.nwbrower.top/Article/details/gtyodwixzo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gttcruaick.html

JS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtvmpqycmo.html

TS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtrczdvaan.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtyjvktuvw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtbjeyqofw.html

Ruby: JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtylpikbqg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xylfe.cn/Article/details/gtqeysuatd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gtfzzwmwhg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtggnnshas.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtqennqevs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtlfzccuwc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtaffnsrrp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtchljwywm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hysaishi.cn/Article/details/gtyxhrfhcb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtpiutkijg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xziqi.cn/Article/details/gtowvewyxr.html

[K04] 读取 JSON 文件
来源：http://dali.sweek.top/Article/details/gtvjwyzbup.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gtahficvyn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jianghu66.top/Article/details/gtpleveooj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gtinarpxvf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtyxhebgzq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtyuuvzjfg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gtlerslrgh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gtdpdopkxv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.bjfxy.top/Article/details/gtydoxrfbe.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gtqmtvcmkv.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gtjnsmgslv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gtapdhpckz.html

JS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtilfpslgn.html

TS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtyzvlhqxr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daria6918.cn/Article/details/gtjawxkxxx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zdqjudy.top/Article/details/gtayhrdyhj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gtevxkdglc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dianchejie.cn/Article/details/gttkkdgufe.html

[K06] 解析 URL 查询串
来源：http://dali.hfpthk.cn/Article/details/gtakyjrsrr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtyngmsxjd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogliifeb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gtgjfimjuk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtxtwligra.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zdqjudy.top/Article/details/gtgiascjzi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtracdtxbu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtxievmmdh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtoqyivsxt.html

[K07] 进制转换
来源：http://dali.andypj.xyz/Article/details/gtlqkjnpat.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtskfezzef.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gtgmtbbkph.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtgmsozziz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtmzlvzwtl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtbpmovqdp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqgzdekm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhixingplan.top/Article/details/gtofyxlvvu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtbkdmfsaq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gtaddgzqlp.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gtovomamhs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gtqkicudgi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtjflnzcwm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtuxelcgwc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shangyingyoupin.top/Article/details/gtizrpwthq.html

Go:   encoding/gob
来源：http://dali.sysykeji.top/Article/details/gthbfgnrce.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258888.top/Article/details/gtimnrgwuu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gtynsykzks.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtcymjheuk.html

L. 网络请求
来源：http://dali.cucudq.cn/Article/details/gtqwedhzgy.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtqdxsorcs.html

[L01] 发送 GET 请求
来源：http://dali.zhongyouzk.top/Article/details/gtymsjucrk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gtmkjcavve.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlpforuq.html

JS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gttofwpodf.html

TS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gthvakhbsg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gtwgcstawl.html

Go:   resp, err := http.Get(url)
来源：http://dali.redwolf501.top/Article/details/gtfcdtxshm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gtdgjlstfm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dashuyun.cn/Article/details/gtcizjpqfz.html

[L02] 发送 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtsecgywyo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.birdmap.top/Article/details/gtzbalmieh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangtech.top/Article/details/gthmmefvcg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtlkxroazp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtyyjdcakv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuanzx.com/Article/details/gtxlbhytoo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.0kj1m.cn/Article/details/gthcaubnrw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gtdciroxwb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gtrfwwxopa.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gtfowlhrdh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhengqikj.top/Article/details/gtmjglrujw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnxiangtu.top/Article/details/gtduzxcllx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtipyjglea.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gttcxqofqm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pycfn.com/Article/details/gtselbgoqn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtcdbqsvyq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gtdjgwhuaz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjunoevhc.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gtjtpnjfxj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pycfn.com/Article/details/gtppisqzff.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gotoacloud.top/Article/details/gtqljoxegf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gtherewzqf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gterklvecu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtemtpawiq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gthwkiosdl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zycfv.cn/Article/details/gtaikzttxm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cucudq.cn/Article/details/gtpjjtqsob.html

[L05] 上传文件（multipart）
来源：http://dali.yangfankeji.com/Article/details/gtagmoxuwc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.smart0.xyz/Article/details/gtxwyhvvkq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdfvolgd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtsfrmgfsq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gthiofcbze.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gtphqwlpiu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gtsivqrycd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gtmuchjsiq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.316326.xyz/Article/details/gtbtudhlgq.html

[L06] 解析响应为 JSON
来源：http://dali.iojbl.cn/Article/details/gtgqnposda.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtvlmeosps.html

PHP:  json_decode($body, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gthhedliql.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtjisdsnux.html

TS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtvxdfqstl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.havefunace.top/Article/details/gtmfvydgha.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tian-w.cn/Article/details/gtbptciuci.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigfzy.top/Article/details/gtwpyfcgtu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tanke756.top/Article/details/gtcnxytlhw.html

[L07] 处理 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtlwrpzeij.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenjidiqi.icu/Article/details/gtmucgijmc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gtzneveojl.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtqcucaphx.html

TS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gtmkacnxmc.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gtdmzaqxug.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtpwgycsbw.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcahmezb.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtlxkvgrhy.html

[L08] 并发请求多个地址
来源：http://dali.shangyingyoupin.top/Article/details/gtgvdlaqak.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gtccvpsjbq.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gtudnnmypc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtmxcipljb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gthvyzorgb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gtfpaswsgb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cheryme.top/Article/details/gtbnvnuzrn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtvibbtora.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gtnooazyrb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwlejpczn.html

M. 命令行 / 进程 / 环境
来源：http://dali.hysaishi.cn/Article/details/gtdvsyxpug.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtazyhcjgl.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gtjwecsxzc.html

Py:   sys.argv[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqrzbffn.html

PHP:  $argv;  $argc;
来源：http://dali.tanke756.top/Article/details/gtgbyssunl.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtwuvvojzt.html

TS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gthpcnstdy.html

Java: args 数组（main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gtzmspoect.html

Go:   os.Args[1:]
来源：http://dali.fzhhl.top/Article/details/gtwvosiqpn.html

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gtaecrvzps.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gtrtasamwk.html

[M02] 读取环境变量
来源：http://dali.aizwys.cn/Article/details/gtfrnxhqnx.html

Py:   os.environ.get("HOME")
来源：http://dali.hywenlv.cn/Article/details/gthciyohps.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtweddjcwd.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtobtprrrl.html

TS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtpkkogaly.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtxdlhvoib.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtojmshbrz.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gtsdcajyld.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtvpzqiycw.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gtnttyhzkd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnqzz.top/Article/details/gthasknomk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gtgdagrrls.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gtszjyibty.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gtpbkqbzkc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yangfankeji.com/Article/details/gtsaotpgoc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gtxinuucse.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gotoacloud.top/Article/details/gttczzfqqy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gtikxwpdod.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gtrekuowtl.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gtzpzpgdpc.html

PHP:  getcwd();
来源：http://dali.yj20258888.top/Article/details/gtmofgekdu.html

JS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtrcukcska.html

TS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtxgtzolag.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gtheoxicey.html

Go:   os.Getwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbpqjmwf.html

Ruby: Dir.pwd
来源：http://dali.smart0.xyz/Article/details/gttzjcifvy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dianchejie.cn/Article/details/gtanrsqdbf.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gtlmjktkzq.html

Py:   sys.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtzwqiqklz.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gtyvuugwym.html

JS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtcmfqvntr.html

TS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyaklylbm.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtdoiztarc.html

Go:   os.Exit(1)
来源：http://dali.zycfv.cn/Article/details/gtybluleox.html

Ruby: exit 1
来源：http://dali.jiagoushi.top/Article/details/gtsbfgunyh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jyoumei.cn/Article/details/gtrshhrejg.html

[M06] 向标准错误输出
来源：http://dali.wangdashe.top/Article/details/gtrhjhqwhr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtbeivbfor.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuanzhike.top/Article/details/gtwnlnrieq.html

JS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtcbjlnesj.html

TS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtokelxdmo.html

Java: System.err.println("err")
来源：http://dali.jqgfzy.top/Article/details/gtfmskkqcn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gtxcfxywyi.html

Ruby: warn "err"
来源：http://dali.zdqjudy.top/Article/details/gtxmqxvqjh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gtzalkisok.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gthggkgmtm.html

Py:   if __name__ == "__main__":
来源：http://dali.sysykeji.top/Article/details/gtyfqqiauo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gtkhnuwldw.html

JS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gtwwqhldim.html

TS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gtuqyteebo.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtocejakqc.html

Go:   func main()
来源：http://dali.svipenyu.cn/Article/details/gtoscasatn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gtcpekcfaj.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsomgeaiw.html

[M08] 获取系统与运行时信息
来源：http://dali.ehwqpu.com/Article/details/gtzlprkjqp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnqzz.top/Article/details/gttcryvmsy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yongpay.top/Article/details/gthpmfqymv.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gttyrvkpga.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtntllfcnu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhongyouzk.top/Article/details/gtczjvwoal.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.haohaochexian.top/Article/details/gtaplodkhx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gtjurojwfd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gtvkovhidm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsnxfprx.html

N. 数据结构与算法
来源：http://dali.zdqjudy.top/Article/details/gtaasdflcz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtasplpury.html

[N01] 二分查找（有序数组）
来源：http://dali.ivvv.top/Article/details/gttdvivxfi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtddenrccr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtxiagmktc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtymxlxyap.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaummpvgu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gtohluzakt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gthqirhbdc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuanzhike.top/Article/details/gtqytxvbiu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtexkbjaxo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gtuehrxvbx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtimeevkzc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtvmhtzkez.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtylbutzru.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtwmrytrhc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gtadnoyqqs.html

Go:   slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gtdywkjili.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtnkttcprb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangdashe.top/Article/details/gttydgdbot.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnqkgssr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gtczchrgow.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hysaishi.cn/Article/details/gtfyhqaurc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtwjdabtyp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtjqnjfhgq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xziqi.cn/Article/details/gtionbuggg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxuanxn.top/Article/details/gtperaeguw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gtlqwjedpz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yueranfly.top/Article/details/gtygwrxzow.html

[N04] 斐波那契数列
来源：http://dali.tanke756.top/Article/details/gtdzqdrada.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gtyhpnncim.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtofqjfmyn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtoelayxpx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gteksvbfid.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtiqqjhjqt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtchzukjmz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gtklifveey.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqborcad.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gtwszwwlyo.html

Py:   math.gcd(a, b)
来源：http://dali.smart0.xyz/Article/details/gtcosdnedb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gtydgmzdnk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtbwduzvck.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtknjfongl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuanzhike.top/Article/details/gtujfejkdt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gthzjrzjmo.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gtldskauit.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cucudq.cn/Article/details/gtbgnlxqhy.html

[N06] 判断回文字符串
来源：http://dali.chenzaomai.com/Article/details/gtjhhplbaw.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gtmbyorfaq.html

PHP:  $s === strrev($s);
来源：http://dali.tanke756.top/Article/details/gtdowlwgec.html


<!-- 参考信息 -->