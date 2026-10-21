代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtdafnejgi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gtmsumncbc.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtaezjwhqx.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtgzonvvle.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenjidiqi.icu/Article/details/gtdvjgnbpu.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gtkaoxawis.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnxiangtu.top/Article/details/gtmjipzinh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gtclucsgct.html

[K02] JSON 字符串转对象
来源：http://dali.xuanzx.com/Article/details/gtvwjxgicw.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gtstixxonh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hysaishi.cn/Article/details/gtljogviza.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtbsiezphi.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtlsbcqlbj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gtyiaxkewx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gteptgjnec.html

Ruby: JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtycjhqixi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gzhubu.top/Article/details/gtbacmjicg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigufen.top/Article/details/gtwfjefrqi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtgppcrhtc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gttpifcxzl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gtundlzvyq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtqubicnxw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sufxvd.cn/Article/details/gtpiboiurx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ivvv.top/Article/details/gtbupnqejj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dianchejie.cn/Article/details/gtiuezzspm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gtruvwzxpd.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gtauaawdzl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuxming.cn/Article/details/gtpohzdpcr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gtztpdcqje.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gtiplikghj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtfjsqeqmb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtrhpfabki.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtedvyiisq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtdmxvlknt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gtwjbscqjp.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gtqkbkwcpj.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenzaomai.com/Article/details/gtgblopvqf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxuanxn.top/Article/details/gtwtqtdjqq.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtzqjvhgec.html

TS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gtesnqbkza.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yueranfly.top/Article/details/gtwyojhszm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.smart0.xyz/Article/details/gtmrvjiplj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbpimqhj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gthogrbmdi.html

[K06] 解析 URL 查询串
来源：http://dali.hysaishi.cn/Article/details/gtkrlpilvv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gtdezrhnkd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dianchejie.cn/Article/details/gtnjwlibfz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gtpxyuzokf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtvvnmarcw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhixingplan.top/Article/details/gtljnhbefi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtfpypwxkx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtwwmgmcmp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtnmlqjxbl.html

[K07] 进制转换
来源：http://dali.sxryk.cn/Article/details/gtxyfbzbhm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtsbuihaii.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xinyue.icu/Article/details/gtvuxxrxig.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gttrzbsidr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtuewkzcgc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtukmgelbw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gtwtivzsdg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yonumen.top/Article/details/gtalcdguqe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtmjoagfft.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmcwzurm.html

Py:   pickle.dumps(obj)
来源：http://dali.birdmap.top/Article/details/gtnarbovyd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tian-w.cn/Article/details/gtobapmopg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gthuebmolg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtphpwcfgw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gtbjcofzqk.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gtorbedfqf.html

Ruby: Marshal.dump(obj)
来源：http://dali.xylfe.cn/Article/details/gttfqppvut.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtmkqihrav.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmvxqopny.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gthohsvwgq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtfwtkekwj.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gtiwnepjmy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gtmteopmcn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.c1oappe.top/Article/details/gtimgaddab.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtobycwdbi.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gthjxismhq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gtlcbgqune.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenlongwang.top/Article/details/gtstjwdema.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangshuangyany.cn/Article/details/gtpnjaxest.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gtfdabztit.html

[L02] 发送 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gtrkjyxcxi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gttlaudpap.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhixingplan.top/Article/details/gtdmiadrzh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gtpmuljcxz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gtabdhhqnc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtecgblhoz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gtvyczhvob.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gttcfiiaxs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gzhubu.top/Article/details/gtbvqerhcb.html

[L03] 设置自定义请求头
来源：http://dali.sxryk.cn/Article/details/gtjobinsve.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gtxjdxaljl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dianchejie.cn/Article/details/gtoucnlldz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtcfawrsyb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayjfqvkv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gthvmlmhlx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtxdsagvre.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gtgqphgqfs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtggqrqnox.html

[L04] 设置超时
来源：http://dali.yj202588.top/Article/details/gtjaaineur.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fengsongda.top/Article/details/gtihngtogs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xinyue.icu/Article/details/gtdgjsyque.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gtvmcayund.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtoidoalfd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daria6918.cn/Article/details/gtjzhravkl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gtkkfwmjyi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gtftcvnyqc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gtnleoqehb.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gtqpezmbvt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aibaodan.cn/Article/details/gtzoxfusxi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gthmiqetht.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gtttfpepxz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gtjmraefge.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cheryme.top/Article/details/gtqspmuvmr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gtvioojvhl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gzhubu.top/Article/details/gtkfgmltpv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtrftlgjsp.html

[L06] 解析响应为 JSON
来源：http://dali.jyoumei.cn/Article/details/gtfjglfzaw.html

Py:   resp.json()
来源：http://dali.yueranfly.top/Article/details/gtsxkhphor.html

PHP:  json_decode($body, true);
来源：http://dali.ybcxt.top/Article/details/gtsfyrfioa.html

JS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtpkglmudk.html

TS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtokvpydpe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtgytxmyfb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gtyjgeieiz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gtdeuhbbqv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gtypqhyuwp.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtejmwegon.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258.top/Article/details/gtzemehcgv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dianchejie.cn/Article/details/gtmnovzdlr.html

JS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gtkgbuqwtf.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtgpxhhgqh.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gtsmadqcpk.html

Go:   resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gtcytqqnfn.html

Ruby: resp.code.to_i
来源：http://dali.dashuyun.cn/Article/details/gtdiitxxeh.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtgfbzrfds.html

[L08] 并发请求多个地址
来源：http://dali.jinqigfzy.top/Article/details/gtryiojcwy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tianlin.xyz/Article/details/gtdflmvdcr.html

PHP:  curl_multi_init() 系列
来源：http://dali.meibo888.top/Article/details/gtrdssvegn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtcbzvndsf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtvrtarqop.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gtlqxrwkqe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxinkj.top/Article/details/gtdftbggqy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gtzvvlksfl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gtuyddvwog.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtghnqjdop.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gtzjfpkhjq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtlqtujoua.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtkdohwkyc.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gtawczojht.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gtxvktexjn.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gtoyvpfmqz.html

TS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtfdxowhlm.html

Java: args 数组（main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtabndltop.html

Go:   os.Args[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtlymjdnex.html

Ruby: ARGV
来源：http://dali.yj202588.top/Article/details/gtwjijyghk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtftmxckrc.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gtkszczvdv.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtmkbfytfr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gtqlqupgcd.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtkjnquitx.html

TS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gttmyspqxx.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtemexlicm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sweek.top/Article/details/gtmpateijy.html

Ruby: ENV["HOME"]
来源：http://dali.jqgufenzy.top/Article/details/gtrecukonl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.iojbl.cn/Article/details/gtmglsrqaw.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangtech.top/Article/details/gteugfcdhq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cqqwz.cn/Article/details/gtjqfyfwtu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daria6918.cn/Article/details/gtvkmetspc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gttqwzprmk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gtfnlcnany.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gtlejqfyza.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cqqwz.cn/Article/details/gthbzlgfde.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gtnesgsnky.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenlongwang.top/Article/details/gtqxftvfmq.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gtbzsjafrt.html

Py:   os.getcwd()
来源：http://dali.hywenlv.cn/Article/details/gtgqjedjnp.html

PHP:  getcwd();
来源：http://dali.fzhhl.top/Article/details/gtsioepkvn.html

JS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gtcmakeula.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtmoiiwlip.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jiagoushi.top/Article/details/gthmkzilfx.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtphpyouyl.html

Ruby: Dir.pwd
来源：http://dali.tanke756.top/Article/details/gtsebavswk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gtskfdmrcl.html

[M05] 设置退出码
来源：http://dali.svipenyu.cn/Article/details/gtijsnmncd.html

Py:   sys.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtowkkpgup.html

PHP:  exit(1);
来源：http://dali.jinqigfzy.top/Article/details/gtzlmrgsvc.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtctrqvekp.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtdoituybv.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtllnqhhki.html

Go:   os.Exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtpwzcbpbd.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gthooxumuv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jiagoushi.top/Article/details/gtbrnedyas.html

[M06] 向标准错误输出
来源：http://dali.bjfxy.top/Article/details/gtxqzlvvnx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gtrloqayzk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gtnvmhmlvf.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtvaquqmuo.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtfxxdotvy.html

Java: System.err.println("err")
来源：http://dali.shzxlz.cn/Article/details/gtvdtyvrte.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.haohaochexian.top/Article/details/gtnqobokts.html

Ruby: warn "err"
来源：http://dali.jianghu66.top/Article/details/gtxkwjtrta.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yonumen.top/Article/details/gtmwwrggzq.html

[M07] 判断是否为主入口
来源：http://dali.gaohongyu789.top/Article/details/gtiyvpsqmj.html

Py:   if __name__ == "__main__":
来源：http://dali.andypj.xyz/Article/details/gtrtoxeqyo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258.top/Article/details/gtyishjngr.html

JS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gtlltxmoad.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlnhthqz.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gtrokozezz.html

Go:   func main()
来源：http://dali.zhoulong.xyz/Article/details/gtbxzrdxay.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gtdfkfrgfp.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258888.top/Article/details/gtxrjpvthf.html

[M08] 获取系统与运行时信息
来源：http://dali.feifeiyinyue.top/Article/details/gtkgeljfaa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.birdmap.top/Article/details/gtmbroubea.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxuanxn.top/Article/details/gtxvnohzxx.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtgclwfyvx.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtaiecmbhs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258888.top/Article/details/gtpiqxhhxk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gthomwdozg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.meibo888.top/Article/details/gtdvprftzz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gtpudhrbts.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtskoxyoyr.html

N. 数据结构与算法
来源：http://dali.pycfn.com/Article/details/gtmfdrypwl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtxivmfpsg.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gtfkbgpykx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbibwecbz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtajckmijf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtxetxzpnf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtmihdkhbh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtcrfvqsku.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtmlbioqto.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgfzy.top/Article/details/gtnesgxzsp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtadlnbfrq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yongpay.top/Article/details/gtiihzvcdk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtkiqyvjpe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tianlin.xyz/Article/details/gtcrutxilg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtzkkgokqd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtlxokzobo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujnvvakr.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtxmxkgkch.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gtqlyjjicp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gtiissocwb.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gtyqlozgmt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenlongwang.top/Article/details/gtiamcigzv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj202588.top/Article/details/gtrokuskgs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtaqiljvdk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtpywjefws.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnxiangtu.top/Article/details/gtdfhyunjz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cucudq.cn/Article/details/gtnbjqsgvu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gtnmjhecca.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnqzz.top/Article/details/gtrcrrtqqi.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gtutsujjle.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gtqdfaulkm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ivvv.top/Article/details/gtnfctukqi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmcahopo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtftqzxggt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daria6918.cn/Article/details/gtriuakhdx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.316326.xyz/Article/details/gtldjlesvm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtieciseag.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtyrofkcno.html

[N05] 最大公约数
来源：http://dali.zhongyouzk.top/Article/details/gtthjpwxau.html

Py:   math.gcd(a, b)
来源：http://dali.tian-w.cn/Article/details/gtbtxhzdoq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jyoumei.cn/Article/details/gtydxzjunt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtenufosbg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtldxzcjwp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.iojbl.cn/Article/details/gttasmkccx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhixingplan.top/Article/details/gthgyqxkpp.html

Ruby: a.gcd(b)
来源：http://dali.daria6918.cn/Article/details/gtnzmeujgn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenjidiqi.icu/Article/details/gtuancwxlj.html

[N06] 判断回文字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtgcfytimd.html

Py:   s == s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtlagxjxoz.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtgqoocgqn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtljdfzmqc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtrdwtvdvd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtznymbruw.html

Go:   // 双指针从两端比较
来源：http://dali.daria6918.cn/Article/details/gtfrjslydj.html

Ruby: s == s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtljoyaije.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gteitbggds.html

[N07] 两数之和（返回下标）
来源：http://dali.pycfn.com/Article/details/gtnsskkhll.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.iojbl.cn/Article/details/gtkmuwhmxv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daria6918.cn/Article/details/gtqntfjjep.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shzxlz.cn/Article/details/gthyoinomu.html

TS:   // 手写 Map<string, number>
来源：http://dali.hammf.cn/Article/details/gtmspmtxnn.html

Java: // 手写 HashMap
来源：http://dali.zdqjudy.top/Article/details/gtpsycessg.html

Go:   // 手写 map[int]int
来源：http://dali.aibaodan.cn/Article/details/gtbhzxtwin.html

Ruby: // 手写 Hash
来源：http://dali.tanke756.top/Article/details/gtxsdkintg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zdqjudy.top/Article/details/gtuepldgqr.html

[N08] 生成全排列
来源：http://dali.fengsongda.top/Article/details/gtnfynqshd.html

Py:   itertools.permutations(arr)
来源：http://dali.yvedp.cn/Article/details/gtybbypnbi.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimiazefr.html

JS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtffigmklw.html

TS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtjvevdxgu.html

Java: // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtovdfombe.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtobbiabdc.html

Ruby: arr.permutation.to_a
来源：http://dali.shuidangran.top/Article/details/gtostysypf.html

C#:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtdvdoyrap.html

[N09] 栈与队列
来源：http://dali.nanxinkj.top/Article/details/gtflzxiqzh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ehwqpu.com/Article/details/gtcwqzklqy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gtskylsoqp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gttephkbon.html


<!-- 参考信息 -->