代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gt2qgthfdxm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ppjwa.cn/Article/details/gt2mfzfpchq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.kuanghao11.cn/Article/details/gt2jwsqrgqq.html

[J10] 取今天 / 本月第一天
来源：http://dali.ydzc1.top/Article/details/gt2jycrbzhr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.mhx1999.top/Article/details/gt2wsepxyjg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258.top/Article/details/gt2mcwemzln.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigufen.top/Article/details/gt2gqsidmwc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2ozjslysj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gt2vxdecuja.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2csnvgydc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fengsongda.top/Article/details/gt2qnjmfbdq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.iojbl.cn/Article/details/gt2peoznepd.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2trnafczd.html

K. JSON 与序列化
来源：http://dali.zdqjudy.top/Article/details/gt2hujhqojp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2qqedgill.html

[K01] 对象转 JSON 字符串
来源：http://dali.pycfn.com/Article/details/gt2lbtjsmwd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gt2lxnumpch.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2rupgxisv.html

JS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gt2pedwxhfq.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2gwoupmgw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yanxiufei.cn/Article/details/gt2xxuscrpz.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hsajeiop.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuanzx.com/Article/details/gt2uttkszim.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2ekfovwgx.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gt2pwqbldmw.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gt2ehaveopb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zycfv.cn/Article/details/gt2byvpalsd.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2bpqcieyf.html

TS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2dcjqrlum.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xsufqwjs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gt2ylqeitej.html

Ruby: JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gt2wpclsavl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2bhqcxlxw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hysaishi.cn/Article/details/gt2vyqtuhtd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gt2plkfgtfo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gt2lvbhtkge.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2lguurdrq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gt2zkftwigm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2shdzcbzk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqdufpqw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2rhrwyjrb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hywenlv.cn/Article/details/gt2dljfbunx.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gt2naksfdoz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.redwolf501.top/Article/details/gt2fmzllbew.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jianghu66.top/Article/details/gt2qoshgryi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gt2uuorqmru.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gt2mxusukyh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gt2fhdpofaw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gt2fypdxxqr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2zskopaot.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2yhioeeuk.html

[K05] 深拷贝对象
来源：http://dali.fengsongda.top/Article/details/gt2oklmnona.html

Py:   copy.deepcopy(obj)
来源：http://dali.shuidangran.top/Article/details/gt2koyqtpdr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ppjwa.cn/Article/details/gt2gizvilfc.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2beutsxbm.html

TS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gt2mwutbgcb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daria6918.cn/Article/details/gt2sdiyhbjy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.andypj.xyz/Article/details/gt2nbhstics.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.meibo888.top/Article/details/gt2eqltnmzp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.iojbl.cn/Article/details/gt2gounwdqp.html

[K06] 解析 URL 查询串
来源：http://dali.yvedp.cn/Article/details/gt2yvmbusae.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258888.top/Article/details/gt2pnptiuux.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shzxlz.cn/Article/details/gt2xojxmlho.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gmqgwvxq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gt2vjyvhmdu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dashuyun.cn/Article/details/gt2msqyiunu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gt2yxfojszb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2pyuzilet.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2kimiduqy.html

[K07] 进制转换
来源：http://dali.smart0.xyz/Article/details/gt2fmixcgvb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2kkdetcnh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gt2lxmqeivh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lofneifv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2tszxoshz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2ofkohxrp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.vqdsnc.cn/Article/details/gt2rxrzpgzm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gt2ulvaunsl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2imvsdoyq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gt2qgrrsjni.html

Py:   pickle.dumps(obj)
来源：http://dali.aizwys.cn/Article/details/gt2ijktrqdt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.316326.xyz/Article/details/gt2btqcofab.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gt2bbhbxngn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gt2nvecwghf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuxming.cn/Article/details/gt2wsdvjxgy.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gt2eiqejjpu.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gt2nlxhjkmw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gt2fqehexps.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2nzpsposo.html

L. 网络请求
来源：http://dali.kuanghao11.cn/Article/details/gt2jbfhojjr.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2fncobluj.html

[L01] 发送 GET 请求
来源：http://dali.jyoumei.cn/Article/details/gt2syihidrd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfgaayus.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.meibo888.top/Article/details/gt2shixyzng.html

JS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gt2dxwvxmfz.html

TS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2rclpngwt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gogol.net.cn/Article/details/gt2zzufwjks.html

Go:   resp, err := http.Get(url)
来源：http://dali.dianchejie.cn/Article/details/gt2fpxzbpws.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gt2zrvgramr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gt2sfujhzaq.html

[L02] 发送 POST JSON
来源：http://dali.xylfe.cn/Article/details/gt2jbgfbmnh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gt2bbywycww.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gt2aqtlzzqs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gt2rqaqncni.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gt2kwkrqkul.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sblunjzp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dashuyun.cn/Article/details/gt2nobhpkxe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhoulong.xyz/Article/details/gt2tbaleqpl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ppibendb.html

[L03] 设置自定义请求头
来源：http://dali.guannengcc.top/Article/details/gt2znxpgenw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yueranfly.top/Article/details/gt2iwcrgbxm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fengsongda.top/Article/details/gt2farqkamj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gt2axbfrkgs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gt2ogbmyoer.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangdashe.top/Article/details/gt2rpucacvw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gt2dmwffoww.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daxiang520.top/Article/details/gt2dumitlrb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xumaedxg.html

[L04] 设置超时
来源：http://dali.nwbrower.top/Article/details/gt2rskxpccf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lppzymev.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gogol.net.cn/Article/details/gt2ivyjbchn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2phfgwnjd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gt2fqyfetpm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gt2iajcybnx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gt2yvatjeiv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangdashe.top/Article/details/gt2gwnncyaq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gt2mknshhoe.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258.top/Article/details/gt2ckarttoh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbxkfiml.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daria6918.cn/Article/details/gt2lsuczlzh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gt2sweaiafi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gt2gkirbipr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sxryk.cn/Article/details/gt2jnxbgpjg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2edzxzrpo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hongshengwenyu.top/Article/details/gt2asgqdegr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2djeenked.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gt2nusdsfrs.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gt2oneemooh.html

PHP:  json_decode($body, true);
来源：http://dali.yuanzhike.top/Article/details/gt2btwqsnqs.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2yrhtqbpe.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gt2njnyxoga.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rolsyhhd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gotoacloud.top/Article/details/gt2cnnkqjdq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gt2htjzrwmr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gogol.net.cn/Article/details/gt2mpejpfhk.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gt2ylqxlsba.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tianlin.xyz/Article/details/gt2ffqkepth.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gt2ifjzposj.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gt2dxlahpnc.html

TS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gt2ktadoerw.html

Java: resp.statusCode()
来源：http://dali.chenlongwang.top/Article/details/gt2nctwrtei.html

Go:   resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gt2xvlkxzne.html

Ruby: resp.code.to_i
来源：http://dali.yueranfly.top/Article/details/gt2stqtiqju.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gt2olmnrtus.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gt2htopjcyu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gogol.net.cn/Article/details/gt2bmxlarhj.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ideyufyr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gt2yjmcjtcu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjdvmilc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xinyue.icu/Article/details/gt2izitjsqp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gt2jzcbawgh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuxming.cn/Article/details/gt2tmxhfurk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2flnccsdu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2nkbvbsnj.html

M. 命令行 / 进程 / 环境
来源：http://dali.c1oappe.top/Article/details/gt2rdcqrlwf.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2hqbrchtx.html

[M01] 读取命令行参数
来源：http://dali.316326.xyz/Article/details/gt2lgfgfysm.html

Py:   sys.argv[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2jsnmpwft.html

PHP:  $argv;  $argc;
来源：http://dali.jiagoushi.top/Article/details/gt2ttexmxpd.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gt2uigrfkcm.html

TS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gt2trzanddz.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gt2kcbnxdaj.html

Go:   os.Args[1:]
来源：http://dali.cashguo.top/Article/details/gt2dqxjhbae.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gt2naelcxuv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gt2qojtmpjq.html

[M02] 读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gt2neanjvcm.html

Py:   os.environ.get("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2olofuhhf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gt2abcenqyw.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjytxvtb.html

TS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gt2ukyqpooi.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2atsuxbur.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2xtvnvisi.html

Ruby: ENV["HOME"]
来源：http://dali.gotoacloud.top/Article/details/gt2xvyfgedj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2bjdxdnhd.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gt2czfxqbrm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2frtlnjip.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gt2bhfvelip.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gt2ntmpqocf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2fsuatrcc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guannengcc.top/Article/details/gt2emhqhdna.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gt2earmvbxp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.bjfxy.top/Article/details/gt2fdbaxytq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gt2qbkmyuyd.html

[M04] 获取当前工作目录
来源：http://dali.yvedp.cn/Article/details/gt2liknlmky.html

Py:   os.getcwd()
来源：http://dali.birdmap.top/Article/details/gt2bbgrooww.html

PHP:  getcwd();
来源：http://dali.fzhhl.top/Article/details/gt2haeclzbv.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2ecjwoafm.html

TS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gt2dicpjnvm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gt2clytfhpf.html

Go:   os.Getwd()
来源：http://dali.ydzc1.top/Article/details/gt2kckoicja.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gt2utzjoqjt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gt2wiqczwcd.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gt2grldufeb.html

Py:   sys.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hnnalekq.html

PHP:  exit(1);
来源：http://dali.pycfn.com/Article/details/gt2qvtlwvkx.html

JS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2shvgqgdk.html

TS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2ghrlzndk.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2kbtcjwsh.html

Go:   os.Exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2kftqrlvh.html

Ruby: exit 1
来源：http://dali.andypj.xyz/Article/details/gt2xtwbbebk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gogol.net.cn/Article/details/gt2fbakriex.html

[M06] 向标准错误输出
来源：http://dali.sxryk.cn/Article/details/gt2zkyyndpf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gt2mrmfqwae.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.feifeiyinyue.top/Article/details/gt2qnlzukzf.html

JS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vpppkbgp.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gt2hwtikcic.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gt2hawkjmyt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gzhubu.top/Article/details/gt2epmbggrc.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gt2lpatgdhn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gt2kbixexki.html

[M07] 判断是否为主入口
来源：http://dali.9152youxi.cn/Article/details/gt2fnwmobgh.html

Py:   if __name__ == "__main__":
来源：http://dali.sufxvd.cn/Article/details/gt2owcqjdbp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gt2zqvkvchc.html

JS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2knqpnkvc.html

TS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gt2gflsyysl.html

Java: public static void main(String[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gt2elpnpkte.html

Go:   func main()
来源：http://dali.yanxiufei.cn/Article/details/gt2fwycpfor.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuanzhike.top/Article/details/gt2cljbjfoh.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gt2fghuklsu.html

[M08] 获取系统与运行时信息
来源：http://dali.shzxlz.cn/Article/details/gt2tnbxhoue.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qvkkveat.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gt2skgwfowm.html

JS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gt2buvciyir.html

TS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gt2cjzodgrz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhoulong.xyz/Article/details/gt2pyxmyuff.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhiwuduotai.top/Article/details/gt2lkaufuig.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.smart0.xyz/Article/details/gt2lqjcjxvs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gt2joufqmit.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2crezhsqq.html

N. 数据结构与算法
来源：http://dali.sweek.top/Article/details/gt2edmowyfr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2lzuhlequ.html

[N01] 二分查找（有序数组）
来源：http://dali.pengpengdd.cyou/Article/details/gt2fimpuhif.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2yxfbsvbf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gt2cmtqeqct.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2aatpwbgd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2xpmjaahz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tetjzcas.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2vjmzbwmm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zfhgtdql.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2cchzilej.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guannengcc.top/Article/details/gt2pctcwoqs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gt2jsimycfl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2wzdocntx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bxmunzru.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gt2aszldumy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xinyue.icu/Article/details/gt2gtqmrfpc.html

Go:   slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gt2qjrfmtaj.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gt2wofmvjmg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gt2nwiwcmuw.html

[N03] 快速排序（分治示例）
来源：http://dali.jlsjyb.cn/Article/details/gt2dvqapgbg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ybcxt.top/Article/details/gt2mbvoxvxp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pycfn.com/Article/details/gt2nqqbkyax.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gt2kwalskcj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gt2ciuerugx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gt2xarutzst.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yanxiufei.cn/Article/details/gt2pitdkeip.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shangyingyoupin.top/Article/details/gt2crteqmql.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yvedp.cn/Article/details/gt2hsayzrlw.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gt2qjipzjcm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gt2jrchbzgq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gt2tjaowubf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gt2ermklyof.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gt2leifywdr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ihizxzor.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhongyouzk.top/Article/details/gt2rmwxgedd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2wojgubth.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sweek.top/Article/details/gt2tvudvvbn.html

[N05] 最大公约数
来源：http://dali.nwbrower.top/Article/details/gt2qcrivdre.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gt2dtmcztpi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2scgtcvgy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2uuncahtn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2phihjqza.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gt2ydfnlhzu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jlsjyb.cn/Article/details/gt2sjvertjk.html

Ruby: a.gcd(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uiqvhrua.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.iojbl.cn/Article/details/gt2rddyzvgd.html

[N06] 判断回文字符串
来源：http://dali.iojbl.cn/Article/details/gt2enrgczqu.html

Py:   s == s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2hiyqriws.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2voseztgf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2eezipigo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gt2rjeswhub.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cashguo.top/Article/details/gt2wcenbtdk.html

Go:   // 双指针从两端比较
来源：http://dali.redwolf501.top/Article/details/gt2wisbeoka.html

Ruby: s == s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2kiuxvqfr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zcpcusgr.html

[N07] 两数之和（返回下标）
来源：http://dali.cucudq.cn/Article/details/gt2jakoisls.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xinyue.icu/Article/details/gt2uxmpicpu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gt2jysmifub.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xinyue.icu/Article/details/gt2ghklunja.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gt2atixfnbz.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gt2vejpmdbv.html


<!-- 参考信息 -->