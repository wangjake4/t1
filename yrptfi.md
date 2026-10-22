代发 wailian999

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2suirhcwl.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gt2xlacyrtw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2gxsbrwpz.html

[K01] 对象转 JSON 字符串
来源：http://dali.dashuyun.cn/Article/details/gt2vlzmewdp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gt2odycyufs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wsdwxblr.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2yynaawzg.html

TS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2xwjpervq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.redwolf501.top/Article/details/gt2igfrckvo.html

Go:   json.Marshal(obj)
来源：http://dali.sweek.top/Article/details/gt2iquffuai.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aibaodan.cn/Article/details/gt2tepecovh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dcqyevdv.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gt2bawvybye.html

Py:   json.loads(s)
来源：http://dali.mhx1999.top/Article/details/gt2iykiuuby.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gt2aqkqxexo.html

JS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2jfdnzmej.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2ohtppbjx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gzhubu.top/Article/details/gt2fbzmzzev.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gt2ssubstra.html

Ruby: JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2vzhdysdf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yvedp.cn/Article/details/gt2coxncake.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gt2euvtwfrh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2avjrdcxp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gt2fephifmo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2jufgjsgk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gt2lzjokcte.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yongpay.top/Article/details/gt2htjvjtpi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dianchejie.cn/Article/details/gt2oifqtmoy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gt2gsdcdgjz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hammf.cn/Article/details/gt2hzwmgspq.html

[K04] 读取 JSON 文件
来源：http://dali.sufxvd.cn/Article/details/gt2cesbgrew.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gt2qztczogq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gt2nqgbyufh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gt2xupzpdht.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gt2fefzllaf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2bwuwjjmo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gt2pauojrll.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tanke756.top/Article/details/gt2ogbkwpyd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gt2ivmbuyxp.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gt2kgmagink.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gtayfrpo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.9152youxi.cn/Article/details/gt2onrojost.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gt2zdbcveim.html

TS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2viatvoew.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.havefunace.top/Article/details/gt2uocohqeg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangdashe.top/Article/details/gt2ykpkntgw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gt2lnueomts.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gt2ntniudpd.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gt2bblvwtus.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kquhkvmy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnqzz.top/Article/details/gt2rzbztvok.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gt2ohtjniyh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gt2zniixjav.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cqqwz.cn/Article/details/gt2vpctzess.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2gkquvcer.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2sskxbpyj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2pxhubnpf.html

[K07] 进制转换
来源：http://dali.pycfn.com/Article/details/gt2vgvtzlqh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ribczegc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.bjfxy.top/Article/details/gt2qbztcbxt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmnfnxvo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nfzaibqn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2urljgfua.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gt2hlmlznrp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gaohongyu789.top/Article/details/gt2qcncjtsf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2obiobyyp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gt2uoaqtlwg.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2rrulogbj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2xxowicpn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gt2uxpepyfj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2bilkjuih.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnxiangtu.top/Article/details/gt2nhfpanas.html

Go:   encoding/gob
来源：http://dali.jinqigfzy.top/Article/details/gt2whqvxysa.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2meucbuqy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gt2dkskrbkl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2rkbedjjt.html

L. 网络请求
来源：http://dali.ydzc1.top/Article/details/gt2igvizxou.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2adjtqhsc.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gt2tvbwjedg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.iojbl.cn/Article/details/gt2tvqltrbn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmzggjgo.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vizlanlb.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gt2arqfpwxm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guowangkeji.top/Article/details/gt2vedjplat.html

Go:   resp, err := http.Get(url)
来源：http://dali.cheryme.top/Article/details/gt2ufotulos.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gt2oktebonq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gt2gvyjdzby.html

[L02] 发送 POST JSON
来源：http://dali.xylfe.cn/Article/details/gt2nsqupzxw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gt2xqdzugyz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gt2azpszixp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gt2bfusypti.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gt2mccncrqe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gt2vfnuwcjc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gt2gvgrhiqk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhixingplan.top/Article/details/gt2timyuaux.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xinyue.icu/Article/details/gt2mhuvmwul.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gt2rjgfdjuv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gt2skmnrnmz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhengqikj.top/Article/details/gt2zuzbywal.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gt2xbqhqlgw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gt2jclwmrxt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sweek.top/Article/details/gt2apzdhnio.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gt2kyostfhy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gt2yasgfuii.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gt2xjhquuqi.html

[L04] 设置超时
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djmjqvmv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jlsjyb.cn/Article/details/gt2jnjgccob.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sweek.top/Article/details/gt2fnvaconu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gt2vgechgms.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gt2lsxjaieh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guannengcc.top/Article/details/gt2ejfjzebf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigfzy.top/Article/details/gt2rrzqtfpl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sxryk.cn/Article/details/gt2vsgjeixg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zdqjudy.top/Article/details/gt2yftibkam.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gt2oagamwwl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yonumen.top/Article/details/gt2xtjwtkwh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xziqi.cn/Article/details/gt2fhyqwsvv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gt2cigofpsp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gt2chothzfk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhongyouzk.top/Article/details/gt2dkemgpmw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gt2rtawdgco.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cheryme.top/Article/details/gt2epwannlr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2feibfgob.html

[L06] 解析响应为 JSON
来源：http://dali.c1oappe.top/Article/details/gt2gizcgumd.html

Py:   resp.json()
来源：http://dali.xylfe.cn/Article/details/gt2fwrhkdmr.html

PHP:  json_decode($body, true);
来源：http://dali.svipenyu.cn/Article/details/gt2bpvjisdw.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2ugjqcned.html

TS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2cpecibue.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gt2ygujfbov.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukwmceki.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aibaodan.cn/Article/details/gt2qqdxcrft.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aaatrwiy.html

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gt2iafnmoiz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenzaomai.com/Article/details/gt2wkrbefki.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuanzhike.top/Article/details/gt2telpwjbg.html

JS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkofrndq.html

TS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gt2dklkmgud.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qhpgvrjf.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gt2doaciyng.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gt2arxrvoea.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gt2imjwkiho.html

[L08] 并发请求多个地址
来源：http://dali.cdnleiting.top/Article/details/gt2qmxtuzkq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.bjfxy.top/Article/details/gt2ntcwjgoe.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gt2xxqbbzuk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gt2dvkdcmjj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gt2nzfngtld.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gt2resjzbui.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lucgqjbu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gt2uqaygzyt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nubeatpk.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ldnzxbcb.html

M. 命令行 / 进程 / 环境
来源：http://dali.guannengcc.top/Article/details/gt2cesoinuu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2cqmpmhbu.html

[M01] 读取命令行参数
来源：http://dali.316326.xyz/Article/details/gt2pyuvuzda.html

Py:   sys.argv[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gt2joamrxvi.html

PHP:  $argv;  $argc;
来源：http://dali.meibo888.top/Article/details/gt2zgagdqil.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2lkvlfxhj.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gt2lbmyrmwp.html

Java: args 数组（main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gt2yjeiduin.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gt2paentdsl.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gt2ycwkhirn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gt2lgvrxgvq.html

[M02] 读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2casqzaou.html

Py:   os.environ.get("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2wrywvajb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gt2imdeievr.html

JS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gt2bfsjxlmh.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gt2ajcsqhsy.html

Java: System.getenv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrezylnk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2tcwqbwhr.html

Ruby: ENV["HOME"]
来源：http://dali.c1oappe.top/Article/details/gt2cxgpockb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zwynknkq.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gt2jwhdbcxo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ydzc1.top/Article/details/gt2nlcrqsmq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pycfn.com/Article/details/gt2nrwoqkoj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2mxyhhkxw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gt2tzffqswk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ehwqpu.com/Article/details/gt2kzfgcibl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxinkj.top/Article/details/gt2qynfxlby.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2ztaldctc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gt2cmdotqzw.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gt2ihhaioho.html

Py:   os.getcwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2szksozpq.html

PHP:  getcwd();
来源：http://dali.yuanzhike.top/Article/details/gt2sxpfdauw.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2ixrdouib.html

TS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gt2mmqlhrpw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fengsongda.top/Article/details/gt2vhwsujmf.html

Go:   os.Getwd()
来源：http://dali.fengsongda.top/Article/details/gt2rqgusngb.html

Ruby: Dir.pwd
来源：http://dali.daria6918.cn/Article/details/gt2oaincefi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.feifeiyinyue.top/Article/details/gt2sqhveziu.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gt2phtyweqk.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2exqghumk.html

PHP:  exit(1);
来源：http://dali.jinqigufen.top/Article/details/gt2lvwvibwp.html

JS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2vdxsedfl.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2bscyqvki.html

Java: System.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2wfxnwtie.html

Go:   os.Exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2wiaqbqin.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gt2qhtznyaq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aibaodan.cn/Article/details/gt2xogorvqe.html

[M06] 向标准错误输出
来源：http://dali.jlsjyb.cn/Article/details/gt2bveeijfg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gt2xwcvdxri.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gt2yrbyxctc.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gt2gzfbqhny.html

TS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gt2bkybsovk.html

Java: System.err.println("err")
来源：http://dali.aizwys.cn/Article/details/gt2xbdokfkz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.svipenyu.cn/Article/details/gt2uinmyzvp.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xkkmgndo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yangfankeji.com/Article/details/gt2qdtxmyfn.html

[M07] 判断是否为主入口
来源：http://dali.jinqigfzy.top/Article/details/gt2sozqgivf.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gt2gkpvacpv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gt2qoxhogzw.html

JS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gt2qzzhvfbg.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2wpmvohpl.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gt2zndsiuml.html

Go:   func main()
来源：http://dali.tanke756.top/Article/details/gt2izekzanp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gt2motwrhdg.html

C#:   static void Main(string[] args)
来源：http://dali.chenzaomai.com/Article/details/gt2omlhrccl.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gt2nolxzgdc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daria6918.cn/Article/details/gt2ruxwfmgh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fzhhl.top/Article/details/gt2wqlprlrs.html

JS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gt2dgzmzvat.html

TS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gt2uaknufvy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.snrcjt.cn/Article/details/gt2xyqviajd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgfzy.top/Article/details/gt2pifwvpns.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.meibo888.top/Article/details/gt2rhhidfft.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pengpengdd.cyou/Article/details/gt2sojpqers.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2gbpiwejg.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gt2hgpdgfkm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2mfuszlkw.html

[N01] 二分查找（有序数组）
来源：http://dali.cqqwz.cn/Article/details/gt2dtomylzs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2ogvtgxea.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dkwuggaw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gt2txbdmdmw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jetkcxkv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgruktdg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2jmzovuhn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2pslhzkki.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2ooubsxhs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2lthiihdb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2edggyhjk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kkwijdlj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gt2nawqxvch.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wjqberpa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xziqi.cn/Article/details/gt2pmrohljw.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gt2cqavhthz.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gt2blpuzaxt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuxming.cn/Article/details/gt2dsfhlpas.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxuanxn.top/Article/details/gt2seglcmcd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ivvv.top/Article/details/gt2epqsfohu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jianghu66.top/Article/details/gt2numdxuqk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gt2awzbzjqa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gt2jbkibdyl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2focrgzqg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gt2jjlqvkqn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cqqwz.cn/Article/details/gt2trgwnvtj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gt2xtudzeby.html

[N04] 斐波那契数列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kidkovps.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2wfutztdw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gt2xmmrlvkm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2ppbmpkwz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gt2mlaltrzw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.iojbl.cn/Article/details/gt2xupiihrv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gt2axkrcvdw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2okwixzdp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2yyptbpky.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gt2lacmxwcy.html

Py:   math.gcd(a, b)
来源：http://dali.andypj.xyz/Article/details/gt2urmmgaxq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qpblmvqw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gt2btgadgmp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jaosjdnb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gt2fszyxetv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gt2hcdlalgu.html

Ruby: a.gcd(b)
来源：http://dali.fengsongda.top/Article/details/gt2kfulerhw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aizwys.cn/Article/details/gt2qadgqvcn.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ifkqmyki.html

Py:   s == s[::-1]
来源：http://dali.fzhhl.top/Article/details/gt2hpnblekl.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkttccgi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gt2rhyfjksh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gt2tzedgprr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqnntmdx.html

Go:   // 双指针从两端比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljlxnhcd.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gt2ywpabwax.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gt2azkqhqca.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gt2wbmldgsl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jiagoushi.top/Article/details/gt2zsnsszee.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhongyouzk.top/Article/details/gt2ibdqiqzh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gt2gkgskmej.html

TS:   // 手写 Map<string, number>
来源：http://dali.hammf.cn/Article/details/gt2esziysww.html

Java: // 手写 HashMap
来源：http://dali.xziqi.cn/Article/details/gt2zekmehrr.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gt2jjdgmwrl.html

Ruby: // 手写 Hash
来源：http://dali.daria6918.cn/Article/details/gt2etdmennd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxuanxn.top/Article/details/gt2jjzlokni.html

[N08] 生成全排列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fbywtftk.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zimbhciq.html

PHP:  // 手写递归交换
来源：http://dali.shuidangran.top/Article/details/gt2kpfvbuaz.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2axxudyut.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2kafcnsfc.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2lpiomllr.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2yfqaordy.html

Ruby: arr.permutation.to_a
来源：http://dali.hongshengwenyu.top/Article/details/gt2rgnacjpq.html

C#:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gt2seppxyoo.html


<!-- 参考信息 -->