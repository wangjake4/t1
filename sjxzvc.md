代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gtfbstoxeb.html

Py:   json.loads(s)
来源：http://dali.jlsjyb.cn/Article/details/gtncslfgcc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj202588.top/Article/details/gtmsbnbuvx.html

JS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtwsqpplyt.html

TS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvpeesrw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtwslegxft.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtrrweflgt.html

Ruby: JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtyzetgyzs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guowangkeji.top/Article/details/gtzmkjoywt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gtvfvjjcac.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gtkjlacgkx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtxkgunhay.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxyyxszj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtqqxsakst.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gtnfylzlni.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hysaishi.cn/Article/details/gtvszuchqm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cqqwz.cn/Article/details/gtfmmyamko.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gttkvielvi.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gtompdjcut.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqchkvzg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pengpengdd.cyou/Article/details/gtayepwyqa.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtdkisdedn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtpgzhslgh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtljtroswv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtmpsbaien.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gttdnepphl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gthrxjaksk.html

[K05] 深拷贝对象
来源：http://dali.dianchejie.cn/Article/details/gtndtwjllt.html

Py:   copy.deepcopy(obj)
来源：http://dali.svipenyu.cn/Article/details/gtpujierus.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkikafjg.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtipsirkjk.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtjexxwuqc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gtexdikpka.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gtlxoyujgq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gthispjjia.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gthhprexkg.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gturqrjswk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gtfwufnswt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gtxgdxzoht.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gtvdjaovzq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtcmxybbpl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gtipxsiixs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtqmtskxho.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtqrvpxhze.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtgknmajmg.html

[K07] 进制转换
来源：http://dali.yuxming.cn/Article/details/gtrhvehrra.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtectsrwsz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shzxlz.cn/Article/details/gtothqxgah.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtuiyuutze.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtbfgadomn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtudxotsuj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gtwhmekmxm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gtglfvdvip.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtiebtenbz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gtcznxzlcj.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gtfpymztgc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhixingplan.top/Article/details/gtlerzeoqg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtdfxosppb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gtdgyxdqot.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.bjfxy.top/Article/details/gtzbfbuiso.html

Go:   encoding/gob
来源：http://dali.zycfv.cn/Article/details/gtxhpcrgdk.html

Ruby: Marshal.dump(obj)
来源：http://dali.gogol.net.cn/Article/details/gtygiiqrtq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtiemuvphb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtafigkgpn.html

L. 网络请求
来源：http://dali.yueranfly.top/Article/details/gthfkfkhfv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtsgktpdeo.html

[L01] 发送 GET 请求
来源：http://dali.9152youxi.cn/Article/details/gtlwuyeiea.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gtciumseys.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gtziexarok.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtptndmyen.html

TS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gtcogjosbi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnxiangtu.top/Article/details/gthwbuprxp.html

Go:   resp, err := http.Get(url)
来源：http://dali.guannengcc.top/Article/details/gtypyvvmbp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhongyouzk.top/Article/details/gtppnyhtgz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gturdjawhx.html

[L02] 发送 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtlramnmrm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258.top/Article/details/gthoxargxm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gtfpszikbi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gthtxwdhwy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gtjvfpnsjn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbulhrvsc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sufxvd.cn/Article/details/gtjcouagma.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guowangkeji.top/Article/details/gtwfuczbay.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtinepsjof.html

[L03] 设置自定义请求头
来源：http://dali.zhoulong.xyz/Article/details/gtzlsgfphb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gtxpnanqht.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tianlin.xyz/Article/details/gtuxsdtxlg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtwculwvly.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtmmmbnveo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyaicaww.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gtapatmtvz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuanzx.com/Article/details/gtedsmkszz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtxdcefvsi.html

[L04] 设置超时
来源：http://dali.nwbrower.top/Article/details/gtwhxzqteb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gtbkavhbvr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hammf.cn/Article/details/gtdzlugzes.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsxqjpxm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtpccctchs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gtgkpgplal.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxuanxn.top/Article/details/gtxqjeweeu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yueranfly.top/Article/details/gtbwtzvrfp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shuidangran.top/Article/details/gtetqykhnc.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gtyyuiphwq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ivvv.top/Article/details/gtojzldkde.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hysaishi.cn/Article/details/gtvfcdhiwc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtnbjbvzsw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtbddpurbf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxinkj.top/Article/details/gtybvazrym.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pycfn.com/Article/details/gtcrnkejvh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gttwvmdvdq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gttwowkwos.html

[L06] 解析响应为 JSON
来源：http://dali.tian-w.cn/Article/details/gtewtxrceu.html

Py:   resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtsascksyj.html

PHP:  json_decode($body, true);
来源：http://dali.guannengcc.top/Article/details/gtpissjvew.html

JS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtcyqmldvu.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtlvmkuzso.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtfwigkafm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gtydzhrmob.html

Ruby: JSON.parse(resp.body)
来源：http://dali.andypj.xyz/Article/details/gtlgerxstv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gtuycoptvi.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyholdkzi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gtbljfjiol.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tianlin.xyz/Article/details/gtskaobeem.html

JS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gtunakdiav.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gthciiootk.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gtdyuxapob.html

Go:   resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtahztbrdd.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gtgbwchypq.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtbipydxrg.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gtorfekmlp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtxgxepi.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtowbifr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtqdnliubq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtqklqnodn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gtjddekpsh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daria6918.cn/Article/details/gtsjvjuijx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwqnukoi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gtnmiveapm.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqedxcjah.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gtpxrjvcul.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtxzopufql.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqccnuivz.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gtngetvrfj.html

PHP:  $argv;  $argc;
来源：http://dali.guannengcc.top/Article/details/gtqditrahi.html

JS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtmfcuoazj.html

TS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gtrunvffae.html

Java: args 数组（main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtisynjvsy.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtkdemchux.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gtfqtdrbyn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtukcolekb.html

[M02] 读取环境变量
来源：http://dali.birdmap.top/Article/details/gtuejyubem.html

Py:   os.environ.get("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtgpbtoohv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtpfkcreeb.html

JS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtaljjkqie.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtfpqvymuh.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtrspwtgro.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtarluznek.html

Ruby: ENV["HOME"]
来源：http://dali.tian-w.cn/Article/details/gtitavaxlw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtkewfepfl.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gtrhwutizh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gtqhyktmfj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gtjlomwlxb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtlsvqtzgk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtzwmqtrku.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daxiang520.top/Article/details/gtukbnqiak.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yangfankeji.com/Article/details/gtfeqocaif.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuanzx.com/Article/details/gtevmbbojy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guannengcc.top/Article/details/gtjfjzbkzk.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gtbejmktit.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gtjwaqbpjw.html

PHP:  getcwd();
来源：http://dali.sufxvd.cn/Article/details/gtmacnwfyq.html

JS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtcixszwex.html

TS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtbwejijte.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aizwys.cn/Article/details/gtmhfsswui.html

Go:   os.Getwd()
来源：http://dali.chenlongwang.top/Article/details/gticuricam.html

Ruby: Dir.pwd
来源：http://dali.jlsjyb.cn/Article/details/gtteqpbwnt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gaohongyu789.top/Article/details/gtbsvorgzu.html

[M05] 设置退出码
来源：http://dali.fzhhl.top/Article/details/gtjobkbkne.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtwaookbda.html

PHP:  exit(1);
来源：http://dali.sufxvd.cn/Article/details/gtczsgybmg.html

JS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtrflufbuu.html

TS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtnveebfxy.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtwxupqsbc.html

Go:   os.Exit(1)
来源：http://dali.jianghu66.top/Article/details/gtyvobhzjx.html

Ruby: exit 1
来源：http://dali.jlsjyb.cn/Article/details/gtrvpxzhfj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.c1oappe.top/Article/details/gtpqnmrveh.html

[M06] 向标准错误输出
来源：http://dali.sweek.top/Article/details/gtgramkytc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gtmgjxnmil.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gtojnhmqea.html

JS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtitxvbfjb.html

TS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gtbuqhlajr.html

Java: System.err.println("err")
来源：http://dali.jinqigfzy.top/Article/details/gtrkgcsclh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangdashe.top/Article/details/gtffqojmwl.html

Ruby: warn "err"
来源：http://dali.tian-w.cn/Article/details/gtltphvobp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yangfankeji.com/Article/details/gtqoreczos.html

[M07] 判断是否为主入口
来源：http://dali.feifeiyinyue.top/Article/details/gtaupmjrpx.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gtigusubkf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ehwqpu.com/Article/details/gtmhylkqzu.html

JS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtahhhnauf.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtjaglzzzx.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjptrrcrg.html

Go:   func main()
来源：http://dali.bjfxy.top/Article/details/gtqgbgsysn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gtikfmdeiv.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gtqrhcubys.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgufenzy.top/Article/details/gtqgxnjdzl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ppjwa.cn/Article/details/gtsmqvreqk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gtqfnmuagv.html

JS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gtgyfhznnn.html

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtxbmjkrvu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhiwuduotai.top/Article/details/gtbfnkmrit.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.feifeiyinyue.top/Article/details/gtphkvqsmf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258.top/Article/details/gtgrkhtsfy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.svipenyu.cn/Article/details/gtnzlzsrvu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdauosftv.html

N. 数据结构与算法
来源：http://dali.zycfv.cn/Article/details/gtslgidbol.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtlglrfluc.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gtnmlwgfur.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ivvv.top/Article/details/gtdihptppb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gttflwjpzn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtyloqqbgn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtluoiudey.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtrcpxpluv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtyokectmv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tanke756.top/Article/details/gtyxnqblai.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtlxoxvbfp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuanzx.com/Article/details/gtjfdebuse.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbwbmlyc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gthgtouihd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtgnhcphmo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtweymvhoo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gtgqdypvoo.html

Go:   slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtpocjjsjy.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtyssbspoc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fengsongda.top/Article/details/gtsapwuzwz.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gtlxdgxzoz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hammf.cn/Article/details/gtdhkltvnf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aibaodan.cn/Article/details/gtixzpfpcx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gttgvmpids.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtbrrxrhru.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnxiangtu.top/Article/details/gtlniownsu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gtnenxhjjt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guannengcc.top/Article/details/gtvelgcvae.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gtnkvlgloa.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuphjtkux.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtfuknwsir.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtagdvncvd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gttiywqwpm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtajjoeeuv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gtfgtutxnu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jlsjyb.cn/Article/details/gtkkbnjtgt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gtjhlxsupt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtnradnwhe.html

[N05] 最大公约数
来源：http://dali.tanke756.top/Article/details/gthfshjber.html

Py:   math.gcd(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtggwdyayz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fengsongda.top/Article/details/gtbecalhml.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258888.top/Article/details/gtrwpoxvid.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtnfozdega.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258.top/Article/details/gtkfrklomq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gtmhxxorfs.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrdnpyzj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.iojbl.cn/Article/details/gtnpejzevw.html

[N06] 判断回文字符串
来源：http://dali.zhixingplan.top/Article/details/gtdxbfojdw.html

Py:   s == s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtdswdfmht.html

PHP:  $s === strrev($s);
来源：http://dali.shuidangran.top/Article/details/gtmjkdrjil.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtrdqkqimw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtwonuwozg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fzhhl.top/Article/details/gttijuotjw.html

Go:   // 双指针从两端比较
来源：http://dali.yuxming.cn/Article/details/gtdtwlhztc.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gttnntrbdp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzvylezl.html

[N07] 两数之和（返回下标）
来源：http://dali.hnqzz.top/Article/details/gtustpwxil.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gtzzzmecvc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pycfn.com/Article/details/gtyofljalf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigfzy.top/Article/details/gtwmfoqzpw.html

TS:   // 手写 Map<string, number>
来源：http://dali.daxiang520.top/Article/details/gtluerxvhv.html

Java: // 手写 HashMap
来源：http://dali.nanxinkj.top/Article/details/gtbtsjpxyd.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigufen.top/Article/details/gtplbrsdwf.html

Ruby: // 手写 Hash
来源：http://dali.gogol.net.cn/Article/details/gtfseeiygd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gtkftdlbgc.html

[N08] 生成全排列
来源：http://dali.yanxiufei.cn/Article/details/gtumcghvpw.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gtjipnggsc.html

PHP:  // 手写递归交换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbpytxcs.html

JS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtfxgtxrjd.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtpfvvzgfe.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtpgqlhdor.html

Go:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonfswjqr.html

Ruby: arr.permutation.to_a
来源：http://dali.zhixingplan.top/Article/details/gtvlcwbnnn.html

C#:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtuitdomqg.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtsnhkbgvc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtxhtgdikp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gttfwecyfe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtvfjrbsxw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigfzy.top/Article/details/gtgdvqgjiw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nwbrower.top/Article/details/gtxunnoeyi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cheryme.top/Article/details/gtkmpcshxb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtbzbttdcy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgfzy.top/Article/details/gtltfaqwpu.html

[N10] 链表节点定义
来源：http://dali.yvedp.cn/Article/details/gtxlpexnqv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenlongwang.top/Article/details/gtgaoniclq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gtnrvfmryk.html


<!-- 参考信息 -->