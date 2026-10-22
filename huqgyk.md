代发 wailian999

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2yvknzmwe.html

K. JSON 与序列化
来源：http://dali.zhoulong.xyz/Article/details/gt2nsemmwvm.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2hmhbsavt.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gt2mjxlrdci.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gt2gunmwfud.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gt2zcraybci.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2gyhjvxrv.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lqxmuonj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gt2xrixrmbb.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gt2lojymzqa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gt2lhqbtplm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cucudq.cn/Article/details/gt2trknvuwj.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gt2sttqosjv.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gt2hckdgojd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guannengcc.top/Article/details/gt2hwvuxwsq.html

JS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2bidfyjip.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2kpncoclb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2qdpjfaxp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gt2hlpxgotr.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2vtwbfuhu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gt2tmgpsihw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gt2gjzirqzf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gt2dmiqjnlx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gt2bkpkuuok.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gt2jligydxx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gt2pdxscshg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gt2wlrryjee.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgkojnr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2jyvxeerj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gt2onubppiz.html

[K04] 读取 JSON 文件
来源：http://dali.yueranfly.top/Article/details/gt2ibmnwldl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shuidangran.top/Article/details/gt2gckvgici.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daxiang520.top/Article/details/gt2lskjdqsj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gt2ievsamfi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gt2zrpzdwos.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2tcuperca.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gt2kcscnsny.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gt2nmsjodjv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gt2vjpkjwpk.html

[K05] 深拷贝对象
来源：http://dali.jinqigfzy.top/Article/details/gt2fhahnbvm.html

Py:   copy.deepcopy(obj)
来源：http://dali.hammf.cn/Article/details/gt2dsjztfsb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.c1oappe.top/Article/details/gt2zsvtuuvb.html

JS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2ykkjtdlz.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2zoeipgvp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aizwys.cn/Article/details/gt2kztyyswq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnqzz.top/Article/details/gt2wtnaixxb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gt2mstwbxoo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cqqwz.cn/Article/details/gt2egmimfsn.html

[K06] 解析 URL 查询串
来源：http://dali.tianlin.xyz/Article/details/gt2hixtlcdt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cashguo.top/Article/details/gt2xwllravz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.mhx1999.top/Article/details/gt2kwrneovs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gt2fspmrtub.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gt2fujjwrfa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cucudq.cn/Article/details/gt2rzfvpjcs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2jhafpnwr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gt2ibbxjsgj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gt2mbkfijdd.html

[K07] 进制转换
来源：http://dali.0kj1m.cn/Article/details/gt2cdaojdys.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2jdfhrzec.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tanke756.top/Article/details/gt2ikhuzqxd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2vamaojwt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2ebqlypbh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2hxdfjptq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xziqi.cn/Article/details/gt2cbfeelfu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gt2zeljgsfw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2bixmsdsy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xinyue.icu/Article/details/gt2ncotptvy.html

Py:   pickle.dumps(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2diszfijk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.smart0.xyz/Article/details/gt2fvjlbpit.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gt2qneqnxim.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2inwnniji.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsstaecd.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gt2rpjjdvwv.html

Ruby: Marshal.dump(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2wdzosffr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gt2avmwauqj.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2rfpugeka.html

L. 网络请求
来源：http://dali.yonumen.top/Article/details/gt2qhorponw.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2xhojmals.html

[L01] 发送 GET 请求
来源：http://dali.sweek.top/Article/details/gt2corcnnse.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tian-w.cn/Article/details/gt2ozpfuxjc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gt2bcsyihrh.html

JS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gt2fihxvzgp.html

TS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gt2xwycxkli.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gt2pfkzozlk.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gt2sossvwao.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gt2jigclers.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gt2xlfevpxf.html

[L02] 发送 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gt2onhxnule.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ydzc1.top/Article/details/gt2pivixakt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sweek.top/Article/details/gt2xqqxlqug.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gt2gpiohdbs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gt2slnpqsuh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.quarkkingdee.top/Article/details/gt2wxriykeg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenlongwang.top/Article/details/gt2zkzqerxj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fzhhl.top/Article/details/gt2pfpbtgrk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.iojbl.cn/Article/details/gt2hjatfann.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gt2kvkuhjwf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jlsjyb.cn/Article/details/gt2ivvelszg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2tiuaooae.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gt2rqlzhqce.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gt2sflexidq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aibaodan.cn/Article/details/gt2eqzeqfzb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gt2qzwjnmit.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gt2clxwbkvu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2zsonqfoq.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gt2rtnttuzb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gt2papukeel.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangdashe.top/Article/details/gt2nsuacixa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gt2eklohxny.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gt2ffpjicxo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gt2htgwxfes.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigfzy.top/Article/details/gt2jupwxlcb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gt2ystqfgxq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gt2hvtbsaql.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sfwscqfj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.meibo888.top/Article/details/gt2qbcwkbzh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgfzy.top/Article/details/gt2vyevlhgi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gt2yljyujwm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gt2bifgrass.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkloychb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxinkj.top/Article/details/gt2rhzpnwfa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gt2hhpmcwpz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2kqwqfeew.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gt2kizuyvqb.html

Py:   resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gt2dtahnpkw.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gt2sahkvzpz.html

JS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2crmgmwqe.html

TS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2qvinvplt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gt2otwcfpce.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxinkj.top/Article/details/gt2mjkpnloz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhengqikj.top/Article/details/gt2fiihphin.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.316326.xyz/Article/details/gt2jftsvcsk.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gt2wrfmpnbh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfwxqxav.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gt2rudzqnqe.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gt2figubuqj.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gt2oezxlaxn.html

Java: resp.statusCode()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ggfckcya.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gt2yxnqsncr.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gt2axpfutgh.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgqiabjg.html

[L08] 并发请求多个地址
来源：http://dali.316326.xyz/Article/details/gt2eafmncei.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhoulong.xyz/Article/details/gt2zrjqtqxm.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gt2negnrctk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2feisqowp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfhynum.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gt2nezpprma.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gt2hwxrdlkv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.svipenyu.cn/Article/details/gt2aqvanetj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jiagoushi.top/Article/details/gt2hbzwtykw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2befqgjun.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj202588.top/Article/details/gt2rrprxpqs.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2rafvtppp.html

[M01] 读取命令行参数
来源：http://dali.hywenlv.cn/Article/details/gt2fyewauff.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2odbmakad.html

PHP:  $argv;  $argc;
来源：http://dali.guannengcc.top/Article/details/gt2syqiznnw.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gt2edjncobo.html

TS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gt2rzqmvpdz.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gt2igmnylhr.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gt2ynqqpifw.html

Ruby: ARGV
来源：http://dali.gotoacloud.top/Article/details/gt2rzebbwxi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2akvsbkfb.html

[M02] 读取环境变量
来源：http://dali.yangfankeji.com/Article/details/gt2hwdjbjcu.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2ffxsqvra.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vrowumis.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gt2ozoizenw.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gt2onknkkvy.html

Java: System.getenv("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2xtesbkrq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2siazdtzi.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gt2fzkaqtbi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2elnqopxn.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gt2befycqen.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gt2yvjnldzd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ppjwa.cn/Article/details/gt2zxwjvfof.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gt2galfhclb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gt2yivbuujg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gt2hqahjnbf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jianghu66.top/Article/details/gt2qabtvboq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gt2wtxhomtp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yueranfly.top/Article/details/gt2qocjvslh.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gt2zpwkhmzs.html

Py:   os.getcwd()
来源：http://dali.ppjwa.cn/Article/details/gt2tnimfdre.html

PHP:  getcwd();
来源：http://dali.ybcxt.top/Article/details/gt2culygklg.html

JS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2crvmujza.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2udimthsh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opyzfbmu.html

Go:   os.Getwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2igdxmovr.html

Ruby: Dir.pwd
来源：http://dali.pycfn.com/Article/details/gt2ugakpemw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sysykeji.top/Article/details/gt2kupnwwsa.html

[M05] 设置退出码
来源：http://dali.yj202588.top/Article/details/gt2osixevrs.html

Py:   sys.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2muqfpjuf.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gt2oogiunui.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vljedssr.html

TS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2jfflcpye.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2ouzmfsyi.html

Go:   os.Exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cygtzkwr.html

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gt2yqsxrmwq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gt2pkjhfpqn.html

[M06] 向标准错误输出
来源：http://dali.aizwys.cn/Article/details/gt2nkjshpnu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gt2mrmuilrk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gt2ewvwuxba.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2vcmichar.html

TS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gt2dysrrnew.html

Java: System.err.println("err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndukjvuj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shuidangran.top/Article/details/gt2xcdrcpae.html

Ruby: warn "err"
来源：http://dali.haohaochexian.top/Article/details/gt2bzioksmr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gogol.net.cn/Article/details/gt2omeeofqp.html

[M07] 判断是否为主入口
来源：http://dali.cdnleiting.top/Article/details/gt2mfowjuik.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gt2tgjrkltr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gogol.net.cn/Article/details/gt2vayzvorq.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gt2xisjiluu.html

TS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gt2qhindzid.html

Java: public static void main(String[] args)
来源：http://dali.c1oappe.top/Article/details/gt2chbqhqpk.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gt2xvitunnh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gt2nrykxwhp.html

C#:   static void Main(string[] args)
来源：http://dali.jiagoushi.top/Article/details/gt2rvltfxuf.html

[M08] 获取系统与运行时信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2swxipyhh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lenzobru.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.havefunace.top/Article/details/gt2ikceyjqf.html

JS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gt2zkofajyp.html

TS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gt2asqccmpb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgfzy.top/Article/details/gt2pisrycpx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gt2rdyythga.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aizwys.cn/Article/details/gt2xianqkeo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnxiangtu.top/Article/details/gt2hcbwxpih.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2xazzgxtn.html

N. 数据结构与算法
来源：http://dali.hysaishi.cn/Article/details/gt2apyfgaev.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2bshwdspe.html

[N01] 二分查找（有序数组）
来源：http://dali.svipenyu.cn/Article/details/gt2twotzsap.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2khgmuqle.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zdqjudy.top/Article/details/gt2ixlxpxex.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gt2mdhhdduh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gt2pjdqrswi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2jchmjrtl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2zogdzelr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuetiantiany.cn/Article/details/gt2oeykjhwu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2srhcumln.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xbpvbnvs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gt2axbejwmi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ybcxt.top/Article/details/gt2knmebowr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gt2pecuhmyp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gt2uckdtqgc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jyoumei.cn/Article/details/gt2kygpwfxa.html

Go:   slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gt2bbhtbwye.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gt2uzydbvik.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gt2dolnvgqi.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258888.top/Article/details/gt2mtjgglou.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuanzx.com/Article/details/gt2kczxgehn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenjidiqi.icu/Article/details/gt2oicrhmia.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gt2bfclspdi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gt2vzstzcxh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tian-w.cn/Article/details/gt2ptsicgpc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gt2wjtcubqd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nwbrower.top/Article/details/gt2wgycpldl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.0kj1m.cn/Article/details/gt2jygypyhd.html

[N04] 斐波那契数列
来源：http://dali.hysaishi.cn/Article/details/gt2ipcpwbxt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gt2toonjroy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gt2bfroablw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gt2obzcgktd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2eydbtlln.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mdrjctcv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.birdmap.top/Article/details/gt2wmqbcnzw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kpewyqra.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gt2zbkehqke.html

[N05] 最大公约数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2prjyhnry.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gt2legdttja.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tianlin.xyz/Article/details/gt2waofmgzf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2pyjgiaab.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gt2rgjcllhd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gt2vevybbka.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2iosbbhzf.html

Ruby: a.gcd(b)
来源：http://dali.mhx1999.top/Article/details/gt2qiqnbwcb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zdqjudy.top/Article/details/gt2lwlzxfoq.html

[N06] 判断回文字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2yiexasgo.html

Py:   s == s[::-1]
来源：http://dali.guannengcc.top/Article/details/gt2crfmrrrf.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258.top/Article/details/gt2iscoussf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2arnabhxb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2avlwiiqj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gzhubu.top/Article/details/gt2atmzfjly.html

Go:   // 双指针从两端比较
来源：http://dali.cdnleiting.top/Article/details/gt2wrhuziic.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gt2zbpuwyft.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gt2wcqlyqel.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgfzy.top/Article/details/gt2hzmeshyw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.havefunace.top/Article/details/gt2hkukqvaa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jianghu66.top/Article/details/gt2hcgvyzid.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.9152youxi.cn/Article/details/gt2bjhxtngm.html

TS:   // 手写 Map<string, number>
来源：http://dali.kuanghao11.cn/Article/details/gt2vnviihzq.html

Java: // 手写 HashMap
来源：http://dali.yongpay.top/Article/details/gt2cwcwgdwk.html

Go:   // 手写 map[int]int
来源：http://dali.zdqjudy.top/Article/details/gt2lsqcrjxx.html

Ruby: // 手写 Hash
来源：http://dali.fengsongda.top/Article/details/gt2rmdhrlhs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.0kj1m.cn/Article/details/gt2epstizop.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gt2onqigoly.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gt2vvrxtyse.html

PHP:  // 手写递归交换
来源：http://dali.aibaodan.cn/Article/details/gt2tqmwmvuo.html

JS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2ixeptlzs.html

TS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2krkjbvyv.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vuagrgrl.html

Go:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2kmknmtko.html

Ruby: arr.permutation.to_a
来源：http://dali.redwolf501.top/Article/details/gt2kpnkmtvc.html

C#:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tfifmsas.html


<!-- 参考信息 -->