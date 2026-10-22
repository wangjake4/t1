代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gt2mdgfigqy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqbigqgw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fzhhl.top/Article/details/gt2mbsenyic.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gt2jnbrfyol.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xlyquktx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenzaomai.com/Article/details/gt2wioqbaoz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tianlin.xyz/Article/details/gt2wfdcwmhd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tanke756.top/Article/details/gt2zrrwdotz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gt2qvkdbvbd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigufen.top/Article/details/gt2eyqtcnht.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yangfankeji.com/Article/details/gt2bnbrcged.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gt2vjwcbzap.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2wrdqckpd.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gt2yhrgwtpl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2hgwtntdu.html

[K01] 对象转 JSON 字符串
来源：http://dali.ydzc1.top/Article/details/gt2vhrzlmnm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gt2dqnbsxkh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gt2bxvgnkea.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2nmarhtzn.html

TS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gt2ffelqfjv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daria6918.cn/Article/details/gt2sjtfloeu.html

Go:   json.Marshal(obj)
来源：http://dali.cheryme.top/Article/details/gt2dqtsvnrt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gt2zyeaxvaj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2xhzkiwoq.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gt2cknzyybl.html

Py:   json.loads(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2lkvbelde.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gt2udojxjoa.html

JS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gt2dhbhlwop.html

TS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2emefxceo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2ttmdsmtt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gt2vssfspct.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gt2yqfnyqfb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gt2jmugjkql.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cqqwz.cn/Article/details/gt2ivqtxcsd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gt2ykbdgbga.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2gzwgnzrg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cyyczcgh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gt2shnsvylp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jianghu66.top/Article/details/gt2ecbmfltu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hjoincca.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ynlezmsz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gzhubu.top/Article/details/gt2vtmeudjj.html

[K04] 读取 JSON 文件
来源：http://dali.sufxvd.cn/Article/details/gt2dpasxaig.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnxiangtu.top/Article/details/gt2uvslhfrs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jlsjyb.cn/Article/details/gt2wwhpjqkg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gt2zivejiyc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gt2nnizonpb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2tircxvrb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gt2qaizartq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.redwolf501.top/Article/details/gt2zdnijqjq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.andypj.xyz/Article/details/gt2kbhqbgst.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gt2wdysgbvu.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzyqqdbw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.vqdsnc.cn/Article/details/gt2qhmjrczl.html

JS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gt2gazykkto.html

TS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2usfcsens.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.bjfxy.top/Article/details/gt2exoriwpo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fzhhl.top/Article/details/gt2dozngzgl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gt2ghpgysbb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gt2wtlklrrb.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gt2ovrslqdj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ybcxt.top/Article/details/gt2auafhhqo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ervmjdvq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gt2vcqqqmhs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gt2pkyeriwe.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gt2fslvxkms.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gt2hvpjvrfu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2idrzflxl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gt2ytzgrzrh.html

[K07] 进制转换
来源：http://dali.vqdsnc.cn/Article/details/gt2pvyegcjq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2aeknbgra.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sufxvd.cn/Article/details/gt2diczesnb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2bxjegxys.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2rrfxrxlv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2keosaaoo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuanzhike.top/Article/details/gt2jyefovhg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gt2dtmtetyk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2uwzvqxzc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuanzhike.top/Article/details/gt2cvlttkgn.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2mjzfhitj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenlongwang.top/Article/details/gt2owgycyqt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gt2zuekogld.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gt2qgsxqtis.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.redwolf501.top/Article/details/gt2wmpppoqj.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gt2xkzdimzh.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gt2usuodrts.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gt2khttycyk.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ypaoevow.html

L. 网络请求
来源：http://dali.cucudq.cn/Article/details/gt2mhckrdos.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2pcvuthiu.html

[L01] 发送 GET 请求
来源：http://dali.ivvv.top/Article/details/gt2gvvuhyvx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gt2lrbaiuuf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gt2czvpuhfs.html

JS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gt2jydecxyx.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gt2ctbadxrn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gt2tiqgkvia.html

Go:   resp, err := http.Get(url)
来源：http://dali.shuidangran.top/Article/details/gt2nlcoivbt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sxzqtgui.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2qvtdzpvx.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gt2vgrfypht.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gt2bpeetept.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qsdnsplk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gt2xdcnhzsn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gt2zywftsov.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.vqdsnc.cn/Article/details/gt2puhvvcum.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.bjfxy.top/Article/details/gt2vugcfwoa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tian-w.cn/Article/details/gt2dpudejii.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukcbxvif.html

[L03] 设置自定义请求头
来源：http://dali.chenlongwang.top/Article/details/gt2qvhjdatp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tian-w.cn/Article/details/gt2wjluyxgx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jianghu66.top/Article/details/gt2vrpyjkpx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gt2andvcpcf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gt2cojiwtln.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gt2vnjavksc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gt2uumkmnrh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.316326.xyz/Article/details/gt2fygmpawh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gt2tszfxfwo.html

[L04] 设置超时
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htzadsop.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jyoumei.cn/Article/details/gt2iytmqxlv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gt2zcajubbz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gt2jjavjmcs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gt2fjskqhqf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2svrwmutl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tanke756.top/Article/details/gt2vpglmrhx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cdnleiting.top/Article/details/gt2gevfkytu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gt2owuokocg.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gt2lcggupym.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.c1oappe.top/Article/details/gt2sdyqdnsb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gt2hdzasqcf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2jtcevlgk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gt2mtsiinex.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.c1oappe.top/Article/details/gt2axlemxua.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhixingplan.top/Article/details/gt2nfzfplou.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gt2lhfdtquh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2tvkcsamm.html

[L06] 解析响应为 JSON
来源：http://dali.c1oappe.top/Article/details/gt2wsettvlx.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gt2plwpvhhk.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gt2txzrvril.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2dtnpkcjw.html

TS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gt2fnphuabp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2vlgxbdpp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hysaishi.cn/Article/details/gt2npiwaled.html

Ruby: JSON.parse(resp.body)
来源：http://dali.andypj.xyz/Article/details/gt2mfcyodag.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gt2evwsuihd.html

[L07] 处理 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gt2rqecuzfd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gt2fxdosdgz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gt2gimpdysr.html

JS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gt2fyyjmtbt.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tdctgjba.html

Java: resp.statusCode()
来源：http://dali.dashuyun.cn/Article/details/gt2bplqlren.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjkebjcr.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmvnlhrx.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gt2uvlkqzwt.html

[L08] 并发请求多个地址
来源：http://dali.chenlongwang.top/Article/details/gt2bdzpttvs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gt2prvheuge.html

PHP:  curl_multi_init() 系列
来源：http://dali.vqdsnc.cn/Article/details/gt2vjualmtq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gt2coslchme.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gt2ejegsbtu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.kuanghao11.cn/Article/details/gt2muluaakc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnqzz.top/Article/details/gt2vqtierdb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.smart0.xyz/Article/details/gt2rzrnmwys.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2swxlyjti.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ylwtawda.html

M. 命令行 / 进程 / 环境
来源：http://dali.havefunace.top/Article/details/gt2ogonupiw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2wrswistu.html

[M01] 读取命令行参数
来源：http://dali.0kj1m.cn/Article/details/gt2itwyhoxh.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gt2axrjyhpd.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gt2pulqbtwh.html

JS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gt2bdgsuzjh.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gt2hexbyzgo.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gt2ebftrxxt.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2amojuuki.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gt2hpwzcxqw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2bknttaea.html

[M02] 读取环境变量
来源：http://dali.xylfe.cn/Article/details/gt2ttmpxyps.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2wmqxcqmp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gt2usbfdfxz.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gt2xrbafxwh.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gt2lnkltets.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2lteoyppz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2swiwmuag.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gt2fgstdbev.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gt2ddofpwfw.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gt2rlkyfrsg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gt2cxkrtrns.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenzaomai.com/Article/details/gt2pntsrqov.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gt2spnhgpai.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2qrftuzog.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gt2sfusnzpb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gt2frralkph.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cucudq.cn/Article/details/gt2htjgiyhq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj202588.top/Article/details/gt2tgxfmsoq.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gt2fcsexhcn.html

Py:   os.getcwd()
来源：http://dali.cdnleiting.top/Article/details/gt2ozqmxtfn.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkrblfve.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfyjpwk.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gt2gvjgjwhb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sweek.top/Article/details/gt2heyvsnyh.html

Go:   os.Getwd()
来源：http://dali.nwbrower.top/Article/details/gt2cyegrthv.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gt2hptdfray.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dianchejie.cn/Article/details/gt2sveiempg.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gt2hlgbcrwr.html

Py:   sys.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2hpmmzjdc.html

PHP:  exit(1);
来源：http://dali.haohaochexian.top/Article/details/gt2zbnvndsk.html

JS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2rvwytryw.html

TS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2epcmhysw.html

Java: System.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2krhxfmnm.html

Go:   os.Exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2pxnizeop.html

Ruby: exit 1
来源：http://dali.xylfe.cn/Article/details/gt2fvtlgoif.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gt2wqqtcmug.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gt2cukeevsj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gt2bmfglsqc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigufen.top/Article/details/gt2hrkcndbr.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gt2gtnxtpbc.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gt2ijhnffte.html

Java: System.err.println("err")
来源：http://dali.iojbl.cn/Article/details/gt2lfvwcnvt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.haohaochexian.top/Article/details/gt2lmzozscm.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gt2livwoyti.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dianchejie.cn/Article/details/gt2hwbjadmd.html

[M07] 判断是否为主入口
来源：http://dali.svipenyu.cn/Article/details/gt2murpmtqv.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gt2oohfawvq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2zrlswbbq.html

JS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gt2eyzvreab.html

TS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gt2cnargurd.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gt2jqbrboff.html

Go:   func main()
来源：http://dali.svipenyu.cn/Article/details/gt2ztlpygok.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yanxiufei.cn/Article/details/gt2gctweqsy.html

C#:   static void Main(string[] args)
来源：http://dali.guannengcc.top/Article/details/gt2etemblnb.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gt2xqyvpgic.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gt2ehysvltd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gt2vjipnkql.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gt2jgphmsto.html

TS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gt2ovlfkowt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuanzhike.top/Article/details/gt2bsvhjgaf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aibaodan.cn/Article/details/gt2hvnupvdg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dianchejie.cn/Article/details/gt2iektdjly.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nwbrower.top/Article/details/gt2pvzacves.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2gdatulop.html

N. 数据结构与算法
来源：http://dali.mhx1999.top/Article/details/gt2nydiatiu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2jzhkdsmg.html

[N01] 二分查找（有序数组）
来源：http://dali.chenzaomai.com/Article/details/gt2syavnphy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2leqmnuix.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2vlxdgasn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gt2krbdofhe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gt2kqeonfcp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2rzywrkcy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2nmfswqzk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gt2cazdggdg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2fqekrxvf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cheryme.top/Article/details/gt2hnymodse.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gt2fvnykuxv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xziqi.cn/Article/details/gt2hdptyyyw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gt2vwtbflwn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gt2xdjfkdya.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gt2wmsnwuff.html

Go:   slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2pkfjruek.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gt2klbyuptg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuanzx.com/Article/details/gt2crcngxgy.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gt2fvorbrmq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ybcxt.top/Article/details/gt2pjhvvrpi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cheryme.top/Article/details/gt2awvqnjyi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gt2kmaztnfa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gt2yahogbov.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkibzsi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cdnleiting.top/Article/details/gt2kxppdyaq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cashguo.top/Article/details/gt2lbhfmjju.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gt2mplncbnt.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gt2ascpwjte.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gt2xlxihodf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gt2beisrvld.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2vmkqnzmi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gt2eztpukeg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqlecpev.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxinkj.top/Article/details/gt2wvhqqcbr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gt2pngvtser.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mwssgykd.html

[N05] 最大公约数
来源：http://dali.xylfe.cn/Article/details/gt2bkpvqcsu.html

Py:   math.gcd(a, b)
来源：http://dali.cashguo.top/Article/details/gt2glxnjbgb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cucudq.cn/Article/details/gt2lwmmrcjm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gt2zcvliwfm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gt2hnxloitx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pycfn.com/Article/details/gt2dfnniyzk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tianlin.xyz/Article/details/gt2kydjekax.html

Ruby: a.gcd(b)
来源：http://dali.meibo888.top/Article/details/gt2rwjjymvl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shzxlz.cn/Article/details/gt2wwrhdkuj.html

[N06] 判断回文字符串
来源：http://dali.yj202588.top/Article/details/gt2nkcfwipt.html

Py:   s == s[::-1]
来源：http://dali.birdmap.top/Article/details/gt2pnpzurqe.html

PHP:  $s === strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gt2gbkfjfid.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2mjtbbzet.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gt2rdukejsc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gt2vmpzgfna.html

Go:   // 双指针从两端比较
来源：http://dali.sxryk.cn/Article/details/gt2nxqgsgut.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gt2mkqzuwqg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gt2btiaoqxm.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gt2tbiwjgzm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hammf.cn/Article/details/gt2lkoyckya.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangdashe.top/Article/details/gt2ykfdpimi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.vqdsnc.cn/Article/details/gt2vqutdpmh.html

TS:   // 手写 Map<string, number>
来源：http://dali.daria6918.cn/Article/details/gt2odisadip.html

Java: // 手写 HashMap
来源：http://dali.zhixingplan.top/Article/details/gt2sjvglqah.html


<!-- 参考信息 -->