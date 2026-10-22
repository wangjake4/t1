代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gt2qcueuidf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cqqwz.cn/Article/details/gt2xoesqobk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2svrlxwxw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2icrkxzav.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hywenlv.cn/Article/details/gt2rxgmixjj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fengsongda.top/Article/details/gt2zzgvdysd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gt2irucrgsq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gt2tickobld.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2tftdpqua.html

K. JSON 与序列化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kyjurhuz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2tlokqwwh.html

[K01] 对象转 JSON 字符串
来源：http://dali.xinyue.icu/Article/details/gt2mkiecwqq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gt2fyfrfkoq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gt2btfmmgap.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gt2uudatujo.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gt2reymurgq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daxiang520.top/Article/details/gt2asuexsyj.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gt2zvyzmjar.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gt2derjanix.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xuuebfia.html

[K02] JSON 字符串转对象
来源：http://dali.yonumen.top/Article/details/gt2vkzhiprf.html

Py:   json.loads(s)
来源：http://dali.gogol.net.cn/Article/details/gt2ielfapzj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sdlxaodf.html

JS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gt2ncbprjzo.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2ymskdgnu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jyoumei.cn/Article/details/gt2tekgklge.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2ifsafpxm.html

Ruby: JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2frmhesiv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zsuubbum.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pycfn.com/Article/details/gt2qfjshwns.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gt2ezjjjjnj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gt2wstprlqn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2jcdqcjxa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2ufuicbtg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daxiang520.top/Article/details/gt2fzndjzdq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yongpay.top/Article/details/gt2jrhqsylw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gt2bivdoxrt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yueranfly.top/Article/details/gt2cdyxctlm.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gt2rdgjrshb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnxiangtu.top/Article/details/gt2eosuncfr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gt2gdaspkgh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gt2epregyvy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2gosuxudr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xziqi.cn/Article/details/gt2aaevinua.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gt2hayuhjtv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gt2mxmfuupp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gt2wtjxnskj.html

[K05] 深拷贝对象
来源：http://dali.yanxiufei.cn/Article/details/gt2odromfzi.html

Py:   copy.deepcopy(obj)
来源：http://dali.tanke756.top/Article/details/gt2abhnaqcy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shzxlz.cn/Article/details/gt2jgbmtjcn.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gt2svnshghj.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gt2ayruwgoy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cheryme.top/Article/details/gt2uqrdvzya.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.havefunace.top/Article/details/gt2rormxfwx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gt2vqmeamsw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.9152youxi.cn/Article/details/gt2mgnlgitu.html

[K06] 解析 URL 查询串
来源：http://dali.ppjwa.cn/Article/details/gt2ptbaooim.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gt2balththq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jyoumei.cn/Article/details/gt2rkzvopvj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gt2nsiwiyju.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2jquxdlte.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sxryk.cn/Article/details/gt2vguadurm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2cikbfvpc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gt2ujwdvsek.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2xotirrdz.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gt2dalgeqec.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2lfmkxwsa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tanke756.top/Article/details/gt2cmloerbt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2qwlkettn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2xdvjtige.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2sxvcdvuu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.quarkkingdee.top/Article/details/gt2lfqlmlff.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gt2czhlhbyr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2werntnvt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.9152youxi.cn/Article/details/gt2htzxrdhb.html

Py:   pickle.dumps(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zkprkqbc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxinkj.top/Article/details/gt2iuabtviz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2avqbylyv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gt2oqdtsebz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sxryk.cn/Article/details/gt2liqrmpyh.html

Go:   encoding/gob
来源：http://dali.gzhubu.top/Article/details/gt2mcyujyon.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ugxzpscj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gt2qqgmyslr.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdkaohuc.html

L. 网络请求
来源：http://dali.guowangkeji.top/Article/details/gt2xojhcbqm.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2onpusfgp.html

[L01] 发送 GET 请求
来源：http://dali.meibo888.top/Article/details/gt2sglbpwpp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dianchejie.cn/Article/details/gt2xuheoxhf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigufen.top/Article/details/gt2fiwirrtt.html

JS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2spvnfgfu.html

TS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gt2esddcmak.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hongshengwenyu.top/Article/details/gt2rxykmglm.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2obxkalyg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gt2bidjkkso.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2xzuxizss.html

[L02] 发送 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gt2illnajdk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gt2cirprylz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuanzx.com/Article/details/gt2kimbsjjp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xzmfewtc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gt2ccnqmorh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gt2ylmsznoi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gt2gbvqftev.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gt2pjeljrda.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2xgmokjoq.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkpoqvth.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cashguo.top/Article/details/gt2ceqcowpw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dianchejie.cn/Article/details/gt2lnahflet.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmftemrs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2dnlwstrz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2shnaosnn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ndtjvohj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gt2mlacjynp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gt2kgkmsgkj.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gt2xzpjbrac.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ydzc1.top/Article/details/gt2osxdolen.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umizhqjc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gt2pdiipztd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rintgaqh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gt2hrkeoomq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258888.top/Article/details/gt2algyfpvv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yongpay.top/Article/details/gt2hbstraiw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gt2bescwndy.html

[L05] 上传文件（multipart）
来源：http://dali.cqqwz.cn/Article/details/gt2enupaefb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jiagoushi.top/Article/details/gt2xwrcpcve.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jiagoushi.top/Article/details/gt2ruoyfwqn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gt2yqkfzitv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ywnvhrej.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gt2qhvmlcjo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2bawnjhlz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nwbrower.top/Article/details/gt2ppectdog.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2rfdwhjwx.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gt2hitutbza.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gt2gxkylfbr.html

PHP:  json_decode($body, true);
来源：http://dali.havefunace.top/Article/details/gt2eptpyura.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2zctbxdxr.html

TS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gt2oxhwwhag.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2inepznwj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigufen.top/Article/details/gt2hnidnadk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.smart0.xyz/Article/details/gt2jtbzhaxo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gt2rziqwikd.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gt2yuwgngxv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yonumen.top/Article/details/gt2vyvehvsp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj202588.top/Article/details/gt2uxhpogjn.html

JS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gt2jgeshxku.html

TS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gt2hzvbibin.html

Java: resp.statusCode()
来源：http://dali.andypj.xyz/Article/details/gt2draifjdk.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gt2apfkiwfw.html

Ruby: resp.code.to_i
来源：http://dali.vqdsnc.cn/Article/details/gt2coaoydeq.html

C#:   (int)resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gt2bsqxwigp.html

[L08] 并发请求多个地址
来源：http://dali.dianchejie.cn/Article/details/gt2hbybrsip.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gt2kycdsonz.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gt2fepfovlo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2uyqbvgdp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gt2qbqrijzc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gt2bhaoanjw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnxiangtu.top/Article/details/gt2mzarugay.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.andypj.xyz/Article/details/gt2ohtaxedt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2fzwtqjlx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2zayggiuu.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gt2ujcusjpt.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2qnwimisk.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gt2saesrpzw.html

Py:   sys.argv[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vodzipox.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xalwoefu.html

JS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gt2uxmdyrmx.html

TS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gt2ojlvzphd.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gt2jujyxyrg.html

Go:   os.Args[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxdkzzyz.html

Ruby: ARGV
来源：http://dali.birdmap.top/Article/details/gt2aboeyylt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2ajyxakqw.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2fidkhgtc.html

Py:   os.environ.get("HOME")
来源：http://dali.smart0.xyz/Article/details/gt2lxhnxntu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gt2wqwbogaz.html

JS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gt2ueaxhicx.html

TS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gt2ggzmtxec.html

Java: System.getenv("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2ghhfbtxu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hammf.cn/Article/details/gt2abqhffqr.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gt2jvopumtf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2amcmzphz.html

[M03] 执行外部命令
来源：http://dali.wangdashe.top/Article/details/gt2imrsozyd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gt2aqjqezxk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gt2kbkonsqx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gt2qqezinzg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gt2sulihmap.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wtbljflr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.feifeiyinyue.top/Article/details/gt2oeaqiaix.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xylfe.cn/Article/details/gt2dvjwcaks.html

C#:   Process.Start("ls", "-l");
来源：http://dali.iojbl.cn/Article/details/gt2kpvsierr.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gt2nsmxmmej.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gt2prekncna.html

PHP:  getcwd();
来源：http://dali.ehwqpu.com/Article/details/gt2jnndegje.html

JS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2gopvchyi.html

TS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gt2aetvjgtj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.vqdsnc.cn/Article/details/gt2qdphfyou.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2voelkliu.html

Ruby: Dir.pwd
来源：http://dali.nanxinkj.top/Article/details/gt2wyelrrfw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sweek.top/Article/details/gt2vtcsvgjx.html

[M05] 设置退出码
来源：http://dali.sxryk.cn/Article/details/gt2kifjavvb.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2xzaevnkh.html

PHP:  exit(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwvnnhhw.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2lbuplqrj.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2xliinokw.html

Java: System.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2jtipunnm.html

Go:   os.Exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2gbyuxkbh.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gt2vhbwqxqo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sxryk.cn/Article/details/gt2jewjrvrq.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htowwgao.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gt2xncuwjmx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shangyingyoupin.top/Article/details/gt2syarrjqg.html

JS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gt2vbshhjkm.html

TS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gt2lmvwivlm.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gt2mwexjpgw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.0kj1m.cn/Article/details/gt2rmtkddbn.html

Ruby: warn "err"
来源：http://dali.gzhubu.top/Article/details/gt2zmuheatm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gt2njnoowvw.html

[M07] 判断是否为主入口
来源：http://dali.kuanghao11.cn/Article/details/gt2yirfwocg.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gt2veqhnblb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aibaodan.cn/Article/details/gt2cdscfbge.html

JS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gt2yvacmhmr.html

TS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gt2dthxagaw.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gt2yatkwoke.html

Go:   func main()
来源：http://dali.jqgfzy.top/Article/details/gt2pszptcdd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gt2dwlhzhus.html

C#:   static void Main(string[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gt2onegwvfb.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gt2xvcbykmo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gt2gtvnszvo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gt2gpvvbrkl.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eqlhebzo.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gt2ahdbxhtb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gt2hsrzwnwl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ehwqpu.com/Article/details/gt2uewotsnt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cdnleiting.top/Article/details/gt2rfbjtkrw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hfdaigyb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tuprivbb.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gt2omumraub.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2lzgzgotg.html

[N01] 二分查找（有序数组）
来源：http://dali.feifeiyinyue.top/Article/details/gt2nohzezpv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2gektliqk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2xbinaeie.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2jhuekwbv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gt2rpakcnrg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2fihrhgzc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2srqjglid.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.c1oappe.top/Article/details/gt2qlgukzrp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2braiutvv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gt2muzuhgea.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gt2mknmkjff.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gogol.net.cn/Article/details/gt2xmrlnvmr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gt2imstjxjs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gt2tzlrmubv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dashuyun.cn/Article/details/gt2uicwxsbs.html

Go:   slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gt2svdbmhiw.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gt2jubvfbgh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hammf.cn/Article/details/gt2onuwhmae.html

[N03] 快速排序（分治示例）
来源：http://dali.zycfv.cn/Article/details/gt2gcphijhc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dgwkezix.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hizfvzbl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gt2xrrojwtd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gt2obgjlfek.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shuidangran.top/Article/details/gt2okuxpluc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pengpengdd.cyou/Article/details/gt2xtoluaxe.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uoteobcf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guowangkeji.top/Article/details/gt2nyezqfza.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gt2qozrchbj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gt2zrhtlprk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gt2hbachjbs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gt2rxbplpex.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2gjxhsefi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gt2rascxfcc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gogol.net.cn/Article/details/gt2wypsduus.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gt2nqtrdlcm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gt2ofbdbciu.html

[N05] 最大公约数
来源：http://dali.yanxiufei.cn/Article/details/gt2kvpjthmk.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gt2faiqvadq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gt2ardssotw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fvlyxykw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gt2uirlskvd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jyoumei.cn/Article/details/gt2iczxsdaa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nwbrower.top/Article/details/gt2wviyntdo.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gt2qtxxnmvh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gt2rtjgqdlb.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nkupgwsb.html

Py:   s == s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gt2cgfjprlt.html

PHP:  $s === strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gt2rjdrkdto.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2nkxazenv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2ivaumpwc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yvedp.cn/Article/details/gt2acyskrze.html

Go:   // 双指针从两端比较
来源：http://dali.dashuyun.cn/Article/details/gt2xwhxbngi.html

Ruby: s == s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2kjmrwyqk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gt2pmlipngz.html

[N07] 两数之和（返回下标）
来源：http://dali.chenjidiqi.icu/Article/details/gt2qofulydm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gt2ifctlmim.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.iojbl.cn/Article/details/gt2wvisppzx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kxpnrrfc.html

TS:   // 手写 Map<string, number>
来源：http://dali.nwbrower.top/Article/details/gt2qazfvanr.html

Java: // 手写 HashMap
来源：http://dali.wangshuangyany.cn/Article/details/gt2wrrdswla.html

Go:   // 手写 map[int]int
来源：http://dali.jqgfzy.top/Article/details/gt2ivilyfih.html

Ruby: // 手写 Hash
来源：http://dali.yvedp.cn/Article/details/gt2szfrtmbi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sxryk.cn/Article/details/gt2uwgrdloy.html

[N08] 生成全排列
来源：http://dali.zhixingplan.top/Article/details/gt2ajuxbkxp.html


<!-- 参考信息 -->