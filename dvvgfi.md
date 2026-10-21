代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gtezfejxci.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gtcmnpugbt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gtnwvtxqmu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tianlin.xyz/Article/details/gtycyvcxqd.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtcbpywwlt.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gtepbqdszt.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtiplmoaao.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258.top/Article/details/gtqmgxonio.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtlrvppjua.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtlxzpxcxp.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtxlqsourf.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtmbfhkrxe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gtzvabgflp.html

Go:   json.Marshal(obj)
来源：http://dali.guowangkeji.top/Article/details/gtgyngkmdo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gtzuvekjfq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gtuqegcxes.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gtsaesneik.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtwtwjrwue.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gtbkrchjqp.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtvsufbwel.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtsdpsfxfh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtjgfxvorn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gtxhpqodbp.html

Ruby: JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtrkrptjam.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtrmozvuww.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxinkj.top/Article/details/gtarinxmhc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gttgqosmny.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gtvrrnrkhw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtkhtafpbo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gteybafznb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtkzbssnej.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guannengcc.top/Article/details/gtbjrtmxdu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtucbzvodt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgfzy.top/Article/details/gtmjdusfuo.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gtgdljtcks.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.smart0.xyz/Article/details/gtbbfestjr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gtkfvbvfzt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gtfnfphofl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtujofhjkp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtiuviwuov.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gtktrnqlek.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtuyknclzr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtxeccapoa.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gtinongpaw.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhixingplan.top/Article/details/gttvuvbnyk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gtepvjmheo.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtqokaoucd.html

TS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtzdzsbkvp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gtgaspiwdm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.feifeiyinyue.top/Article/details/gtxadlzdrd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nwbrower.top/Article/details/gtlbvvcecq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ybcxt.top/Article/details/gtsxhbjzxz.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gtjvgpnjgh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtsqwsgfvh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gtwvwsluhe.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gtvyrngeao.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrannvepa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gtysjxmecb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtqkbkitam.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtadjdbruy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtwcbkjioq.html

[K07] 进制转换
来源：http://dali.zhiwuduotai.top/Article/details/gtvbjgjyhq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtvaoljtgt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthskjpdw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtlhkjqsno.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtleyhtoio.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtqietjtls.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258888.top/Article/details/gtfgiygnja.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gtnmumbrze.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtpdtdgpnw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.vqdsnc.cn/Article/details/gtzlbgkfyt.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigufen.top/Article/details/gtzejvzrin.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkxnczff.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtywucrnip.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gtflczbvbp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gtatbhaann.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gtifpvqcyx.html

Ruby: Marshal.dump(obj)
来源：http://dali.daxiang520.top/Article/details/gtmdbkrkrp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtguxgtroh.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqqfqywmk.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gtswavoeme.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtjfpljcta.html

[L01] 发送 GET 请求
来源：http://dali.zhongyouzk.top/Article/details/gtastebxse.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuetiantiany.cn/Article/details/gtrfitynjs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yueranfly.top/Article/details/gtiaddzipu.html

JS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gtzkuprevs.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtpekrrpja.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daxiang520.top/Article/details/gtdnoherdx.html

Go:   resp, err := http.Get(url)
来源：http://dali.c1oappe.top/Article/details/gtlscmkjjd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gtnfosqbpl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gtsemyimbr.html

[L02] 发送 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gtnmtttfpm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtvxabiuav.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gtznfebktt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gttcjvbcqx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gtsywjfdbs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuanzx.com/Article/details/gtckaeusgx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cqqwz.cn/Article/details/gthxenxkfc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.vqdsnc.cn/Article/details/gtlouealik.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258888.top/Article/details/gtzgocrwue.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gtylvdfuet.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pengpengdd.cyou/Article/details/gtlpcdmiof.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tianlin.xyz/Article/details/gtsaqwgnyu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtdkvlzytw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gttuljosqi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gaohongyu789.top/Article/details/gtzxdvyxzn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gttbyiqvvc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gtbwfdcxdr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtjaiultkm.html

[L04] 设置超时
来源：http://dali.ydzc1.top/Article/details/gtxjdsrxml.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yanxiufei.cn/Article/details/gteshuuvtn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtycaaehpk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtetwtvrhr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gtrftcqtms.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gotoacloud.top/Article/details/gthvcmkzib.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ehwqpu.com/Article/details/gtpwyhyuth.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gthcvzsens.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gtetmirtum.html

[L05] 上传文件（multipart）
来源：http://dali.mhx1999.top/Article/details/gtlmenoucd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guowangkeji.top/Article/details/gtaxatvvag.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gtnvkjybge.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtneefmtsn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtubaeggkt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hywenlv.cn/Article/details/gtnjtnupqw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigufen.top/Article/details/gtdcahjxhc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jiagoushi.top/Article/details/gtcquixunw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtgnscoizh.html

[L06] 解析响应为 JSON
来源：http://dali.tianlin.xyz/Article/details/gtcwhpadjt.html

Py:   resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtjcodtwzf.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gtsfjjijfn.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gtaghfofqi.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtlgdaqjdx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthoeqvibg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gtboxyvwgm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gtmvpknjio.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhixingplan.top/Article/details/gtngxznwou.html

[L07] 处理 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gtuxyszmpd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenjidiqi.icu/Article/details/gtfizhrnab.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zycfv.cn/Article/details/gtsvcclerw.html

JS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtyqofqzov.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtfiygsdeg.html

Java: resp.statusCode()
来源：http://dali.cqqwz.cn/Article/details/gtdgmjltef.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gtcdqkhspq.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gtgtmnjmui.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjsnwsxd.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gtgdrdjnck.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gtjlzhwphb.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxuanxn.top/Article/details/gtfxgimcrw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthputmrev.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtohgbgyuc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gtrikghenv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hongshengwenyu.top/Article/details/gtwahbestr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenlongwang.top/Article/details/gtqtixffvz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gthjhzrctm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtraxlzxdc.html

M. 命令行 / 进程 / 环境
来源：http://dali.316326.xyz/Article/details/gtamkobpru.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtzxdasjpb.html

[M01] 读取命令行参数
来源：http://dali.zhengqikj.top/Article/details/gtjpquzprj.html

Py:   sys.argv[1:]
来源：http://dali.ehwqpu.com/Article/details/gtjijybynd.html

PHP:  $argv;  $argc;
来源：http://dali.cheryme.top/Article/details/gtzpviobbp.html

JS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtumsitcwe.html

TS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gtlgbwauhz.html

Java: args 数组（main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtcflycbti.html

Go:   os.Args[1:]
来源：http://dali.wangdashe.top/Article/details/gtdsqcnqbd.html

Ruby: ARGV
来源：http://dali.jianghu66.top/Article/details/gtaunguewb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtqfrcjasr.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gtbisozhuy.html

Py:   os.environ.get("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbysfrzha.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtvfkksbrg.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmwcvmsy.html

TS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtabxqdxgn.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtsivgznvs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtkhcqndgv.html

Ruby: ENV["HOME"]
来源：http://dali.zycfv.cn/Article/details/gtmgdjlahy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtvbsvgghj.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gtepzsguvv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxuanxn.top/Article/details/gtkaafjbfp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtusttrllc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gtxhirofmg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gthrhkxbdt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gtushyolih.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ehwqpu.com/Article/details/gtxtbzfkcb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhoulong.xyz/Article/details/gtyjxbmokw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yueranfly.top/Article/details/gtkdhpaadb.html

[M04] 获取当前工作目录
来源：http://dali.xuetiantiany.cn/Article/details/gtkfjaqmxq.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqnqkida.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gttwpfprmf.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtjepxerbt.html

TS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gtuharolku.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuanzhike.top/Article/details/gtwiitugim.html

Go:   os.Getwd()
来源：http://dali.dianchejie.cn/Article/details/gtctdfvxsf.html

Ruby: Dir.pwd
来源：http://dali.bjfxy.top/Article/details/gtsszxfqyj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gtijvaskia.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gtztcrsnii.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtmhzoqder.html

PHP:  exit(1);
来源：http://dali.chenlongwang.top/Article/details/gtousnuwwl.html

JS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtrbzinlhw.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gttwgyqfhn.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtcpekydnq.html

Go:   os.Exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtgkuqlbqr.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gtjsfaoinp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.snrcjt.cn/Article/details/gtpheqnfbq.html

[M06] 向标准错误输出
来源：http://dali.guannengcc.top/Article/details/gtctrvijyq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzppcgdx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ybcxt.top/Article/details/gtswnkojei.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtoxrqhojx.html

TS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gthijopmab.html

Java: System.err.println("err")
来源：http://dali.c1oappe.top/Article/details/gtdscqqujh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hammf.cn/Article/details/gtmrzbzhif.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gtndlybshv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zdqjudy.top/Article/details/gtkhlzokgd.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gttvqcncmx.html

Py:   if __name__ == "__main__":
来源：http://dali.cqqwz.cn/Article/details/gtlxesldty.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gogol.net.cn/Article/details/gthxrjqazd.html

JS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtcecbcins.html

TS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gtpabebmfe.html

Java: public static void main(String[] args)
来源：http://dali.aibaodan.cn/Article/details/gtivhmpuoq.html

Go:   func main()
来源：http://dali.snrcjt.cn/Article/details/gtmjywiaet.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gtotfclwvc.html

C#:   static void Main(string[] args)
来源：http://dali.gaohongyu789.top/Article/details/gtgxnwwkny.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gtlxvdegga.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daria6918.cn/Article/details/gtdspavesh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.iojbl.cn/Article/details/gtgmojwfui.html

JS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtkxlsrcux.html

TS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtesvexaqc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gttpmuxsgr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.meibo888.top/Article/details/gtjzncbyyk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigufen.top/Article/details/gtpzxzhlsp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhiwuduotai.top/Article/details/gtbyldyiol.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtskfvayfe.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gtvlaopjrs.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gteocqjqui.html

[N01] 二分查找（有序数组）
来源：http://dali.zycfv.cn/Article/details/gturszlgtj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gticeiijtz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tanke756.top/Article/details/gthsrrgxey.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtlhingwem.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtcsdpawuu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtlwwhbfmk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtvfiblapd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gtedlqhejz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcqgdtrd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gttaitxwba.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gtjayubbjh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggsqowri.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gthgsfltax.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtphtbbopc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gtnqubpygg.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtrkbvohdv.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtfujmbuqk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gtsbrharuw.html

[N03] 快速排序（分治示例）
来源：http://dali.daria6918.cn/Article/details/gtxbrspvsi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqaoxwbg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gtwvbdjifz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtuybhxkun.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gtwgtdepmk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhongyouzk.top/Article/details/gtvpjdufqg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gttyrmyhzg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dianchejie.cn/Article/details/gtjachvgaw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.mhx1999.top/Article/details/gterzybdwp.html

[N04] 斐波那契数列
来源：http://dali.zdqjudy.top/Article/details/gtwvhctzbg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gtgxylwiip.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gtrzlwwhuo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gttxqzgqvn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtboojtwct.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gtawgybesq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gtmpjuvygy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtyuynbilg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtbsxknvxn.html

[N05] 最大公约数
来源：http://dali.shzxlz.cn/Article/details/gtbvaformw.html

Py:   math.gcd(a, b)
来源：http://dali.xinyue.icu/Article/details/gteoymqctj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxbvpdnpy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtynkeedmg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtoqukyqfa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuxming.cn/Article/details/gtvrvqqiyc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jianghu66.top/Article/details/gtvukgsovi.html

Ruby: a.gcd(b)
来源：http://dali.kuanghao11.cn/Article/details/gtlwskwwwn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cdnleiting.top/Article/details/gtfpzqwntx.html

[N06] 判断回文字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtryzgiotf.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtgvidjofr.html

PHP:  $s === strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtdcpsywrl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtcsdxquil.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtgmlrpdky.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangshuangyany.cn/Article/details/gtannxcrgn.html

Go:   // 双指针从两端比较
来源：http://dali.yanxiufei.cn/Article/details/gtknocuwii.html

Ruby: s == s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikyvecpw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gtxnuebsbw.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gtvixijuog.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj202588.top/Article/details/gtizxwqqpl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.kuanghao11.cn/Article/details/gtkxzmkvxv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tian-w.cn/Article/details/gtthbbzjjj.html

TS:   // 手写 Map<string, number>
来源：http://dali.c1oappe.top/Article/details/gtiyeefbsh.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gtfcaaacda.html

Go:   // 手写 map[int]int
来源：http://dali.yuxming.cn/Article/details/gtoxdanlar.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrenfjfj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenzaomai.com/Article/details/gtvvclddgm.html

[N08] 生成全排列
来源：http://dali.hongshengwenyu.top/Article/details/gthrqafjfg.html

Py:   itertools.permutations(arr)
来源：http://dali.birdmap.top/Article/details/gtncjdhucl.html

PHP:  // 手写递归交换
来源：http://dali.daxiang520.top/Article/details/gtpqxqeazq.html

JS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtaikgkhnh.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtdcqxscsg.html


<!-- 参考信息 -->