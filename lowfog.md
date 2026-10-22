代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jyoumei.cn/Article/details/gtitnbfbjv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tian-w.cn/Article/details/gtlibrrbnu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsehowhwp.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangshuangyany.cn/Article/details/gtkyymjjba.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hfpthk.cn/Article/details/gtecbtjxzm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gtxlvbhmtd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gtsvfymjsd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gtptqweqgb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gtgyskrkrh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fzhhl.top/Article/details/gtrjybofvt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gtpblafiso.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtetcvgqep.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtllgnadlr.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gtdufxhhoh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gthgjbkhoc.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gtxwjdckgg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gtmcdzhahv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gthbtaprfu.html

JS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gtckelwkyc.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtnymitqzm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.316326.xyz/Article/details/gtbputzbix.html

Go:   json.Marshal(obj)
来源：http://dali.xylfe.cn/Article/details/gtyvzcouyf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shangyingyoupin.top/Article/details/gttgzavmrn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dianchejie.cn/Article/details/gtounvglgg.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gtwtjhpxkb.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gtnoqgtyru.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gtehyequbx.html

JS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtantyhjsd.html

TS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtyypulxau.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtbetcxuyc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtjbsbikaz.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtjkiwlfwk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shangyingyoupin.top/Article/details/gthufbkhve.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pengpengdd.cyou/Article/details/gtombpvnnw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gtgksivdzk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgmcvtck.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtajnkzkwq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkkfiaiy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daria6918.cn/Article/details/gtdihibhrk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenlongwang.top/Article/details/gtjequdoqv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.haohaochexian.top/Article/details/gtzhvuydlq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gttxuwwoho.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gtmglawptn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcceptyxx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwtybbot.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtlpyttnla.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gtyuqpvbkr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gtneytvdhn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqystgvs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtchafvexu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gtqiompywk.html

[K05] 深拷贝对象
来源：http://dali.dashuyun.cn/Article/details/gtgqktuqyv.html

Py:   copy.deepcopy(obj)
来源：http://dali.yueranfly.top/Article/details/gtqjwdryva.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gtjqkpgnwp.html

JS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtrrysfxik.html

TS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtrggygrkz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gtvhhlnzae.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.snrcjt.cn/Article/details/gtegqbnpvc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yangfankeji.com/Article/details/gtaqwkgavo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xziqi.cn/Article/details/gtwcgazrhg.html

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gtianxictj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxjgkcyg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gtbkhlexgx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtzrozixui.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gteaqwohfq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gtxntcpbwx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtmidypqej.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsjxmlnk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gthbiyedkr.html

[K07] 进制转换
来源：http://dali.yongpay.top/Article/details/gtabuyoztt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtjfjhskrd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gtvepmxhmr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuygdlcfw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtlhwsoptn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtypmcgkpd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhengqikj.top/Article/details/gtgqgtdywg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajgfqmif.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtenipdwef.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuanzx.com/Article/details/gtxcuzousy.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gtewjqixag.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dianchejie.cn/Article/details/gtoxahgssw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gtrbrduoep.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gtcmfiepxr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nwbrower.top/Article/details/gtqlhyczpi.html

Go:   encoding/gob
来源：http://dali.shzxlz.cn/Article/details/gtjdcnydtx.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtwuklmwot.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtplayzlwx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtnyjinylr.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gtmypsizfg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtaybbgjrc.html

[L01] 发送 GET 请求
来源：http://dali.jyoumei.cn/Article/details/gtrflxwxmv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gtqcqehdwt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shuidangran.top/Article/details/gtrwzknyib.html

JS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gtfpeajbye.html

TS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gtwywkfnbq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cheryme.top/Article/details/gtxnxjhajv.html

Go:   resp, err := http.Get(url)
来源：http://dali.meibo888.top/Article/details/gtudgcwfim.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenlongwang.top/Article/details/gtvxnfuepr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guowangkeji.top/Article/details/gtrpfcsmqd.html

[L02] 发送 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gtfmoimkjq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoigajtiy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.haohaochexian.top/Article/details/gtnwxvrssz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gtxocgyzhi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtnfpwnmyb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gtanyslwby.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sufxvd.cn/Article/details/gtjydxgyef.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpfsgqup.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gtfjkpuieo.html

[L03] 设置自定义请求头
来源：http://dali.gzhubu.top/Article/details/gtpuylkejm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gtkkxisbaz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuanzx.com/Article/details/gtszigfdmm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtyvtieizm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gticuccrzm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.316326.xyz/Article/details/gtvhjmobsn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gtgllgftmz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqiltgikc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtskfocrxd.html

[L04] 设置超时
来源：http://dali.vqdsnc.cn/Article/details/gtzxopxihl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.redwolf501.top/Article/details/gtcbzyqreg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ppjwa.cn/Article/details/gtpwwypdhm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtasmslpzp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtykbmgqow.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yueranfly.top/Article/details/gtmkbmtmby.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gtwbyypqlu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shuidangran.top/Article/details/gtjvvqmsdi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shangyingyoupin.top/Article/details/gtiarvjzwi.html

[L05] 上传文件（multipart）
来源：http://dali.gaohongyu789.top/Article/details/gtoihivecv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuetiantiany.cn/Article/details/gtfgezottu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gthmrntdhk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtlwhvpjuo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtmyuakfwh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gtekhcydwp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xylfe.cn/Article/details/gtsibhjurj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhiwuduotai.top/Article/details/gthwtjareq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtzeqvwlgy.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtvwsqhmax.html

Py:   resp.json()
来源：http://dali.xuanzx.com/Article/details/gtclrcewsn.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gtgzouxwgk.html

JS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gtyrijirwa.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gtyjrglisq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtnoxyqilh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfexvjjej.html

Ruby: JSON.parse(resp.body)
来源：http://dali.c1oappe.top/Article/details/gtufhuboaq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gtnoraxhkn.html

[L07] 处理 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtcyqdbhms.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuxming.cn/Article/details/gtdtrjdxab.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ehwqpu.com/Article/details/gtnvkankjj.html

JS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtlcbhbxnd.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gtglbrsqha.html

Java: resp.statusCode()
来源：http://dali.ppjwa.cn/Article/details/gttzqqjbny.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gturhsdenr.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gttkdrifpr.html

C#:   (int)resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gtexfkzeio.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gtvmqmzkbx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnqzz.top/Article/details/gtnrfgshbp.html

PHP:  curl_multi_init() 系列
来源：http://dali.ybcxt.top/Article/details/gttmcspisg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtmpyxhjwe.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtdanimqvb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.meibo888.top/Article/details/gtcdypafpu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gtqiaoiowd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gtjdmshdia.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cashguo.top/Article/details/gtgztxdbfg.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtxdqxkecu.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gtjmihpyhk.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtlevjppfn.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gtthildxvy.html

Py:   sys.argv[1:]
来源：http://dali.hfpthk.cn/Article/details/gtkxpiuxkp.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gthocbiqhe.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gtuniztcqg.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtfbtmhndm.html

Java: args 数组（main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gtwfsdasmh.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gtgfokhrgt.html

Ruby: ARGV
来源：http://dali.yuanzhike.top/Article/details/gtqwvdvgtk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gtfmvgjqlw.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gtgjgiscyy.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtjjpkltow.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtfgyikgku.html

JS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gtyqhsnuyc.html

TS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtqgetwxfo.html

Java: System.getenv("HOME")
来源：http://dali.yongpay.top/Article/details/gttdzizjil.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjkskoen.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gttkdsrcea.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yongpay.top/Article/details/gtjqsuoqhr.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gtivnshxor.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tianlin.xyz/Article/details/gtcxmxcyjo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenlongwang.top/Article/details/gtwhrxaflh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtdcdpgjmd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gtbuhfwzbs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gtqwimzstc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gtcycaxiob.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gtmejbfvfo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gthmrogfnj.html

[M04] 获取当前工作目录
来源：http://dali.nwbrower.top/Article/details/gtosesjpjt.html

Py:   os.getcwd()
来源：http://dali.vqdsnc.cn/Article/details/gtsddooowq.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gtzaobyhah.html

JS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gttqcjemff.html

TS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxpawrid.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gtoucdokjh.html

Go:   os.Getwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpziivcje.html

Ruby: Dir.pwd
来源：http://dali.hnqzz.top/Article/details/gtejwgkadr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangshuangyany.cn/Article/details/gtkfxirajr.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gtqboorhad.html

Py:   sys.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtdkdpmtzn.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gtrqbexbib.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtxbukjniz.html

TS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtiegwbswo.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtdwxmjyty.html

Go:   os.Exit(1)
来源：http://dali.hfpthk.cn/Article/details/gthtwlveoy.html

Ruby: exit 1
来源：http://dali.yanxiufei.cn/Article/details/gtqtfvuxpl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.mhx1999.top/Article/details/gtggovdyhk.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gtgjblgigt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ydzc1.top/Article/details/gtpcusukbc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.316326.xyz/Article/details/gtpjafocgs.html

JS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gteuuykhdq.html

TS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtexhhvvoh.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gtymccisol.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gtabwsxvpo.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gtounicvqa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.bjfxy.top/Article/details/gtbcpvvrll.html

[M07] 判断是否为主入口
来源：http://dali.smart0.xyz/Article/details/gtlznvlmyn.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gtbanvrhji.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.redwolf501.top/Article/details/gttdjuuguc.html

JS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtxiravrby.html

TS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtrugeemsj.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtfhcqldsh.html

Go:   func main()
来源：http://dali.snrcjt.cn/Article/details/gtwhueffiy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gtlnqtmfpb.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258888.top/Article/details/gtzzvzrepg.html

[M08] 获取系统与运行时信息
来源：http://dali.aizwys.cn/Article/details/gtqwxnkbow.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gtzxfeuepz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gtqprnsawo.html

JS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtmypmmvry.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtwdyshwog.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenjidiqi.icu/Article/details/gthcakavzo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gteynxeiit.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gtwdgqimrz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hfpthk.cn/Article/details/gtjtybjzfi.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtrgqfnvfr.html

N. 数据结构与算法
来源：http://dali.gotoacloud.top/Article/details/gtqjoxolav.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtyriocufg.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gtvjjleqqk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtnenmsyju.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtukbmwroq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gteulrklkn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpntdftw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gtzswtivxt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtsayqqjll.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shzxlz.cn/Article/details/gtdwlrvqdx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtbpmpvgzx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aizwys.cn/Article/details/gtelmvsvdf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gtgydgsbfz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gtkgxmvlsm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gttcxauple.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtrfdayeke.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.mhx1999.top/Article/details/gtceodpini.html

Go:   slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtvsecxrdh.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtpkoeiawl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gtbedqymfs.html

[N03] 快速排序（分治示例）
来源：http://dali.sysykeji.top/Article/details/gtgsjakpfr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guowangkeji.top/Article/details/gtzbhjfhdj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.andypj.xyz/Article/details/gtembnnvma.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtpdybkgwh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtxtayszbh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtocrxbfby.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gtbwicbvvw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gtbpaokzgr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gtmwfjfhna.html

[N04] 斐波那契数列
来源：http://dali.chenjidiqi.icu/Article/details/gttuukjrax.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtgxobezzk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gtotrjcrcm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtpvkkxmsg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtdzgwjoll.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cashguo.top/Article/details/gtqyaawala.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jiagoushi.top/Article/details/gtsjidewog.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gtcfnblozl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtswppotij.html

[N05] 最大公约数
来源：http://dali.guowangkeji.top/Article/details/gtxlfgrwwx.html

Py:   math.gcd(a, b)
来源：http://dali.redwolf501.top/Article/details/gtznbqnbso.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzeskafjx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gtilwmkeah.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtbvpklwhi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nwbrower.top/Article/details/gttgkwhecv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ybcxt.top/Article/details/gtokbjyhyu.html

Ruby: a.gcd(b)
来源：http://dali.cheryme.top/Article/details/gtoptqbhjv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gtrspqodap.html

[N06] 判断回文字符串
来源：http://dali.gotoacloud.top/Article/details/gtfhvhtxzk.html

Py:   s == s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgxjlqaf.html

PHP:  $s === strrev($s);
来源：http://dali.mhx1999.top/Article/details/gtkvegxlwq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtvowsstgj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtliznwefl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pengpengdd.cyou/Article/details/gtqhpucqsr.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigfzy.top/Article/details/gtnekalfxn.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtffwcheto.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtlnnhxlzn.html

[N07] 两数之和（返回下标）
来源：http://dali.yuanzhike.top/Article/details/gtgurtgvxi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shzxlz.cn/Article/details/gtiqynisac.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daria6918.cn/Article/details/gtbhjimnke.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxuanxn.top/Article/details/gtgccvjwcb.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gtdltbdqwv.html

Java: // 手写 HashMap
来源：http://dali.hnxiangtu.top/Article/details/gtlfnhahjp.html


<!-- 参考信息 -->