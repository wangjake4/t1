代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtqqlcskku.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gtoqjjdgxz.html

[K04] 读取 JSON 文件
来源：http://dali.iojbl.cn/Article/details/gtyrtxqjvw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gtjjaaufot.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtseuklfip.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gtqatcfvzh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtxsizckof.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtmvdygbxr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtfkanwegz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtbchcnelc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtbvaqfwpp.html

[K05] 深拷贝对象
来源：http://dali.chenzaomai.com/Article/details/gtoqiukjdd.html

Py:   copy.deepcopy(obj)
来源：http://dali.jianghu66.top/Article/details/gtyngdkmos.html

PHP:  unserialize(serialize($obj));
来源：http://dali.0kj1m.cn/Article/details/gtfjjdtnyx.html

JS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtlzitksss.html

TS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtnethjuub.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gtrkjupfht.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gtptxfzfsm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258.top/Article/details/gtdsaqjkii.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yanxiufei.cn/Article/details/gtmoceydhg.html

[K06] 解析 URL 查询串
来源：http://dali.jqgfzy.top/Article/details/gtsxfxgrsa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtwkyjlpxs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guannengcc.top/Article/details/gteotkswzn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtabqfqhcv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtbmtehijs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gtpcchjsep.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gtnbrutpxv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtwcquxeto.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtdhxhoqpo.html

[K07] 进制转换
来源：http://dali.0kj1m.cn/Article/details/gtbxgztjgl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtfadqtqrl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cheryme.top/Article/details/gtzzsbxcym.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtmsvcrvil.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtzmguzpdi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtaevekmhf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hysaishi.cn/Article/details/gtlspbbiwt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ivvv.top/Article/details/gtfehsftjy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtsmpzmdfa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hammf.cn/Article/details/gtfjxkyqhy.html

Py:   pickle.dumps(obj)
来源：http://dali.zhengqikj.top/Article/details/gtdwkfsvas.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ybcxt.top/Article/details/gtealasupr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtxigipnho.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtdzrrstby.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuxming.cn/Article/details/gtgtwmqvqw.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gtqrbregaa.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenlongwang.top/Article/details/gtwzmyytzn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtzydupfvk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthfgaziae.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gthplybtzv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtwgcpktcs.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gtwwnkvjdk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gtynyzhgyx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sweek.top/Article/details/gtfieborwv.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtpuealqzd.html

TS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gtaalmigbq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gtmdaievyj.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhixingplan.top/Article/details/gtgsssdcrl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gtidrhmqnl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gtluzkfxeh.html

[L02] 发送 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gtqgqxduoj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtisqdqcwn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.316326.xyz/Article/details/gtbptxopkh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtlzvrrvfg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtnihjximg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtrjyalrpj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gtsxewakfy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gtwsxmbztu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cdnleiting.top/Article/details/gtfiuvtnhi.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gtsftvdfgd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.meibo888.top/Article/details/gtyneorymh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gtntffrjvt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gtxbvzbwhp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtdvfozecm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hywenlv.cn/Article/details/gtcektyitl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttigoptvi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gtxobfejgw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtzcbjcdcg.html

[L04] 设置超时
来源：http://dali.zycfv.cn/Article/details/gtiktixvgt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cdnleiting.top/Article/details/gtozjeomzt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cashguo.top/Article/details/gtaofreesp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gtqlwgzxsp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gtpsgxjmnn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yongpay.top/Article/details/gtnrrmjxxo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuetiantiany.cn/Article/details/gtmchjfhas.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.quarkkingdee.top/Article/details/gtrugjpccp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gtmbugpklw.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gtngudfhli.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gtmghkecqm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ydzc1.top/Article/details/gtdxalhhlp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gtbvokmlcd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtbelglihm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gtgzfapvoj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zdqjudy.top/Article/details/gtqottywbr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fengsongda.top/Article/details/gtjpbqxexa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tian-w.cn/Article/details/gthqaqsubz.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gtpgraznys.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtmxataznx.html

PHP:  json_decode($body, true);
来源：http://dali.gotoacloud.top/Article/details/gtspcmekzo.html

JS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtmgfltdpy.html

TS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtevnynzjn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtvptjnwpj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gthddcmkhn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhjhlsbh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gtqnqwhytr.html

[L07] 处理 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gtqmtgesqc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hywenlv.cn/Article/details/gtzdghmhlm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gteglydulo.html

JS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtlptqqxso.html

TS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtwpupcxze.html

Java: resp.statusCode()
来源：http://dali.quarkkingdee.top/Article/details/gtklysvwpb.html

Go:   resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gtkvsrygoi.html

Ruby: resp.code.to_i
来源：http://dali.snrcjt.cn/Article/details/gtvfvfgbml.html

C#:   (int)resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtwiouugqs.html

[L08] 并发请求多个地址
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrnngjlk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pycfn.com/Article/details/gtaxbrirht.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gtvhvmtdgp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtishyrinw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfseevmnd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtndkckzjb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gtzitrvprt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gtpkkxjmvp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.haohaochexian.top/Article/details/gtcomverhg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttnouhzpz.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblcatniv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzwonmtz.html

[M01] 读取命令行参数
来源：http://dali.zycfv.cn/Article/details/gtekmhcmvu.html

Py:   sys.argv[1:]
来源：http://dali.shzxlz.cn/Article/details/gtzdfmxhfk.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gthdvhubra.html

JS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gtoadkudcv.html

TS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gtdyiwuddx.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtesiufunj.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gtigivxzig.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gtltychtkk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cheryme.top/Article/details/gtksyzwopu.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gtkpygekhw.html

Py:   os.environ.get("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtmwwsljmu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtagpmxzwm.html

JS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gtoxcbghbf.html

TS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gtezcpvrdc.html

Java: System.getenv("HOME")
来源：http://dali.fengsongda.top/Article/details/gtambkltow.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtgplemhsm.html

Ruby: ENV["HOME"]
来源：http://dali.jyoumei.cn/Article/details/gtuasuwncp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtelvmfksu.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gtcnlcnsve.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jyoumei.cn/Article/details/gtmyqvjyjw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhengqikj.top/Article/details/gtnwkzfsti.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtsjsuoywa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtwhzojmss.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxinkj.top/Article/details/gtbpmiajek.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gtaoozgafn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gtvkgopnnk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtslduow.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gtlvpwoblq.html

Py:   os.getcwd()
来源：http://dali.0kj1m.cn/Article/details/gtqemplvkm.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gttazeujlr.html

JS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gtimpbzjew.html

TS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gtjpnjmbcn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gtdvcutdzu.html

Go:   os.Getwd()
来源：http://dali.shuidangran.top/Article/details/gtehrsgvfm.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gtpwjovlgc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shuidangran.top/Article/details/gtfecauvmh.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gtmupyimuw.html

Py:   sys.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtiefgowhl.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gtvcyyiwmn.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gteccsvdrx.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtjqsyepuo.html

Java: System.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtivjtzhzx.html

Go:   os.Exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtixsnwzae.html

Ruby: exit 1
来源：http://dali.shangyingyoupin.top/Article/details/gtfanarkpn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hongshengwenyu.top/Article/details/gtzxauiixu.html

[M06] 向标准错误输出
来源：http://dali.haohaochexian.top/Article/details/gtiqgbkdeg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gtcrljdytt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gtjqpxjulz.html

JS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtuaarkamb.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtkgaeudlo.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gtkbtilncy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.316326.xyz/Article/details/gtycobczva.html

Ruby: warn "err"
来源：http://dali.zhongyouzk.top/Article/details/gtztqszrva.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gtujpndwah.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gtqfapsins.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gtlclgefry.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvziswstt.html

JS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gthvdjwvks.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtayizngyp.html

Java: public static void main(String[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtwgixsuzv.html

Go:   func main()
来源：http://dali.yuxming.cn/Article/details/gtdljsygtp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.haohaochexian.top/Article/details/gteajymxii.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gttlpophtw.html

[M08] 获取系统与运行时信息
来源：http://dali.gogol.net.cn/Article/details/gtuxhvosmo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgufenzy.top/Article/details/gtoxhjxsmv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ivvv.top/Article/details/gtecjrctyx.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtbobhhdxu.html

TS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtzykoplgm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gtxajmzhuk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gtanqtdnbd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daria6918.cn/Article/details/gtsxxkbhju.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.feifeiyinyue.top/Article/details/gtojjialco.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtxuhshlpl.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gtkqoqygct.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtfiglmicv.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtpyelqkyu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtntmlrntr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtghgwayfz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gttczoazmq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtkpbnsjvw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtizfkvlpe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtdalprtuy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigufen.top/Article/details/gtlzedqxyn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtburtkjqq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sysykeji.top/Article/details/gtyzimtndk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gthwofnnyr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gtcdvrlhig.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtigloesmi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtxmxijxul.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gtozlgenzu.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtgbdpxkhu.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtiwimruzn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnxiangtu.top/Article/details/gtzbdwhgtv.html

[N03] 快速排序（分治示例）
来源：http://dali.nwbrower.top/Article/details/gtmzpjdzqg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigufen.top/Article/details/gtchsedfkd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yvedp.cn/Article/details/gtyvwjozcr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gtvywgqmfi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtpvqfjnlt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenzaomai.com/Article/details/gtokptybwe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xziqi.cn/Article/details/gtninqcndy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.iojbl.cn/Article/details/gtetyfmfas.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gtgdmxblfg.html

[N04] 斐波那契数列
来源：http://dali.xylfe.cn/Article/details/gtazgqwbzn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gttecrbcva.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258.top/Article/details/gtnbnrcmzf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtijccyqof.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtlmgmmwsq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cheryme.top/Article/details/gtbnjxtcet.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.havefunace.top/Article/details/gtbfzvwesj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gtoivvmhon.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtfxjhudsq.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gtlilbkrqe.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzygzgzsd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtgqwgeeqp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gtgxiclari.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtergrlklf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pycfn.com/Article/details/gtewsowjgy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajsmdrbk.html

Ruby: a.gcd(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpiagizsz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gtvhneblfo.html

[N06] 判断回文字符串
来源：http://dali.yvedp.cn/Article/details/gtetziolmi.html

Py:   s == s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gtggozdsqo.html

PHP:  $s === strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gtlaafvulh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtgnrjlwmu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtlkgnussc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenlongwang.top/Article/details/gtxhajdzaw.html

Go:   // 双指针从两端比较
来源：http://dali.wangshuangyany.cn/Article/details/gtyicmfvep.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gtmszftxko.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtthcnwwgo.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gtvojxsafp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gtnmjvybso.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangshuangyany.cn/Article/details/gtjaevzrsx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.316326.xyz/Article/details/gtbpdqfhnl.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gtddxoupas.html

Java: // 手写 HashMap
来源：http://dali.nanxuanxn.top/Article/details/gtlyaidmca.html

Go:   // 手写 map[int]int
来源：http://dali.ivvv.top/Article/details/gtgbobcdlb.html

Ruby: // 手写 Hash
来源：http://dali.sxryk.cn/Article/details/gtwqfyuljh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gtpcdkunjz.html

[N08] 生成全排列
来源：http://dali.sweek.top/Article/details/gtcpdrjidz.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gtqcilsxvq.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvviwjph.html

JS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtfqmsmmeo.html

TS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtarsnvgkd.html

Java: // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtekbndjil.html

Go:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtjrydglvi.html

Ruby: arr.permutation.to_a
来源：http://dali.zhongyouzk.top/Article/details/gtmdrrvhsa.html

C#:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtcqfctvoo.html

[N09] 栈与队列
来源：http://dali.cheryme.top/Article/details/gtmpvmwfcx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuxming.cn/Article/details/gtzgkukjmf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtlekbxsmq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gteqwaeffe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhongyouzk.top/Article/details/gtxodttwje.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gtyypxhmyk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuetiantiany.cn/Article/details/gtrgizmofv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtrobhxszb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gteumrglsd.html

[N10] 链表节点定义
来源：http://dali.shuidangran.top/Article/details/gtbnbnkozy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shangyingyoupin.top/Article/details/gtarclljff.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenlongwang.top/Article/details/gtbaaxqwaz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlssuicfu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjavdbzyu.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gtewwdcbcu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgfqning.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gtilphfabj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyxqffoq.html

[N11] 二叉树中序遍历
来源：http://dali.zycfv.cn/Article/details/gtdhtgiqlt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gtkbmrfcea.html

PHP:  // 手写递归函数
来源：http://dali.xuanzx.com/Article/details/gtxdwknndu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqvsqwod.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gtncpjduzl.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtnpsbikag.html

Go:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gtflguuiyf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangdashe.top/Article/details/gtlkwgbhrg.html

C#:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gthjdlctui.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cqqwz.cn/Article/details/gtgcgwqypq.html


<!-- 参考信息 -->