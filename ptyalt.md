代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxuanxn.top/Article/details/gt2rzxzokim.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gt2uwigcckk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yvedp.cn/Article/details/gt2iaeffjki.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2ebuguzlw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xziqi.cn/Article/details/gt2bpcmxrns.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuanzhike.top/Article/details/gt2uiqrlzfo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daxiang520.top/Article/details/gt2fahqpbaf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigufen.top/Article/details/gt2pbjionqw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2sbkqemwv.html

K. JSON 与序列化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2htytqjwq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmhsakry.html

[K01] 对象转 JSON 字符串
来源：http://dali.dashuyun.cn/Article/details/gt2perbrucx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gt2gvmdmoxb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gt2iuzjbwle.html

JS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2njzsimtl.html

TS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2aqdgsezg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dianchejie.cn/Article/details/gt2buxjwvpe.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2eirlipbd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gt2yrpejxoi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tian-w.cn/Article/details/gt2vfsihurw.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gt2yydeqfkt.html

Py:   json.loads(s)
来源：http://dali.ivvv.top/Article/details/gt2jyamllug.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gt2avqywdlw.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2uutmjujn.html

TS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2twkaixnf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qiymnlrn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gt2upzfcvli.html

Ruby: JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2hrbeuwae.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ohjuancn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuanzx.com/Article/details/gt2fiafbrcs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gt2qauyjsdr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gt2hbastxwe.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2fhlpjtcq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2lqpcgsbn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2qqbotsgn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lbwxboef.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2awckfdsy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ydzc1.top/Article/details/gt2gqeqpuqx.html

[K04] 读取 JSON 文件
来源：http://dali.yonumen.top/Article/details/gt2tcliwelm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gt2talcgebw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gt2qjlhzaqy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gt2osojtgpo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gt2ucbaixdn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2oueuvwvm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gt2gjqosiis.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gt2rycoztcn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bnsspowh.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbikwioo.html

Py:   copy.deepcopy(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2gmwzldiq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hongshengwenyu.top/Article/details/gt2apouhtzd.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfcxrybv.html

TS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gt2qohtrgkf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.snrcjt.cn/Article/details/gt2dbcwqthf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gt2gandfrez.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vbzxxxed.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhixingplan.top/Article/details/gt2xmfdufkn.html

[K06] 解析 URL 查询串
来源：http://dali.aibaodan.cn/Article/details/gt2rnqhwoob.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guannengcc.top/Article/details/gt2xfwfawuy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjyrnqaa.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2ticnaolg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2tigovflr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gt2posotlvk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lsjqmfwq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nkqygixw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2rylbnomt.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gt2klldrojd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2jfaoduig.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gt2dkyybtfv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2fihohvfp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2tvrcnnay.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2czwwdbpt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihcpfzzq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sxryk.cn/Article/details/gt2xadjfxzw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2ylzsqyzd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aizwys.cn/Article/details/gt2vwrojmjn.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2ncimwixl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gt2qcerqdom.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gt2oclzqkyr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2uviqykcn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gt2khyuibwn.html

Go:   encoding/gob
来源：http://dali.sweek.top/Article/details/gt2qzvzztsz.html

Ruby: Marshal.dump(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2irjyziyl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258.top/Article/details/gt2rugggvke.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2dplekimh.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gt2wurevvwb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ynvgbznf.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gt2azwakhot.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangdashe.top/Article/details/gt2etjwohxk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.redwolf501.top/Article/details/gt2ahnlrocr.html

JS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gt2wsoqwbpu.html

TS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2lsxmqljo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gt2pogbcnhd.html

Go:   resp, err := http.Get(url)
来源：http://dali.hysaishi.cn/Article/details/gt2hsngujtw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gt2aqiiajem.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cdnleiting.top/Article/details/gt2znjhlpnl.html

[L02] 发送 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gt2usffbkjw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gt2ymhgxnwb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.andypj.xyz/Article/details/gt2jwrvuzqu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gt2ztstvupe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2swuxkolm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zycfv.cn/Article/details/gt2hcbmguwz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.c1oappe.top/Article/details/gt2wfjefqem.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sxryk.cn/Article/details/gt2hyhkgboq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gzhubu.top/Article/details/gt2xtrbvpwj.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfpcliwg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gt2rgqfvpus.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2dkmqbhpa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gt2vkhcnaom.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gt2pngronvc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258888.top/Article/details/gt2iqykkgeb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gt2eyjifomf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gt2dtggssfm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gt2tuwxzijf.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gt2gtyyvchm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fengsongda.top/Article/details/gt2kydzxgmh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gt2alneidye.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gt2bufexvvb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gt2mqbqqgft.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnqzz.top/Article/details/gt2tracawkq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oftbwlqx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gt2tddkfqdn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jiagoushi.top/Article/details/gt2lnoxszjo.html

[L05] 上传文件（multipart）
来源：http://dali.ybcxt.top/Article/details/gt2eoajbhyd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gt2xshjyved.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2liqulsbg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gt2xdcpycdy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gt2wybwewtq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2cilkokvk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gt2puiwnjqo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gt2qvsmpmyq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2jibmnbtj.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gt2tfqrmwpc.html

Py:   resp.json()
来源：http://dali.jianghu66.top/Article/details/gt2yqoabcbf.html

PHP:  json_decode($body, true);
来源：http://dali.aizwys.cn/Article/details/gt2ygyqmoxt.html

JS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gt2xadahcrv.html

TS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gt2lefixloa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gt2sgccgnti.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aibaodan.cn/Article/details/gt2rgcycoyi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.snrcjt.cn/Article/details/gt2zhzegesw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gt2motjkylj.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gt2fuujkzbz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gt2xktbyvrn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jyoumei.cn/Article/details/gt2ahxynlze.html

JS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gt2cpnxcykh.html

TS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgfadork.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gt2cupjsllk.html

Go:   resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gt2rvwnvbej.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gt2zhhsorcv.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gt2dttikbnl.html

[L08] 并发请求多个地址
来源：http://dali.xziqi.cn/Article/details/gt2fjmyyusb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gt2eaeyirzs.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gt2fsiwvpik.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2nfgoqptx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gt2fndurhtr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfgwloee.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhixingplan.top/Article/details/gt2xqeuhmut.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gt2coaohofa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.c1oappe.top/Article/details/gt2cthptpsl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ozkowpjx.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gt2elyjlkjf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hkqgxbou.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gt2jqastgrk.html

Py:   sys.argv[1:]
来源：http://dali.jianghu66.top/Article/details/gt2iepgswqg.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gt2igjzgeme.html

JS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2olnxzgtr.html

TS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wqybzzxn.html

Java: args 数组（main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gt2mncenlbe.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gt2gqkdnwmx.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gt2tojtsxkc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ilbrshwk.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gt2lybmbkni.html

Py:   os.environ.get("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2mtuyzbui.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gt2dvmaymue.html

JS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2wnxevrfv.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2ecffrdnq.html

Java: System.getenv("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2cclqoxwp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2pqdctyck.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigufen.top/Article/details/gt2apibdret.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2erafazbr.html

[M03] 执行外部命令
来源：http://dali.zhengqikj.top/Article/details/gt2gohtxttp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gt2ojkyhlhj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gt2nbjsldcd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2cbfxvmga.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gt2ztsevpmj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gt2ydphcfky.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgfzy.top/Article/details/gt2iymcbezv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.redwolf501.top/Article/details/gt2tfnaqalk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gt2fbbqqzlq.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yoescbtq.html

Py:   os.getcwd()
来源：http://dali.gogol.net.cn/Article/details/gt2lmgkeaph.html

PHP:  getcwd();
来源：http://dali.ivvv.top/Article/details/gt2iruogiqo.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gt2dtvxjjeb.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gt2brsaesgl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.haohaochexian.top/Article/details/gt2qvhwdeey.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2srcwmwbx.html

Ruby: Dir.pwd
来源：http://dali.yj202588.top/Article/details/gt2yyhusosx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aibaodan.cn/Article/details/gt2pkjjcipd.html

[M05] 设置退出码
来源：http://dali.316326.xyz/Article/details/gt2zopvhroy.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2vapornyd.html

PHP:  exit(1);
来源：http://dali.guannengcc.top/Article/details/gt2fhjqszlk.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2ffhcryno.html

TS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2nhkmonyj.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2dbrcwuvr.html

Go:   os.Exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2hautgogy.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gt2gfovslvb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gt2apvmyiku.html

[M06] 向标准错误输出
来源：http://dali.sxryk.cn/Article/details/gt2wdomssvl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gt2josxzeoq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.iojbl.cn/Article/details/gt2pwfgoibo.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gt2whdxjxfx.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gt2yirphchy.html

Java: System.err.println("err")
来源：http://dali.aizwys.cn/Article/details/gt2yvlsazri.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gt2zggffasw.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gt2hudewebl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2fxwflfgr.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gt2axtrfbjx.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gt2vampgozu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnrdcnpa.html

JS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gt2nnywnmws.html

TS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gt2amkchghb.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2advdhnlk.html

Go:   func main()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aafcqtdf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gt2wbxqpvho.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gt2ckivsmex.html

[M08] 获取系统与运行时信息
来源：http://dali.yonumen.top/Article/details/gt2jpveohnd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gt2qxqyhyai.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258.top/Article/details/gt2swoaqddq.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbppevcr.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gt2jpyntlxn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gt2uldmqfun.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gt2apqqvppe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daria6918.cn/Article/details/gt2gulbhpfa.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.feifeiyinyue.top/Article/details/gt2yabnzzlt.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2nnwpaiyn.html

N. 数据结构与算法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqxmppyl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2xvyfkbgn.html

[N01] 二分查找（有序数组）
来源：http://dali.guowangkeji.top/Article/details/gt2nnshooas.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2ygvwwrif.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2sysrjena.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gt2adsxjvbe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywdfbpln.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2ufpfhjge.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2geqzmdwz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gt2syzorlzv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2kgzzyrgn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuanzhike.top/Article/details/gt2avcjomca.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umlsdhww.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gt2zkwhojfa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gt2vtbzjgdl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gt2zsgnpsih.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gt2bnaidrcw.html

Go:   slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2zzhbrskr.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gt2eonfrkpp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gt2hyengqrn.html

[N03] 快速排序（分治示例）
来源：http://dali.fzhhl.top/Article/details/gt2hatcbywe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2attfbmdv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gt2bqxmhorr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2nxaebcdl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gt2esdrkohm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gt2rwmkycks.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgfzy.top/Article/details/gt2eixcmodf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jianghu66.top/Article/details/gt2zipaghnx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2maotuyoo.html

[N04] 斐波那契数列
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnewctgo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gt2qovinutu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2iyrrhfrp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2exfljzgb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gt2myealobc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sxryk.cn/Article/details/gt2dirfccdb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybtduabj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gt2zzxveqmc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gt2fyiacfhk.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrlbucuw.html

Py:   math.gcd(a, b)
来源：http://dali.svipenyu.cn/Article/details/gt2hbqgyapr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srghqxcz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ztliyuus.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2bqhndakt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuetiantiany.cn/Article/details/gt2yyfomqkm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gt2lgtucwcg.html

Ruby: a.gcd(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2aatcbhxd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.bjfxy.top/Article/details/gt2wtwjyjhm.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gt2zjzlnmsu.html

Py:   s == s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2irnassla.html

PHP:  $s === strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gt2qfnzpftk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gt2kqvpfypq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gt2kwgidple.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.iojbl.cn/Article/details/gt2goeiqipt.html

Go:   // 双指针从两端比较
来源：http://dali.cqqwz.cn/Article/details/gt2jnmxbkon.html

Ruby: s == s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2hxlfrcks.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwqpfhan.html

[N07] 两数之和（返回下标）
来源：http://dali.tian-w.cn/Article/details/gt2gtzowmqa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangdashe.top/Article/details/gt2cyphaygi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gt2sieondzl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tianlin.xyz/Article/details/gt2qbrpqxfs.html

TS:   // 手写 Map<string, number>
来源：http://dali.gotoacloud.top/Article/details/gt2sodbwxaj.html

Java: // 手写 HashMap
来源：http://dali.sysykeji.top/Article/details/gt2dnjzwrol.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gt2khknyygw.html

Ruby: // 手写 Hash
来源：http://dali.pycfn.com/Article/details/gt2xgrkdapv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aibaodan.cn/Article/details/gt2bramjgdw.html

[N08] 生成全排列
来源：http://dali.shzxlz.cn/Article/details/gt2sttvmgkw.html


<!-- 参考信息 -->