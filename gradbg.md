代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtvywqygcd.html

[J08] 提取年月日与星期
来源：http://dali.xylfe.cn/Article/details/gtbmxvnwqd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gtknduzdix.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gtbclmdpft.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.vqdsnc.cn/Article/details/gtwaynimbl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258888.top/Article/details/gtzuprgjpy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yangfankeji.com/Article/details/gtbkmgjqxi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gtuhmkkyap.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gtfbnpxsjx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tanke756.top/Article/details/gtrizvouwv.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gteswixxbk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gtbnsdyxjc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gtfkyfqtdw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtcxfojgnt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtzwuiffbx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gtwdpmwyes.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xinyue.icu/Article/details/gtrmqhlnhs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gtohodzkpc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guowangkeji.top/Article/details/gteldxpwrc.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gtsfmfijpv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gtdervwevj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gtfphwfuin.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gtksojxvoa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtgtlwuizs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gttinicbbm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjoyaywf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pengpengdd.cyou/Article/details/gtvwdjtlat.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.c1oappe.top/Article/details/gtbaxldgmf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkyyvbqpx.html

K. JSON 与序列化
来源：http://dali.bjfxy.top/Article/details/gtmlhprzuz.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtlsphezsi.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtghnuxcdb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gteisrcqyt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtcyqmvtzh.html

JS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gtcjitkcql.html

TS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtxwyxvrhh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gtxucwrnrt.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gtnrjaxvve.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gtahzuawhy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gtgdysfbei.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnslndoyz.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gtuujzwzap.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ehwqpu.com/Article/details/gtcegldhnf.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtkaatgfgn.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtogrlmqce.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtmqdhxcmn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtuypgpyvk.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzjzlbtj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gtjqnngxql.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fengsongda.top/Article/details/gtkrqhloml.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtjezfolog.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtrluunaqf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gtfjnldjbi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtxoyepjix.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ydzc1.top/Article/details/gtqsiaquln.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gtvxvxxweb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tian-w.cn/Article/details/gtzxfzlauy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjejchns.html

[K04] 读取 JSON 文件
来源：http://dali.yangfankeji.com/Article/details/gtmaaoleka.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtgpimpbac.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gtlsgklxpr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtjsqvfsuh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtsvqmzzku.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtkjwuhodo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtibhjvzqv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtexucziir.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gtzjawjzba.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gtpwinknta.html

Py:   copy.deepcopy(obj)
来源：http://dali.fengsongda.top/Article/details/gtermlhhka.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfzqhbni.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtypqzqawu.html

TS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtemywfjrt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dashuyun.cn/Article/details/gtebkfmfts.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.meibo888.top/Article/details/gtqtynzhdm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jianghu66.top/Article/details/gtfkwvmpgg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tanke756.top/Article/details/gtzjdjzksz.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gtatxajndg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnowlxlxa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuxming.cn/Article/details/gtgedpssbw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtrptzviqm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaaynjtta.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cashguo.top/Article/details/gthgqbmwlp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtrlivbzct.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtptggausz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtbzubvhkp.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gtusojkfuy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtifjeytky.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.meibo888.top/Article/details/gtugzahixn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtzbcuxohu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtgtvubthd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtfchtjxne.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tian-w.cn/Article/details/gtddjkkbbk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gtwbzkvtsn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtntibwuor.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gtjogcaqzf.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtdndgocwm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjxvfyzq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtdgvoddij.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtcsssewhc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.kuanghao11.cn/Article/details/gtgniolufh.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gtkwwigzkn.html

Ruby: Marshal.dump(obj)
来源：http://dali.ivvv.top/Article/details/gtljovhbsa.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gtkiatolmv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofaancol.html

L. 网络请求
来源：http://dali.nanxuanxn.top/Article/details/gtoiflonfm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtqwlirgaz.html

[L01] 发送 GET 请求
来源：http://dali.meibo888.top/Article/details/gteorprjep.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gtmzcewnna.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guannengcc.top/Article/details/gtymdkqcci.html

JS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gtojcyhsif.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gtpkkkahwj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfvdgunt.html

Go:   resp, err := http.Get(url)
来源：http://dali.shzxlz.cn/Article/details/gtcwroqpzf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpeysekcz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gtazfpxfhe.html

[L02] 发送 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtkrrkdflh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gtbztcgdsd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhengqikj.top/Article/details/gtropcjyaa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtaeumtgnu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gtuoeidnkn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdubxjvq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gtkapustzg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daria6918.cn/Article/details/gthctjewjb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gtscpcbhpg.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gttbhezgtc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hfpthk.cn/Article/details/gtgwqdkdxi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtwqhtmztd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtbjjgsszv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtckhjjoni.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gtnazqwwrp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gtzkzjkvhw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj202588.top/Article/details/gttjcwuroj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gtdeftrvfp.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gtsluxrbho.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tanke756.top/Article/details/gtjjhbotpl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hywenlv.cn/Article/details/gtinckdkvd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtlgiwehzp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtjgyykcer.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dashuyun.cn/Article/details/gtxzjcqdax.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gtrvwsxqpu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gtxujaajic.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xylfe.cn/Article/details/gtxxgqhpbx.html

[L05] 上传文件（multipart）
来源：http://dali.gzhubu.top/Article/details/gtvafuthsg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jlsjyb.cn/Article/details/gtyenwmtet.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shangyingyoupin.top/Article/details/gtpldbqvsc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gtxhwzivhh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtvkpkzktc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.iojbl.cn/Article/details/gttxdradkf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.316326.xyz/Article/details/gtrggfokid.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ydzc1.top/Article/details/gtvmfnnowd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtfkjobxvl.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gtdxsxqcqk.html

Py:   resp.json()
来源：http://dali.iojbl.cn/Article/details/gthnuuqeoz.html

PHP:  json_decode($body, true);
来源：http://dali.cqqwz.cn/Article/details/gtpjzarlvj.html

JS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwkfxxlo.html

TS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gtipkabgbr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtrlhqtoid.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlykaqjop.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daria6918.cn/Article/details/gtwdpimjhh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.c1oappe.top/Article/details/gtzhvthryf.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtcrehkzko.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gtvvdrurwa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnxiangtu.top/Article/details/gtlgwfcnrq.html

JS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gtivnvmssg.html

TS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtapktjvhl.html

Java: resp.statusCode()
来源：http://dali.yvedp.cn/Article/details/gtyhlcgyli.html

Go:   resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gttgpqwoms.html

Ruby: resp.code.to_i
来源：http://dali.xuanzx.com/Article/details/gttcnlavjd.html

C#:   (int)resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gtpzolcofx.html

[L08] 并发请求多个地址
来源：http://dali.yanxiufei.cn/Article/details/gtvkymohqh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gtnecyqusf.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gtuddpkffr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gtypwlgftr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtxvqvnlvq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gtuacwgddt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhengqikj.top/Article/details/gtvmgoffau.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gzhubu.top/Article/details/gtvjxkhhfl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gtgubzrvbc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtnotimtzi.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gtipnisvlw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gttsearajk.html

[M01] 读取命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlrfoymj.html

Py:   sys.argv[1:]
来源：http://dali.yj20258.top/Article/details/gtedrffezr.html

PHP:  $argv;  $argc;
来源：http://dali.cqqwz.cn/Article/details/gtitiisxxo.html

JS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdstysmw.html

TS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gtmkhpvqmw.html

Java: args 数组（main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gttxlkhybo.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtgomwuodm.html

Ruby: ARGV
来源：http://dali.ybcxt.top/Article/details/gtozylpdxh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gtkoixlrgl.html

[M02] 读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctwaawir.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gtzohqxmkn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtfarragoi.html

JS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtgtueiogh.html

TS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtmrlqfzld.html

Java: System.getenv("HOME")
来源：http://dali.yonumen.top/Article/details/gtolirfwss.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtxjtevkez.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gtcogynwnd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gtxqyjywxp.html

[M03] 执行外部命令
来源：http://dali.smart0.xyz/Article/details/gtxmgwznyi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gtdyqieznc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gtuuvwjouy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtnsulqceu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtvmfivmws.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gtvmftimqn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqdeanjy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gaohongyu789.top/Article/details/gtkmudxxnl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gtuuefjyxz.html

[M04] 获取当前工作目录
来源：http://dali.gzhubu.top/Article/details/gtkwtmtnmj.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtxgmsrqiv.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gtfwonixnn.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtojofhdsd.html

TS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtflphwxoj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gtahipuzud.html

Go:   os.Getwd()
来源：http://dali.xziqi.cn/Article/details/gtcqbklcqe.html

Ruby: Dir.pwd
来源：http://dali.svipenyu.cn/Article/details/gtbrqqomzo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gtjsnkbvao.html

[M05] 设置退出码
来源：http://dali.zhoulong.xyz/Article/details/gtzismtlhl.html

Py:   sys.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtxlngvohb.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gtcvyepxek.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtyyexrkpr.html

TS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtemdvppjk.html

Java: System.exit(1)
来源：http://dali.sweek.top/Article/details/gtkxiaqipf.html

Go:   os.Exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtqzmisnuc.html

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gthwfhauyx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gtobnevpsf.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gttdyvwnvu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gtkskjwfag.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yonumen.top/Article/details/gtufqdalap.html

JS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtjhvntlmt.html

TS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtplhobokg.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gtkdywnfvd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gtwpvyomgr.html

Ruby: warn "err"
来源：http://dali.ehwqpu.com/Article/details/gtqelrvoul.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zycfv.cn/Article/details/gteifhqloq.html

[M07] 判断是否为主入口
来源：http://dali.9152youxi.cn/Article/details/gtymrlzxxg.html

Py:   if __name__ == "__main__":
来源：http://dali.guannengcc.top/Article/details/gtocyykpxm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258888.top/Article/details/gtzwuiiumv.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbltdreze.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtxrwmolwd.html

Java: public static void main(String[] args)
来源：http://dali.hammf.cn/Article/details/gthvjxvsma.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gtelzfiudv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shangyingyoupin.top/Article/details/gtcarxjgqb.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gtvvyxkyoa.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gtyddioeoz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtaazfwxay.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhongyouzk.top/Article/details/gtyqhdkkyo.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtyuagrtuq.html

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtpxfpklbr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hywenlv.cn/Article/details/gtvperipwp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sufxvd.cn/Article/details/gtcyoxrqas.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangtech.top/Article/details/gtppqinfpr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gthvrorahe.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtcivxwqxs.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gtfbnjhtbt.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxnwepdxi.html

[N01] 二分查找（有序数组）
来源：http://dali.yuxming.cn/Article/details/gtddunyawg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtdvyayfio.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xinyue.icu/Article/details/gtbyykbrse.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtahagankz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtphqnhdkq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtfhxrmohr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtzhhtokil.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hfpthk.cn/Article/details/gtuovdwsza.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtnltvzniu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.9152youxi.cn/Article/details/gtdpyugkvy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtmmxprjkz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtnhenttsw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtptpefjgu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gtgwvfpbzu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gtyrkymurp.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtzkylimmh.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtnjlhlsnw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258.top/Article/details/gtrrclmyfd.html

[N03] 快速排序（分治示例）
来源：http://dali.yj202588.top/Article/details/gtsolpvvoi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.iojbl.cn/Article/details/gtcfcrfunt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.meibo888.top/Article/details/gtjqpyciwv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gtwletfgxj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gtenjzzfoi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gthdhaqtoa.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hongshengwenyu.top/Article/details/gttvkbtntw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ydzc1.top/Article/details/gtemgcnwnw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cdnleiting.top/Article/details/gtwvtegzyf.html

[N04] 斐波那契数列
来源：http://dali.tanke756.top/Article/details/gtqhbluyse.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtwkqabzdf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gtddoudyvv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtzgaqqwmi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtmvegbssm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gticrcolte.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangdashe.top/Article/details/gtswvlmotk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gtyllcbvmr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtfqygafdh.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gttgmbkmyv.html

Py:   math.gcd(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxoxgrlot.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gtbznnmzaa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtctrhxsgs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gtgmzalfqu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.haohaochexian.top/Article/details/gtbexvjybg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yangfankeji.com/Article/details/gtbelxygzm.html

Ruby: a.gcd(b)
来源：http://dali.shuidangran.top/Article/details/gtrptblmyh.html


<!-- 参考信息 -->