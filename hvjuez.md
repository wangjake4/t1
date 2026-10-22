代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gt2oskyfgfi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gt2efneehfj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxinkj.top/Article/details/gt2jvychnuw.html

[J10] 取今天 / 本月第一天
来源：http://dali.gaohongyu789.top/Article/details/gt2hdpmswys.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jyoumei.cn/Article/details/gt2xaluoggn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gt2fxusqsbo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2zjgbzcmj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2jbybtvba.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gt2tnqxaofg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ehwqpu.com/Article/details/gt2thsybcmy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gt2fnplxeyb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2okapytfx.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ruzdijnl.html

K. JSON 与序列化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjctswnm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2foloabhy.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2kvekvbyg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gt2ltavnooh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lgbzdick.html

JS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gt2kfgxrgtv.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2bkorgmfp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aibaodan.cn/Article/details/gt2mqpdmfwa.html

Go:   json.Marshal(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2epzhcosk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhongyouzk.top/Article/details/gt2qclwesno.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2ghxgmesv.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gt2aowehwxy.html

Py:   json.loads(s)
来源：http://dali.316326.xyz/Article/details/gt2nkxnoxxf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gt2vivpwwqc.html

JS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gt2fribqukz.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uocozoca.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2okavmlto.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gt2hlunhxsd.html

Ruby: JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gt2tfqvdmqh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmdfcwnl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ivvv.top/Article/details/gt2oebibpdh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gt2nwurcgjj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gt2psrdodmb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2mqyiejgy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gt2bddnvbml.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gt2xlyxhjpq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxinkj.top/Article/details/gt2vbyzrfml.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.meibo888.top/Article/details/gt2zrjrvzcj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ozvxkakw.html

[K04] 读取 JSON 文件
来源：http://dali.ehwqpu.com/Article/details/gt2svrwjcmw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yongpay.top/Article/details/gt2znlgrbaa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.haohaochexian.top/Article/details/gt2xliwlfhn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gt2xwdbhgbr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2bpbtvncu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sysykeji.top/Article/details/gt2hfmoyoqq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gt2zckdpzts.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fengsongda.top/Article/details/gt2arqclvxo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jianghu66.top/Article/details/gt2uyxdmegk.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gt2iuvtetde.html

Py:   copy.deepcopy(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2vxaoxufg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guannengcc.top/Article/details/gt2wnkyzhkz.html

JS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2iuahgjzc.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2hrfuwfjo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gt2gtmwfijz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhiwuduotai.top/Article/details/gt2jekbvukp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhpyvipk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gt2qjdcdqos.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gt2jvvaobws.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktujorpw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zycfv.cn/Article/details/gt2feldqxok.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gt2oatpvplk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gt2znhbijdk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pycfn.com/Article/details/gt2vqfcopyl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2gczrciuh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gt2cvtpvnik.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gt2gmjluxie.html

[K07] 进制转换
来源：http://dali.vqdsnc.cn/Article/details/gt2cjhgcxms.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2cdcbjwgc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sxryk.cn/Article/details/gt2htiqrknr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2vtahjwdk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2vjhjeqxs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2dgnqvjjc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxuanxn.top/Article/details/gt2himqyohc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258888.top/Article/details/gt2zrhgvmde.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2jrojtxwu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jiagoushi.top/Article/details/gt2qogynddr.html

Py:   pickle.dumps(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2ozgatxei.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lupitmec.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gt2sxbarini.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gt2gopoyuir.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jianghu66.top/Article/details/gt2ltzqwcja.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dfzgnmas.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2knqosipm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gt2duqxdnaa.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2phoskdxy.html

L. 网络请求
来源：http://dali.dashuyun.cn/Article/details/gt2llmmynjp.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2rodgemmn.html

[L01] 发送 GET 请求
来源：http://dali.feifeiyinyue.top/Article/details/gt2ispjqlml.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hywenlv.cn/Article/details/gt2hbgfpfkk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yanxiufei.cn/Article/details/gt2yczaeexj.html

JS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gt2jnqveqpy.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gt2igrdxaix.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txreovlc.html

Go:   resp, err := http.Get(url)
来源：http://dali.gzhubu.top/Article/details/gt2fqaxecza.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ivvv.top/Article/details/gt2qpgqgnoc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gt2uqtvbejz.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gt2nzursacf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gt2pjfpumlj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gt2ikjkhfos.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gt2ceulatcf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gt2fqmvrspk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zdqjudy.top/Article/details/gt2brrikcuz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.quarkkingdee.top/Article/details/gt2xddkvyae.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gt2izhsltrd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2becjgejt.html

[L03] 设置自定义请求头
来源：http://dali.quarkkingdee.top/Article/details/gt2aimdseef.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tianlin.xyz/Article/details/gt2bnpbwvlg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2fzkfgcyw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gt2cxyoaxoe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gt2abfijsai.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nwbrower.top/Article/details/gt2mqitiurc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gt2wopgwozf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gt2zorizzeh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gt2uayncruz.html

[L04] 设置超时
来源：http://dali.sufxvd.cn/Article/details/gt2vvhqypqe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zycfv.cn/Article/details/gt2vmjgmpcb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jlsjyb.cn/Article/details/gt2woajdxzz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gt2xusgncxb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gt2gxyloggi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gt2jfobyqhk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gt2efopgdfc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhoulong.xyz/Article/details/gt2cwiboiry.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ybcxt.top/Article/details/gt2nyqttgvc.html

[L05] 上传文件（multipart）
来源：http://dali.bjfxy.top/Article/details/gt2knxmxmdx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgufenzy.top/Article/details/gt2ipwmrmnm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gt2tpsxsxvo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gt2qjsjeyjd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdczcwnr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gt2xcqcbtxp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vqnjaaqe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gt2arwqxxsp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2ahlriisr.html

[L06] 解析响应为 JSON
来源：http://dali.yonumen.top/Article/details/gt2lhqxvbly.html

Py:   resp.json()
来源：http://dali.yongpay.top/Article/details/gt2mmunkygs.html

PHP:  json_decode($body, true);
来源：http://dali.chenzaomai.com/Article/details/gt2ipmkbgsz.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2htkvnyli.html

TS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gt2hqeerlqo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2gbaritvd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gt2yyznrexu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zdqjudy.top/Article/details/gt2mfhymyfj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fzhhl.top/Article/details/gt2xxnmitnb.html

[L07] 处理 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gt2thmeotjk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gt2vyotqahl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.havefunace.top/Article/details/gt2tlcgpjaw.html

JS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2ybjueeuc.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2zqkhhghk.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gt2ifzrcqys.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gt2bcfotawu.html

Ruby: resp.code.to_i
来源：http://dali.zhongyouzk.top/Article/details/gt2dtruyaca.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gt2bztvcwuo.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gt2kbnkidzz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gt2mtwewifu.html

PHP:  curl_multi_init() 系列
来源：http://dali.xinyue.icu/Article/details/gt2enfeafxm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2zwjvupxd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gt2zdgdqlqu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tianlin.xyz/Article/details/gt2ecjfjsoq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sysykeji.top/Article/details/gt2ylctrdns.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gt2eryjbpjz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gt2kwlxepst.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2jczanfgr.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gt2iysrdzih.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ugwzawfb.html

[M01] 读取命令行参数
来源：http://dali.sxryk.cn/Article/details/gt2yxppzqer.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gt2axitxkzn.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gt2lotsklll.html

JS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gt2qpxzfqho.html

TS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gt2emtfmpan.html

Java: args 数组（main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gt2gyrafjby.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gt2dbplpcwc.html

Ruby: ARGV
来源：http://dali.zdqjudy.top/Article/details/gt2uyhfnuyf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gt2wvhyyzac.html

[M02] 读取环境变量
来源：http://dali.andypj.xyz/Article/details/gt2mxwnqzvu.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cukijzlk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2ciavxrzn.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gt2wynfpism.html

TS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gt2qgojqvfp.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2zfyximfb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmcgpwfh.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gt2ywxiaaxp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2tacxzcca.html

[M03] 执行外部命令
来源：http://dali.gaohongyu789.top/Article/details/gt2gznkvnei.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zycfv.cn/Article/details/gt2ddyxyylk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ixxvzzst.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2wyzefuqe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gt2aioljrzy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnqzz.top/Article/details/gt2qxfmlcxq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gt2mperende.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxinkj.top/Article/details/gt2wwrtbffo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gt2grdmeftc.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gt2vvfrrtrz.html

Py:   os.getcwd()
来源：http://dali.chenlongwang.top/Article/details/gt2vejfblgg.html

PHP:  getcwd();
来源：http://dali.cucudq.cn/Article/details/gt2jjccdlkk.html

JS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gt2atrvsqda.html

TS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnswilrm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.smart0.xyz/Article/details/gt2cbqaefzq.html

Go:   os.Getwd()
来源：http://dali.wangdashe.top/Article/details/gt2wwklkzpa.html

Ruby: Dir.pwd
来源：http://dali.tianlin.xyz/Article/details/gt2djtrgptw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmfuafmb.html

[M05] 设置退出码
来源：http://dali.zhengqikj.top/Article/details/gt2bzssjlxu.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2uxlkouot.html

PHP:  exit(1);
来源：http://dali.jiagoushi.top/Article/details/gt2ynvhulbz.html

JS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2zxxqftey.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jrxeexwc.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rtlaarqj.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2mrpfstuu.html

Ruby: exit 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkuaenlr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkvdhioz.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gt2qxsfayio.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gt2ydqrkjxa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ehwqpu.com/Article/details/gt2clwtqylj.html

JS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gt2lbuajbyb.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gt2aofyxeot.html

Java: System.err.println("err")
来源：http://dali.svipenyu.cn/Article/details/gt2bcvxivww.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qwpqtcyu.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gt2qohpzwin.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gt2zgmomzsl.html

[M07] 判断是否为主入口
来源：http://dali.iojbl.cn/Article/details/gt2iumfpymh.html

Py:   if __name__ == "__main__":
来源：http://dali.ehwqpu.com/Article/details/gt2cdopjnde.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gt2icypnpre.html

JS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gt2hlhbzcvk.html

TS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gt2lyqijiuh.html

Java: public static void main(String[] args)
来源：http://dali.guannengcc.top/Article/details/gt2vjfsapmu.html

Go:   func main()
来源：http://dali.chenlongwang.top/Article/details/gt2eocoysss.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gt2jzxxncom.html

C#:   static void Main(string[] args)
来源：http://dali.nwbrower.top/Article/details/gt2vtnfboyu.html

[M08] 获取系统与运行时信息
来源：http://dali.0kj1m.cn/Article/details/gt2lpwyebum.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shuidangran.top/Article/details/gt2fxkdfukc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dashuyun.cn/Article/details/gt2woyfjahx.html

JS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gt2lrqgxrmv.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gt2syckomtn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gt2cdjufqjv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gt2wbiedugh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gt2cpalhiyu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj202588.top/Article/details/gt2xrktcqvy.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ctuqyrdk.html

N. 数据结构与算法
来源：http://dali.vqdsnc.cn/Article/details/gt2julioimv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2zkdclmfo.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gt2nrhtcmuq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2sfavwopm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cdnleiting.top/Article/details/gt2llmgfdfp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gt2gcovjojp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gt2segvjrlx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxhpwzc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2sgjpaihl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eaapfvjv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2mdwslofr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gt2zhdhpcmn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gt2clqtqifi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gt2cxmjmxce.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gt2saygmbrp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gt2zsgxblqk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tanke756.top/Article/details/gt2fwkzqkok.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gt2ckdktihc.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gt2tokcdlgh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xtqtyscm.html

[N03] 快速排序（分治示例）
来源：http://dali.yanxiufei.cn/Article/details/gt2uuimiorj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cheryme.top/Article/details/gt2prouzcdn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gt2lcwexmyq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gt2rldaiazq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gt2nafnufdc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigfzy.top/Article/details/gt2tmkdsory.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gt2vpnxobnw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gt2vuegqdht.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cucudq.cn/Article/details/gt2pknzwgkm.html

[N04] 斐波那契数列
来源：http://dali.yanxiufei.cn/Article/details/gt2moeghdud.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gt2dghzxosi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gt2pelygxhh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2egdqjrud.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2kumxrskj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nwbrower.top/Article/details/gt2exuwqpzz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpvjokxc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gt2mqiskkaz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2krqduebb.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxrrdxgi.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ptzjimnz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tian-w.cn/Article/details/gt2wnmdbgpc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwqlkxzj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ndgcwdwj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhiwuduotai.top/Article/details/gt2esyqlegx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.vqdsnc.cn/Article/details/gt2ntlmwreh.html

Ruby: a.gcd(b)
来源：http://dali.hysaishi.cn/Article/details/gt2trkoypep.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cheryme.top/Article/details/gt2tkbegkbz.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmoxevu.html

Py:   s == s[::-1]
来源：http://dali.bjfxy.top/Article/details/gt2heatqysp.html

PHP:  $s === strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qulqhjzf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cuodsglf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gt2rmnalxib.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gt2qkqqofis.html

Go:   // 双指针从两端比较
来源：http://dali.redwolf501.top/Article/details/gt2ddebtdsu.html

Ruby: s == s.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2lbhmbxqx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gt2lewzwupt.html

[N07] 两数之和（返回下标）
来源：http://dali.xylfe.cn/Article/details/gt2fyugyofj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258888.top/Article/details/gt2ctwwnzoq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gotoacloud.top/Article/details/gt2eiredkkw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fengsongda.top/Article/details/gt2rocwjepp.html

TS:   // 手写 Map<string, number>
来源：http://dali.andypj.xyz/Article/details/gt2albxdimm.html

Java: // 手写 HashMap
来源：http://dali.nwbrower.top/Article/details/gt2stcpniom.html


<!-- 参考信息 -->