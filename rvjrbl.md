代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gt2arotibgj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjcbfrhy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gt2zzpdlvce.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tanke756.top/Article/details/gt2rahybqhm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.c1oappe.top/Article/details/gt2jrhiubmb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gogol.net.cn/Article/details/gt2fhkbkvrd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gt2kshpxzka.html

[J10] 取今天 / 本月第一天
来源：http://dali.yonumen.top/Article/details/gt2qwbzlbky.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenzaomai.com/Article/details/gt2nwrnyqxt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gt2emjmfpmz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2osfdtfkj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guannengcc.top/Article/details/gt2uhftzzpa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.snrcjt.cn/Article/details/gt2gwfymqkj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gt2jlajjisz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.kuanghao11.cn/Article/details/gt2tenylkcb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cheryme.top/Article/details/gt2yitcsanf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2wyxmdxfm.html

K. JSON 与序列化
来源：http://dali.zhiwuduotai.top/Article/details/gt2lbrqigif.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ndtvrzla.html

[K01] 对象转 JSON 字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2ebpgnqkm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gt2gwjihcft.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gt2hrgztdci.html

JS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dwimejtz.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2elvoggoq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tianlin.xyz/Article/details/gt2qskcbcre.html

Go:   json.Marshal(obj)
来源：http://dali.wangdashe.top/Article/details/gt2mksujsqp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cqqwz.cn/Article/details/gt2qlswnwqm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2njqtmpxz.html

[K02] JSON 字符串转对象
来源：http://dali.hysaishi.cn/Article/details/gt2ccqzigmm.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gt2abnypzzh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xziqi.cn/Article/details/gt2xzmhixez.html

JS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gt2srymdlya.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2qdxssjvy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guowangkeji.top/Article/details/gt2fvpuxmti.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnmsqtgj.html

Ruby: JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2sgdsfibs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cheryme.top/Article/details/gt2jfqgewgd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gt2tahidquy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gt2giyrbuxe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gt2cwayitoa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gt2kqxbdtec.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kuzwhrod.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gt2zflxgsps.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gt2wjhxfraz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2kysojwuw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gogol.net.cn/Article/details/gt2ruzlrxbq.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gt2eofctdge.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2tqumbbdx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gt2hgdnncmr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gt2eibjomxa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gt2oyjltutj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gt2uetwhylu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gt2lxbhymiw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.smart0.xyz/Article/details/gt2ewodfsst.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gt2gneivrhf.html

[K05] 深拷贝对象
来源：http://dali.chenlongwang.top/Article/details/gt2hzatunko.html

Py:   copy.deepcopy(obj)
来源：http://dali.havefunace.top/Article/details/gt2patngozj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2esyeihgc.html

JS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2ohbubrdc.html

TS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2jtcxrdbk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjbmeoac.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuxming.cn/Article/details/gt2mygxmisl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.mhx1999.top/Article/details/gt2bgvqgrbg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gt2aoidijqx.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gt2hbvtwnaq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gt2hfgwbwvn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2atekywbd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gt2bsuampke.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gt2sksezcyz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gt2lgaysubh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2myqdqtpw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oiasbdrs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gt2nuswjvzh.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gt2rhfgqzms.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2hecsvleo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfxfoops.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2dzvxxzac.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2bdbdyles.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2yqpidqlf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gt2upshwnhl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gt2rdezywnu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fndugrou.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuxming.cn/Article/details/gt2pkeagbbs.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvtcxjjk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxinkj.top/Article/details/gt2jxvlcgwh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2ugyftuzr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gt2kcgadhaz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ppjwa.cn/Article/details/gt2qegwwozq.html

Go:   encoding/gob
来源：http://dali.jqgfzy.top/Article/details/gt2nfaseyex.html

Ruby: Marshal.dump(obj)
来源：http://dali.birdmap.top/Article/details/gt2xbvkckuz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gt2xocgjkjw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2sqjgycoa.html

L. 网络请求
来源：http://dali.hammf.cn/Article/details/gt2bmewablb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2jtvhgkrf.html

[L01] 发送 GET 请求
来源：http://dali.bjfxy.top/Article/details/gt2wqtpsyww.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhecxcui.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuxming.cn/Article/details/gt2sgubbedc.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gt2gqakxctr.html

TS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gt2ghqidoha.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.0kj1m.cn/Article/details/gt2kwlyswme.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xuyhqykw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gt2dufyszmb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.iojbl.cn/Article/details/gt2duybqpxx.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vfjxuxjk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2gorfjipq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuanzx.com/Article/details/gt2aawpnmbd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gt2zrafghhv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gt2ipaqqgzi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yueranfly.top/Article/details/gt2drkobxqg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmqswksm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gt2nutdajeq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hammf.cn/Article/details/gt2lpcdtdbi.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gt2tfcnpibx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgufenzy.top/Article/details/gt2eyglkydh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gt2dslrsdux.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gt2qhevzpfk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fddqcrjg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258888.top/Article/details/gt2rqnsnogt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gt2nbtjvzxl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangshuangyany.cn/Article/details/gt2fhabtuil.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gt2xnutqtrq.html

[L04] 设置超时
来源：http://dali.yj202588.top/Article/details/gt2iouqcifp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gt2pokoxovl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gt2jgeiiigt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gt2ftwqytdb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gt2ftmbpfau.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfpoarmb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gt2wjhhcken.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.316326.xyz/Article/details/gt2eywnwzzn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ufbaglgg.html

[L05] 上传文件（multipart）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knwquvan.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gt2oltankyy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gt2lxlbjduc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gt2zwoarhob.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gt2spcuipsk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gt2rhnmlldv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shuidangran.top/Article/details/gt2nrcewold.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nwbrower.top/Article/details/gt2attzzldk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2ehbcfghn.html

[L06] 解析响应为 JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2bggschqv.html

Py:   resp.json()
来源：http://dali.xuanzx.com/Article/details/gt2eunamamo.html

PHP:  json_decode($body, true);
来源：http://dali.yj202588.top/Article/details/gt2eomhmdgt.html

JS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gt2ejunwidd.html

TS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2piiykauh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gt2esuwufzd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zdqjudy.top/Article/details/gt2nflgstac.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aizwys.cn/Article/details/gt2wiwlkcpm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gt2beslajsj.html

[L07] 处理 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gt2ausviekg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gt2floszvkc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.snrcjt.cn/Article/details/gt2fuczsbne.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gt2rbefyptl.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gt2krswagil.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gt2tfymfckt.html

Go:   resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gt2nejsosmm.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gt2hdavkwkd.html

C#:   (int)resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gt2rwxmmgnm.html

[L08] 并发请求多个地址
来源：http://dali.yuxming.cn/Article/details/gt2pupombti.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gt2taekgufv.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gt2fbgjxbev.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2ounbcknk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2kxjqysfq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gt2tpuqkrgr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ydzc1.top/Article/details/gt2ryklsiwe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bbrreuxu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zgpnfamf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2highridz.html

M. 命令行 / 进程 / 环境
来源：http://dali.ivvv.top/Article/details/gt2pbxegoje.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2oueeyxfn.html

[M01] 读取命令行参数
来源：http://dali.gzhubu.top/Article/details/gt2imhkxwcd.html

Py:   sys.argv[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2uzuwcgnh.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gt2cazzvoml.html

JS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gt2kulopufs.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gt2oniqrxuu.html

Java: args 数组（main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gt2gcqjtbhf.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gt2lekjsvck.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gt2ftasmqzs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gt2cljajerv.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2fqoyljcj.html

Py:   os.environ.get("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2dovwffwj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gt2reghuaja.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gt2ctcvglhy.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2pbatabbp.html

Java: System.getenv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ktlkzabe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2rrjjwmfh.html

Ruby: ENV["HOME"]
来源：http://dali.feifeiyinyue.top/Article/details/gt2udhhepqg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2caqbnsyp.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gt2vzsbvqka.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cdnleiting.top/Article/details/gt2rxmxetkp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.smart0.xyz/Article/details/gt2bqjkxnoi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gt2lwovlalt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gt2vsbomwxl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gt2xhlgyujv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gt2skkuucfh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gt2tkbhxmnc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuetiantiany.cn/Article/details/gt2xxpondmu.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gt2dowhcicw.html

Py:   os.getcwd()
来源：http://dali.mhx1999.top/Article/details/gt2edupeemo.html

PHP:  getcwd();
来源：http://dali.ybcxt.top/Article/details/gt2ikjusotl.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2tqilahbj.html

TS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gt2txecysvu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gt2zghthqay.html

Go:   os.Getwd()
来源：http://dali.ydzc1.top/Article/details/gt2vwibybri.html

Ruby: Dir.pwd
来源：http://dali.jqgfzy.top/Article/details/gt2ouewwqwb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hachwgpf.html

[M05] 设置退出码
来源：http://dali.smart0.xyz/Article/details/gt2lkztucji.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2oejosjge.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gt2syqcgrre.html

JS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2ebpercps.html

TS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2bmcznnrq.html

Java: System.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2vqmoslvh.html

Go:   os.Exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2nvabmhob.html

Ruby: exit 1
来源：http://dali.shuidangran.top/Article/details/gt2ffaiiirx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pycfn.com/Article/details/gt2fpshhqpt.html

[M06] 向标准错误输出
来源：http://dali.haohaochexian.top/Article/details/gt2irunxbbc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gt2dxqnofkk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigfzy.top/Article/details/gt2wdtnxcch.html

JS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gt2myppzqls.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gt2gbmsiyzk.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gt2molbuxrv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gt2zgtsiahq.html

Ruby: warn "err"
来源：http://dali.pengpengdd.cyou/Article/details/gt2jyujvwlt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gt2bayzvkpx.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gt2kwcfecmw.html

Py:   if __name__ == "__main__":
来源：http://dali.jyoumei.cn/Article/details/gt2yoqmlrek.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfocpkjs.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ioszrurs.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gt2ikxiuvre.html

Java: public static void main(String[] args)
来源：http://dali.hfpthk.cn/Article/details/gt2elucshbe.html

Go:   func main()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2unzbzyni.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nwbrower.top/Article/details/gt2lsnojnek.html

C#:   static void Main(string[] args)
来源：http://dali.ivvv.top/Article/details/gt2dxscrwzb.html

[M08] 获取系统与运行时信息
来源：http://dali.0kj1m.cn/Article/details/gt2lqlnzbsl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gt2jcclopdb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yongpay.top/Article/details/gt2hmoierhe.html

JS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gt2fpichrkc.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfeusvhv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuxming.cn/Article/details/gt2gbrnbzhx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gotoacloud.top/Article/details/gt2svqrxaux.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daxiang520.top/Article/details/gt2fgzakvri.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.iojbl.cn/Article/details/gt2sxntwhjn.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2jthewfhc.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gt2rlzvrdsv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2dresxoxs.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxuanxn.top/Article/details/gt2evhvwuvf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2eewuenxd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2ipsgxwnz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gt2iopayrwo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2ddwunkik.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqxoorvn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2gklfzklq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gt2mzmvswcx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rlcxiybo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gt2wdoyptqo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gt2xcxxkvpg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxinkj.top/Article/details/gt2mwrvngvi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mebdtxkg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gt2vwgpvosb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.mhx1999.top/Article/details/gt2rhjodeuj.html

Go:   slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gt2swhijqqx.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gt2xjfhkugd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2owmlyskg.html

[N03] 快速排序（分治示例）
来源：http://dali.shzxlz.cn/Article/details/gt2meaohvcy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gt2avgzufch.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cdnleiting.top/Article/details/gt2tydwxoyp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gt2tigjzvuh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gt2kinnvcvw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gt2uhzlpewy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zycfv.cn/Article/details/gt2egxbxooj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgfzy.top/Article/details/gt2icwpinin.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnxiangtu.top/Article/details/gt2nxpayhjf.html

[N04] 斐波那契数列
来源：http://dali.tanke756.top/Article/details/gt2kwxpprlh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2aryckisb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gt2xlywcwoq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gt2nvqwsacf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2ubdroaiz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yongpay.top/Article/details/gt2dzoawybe.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.0kj1m.cn/Article/details/gt2eipslvug.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gt2slyjuffn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gt2pytkagzi.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gt2sdjlocsd.html

Py:   math.gcd(a, b)
来源：http://dali.aibaodan.cn/Article/details/gt2niuqivsm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jqmfdfmx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gt2kpgzczor.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2hodjorvv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sxryk.cn/Article/details/gt2yogpnzhz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gt2xurfkjch.html

Ruby: a.gcd(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lyvvckvq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gt2yukaaxfy.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2iwatdqzs.html

Py:   s == s[::-1]
来源：http://dali.smart0.xyz/Article/details/gt2vzouihqy.html

PHP:  $s === strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2holnrmnb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2oloyenta.html

TS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gt2iqdjnqel.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gogol.net.cn/Article/details/gt2lbziatbc.html

Go:   // 双指针从两端比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xlcylfpn.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gt2avfowhzv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gt2yjoybvpc.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gt2spkwwgdn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhongyouzk.top/Article/details/gt2azbmkled.html


<!-- 参考信息 -->