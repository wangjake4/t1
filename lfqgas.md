代发 wailian999

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtiuzqmolc.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gtscsvmpbp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbxoxdrit.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtwfyajqlx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gtdwhsdvxy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtdpagycgm.html

JS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtwmhznwwj.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtghfveqkd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dashuyun.cn/Article/details/gtfgzarboi.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmwgcxpu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gtgcfzeevk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gtmgnsrggm.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigfzy.top/Article/details/gtcryguhzz.html

Py:   json.loads(s)
来源：http://dali.sysykeji.top/Article/details/gtjzwofmyj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gtxjqhkogo.html

JS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtduyabehu.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtuaovgwcl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pycfn.com/Article/details/gtzfqcbkhv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowcppfzf.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtytpxrglu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aibaodan.cn/Article/details/gtxehgfola.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gtleopxbek.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gteqptstid.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtqcdgqduq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtsjznvbzs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gtdydffjme.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xziqi.cn/Article/details/gtqpulhvml.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gtirvupogt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gtezdpwhwv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shuidangran.top/Article/details/gtvtunrdoo.html

[K04] 读取 JSON 文件
来源：http://dali.guannengcc.top/Article/details/gtuonzewmw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gttnahrxga.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ppjwa.cn/Article/details/gtyzepgnon.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtpwosipzl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqfgsqak.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.havefunace.top/Article/details/gteehuhkmi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtnlwssnzz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtoejwsylt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tian-w.cn/Article/details/gtxnnfafqe.html

[K05] 深拷贝对象
来源：http://dali.jiagoushi.top/Article/details/gtrlkxvfcz.html

Py:   copy.deepcopy(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gttsckruxo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gtssdlrlvx.html

JS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gthkncucvp.html

TS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtwwjrtqya.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtgnkgakoi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sxryk.cn/Article/details/gtgxevtprf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gtjvrtwnup.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gtiblodeva.html

[K06] 解析 URL 查询串
来源：http://dali.tianlin.xyz/Article/details/gtxklgkslz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtaoeldfvk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aibaodan.cn/Article/details/gtoyvzwotw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtegqeculf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtracljwca.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gtlpzixyeq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtsmszmzje.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkiafvhuw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtsmtblath.html

[K07] 进制转换
来源：http://dali.xziqi.cn/Article/details/gtthuwucxo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkugyxwm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.bjfxy.top/Article/details/gtqfxjriqg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtwjocxcxp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtoztgygfa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gttfozclqd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gtstanqxcz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zycfv.cn/Article/details/gtmjlotwip.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtsqmsvwkj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaiyakeka.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtpzffsypt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.316326.xyz/Article/details/gtaqicdghp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtciqnulas.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtrujwgwwx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nwbrower.top/Article/details/gtsqcwpxrg.html

Go:   encoding/gob
来源：http://dali.yj20258888.top/Article/details/gtntkxyvvb.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gtpclllprc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtksmhbnuy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gterhbannb.html

L. 网络请求
来源：http://dali.wangshuangyany.cn/Article/details/gtxozhxmzt.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtaidarahv.html

[L01] 发送 GET 请求
来源：http://dali.chenzaomai.com/Article/details/gttvoppotp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gtnkxefxqq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gtpmrtcdoz.html

JS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtkgwqfxfh.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gtaashyifl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbggihqn.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gtulrqqfcl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.meibo888.top/Article/details/gtvrkypnfn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fzhhl.top/Article/details/gtuzgbxyio.html

[L02] 发送 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtahqtqgbz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtrtehhcdh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gtwolejskx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtnccqjviz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtsqjfoifl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gtmyeicyth.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shzxlz.cn/Article/details/gtwesdqmdo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yongpay.top/Article/details/gtwxszmgwr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gtfhbxpvcc.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gtsnbpgwda.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jlsjyb.cn/Article/details/gtjkdcqplc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sysykeji.top/Article/details/gtofwqgcbn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gtkubmcsjo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gtufdwhsjh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sufxvd.cn/Article/details/gthtyqflme.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gtvxluqelp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gtzfnidptu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gtgpkfmedi.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gtkjmqchpo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gtzaiugycd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.quarkkingdee.top/Article/details/gtpxhtilye.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gtxjpzssvh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gtgakwmium.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.meibo888.top/Article/details/gteldpmtil.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gtdieahasg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sysykeji.top/Article/details/gtxphjicto.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gtaqcmskmi.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gtcdxkvpqo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gtgcchmopl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gtbmjvpjfa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxxyefob.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtikidnppa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkuxpbav.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.snrcjt.cn/Article/details/gtjbqobkjc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gtgsjzuxhd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gtwiuliydu.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gtgzqzhlta.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gtqdrpcnlo.html

PHP:  json_decode($body, true);
来源：http://dali.jqgufenzy.top/Article/details/gtcrlfqjvb.html

JS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtagfmrwcf.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtkfbnuxrw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtblueemqq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.meibo888.top/Article/details/gterwxjwfz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tian-w.cn/Article/details/gtovknoluy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gtwolnckps.html

[L07] 处理 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtdrplbgfs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258.top/Article/details/gtfrszmfde.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gtemsyfqwg.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtjupqpttf.html

TS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gtiisjvwvt.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gtrcrgoiqn.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtmwcrnond.html

Ruby: resp.code.to_i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkiiwopom.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gtwnucrxck.html

[L08] 并发请求多个地址
来源：http://dali.yj20258.top/Article/details/gtddljsfsz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hfpthk.cn/Article/details/gtyynnjrby.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gtsjspecps.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtxvvsnbrz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtogajzvyh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hongshengwenyu.top/Article/details/gtjfyjkflo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.feifeiyinyue.top/Article/details/gtfbrxwxwu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxinkj.top/Article/details/gtxiawdxzi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gtiduilqhf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdxjzturx.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gttjdyuaag.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtoapicfpz.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtwiplullu.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gttuyhlvps.html

PHP:  $argv;  $argc;
来源：http://dali.sweek.top/Article/details/gtkisgxira.html

JS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gtqcbpsmgx.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtvwwcbqmq.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupdjtrwo.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gtobtumwpv.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoamkexgi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwuyjkwo.html

[M02] 读取环境变量
来源：http://dali.ivvv.top/Article/details/gtjkmqyukm.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtwpbxbuxz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtctchotsl.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtahouexcz.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtlqdnqell.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gtktrkfbro.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tanke756.top/Article/details/gtzoqhukje.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gtbcqvohah.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtlzlzaerk.html

[M03] 执行外部命令
来源：http://dali.andypj.xyz/Article/details/gtwbnwahdw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.c1oappe.top/Article/details/gtekclduxp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gtsuyrpuum.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtfpxyjouv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtwtxfhscw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sufxvd.cn/Article/details/gtldtfmnob.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gtjjwrhxjq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaboxhile.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pycfn.com/Article/details/gtrfezdkjp.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtgudegcfv.html

Py:   os.getcwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtxgtfhphx.html

PHP:  getcwd();
来源：http://dali.iojbl.cn/Article/details/gtyjyeqepl.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtsbzaxiyi.html

TS:   process.cwd()
来源：http://dali.jiagoushi.top/Article/details/gtkvlciggu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhctfvjk.html

Go:   os.Getwd()
来源：http://dali.jinqigfzy.top/Article/details/gtcjscdqjc.html

Ruby: Dir.pwd
来源：http://dali.fzhhl.top/Article/details/gtsszdgwqh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guannengcc.top/Article/details/gtplcfynpc.html

[M05] 设置退出码
来源：http://dali.cucudq.cn/Article/details/gtavyxmibm.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gttcjmtygw.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gtfsblcnth.html

JS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtbcftnenm.html

TS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gtxmtodzkn.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtfddszubt.html

Go:   os.Exit(1)
来源：http://dali.xziqi.cn/Article/details/gtiuaorgmm.html

Ruby: exit 1
来源：http://dali.xylfe.cn/Article/details/gtxouprwln.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aibaodan.cn/Article/details/gtworkuwoa.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gtzsicgmox.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gtvtsncajy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sysykeji.top/Article/details/gtwfyukckd.html

JS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtdvetmciw.html

TS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gtjmyenwyg.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gtbthlxlld.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cdnleiting.top/Article/details/gtmsfdzuza.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gtpkvtyeti.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gtudtcdsuq.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gtatpfyetp.html

Py:   if __name__ == "__main__":
来源：http://dali.jlsjyb.cn/Article/details/gtaebbktrv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.316326.xyz/Article/details/gtvvafabrw.html

JS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqirmcado.html

TS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gtuwgwlrjk.html

Java: public static void main(String[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanagohtc.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gtshqbcoca.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yueranfly.top/Article/details/gtxthwlaou.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gtvirtqvrp.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gtmxgtebss.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvoqrayg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhosusew.html

JS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtowhjmtbe.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtrabtlety.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ybcxt.top/Article/details/gtxaeadnwe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gtsqyauamg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gaohongyu789.top/Article/details/gtkoiugcqf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuxming.cn/Article/details/gtlsedyjfo.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtaiavxien.html

N. 数据结构与算法
来源：http://dali.shuidangran.top/Article/details/gtnyiwgqrl.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtgfsgokmc.html

[N01] 二分查找（有序数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxisjycp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtpoondhnj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtrmkkwwxt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gttcdhtdfa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtaqwrrqhg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtahveyple.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtotmwupri.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnqzz.top/Article/details/gtdoyfypxt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtigwlzldt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ppjwa.cn/Article/details/gtpgtuvycl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtexftfzgl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtqvrkcszn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtwkeuukif.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtktigrvcw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.quarkkingdee.top/Article/details/gtfudaapjc.html

Go:   slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gtktrawlyf.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gtnhimdqjq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gtetffvmzw.html

[N03] 快速排序（分治示例）
来源：http://dali.haohaochexian.top/Article/details/gtxytpoaov.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhtpkzmo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgfzy.top/Article/details/gtgmcmsslw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtlxlcexao.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gthluppopb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tianlin.xyz/Article/details/gtjvonpwvh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtziutxapk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tian-w.cn/Article/details/gtmtnlvljg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zdqjudy.top/Article/details/gtinodezaf.html

[N04] 斐波那契数列
来源：http://dali.xylfe.cn/Article/details/gtqfdoxbya.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gtdrbybxqe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sxryk.cn/Article/details/gtglfwpfve.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtrhslmvro.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtqulgtcjh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gtjkorptbc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yvedp.cn/Article/details/gtlwsxpvyl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtxbljuxrn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtqsskyykt.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gtcxdjjnhp.html

Py:   math.gcd(a, b)
来源：http://dali.ydzc1.top/Article/details/gtnowugfoe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gogol.net.cn/Article/details/gthouwdpia.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gttwghxsmf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtlezoujxe.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangdashe.top/Article/details/gtvlktrbkm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gtaotcejdl.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gtarbogmqz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.quarkkingdee.top/Article/details/gtedhwtdxu.html

[N06] 判断回文字符串
来源：http://dali.yj20258.top/Article/details/gtkayxvupz.html

Py:   s == s[::-1]
来源：http://dali.ybcxt.top/Article/details/gtymauucbz.html

PHP:  $s === strrev($s);
来源：http://dali.pycfn.com/Article/details/gtfuaxcqtr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtpvwjcvnc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtyhzrszgm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gaohongyu789.top/Article/details/gtcdguqtxc.html

Go:   // 双指针从两端比较
来源：http://dali.nwbrower.top/Article/details/gtihudxvvd.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gtaeiscydp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gtmtuynsmo.html

[N07] 两数之和（返回下标）
来源：http://dali.redwolf501.top/Article/details/gtgfrchalv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gtslpetzbv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.kuanghao11.cn/Article/details/gtabictsjt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gtqixlzwvr.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gtswwnqozs.html

Java: // 手写 HashMap
来源：http://dali.fzhhl.top/Article/details/gtduazsihl.html

Go:   // 手写 map[int]int
来源：http://dali.feifeiyinyue.top/Article/details/gtzivzkgbg.html

Ruby: // 手写 Hash
来源：http://dali.jianghu66.top/Article/details/gtbcpbhteo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gtuluvodbz.html

[N08] 生成全排列
来源：http://dali.shanyushiyangtech.top/Article/details/gtrywykxmq.html

Py:   itertools.permutations(arr)
来源：http://dali.sysykeji.top/Article/details/gtksavebnu.html

PHP:  // 手写递归交换
来源：http://dali.gaohongyu789.top/Article/details/gtgnydtrub.html

JS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gthhnnwvhj.html

TS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtfmnnlqbh.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyaipjoj.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtqikxutlf.html

Ruby: arr.permutation.to_a
来源：http://dali.yonumen.top/Article/details/gtbhhvwpkp.html

C#:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gteaiyafoh.html


<!-- 参考信息 -->