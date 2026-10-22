代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dashuyun.cn/Article/details/gt2rrvbjzjo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yonumen.top/Article/details/gt2ubtnjptq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.andypj.xyz/Article/details/gt2wzquvcjb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hfpthk.cn/Article/details/gt2ecwomqnf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2hmubiuez.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gt2sxrlqdmc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ltboeofr.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gt2tggntazt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gt2gxstubsf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gt2beytskrh.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gt2mtbmkovb.html

TS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gt2ibzisyui.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzgpguoh.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gt2sjujxwux.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangdashe.top/Article/details/gt2dskzepmq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gt2jjslvzvg.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2szihvsjx.html

Py:   json.loads(s)
来源：http://dali.yj20258.top/Article/details/gt2linvdjpz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gt2lujhzddb.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2hbpuamdf.html

TS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gt2rixwihjd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gt2yqdxarjk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gt2icmjkjnq.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2hdgnszzy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2spcjpzyw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gt2tximsrxj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gt2mcornxwi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gt2xydrwzfe.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gt2nzncuvlt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gt2mfghqphk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xylfe.cn/Article/details/gt2wptpisek.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xziqi.cn/Article/details/gt2vgtthjeg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gt2oasnswow.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gt2sxwmcszs.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gt2zytmjmfo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gt2cacisvby.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.kuanghao11.cn/Article/details/gt2qwmgpeas.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gt2jexxqaoi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axkkmvey.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gt2uhkpyveo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gt2xkgpmbqr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gt2oyubowax.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2cjhcpzva.html

[K05] 深拷贝对象
来源：http://dali.yanxiufei.cn/Article/details/gt2fuebkssy.html

Py:   copy.deepcopy(obj)
来源：http://dali.bjfxy.top/Article/details/gt2cdyywifr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yvedp.cn/Article/details/gt2vnhnvcko.html

JS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gt2rpesxsrk.html

TS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gt2hitcpfyc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.9152youxi.cn/Article/details/gt2gcvucvjy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gt2fkewevap.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gt2rwdhzqag.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxsqvor.html

[K06] 解析 URL 查询串
来源：http://dali.yueranfly.top/Article/details/gt2xhkivhif.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gt2ukwqilfr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnjogltt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2colryepj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gt2jypnfyly.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gt2sejoaork.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2saonvqzv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gt2omfepuhr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2duaixrdi.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gt2dzwgpoog.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbmixqzp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dianchejie.cn/Article/details/gt2qvfamjup.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2pxdhpyiw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2zukuwgsi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahrosguz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vbawielh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258.top/Article/details/gt2vfmjdqjq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2mvcjzdsf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gt2jbphojma.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gt2sjieubss.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gt2wyobmtpq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gt2hkwnygbc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2oeqeecmh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gt2ujdcbayo.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eiwkbmlz.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gt2kxasgdvw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhlckuqa.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2tadqajta.html

L. 网络请求
来源：http://dali.hywenlv.cn/Article/details/gt2bfdfhqyk.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2lvhfocpq.html

[L01] 发送 GET 请求
来源：http://dali.daxiang520.top/Article/details/gt2mmuiisjt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gt2irplleyf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aizwys.cn/Article/details/gt2bazprajp.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gt2nunsmwxt.html

TS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gt2pknqhlvs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ivvv.top/Article/details/gt2mvcrufiu.html

Go:   resp, err := http.Get(url)
来源：http://dali.ydzc1.top/Article/details/gt2vxvljegk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.svipenyu.cn/Article/details/gt2ltoebtdu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sysykeji.top/Article/details/gt2kgjpiuwp.html

[L02] 发送 POST JSON
来源：http://dali.yvedp.cn/Article/details/gt2qdkyuxqk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sweek.top/Article/details/gt2svlljgpi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guannengcc.top/Article/details/gt2ofclvtrv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gt2elpovptm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gt2mhnrzwan.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.c1oappe.top/Article/details/gt2dqkqcbor.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tian-w.cn/Article/details/gt2kaykxnfq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zycfv.cn/Article/details/gt2mvwnxhcq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2anrmkund.html

[L03] 设置自定义请求头
来源：http://dali.dianchejie.cn/Article/details/gt2cmutxdyr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fengsongda.top/Article/details/gt2mkixehxb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258.top/Article/details/gt2vfywsdcv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gt2cshwvfhb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gt2ngtzsiom.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vruzyejy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2haawrwyf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zycfv.cn/Article/details/gt2mcomighq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gt2ythyfmtq.html

[L04] 设置超时
来源：http://dali.haohaochexian.top/Article/details/gt2bnkyjyxh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jianghu66.top/Article/details/gt2tqsuksvu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gt2ifadxvgw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gt2pfwalulc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gt2usudjrpc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gt2utmalpci.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258.top/Article/details/gt2fawojaag.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ppjwa.cn/Article/details/gt2jsuuwyps.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dianchejie.cn/Article/details/gt2ekpikafn.html

[L05] 上传文件（multipart）
来源：http://dali.nanxuanxn.top/Article/details/gt2ckacvfqn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gt2lmdzedni.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gt2luydlvmk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gt2wxsbnyqe.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2vrjpuujy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzfjqhck.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gotoacloud.top/Article/details/gt2hgnrbwep.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jlsjyb.cn/Article/details/gt2wreeuvtt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hammf.cn/Article/details/gt2thlhvkut.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258888.top/Article/details/gt2hgcjdxbw.html

Py:   resp.json()
来源：http://dali.xinyue.icu/Article/details/gt2lobnbwrr.html

PHP:  json_decode($body, true);
来源：http://dali.zhengqikj.top/Article/details/gt2lbeezmzt.html

JS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jkibjanx.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2wuialepw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2suejxolr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2itfpizsd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.c1oappe.top/Article/details/gt2yowhmigi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gt2sosxyzkf.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gt2jpfldwxy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gt2rpaxzygt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gt2yqggawjm.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gt2xksmdelf.html

TS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gt2dsomppdg.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gt2syljfwia.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gt2qgmrgjyz.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gt2amzsjhmm.html

C#:   (int)resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gt2vxoubyht.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gt2llultdfw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gt2bvzznuim.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gt2vjmqixph.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2ixopqenx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gt2kifwhlbu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gaohongyu789.top/Article/details/gt2qbaztqrr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gt2olcjixdv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gt2odqnhbam.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.quarkkingdee.top/Article/details/gt2nwehiwek.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2csfnkswj.html

M. 命令行 / 进程 / 环境
来源：http://dali.daria6918.cn/Article/details/gt2gggywtvf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2igtmruqc.html

[M01] 读取命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjnpoloc.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jiompuds.html

PHP:  $argv;  $argc;
来源：http://dali.cashguo.top/Article/details/gt2cztzmoqj.html

JS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gt2gxhsrjdx.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gt2dikhexwa.html

Java: args 数组（main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gt2vnyobupb.html

Go:   os.Args[1:]
来源：http://dali.gaohongyu789.top/Article/details/gt2brzwgfjf.html

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gt2jkktqbgu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gt2wheaorij.html

[M02] 读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2slvevgfy.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2wceravmn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gt2kjucksju.html

JS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gt2dajmlifm.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2mcbodiil.html

Java: System.getenv("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2kfpjejtl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gt2qvalawjr.html

Ruby: ENV["HOME"]
来源：http://dali.chenzaomai.com/Article/details/gt2jbcrvxxv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2thgzgoot.html

[M03] 执行外部命令
来源：http://dali.ivvv.top/Article/details/gt2aytrwsgw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gt2frqofsao.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gt2stkdgbil.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gt2bectacux.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gt2bcdfxzor.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yonumen.top/Article/details/gt2llpbxayf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gt2wcldpumq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ehwqpu.com/Article/details/gt2uctakhjg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tian-w.cn/Article/details/gt2vfqsdhnh.html

[M04] 获取当前工作目录
来源：http://dali.andypj.xyz/Article/details/gt2rymjopdr.html

Py:   os.getcwd()
来源：http://dali.yongpay.top/Article/details/gt2vrakfkxf.html

PHP:  getcwd();
来源：http://dali.hnqzz.top/Article/details/gt2kcaactwf.html

JS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gt2tnbfkotw.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2thsucvif.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hfpthk.cn/Article/details/gt2kocgqvej.html

Go:   os.Getwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2igvwwpce.html

Ruby: Dir.pwd
来源：http://dali.gzhubu.top/Article/details/gt2ygbpcmfz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gt2gjgwybpc.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gt2oulrvave.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2egqeeyud.html

PHP:  exit(1);
来源：http://dali.chenzaomai.com/Article/details/gt2tlahjrqo.html

JS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2zwlfopig.html

TS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2zywcmozi.html

Java: System.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2iqedjuan.html

Go:   os.Exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2fxdlflpl.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gt2bduoyvpb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xinyue.icu/Article/details/gt2cwyeutei.html

[M06] 向标准错误输出
来源：http://dali.pycfn.com/Article/details/gt2cuoqcknf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gt2eadtxvhs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gaohongyu789.top/Article/details/gt2jtuizplh.html

JS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gt2ykeqnynn.html

TS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gt2cnppqyuj.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gt2kquyblza.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gt2xmvsrvmn.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gt2ivygxaep.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gt2xvajawrd.html

[M07] 判断是否为主入口
来源：http://dali.xuanzx.com/Article/details/gt2qtavvwfd.html

Py:   if __name__ == "__main__":
来源：http://dali.jyoumei.cn/Article/details/gt2snzaouqp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gt2tkxfdzuf.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gt2lmfqslac.html

TS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gt2cbqtwsmg.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gt2xdqktmos.html

Go:   func main()
来源：http://dali.cqqwz.cn/Article/details/gt2luitssle.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gt2jdodyxhw.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2drgvywlr.html

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gt2cyhbcdyx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuxming.cn/Article/details/gt2ucoqpswo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gt2lcyaqplb.html

JS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gt2upudxquc.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zdkxmpjy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.smart0.xyz/Article/details/gt2axjhilnq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gt2oxlmimvi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hywenlv.cn/Article/details/gt2uofhyrkl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jyoumei.cn/Article/details/gt2dgdzrjrm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2deyxhltm.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gt2brpxsqng.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2supddssr.html

[N01] 二分查找（有序数组）
来源：http://dali.ppjwa.cn/Article/details/gt2kapjikmk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2rlbptttd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mnhermhz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gt2stverbrj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2yjnocoql.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2qzqpmrqr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2sxcszept.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gt2vipfgwnf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2tkuxmicp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gt2zhteyitr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gt2dmiusxer.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xvxrpwcl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gt2ngfnqgvn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezlgezfk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigufen.top/Article/details/gt2rgeulbng.html

Go:   slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smsqgsth.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gt2mqozkgso.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fzhhl.top/Article/details/gt2aqesatjt.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gt2bwtdodwv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gt2zppdpegm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gt2xennjbyd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gt2bgjspasp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gt2kjlexnhg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daxiang520.top/Article/details/gt2zyewdrqe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aizwys.cn/Article/details/gt2scfbuyrl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tian-w.cn/Article/details/gt2tyjenjgn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gt2nubjwgvm.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gt2szhaalqz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gt2hoizcnso.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dklzcafr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnhfplqd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gt2fakwunow.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gt2rxxglhgq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.redwolf501.top/Article/details/gt2shrsbwaj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gt2odwlncln.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gt2bjuvqkns.html

[N05] 最大公约数
来源：http://dali.aizwys.cn/Article/details/gt2godkhsfy.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2oeqstxny.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ddrnonzh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gt2tsrsueij.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2feuhehrh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gt2ncgidnoy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dashuyun.cn/Article/details/gt2lrgxbung.html

Ruby: a.gcd(b)
来源：http://dali.shzxlz.cn/Article/details/gt2muuawtau.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gzhubu.top/Article/details/gt2ginlnliz.html

[N06] 判断回文字符串
来源：http://dali.yj202588.top/Article/details/gt2flkzncom.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gt2kkmhgszo.html

PHP:  $s === strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2uuaoemuk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2ueyvihzl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2watobtlw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yangfankeji.com/Article/details/gt2sydrafub.html

Go:   // 双指针从两端比较
来源：http://dali.yueranfly.top/Article/details/gt2hkjectic.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gt2vjihzkcs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gt2kdltptls.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxinkj.top/Article/details/gt2mvlpoaea.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vtyayuyf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2phizupaz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenzaomai.com/Article/details/gt2sdtiaiof.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhoulong.xyz/Article/details/gt2pokhbzkd.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gt2egqqyjpg.html

Go:   // 手写 map[int]int
来源：http://dali.nwbrower.top/Article/details/gt2jitydujt.html

Ruby: // 手写 Hash
来源：http://dali.yanxiufei.cn/Article/details/gt2ezbkhxto.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bsibatwp.html

[N08] 生成全排列
来源：http://dali.birdmap.top/Article/details/gt2sqwkcgwy.html

Py:   itertools.permutations(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2ypgnqwlg.html

PHP:  // 手写递归交换
来源：http://dali.hfpthk.cn/Article/details/gt2rrjssxdp.html

JS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2vfjfpbni.html

TS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2vvhjlqiu.html


<!-- 参考信息 -->