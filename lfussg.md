代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2skdjwdai.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnxiangtu.top/Article/details/gt2gwulmbgb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gt2yxpsvhew.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gt2qwvwwgzj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ajdrvehi.html

K. JSON 与序列化
来源：http://dali.hnxiangtu.top/Article/details/gt2cxguhtul.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxbniwsi.html

[K01] 对象转 JSON 字符串
来源：http://dali.sweek.top/Article/details/gt2nrdxlnaq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2srbbwfzn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gt2dckflfjd.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2hqlldrcp.html

TS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2esnrkvah.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yueranfly.top/Article/details/gt2rzaiehop.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2struwrtp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sufxvd.cn/Article/details/gt2dhktuuxa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.meibo888.top/Article/details/gt2qmolnbka.html

[K02] JSON 字符串转对象
来源：http://dali.nanxuanxn.top/Article/details/gt2aockyypg.html

Py:   json.loads(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ooncuukm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gotoacloud.top/Article/details/gt2afaupnig.html

JS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gt2zjyawyek.html

TS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ygzsskcv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jiagoushi.top/Article/details/gt2vlepxvvd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gt2vblnydot.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2auqdojoa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2urbdwdwy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gt2elzbeuwt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gt2ofyyjpau.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gt2gneqepnt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2dcrqpbkw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2gvxdpyxn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ydzc1.top/Article/details/gt2qhpfgfca.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258.top/Article/details/gt2zgmltsag.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwmjfeef.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbimdoj.html

[K04] 读取 JSON 文件
来源：http://dali.sufxvd.cn/Article/details/gt2lxxqqlqr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fzhhl.top/Article/details/gt2ehhfvynb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenzaomai.com/Article/details/gt2sxazxher.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gt2kbuyiuwy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2bvppwcsh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2neyryzju.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gt2mrfwxbxq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guannengcc.top/Article/details/gt2dgwucogm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gt2tckeuvrq.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gt2oprtsypg.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gt2edotungr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.9152youxi.cn/Article/details/gt2rxitcmxq.html

JS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gt2fqbzatjk.html

TS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2ftowrqvv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gt2abryeksh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daxiang520.top/Article/details/gt2yldkjeet.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daria6918.cn/Article/details/gt2ctklockf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.smart0.xyz/Article/details/gt2aerduepu.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gt2bvgxqdvh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zycfv.cn/Article/details/gt2jarnjngq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.havefunace.top/Article/details/gt2omjzrczh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gt2fhigwhlp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gt2drtlyzrs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ivvv.top/Article/details/gt2pgkpulmd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2zsnprgtz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2jkoeszqu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2ehxpvwis.html

[K07] 进制转换
来源：http://dali.fengsongda.top/Article/details/gt2otujcxsa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2ollclasr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ydzc1.top/Article/details/gt2jxweeiya.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2qfsmfsyj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2ztxydxlx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2qwugtajt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxpicjab.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fengsongda.top/Article/details/gt2lqzvtuuf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2rcrgeyqm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hywenlv.cn/Article/details/gt2rxhxixbq.html

Py:   pickle.dumps(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2fqcjfzzx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jyoumei.cn/Article/details/gt2owparuhr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gt2ajkxqwbr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2vnwnfogj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hongshengwenyu.top/Article/details/gt2isvupadz.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gt2vizshezh.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gt2nxcmpxtq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gt2jpztmqjv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntaqjozu.html

L. 网络请求
来源：http://dali.yangfankeji.com/Article/details/gt2vjreffgc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2tkjgrbmf.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gt2ogvkheax.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gt2vbrrxvzq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gt2kvrfizwy.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gt2outqhjby.html

TS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gt2nnevjulp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangdashe.top/Article/details/gt2quacabgi.html

Go:   resp, err := http.Get(url)
来源：http://dali.shzxlz.cn/Article/details/gt2zmkksxae.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zycfv.cn/Article/details/gt2wxqkyqlw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gt2ykyxfade.html

[L02] 发送 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gt2xuuolzqs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ydzc1.top/Article/details/gt2jqogsyml.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2svtgasfj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gt2yrndylja.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gt2vogbbptg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhoulong.xyz/Article/details/gt2tausfsph.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangshuangyany.cn/Article/details/gt2uzdjauaa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jlsjyb.cn/Article/details/gt2obmjlarf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gt2rfllkbye.html

[L03] 设置自定义请求头
来源：http://dali.daria6918.cn/Article/details/gt2udtvgqmx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tian-w.cn/Article/details/gt2mziujxxx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.haohaochexian.top/Article/details/gt2vrgnhqqa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gt2xwfkezij.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gt2cvtmwtcs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gt2rpcmmpfq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2davyccsg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhoulong.xyz/Article/details/gt2fzpwmkbn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gt2dgwvexij.html

[L04] 设置超时
来源：http://dali.yuxming.cn/Article/details/gt2ghmrgiat.html

Py:   requests.get(url, timeout=5)
来源：http://dali.9152youxi.cn/Article/details/gt2gyszhyfm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gt2buzrduvx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gt2edqbsqho.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gt2ipdnimkx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umyedsns.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gogol.net.cn/Article/details/gt2ueoylolu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangdashe.top/Article/details/gt2azzdhtbz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gt2cbbmmlvg.html

[L05] 上传文件（multipart）
来源：http://dali.ivvv.top/Article/details/gt2xsidancz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gt2glufjmhy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gt2kvzyxlnl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sfkfsocn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gt2acsfpwfv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gt2cnxvyoat.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2clfdzjxn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daxiang520.top/Article/details/gt2kjhxrwkv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2xegjvtqr.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gt2bhaztbwp.html

Py:   resp.json()
来源：http://dali.9152youxi.cn/Article/details/gt2kljuuphf.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gt2chyucxrf.html

JS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2lwqurfzr.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2cbqzsdxo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2maidpuzn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abfphjln.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nwbrower.top/Article/details/gt2jehbhlli.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ydzc1.top/Article/details/gt2zegwhoef.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gt2bulprrii.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gt2byymrfwg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gt2gqgwhtaf.html

JS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gt2cewgrgsn.html

TS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gt2xxhlzsgl.html

Java: resp.statusCode()
来源：http://dali.yuanzhike.top/Article/details/gt2lbaulkwo.html

Go:   resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gt2nycljbhx.html

Ruby: resp.code.to_i
来源：http://dali.tianlin.xyz/Article/details/gt2sbklhtrn.html

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gt2hbyvwaqd.html

[L08] 并发请求多个地址
来源：http://dali.zhoulong.xyz/Article/details/gt2dnopzdtl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnxiangtu.top/Article/details/gt2enhyqjda.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2susnauqy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gt2kcnvguwh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gt2rxcpbdcy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gt2lwkuyvhl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fzhhl.top/Article/details/gt2esiediuz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gt2ztrjqhts.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhengqikj.top/Article/details/gt2sylkzmqs.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ishmgtlr.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gt2boxluqdv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ywenrbys.html

[M01] 读取命令行参数
来源：http://dali.iojbl.cn/Article/details/gt2fnyhwuym.html

Py:   sys.argv[1:]
来源：http://dali.tanke756.top/Article/details/gt2srfwnpor.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gt2xgjadwpc.html

JS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gt2kfgdccpl.html

TS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gt2dtliaqiv.html

Java: args 数组（main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gt2dtuamihc.html

Go:   os.Args[1:]
来源：http://dali.yongpay.top/Article/details/gt2fpwaqecm.html

Ruby: ARGV
来源：http://dali.yj202588.top/Article/details/gt2nlfvdstl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gt2mgdjwlrr.html

[M02] 读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gt2qtpvvhhr.html

Py:   os.environ.get("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2imiqnthy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gt2hwcnbtup.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mbnpdhwr.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gt2oxchqvkc.html

Java: System.getenv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdwvstvi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2gubwyisu.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gt2ginrqdki.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2avlsmehh.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gt2mwrsaksl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cucudq.cn/Article/details/gt2tyoqejya.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yongpay.top/Article/details/gt2yjpbmqxq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gt2jvoygilw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gt2hjblmgnl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.9152youxi.cn/Article/details/gt2sxwgmevk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yueranfly.top/Article/details/gt2zppfuxsi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gt2vryrekht.html

C#:   Process.Start("ls", "-l");
来源：http://dali.quarkkingdee.top/Article/details/gt2oekgbzij.html

[M04] 获取当前工作目录
来源：http://dali.nanxinkj.top/Article/details/gt2ygltrbwp.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gt2etvlmgom.html

PHP:  getcwd();
来源：http://dali.gzhubu.top/Article/details/gt2ocsgfirt.html

JS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gt2tnffcsxt.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gt2fsbihgmy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.andypj.xyz/Article/details/gt2gfqebdlw.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2svirisfy.html

Ruby: Dir.pwd
来源：http://dali.birdmap.top/Article/details/gt2xoqbjvpy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.iojbl.cn/Article/details/gt2keprdlor.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gt2mfdongtn.html

Py:   sys.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rtimpgyb.html

PHP:  exit(1);
来源：http://dali.yuxming.cn/Article/details/gt2kdbynhmk.html

JS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2laavjllt.html

TS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2nhyvuplg.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2pzwjeocj.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2bmoohizq.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gt2dqxvedvs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guannengcc.top/Article/details/gt2cbohklgt.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gt2sisokbxw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gt2eopttlmq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2budnvnib.html

JS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gt2anmjcgff.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wxmuyvlg.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gt2mqwpmksc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shzxlz.cn/Article/details/gt2nsttyufz.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gt2mkthgjlh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aizwys.cn/Article/details/gt2geviwdpi.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gt2hsektskc.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gt2jtoscssp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gt2knijxpnk.html

JS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gt2dquilddg.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2niqlwupk.html

Java: public static void main(String[] args)
来源：http://dali.jlsjyb.cn/Article/details/gt2clmsgvty.html

Go:   func main()
来源：http://dali.zhoulong.xyz/Article/details/gt2ijbktqqf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gt2oclfpbol.html

C#:   static void Main(string[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrifhnzh.html

[M08] 获取系统与运行时信息
来源：http://dali.cashguo.top/Article/details/gt2dimvwgns.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hywenlv.cn/Article/details/gt2auuautjz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jiagoushi.top/Article/details/gt2zhplxtqs.html

JS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gt2quhnbyyq.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gt2qwasishe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.mhx1999.top/Article/details/gt2einqxmma.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gt2qsjmokaa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gt2plrnfbee.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gt2rvcwjjbj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ussbuwwi.html

N. 数据结构与算法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cdkykamp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ygpoiicb.html

[N01] 二分查找（有序数组）
来源：http://dali.fzhhl.top/Article/details/gt2ppbinsqk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkmlava.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2zcvmvttq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gt2uapkxhot.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gt2mterpksx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2ccpumhep.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2xjwbyavy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shzxlz.cn/Article/details/gt2untgdcal.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2binshaeb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yonumen.top/Article/details/gt2oalhdsbo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqqkepjl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sysykeji.top/Article/details/gt2frfvmzvi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gt2ryouqnky.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gt2rvlkemlh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpjzroic.html

Go:   slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dwxcsetk.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gt2qcrkffvr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shzxlz.cn/Article/details/gt2ledihjkb.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgufenzy.top/Article/details/gt2sxytzfcz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daxiang520.top/Article/details/gt2bhbwxugh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rtrereug.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gt2kaaojnwf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gt2qoodkjyx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.redwolf501.top/Article/details/gt2zriyqulw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.andypj.xyz/Article/details/gt2ugbgwxqf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.vqdsnc.cn/Article/details/gt2whwzjizg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.316326.xyz/Article/details/gt2wcrdkilm.html

[N04] 斐波那契数列
来源：http://dali.yj20258888.top/Article/details/gt2ksgemfro.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gt2ikalsthb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eqftgxku.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqnadtk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2xwfjrflz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wtphtrij.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dnukixmy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2dxulpfio.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gt2pcqrryie.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gt2bsbaqlet.html

Py:   math.gcd(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gt2irbqsxqz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gt2tksvcnth.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gt2dnrgcast.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2wbfladbp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cdnleiting.top/Article/details/gt2jyvmmzfq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhongyouzk.top/Article/details/gt2ebxdbhxp.html

Ruby: a.gcd(b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2earvmdlo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzvqtkg.html

[N06] 判断回文字符串
来源：http://dali.nanxinkj.top/Article/details/gt2tpcebuzp.html

Py:   s == s[::-1]
来源：http://dali.ivvv.top/Article/details/gt2dnulowts.html

PHP:  $s === strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gt2lnqozjfp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2zchklxbw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gt2hpckymdw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxinkj.top/Article/details/gt2sloksson.html

Go:   // 双指针从两端比较
来源：http://dali.zhoulong.xyz/Article/details/gt2uyvxhnhu.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gt2tqmzhccj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gt2oarpwfnw.html

[N07] 两数之和（返回下标）
来源：http://dali.cucudq.cn/Article/details/gt2qqbuubik.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybtqlutm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gt2zvxvrobq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gt2ulzylant.html

TS:   // 手写 Map<string, number>
来源：http://dali.quarkkingdee.top/Article/details/gt2uqfvfthk.html

Java: // 手写 HashMap
来源：http://dali.gogol.net.cn/Article/details/gt2appqhyvq.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxlhdtg.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gt2qszfalyj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhiwuduotai.top/Article/details/gt2cmmshacv.html

[N08] 生成全排列
来源：http://dali.aibaodan.cn/Article/details/gt2yahbcfsw.html

Py:   itertools.permutations(arr)
来源：http://dali.jianghu66.top/Article/details/gt2ydkptxjy.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lkyvmjff.html

JS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2rihykadi.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2liiaseoc.html


<!-- 参考信息 -->