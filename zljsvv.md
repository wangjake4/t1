代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zdqjudy.top/Article/details/gt2hyluylmy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gt2xjnraizz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gt2vvibrrby.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.haohaochexian.top/Article/details/gt2bwoagbwc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gt2infhwtty.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gt2vbrginmk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gt2yeknbnkd.html

[J10] 取今天 / 本月第一天
来源：http://dali.hongshengwenyu.top/Article/details/gt2tliiizza.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gt2ybsrwmqq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gt2fnzajkbg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gt2lizqpueu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2kcbqgqmt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gt2lgbunufe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djdeevxn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuanzx.com/Article/details/gt2scqvkzaj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fengsongda.top/Article/details/gt2mqigmjmh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2zgtgjxmx.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gt2qvpeleeo.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2kdlnyqhc.html

[K01] 对象转 JSON 字符串
来源：http://dali.havefunace.top/Article/details/gt2gjzhovky.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gt2lxxdnmzz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gt2uzyfcdsc.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gt2awxkiefu.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2wgjqkbwp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ivvv.top/Article/details/gt2jgcintis.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gt2qwrhigix.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gt2jjddacxp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hammf.cn/Article/details/gt2rqprxucg.html

[K02] JSON 字符串转对象
来源：http://dali.zhoulong.xyz/Article/details/gt2vtxnzmnu.html

Py:   json.loads(s)
来源：http://dali.nanxinkj.top/Article/details/gt2inzpzzsk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tianlin.xyz/Article/details/gt2cinfjtop.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2nzwrdtqj.html

TS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2agpgavvn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2ohdenpbk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mcyfpcie.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2taoukrfo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gzhubu.top/Article/details/gt2qkahvvzi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gt2wdrqwxna.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gt2pkrhtvkr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2tkzqogvg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2uxvkkruo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2byhtbgan.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pycfn.com/Article/details/gt2pwghknqb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mbfodnkk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2fqjadyim.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuanzx.com/Article/details/gt2nippfzcd.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gt2jthtntlp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gt2mxmaqbox.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.quarkkingdee.top/Article/details/gt2fqtdhawz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlnzanbi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gt2fxmvzujw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ybcxt.top/Article/details/gt2lnhyxnmp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gt2cofbysbm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2lgdpkqfz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tanke756.top/Article/details/gt2bbfpwsfl.html

[K05] 深拷贝对象
来源：http://dali.xuanzx.com/Article/details/gt2rwxwzvch.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2ioestxzd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gt2nznjxnzs.html

JS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gt2kgrsmqnt.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gt2vuyntjhm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xinyue.icu/Article/details/gt2quaqkdhi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.316326.xyz/Article/details/gt2mfwnjpsm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gt2dilqmyyh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gt2xjxmsvym.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258.top/Article/details/gt2njlxgwga.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulzngjsu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.haohaochexian.top/Article/details/gt2bwmuyojs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gt2oqlvmugv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlzbdsb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hysaishi.cn/Article/details/gt2eqhlqqfr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2nqbpoutr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2qhmhgfcm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2waagfowg.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gt2wvkgudvo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2niqihroy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fengsongda.top/Article/details/gt2lueoudra.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gt2gyxucouj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2vpjafnqe.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2tfxnxjjy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gogol.net.cn/Article/details/gt2sezonuno.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.bjfxy.top/Article/details/gt2vvyszpnz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2glchkhbo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnqzz.top/Article/details/gt2iteqxltv.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2fkvzywiw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ybcxt.top/Article/details/gt2yyaiobqj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gt2lklunynn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gt2ixxihupx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gzhubu.top/Article/details/gt2nwzrifyb.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gt2lihxahnz.html

Ruby: Marshal.dump(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2qiksomar.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gt2bqqlommz.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2rawsfaxx.html

L. 网络请求
来源：http://dali.yvedp.cn/Article/details/gt2lonfgydx.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2xybqxkuh.html

[L01] 发送 GET 请求
来源：http://dali.9152youxi.cn/Article/details/gt2gqcvbgjv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dianchejie.cn/Article/details/gt2hikhhuxb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gt2pslgzjky.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2tkmxfkcj.html

TS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gt2tecylutq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.9152youxi.cn/Article/details/gt2wyancpuq.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvfrkipv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.meibo888.top/Article/details/gt2zaoslgms.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangdashe.top/Article/details/gt2rgsluuhq.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gt2uriivzrc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shuidangran.top/Article/details/gt2vfsgxlfi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dashuyun.cn/Article/details/gt2xyegdojo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gt2pejsypwp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntnichwd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yanxiufei.cn/Article/details/gt2aoxslzkm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbivmxrz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cashguo.top/Article/details/gt2kjcgarjo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj202588.top/Article/details/gt2iqtktstk.html

[L03] 设置自定义请求头
来源：http://dali.jlsjyb.cn/Article/details/gt2rxzvdpvl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zdqjudy.top/Article/details/gt2odsbexrg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gt2wcanpiaw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gt2zsorqgvs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gt2cvtzwcpk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.redwolf501.top/Article/details/gt2waewlxzm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gt2bbdvofpg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jyoumei.cn/Article/details/gt2gzaqwmrj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gt2bpybppro.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lnmardoa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.redwolf501.top/Article/details/gt2hpwokzzs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yueranfly.top/Article/details/gt2drmjhmvs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gt2ngcjvbok.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gt2aiijzddy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jyoumei.cn/Article/details/gt2qqbhyrdl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hammf.cn/Article/details/gt2crpwbcmd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sxryk.cn/Article/details/gt2dcckrddk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gt2fhvsolad.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dfldhvxj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gt2qjinhpcp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daria6918.cn/Article/details/gt2zghulhne.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gt2rfyfgotp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gt2uouabcib.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gt2kchlkoye.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cheryme.top/Article/details/gt2gzoexmjm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2efdbvuri.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2uucoavda.html

[L06] 解析响应为 JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2ypxectbc.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2wcfzjpby.html

PHP:  json_decode($body, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2agllivag.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gt2tlpjeuhy.html

TS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2ibzedkwz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2dutrxdrg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhiwuduotai.top/Article/details/gt2slnctbmt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgufenzy.top/Article/details/gt2rtkevhnl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dejtelnq.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gt2lceoivli.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gt2mfmsxwwl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yonumen.top/Article/details/gt2gbokpxvq.html

JS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gt2jzmkhkng.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gt2rpnioqev.html

Java: resp.statusCode()
来源：http://dali.bjfxy.top/Article/details/gt2idodzcxj.html

Go:   resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gt2kcsoxmxb.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gt2sgenoonr.html

C#:   (int)resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gt2xcipksqw.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gt2balgglmt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dashuyun.cn/Article/details/gt2uqbqruih.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gt2xadinozu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gt2aunsufiq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gt2vcydxjxq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jianghu66.top/Article/details/gt2xbsasnjr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hammf.cn/Article/details/gt2lzbmuydi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gt2wztwmzbr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.smart0.xyz/Article/details/gt2degubhsh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2zwkwtowb.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gt2fmjplxir.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ljlvkjjr.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gt2ynuuujba.html

Py:   sys.argv[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqvpdyit.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gt2ufksjyug.html

JS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gt2lpqgjovy.html

TS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gt2flpzftpu.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gt2alhuznjg.html

Go:   os.Args[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2pkenxkxs.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gt2wkmqsitv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gt2utlnojji.html

[M02] 读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2gwfxzcgo.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2dlzadamw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gt2cphizukf.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gt2fnezshlj.html

TS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gt2xbruecli.html

Java: System.getenv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2qawatmcv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2rbdjfoxd.html

Ruby: ENV["HOME"]
来源：http://dali.fengsongda.top/Article/details/gt2jxjgulsz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2txkdessa.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gt2jumekizx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdccshvr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gt2vssfaiie.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gt2qklciirv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xruiemnu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daxiang520.top/Article/details/gt2dyfuoifq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenzaomai.com/Article/details/gt2hvmkfnou.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fengsongda.top/Article/details/gt2koqtjdrz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gt2cdlvouav.html

[M04] 获取当前工作目录
来源：http://dali.0kj1m.cn/Article/details/gt2fsrlcqey.html

Py:   os.getcwd()
来源：http://dali.tanke756.top/Article/details/gt2pksmhlkw.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gt2yrfmkkas.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gt2ycwwmkze.html

TS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gt2yxssatzi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gt2opqyhfyz.html

Go:   os.Getwd()
来源：http://dali.jqgfzy.top/Article/details/gt2jtekxabn.html

Ruby: Dir.pwd
来源：http://dali.meibo888.top/Article/details/gt2hrqdspyv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fengsongda.top/Article/details/gt2mlwgruwc.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llusgeui.html

Py:   sys.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2hkqvdain.html

PHP:  exit(1);
来源：http://dali.jyoumei.cn/Article/details/gt2whjlcbou.html

JS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2hgakhxlf.html

TS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2xmbpcvhj.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2gnkvkgki.html

Go:   os.Exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2tzptatou.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gt2ssjfyfov.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gt2klmivync.html

[M06] 向标准错误输出
来源：http://dali.jlsjyb.cn/Article/details/gt2vjaxxpow.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gt2tzjjfwtr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.kuanghao11.cn/Article/details/gt2grusxigs.html

JS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gt2bakjoonp.html

TS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gt2yvmmxdzp.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gt2apqtvjjz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gt2gnrcggqp.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gt2xpebjjkv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbtjoru.html

[M07] 判断是否为主入口
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzdpjiiv.html

Py:   if __name__ == "__main__":
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2okwxibzg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cqqwz.cn/Article/details/gt2bhtkrevd.html

JS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gt2amhrdiph.html

TS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gt2wmxmhluz.html

Java: public static void main(String[] args)
来源：http://dali.yvedp.cn/Article/details/gt2jjcxggsv.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gt2hqcxskrd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gaohongyu789.top/Article/details/gt2fgvribyi.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gt2ndwinobg.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gt2tvkgteyl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ehwqpu.com/Article/details/gt2sliilfxz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhoulong.xyz/Article/details/gt2eymigxcd.html

JS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tcukokqn.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gt2vyfmglhg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gt2jjuphrvm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nwbrower.top/Article/details/gt2zkzhhcdx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ehwqpu.com/Article/details/gt2fafaghlx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.vqdsnc.cn/Article/details/gt2qakxezsw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2xwuxsopt.html

N. 数据结构与算法
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxmsbxgy.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2tmjgpvdm.html

[N01] 二分查找（有序数组）
来源：http://dali.redwolf501.top/Article/details/gt2nuydzljb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2cgawvblr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gt2tmhqkbit.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gt2qznbwqwg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gt2ijeynsjr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2ifjzbgfz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2stfbumjv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.birdmap.top/Article/details/gt2adypcnzs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2xlssijyw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gt2aplcqthc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gt2nkthbroz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2ehkwtssl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gt2pazhmpie.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gt2hadrsesy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hfpthk.cn/Article/details/gt2eanqinuk.html

Go:   slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gt2nahuvdei.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gt2qoicsnjc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sufxvd.cn/Article/details/gt2wvgpdmfx.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gt2vjhpkyif.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yonumen.top/Article/details/gt2kxwidccy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shuidangran.top/Article/details/gt2hmgzmkup.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gt2kvttnchp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gt2jxothvdr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2opbjdmfs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gt2ccrvqwqs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dashuyun.cn/Article/details/gt2dbpmdbcm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2laydmlfv.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzyvtpcm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2vvzxuitj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gt2rpudqnrk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpqjkdsp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gt2nhtgretw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kdhgzxlv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.vqdsnc.cn/Article/details/gt2xfftahpl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gt2risfytec.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vrcujtem.html

[N05] 最大公约数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykjreajq.html

Py:   math.gcd(a, b)
来源：http://dali.havefunace.top/Article/details/gt2yvhnsnjo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ofhkgjtp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gt2tilsdslb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gt2pcykqatd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.svipenyu.cn/Article/details/gt2iwleamuv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aizwys.cn/Article/details/gt2zefesbea.html

Ruby: a.gcd(b)
来源：http://dali.ivvv.top/Article/details/gt2otojqehq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gt2cmvjvjvm.html

[N06] 判断回文字符串
来源：http://dali.nanxinkj.top/Article/details/gt2ejoppbzp.html

Py:   s == s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gt2rhkziwar.html

PHP:  $s === strrev($s);
来源：http://dali.fengsongda.top/Article/details/gt2rntsqkwf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2hrqhmklh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2zzahhycf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ehwqpu.com/Article/details/gt2iteqpvkk.html

Go:   // 双指针从两端比较
来源：http://dali.hysaishi.cn/Article/details/gt2lrwgydrf.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gt2bjhlryfc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gt2jhlyaqdp.html

[N07] 两数之和（返回下标）
来源：http://dali.zhongyouzk.top/Article/details/gt2pmvgbyyf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gt2zriabxrn.html


<!-- 参考信息 -->