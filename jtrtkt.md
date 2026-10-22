代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gt2zfvrybrt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2ztwdxwbk.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2xdkjshrg.html

TS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gt2qzsqkdsq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fengsongda.top/Article/details/gt2mzpfwogp.html

Go:   json.Marshal(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2dastvggc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gt2otrjxipd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ydzc1.top/Article/details/gt2tmnrxsds.html

[K02] JSON 字符串转对象
来源：http://dali.fzhhl.top/Article/details/gt2hhnofcdq.html

Py:   json.loads(s)
来源：http://dali.shuidangran.top/Article/details/gt2huzrxwox.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258888.top/Article/details/gt2begkbqpz.html

JS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2ogomapvj.html

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gt2dmbtrqoh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2njckpout.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gt2dzurrajt.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2jpcgdwcq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xinyue.icu/Article/details/gt2jqjqddfm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gt2buxuktlt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gt2cgkzplcy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gt2trvncfpr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2lrqcwiht.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gt2qljqyptw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2pbopyjlc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gt2xsykerzp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.havefunace.top/Article/details/gt2mycjhjky.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gt2yzlllndm.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gt2khdinrqw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gaohongyu789.top/Article/details/gt2gevvysim.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gt2ngvtephd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gt2ggkqfgnz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2cskwmkge.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.316326.xyz/Article/details/gt2ntnfcqvx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gt2hfvapqrk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gt2tqngzppu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gt2hppaugxl.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gt2copbgndo.html

Py:   copy.deepcopy(obj)
来源：http://dali.jianghu66.top/Article/details/gt2oxnuxnzq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.kuanghao11.cn/Article/details/gt2przhukwl.html

JS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gt2xymcnuax.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cmjpoxou.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj202588.top/Article/details/gt2epeevgcl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrmrichz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tanke756.top/Article/details/gt2duorbvyy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xziqi.cn/Article/details/gt2udzyhlme.html

[K06] 解析 URL 查询串
来源：http://dali.ppjwa.cn/Article/details/gt2qwrsmdkk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gt2txigfqsn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gezacvcf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gt2astvkymf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gt2nayxafdy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tian-w.cn/Article/details/gt2ibudpzyp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2ykfxutrk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2ikdcmyoq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2gheekicr.html

[K07] 进制转换
来源：http://dali.yuanzhike.top/Article/details/gt2doxtiuyr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwudwljs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nwbrower.top/Article/details/gt2ryvgxnnn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hlpomxjd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2nevcxxei.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2btgjrwjk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpfowvas.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yongpay.top/Article/details/gt2pglaiqmk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwfagmqt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guannengcc.top/Article/details/gt2waxoghgv.html

Py:   pickle.dumps(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2komjseni.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gt2cxdrybve.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gt2ibrlsqpq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xeuvbhpq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gt2nnaejwxo.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gt2aopntvan.html

Ruby: Marshal.dump(obj)
来源：http://dali.guannengcc.top/Article/details/gt2mahrgpyu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gt2dgxckdjj.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gzxdorql.html

L. 网络请求
来源：http://dali.hnqzz.top/Article/details/gt2aamqpbho.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2cciswpyb.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gt2gieyybxr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gt2hktpjpoe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daxiang520.top/Article/details/gt2xtyaupso.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gt2fpmolxdo.html

TS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2plxihxws.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gt2wprkbzqs.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fhkjnakz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuanzx.com/Article/details/gt2bimsnadu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gt2bqmswwss.html

[L02] 发送 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gt2xtkeldze.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gt2ealzqgqn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnqzz.top/Article/details/gt2lixddhom.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gt2dcvrpiou.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gt2mdjlbcmb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xylfe.cn/Article/details/gt2hxkfxnbz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.kuanghao11.cn/Article/details/gt2oltvcupo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zycfv.cn/Article/details/gt2wzqhgbnf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pycfn.com/Article/details/gt2rlywfnaj.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gt2njrqiuax.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2govotjmu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2jfxhzfjk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gt2sengfjwl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gt2luhdvjuv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uilbpmno.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gt2wjoezzds.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhengqikj.top/Article/details/gt2vugclrqg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gt2ueluzacw.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gt2ebtsnwnd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zycfv.cn/Article/details/gt2hucluxgb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gt2lxptmdkb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gt2oibnfway.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gt2pwqyunhj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuxming.cn/Article/details/gt2ppyrgvwo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gt2vatodhll.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gogol.net.cn/Article/details/gt2xqvdlbqy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ydzc1.top/Article/details/gt2giuvaqwq.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gt2dpxzmfcb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwdgmwpf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tian-w.cn/Article/details/gt2aayotvnw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gt2hqqlilap.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gt2pawmnyou.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdwffqgf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shuidangran.top/Article/details/gt2vhfyjgyk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxinkj.top/Article/details/gt2kbnfvwpo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2birvxlue.html

[L06] 解析响应为 JSON
来源：http://dali.yonumen.top/Article/details/gt2cqldfxay.html

Py:   resp.json()
来源：http://dali.yueranfly.top/Article/details/gt2xmmuzios.html

PHP:  json_decode($body, true);
来源：http://dali.meibo888.top/Article/details/gt2fiysjooe.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2wuhersfn.html

TS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gt2ojqkxkze.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2zlwadkmo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jiagoushi.top/Article/details/gt2ouvosasw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gt2xvulpnrx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xziqi.cn/Article/details/gt2skoyojbu.html

[L07] 处理 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gt2intxrytq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eelpznph.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gt2ikflzgoq.html

JS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gt2apsbzxum.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gt2dqxtdcxp.html

Java: resp.statusCode()
来源：http://dali.hnqzz.top/Article/details/gt2zhskrrlr.html

Go:   resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gt2lclybbol.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2lddhiptw.html

C#:   (int)resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gt2jgzwyrqi.html

[L08] 并发请求多个地址
来源：http://dali.haohaochexian.top/Article/details/gt2ptwkuytu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gt2qdfdujdb.html

PHP:  curl_multi_init() 系列
来源：http://dali.zdqjudy.top/Article/details/gt2rwblnvqb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gt2xfjxgxbc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gt2kgkkotzv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.kuanghao11.cn/Article/details/gt2aezaazbe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gt2nqgzxzkt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aibaodan.cn/Article/details/gt2itvzijtc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gt2ydnhgmvb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2svsvcxbd.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gt2vzrwwdpa.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvzcsglp.html

[M01] 读取命令行参数
来源：http://dali.pycfn.com/Article/details/gt2zlglkobp.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gt2vqqmjcod.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gt2atrjwmen.html

JS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gt2dtaoehpx.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gt2wutewtlo.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gt2whzurgsh.html

Go:   os.Args[1:]
来源：http://dali.gotoacloud.top/Article/details/gt2fbpgwmzn.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlkumhv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gt2lbqxyvid.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gt2adoagblt.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2zqqrxysz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2dpcuonnx.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gt2grrccvgh.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gt2okyncrwk.html

Java: System.getenv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2vwefkklg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2hzmyxlto.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gt2jnqwledr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2ekjwcecl.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gt2plnlbvlr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gt2cdtduzcz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kmjleysz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gt2epdnvaij.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gt2osbfucip.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgfcvxup.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2brzzegny.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.iojbl.cn/Article/details/gt2fzpejvga.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gt2zydxnkbd.html

[M04] 获取当前工作目录
来源：http://dali.zycfv.cn/Article/details/gt2xkdrpkir.html

Py:   os.getcwd()
来源：http://dali.tianlin.xyz/Article/details/gt2abhjnweb.html

PHP:  getcwd();
来源：http://dali.tianlin.xyz/Article/details/gt2zhixgpdk.html

JS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gt2tsiivblk.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gt2mbybrfcx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gt2bkxhlbyf.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gt2kgrvhddm.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gt2ggprrkpo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gogol.net.cn/Article/details/gt2gbhcjzeb.html

[M05] 设置退出码
来源：http://dali.smart0.xyz/Article/details/gt2ysxkcpvw.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2lwifdajl.html

PHP:  exit(1);
来源：http://dali.chenzaomai.com/Article/details/gt2yxarlykr.html

JS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2yhuntfzf.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2zxosruap.html

Java: System.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzibuzlm.html

Go:   os.Exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2ehbtfvin.html

Ruby: exit 1
来源：http://dali.meibo888.top/Article/details/gt2odvivqlr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.kuanghao11.cn/Article/details/gt2ocxocilj.html

[M06] 向标准错误输出
来源：http://dali.zhoulong.xyz/Article/details/gt2uoygxogi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kbatjmds.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cucudq.cn/Article/details/gt2ogkrzctv.html

JS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gt2yzkvtles.html

TS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gt2jbmavxpl.html

Java: System.err.println("err")
来源：http://dali.hfpthk.cn/Article/details/gt2brccmmum.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuxming.cn/Article/details/gt2uuvflaad.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gt2ewcuchqe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ppjwa.cn/Article/details/gt2kpdjcmai.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gt2mmjdkbqw.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gt2qwowmych.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhongyouzk.top/Article/details/gt2qypivznj.html

JS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gt2yvbdxlgj.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gt2encfxqoj.html

Java: public static void main(String[] args)
来源：http://dali.yj20258888.top/Article/details/gt2kaeppebt.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gt2mokocafx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sysykeji.top/Article/details/gt2zsndphzy.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxoctpom.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgufenzy.top/Article/details/gt2swoutgiu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tian-w.cn/Article/details/gt2pungxntf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.snrcjt.cn/Article/details/gt2cwxqymaf.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gt2priuftdu.html

TS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gt2bfhpttru.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuanzhike.top/Article/details/gt2gsoqckva.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hysaishi.cn/Article/details/gt2dnsxjqtt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2kigbgtes.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gt2kdqfpqow.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2sadrbjoz.html

N. 数据结构与算法
来源：http://dali.hysaishi.cn/Article/details/gt2mjrwzder.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwndqfmc.html

[N01] 二分查找（有序数组）
来源：http://dali.jyoumei.cn/Article/details/gt2fqrjstaw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2siykmmys.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ysuypqhl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gt2zpvmjkst.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gt2amfkbvmu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2rpdwzrca.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2qyzekary.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gt2oksicjuk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2ytvbqykf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yanxiufei.cn/Article/details/gt2fcpkwbuu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gt2fqodwggo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2kcuygvkx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gt2jyxlwslh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gt2nfciywxi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tanke756.top/Article/details/gt2orsnfqwe.html

Go:   slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gt2aikjkysf.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gt2pujllnyw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2locmowhg.html

[N03] 快速排序（分治示例）
来源：http://dali.sweek.top/Article/details/gt2fheegsmt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gt2djmunzjd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjolradi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gt2ngcgusuu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gt2nvyectos.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fpcljrlb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gt2jytpzdxo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nwbrower.top/Article/details/gt2ylzcdpwr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.redwolf501.top/Article/details/gt2adbpzrmr.html

[N04] 斐波那契数列
来源：http://dali.cheryme.top/Article/details/gt2dwqnbgdl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gt2nimodsnj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gt2noztsxap.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvvnqcn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gt2lbtfjday.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gt2xpobckvp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yongpay.top/Article/details/gt2osnhckhc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2fklertfx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gt2rkyczngp.html

[N05] 最大公约数
来源：http://dali.cucudq.cn/Article/details/gt2vhlizmvm.html

Py:   math.gcd(a, b)
来源：http://dali.jyoumei.cn/Article/details/gt2ygtolfle.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ivvv.top/Article/details/gt2xlarjcwd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gt2czrllhdr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gt2mpnuwlxg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gt2ywtetuhw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gogol.net.cn/Article/details/gt2eyinnsoj.html

Ruby: a.gcd(b)
来源：http://dali.316326.xyz/Article/details/gt2jhdgijyd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yanxiufei.cn/Article/details/gt2roqvgnsv.html

[N06] 判断回文字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwhdakph.html

Py:   s == s[::-1]
来源：http://dali.zycfv.cn/Article/details/gt2rbvranti.html

PHP:  $s === strrev($s);
来源：http://dali.ybcxt.top/Article/details/gt2lqfkuuaz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2qsittwib.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2uvacggwu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.snrcjt.cn/Article/details/gt2tuxwdlnw.html

Go:   // 双指针从两端比较
来源：http://dali.zhoulong.xyz/Article/details/gt2rjoigguy.html

Ruby: s == s.reverse
来源：http://dali.dashuyun.cn/Article/details/gt2whtoacph.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2xekqgbcg.html

[N07] 两数之和（返回下标）
来源：http://dali.yanxiufei.cn/Article/details/gt2bsuzhngt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fengsongda.top/Article/details/gt2zzgewtvn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.mhx1999.top/Article/details/gt2opelckrk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gt2lgsaasco.html

TS:   // 手写 Map<string, number>
来源：http://dali.hysaishi.cn/Article/details/gt2oyktzmuk.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xfohlzfx.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gt2gdqjvzmm.html

Ruby: // 手写 Hash
来源：http://dali.jianghu66.top/Article/details/gt2dvtuvdfk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ydzc1.top/Article/details/gt2rlnjuags.html

[N08] 生成全排列
来源：http://dali.bjfxy.top/Article/details/gt2lmnizvry.html

Py:   itertools.permutations(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2bbzshgll.html

PHP:  // 手写递归交换
来源：http://dali.yueranfly.top/Article/details/gt2xzlihmzr.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2jgxzvbnt.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2cntrqusc.html

Java: // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2ocxrlpat.html

Go:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2bkfjdipp.html

Ruby: arr.permutation.to_a
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjzgvxcg.html

C#:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2pitciwjl.html

[N09] 栈与队列
来源：http://dali.jinqigufen.top/Article/details/gt2xtywgbne.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2giaqapwy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuanzx.com/Article/details/gt2pemzzbux.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tcrzzgrd.html


<!-- 参考信息 -->