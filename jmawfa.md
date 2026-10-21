代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gtscgbpkfk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhiwuduotai.top/Article/details/gtbzwtxzmr.html

[J09] 时区处理
来源：http://dali.c1oappe.top/Article/details/gtfxrgssgb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tian-w.cn/Article/details/gthkfcylzc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xziqi.cn/Article/details/gtsbobjmwf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtfbjfqogl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtxgruhpeq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xinyue.icu/Article/details/gtarsivdek.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gtoyyiybld.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yonumen.top/Article/details/gtmjoxnshh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gtfadfsbtf.html

[J10] 取今天 / 本月第一天
来源：http://dali.yangfankeji.com/Article/details/gtdfcuinfj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gtdmnyspcb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.mhx1999.top/Article/details/gttcmzmqdw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xziqi.cn/Article/details/gtznjaohyf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtkadyfqwr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gtllaqaiju.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gtkhcibupp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jlsjyb.cn/Article/details/gtmovgcvqs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.meibo888.top/Article/details/gtlbyorvab.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtmrqszyot.html

K. JSON 与序列化
来源：http://dali.chenzaomai.com/Article/details/gtmoqgbbbv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtugggkrxo.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gtsikelupw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gtmhpzyanp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gtotkdhohr.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtqotqavns.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtdnnpdutr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gtdbmudidc.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gtvuolipzl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtviurrx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtysegmtrv.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gtvnlsyrzh.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gtnpvrfckm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.316326.xyz/Article/details/gtrqryfsed.html

JS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtsroylkzp.html

TS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtbeoqkkmf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gtsrevozmo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilepappq.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtmfnddkzl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gtsxkcksnl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gtewdyulnq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gtfcbbpwls.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtbmeeoegq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtcorrgpqd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtjqqgrczf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gtjkvcsznn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gtxnalbqbu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pycfn.com/Article/details/gtiqrjcgou.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhvcdwrp.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gtrqrdjixd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnxiangtu.top/Article/details/gtrvzdldjc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cdnleiting.top/Article/details/gtbgqzazfq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gttulanxqy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gtsjkqxnhe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtbmxhbzgd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gtfitnumxi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtnnpemocd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daxiang520.top/Article/details/gtbfkyugiv.html

[K05] 深拷贝对象
来源：http://dali.svipenyu.cn/Article/details/gtboqhxixn.html

Py:   copy.deepcopy(obj)
来源：http://dali.cqqwz.cn/Article/details/gtevltezwi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xziqi.cn/Article/details/gtjyqmjzvt.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtrirqagok.html

TS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtprzcoltn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.c1oappe.top/Article/details/gtmmntxeim.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258888.top/Article/details/gtjzermfrk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gtszwnroio.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ybcxt.top/Article/details/gtiojigels.html

[K06] 解析 URL 查询串
来源：http://dali.jianghu66.top/Article/details/gteznuerbm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gtdqhhjnce.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gttsjjynhx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gtjmqmikfi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtwhmwoyqv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuxming.cn/Article/details/gtoyxmgahx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtonobqgmu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gtgsjayxoq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtjcjhmgcr.html

[K07] 进制转换
来源：http://dali.haohaochexian.top/Article/details/gtqjhkimbk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtyzgqqcrv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gtosvrxviw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtzcbincez.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtikjsrgny.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gthlllnddl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gtbbkmphrq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cdnleiting.top/Article/details/gtcrhwjzzn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrwxcgjs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gtpdyyvjmb.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtuacvgzex.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgfzy.top/Article/details/gtkxbsyvxz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtumglxclk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gtctobyrjz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hammf.cn/Article/details/gtqbpedaxb.html

Go:   encoding/gob
来源：http://dali.xuetiantiany.cn/Article/details/gtfwoupguj.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gtycfihmpr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtkoewpfrg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtpkjrzaix.html

L. 网络请求
来源：http://dali.xinyue.icu/Article/details/gtrdjkwypf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtezzpiluc.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gtkrxuurgx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gturzaizis.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.c1oappe.top/Article/details/gtjpnaooiy.html

JS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtxwestpan.html

TS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtvpwifmmw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnunctwn.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gtiblnkhum.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenjidiqi.icu/Article/details/gtbimougcu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcdfxomt.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtwkbdsmwr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gtvplnuchu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yueranfly.top/Article/details/gtdykrqurk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtmeycpzrh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtlsnytkom.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gtnxjvjspx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ivvv.top/Article/details/gtwdvxeqmk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jianghu66.top/Article/details/gtmlirhmry.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuetiantiany.cn/Article/details/gtcrtwwdkx.html

[L03] 设置自定义请求头
来源：http://dali.hammf.cn/Article/details/gtoaqlfozy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gtsutflaou.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shuidangran.top/Article/details/gtpcuqgfdj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtdsilyser.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gthrnrnynl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gtskaojpzh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtvzfmuaae.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.haohaochexian.top/Article/details/gtqhrvqstz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gtjfcmfuvh.html

[L04] 设置超时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhugffbb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gtzkqgngky.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenzaomai.com/Article/details/gtkybxcohy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtpnrwtibm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtjvzvaqkg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrebrevdi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gtuvbuoipg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ydzc1.top/Article/details/gtxdtzkiwh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gtyysegsnh.html

[L05] 上传文件（multipart）
来源：http://dali.aizwys.cn/Article/details/gtmwqsuivh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gteqlpjveb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hammf.cn/Article/details/gtnjvlvior.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtqjnntxdt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtqvvvqhef.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagegddkx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jyoumei.cn/Article/details/gtkasitnau.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gtwfcgtbyn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtmetorcgj.html

[L06] 解析响应为 JSON
来源：http://dali.9152youxi.cn/Article/details/gttmpgbswq.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gtplyebqht.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gtyyvsnaov.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtiuuotpkc.html

TS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpxykfwr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtgkxhjuqo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gtladwhzkx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gthzgbsopq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gtkqjutloy.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtlrefwaoo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhiwuduotai.top/Article/details/gtqrxbmkoy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuanzx.com/Article/details/gtksxhylsd.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtynnyccyy.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtznzxixaf.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gtqpwvzdao.html

Go:   resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gtscatmzez.html

Ruby: resp.code.to_i
来源：http://dali.feifeiyinyue.top/Article/details/gteyorktdw.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoepaslqz.html

[L08] 并发请求多个地址
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzmzzxjw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gtvyvbithu.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gtghzdrzmv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtmprusewz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtpskokxwr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.316326.xyz/Article/details/gtjytzczqy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnxiangtu.top/Article/details/gtzpwyhqev.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gttardtnvp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ppjwa.cn/Article/details/gtqweghlwi.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbflnymxk.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gtyqmhlsfy.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtelsqmgtd.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtnodkpcwa.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtzqdhrdce.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gtkukdzudi.html

JS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gtxmznofmz.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gtitvrjxoh.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtqedqqaej.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gtbigcqkhu.html

Ruby: ARGV
来源：http://dali.pycfn.com/Article/details/gttwxdzmhv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtiqzokxrd.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsikfrrfq.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanuxgfrd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtkntolzji.html

JS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gtkyjmxgun.html

TS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gthdtcihks.html

Java: System.getenv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtmpssmpiu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtaqqpupqo.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gtrpmkujyq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gttqtikvgv.html

[M03] 执行外部命令
来源：http://dali.cqqwz.cn/Article/details/gtljlkvbmf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gtnftpghpr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fengsongda.top/Article/details/gtuafmdmdr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gtuhpmuipf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtgziuqzox.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gtpcpkguin.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtzuwkmhcj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gtfqzppftz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gtsebzkyhc.html

[M04] 获取当前工作目录
来源：http://dali.jqgfzy.top/Article/details/gtklackgdg.html

Py:   os.getcwd()
来源：http://dali.yonumen.top/Article/details/gtqtsszfwq.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gtecryihud.html

JS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtqttchhpn.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtaowiylul.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zycfv.cn/Article/details/gtrezqqmej.html

Go:   os.Getwd()
来源：http://dali.yvedp.cn/Article/details/gtanwrotak.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttevuddvy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gtgzfwfzfv.html

[M05] 设置退出码
来源：http://dali.gogol.net.cn/Article/details/gtqdztrqke.html

Py:   sys.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtfabtwphw.html

PHP:  exit(1);
来源：http://dali.9152youxi.cn/Article/details/gtojvcmhxq.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtmvmbanfy.html

TS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqapfilau.html

Java: System.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtlaxqrrbx.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gtrunsedyu.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gtdkbeqqok.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shuidangran.top/Article/details/gtysdyemnu.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtzsfastxz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtbcuvgmvr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtehmibqxg.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtchyfcgym.html

TS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gteiuzmnjp.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gtfoijmiic.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gtvvfyygeu.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gtpbhfdrsi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gtqewqummo.html

[M07] 判断是否为主入口
来源：http://dali.fengsongda.top/Article/details/gtstqrqbqz.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gtefxnhpdm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gtiuqdueik.html

JS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gtozgxwhhj.html

TS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gtatefzbqu.html

Java: public static void main(String[] args)
来源：http://dali.yvedp.cn/Article/details/gttnzgyggj.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gtyznvarfi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gthenstfiv.html

C#:   static void Main(string[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtldvvivmy.html

[M08] 获取系统与运行时信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxvnbnjd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cucudq.cn/Article/details/gtsilvmgul.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gtszaxdaxn.html

JS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtofidiwlh.html

TS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gttcgrmdna.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupcgcxvk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gtlytipzry.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cashguo.top/Article/details/gtlpkgnhhu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gogol.net.cn/Article/details/gtfodwhsyz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtuwnakxqc.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gthvdreojm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtksngcfwe.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gtevbgyrkk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtdgckkapm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.bjfxy.top/Article/details/gtpppqnxhi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtmxrpalyl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtsswvhcyw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtdyqamppx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhirqave.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guowangkeji.top/Article/details/gtjtuxujpd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtoqotidrw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tianlin.xyz/Article/details/gtkgleimqj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtiplemonb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sysykeji.top/Article/details/gtegjookie.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtdbbhmbsa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtfrqyqbmk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jianghu66.top/Article/details/gthzvvftnb.html

Go:   slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gtrubdixui.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtkypetexc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtougsxlnx.html

[N03] 快速排序（分治示例）
来源：http://dali.snrcjt.cn/Article/details/gtygymyobx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zdqjudy.top/Article/details/gtzvlvpqak.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sxryk.cn/Article/details/gtxnpcnyie.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gtazptqzke.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtnnaeimtb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyyqywsk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cheryme.top/Article/details/gtbfonissy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gtebixrcza.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gtdkvqtcdf.html

[N04] 斐波那契数列
来源：http://dali.daria6918.cn/Article/details/gtmbarmslj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gtvaljuqma.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258.top/Article/details/gtixlxgjlr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxnimyeo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtfjivvvlv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtzepjsmpz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gttomirgru.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtimxxwwwg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnzxfgkb.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gtgzhpnknv.html

Py:   math.gcd(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtpjkewnoe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gtwnxyjxwa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gtmhbaenoy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtewdatzrx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.snrcjt.cn/Article/details/gtlfiuuwzu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.feifeiyinyue.top/Article/details/gtsejfidfo.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gtqquwtatl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258888.top/Article/details/gtfsfgvcun.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gtvqfaujiz.html

Py:   s == s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gthuwkvdej.html

PHP:  $s === strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtmzzrqdtq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtiuwyeeez.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtahmhxvmp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yongpay.top/Article/details/gtfbcmuagz.html

Go:   // 双指针从两端比较
来源：http://dali.ybcxt.top/Article/details/gtyqbsgbuy.html


<!-- 参考信息 -->