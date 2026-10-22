代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hysaishi.cn/Article/details/gtsatfltny.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gtldjlbxek.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gtmslhyexh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jiagoushi.top/Article/details/gtegetclmt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgufenzy.top/Article/details/gtlepcxkcl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gtbfhoamac.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtfoqnhgar.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gtvndayauy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.haohaochexian.top/Article/details/gtfqslcclr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gtinmuelkx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gtmxrggavn.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gtenqfpxkp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gtylgfgeql.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gtsvnppzuh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ehwqpu.com/Article/details/gtasosclva.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guannengcc.top/Article/details/gtffssnwze.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hammf.cn/Article/details/gtijatbpmk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinghuilouyu.cn/Article/details/gtryrjqcpz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.vqdsnc.cn/Article/details/gtqmmpfylp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gtreyczqjn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtdrinbtcl.html

K. JSON 与序列化
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvluzsmu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtflwhfcgj.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gtlzjnihnk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtmdxgewbo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzmggrfe.html

JS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtkfcroxlg.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtcrrkillc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gaohongyu789.top/Article/details/gtcjuvbuir.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtnpvgipdf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gtlimtohlc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtdjdkpheg.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gtcgjvprmp.html

Py:   json.loads(s)
来源：http://dali.cqqwz.cn/Article/details/gtncdmxxui.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sweek.top/Article/details/gtztvzxwey.html

JS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtjmvmsgip.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtwxgggikl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gtqvjosayp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwifkzrpi.html

Ruby: JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxouodfa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gticbqcbvv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxinkj.top/Article/details/gtjdweaxgz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtxwdbaqww.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gtsdihypqd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtxeofxnzz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtsehqbrel.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtnmmglgjy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gtuovwvgrv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpywzqfgk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gtrnxiwadu.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gtmfjajjat.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhengqikj.top/Article/details/gtjwwlpkex.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gtzyuazxvk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtiswfykrx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltjrasij.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daxiang520.top/Article/details/gtcyqakicp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtbdroxlor.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gttfonosge.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtexvuaqci.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gtmwawdahr.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gteudodvfo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gtqddsfipm.html

JS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtrfoyvvqh.html

TS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtnoulabko.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hammf.cn/Article/details/gtzdpchpzp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gtjnvyztno.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gtowqnrzyt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dashuyun.cn/Article/details/gtrzdocpvn.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gtfnbckmyz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gtowdrmitu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jiagoushi.top/Article/details/gtafoqikft.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtpcnwqrwi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtkmweedkt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gtmgelxqao.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtdbejykyy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtxwmfdfqi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtsterrgue.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gttckymmdi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtoftjpkgd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yanxiufei.cn/Article/details/gtejzxvpzv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtopvlwtke.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtovegsmrn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtfczppsxb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gtswdittzd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guowangkeji.top/Article/details/gtbficrtpb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtmmqrnhoh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.birdmap.top/Article/details/gtghuudezx.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gtmvkosfir.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gzhubu.top/Article/details/gtmzepxatn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtgwcfnais.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gtfryvcvxc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yueranfly.top/Article/details/gtbtrjtqhe.html

Go:   encoding/gob
来源：http://dali.pengpengdd.cyou/Article/details/gtqebubnfu.html

Ruby: Marshal.dump(obj)
来源：http://dali.shuidangran.top/Article/details/gtgidyqlrw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtegzyvkwk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtnpmummgn.html

L. 网络请求
来源：http://dali.9152youxi.cn/Article/details/gtoufkifpl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtpjauolef.html

[L01] 发送 GET 请求
来源：http://dali.aibaodan.cn/Article/details/gtvrxzpajh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gtoqffguzi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfaotyrhr.html

JS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gtyinmkngm.html

TS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtixyqxvcz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gtpjzhegyb.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gtnfxwevql.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gttndxxhlx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gterlaqjep.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtyozwdyhg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gtnodbfwuc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daria6918.cn/Article/details/gtntepxwzd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gtyqgwjeku.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gtinpyhbor.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ehwqpu.com/Article/details/gtdvtlyjkz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fzhhl.top/Article/details/gtfdgguiuo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yvedp.cn/Article/details/gtxhqzjmmk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nwbrower.top/Article/details/gthhlaajck.html

[L03] 设置自定义请求头
来源：http://dali.pycfn.com/Article/details/gtczclirrd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjcdenwo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.kuanghao11.cn/Article/details/gtlstdvjlc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtntdgjbgg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gtkamxbhad.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shuidangran.top/Article/details/gtoagmocly.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gtmiexnfwq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gtwlzqeutp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtmdyuwwbw.html

[L04] 设置超时
来源：http://dali.hnxiangtu.top/Article/details/gtuetdygcr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gtnldxiorz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tanke756.top/Article/details/gtavkeeapf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtpekcpwix.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gtdkpfyiqs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gtfiwehpll.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gtfmimsdtw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.kuanghao11.cn/Article/details/gtwdstggpj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gtawmrhxzg.html

[L05] 上传文件（multipart）
来源：http://dali.hammf.cn/Article/details/gtwasdoldu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cashguo.top/Article/details/gtciyqcbwk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shuidangran.top/Article/details/gtcffsetdz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtevwsohqw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gtlpgwohqc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgufenzy.top/Article/details/gthsmxigtm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gtyjfedfxb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangdashe.top/Article/details/gtljyzqinl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtocxuxkgk.html

[L06] 解析响应为 JSON
来源：http://dali.tian-w.cn/Article/details/gtihqgwbax.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtdmqhuxil.html

PHP:  json_decode($body, true);
来源：http://dali.hysaishi.cn/Article/details/gtnqkkzfvr.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtvymofvks.html

TS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gtpaatwinl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.havefunace.top/Article/details/gtathwqkev.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gtandthxzf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gtuecqqlio.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hywenlv.cn/Article/details/gtksmfjgna.html

[L07] 处理 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtdfetjmbn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenlongwang.top/Article/details/gtvgodbooq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gthiykrdkv.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtmdaayhdu.html

TS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtwvswnbzy.html

Java: resp.statusCode()
来源：http://dali.zhengqikj.top/Article/details/gtckesivfy.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gthdnavros.html

Ruby: resp.code.to_i
来源：http://dali.gotoacloud.top/Article/details/gtkeuvllbd.html

C#:   (int)resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gtsktlpbbb.html

[L08] 并发请求多个地址
来源：http://dali.hysaishi.cn/Article/details/gttshzlbfo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cheryme.top/Article/details/gtuczxvkld.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gtlmfuqbyo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtytmgywmx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytdmotcv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gtktauzssc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hfpthk.cn/Article/details/gtzrxspqtu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuxming.cn/Article/details/gtybvhqmlt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cdnleiting.top/Article/details/gthjuejxkp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtyhfwpfpx.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuxming.cn/Article/details/gthvhvrphg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtpzyyfisn.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gtuvcvblch.html

Py:   sys.argv[1:]
来源：http://dali.smart0.xyz/Article/details/gtfbxzwbnw.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gtgsueundw.html

JS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtobrxvzmu.html

TS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtixbmfgjc.html

Java: args 数组（main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gtpglhrbsh.html

Go:   os.Args[1:]
来源：http://dali.ppjwa.cn/Article/details/gthfoynfat.html

Ruby: ARGV
来源：http://dali.hammf.cn/Article/details/gtoqesmuhj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtmyljhfvj.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gtcxogejvz.html

Py:   os.environ.get("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtfpqhqwzu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtqscknsks.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtqdyfgxap.html

TS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtvtnetfey.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gtuchphdnh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvwdfxzk.html

Ruby: ENV["HOME"]
来源：http://dali.gotoacloud.top/Article/details/gtrfwcnqou.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtutgdufzq.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gtqcqcivtq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gttqopodec.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zycfv.cn/Article/details/gtxhdhplbc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtrgbdyens.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gtvpkfodbk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.9152youxi.cn/Article/details/gtcmddiekp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gtzcwoojvb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gtsbbnfjif.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xinyue.icu/Article/details/gtezttcssn.html

[M04] 获取当前工作目录
来源：http://dali.hysaishi.cn/Article/details/gtrpyfggzd.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtegbkjbgm.html

PHP:  getcwd();
来源：http://dali.yanxiufei.cn/Article/details/gtivfmasze.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtrmbbzgqo.html

TS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gtuszpfipe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shzxlz.cn/Article/details/gtgadocgfc.html

Go:   os.Getwd()
来源：http://dali.smart0.xyz/Article/details/gtnnxyawcd.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gtvmvcpvtc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.mhx1999.top/Article/details/gticeefufv.html

[M05] 设置退出码
来源：http://dali.daria6918.cn/Article/details/gtjkoqkahb.html

Py:   sys.exit(1)
来源：http://dali.yongpay.top/Article/details/gthcoakbxf.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gtshvtsyvf.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtmidcddim.html

TS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtmdvfvcnd.html

Java: System.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtktilwxkn.html

Go:   os.Exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtiaxmkyuu.html

Ruby: exit 1
来源：http://dali.daria6918.cn/Article/details/gtoxtqkilv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nwbrower.top/Article/details/gtntgxefuo.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gtblfyavxq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtzkrcpmrv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gtgdouocrr.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtidxecoqz.html

TS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gttgmcxsxq.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtbpknhkfl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.snrcjt.cn/Article/details/gteqzsukak.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gtbjmptypa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gtejeoycyo.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gtkflkyspq.html

Py:   if __name__ == "__main__":
来源：http://dali.pycfn.com/Article/details/gtgnhfoxxx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj202588.top/Article/details/gtdofwbpxr.html

JS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtwdxxbjlb.html

TS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gttwdgdanf.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gthkapjaij.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gtzortlgtt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.birdmap.top/Article/details/gtdzoeypez.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gtpiqtqcra.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gtsfcczkhe.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gttrdrtfax.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.redwolf501.top/Article/details/gtmndssjhh.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtxzvldsbr.html

TS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtacpcmmhl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ppjwa.cn/Article/details/gtpnawyetw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtteurftuu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhoulong.xyz/Article/details/gtgltpygtv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzihifvv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthktebmtz.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gttbuhupft.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtlvmfxkum.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gtmiavkato.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtzxeoflvo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtgcxvvklc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtypcswcig.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gtavgivhwn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtgunfxswe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gttagfzulo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gtytqdfbij.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtoizgykwk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shzxlz.cn/Article/details/gtwpobkhca.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtftekicwh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtnpjnphti.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtnlxrpotw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtcujllssd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gtpjcwjiph.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtclfgabbl.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtxpuuwyar.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gtbwoyusoi.html

[N03] 快速排序（分治示例）
来源：http://dali.sysykeji.top/Article/details/gtticietwd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gtdfcbcjbb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hysaishi.cn/Article/details/gtqkvatilp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gtwblecqnl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gttwnuglwp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gtarwleyog.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ybcxt.top/Article/details/gtnhwpbrqg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.kuanghao11.cn/Article/details/gtogrswlne.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dianchejie.cn/Article/details/gtbzrcjogi.html

[N04] 斐波那契数列
来源：http://dali.ybcxt.top/Article/details/gtxofxabli.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrritwnke.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtyamboflg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtljwipebh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtqpfzdnfz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtcouwcbuc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxinkj.top/Article/details/gtydsrmoya.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gtyoibkbgr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtsupgcjtz.html

[N05] 最大公约数
来源：http://dali.cucudq.cn/Article/details/gtjhiyohxr.html

Py:   math.gcd(a, b)
来源：http://dali.nwbrower.top/Article/details/gtykwtadrr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gtbnazgjph.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gtiqggkyxn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtamizotpb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gtzilzernz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gtipubrwnr.html

Ruby: a.gcd(b)
来源：http://dali.aizwys.cn/Article/details/gtvcyyqwap.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gtsfgoxlvm.html

[N06] 判断回文字符串
来源：http://dali.yueranfly.top/Article/details/gtmnvsxrbd.html

Py:   s == s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtmsrdojkl.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtepgswecb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtlhjpzjju.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtwpohothh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gtabjzdhzv.html

Go:   // 双指针从两端比较
来源：http://dali.nwbrower.top/Article/details/gtqlaqsrrg.html


<!-- 参考信息 -->