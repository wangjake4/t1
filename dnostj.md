代发 wailian999

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2nnfkezck.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gt2qkcztsbj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2dfpdrtdf.html

[K01] 对象转 JSON 字符串
来源：http://dali.nwbrower.top/Article/details/gt2yhiqrtgi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hngytsps.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2lnsxggcx.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2cqpemren.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2atgzsswj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jlsjyb.cn/Article/details/gt2bacsefxn.html

Go:   json.Marshal(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybiwxalk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gt2nmrqlgsz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2pwbgvmqe.html

[K02] JSON 字符串转对象
来源：http://dali.jlsjyb.cn/Article/details/gt2bayrjqlt.html

Py:   json.loads(s)
来源：http://dali.chenlongwang.top/Article/details/gt2hnyovxlg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.316326.xyz/Article/details/gt2yqrbcepm.html

JS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gt2xjutnuov.html

TS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2myafdabp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2ejnlsrul.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gt2yjyyytga.html

Ruby: JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gt2ftufbwez.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gt2uoctpczt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cqqwz.cn/Article/details/gt2beylssub.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gt2lkbxzhie.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gt2duuitrcu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2pvlujxry.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gt2dwqwvqdx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yvedp.cn/Article/details/gt2rpnsoclk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cashguo.top/Article/details/gt2xpkyoypk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gt2vsxdlard.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.quarkkingdee.top/Article/details/gt2ilghlese.html

[K04] 读取 JSON 文件
来源：http://dali.hfpthk.cn/Article/details/gt2azfbzpmq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2fjgtwpni.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gt2iprkbdmb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gt2qufmhwon.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoyhsgt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gt2xnmvllez.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wevyopzp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yongpay.top/Article/details/gt2nomagriw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvtbeedm.html

[K05] 深拷贝对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtuhfzmi.html

Py:   copy.deepcopy(obj)
来源：http://dali.yonumen.top/Article/details/gt2ajkkxxyn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hysaishi.cn/Article/details/gt2hgdsmtzg.html

JS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gt2ebyqubec.html

TS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gt2zbtctsvm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tbgdqopa.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuetiantiany.cn/Article/details/gt2lgjnexwh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gzhubu.top/Article/details/gt2qlkufoga.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shzxlz.cn/Article/details/gt2jddcljju.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gt2qmoveecn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shuidangran.top/Article/details/gt2catzirfq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gt2fxxpyuto.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gt2zenrbwbl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gt2rtcodhin.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gt2eynvpiht.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gt2bwguxyom.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2osimgzdm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2gvfjnwov.html

[K07] 进制转换
来源：http://dali.hywenlv.cn/Article/details/gt2pildtssp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2famomqwc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gt2piexsocy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2kpiyzkpy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2ttunqpvw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2yrtiukup.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yvedp.cn/Article/details/gt2gbrcwxit.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ivvv.top/Article/details/gt2izybzkwi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2mriltnog.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.meibo888.top/Article/details/gt2wruizioi.html

Py:   pickle.dumps(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2gxuqxfbp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xylfe.cn/Article/details/gt2fzfamkwb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gt2vudopsgc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gt2towxzxxo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gt2msfnqzcr.html

Go:   encoding/gob
来源：http://dali.andypj.xyz/Article/details/gt2ytvajjal.html

Ruby: Marshal.dump(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrbbjzjt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gt2jrkrlvla.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2wdptdrua.html

L. 网络请求
来源：http://dali.dashuyun.cn/Article/details/gt2dhwsebii.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2knchszbr.html

[L01] 发送 GET 请求
来源：http://dali.nanxinkj.top/Article/details/gt2hepkmizr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gt2puclgtaz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gt2unczbyih.html

JS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gt2swcdgoci.html

TS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2auuczhfa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gt2nckfuoza.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yntnnxki.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fzhhl.top/Article/details/gt2hvffjeia.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2ctbhfbut.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gt2gexdqffy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gt2hfxufcym.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gt2zktbqvsh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gt2orstqrpj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gt2wqicxypl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnqzz.top/Article/details/gt2unfjdeqk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gt2neqxojkh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvwbmfrx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.mhx1999.top/Article/details/gt2fezhgkbj.html

[L03] 设置自定义请求头
来源：http://dali.tanke756.top/Article/details/gt2ijecqlix.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gt2xlznumeb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.haohaochexian.top/Article/details/gt2unguqwxv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gt2cbkflrmf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gt2hjnakgqo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gt2almpczhs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2tmlzmlwm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pycfn.com/Article/details/gt2leebezqe.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gt2thvwuplh.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gt2xskyarwd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sufxvd.cn/Article/details/gt2veyvyuyw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhoulong.xyz/Article/details/gt2xdwdjrpo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gt2vzlcbrvi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gt2sosycnbf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.meibo888.top/Article/details/gt2kcvyfzgz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gt2qlecwmeu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gt2ewkcltjd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gt2podtzsgh.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gt2ektuqval.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gaohongyu789.top/Article/details/gt2bmcgbhes.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fzhhl.top/Article/details/gt2fbmxunok.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gt2kqwhwnpa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gt2vayltztw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnxiangtu.top/Article/details/gt2reqwwptb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnxiangtu.top/Article/details/gt2saqppcck.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gt2fmnaerox.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2wfjcwdfm.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gt2fcjbeooy.html

Py:   resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2alchyhoa.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gt2xwykppzn.html

JS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2qgskbsap.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gt2rntfvsrz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwmdszxs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gt2qvfemcri.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vrccjtji.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fzhhl.top/Article/details/gt2hhhvtefe.html

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gt2zgvpbkyz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehwgrgja.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2jzasppug.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gt2ffrzhwjb.html

TS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gt2hnwsgbvv.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gt2lyhmvjwr.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gt2wgwntcyi.html

Ruby: resp.code.to_i
来源：http://dali.yj20258888.top/Article/details/gt2cketinhy.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gt2ornqotjq.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gt2gmgzfaxt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.c1oappe.top/Article/details/gt2iedzmmyq.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gt2xpckyyio.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2hiyowgqf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gt2hienttmj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.bjfxy.top/Article/details/gt2uytktrfv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.0kj1m.cn/Article/details/gt2gkpieytj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ivvv.top/Article/details/gt2xzbnhija.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.meibo888.top/Article/details/gt2knwakrhd.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2enedsegm.html

M. 命令行 / 进程 / 环境
来源：http://dali.fzhhl.top/Article/details/gt2bvlgfybh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ojucwiwg.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gt2mkamdcrm.html

Py:   sys.argv[1:]
来源：http://dali.haohaochexian.top/Article/details/gt2xpavetua.html

PHP:  $argv;  $argc;
来源：http://dali.zhongyouzk.top/Article/details/gt2lsfcfwip.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gt2krndttio.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gt2fhfdpczz.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gt2kdjjqbty.html

Go:   os.Args[1:]
来源：http://dali.yvedp.cn/Article/details/gt2clszusoc.html

Ruby: ARGV
来源：http://dali.tanke756.top/Article/details/gt2cbktvofm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gt2vaywlnbf.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gt2ucfujqnj.html

Py:   os.environ.get("HOME")
来源：http://dali.yongpay.top/Article/details/gt2spikuefd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gt2qrwqpyhu.html

JS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gt2oiedllnc.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gt2rwaeaosv.html

Java: System.getenv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gt2aiqirmbb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2fdgonmfw.html

Ruby: ENV["HOME"]
来源：http://dali.tianlin.xyz/Article/details/gt2piqnakfy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2wiyrtqou.html

[M03] 执行外部命令
来源：http://dali.jianghu66.top/Article/details/gt2ghrjvjqb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nwbrower.top/Article/details/gt2sligwgji.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guannengcc.top/Article/details/gt2jzxyvotc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gt2rqidmerh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gt2cwvcvfib.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xnyvqgvn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.kuanghao11.cn/Article/details/gt2xdyxcnyd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gt2mwpomowe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yongpay.top/Article/details/gt2hmubehhg.html

[M04] 获取当前工作目录
来源：http://dali.smart0.xyz/Article/details/gt2yygofdkj.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mxdqlprd.html

PHP:  getcwd();
来源：http://dali.xinyue.icu/Article/details/gt2fbztyqfc.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gt2kgvattjk.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2fhpdvmns.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gt2ussjowfq.html

Go:   os.Getwd()
来源：http://dali.tian-w.cn/Article/details/gt2ccudhpdu.html

Ruby: Dir.pwd
来源：http://dali.jlsjyb.cn/Article/details/gt2retolphy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.vqdsnc.cn/Article/details/gt2wcxligdv.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gt2sufntnjr.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2gmmkhdfu.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gt2ikjhhtha.html

JS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2waxqxlvk.html

TS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2dbxamhkr.html

Java: System.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2gftzjixh.html

Go:   os.Exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2nrojdmrq.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gt2cozvolln.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnqzz.top/Article/details/gt2yadvnsoz.html

[M06] 向标准错误输出
来源：http://dali.zycfv.cn/Article/details/gt2xfjbhmqo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gt2mjomojzx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gt2oarpybru.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2fctbssxo.html

TS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gt2gvkvemmq.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gt2hilpvjlk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gt2pdbwucoa.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2focnrqhi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2izgdaaex.html

[M07] 判断是否为主入口
来源：http://dali.cdnleiting.top/Article/details/gt2nckiturw.html

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gt2qcdvlrzp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gt2ckjwhrxp.html

JS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gt2glkrhrfb.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gt2hqdquiig.html

Java: public static void main(String[] args)
来源：http://dali.andypj.xyz/Article/details/gt2fsypmduo.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gt2fbmggygu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zdqjudy.top/Article/details/gt2lnpuiolh.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gt2cevcgxfk.html

[M08] 获取系统与运行时信息
来源：http://dali.feifeiyinyue.top/Article/details/gt2kbnouacm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqnorrsc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258.top/Article/details/gt2kgusiifu.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gt2bbzhbekq.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gt2xtwsviik.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sysykeji.top/Article/details/gt2fklkbfhx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhoulong.xyz/Article/details/gt2fgdtilbp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cdnleiting.top/Article/details/gt2ntungwdz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fzhhl.top/Article/details/gt2fwxornoy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2xmdxpcig.html

N. 数据结构与算法
来源：http://dali.316326.xyz/Article/details/gt2sywpoxth.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2wdfrrhur.html

[N01] 二分查找（有序数组）
来源：http://dali.yueranfly.top/Article/details/gt2bkxxtqhn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2fnzubdix.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gt2fjlolyky.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2kjpbeeya.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gt2yzaowjhp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2dhrlwrik.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2zjnpzobt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gt2lxtacuba.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2brovidfl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gt2fnygdeyv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2denkxhun.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gt2qqpyizhe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gt2mrubutvr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gt2swsxpkxy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zdqjudy.top/Article/details/gt2izkvyqrp.html

Go:   slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2ipimhjof.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gt2iymxprqh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xinyue.icu/Article/details/gt2gmqplsxk.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gt2cvcicyxi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vaxqxqjb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hongshengwenyu.top/Article/details/gt2rhbtanjb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2squlkyrl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gt2ufhnqdqp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrpqidw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gt2jqgizbov.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jlsjyb.cn/Article/details/gt2tnbfdwsr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fzhhl.top/Article/details/gt2wibfumnq.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gt2ldkiokgb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gt2ztewhxno.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gt2hrwpexah.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gt2vzzhzmak.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2dsorpmhm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gt2fwfyhuya.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj202588.top/Article/details/gt2rxmymcui.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gt2cvylqymn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gt2uudwnjim.html

[N05] 最大公约数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oahgzpsv.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gt2kckdacux.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xziqi.cn/Article/details/gt2yxrgzrbk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gt2mojryhvg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gt2plovrhtc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shuidangran.top/Article/details/gt2hqqkiqpr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.haohaochexian.top/Article/details/gt2fyjrgudc.html

Ruby: a.gcd(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vywjpjyj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.birdmap.top/Article/details/gt2wwjkpjgy.html

[N06] 判断回文字符串
来源：http://dali.zdqjudy.top/Article/details/gt2xwrgqpqv.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gt2wyliblur.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gt2wozpzytt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2vvrmglsg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vrltbljk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.0kj1m.cn/Article/details/gt2azehsmxy.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigfzy.top/Article/details/gt2loxltwiy.html

Ruby: s == s.reverse
来源：http://dali.hnqzz.top/Article/details/gt2tptrylrt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gt2vampsmht.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkzxmdde.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gt2anfqlhbj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tian-w.cn/Article/details/gt2bplrsqhz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tnulkvsq.html

TS:   // 手写 Map<string, number>
来源：http://dali.guannengcc.top/Article/details/gt2kaudbwvj.html

Java: // 手写 HashMap
来源：http://dali.zdqjudy.top/Article/details/gt2scppbvkf.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gt2zqtqpylf.html

Ruby: // 手写 Hash
来源：http://dali.wangdashe.top/Article/details/gt2gaqmqyfl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigufen.top/Article/details/gt2hvemqwrb.html

[N08] 生成全排列
来源：http://dali.yanxiufei.cn/Article/details/gt2qhxdjfok.html

Py:   itertools.permutations(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2gjntmdhi.html

PHP:  // 手写递归交换
来源：http://dali.zdqjudy.top/Article/details/gt2ulspdwjc.html

JS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2gsbqghuk.html

TS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2cofblanr.html

Java: // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2ccolxlwy.html

Go:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2isvcafjq.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgfzy.top/Article/details/gt2xkawkjlq.html

C#:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2ivypilwp.html


<!-- 参考信息 -->