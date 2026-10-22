代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwljode.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2nlovtujk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2bythzkkp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsjefly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfgvizh.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2qqenucsh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhdakmu.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcqnzcs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2pabardzh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgotafmj.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pntlyfmf.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqazjygo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2irslblwb.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqngeotw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2draocxtg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkapcxs.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hmehvfdn.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wthbduvr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jdurmpwj.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsehesjd.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmitctm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2noydfjpd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwqpfbx.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2adbaqtot.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwmdmjk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoyzxvw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2tabqruvc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkohtab.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2semrfibj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvnbvop.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwtihzy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2djiuaqtg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjfocst.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnqlqwz.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrjucgg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjokcqe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjteshng.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tggxzvzj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uoslipww.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeubeeq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxpdpob.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hutdrilx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ynedlocs.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xaovkyuj.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcboryl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuyziny.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwlufhp.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkwrpll.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2nncemnqn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2zepwownb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmpnawu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjgmyor.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2czurxnwl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2tofkfjds.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyjgejq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bndosatk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dupkncky.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjnwvyq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkraijqu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjhfacr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejayffaj.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fntfyjez.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkgjlww.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2jszunizy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjvlecq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvqyvfi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaivedc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmggaplb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kljimqlj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlqfvxo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxfsaia.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbkgsio.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oerzseaw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwvihao.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2lddgrfvh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2nmagpzdf.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhwzakv.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmsrhdb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2pebvppar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2foyrpktp.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vbomfoul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnffqsfg.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfufeuf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqrugxg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2fhatumko.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2kptxngnv.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2csvggcfp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2khwllsst.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyunovcl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwofvoa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2akntnure.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2clszhwbg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiydxsy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgyjiwk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2etfhhnax.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zcknzfqn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2zawhcdko.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhijtxpz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2innngfxv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzymwbyf.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcocpei.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqxmbgi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bniwobij.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2wfysmhke.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbrkzhd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmklvhf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxssshg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2bttqixqb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjzegzb.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvkneik.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrouzru.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgabesc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkfrgdv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfdagrk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzjkwvo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsojxjsa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqmpbmz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuyrrzt.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqzdoxe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2ijikbtno.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2akrjkkmn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2gsihqagd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2suwdihvm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxxcpkj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwusqdth.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrwodsk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmmyquy.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbwqdyk.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkreglxv.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcobvgg.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fivvqyxm.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvywtdgn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbjftoi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfjjfjk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpkekeg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2igdxmnwx.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qicxoceb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2tamyxfdk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2edmoargu.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsvvkry.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2amchjims.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiklzsz.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2tefrjltw.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmmfope.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyhaynv.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdkvtxd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyfllly.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2scegkawg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgexzxv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cncvkzrw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2gbscjlhi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2sucbsony.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqrsyqf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvysnmx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmpndxa.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2evzqacrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kydqrztm.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtpjwag.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjnvnfu.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjquiscg.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcwdxhq.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmynsjny.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhzlxdr.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qadgdouu.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcgbcco.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbysfkt.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxbthpm.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2viowrtxz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2paxrketb.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnbuxjk.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2fztaxjsb.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkloukp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2runlloue.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2enklpyak.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cstoldik.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuabcaj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2buzuidnw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjudpvla.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xobgzmul.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbgqfmf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tasrbtkd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhldoff.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkjvige.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwhcpmh.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mssxyovl.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dibqulnd.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2uybyoluo.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcnkthw.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkswcge.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkymdbg.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2brkomsvj.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkonozk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzfgkcs.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuqxnmk.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymafwgai.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bngglcon.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbfoqzr.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxgagat.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2atxsztmx.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2chinskgm.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gcenxxoi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbjevej.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xiltambw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfpxyfx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnrwlph.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwyzigu.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpnlowl.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsevznx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyctaktb.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwceheuo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rackgrob.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbsqvue.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2skudrcki.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnwecbw.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmxwnde.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2pieaknji.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmcauzf.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckghktcb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2msncycfw.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2szeengol.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2eokbhzxy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdzqyfg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsefodl.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2abrwybuj.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqwenid.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2frpxnxfd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hevmutjd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2cufqetxb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2jitzsqio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcvjcrh.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaugdym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkisxjr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2djfuyhzl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxfulrg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2caevgkly.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jugtvjtx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxpfvwu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2afxcjzwz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zimuujcf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqhitmv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wodnqcbp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdluqjj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2weyotjwu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qldtmbce.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzrwkqk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jedaekxb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2anbdpocz.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vigiwxmn.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nydznicc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2asgmulcq.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2axrpmcli.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpcjuvk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2syujcqqe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwqnyml.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2apkbyuuc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlzwlgf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uxouwomr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqdwyth.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qloqchya.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ierqdkbb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2seohrkjz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdbessy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjoqyluc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nilhsogi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tygohoyd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gywtsjup.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnbemcu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrepryys.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfymlgy.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rapwzfpz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtouyet.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsmvhfr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvxtkuk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rahhajno.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqdysqn.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuwfmfi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgwoohk.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cosiieej.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fiazfcis.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpimsht.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcdzodr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wchzhnxe.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2meyvgmzp.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2chliqnar.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrbvwvk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcuhrhz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjifmisj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2huaxqxsa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2tovvmslg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcyakoz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxjmstd.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2roacmbrc.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjoedqc.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcmnscs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2otayljom.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2synvmhfc.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2scocrusv.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpijxnt.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcasfdh.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrxykpo.html


<!-- 参考信息 -->