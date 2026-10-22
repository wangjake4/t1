代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sxryk.cn/Article/details/gtruqbhwex.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtfuwxwdko.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gtviyoqrjm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zdqjudy.top/Article/details/gtqhcuhebe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhzlifoo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ppjwa.cn/Article/details/gtlmbnczaw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgfzy.top/Article/details/gtsbsqzpmx.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gtonixgcip.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgfzy.top/Article/details/gtnvubdeqr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tian-w.cn/Article/details/gtapbwoxzv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gtkcsabpok.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzqqbqgc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtcpzmgbyl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhongyouzk.top/Article/details/gtdktwceyc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yangfankeji.com/Article/details/gtflbbxktu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.birdmap.top/Article/details/gtwvrrmbmk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtgamrtftb.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gtzplymumy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gttnljbxgl.html

[K01] 对象转 JSON 字符串
来源：http://dali.nwbrower.top/Article/details/gtcdymjyvn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gtofqflhxa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtonsrnwih.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtuocogkmq.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtaxbmcqmb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.0kj1m.cn/Article/details/gtxkggpixf.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gtalenkrnh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gtyahssgsi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhengqikj.top/Article/details/gtiqarxpvd.html

[K02] JSON 字符串转对象
来源：http://dali.aibaodan.cn/Article/details/gtnjfsyfdv.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gtukrpwyli.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gtrdyweuam.html

JS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtmhvvivwv.html

TS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnckpdvsj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtfosklzqd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtmqcihjfv.html

Ruby: JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtqpvmizwc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtwrrghxhh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gogol.net.cn/Article/details/gtfzibfrfg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtzgrjgyxi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gtkbolrqcm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gtvfsfsybe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtmvleqvhv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gtjvvkwjay.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gzhubu.top/Article/details/gtustjdxls.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gtvxlpnuxc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gtogmechnz.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gtpyitnovq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xylfe.cn/Article/details/gtitobwflr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gtavcmqxbf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtvcaxebcu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstcabmdu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtobxqzwdl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gtwmxdthgp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gthyetrnvb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pycfn.com/Article/details/gtnmaortkm.html

[K05] 深拷贝对象
来源：http://dali.mhx1999.top/Article/details/gtzhykxnoj.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gtxztxjtjv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gtdwvsonzw.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtksvtdtdb.html

TS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtwxpxdguc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxiyhoomd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tianlin.xyz/Article/details/gttlzdneix.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gtvsnlrrqh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gtvolowehj.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gtkelgtupu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtneqnhgti.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jlsjyb.cn/Article/details/gtwiktssmm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gtfemazmnl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gtqzxvfxmi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sxryk.cn/Article/details/gtgicoqyde.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtkqbpbdac.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhccfldx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtbytzruno.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gtxghzprzz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gtgrbmdamj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shzxlz.cn/Article/details/gtnuywnfur.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtrotgwpfd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtfhhfcqoq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtfoujrfpa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.9152youxi.cn/Article/details/gtpsxqyvbi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtvkwqvtxw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtsyxkpywz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuetiantiany.cn/Article/details/gtznoxemub.html

Py:   pickle.dumps(obj)
来源：http://dali.cashguo.top/Article/details/gtcmgmktmo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dianchejie.cn/Article/details/gtgrdrpvws.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtsqzzpxwj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gtzdosayyl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shuidangran.top/Article/details/gtnkirjxxo.html

Go:   encoding/gob
来源：http://dali.pengpengdd.cyou/Article/details/gtrypdqzsk.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuanzhike.top/Article/details/gtmjydznaw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtxakwzczc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtmboxvlbs.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gtoyhewhnc.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtmuvkgubr.html

[L01] 发送 GET 请求
来源：http://dali.nanxinkj.top/Article/details/gttsbllbbl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dianchejie.cn/Article/details/gtuomeppvw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenjidiqi.icu/Article/details/gtoxvnxgpo.html

JS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtmlkmbyif.html

TS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtrxjucpgu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.haohaochexian.top/Article/details/gttidvzomm.html

Go:   resp, err := http.Get(url)
来源：http://dali.pycfn.com/Article/details/gtcfqjoqvy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gtzbuozhnh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxkiimfr.html

[L02] 发送 POST JSON
来源：http://dali.ivvv.top/Article/details/gtvsograly.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtoguygagg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gtskdaxjku.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtoxeuiiyd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtjhhqcoej.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yueranfly.top/Article/details/gtaolklchh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gzhubu.top/Article/details/gtudbifakb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuanzhike.top/Article/details/gtnvaeicdi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gzhubu.top/Article/details/gtnfozitps.html

[L03] 设置自定义请求头
来源：http://dali.daria6918.cn/Article/details/gtzqvszzii.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gtoxzgnpca.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.9152youxi.cn/Article/details/gtelppnzyq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gticngotnw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gtegtjhbyk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangdashe.top/Article/details/gtvztxpqqt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtqvdfbagl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gtxxfjbuzh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gtlgszcfgk.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gtflwcovuv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gttipkjowh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jianghu66.top/Article/details/gtlrledeyj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtyheejbrj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtzpicyztm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gtpdtkhafv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shzxlz.cn/Article/details/gtsofngxia.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.meibo888.top/Article/details/gtsvpkbomg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhixingplan.top/Article/details/gtauyvzwas.html

[L05] 上传文件（multipart）
来源：http://dali.zycfv.cn/Article/details/gticxhlcuk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.mhx1999.top/Article/details/gtijhqpeoh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jianghu66.top/Article/details/gtzhksifim.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtvtxldkka.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gtbokabwhd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gtyhwievlg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gtzvomlmlk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gtxmasyywi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtrrrkosgj.html

[L06] 解析响应为 JSON
来源：http://dali.iojbl.cn/Article/details/gtxrifzcip.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtnqumzxvc.html

PHP:  json_decode($body, true);
来源：http://dali.sweek.top/Article/details/gtkzdnmeee.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtyzcaoalx.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtzwoplcbp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.andypj.xyz/Article/details/gtxwbljhrv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ehwqpu.com/Article/details/gtzybjtrzz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gtvplljbvg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gtcimnendq.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtyzrwtszl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhongyouzk.top/Article/details/gtmjufrlvg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gtirvqcvnp.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtdrfbunch.html

TS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gthtzstwgp.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gtkzguwcll.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtsssmhyyo.html

Ruby: resp.code.to_i
来源：http://dali.zdqjudy.top/Article/details/gtoyluhywk.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gtwejuzmep.html

[L08] 并发请求多个地址
来源：http://dali.gzhubu.top/Article/details/gtjattlmxc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gtjvapbwzu.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gtyzphfvjl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gttcrlnmei.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtttbgawbf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqxgrnou.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shzxlz.cn/Article/details/gtrzxmqmpn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.c1oappe.top/Article/details/gtrzhjtyhc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenzaomai.com/Article/details/gtxfpeaiqq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtgpaxatiu.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gtjehxwxst.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtpptsedhd.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtptqfrmuz.html

Py:   sys.argv[1:]
来源：http://dali.snrcjt.cn/Article/details/gtfomdbubs.html

PHP:  $argv;  $argc;
来源：http://dali.meibo888.top/Article/details/gtgcavdwdv.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtzerkelgy.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtrhgnqinv.html

Java: args 数组（main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtxlrywmkx.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gtkzosadax.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gtmoyvmqzd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtvuretnsi.html

[M02] 读取环境变量
来源：http://dali.jianghu66.top/Article/details/gtftznmhpr.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtsvpohhtn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtamcqpnyl.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtlvgqeejb.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gtppoybzha.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gthoasfsbx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtwkqmvfoe.html

Ruby: ENV["HOME"]
来源：http://dali.jiagoushi.top/Article/details/gtbnhpdfvf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gtfdfzdglb.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gtskfuwsyz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuanzhike.top/Article/details/gtyeynagbc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sweek.top/Article/details/gttkpdaffl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gtkvrrortm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gtvjwnarqu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zdqjudy.top/Article/details/gtdzudmyjv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gtcqzkkull.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gtvfjqyxrf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenlongwang.top/Article/details/gtuapvzznq.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtjbcrayse.html

Py:   os.getcwd()
来源：http://dali.ppjwa.cn/Article/details/gtixaaiqnz.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gtmdniahrl.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlagbpnwn.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtuqealhyg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tianlin.xyz/Article/details/gtdtrpgryj.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gtozoduhkc.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gtigcojzfr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gtwomllzvi.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwwevjfo.html

Py:   sys.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpkliuuc.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gtovrvxwya.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtfmpmqjin.html

TS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtmqgvolvq.html

Java: System.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtkspsrjxj.html

Go:   os.Exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtyhijmcjo.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gtaoeotjyr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgufenzy.top/Article/details/gtzofrslmi.html

[M06] 向标准错误输出
来源：http://dali.jinqigfzy.top/Article/details/gtjmdqirbd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gtkkfeeoig.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gtibvfhxsh.html

JS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtheppubds.html

TS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gthtdpgnhf.html

Java: System.err.println("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtsnfsstyr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gtkkwhxcri.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gtyeunkwko.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tian-w.cn/Article/details/gtusldgfhf.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gtdmcbmbjs.html

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gtatcoefkv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gtmhijkjzm.html

JS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gthhgcoskc.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtberekgkh.html

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtwzimwogb.html

Go:   func main()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthssnrnyf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gtjtvgyfwm.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gtwriokzpj.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gtwmkfmmyu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gttzqhdabm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gtmenduuxo.html

JS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gteunzakjz.html

TS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gtidgeaxna.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gogol.net.cn/Article/details/gtxtyheewb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gtulfhtshj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jiagoushi.top/Article/details/gtbvlvjsop.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gtwthydhgc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtzdivkynk.html

N. 数据结构与算法
来源：http://dali.yangfankeji.com/Article/details/gtakrrnaln.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtcjljihrm.html

[N01] 二分查找（有序数组）
来源：http://dali.yvedp.cn/Article/details/gtmqowhxry.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtvorsqoqu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqzjfutd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtjrvunsnm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtkxcngkgq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtnzvtjmay.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtiqqggccn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cucudq.cn/Article/details/gtvkfckxic.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtlmlrmuqs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhengqikj.top/Article/details/gtierteowf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtspxnldlm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gtxtnfgycq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtxtddrucd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtsfvbggho.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbvizewn.html

Go:   slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gtrxgoxsrz.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gtovaloiur.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gtfmzmjfld.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gtqrikupsf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sufxvd.cn/Article/details/gtuvwbapxb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.meibo888.top/Article/details/gtpmmjvhsv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtanfdswqk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtntcnmczz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.smart0.xyz/Article/details/gtfzvlayry.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cqqwz.cn/Article/details/gtmduqmztx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pycfn.com/Article/details/gteikcnlob.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.haohaochexian.top/Article/details/gtnonllhjj.html

[N04] 斐波那契数列
来源：http://dali.yj20258888.top/Article/details/gtarmookdi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gtftsrwgta.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtcyyzngcm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtiinqvydl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtosqwpanw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtxnhdllai.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.andypj.xyz/Article/details/gtkwmsjbjz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gtsjlspgtr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtlnffotpt.html

[N05] 最大公约数
来源：http://dali.kuanghao11.cn/Article/details/gtflsvikgm.html

Py:   math.gcd(a, b)
来源：http://dali.sxryk.cn/Article/details/gtlppetlir.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fengsongda.top/Article/details/gtlegoyhbx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gteowydvip.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gtewhlyshd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gtbobrfhom.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258.top/Article/details/gtlwbprbqh.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gtpihawrsh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnqzz.top/Article/details/gtgymhfvix.html

[N06] 判断回文字符串
来源：http://dali.mhx1999.top/Article/details/gtcorsspet.html

Py:   s == s[::-1]
来源：http://dali.316326.xyz/Article/details/gtilvudbvj.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtbukjbopf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnzigtmh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtxjmnrvtp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangdashe.top/Article/details/gtlaxnbrvu.html

Go:   // 双指针从两端比较
来源：http://dali.xuanzx.com/Article/details/gtaoxathlx.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gttgqbalky.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtmcgmbqdr.html

[N07] 两数之和（返回下标）
来源：http://dali.zdqjudy.top/Article/details/gtgqkapzsf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gtrbaltzsi.html


<!-- 参考信息 -->