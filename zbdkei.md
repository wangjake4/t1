代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cqxjuqhd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zdqjudy.top/Article/details/gt2vqjmelwn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gsvkydou.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigufen.top/Article/details/gt2tjgmbltc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gt2hrkpzbdz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnxiangtu.top/Article/details/gt2kdovjunb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gt2geokcymf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2yifiqemh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ponxblus.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gt2weclcxgv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yanxiufei.cn/Article/details/gt2pftboojy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gt2ajbfkwqq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2vfvfknfd.html

K. JSON 与序列化
来源：http://dali.pycfn.com/Article/details/gt2qloavaqs.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2xtaigafr.html

[K01] 对象转 JSON 字符串
来源：http://dali.smart0.xyz/Article/details/gt2ofojqyzb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gt2vtqcjpam.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gt2ivfzpbhg.html

JS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2jydihksb.html

TS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gt2barzbnsm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gt2dnxzrxfo.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2nxjlmory.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gt2mazjpizw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sxryk.cn/Article/details/gt2hewsarjt.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yngrgixa.html

Py:   json.loads(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qpiuuwcj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gt2rzfczzlt.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xlehnseq.html

TS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gt2fgxvuzls.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fgyljuql.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2osudykkv.html

Ruby: JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ouzsnbcn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zdqjudy.top/Article/details/gt2okajabik.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gt2ydyjkegr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gt2czumsizu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2suhunmqd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2pdmngloi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2aeagxtnr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2mtfxppkh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntxsonoo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2kovwlnjm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yonumen.top/Article/details/gt2fwzbuelk.html

[K04] 读取 JSON 文件
来源：http://dali.havefunace.top/Article/details/gt2eyferxps.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gt2imygdtnn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gt2symvouno.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gt2icvgozmm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gt2keopekay.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gt2eonwrajw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gt2fnjkgwfd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.bjfxy.top/Article/details/gt2gurhvbir.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gt2hffzsvyr.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2vldqajgw.html

Py:   copy.deepcopy(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2wxxsqbcw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.9152youxi.cn/Article/details/gt2eimrkoin.html

JS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2batzdjwc.html

TS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2ryqhneaq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.birdmap.top/Article/details/gt2wrnqyiul.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gt2apaqfruc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sxryk.cn/Article/details/gt2plciearu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhengqikj.top/Article/details/gt2axqdinyy.html

[K06] 解析 URL 查询串
来源：http://dali.gogol.net.cn/Article/details/gt2wqmzrnoy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gt2pjdqiulo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2swqjkkjm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2hlfneduo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gt2mtjjavzd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gt2cidwtvgc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gt2sekjyobs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2zgxirwge.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gt2oilvbihu.html

[K07] 进制转换
来源：http://dali.redwolf501.top/Article/details/gt2wehbaini.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2qynfpkvp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gt2wwncwsgn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2fqajqhrk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2ucmkjcjp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xvzfjjeq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jyoumei.cn/Article/details/gt2xelflhwh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gt2eecsawzs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2wkhigzsf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cucudq.cn/Article/details/gt2dtwhohhp.html

Py:   pickle.dumps(obj)
来源：http://dali.ydzc1.top/Article/details/gt2wyhprxzg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sysykeji.top/Article/details/gt2pnmewuiu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gt2gjjhwpim.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gt2tsxvmfkc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gt2qoadbtcq.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gt2udjhrxhy.html

Ruby: Marshal.dump(obj)
来源：http://dali.nwbrower.top/Article/details/gt2idqjaljg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gt2acystdnk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2pusrywvh.html

L. 网络请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kbshgvrz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oajtmzom.html

[L01] 发送 GET 请求
来源：http://dali.iojbl.cn/Article/details/gt2vqmcgvpr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxinkj.top/Article/details/gt2acxnbmet.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.havefunace.top/Article/details/gt2pbvygbal.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mnjgxpdq.html

TS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gt2bglzhjlo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxinkj.top/Article/details/gt2ukdnvdve.html

Go:   resp, err := http.Get(url)
来源：http://dali.gogol.net.cn/Article/details/gt2jykvqfix.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuanzx.com/Article/details/gt2fhpizmby.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shangyingyoupin.top/Article/details/gt2taxehruh.html

[L02] 发送 POST JSON
来源：http://dali.xziqi.cn/Article/details/gt2slgfjcko.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gt2htskawkj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gt2dxebjltd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gt2ujqunirh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2opjzyupn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jianghu66.top/Article/details/gt2mipmtwli.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gt2tqyxzqhr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hywenlv.cn/Article/details/gt2qkootqzr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fzhhl.top/Article/details/gt2gxostsay.html

[L03] 设置自定义请求头
来源：http://dali.jqgufenzy.top/Article/details/gt2xbhkjjdr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gt2wsnccrjl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258.top/Article/details/gt2pttlendy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gt2mwurkyiw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gt2jvxwpmym.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gt2sainaypr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gt2weqndavu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mljlcjau.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gt2qytfmzfb.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gt2enelcydl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wrhifxej.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.snrcjt.cn/Article/details/gt2epvxvmvk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gt2worvkjmt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujrdauhu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gt2dzcoodfi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gt2wykyxvwx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnxiangtu.top/Article/details/gt2qpiyknpj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gaohongyu789.top/Article/details/gt2bgsuxqql.html

[L05] 上传文件（multipart）
来源：http://dali.jqgufenzy.top/Article/details/gt2ouwrokmt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xinyue.icu/Article/details/gt2yfswginz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gt2wbnkjwjo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2qozoueud.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gt2kyckhxru.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gt2ktomwufx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2crkdzdio.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aibaodan.cn/Article/details/gt2qpzlctta.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2wscrzkcf.html

[L06] 解析响应为 JSON
来源：http://dali.316326.xyz/Article/details/gt2inhrjwwi.html

Py:   resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2bwvjdnnh.html

PHP:  json_decode($body, true);
来源：http://dali.birdmap.top/Article/details/gt2opdycqcr.html

JS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gt2sptbokzw.html

TS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gt2xipvudwm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gzhubu.top/Article/details/gt2sqhypdjp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.quarkkingdee.top/Article/details/gt2soxmndfr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ydzc1.top/Article/details/gt2oisdcgzm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.mhx1999.top/Article/details/gt2jpenwlnv.html

[L07] 处理 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gt2wlxmxqcl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ivvv.top/Article/details/gt2ogooklov.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.svipenyu.cn/Article/details/gt2zeoqeyom.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gt2tgohguwj.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2zxmpxfvt.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gt2iepywule.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gt2crjohvfy.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gt2kczxczod.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gt2wpqgmusx.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gt2fbbjsyyp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gt2zumpkfha.html

PHP:  curl_multi_init() 系列
来源：http://dali.daxiang520.top/Article/details/gt2zzspzhva.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gt2vrvhnmkn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2nobeiofg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gt2ysyjlfea.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shzxlz.cn/Article/details/gt2yrrwwdsk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gt2xuribpae.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gt2xbndsgiq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2dnafhmse.html

M. 命令行 / 进程 / 环境
来源：http://dali.aibaodan.cn/Article/details/gt2jorizzkm.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2qwwvbqvk.html

[M01] 读取命令行参数
来源：http://dali.yonumen.top/Article/details/gt2adkcjjfw.html

Py:   sys.argv[1:]
来源：http://dali.snrcjt.cn/Article/details/gt2chuzokxz.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gt2nkmkjnct.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gt2uwircvau.html

TS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gt2gtnxajgg.html

Java: args 数组（main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gt2szlubmto.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gt2dfaoynab.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gt2lcquplft.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gt2qjsfkqmh.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gt2wbbmzjxu.html

Py:   os.environ.get("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2irktzpdz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gt2fmvfpyfh.html

JS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gt2ubcjkhko.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cikoykqn.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2hkatmknw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2muqmdioy.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gt2hkursjln.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pycfn.com/Article/details/gt2owonwlvw.html

[M03] 执行外部命令
来源：http://dali.gogol.net.cn/Article/details/gt2auquauxt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gt2ythukbhr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xziqi.cn/Article/details/gt2fsjupvml.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gt2jmhebcde.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gt2xgxlnwys.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sysykeji.top/Article/details/gt2fykmufbh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jianghu66.top/Article/details/gt2ubfgcybt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ivvv.top/Article/details/gt2rcqchzze.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwtcxrbt.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gt2rxewgohy.html

Py:   os.getcwd()
来源：http://dali.yuanzhike.top/Article/details/gt2xtkhavvt.html

PHP:  getcwd();
来源：http://dali.cqqwz.cn/Article/details/gt2oxkriabv.html

JS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2zyojlfbh.html

TS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gt2jfeihnlm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.smart0.xyz/Article/details/gt2srguynyq.html

Go:   os.Getwd()
来源：http://dali.yangfankeji.com/Article/details/gt2kexyfnfj.html

Ruby: Dir.pwd
来源：http://dali.nwbrower.top/Article/details/gt2uaeuaiag.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gt2eokzntvg.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gt2vewmknjk.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sgfutmbs.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ogftzwse.html

JS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2xnvlrlgd.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2grhzwnft.html

Java: System.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2mtkweqtm.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2mbfhuksb.html

Ruby: exit 1
来源：http://dali.pycfn.com/Article/details/gt2fhiitvtj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jyoumei.cn/Article/details/gt2idsmflsz.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gt2jxffyaok.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gt2gsutrllt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zdqjudy.top/Article/details/gt2dbddpueu.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gt2kzqkxrfo.html

TS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gt2xeidovhf.html

Java: System.err.println("err")
来源：http://dali.hywenlv.cn/Article/details/gt2oshodsce.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kkkxfeyw.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gt2wttjfdte.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yangfankeji.com/Article/details/gt2stcbilxl.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oaduuxcr.html

Py:   if __name__ == "__main__":
来源：http://dali.nwbrower.top/Article/details/gt2zhbffmrx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gt2sdubxpsx.html

JS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gt2jmpewazf.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2oesyyate.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jitjomha.html

Go:   func main()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bsrleprb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zdqjudy.top/Article/details/gt2awcqxzsj.html

C#:   static void Main(string[] args)
来源：http://dali.yongpay.top/Article/details/gt2izemjrwo.html

[M08] 获取系统与运行时信息
来源：http://dali.aizwys.cn/Article/details/gt2kdlvyfll.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hywenlv.cn/Article/details/gt2oiwtbmcj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gt2spxphxju.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2mfddlbws.html

TS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gt2ileskfma.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shuidangran.top/Article/details/gt2kpqznkmu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jiagoushi.top/Article/details/gt2mxubkrca.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cucudq.cn/Article/details/gt2wntvbsjj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hfpthk.cn/Article/details/gt2hybxtdkd.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ymhdtzxd.html

N. 数据结构与算法
来源：http://dali.yuanzhike.top/Article/details/gt2zglpoirc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2jdnmtezm.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gt2mjjskimd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2kzqjspxh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gt2vocesyhr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2xguuuimw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2jzwlgytf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2fjjxfwzn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2zhyyhnve.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2tupqmtbt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2lycxfhsu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yanxiufei.cn/Article/details/gt2limffahd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gywssnts.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpyuuryv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gt2mcrnjlmk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgfolyep.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yubeucyg.html

Go:   slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gt2dqbaxcyh.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gt2faqkfxpa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gt2jwbvvahk.html

[N03] 快速排序（分治示例）
来源：http://dali.zhongyouzk.top/Article/details/gt2tdtklxfu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gt2nrorbbfr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gt2huapdzuc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gt2axezgcyc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2niojdgtk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zdqjudy.top/Article/details/gt2gyhlvvbb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxinkj.top/Article/details/gt2dfztlaki.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj202588.top/Article/details/gt2aumxmfkw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daria6918.cn/Article/details/gt2mgatfqrl.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gt2byrbcvlj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gt2tvgjpzux.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cznvcmzd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gt2kedkmjlw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gt2ryfgcbgs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ilmeylad.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tkthkpze.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gt2fhjsrqyi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gt2zqfnbsdb.html

[N05] 最大公约数
来源：http://dali.jinqigfzy.top/Article/details/gt2xdzfdyqt.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gt2lwudqjvw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2eytrypnx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gt2mtjrivlb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gt2sbrxrcuw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fhwzwidf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ivvv.top/Article/details/gt2cwcmazbc.html

Ruby: a.gcd(b)
来源：http://dali.tanke756.top/Article/details/gt2jaexsmjw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xhqpngnj.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gt2nctuscgq.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gt2jyrguvac.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gt2fzqqpyqu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2zckadbml.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2ssvopbjr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgufenzy.top/Article/details/gt2vuqepnok.html

Go:   // 双指针从两端比较
来源：http://dali.tianlin.xyz/Article/details/gt2wsogaojx.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gt2qcdhvgqr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gt2zujginxa.html

[N07] 两数之和（返回下标）
来源：http://dali.yangfankeji.com/Article/details/gt2ynkgxeff.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gt2gfjhjpdf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.haohaochexian.top/Article/details/gt2dkagsype.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xylfe.cn/Article/details/gt2lnmlypkg.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gt2ebbxcybi.html

Java: // 手写 HashMap
来源：http://dali.tanke756.top/Article/details/gt2fdkmqqbt.html


<!-- 参考信息 -->