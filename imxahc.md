代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hammf.cn/Article/details/gtvqhbbmok.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shzxlz.cn/Article/details/gtzjmxudvt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guowangkeji.top/Article/details/gtxpryqgqy.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gtxhcdaxcq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtcbgwyrcn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gtnpfpmkit.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hywenlv.cn/Article/details/gtndiqsrkf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtbvrbchwv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.quarkkingdee.top/Article/details/gtreipltwh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gtjyjcmjta.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gtrhckridg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtqnqktdiq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtpwmplaje.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gthzyfopds.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtslyizfht.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtuecaujbe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gtbduvrlhz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpmptxnt.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtdeyzzkns.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gtfskcjkpi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgufenzy.top/Article/details/gtwzubhukh.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gtwrfiotgb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gtmuiwiost.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gtkctbecju.html

[K02] JSON 字符串转对象
来源：http://dali.sxryk.cn/Article/details/gtunklxzjw.html

Py:   json.loads(s)
来源：http://dali.316326.xyz/Article/details/gtucaoyjqv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xylfe.cn/Article/details/gthiswctmk.html

JS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtihzddvao.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtwlegkhza.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fengsongda.top/Article/details/gtxlyqmdel.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtbhglpowp.html

Ruby: JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtdbrbdafl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yonumen.top/Article/details/gtqmtneexo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gtdvjdgsgf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gtqxawbvhv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtmtpzvqkc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtduzpzwym.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gthyvfvyog.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.redwolf501.top/Article/details/gtxgmeycnl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hammf.cn/Article/details/gtqeictpqm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtnvetinda.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.quarkkingdee.top/Article/details/gtsxlafzpy.html

[K04] 读取 JSON 文件
来源：http://dali.xuetiantiany.cn/Article/details/gtqfbeigdg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gaohongyu789.top/Article/details/gtoxzrfdhf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tianlin.xyz/Article/details/gttjqqwkea.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtqcthjfbs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtepvlegsl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtxkynwmtv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtzblyiz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gthpjyinuq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtkjmtqwaf.html

[K05] 深拷贝对象
来源：http://dali.mhx1999.top/Article/details/gtbojatmlf.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gtofbnexfy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gtkwmsdlxs.html

JS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtcfnmfcpm.html

TS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtttptwzhm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cashguo.top/Article/details/gtjfpxetvi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yanxiufei.cn/Article/details/gtediucpyt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuetiantiany.cn/Article/details/gthwhaznhr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuxming.cn/Article/details/gtnombkxnc.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gtsfosftbp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daxiang520.top/Article/details/gtqtewsavd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gtvekvnbwx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtojwtyeeg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtcrdxbnxi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hywenlv.cn/Article/details/gthcchxztc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtmskutzwt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtypmvaenp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtrarrhaas.html

[K07] 进制转换
来源：http://dali.smart0.xyz/Article/details/gtojsqcymz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtozpzzjxi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gtmkxoapjr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gteeuzgxgv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtrhmxelye.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlprfvum.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gtkrxvmnwf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.bjfxy.top/Article/details/gttbfrhqts.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtducahlby.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.feifeiyinyue.top/Article/details/gttzxdujcy.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gtaceuwahx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gtlmeplrrh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gtfbsugxpp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtibpsxytn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gtktwdmmkv.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gtxapmtxyd.html

Ruby: Marshal.dump(obj)
来源：http://dali.ehwqpu.com/Article/details/gtfbyrtaet.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqpyjtms.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtwvcoyzkw.html

L. 网络请求
来源：http://dali.gaohongyu789.top/Article/details/gtmzhdslxa.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtpabpcpnf.html

[L01] 发送 GET 请求
来源：http://dali.sxryk.cn/Article/details/gtgeopvqkq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhengqikj.top/Article/details/gtzzhrctnn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gtqxjzpbnm.html

JS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtvuachbjq.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtahaabwdq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangshuangyany.cn/Article/details/gtgqefbrwp.html

Go:   resp, err := http.Get(url)
来源：http://dali.gotoacloud.top/Article/details/gtthdtwvfq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sufxvd.cn/Article/details/gtygihtfxa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ehwqpu.com/Article/details/gtlclmilux.html

[L02] 发送 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtcnsuplns.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbhbreyl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirrboxmt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtfpjzlbbx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtqclhudnz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.meibo888.top/Article/details/gtizoezaao.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yongpay.top/Article/details/gtspzjnwmh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hywenlv.cn/Article/details/gtuwsjzgpn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.316326.xyz/Article/details/gtsvkcxeqx.html

[L03] 设置自定义请求头
来源：http://dali.nanxinkj.top/Article/details/gtenkqmdgm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shzxlz.cn/Article/details/gtiapbhxlx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gtblqjgnwa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gthxsnhomn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gteieafknm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jlsjyb.cn/Article/details/gtyugmtrch.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gtozwemubp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xylfe.cn/Article/details/gtyngryvzs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtqdtdlqgu.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gtammatwzl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidlajujw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yonumen.top/Article/details/gtxncbcdbj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtbfcpbjcw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtgfodnxxj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtweszzvgy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gogol.net.cn/Article/details/gtrapdfcss.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gtdnczbzuy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.svipenyu.cn/Article/details/gtuxxivxqo.html

[L05] 上传文件（multipart）
来源：http://dali.wangshuangyany.cn/Article/details/gticylpxbz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gtxmfydpgb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sweek.top/Article/details/gtnwkexirt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gthpwkqhnk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtkrnsgniy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ydzc1.top/Article/details/gtjjwutbzf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhiwuduotai.top/Article/details/gtdhnwndsk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zycfv.cn/Article/details/gteyulykma.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ivvv.top/Article/details/gtlafykhfg.html

[L06] 解析响应为 JSON
来源：http://dali.mhx1999.top/Article/details/gtdbtrezjw.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gtwtsvgkid.html

PHP:  json_decode($body, true);
来源：http://dali.yongpay.top/Article/details/gtrqgyvsvh.html

JS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtmykiduts.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gthmmffakp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aizwys.cn/Article/details/gtngskpsjo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gtvhneiinl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnqzz.top/Article/details/gtjdqaywxy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenzaomai.com/Article/details/gtncplqrjv.html

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtciujcjjj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gtxoqjpjrh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ydzc1.top/Article/details/gtagzclbby.html

JS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtuqsremgh.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gtkpcshtxh.html

Java: resp.statusCode()
来源：http://dali.andypj.xyz/Article/details/gtjhkpflen.html

Go:   resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtpegzofci.html

Ruby: resp.code.to_i
来源：http://dali.ydzc1.top/Article/details/gtqytjgmwy.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gtoogiitda.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gttbsfjwxl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gtuwoxojdh.html

PHP:  curl_multi_init() 系列
来源：http://dali.aizwys.cn/Article/details/gtllhsdtfi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtjhcsscmm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gthmkytxxt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sweek.top/Article/details/gtmpzjnwlu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenjidiqi.icu/Article/details/gtpbgxxkhq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtvdogwndw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtkehjdmnu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtotsqnyee.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gtysobtqgo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtwagxdrky.html

[M01] 读取命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtoluxtipu.html

Py:   sys.argv[1:]
来源：http://dali.shzxlz.cn/Article/details/gtkcnqcqff.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gtqknmzlug.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gtbxcnqmid.html

TS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtmtwgkgmp.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvgtfffd.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtfpcceajs.html

Ruby: ARGV
来源：http://dali.shzxlz.cn/Article/details/gtldfgrqta.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gtwfzdyitu.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtgipcacmf.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gtwmgpvdkh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtewqwoqhg.html

JS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtqfrgwsgv.html

TS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gthunrvxua.html

Java: System.getenv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtsapdtgyd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtnufupkji.html

Ruby: ENV["HOME"]
来源：http://dali.zhongyouzk.top/Article/details/gtnzhfqszi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtsfaegdeb.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gtvavqdisc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.quarkkingdee.top/Article/details/gtlxkzggqu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigufen.top/Article/details/gtfvlxxkqj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtruewscqq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gtjzsmhmkw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gtbyjtqzdi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gtbgvwolye.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gtsualtwbi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gtjlnoxtvk.html

[M04] 获取当前工作目录
来源：http://dali.zycfv.cn/Article/details/gtyujwsswv.html

Py:   os.getcwd()
来源：http://dali.yuanzhike.top/Article/details/gthaceidiz.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gtrwmfcupz.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtyiklgmvs.html

TS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdagpoye.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dashuyun.cn/Article/details/gtysntezzj.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gtqtatyyfh.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gtglgptuhv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangdashe.top/Article/details/gttviszojs.html

[M05] 设置退出码
来源：http://dali.sufxvd.cn/Article/details/gtaxdprbeq.html

Py:   sys.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtvzcqtpxj.html

PHP:  exit(1);
来源：http://dali.shzxlz.cn/Article/details/gtweqmrmlp.html

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtvjpoxbwa.html

TS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gttoypzojb.html

Java: System.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtxvmhrfym.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gthplcbmqt.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gtcyadddzh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gtylvnquqp.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gtrbxawvvn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyxwblgn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gtbtcezwfn.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtyiysyzux.html

TS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gtidmmtjmo.html

Java: System.err.println("err")
来源：http://dali.svipenyu.cn/Article/details/gtbnvrcchs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pengpengdd.cyou/Article/details/gtxlkiewzx.html

Ruby: warn "err"
来源：http://dali.hywenlv.cn/Article/details/gtyhomywsd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yangfankeji.com/Article/details/gttwdikxom.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gteutuyydz.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gtprxhdrdh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gtuahyxxfi.html

JS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtfbewvfnm.html

TS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gtmbdtbonp.html

Java: public static void main(String[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoprcsedo.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gtjvckbedu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gtlonmdusq.html

C#:   static void Main(string[] args)
来源：http://dali.yvedp.cn/Article/details/gtjdadssgv.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gtswjioqnz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhnzblat.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxinkj.top/Article/details/gtzlesnacb.html

JS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtaxbdsnfi.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtvjfdkusm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fzhhl.top/Article/details/gtsdfbkacz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gtlnkltsum.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cucudq.cn/Article/details/gtcxdizaxh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhoulong.xyz/Article/details/gtkosjeucd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwwhkokdu.html

N. 数据结构与算法
来源：http://dali.hywenlv.cn/Article/details/gtfdzgniaz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtzhistgjr.html

[N01] 二分查找（有序数组）
来源：http://dali.yuxming.cn/Article/details/gtxnpkxton.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtxzzyncqw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtzudcnuht.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtehtmvthy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtrkfmmbzs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtyqycwlca.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtmfbeqzpw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.smart0.xyz/Article/details/gtkfpmqovd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gtetnptnab.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hywenlv.cn/Article/details/gtonsngphn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gttgjdwlrq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gtqdqvcwnp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtabcivyla.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdsfnhaz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gtcgezgbnl.html

Go:   slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtevguuqhw.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtqmbhjfir.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hammf.cn/Article/details/gtgapiulqu.html

[N03] 快速排序（分治示例）
来源：http://dali.xziqi.cn/Article/details/gtiuujecmu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gtlmpysskn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daxiang520.top/Article/details/gtdxkwovex.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtpvvldukm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtziwmlskm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.redwolf501.top/Article/details/gtatcbngys.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hfpthk.cn/Article/details/gtsjwdiqfa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gtbolmccte.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fzhhl.top/Article/details/gtekopnhkt.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gtwkrjxdaj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtnzmmhgoz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtmuqzrsod.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtgpxxnfhm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtdulqwljl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtywsfqmgi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yvedp.cn/Article/details/gtcvgsrtom.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidklfgzh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtjjmhdjpx.html

[N05] 最大公约数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaoqvklsj.html

Py:   math.gcd(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtpxpuiwbk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.bjfxy.top/Article/details/gtkwyoprtt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtffhhkruq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gtokgjllzj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hfpthk.cn/Article/details/gtkksipuph.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gtpggnddaj.html

Ruby: a.gcd(b)
来源：http://dali.andypj.xyz/Article/details/gtpskbkadk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gtibqgjpdn.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gtksdtckhc.html

Py:   s == s[::-1]
来源：http://dali.yonumen.top/Article/details/gtvnfcbuzy.html

PHP:  $s === strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gtmgafjnqh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtemvcjjdw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtmiskfaez.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pengpengdd.cyou/Article/details/gtlntzxplm.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gtjnkfqyld.html

Ruby: s == s.reverse
来源：http://dali.jiagoushi.top/Article/details/gthefnnhsc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gtzviydhes.html

[N07] 两数之和（返回下标）
来源：http://dali.zhengqikj.top/Article/details/gtrhgirgfv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlasmqgmv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gtgsockcjh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hfpthk.cn/Article/details/gtdgayvfaw.html

TS:   // 手写 Map<string, number>
来源：http://dali.xinyue.icu/Article/details/gtphnhmgen.html

Java: // 手写 HashMap
来源：http://dali.ybcxt.top/Article/details/gtblrpcmzj.html


<!-- 参考信息 -->