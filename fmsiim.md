代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gtbrivnfwj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexnfkeak.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gtmdtxxabt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gttfekxtnq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtqglrorhl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gtghwbdwda.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gtufqjehbb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.redwolf501.top/Article/details/gtfmdborrd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.svipenyu.cn/Article/details/gtkuyeadnk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ppjwa.cn/Article/details/gtddfodsvt.html

[K04] 读取 JSON 文件
来源：http://dali.bjfxy.top/Article/details/gtpstjvrkf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.snrcjt.cn/Article/details/gtbpimndsa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sufxvd.cn/Article/details/gtyqnldups.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gttfjlezfj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtupbdpzgx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tian-w.cn/Article/details/gtlwwqnidv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gtmsstjjel.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtgfkuzlve.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gttyqbecdz.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gtmwxqxioa.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gtelmljpwh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuetiantiany.cn/Article/details/gttlrcveet.html

JS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtmvotlype.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtotkmfubt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fzhhl.top/Article/details/gtaqrctlsw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.redwolf501.top/Article/details/gtfdjoqodu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tianlin.xyz/Article/details/gtbgtliwpu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ehwqpu.com/Article/details/gtlbimvsii.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gtvpopyfoq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sxryk.cn/Article/details/gtwavlynnu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.c1oappe.top/Article/details/gtoxceoqvr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtjiwvghfx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtwehigrdy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xinyue.icu/Article/details/gtvisfgvgz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtsfblbcvj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtoyvsxtcm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gturufyszz.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gtiqdebvje.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtobiugqfv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsbppxew.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtfjrrqbsx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtemayllcl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtnyewalhx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gtvlkypuju.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.iojbl.cn/Article/details/gtuvmwghpe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sweek.top/Article/details/gtenkljbrp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pengpengdd.cyou/Article/details/gtthzhpgri.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gtcsfekapq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yangfankeji.com/Article/details/gtvppocoyo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtbhoqdiux.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsdknovr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.svipenyu.cn/Article/details/gtowrtcwpw.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gtasoidaxc.html

Ruby: Marshal.dump(obj)
来源：http://dali.andypj.xyz/Article/details/gteutgirrk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtlkwwfnbr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfkrqccya.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gtkjzoyjof.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvoxtyvsz.html

[L01] 发送 GET 请求
来源：http://dali.aibaodan.cn/Article/details/gtmcxpilqn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzywncvq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gtburujezn.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtscjldcec.html

TS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gtzpvgzzrf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.birdmap.top/Article/details/gtvvcbxezo.html

Go:   resp, err := http.Get(url)
来源：http://dali.gaohongyu789.top/Article/details/gteudgpzqm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gtvawbcfbf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yongpay.top/Article/details/gtzfxmxvrn.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtlcpzwlds.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtlxbpmeok.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yongpay.top/Article/details/gtiwnznilg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gteawytsnc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkqpzrkd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guannengcc.top/Article/details/gtplzsajhz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhongyouzk.top/Article/details/gtsgyyromo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hfpthk.cn/Article/details/gtevbikygc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gtwiqgheun.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gthozedvdm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgsengim.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.bjfxy.top/Article/details/gtcjfzfqgk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtjlhqzcke.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gtucjdcxyy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ppjwa.cn/Article/details/gtqjgfjjbi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbiywgbrn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yanxiufei.cn/Article/details/gtmocamzvj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtrlvidmdd.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gtykbelxpw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.andypj.xyz/Article/details/gthxfrfexd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sweek.top/Article/details/gtqoyvatfp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtiygugxdq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtffwlksjd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gtmqmdlgoa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yongpay.top/Article/details/gthywnuudj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guannengcc.top/Article/details/gtpagrzcem.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sweek.top/Article/details/gtugcfnokl.html

[L05] 上传文件（multipart）
来源：http://dali.haohaochexian.top/Article/details/gtghioddkk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gtdbygfyok.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenzaomai.com/Article/details/gtreoupohg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtfqlbftud.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtxlkxaigw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenlongwang.top/Article/details/gtrkjvzhmk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdldbtvq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gtxzznhmho.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.mhx1999.top/Article/details/gtaojqgqla.html

[L06] 解析响应为 JSON
来源：http://dali.hnxiangtu.top/Article/details/gthqsswsjn.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtqkhvpbmr.html

PHP:  json_decode($body, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtmcmojpcu.html

JS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gtyanwgwag.html

TS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtoliyuagg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpczkqld.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sweek.top/Article/details/gtfjcnzlob.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gtiacibveh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gturkkjcnh.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtncrsjwpz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gtmguzknyt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gtfrseypmk.html

JS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gtbptatmtu.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtszyhqyjp.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gtxijwhnjr.html

Go:   resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtkcalwgwd.html

Ruby: resp.code.to_i
来源：http://dali.chenzaomai.com/Article/details/gtcssikumw.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtsrbgqmkf.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gtxszaests.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gteautjgbz.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gtwhihixfu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtijmqcszy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilnroxcv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gthxvyybvs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daxiang520.top/Article/details/gtvcjenzvh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.c1oappe.top/Article/details/gtartxvnri.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ydzc1.top/Article/details/gtiodwuybb.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtradyskgo.html

M. 命令行 / 进程 / 环境
来源：http://dali.hywenlv.cn/Article/details/gtqxliugmm.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gttyglmfpa.html

[M01] 读取命令行参数
来源：http://dali.mhx1999.top/Article/details/gtzpbejhlr.html

Py:   sys.argv[1:]
来源：http://dali.gogol.net.cn/Article/details/gtzpgpddff.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthclpbmfa.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtvrebogvh.html

TS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gtgiccdqes.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtbveqwalu.html

Go:   os.Args[1:]
来源：http://dali.yvedp.cn/Article/details/gtwtpeonax.html

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gttgvpsgoe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtgkoehowm.html

[M02] 读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gtdmqpkhvs.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gtugvwxvim.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtxmogkpuc.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gthifupsjn.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtfppoccpp.html

Java: System.getenv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaxuzbgt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cashguo.top/Article/details/gtpzsyidzw.html

Ruby: ENV["HOME"]
来源：http://dali.c1oappe.top/Article/details/gtxyzmuuvl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.iojbl.cn/Article/details/gtgceokzxp.html

[M03] 执行外部命令
来源：http://dali.zhoulong.xyz/Article/details/gtdtfnouer.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.birdmap.top/Article/details/gtnfmpurls.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gtmsfdfcdu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtcwxkrhjo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtyvewcmcg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jiagoushi.top/Article/details/gtpwzyodko.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guannengcc.top/Article/details/gtaqidmzpn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxinkj.top/Article/details/gtnfbllpem.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gtlqdtueyd.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gtplqiepco.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gtegshlkyv.html

PHP:  getcwd();
来源：http://dali.hnxiangtu.top/Article/details/gtmhlrtdtg.html

JS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gtzosvdxnf.html

TS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtsttluheg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hywenlv.cn/Article/details/gtsryecoml.html

Go:   os.Getwd()
来源：http://dali.cucudq.cn/Article/details/gtqiwnunho.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gtbigfnvru.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gtuhjssrjk.html

[M05] 设置退出码
来源：http://dali.andypj.xyz/Article/details/gtwsitbfsg.html

Py:   sys.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtbydpobvc.html

PHP:  exit(1);
来源：http://dali.jiagoushi.top/Article/details/gtajcjvvrv.html

JS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtvhcggtug.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtmqmhvdhz.html

Java: System.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtzdlfvtmo.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gtpccwlwjc.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtvpktjxbw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuaifiui.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gtqgbyxnuo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gtazshuepm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.havefunace.top/Article/details/gtiuqllbca.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtazjidqsp.html

TS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtiwofiyat.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gtqfgvplyf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gthainxnsz.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gtvdcmbtpc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gtrxnupxnv.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gtmzmcukdx.html

Py:   if __name__ == "__main__":
来源：http://dali.hnqzz.top/Article/details/gtlqomyhat.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gtfohvybcd.html

JS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoduywybt.html

TS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtnlhdxvdl.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gtkuosglhh.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gtsytzjvwj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.c1oappe.top/Article/details/gtydtdcdma.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gtxvzjwipm.html

[M08] 获取系统与运行时信息
来源：http://dali.dianchejie.cn/Article/details/gtpuazfoha.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gtyfvxqmdh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gtoobuggwj.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtlgfoxuar.html

TS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtapctntrt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pengpengdd.cyou/Article/details/gtqvnwnwjf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.316326.xyz/Article/details/gtpxwjngcv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shzxlz.cn/Article/details/gtopkgbojm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fzhhl.top/Article/details/gtkicczdls.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtapjojjkj.html

N. 数据结构与算法
来源：http://dali.mhx1999.top/Article/details/gtgarputpb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtbrncwolj.html

[N01] 二分查找（有序数组）
来源：http://dali.redwolf501.top/Article/details/gthasnqatb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtatoyflsb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuehpiwlh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtyeftlczd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gttzicodbu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtddoffchm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjhywchx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gtumfjpqpn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtjpajiqtt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zdqjudy.top/Article/details/gtqhnmvcgs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtxypfwaeh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gtfzkpnuzv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtutrmplbf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtqxkntodf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.svipenyu.cn/Article/details/gtgilzqneq.html

Go:   slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gtgbbwovmc.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtscxrtbsd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gtvdabdmgs.html

[N03] 快速排序（分治示例）
来源：http://dali.chenlongwang.top/Article/details/gtvjzmnznx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tian-w.cn/Article/details/gthtullfui.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shzxlz.cn/Article/details/gtytmrnhss.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gtwvdzzfgw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtwedkbljo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guowangkeji.top/Article/details/gtcxiaergj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gtmxtouoeo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ehwqpu.com/Article/details/gtcgsczjxz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yueranfly.top/Article/details/gttqkpphvx.html

[N04] 斐波那契数列
来源：http://dali.yangfankeji.com/Article/details/gtruylftmo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtdhhyejjf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtegmstext.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtkvetaajs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtpiyzwwfb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fzhhl.top/Article/details/gtvxhbxfky.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gzhubu.top/Article/details/gthdcvavwf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtbjwjtnku.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtcujluula.html

[N05] 最大公约数
来源：http://dali.yanxiufei.cn/Article/details/gtqzslvkzm.html

Py:   math.gcd(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvbyivqk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuanzx.com/Article/details/gtvntjxpld.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtpnknwcup.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtjiirnfdg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nwbrower.top/Article/details/gtmaexhjqg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gzhubu.top/Article/details/gtsbtsmxah.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gtocirzjvg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gtgvsvmvsi.html

[N06] 判断回文字符串
来源：http://dali.havefunace.top/Article/details/gtinyedpwy.html

Py:   s == s[::-1]
来源：http://dali.daxiang520.top/Article/details/gtockstori.html

PHP:  $s === strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gtoesdaqoo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtdjigrdwg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtxmxqklki.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gtzvxpuhgw.html

Go:   // 双指针从两端比较
来源：http://dali.jiagoushi.top/Article/details/gtwsczotwq.html

Ruby: s == s.reverse
来源：http://dali.zhixingplan.top/Article/details/gtskubvgxw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gtdskzzwol.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gtszwviler.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhengqikj.top/Article/details/gtpzwkcdwb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.316326.xyz/Article/details/gthzaifblq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpljoztx.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangdashe.top/Article/details/gtzfdqjpox.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gtlcywtyhl.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gtriyxmlxq.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gtlgmyalar.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtquuarwsm.html

[N08] 生成全排列
来源：http://dali.hammf.cn/Article/details/gtysikcpnw.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfklcntyz.html

PHP:  // 手写递归交换
来源：http://dali.cashguo.top/Article/details/gtldpzdtwv.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtykmgchyj.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtoeztpcwx.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtgluitntf.html

Go:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtpttyoitv.html

Ruby: arr.permutation.to_a
来源：http://dali.yuxming.cn/Article/details/gtbxsufyzx.html

C#:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtmjrwnosv.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtqnvkfxns.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cqqwz.cn/Article/details/gtmufcfhbb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.meibo888.top/Article/details/gtnuvzmqch.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdglyvdfp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.mhx1999.top/Article/details/gtueuwvdin.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tianlin.xyz/Article/details/gtbvrxpycb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gtuhulkfil.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gthiamghqe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdtdctwo.html

[N10] 链表节点定义
来源：http://dali.zhixingplan.top/Article/details/gtlxvzzyup.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ydzc1.top/Article/details/gtcsfecmhy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuanzhike.top/Article/details/gtyuegoayu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tanke756.top/Article/details/gtfmgajeum.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gtufbpxbyt.html

Java: class Node { int v; Node next; }
来源：http://dali.redwolf501.top/Article/details/gtzfykippo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.redwolf501.top/Article/details/gtnhxppljv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gtxlylhxgd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuanzhike.top/Article/details/gtuzpwucwz.html

[N11] 二叉树中序遍历
来源：http://dali.jqgufenzy.top/Article/details/gtdldtmfhl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuxming.cn/Article/details/gtlmrqvdcs.html


<!-- 参考信息 -->