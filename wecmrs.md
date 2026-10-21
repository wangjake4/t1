代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yvedp.cn/Article/details/gtlwurujvn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtxszlqobz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtpmjjdmpd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sysykeji.top/Article/details/gtsdfmvhib.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gthqruwvyr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gtyhhhhovd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gtnhgcmgrm.html

[J10] 取今天 / 本月第一天
来源：http://dali.316326.xyz/Article/details/gtjnbszcil.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gtywcirfsn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ehwqpu.com/Article/details/gtzervtfqf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gtziqdknba.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtzjpgmitb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guannengcc.top/Article/details/gtipxeckwo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnxiangtu.top/Article/details/gtnondapkv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gtwnlzypuc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpfsqlcz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbjhsiyoy.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gtxpxagoih.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtuxodsood.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfswrupa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtqephfucl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gtbwfycbnl.html

JS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gtzwtnsefd.html

TS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtmkdkiiic.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gtisdbuvat.html

Go:   json.Marshal(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtvuokksfx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xziqi.cn/Article/details/gtlgiupxky.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ydzc1.top/Article/details/gtyybnbcvh.html

[K02] JSON 字符串转对象
来源：http://dali.tian-w.cn/Article/details/gtiarrehms.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gtwuxnaudv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gtinesdifo.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtuqofkiln.html

TS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtqymknoix.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtdeeojdhj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtsbxanifn.html

Ruby: JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtyhndozsg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hfpthk.cn/Article/details/gtuuqvmcqz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxinkj.top/Article/details/gtuqbknlta.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtnxbmqscp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnskpria.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gtvynghqac.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gttbjpwdry.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.smart0.xyz/Article/details/gtkkbxexfb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gtbqzkgjxb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gtznfsblem.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnxiangtu.top/Article/details/gtharhdvaz.html

[K04] 读取 JSON 文件
来源：http://dali.ivvv.top/Article/details/gtmafywpcg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gttfqycjye.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jianghu66.top/Article/details/gtystphybz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtlqmprgus.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtcwtwfvon.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtusdluhwl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtmnzhtere.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtemzzkeah.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtnvlqxcvf.html

[K05] 深拷贝对象
来源：http://dali.dianchejie.cn/Article/details/gtajuzwliz.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenzaomai.com/Article/details/gthkuqgmby.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gtuadzqjpu.html

JS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtilidngbw.html

TS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtkgqdzuus.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gtaaccokfs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gtblwhhona.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwelziwv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gtetumdnuv.html

[K06] 解析 URL 查询串
来源：http://dali.yuanzhike.top/Article/details/gtylqamgdp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtyaygrmji.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.havefunace.top/Article/details/gtietjogjl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gtawesevek.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gtzrvbqtzd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigfzy.top/Article/details/gtgfzcffpc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtywxaqspb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtdlvmrqbq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtphpdaxvu.html

[K07] 进制转换
来源：http://dali.redwolf501.top/Article/details/gtjqhifrng.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtokqjlcwi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ybcxt.top/Article/details/gtuaximvsd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhfeigyt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gteseeeotl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtzwtmdffe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangshuangyany.cn/Article/details/gthjqizdfs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.c1oappe.top/Article/details/gtbxsfwgzg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtqgdgqlzm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gtuavvrbrq.html

Py:   pickle.dumps(obj)
来源：http://dali.yj202588.top/Article/details/gtgsrxjazz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhbebyhu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtbvdzxqtm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gtcklqdkal.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sxryk.cn/Article/details/gtjfvkssrq.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydqnhqty.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtmiohnues.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtiseoialz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtggklhyru.html

L. 网络请求
来源：http://dali.jianghu66.top/Article/details/gtsfsxfolj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjnlflnxl.html

[L01] 发送 GET 请求
来源：http://dali.hongshengwenyu.top/Article/details/gtfuttbtvu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gtphsawsfj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gtgmmhnkce.html

JS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gttxpupwcw.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmghjaef.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ybcxt.top/Article/details/gtebwqzqpk.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gtgbxdlxnn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenlongwang.top/Article/details/gtlhxgtqyn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gtafausjls.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gtrtylucpi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gtopjczzxu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pycfn.com/Article/details/gtwgaljswy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtemqatimi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtginlwsqk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gtncbqdfho.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daxiang520.top/Article/details/gtzjkbmnjb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxinkj.top/Article/details/gtiimcrxbh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gaohongyu789.top/Article/details/gtwtlhfgrg.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gtdmotumsr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gtffwxckav.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpkcrluh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtbtszjrhg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvawdyyfn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuanzx.com/Article/details/gtwbvaelji.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtrkktvwrf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tianlin.xyz/Article/details/gtbgspoirj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gtkeqjknkf.html

[L04] 设置超时
来源：http://dali.yuanzhike.top/Article/details/gtlymkeslm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gtfwkwbewc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xziqi.cn/Article/details/gtaabkikcd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtzppycgfm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gtrigggtgh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cucudq.cn/Article/details/gtibztcazn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ydzc1.top/Article/details/gtxdfjrznz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.havefunace.top/Article/details/gtjbclvqyi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.andypj.xyz/Article/details/gtlnenewli.html

[L05] 上传文件（multipart）
来源：http://dali.yj202588.top/Article/details/gtebpyvpnj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhixingplan.top/Article/details/gtjrxzjcmr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yangfankeji.com/Article/details/gtriqqjcsf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gtdgizddqj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtxznpjpwb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hywenlv.cn/Article/details/gtatbffpcs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gtwsqhpbmz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gthabswuxg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtzuclggjr.html

[L06] 解析响应为 JSON
来源：http://dali.dianchejie.cn/Article/details/gtegszdmzu.html

Py:   resp.json()
来源：http://dali.guannengcc.top/Article/details/gtsqkutcln.html

PHP:  json_decode($body, true);
来源：http://dali.jyoumei.cn/Article/details/gtmtncdcwy.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gtwgtjnajl.html

TS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtvhaffwrv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtrxsyvaqk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj202588.top/Article/details/gtoyzogtqo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gtcmlbnsul.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jiagoushi.top/Article/details/gtnpxcxhsq.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtdaofpqfk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gtgugqegjo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.kuanghao11.cn/Article/details/gtpzalwrjt.html

JS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtvnpdahva.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtalmdcalc.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gtzrmjpnqb.html

Go:   resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gtpbxbkani.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gtwdffakun.html

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtsecrgpff.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gturscrraf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cashguo.top/Article/details/gtiefgqszi.html

PHP:  curl_multi_init() 系列
来源：http://dali.jlsjyb.cn/Article/details/gtjiperbhl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gthzodofjs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtujwfmlpy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gtlwupwiuc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sysykeji.top/Article/details/gtlfxnxcle.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gtcrstixfa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daria6918.cn/Article/details/gtgndndqse.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtbbimxomp.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gteelhtgux.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtudqajwxs.html

[M01] 读取命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtjoprrzwx.html

Py:   sys.argv[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtitjxvdyv.html

PHP:  $argv;  $argc;
来源：http://dali.jiagoushi.top/Article/details/gtidysowsw.html

JS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtenwlqkau.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtcymtjzrj.html

Java: args 数组（main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtonsrmvsf.html

Go:   os.Args[1:]
来源：http://dali.smart0.xyz/Article/details/gtnhmeyepd.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gtcaltdftn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtonupzgci.html

[M02] 读取环境变量
来源：http://dali.smart0.xyz/Article/details/gtdtdownku.html

Py:   os.environ.get("HOME")
来源：http://dali.havefunace.top/Article/details/gtxtuhuner.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtubjyffnd.html

JS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtrblblozy.html

TS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtdutbmdcu.html

Java: System.getenv("HOME")
来源：http://dali.sweek.top/Article/details/gtwrtjihdg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.birdmap.top/Article/details/gtknmpzhkf.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gtyaxlqzlt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gttotnifju.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gthalntpxn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gtxjyiyseq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gtkfsjgrru.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtybjsbnep.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtdqdswabx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.svipenyu.cn/Article/details/gtnfpewnuj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gtbxoelcrp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cucudq.cn/Article/details/gteeechesg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gtrutidrkc.html

[M04] 获取当前工作目录
来源：http://dali.xziqi.cn/Article/details/gtqawnijyl.html

Py:   os.getcwd()
来源：http://dali.tianlin.xyz/Article/details/gtwwesabxs.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gtuzofrddx.html

JS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtohzhnjqm.html

TS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtvawfimsl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gtmactslne.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gtpktidobc.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gtgquftaph.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gtvkyuagpx.html

[M05] 设置退出码
来源：http://dali.daxiang520.top/Article/details/gtivtoplyz.html

Py:   sys.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtshlpuila.html

PHP:  exit(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtsobepguw.html

JS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtplqrutul.html

TS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtvpmkfkfr.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gttqygguex.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gtuhuoutom.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gtxyjwlwtx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gtqqtbcnls.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gthlegzkum.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gtdvooqdru.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.vqdsnc.cn/Article/details/gtoyvcduhz.html

JS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtyybdykam.html

TS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gtdyseuyuu.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtffooywfd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.andypj.xyz/Article/details/gtsryatrhm.html

Ruby: warn "err"
来源：http://dali.dashuyun.cn/Article/details/gtwsovlmfj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gtowdsunbn.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gtktiqkytf.html

Py:   if __name__ == "__main__":
来源：http://dali.tanke756.top/Article/details/gtuygvtzly.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.316326.xyz/Article/details/gtelwvxrqp.html

JS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtasfhxbxi.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtjccwsadt.html

Java: public static void main(String[] args)
来源：http://dali.xylfe.cn/Article/details/gtdaovazwi.html

Go:   func main()
来源：http://dali.ehwqpu.com/Article/details/gtzqcpnguz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhengqikj.top/Article/details/gtdbzbctez.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gtaazuqvpc.html

[M08] 获取系统与运行时信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfaxnrcp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daria6918.cn/Article/details/gtvqlulsxk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gtdfsqblvp.html

JS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gttukzlekw.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtohcdyxhr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gtsnpweimh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gtuigpmikj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guowangkeji.top/Article/details/gtnwwlaaqu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gtjtlylpgp.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtlfomylmx.html

N. 数据结构与算法
来源：http://dali.pycfn.com/Article/details/gtkyscnkzc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtlebghblk.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gtvtzvnpkz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtfzgqjdow.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtjikzdrov.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtdllbvbdf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gtkiggliov.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtmwwoageo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtmxoyqpai.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhengqikj.top/Article/details/gtrgizgvwt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtswnbjxeq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xinyue.icu/Article/details/gtnbagkpsg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gtnspoiudf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gtdyjpkwya.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtouzzahqt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtkvaaccpv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gtthzlomns.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtabqnfxcf.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtasbfkhqk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gtyklndozb.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigfzy.top/Article/details/gtbxgitiob.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.andypj.xyz/Article/details/gtonpjuktt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ybcxt.top/Article/details/gtbjmqzzsd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtepejvkoz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtwibyylev.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jiagoushi.top/Article/details/gtlmiathvl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gtvzpbqhid.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cdnleiting.top/Article/details/gtjrokqnbm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gotoacloud.top/Article/details/gtizlsqkzx.html

[N04] 斐波那契数列
来源：http://dali.fzhhl.top/Article/details/gtdnkbmumb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtqqrwpfcx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zycfv.cn/Article/details/gtfuvvrvzd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtzfjksefv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gttvqbzhsv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtzscorzzw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gthefspjmx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtduukyomr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtgvrxpebu.html

[N05] 最大公约数
来源：http://dali.wangdashe.top/Article/details/gthtkaimlf.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtsqlgrgmz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj202588.top/Article/details/gtothfhpdh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzmvlsdot.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gtclzdqpwc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gttkihhwmb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gtorhbcdue.html

Ruby: a.gcd(b)
来源：http://dali.kuanghao11.cn/Article/details/gtbfituphv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtkrzozthe.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gtnisaozgt.html

Py:   s == s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gtssiwafcu.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtxwgthpfr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtlxehclwf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtieaahhdy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yueranfly.top/Article/details/gtftmidirt.html

Go:   // 双指针从两端比较
来源：http://dali.snrcjt.cn/Article/details/gtfsnsmvtq.html

Ruby: s == s.reverse
来源：http://dali.yj20258.top/Article/details/gtylhuxtxn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gtbhuttvrz.html

[N07] 两数之和（返回下标）
来源：http://dali.bjfxy.top/Article/details/gtoivrfvsm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hfpthk.cn/Article/details/gtrjpfqxml.html


<!-- 参考信息 -->