代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yanxiufei.cn/Article/details/gtcyzvtfar.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.c1oappe.top/Article/details/gtehitwwls.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cucudq.cn/Article/details/gtybnfhohn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dianchejie.cn/Article/details/gtsgawhxzm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gthuufuaoc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gtziodxiob.html

[J09] 时区处理
来源：http://dali.chenzaomai.com/Article/details/gtxxzmhexr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnxiangtu.top/Article/details/gtmycokdxi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fengsongda.top/Article/details/gtoyiradvu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtoohxrhjp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtnrrguiof.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxpavmjf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gtxoflafcx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gthmgqyyfi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gtsvsnagny.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gthqdyylpy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daxiang520.top/Article/details/gtqmehwmqd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hysaishi.cn/Article/details/gthgdxbqar.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.smart0.xyz/Article/details/gtruxvzpvg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtbzasyxeg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbxucybc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gtvhlfwnjo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ppjwa.cn/Article/details/gtpzucbnqj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jlsjyb.cn/Article/details/gtvbcqfhno.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtilfyyvag.html

K. JSON 与序列化
来源：http://dali.fengsongda.top/Article/details/gtbziztptq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtoqceywzn.html

[K01] 对象转 JSON 字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtanfxadnd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtyjpkldvr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gtwthwxqrm.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtxaoawzad.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gttisaizpp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gotoacloud.top/Article/details/gtigorchxr.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigufen.top/Article/details/gtngmrdthn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pycfn.com/Article/details/gtiybxvwjx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gtxszmjjfa.html

[K02] JSON 字符串转对象
来源：http://dali.jianghu66.top/Article/details/gtoipxucdd.html

Py:   json.loads(s)
来源：http://dali.hammf.cn/Article/details/gtlzkynesy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.haohaochexian.top/Article/details/gtxraazwex.html

JS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtppnwocza.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gturskpmyz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtrvozdeoi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtpangiklp.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gterbvrdde.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gtuktvvnfe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zdqjudy.top/Article/details/gtqqwmuhsb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtepxoygev.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtdzqamikb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtcrdkzhqz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtmlboznft.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sweek.top/Article/details/gteugsbuvy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zdqjudy.top/Article/details/gtrkbrddle.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sysykeji.top/Article/details/gtnriffhhh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yongpay.top/Article/details/gtvptkfasc.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gtkrlbnyum.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gtwsnehjhg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxinkj.top/Article/details/gtimpykxoj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gtzqjckgfg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gtyrixaczr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtofqcldyq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqcvfqlr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtbfgmoubc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtihcxtdbq.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gtuqyfwtvc.html

Py:   copy.deepcopy(obj)
来源：http://dali.gzhubu.top/Article/details/gtxuqpqbdg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gtroycbuxb.html

JS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtjqbfukqr.html

TS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtiggaumvh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtvgxkxhyz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fengsongda.top/Article/details/gtoucywgwt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgufenzy.top/Article/details/gthvsvcwoz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.316326.xyz/Article/details/gtimmcvofo.html

[K06] 解析 URL 查询串
来源：http://dali.kuanghao11.cn/Article/details/gtrwpiishd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzctcqrd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dianchejie.cn/Article/details/gtcssmyefw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gthhacpjxh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtwlexneev.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gttgitgqnn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtsjvrygcq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtohrhacnl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtvmqrcxzf.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gtxyacpgti.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtmmnmqzpd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hywenlv.cn/Article/details/gtbyfosqll.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtlfjlxrdb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtwyiunacl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtjygzgrbm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.quarkkingdee.top/Article/details/gtvvixwczs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jlsjyb.cn/Article/details/gtxpgtwvzf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtyavekvxg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ehwqpu.com/Article/details/gttuxuhxiw.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gtoalmxlka.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.haohaochexian.top/Article/details/gtupanvmba.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gtuaambiqs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gtbiepwvdg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenzaomai.com/Article/details/gtjayxzbyw.html

Go:   encoding/gob
来源：http://dali.chenzaomai.com/Article/details/gtvlzszkdd.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258888.top/Article/details/gtfnqcbvnq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtnyilefkz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtkisimjki.html

L. 网络请求
来源：http://dali.hysaishi.cn/Article/details/gtrsjtvgjc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtpjasowqd.html

[L01] 发送 GET 请求
来源：http://dali.chenlongwang.top/Article/details/gtkuxchxjr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigufen.top/Article/details/gtuxzxyzdd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gtfseqncth.html

JS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtazxskfmm.html

TS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtnefdvmtn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yueranfly.top/Article/details/gtacbtivpj.html

Go:   resp, err := http.Get(url)
来源：http://dali.0kj1m.cn/Article/details/gtipxnmtxf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangshuangyany.cn/Article/details/gtfwchihjx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtwhuyharq.html

[L02] 发送 POST JSON
来源：http://dali.meibo888.top/Article/details/gtgtvvddxt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gteiwnylco.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yangfankeji.com/Article/details/gtwzmttmxs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gtyjgbrydm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtdztwkpke.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtbiblkzxq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdoskdsb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jiagoushi.top/Article/details/gtjuugtuhy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gtjxjwpkuh.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gtqjgusfvq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cdnleiting.top/Article/details/gtfvoaftix.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gtzeapkusp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gtwpeodjmb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtpvqdagbl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gttortfwtp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtkoordgor.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hywenlv.cn/Article/details/gtcgajulsd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtjxvknwwz.html

[L04] 设置超时
来源：http://dali.yj202588.top/Article/details/gtxqorxnth.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnxiangtu.top/Article/details/gtgbyihyja.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gtsrwdfadv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtlvgpulmv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtlblprwno.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gteomejsie.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gtejjfqdpy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrbcjewo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.bjfxy.top/Article/details/gtyrszwmdl.html

[L05] 上传文件（multipart）
来源：http://dali.cdnleiting.top/Article/details/gtpyjtjyjj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gogol.net.cn/Article/details/gtrhugilfz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.birdmap.top/Article/details/gtnsuycyzc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtjwjbuttr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gtuwavkvod.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gtdrhummho.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gtklpwrwju.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.mhx1999.top/Article/details/gtawaxwsrk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtxrqmaaor.html

[L06] 解析响应为 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwimrcgj.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gtercdmmik.html

PHP:  json_decode($body, true);
来源：http://dali.zhengqikj.top/Article/details/gtuwhxvbil.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gthcjopurr.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtsjlfvamn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtjljiupwj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gtzhabwgoy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dianchejie.cn/Article/details/gtkwvxkrgq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtotinnzvw.html

[L07] 处理 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtgdrsvuim.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gtgvwjaxjs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigfzy.top/Article/details/gtbllhvkrx.html

JS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gterhfzztt.html

TS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gthjbctibc.html

Java: resp.statusCode()
来源：http://dali.zdqjudy.top/Article/details/gtejvzysgs.html

Go:   resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtgdgvigbz.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gtcdwkuvyb.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtpaahnueb.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gtbvtepojl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gtopjmdngq.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gtziwejaup.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtatvffhjq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtbzshbyqn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj202588.top/Article/details/gtapzifooq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gtthhynwxw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gtouscjxcb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gtfwbnpmnb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtvatkvurh.html

M. 命令行 / 进程 / 环境
来源：http://dali.ehwqpu.com/Article/details/gtptmjxxgs.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtfkckcpmm.html

[M01] 读取命令行参数
来源：http://dali.iojbl.cn/Article/details/gtzejxqijn.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkepqpmz.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gtqaqhexax.html

JS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtgwhbbsic.html

TS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gtapazwrty.html

Java: args 数组（main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gtpjabconv.html

Go:   os.Args[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtmcxwrank.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gtabeaeebp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtiuyogstt.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gtpmwqgsid.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gtmuubbxyx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtprfodbbw.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczgrownm.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gtjhrirhga.html

Java: System.getenv("HOME")
来源：http://dali.ivvv.top/Article/details/gtzamcimco.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sysykeji.top/Article/details/gtxzidrosk.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gtmottlrdv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtxhhcwust.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gtiwugslwu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ppjwa.cn/Article/details/gthmuwvtph.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gtibcvohkl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gtimtltxlh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtgaycrene.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shzxlz.cn/Article/details/gtxelgzlwu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gtcowiormp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsnvdjmy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yanxiufei.cn/Article/details/gtmojccxia.html

[M04] 获取当前工作目录
来源：http://dali.mhx1999.top/Article/details/gtafhjlaij.html

Py:   os.getcwd()
来源：http://dali.dianchejie.cn/Article/details/gtgqbfnsnz.html

PHP:  getcwd();
来源：http://dali.dianchejie.cn/Article/details/gtgaqnkegj.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtcufxxjld.html

TS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gtkekdmlwa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.andypj.xyz/Article/details/gtjjvrfhtk.html

Go:   os.Getwd()
来源：http://dali.jinqigfzy.top/Article/details/gtpiwidfdl.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gtmrbisvha.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daxiang520.top/Article/details/gthuknnuae.html

[M05] 设置退出码
来源：http://dali.meibo888.top/Article/details/gtquyfxcnb.html

Py:   sys.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtuqlpelzt.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gtretpuaod.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtiwrrlckn.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtigcuteli.html

Java: System.exit(1)
来源：http://dali.meibo888.top/Article/details/gtsiccyjmq.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gtpxyxspfo.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gtmlejzyei.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hammf.cn/Article/details/gtquxkwlqv.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gtsahbtfpq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gtdeongzvd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenzaomai.com/Article/details/gtpharxkvx.html

JS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gttmzizaaf.html

TS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gthntxiwfh.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gtjwrnpkmv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jlsjyb.cn/Article/details/gtpoxmkrba.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gtiseaefot.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.meibo888.top/Article/details/gttgwudqjc.html

[M07] 判断是否为主入口
来源：http://dali.dianchejie.cn/Article/details/gtslyzzytl.html

Py:   if __name__ == "__main__":
来源：http://dali.jyoumei.cn/Article/details/gticrrkzhn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gtfpealoec.html

JS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gtlnnaujqu.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtjidyxckr.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gtsjnlpjnd.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gtzjwroraq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxuanxn.top/Article/details/gtgiqrxtbj.html

C#:   static void Main(string[] args)
来源：http://dali.tianlin.xyz/Article/details/gtbnpsslyu.html

[M08] 获取系统与运行时信息
来源：http://dali.zhoulong.xyz/Article/details/gtkjuciypy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuxming.cn/Article/details/gtztzfufnt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenjidiqi.icu/Article/details/gthtrbbgog.html

JS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gtzepcjhzw.html

TS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gttutjrvrg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gtwzqneeic.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ybcxt.top/Article/details/gtvtmqitid.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gtiavaydqk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gtuwdpeupg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtuioewoug.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gtwhutxycu.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtmdyykzdo.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gtbftwekcu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtaytzjtwk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gtradshhmb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gtkdnxvuth.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtnsvofepc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtqnxoticw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gttmtxuoev.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.kuanghao11.cn/Article/details/gtchgdynhm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtqrtgrjsj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenzaomai.com/Article/details/gtkxkanafs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtygnwnhmn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtvfeidgfv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtvcmmkgoa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gttnsxkkfh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yanxiufei.cn/Article/details/gtiyryxfkv.html

Go:   slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gtkglvhswq.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gtzwqzmfsu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.svipenyu.cn/Article/details/gtyhocdhmx.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gtybarfnlz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cashguo.top/Article/details/gtaulszuel.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ivvv.top/Article/details/gtseqgpqke.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtdwsjncwv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gtlpeqvdjb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shangyingyoupin.top/Article/details/gteafjsgbj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hysaishi.cn/Article/details/gtkuozpsot.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.haohaochexian.top/Article/details/gtitjcroes.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gtnojgcgxw.html

[N04] 斐波那契数列
来源：http://dali.jqgfzy.top/Article/details/gtgqswgzci.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gtvavqqizl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtgxkgaeda.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtrjivwmlp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtslyydjpm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtashbttmh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sysykeji.top/Article/details/gtuhaucaeu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtvcwzzgur.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtxaasnvhg.html

[N05] 最大公约数
来源：http://dali.nwbrower.top/Article/details/gtockvtciw.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gtxmneabdw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nwbrower.top/Article/details/gtzpgiivhi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyweuotld.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtpomndonc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuetiantiany.cn/Article/details/gteakqehub.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258888.top/Article/details/gtvdiwvvbs.html

Ruby: a.gcd(b)
来源：http://dali.cdnleiting.top/Article/details/gtfkjnrogd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gtvsetibgq.html

[N06] 判断回文字符串
来源：http://dali.9152youxi.cn/Article/details/gttnpribxe.html

Py:   s == s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtozbeewlh.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtkptyoqsd.html


<!-- 参考信息 -->