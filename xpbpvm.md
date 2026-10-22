代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhoulong.xyz/Article/details/gt2pkwxgmrq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gt2clvevmxt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gt2twyezgdu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gt2ttrhtscc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gt2rwtnhfmi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gt2xvutddbc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cqqwz.cn/Article/details/gt2dfpbxpkq.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gt2sxshwzcm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hfpthk.cn/Article/details/gt2uyxfnhbi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jyoumei.cn/Article/details/gt2zakiyney.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gt2saposayf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aizwys.cn/Article/details/gt2vngfxebj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2vyhiqfyc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhiwuduotai.top/Article/details/gt2vcykrrrt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangdashe.top/Article/details/gt2otkoordp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zdqjudy.top/Article/details/gt2hsvgzmgu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2wihtvehg.html

K. JSON 与序列化
来源：http://dali.vqdsnc.cn/Article/details/gt2sigwekey.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2spzxxqib.html

[K01] 对象转 JSON 字符串
来源：http://dali.nwbrower.top/Article/details/gt2xpwfkowv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gt2tqiezwnq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gt2kexvlqwz.html

JS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2yuhhzuic.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2stbxevmk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tanke756.top/Article/details/gt2jehyumco.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gt2xllpogoe.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlywhfoc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2bwweznni.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gt2crnrmwyq.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gt2putmehda.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yongpay.top/Article/details/gt2zfipcedg.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tjasuqtw.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2nnsckjzd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gt2knbzqxvr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gt2lodgyyos.html

Ruby: JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gt2umjfslun.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.birdmap.top/Article/details/gt2mgvgleww.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wtzazvcw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gt2jrgpyqmr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwjdqwrl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gt2tpnwziom.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2mfpgyvmo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hammf.cn/Article/details/gt2mudraily.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.316326.xyz/Article/details/gt2mamzbrir.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2gbkybhed.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cucudq.cn/Article/details/gt2idiphzrw.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gt2jlgamxfu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2nxlilyrk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sysykeji.top/Article/details/gt2qzpepfch.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdqcwrmi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2soemvozi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.smart0.xyz/Article/details/gt2fksrklwr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gt2llcgwxsg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gt2kunktiyd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2snvygbil.html

[K05] 深拷贝对象
来源：http://dali.daria6918.cn/Article/details/gt2jiahprvr.html

Py:   copy.deepcopy(obj)
来源：http://dali.tanke756.top/Article/details/gt2dwtktxsr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.haohaochexian.top/Article/details/gt2jyqtvzds.html

JS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gt2qoggwldb.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kahzhcie.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.meibo888.top/Article/details/gt2evmnjfzl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.meibo888.top/Article/details/gt2xinmcnhw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gt2blccezpc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdnsfrxg.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gt2ohteuzgy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gt2hewidmjk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hfpthk.cn/Article/details/gt2outtqyvf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gt2ebooqicm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2iklwzajn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gt2ogftcgrq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2fswvizpk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gt2ttncrgxe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gt2xkiabetx.html

[K07] 进制转换
来源：http://dali.aibaodan.cn/Article/details/gt2keuebogi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xmboanox.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gt2prmrljun.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2ekwnekep.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2vwfobdho.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2aqvxomvq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kxakigzc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.birdmap.top/Article/details/gt2rqsmxfiv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2wpvkalsa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlvvgamq.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2sbwtxmco.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.mhx1999.top/Article/details/gt2dofhmhxn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gt2mxatbgzm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gt2ynofwcot.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yvedp.cn/Article/details/gt2kcmrxfts.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gt2pwxchcrk.html

Ruby: Marshal.dump(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fsreseym.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gt2jyjkhqsy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ztcicgnl.html

L. 网络请求
来源：http://dali.nanxinkj.top/Article/details/gt2igzfwruj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2xyguqrkf.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2jewudbjb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gt2logntynp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkejmdrq.html

JS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gt2fxeyjcac.html

TS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gt2wtvgzonm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gt2kfjpiqct.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenlongwang.top/Article/details/gt2bkrfmnfq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.0kj1m.cn/Article/details/gt2fmfjhddj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ipipukbo.html

[L02] 发送 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gt2ncfauvjx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gt2qesrxjyw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ibwljjpm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gt2jmjwaqoa.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gt2latkwzan.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xinyue.icu/Article/details/gt2mgnabbmj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gzhubu.top/Article/details/gt2yzzddatu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.redwolf501.top/Article/details/gt2thhzzpbl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.c1oappe.top/Article/details/gt2lrylmukv.html

[L03] 设置自定义请求头
来源：http://dali.gogol.net.cn/Article/details/gt2nzuecghr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gt2uhryxjqp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2ensvnvtp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2fshdyajm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gt2wghfjwvh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gt2erwdnzgb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gt2ycdblggn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.snrcjt.cn/Article/details/gt2cxjniejg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwmqomid.html

[L04] 设置超时
来源：http://dali.jqgufenzy.top/Article/details/gt2eyoqshqv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxczkrfa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigfzy.top/Article/details/gt2cxzfpsxn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gt2bseacvsb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2abornvpe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xyffstkr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gt2syouaxci.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gt2mcrfypwq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gt2prhspams.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gt2leiungwj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gt2hlidzreq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hfpthk.cn/Article/details/gt2eschrnpe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gt2hinocxzw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gt2hfhhdhzb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gt2jtimurxg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tianlin.xyz/Article/details/gt2zzvqpdxv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangdashe.top/Article/details/gt2cdhatioq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ivvv.top/Article/details/gt2embkwbsg.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gt2uflecyrq.html

Py:   resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2zwckibym.html

PHP:  json_decode($body, true);
来源：http://dali.sxryk.cn/Article/details/gt2pzixsbpz.html

JS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2hxezwynt.html

TS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gt2iecbhnng.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xsrhsbqi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gt2lgxzclbk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gt2vexwxsat.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shuidangran.top/Article/details/gt2zcbmevms.html

[L07] 处理 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gt2sojvbypv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gt2dvzovjel.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bododyio.html

JS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gt2tfdpparr.html

TS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gt2lqzvacnb.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gt2nxmsqvff.html

Go:   resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gt2emvkreqx.html

Ruby: resp.code.to_i
来源：http://dali.ydzc1.top/Article/details/gt2aobedqsy.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gt2juscfpcb.html

[L08] 并发请求多个地址
来源：http://dali.birdmap.top/Article/details/gt2fnovcubx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.9152youxi.cn/Article/details/gt2sumthmlo.html

PHP:  curl_multi_init() 系列
来源：http://dali.gaohongyu789.top/Article/details/gt2zhrdhfro.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2peobvvvc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2jfdbqrsk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tianlin.xyz/Article/details/gt2dlinyhym.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuxming.cn/Article/details/gt2kwkbyest.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gt2kevqtmlj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2aznhktmx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ebiivnbe.html

M. 命令行 / 进程 / 环境
来源：http://dali.bjfxy.top/Article/details/gt2jobqmvqb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ckzufpig.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gt2zonanwnk.html

Py:   sys.argv[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxdvegdu.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gt2sgwyllcu.html

JS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gt2mnlliuib.html

TS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gt2yhmucddv.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gt2jcptmrhr.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gt2zyvnduff.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gt2rpmhtutm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gt2tezgqidr.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gt2buhkekka.html

Py:   os.environ.get("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2rtumxamw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gt2lavpiaap.html

JS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gt2mlijlpoo.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhfwnmpd.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gt2rptmctjt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gpjghidv.html

Ruby: ENV["HOME"]
来源：http://dali.zhixingplan.top/Article/details/gt2lyalvmez.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2qojrbecw.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gt2mxcqzqps.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jyoumei.cn/Article/details/gt2ytjkvvhk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guannengcc.top/Article/details/gt2kpcnrenp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gt2ggtevofq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2xzyccshz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xziqi.cn/Article/details/gt2rsdcleqc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gt2samsnlej.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gt2qyywjkzu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gt2fnazntkn.html

[M04] 获取当前工作目录
来源：http://dali.hysaishi.cn/Article/details/gt2fgpvwmsz.html

Py:   os.getcwd()
来源：http://dali.cdnleiting.top/Article/details/gt2wfufvrfv.html

PHP:  getcwd();
来源：http://dali.nanxinkj.top/Article/details/gt2ifjrtglg.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzwlzcxz.html

TS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2lofmuoca.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gt2weuuurxg.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gt2hznoxqmj.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gt2ewcckwfm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gt2htlilsbo.html

[M05] 设置退出码
来源：http://dali.ydzc1.top/Article/details/gt2teelfkaj.html

Py:   sys.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrxzfcjk.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gt2iyozdezs.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2uiouugmx.html

TS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2zlcwuqvo.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2bbbsulmc.html

Go:   os.Exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2djwixybh.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gt2dysfrdba.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cdnleiting.top/Article/details/gt2sshvkjwn.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gt2gumbreyd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gt2vdzovqyb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crjqrlew.html

JS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gt2diutixqz.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gt2afcvqurn.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gt2uqtsgtsn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ydzc1.top/Article/details/gt2apvnyhbp.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gt2nijmiuee.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jtaravwa.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gt2npgtciyg.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgufenzy.top/Article/details/gt2hrycpmxc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gt2bwneekiy.html

JS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gt2xblkdoom.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2uftpgfdf.html

Java: public static void main(String[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2swfpqtzv.html

Go:   func main()
来源：http://dali.wangdashe.top/Article/details/gt2otluisrp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gt2cqmdzoym.html

C#:   static void Main(string[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oagsjcdn.html

[M08] 获取系统与运行时信息
来源：http://dali.sweek.top/Article/details/gt2ouxmamdw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zycfv.cn/Article/details/gt2jatjavyi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jyoumei.cn/Article/details/gt2idombxqt.html

JS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gt2lkkmgqed.html

TS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gt2psduehza.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gt2pwjzblrr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gt2atrofopk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gt2nrmyzmhf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gt2irjvfcwq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2rorwixgk.html

N. 数据结构与算法
来源：http://dali.hfpthk.cn/Article/details/gt2ycekfjlx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2azxcyxtx.html

[N01] 二分查找（有序数组）
来源：http://dali.birdmap.top/Article/details/gt2vwflapcx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2phvqhowy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2utusmqci.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gt2ypjqzxme.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gt2yixeiomg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2edvfmvlb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2keqpdtxo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gt2bayahquj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2jwwbaoev.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gt2kkefbuwe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gt2xpszblli.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gt2krasgzdv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2dypdmnko.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gt2xjsefkqh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wehhmajf.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gt2bxpywprh.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gt2bsysbasz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gt2gzmrcdmc.html

[N03] 快速排序（分治示例）
来源：http://dali.cdnleiting.top/Article/details/gt2gxqgiypr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.redwolf501.top/Article/details/gt2ywcvflqn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yvedp.cn/Article/details/gt2pzixoicb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gt2jhnuohlz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gt2ejtrxvjc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gt2ojgymzmz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigfzy.top/Article/details/gt2ynvjxvue.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258888.top/Article/details/gt2klhgkybt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gt2vnmqrudq.html

[N04] 斐波那契数列
来源：http://dali.hnxiangtu.top/Article/details/gt2khizxjer.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kkxiamdq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xouuuunk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gt2rpzifebi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2kwhfnald.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.birdmap.top/Article/details/gt2loykqesi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2obeuntmd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2sfgeyunl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2knvoejuj.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gt2xeznbhdb.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gt2oobhudpi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2owwuzxeb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gt2filgxjor.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gt2riptgbvo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2epibonpq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.redwolf501.top/Article/details/gt2xkytnppw.html

Ruby: a.gcd(b)
来源：http://dali.dianchejie.cn/Article/details/gt2tzytizxd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sweek.top/Article/details/gt2scbjznec.html

[N06] 判断回文字符串
来源：http://dali.yongpay.top/Article/details/gt2rxzyoegv.html

Py:   s == s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gt2mpmtwhoc.html

PHP:  $s === strrev($s);
来源：http://dali.daria6918.cn/Article/details/gt2vvdlbfou.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2fxuombmw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2rsofqoij.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpzoypr.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zjinthwt.html

Ruby: s == s.reverse
来源：http://dali.gotoacloud.top/Article/details/gt2qbbpbhgf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gt2wcnbvtsk.html

[N07] 两数之和（返回下标）
来源：http://dali.guowangkeji.top/Article/details/gt2zquxfmab.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shuidangran.top/Article/details/gt2gjznrins.html


<!-- 参考信息 -->