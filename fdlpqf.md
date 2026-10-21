代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gtfpvglpbr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cdnleiting.top/Article/details/gtqeupojqt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tianlin.xyz/Article/details/gtcvhnsxgy.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtyfllccdj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gtvtyjwjup.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gtliewsobl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gtayondojf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aizwys.cn/Article/details/gtskwfokrg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqywlunjd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hfpthk.cn/Article/details/gtknmmuuve.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gtbqiuviwd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nwbrower.top/Article/details/gtugbenexf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtqrsgsbfo.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gtxnlamwin.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gttqtmasme.html

[K01] 对象转 JSON 字符串
来源：http://dali.snrcjt.cn/Article/details/gtqlkyqdzg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtecydtzoo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtllzpddne.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtdgnbhojn.html

TS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gttjwfbgxr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.kuanghao11.cn/Article/details/gtywnybuwh.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqejgdef.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangshuangyany.cn/Article/details/gtjbfikwht.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.meibo888.top/Article/details/gtvckbvura.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gtaxvbhwko.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gtgfhyghgf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gtbejhqwjo.html

JS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtaupdwybc.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtmmrmaehn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.birdmap.top/Article/details/gtmngcfpgx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfoaiwzb.html

Ruby: JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtzingrdta.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhongyouzk.top/Article/details/gtvhyxwwpc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ehwqpu.com/Article/details/gtxdqrzhqi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtzibkcuef.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gtimkkfmre.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtufokhtqy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtzrouhxuy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtgzmdhoay.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnxiangtu.top/Article/details/gtcvxviqfv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aizwys.cn/Article/details/gthzoxkjki.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigfzy.top/Article/details/gtejoucoje.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gtfmgykwck.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gtrkgcdxpu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jianghu66.top/Article/details/gttwygwquq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gttvfmkasf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gtqcixhjma.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtppgkhjqz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtjtikwiyl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtqshmqzsr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtwbzcmqzb.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gtwxlijxgc.html

Py:   copy.deepcopy(obj)
来源：http://dali.cqqwz.cn/Article/details/gtnubwjtdz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gtowvjwlqf.html

JS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpihhscy.html

TS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gtwqxocpxs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtcxovjrrl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gzhubu.top/Article/details/gtulhbwsiw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sxryk.cn/Article/details/gtugnccjwj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcduhcwat.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gtzdsfblba.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gtjlfnfaxd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gtdlairtvr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gtsksuzuka.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtqawzjgbc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.snrcjt.cn/Article/details/gtsipldwxe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtlcnbpxnk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtaxifsuks.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtaxzbtoby.html

[K07] 进制转换
来源：http://dali.0kj1m.cn/Article/details/gtzjjquqee.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtzmsokcwf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ehwqpu.com/Article/details/gtljjtourj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtuqganwte.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtrhjjicux.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gthxdjbdob.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gtpvxxknqg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gtmyvjzkul.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtcuahppmt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gogol.net.cn/Article/details/gtokfmjkei.html

Py:   pickle.dumps(obj)
来源：http://dali.dianchejie.cn/Article/details/gtszxktnna.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenzaomai.com/Article/details/gtdvfvedhx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtgzlnnkuj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtgrudjlym.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtitcmxmrl.html

Go:   encoding/gob
来源：http://dali.cdnleiting.top/Article/details/gtdepdqppk.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtmmvlbnxt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtsidwoyxb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtcahilqcr.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gtgxngtgft.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtblnvrjhy.html

[L01] 发送 GET 请求
来源：http://dali.ppjwa.cn/Article/details/gtukzrhlfi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daria6918.cn/Article/details/gtbokuaawn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xylfe.cn/Article/details/gtyffwhxrv.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtmushhiku.html

TS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtqpncxege.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gtoosvpuez.html

Go:   resp, err := http.Get(url)
来源：http://dali.iojbl.cn/Article/details/gtvyhzzgik.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gthvgwlhrp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuxming.cn/Article/details/gtsesjytre.html

[L02] 发送 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gturqsbvvd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtqqrgqber.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yangfankeji.com/Article/details/gtxghmpagm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gtnuayzugk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtvzxjnyvh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtdsnanqpz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gtpwkyjzzq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.mhx1999.top/Article/details/gtjfuaxydg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsewqwwk.html

[L03] 设置自定义请求头
来源：http://dali.quarkkingdee.top/Article/details/gtueipwrdf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxinkj.top/Article/details/gtvdinnyrw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gtnseszmmm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtfitlbgpa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtdchngxhb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yongpay.top/Article/details/gttxhjatge.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gthdhebmft.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yanxiufei.cn/Article/details/gtnlmljxhd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gtjpjtsszr.html

[L04] 设置超时
来源：http://dali.cashguo.top/Article/details/gtnfwmbpfz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aizwys.cn/Article/details/gtpnwkqpsl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gtmnwdmsux.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtuwduvipr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtnwzwzaso.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gtoiwmhuxr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jyoumei.cn/Article/details/gtsqrtxawe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangdashe.top/Article/details/gtxvmhllcn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gtqprsxwpl.html

[L05] 上传文件（multipart）
来源：http://dali.xinyue.icu/Article/details/gtblvjshvv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigfzy.top/Article/details/gtlezftifx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jianghu66.top/Article/details/gtplftuiqs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gtueijtbiy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtztnltpyo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.birdmap.top/Article/details/gtlsjexbws.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gtnfbhhyju.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gtzryujrvl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj202588.top/Article/details/gtnxdneouu.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gtpndojdrb.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gtvzvmfbwj.html

PHP:  json_decode($body, true);
来源：http://dali.yongpay.top/Article/details/gtgpexdesp.html

JS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtrhtsnyge.html

TS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gttqojwrgt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtofigwpvu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ybcxt.top/Article/details/gtfgpwbrwc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gzhubu.top/Article/details/gtlqjocxyh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tanke756.top/Article/details/gtcxrxfiuh.html

[L07] 处理 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gtptvsyhlh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gtobiigovc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yanxiufei.cn/Article/details/gtjrhuamjg.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtwuqmsygh.html

TS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gttryshxcu.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gtxgaigrsn.html

Go:   resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtayrdqcqk.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gthymsqlzx.html

C#:   (int)resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gttehqudll.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gtwquzgeva.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gtrpnuitog.html

PHP:  curl_multi_init() 系列
来源：http://dali.hywenlv.cn/Article/details/gtateayxoj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtqmhsxhbl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtdrrinosq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gzhubu.top/Article/details/gtdcqlukgi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gtibndqkzh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guowangkeji.top/Article/details/gttjvgfgki.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtsygqufkn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtrlbcspet.html

M. 命令行 / 进程 / 环境
来源：http://dali.gogol.net.cn/Article/details/gtaacyduii.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtksvjitcc.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gttehxedqr.html

Py:   sys.argv[1:]
来源：http://dali.shzxlz.cn/Article/details/gtdadeuxiz.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gtzqtskxdk.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gttowydoin.html

TS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gtuoklvbpo.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrgwkwdx.html

Go:   os.Args[1:]
来源：http://dali.sweek.top/Article/details/gtibfftxfk.html

Ruby: ARGV
来源：http://dali.tianlin.xyz/Article/details/gtnhqdoxld.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtsljnueke.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtshvjlfgb.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtyulpptcy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtomlwbxiv.html

JS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtlqojhywl.html

TS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtlvupiqml.html

Java: System.getenv("HOME")
来源：http://dali.cashguo.top/Article/details/gtdiktmfqq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtufynybxj.html

Ruby: ENV["HOME"]
来源：http://dali.shzxlz.cn/Article/details/gthrdwfyxv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnqzz.top/Article/details/gthrcqgudd.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gtbcmlsdov.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yongpay.top/Article/details/gtjveeoxck.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cucudq.cn/Article/details/gtysrpinam.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gtxlsihuzy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtgbjhpwxw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuanzhike.top/Article/details/gtcfktenjt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fzhhl.top/Article/details/gtgwalqazs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nwbrower.top/Article/details/gtyrjmmdcu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhiwuduotai.top/Article/details/gtdzxdvyqs.html

[M04] 获取当前工作目录
来源：http://dali.nanxinkj.top/Article/details/gthayondhq.html

Py:   os.getcwd()
来源：http://dali.cashguo.top/Article/details/gtfgprmwnj.html

PHP:  getcwd();
来源：http://dali.fzhhl.top/Article/details/gtlxqydnlf.html

JS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtbitxmgad.html

TS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gteeefxjjz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gtzqhjkjjl.html

Go:   os.Getwd()
来源：http://dali.wangdashe.top/Article/details/gtdxnhidup.html

Ruby: Dir.pwd
来源：http://dali.tian-w.cn/Article/details/gtnkivktik.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hywenlv.cn/Article/details/gtbtybpvdw.html

[M05] 设置退出码
来源：http://dali.ehwqpu.com/Article/details/gtkgmqfonr.html

Py:   sys.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtzxparnyp.html

PHP:  exit(1);
来源：http://dali.jiagoushi.top/Article/details/gtyytcxjwb.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtrnwvfbjj.html

TS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtjuabuyrm.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtdnoxmdth.html

Go:   os.Exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtjiflgelv.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gtgfblhamb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhengqikj.top/Article/details/gtrkcjoubz.html

[M06] 向标准错误输出
来源：http://dali.jlsjyb.cn/Article/details/gtoioscfab.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtttwhemhm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sysykeji.top/Article/details/gtcombkbnn.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtjczsaclf.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gtbgupohha.html

Java: System.err.println("err")
来源：http://dali.daria6918.cn/Article/details/gtacipbcft.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gtvjlppwlg.html

Ruby: warn "err"
来源：http://dali.zhongyouzk.top/Article/details/gtugkyidcq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gtzlavxncv.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gtogquktai.html

Py:   if __name__ == "__main__":
来源：http://dali.kuanghao11.cn/Article/details/gtymdmgmcv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gteeljhyjj.html

JS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gteggckqkh.html

TS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtprhrzuyx.html

Java: public static void main(String[] args)
来源：http://dali.yj20258888.top/Article/details/gtcvozpscm.html

Go:   func main()
来源：http://dali.c1oappe.top/Article/details/gtimitxwkq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gtaudnaokr.html

C#:   static void Main(string[] args)
来源：http://dali.dashuyun.cn/Article/details/gtathhgzam.html

[M08] 获取系统与运行时信息
来源：http://dali.cqqwz.cn/Article/details/gtjfieoeke.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tian-w.cn/Article/details/gtwwfxfwux.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aibaodan.cn/Article/details/gtcoqckvdm.html

JS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtugarxfzh.html

TS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gtyjhmegjy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.birdmap.top/Article/details/gtrsjcvapj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gtmzslsesy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gtjxbwwllq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhoulong.xyz/Article/details/gtsmxpvgws.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjutfbuqd.html

N. 数据结构与算法
来源：http://dali.iojbl.cn/Article/details/gtfqqohdah.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtjzcvabtb.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gtgapytzbt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtnrqiuokj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtrtemwpes.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvyzcskr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtsavcnfcd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtmldnasoi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtpkdnepak.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuanzx.com/Article/details/gtuzgrtugl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtybvbpcwl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gtxwnolbta.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gttcmoxzcf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhixingplan.top/Article/details/gtyafywgcu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoucccost.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gteitxpjcm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gtwzelzfcn.html

Go:   slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtedpqblls.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtquvrimme.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnxiangtu.top/Article/details/gtfllynhdc.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gtygnilyay.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhengqikj.top/Article/details/gtfchrxrvn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gtgtgetbeh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtpsailgql.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtetdyeskd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fzhhl.top/Article/details/gtzjwgtlgo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgufenzy.top/Article/details/gtswzagbkg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.mhx1999.top/Article/details/gtmleoikip.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqaebdjl.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggncyijl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtjsufrhrl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcrtbgov.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtwvxnvnfn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtaukzumde.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gtsfcckllm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cqqwz.cn/Article/details/gtbaqfrjow.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtwgpeqnjn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtfumaxhff.html

[N05] 最大公约数
来源：http://dali.nanxinkj.top/Article/details/gtabfvvvxo.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gtfpmpqrfo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guowangkeji.top/Article/details/gthglwmilc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtbdyfsqwv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gtyxwhzqsl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sysykeji.top/Article/details/gtcetuvhao.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.feifeiyinyue.top/Article/details/gtkzsefdop.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gtgzxuwxui.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ydzc1.top/Article/details/gtbtbhdcou.html

[N06] 判断回文字符串
来源：http://dali.shzxlz.cn/Article/details/gtxhdxxtzl.html

Py:   s == s[::-1]
来源：http://dali.316326.xyz/Article/details/gtmhmmpwnz.html

PHP:  $s === strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtxiybtpyt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtripuylrc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtbkwekfrh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgfzy.top/Article/details/gtkyqgcnun.html

Go:   // 双指针从两端比较
来源：http://dali.jqgufenzy.top/Article/details/gtjrahjxfo.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gtwccilfle.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtmaxbztur.html

[N07] 两数之和（返回下标）
来源：http://dali.cashguo.top/Article/details/gtxcwosxxo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gtsigicanv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fzhhl.top/Article/details/gtfmgnadee.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gtwawpufjh.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuanzx.com/Article/details/gtuegpjttz.html

Java: // 手写 HashMap
来源：http://dali.iojbl.cn/Article/details/gtoqlkhxlf.html


<!-- 参考信息 -->