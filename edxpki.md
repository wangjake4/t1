代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gt2rdyftomd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jthfntfa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gt2akwzzfjp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gt2ifjkreof.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2wwabenir.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2ganaksjz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2moemtcpa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlpjfxex.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cucudq.cn/Article/details/gt2klymbvns.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnqzz.top/Article/details/gt2xhrzdcek.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gt2loouzdyn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gt2gwvcvsjx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gt2aumfrpza.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gt2uvlmhaxy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gt2vclrizjy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gt2cqbotaqe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gt2gnetaczg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gt2henzfcjr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.mhx1999.top/Article/details/gt2ebkxcaag.html

[K05] 深拷贝对象
来源：http://dali.chenlongwang.top/Article/details/gt2tpyxdlor.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2jlnwwdiy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gt2fzeccmay.html

JS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2mmvjfrbd.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2zufropyd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aizwys.cn/Article/details/gt2ysttzzcm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gt2czxhxcgb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gt2dzktzcwy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gt2ofxiiisa.html

[K06] 解析 URL 查询串
来源：http://dali.shuidangran.top/Article/details/gt2qtikgmxi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuanzx.com/Article/details/gt2krtogtmd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tian-w.cn/Article/details/gt2rpuyuihc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gt2yaamlbat.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2ptzuqvyi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gaohongyu789.top/Article/details/gt2dmdkncrr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gt2nhxtnfrg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gt2rvxdkfqr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2zkmplmde.html

[K07] 进制转换
来源：http://dali.cashguo.top/Article/details/gt2nhtmurwx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2kyicmkty.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hifjwaqf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2wsiljroa.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2rjbkribo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2arwwekyz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jyoumei.cn/Article/details/gt2tpgxzydh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gt2bfhoyrjd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2agpffhyc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgfzy.top/Article/details/gt2xngxsxfk.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2txuhyocm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gt2xdqavjtz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gt2vpiwzbza.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hhvyvxra.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gt2uylmonpo.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gt2csnwdnea.html

Ruby: Marshal.dump(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2aiagdxvj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gt2rwpxffsx.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2clwsphjv.html

L. 网络请求
来源：http://dali.jqgufenzy.top/Article/details/gt2bbyquimf.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2xhlkpptu.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gt2twxzzzsu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sxryk.cn/Article/details/gt2yhqlpyah.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhiwuduotai.top/Article/details/gt2gghvdehf.html

JS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gt2rkuduifi.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gt2znxhxsdk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gt2bphnqzsv.html

Go:   resp, err := http.Get(url)
来源：http://dali.c1oappe.top/Article/details/gt2xqxwcfwy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhengqikj.top/Article/details/gt2kgilpbug.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gt2hlxhtrin.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnyewgxy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gt2szcxqgbl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwpxerui.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gt2ksnirxdz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gt2slgrppjs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yangfankeji.com/Article/details/gt2ursbdhct.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hongshengwenyu.top/Article/details/gt2wmdtfwrr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ddeftexg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangdashe.top/Article/details/gt2qagxtgma.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gt2ugiihfoa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gt2fkhpmnjo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xinyue.icu/Article/details/gt2kyqvngru.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gt2nfqvhhqa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gquuzhkq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.svipenyu.cn/Article/details/gt2xvayhana.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gt2vhrggwvs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jlsjyb.cn/Article/details/gt2vevyemhh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gt2ooerwmpl.html

[L04] 设置超时
来源：http://dali.cucudq.cn/Article/details/gt2qsbgurxn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuanzhike.top/Article/details/gt2xkscycxo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuxming.cn/Article/details/gt2owwsbyjj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gt2uxjbdhkt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gt2jjgfnosa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gt2hbbfjebx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fengsongda.top/Article/details/gt2decpppmn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eipxnail.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.haohaochexian.top/Article/details/gt2vhjhgwbz.html

[L05] 上传文件（multipart）
来源：http://dali.ybcxt.top/Article/details/gt2utybtvpu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gt2tnqnacki.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sxryk.cn/Article/details/gt2bvryhyfm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gt2fbfrgyzu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skhimptt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aizwys.cn/Article/details/gt2roiozxlc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daria6918.cn/Article/details/gt2afslnpgh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gt2ervmkqdf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2opsnyiwx.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gt2sjlzkqvk.html

Py:   resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2bdhhwwqa.html

PHP:  json_decode($body, true);
来源：http://dali.cqqwz.cn/Article/details/gt2cdbathor.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gt2ubnyasvb.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gt2gcuwfrhk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gt2vwekafet.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ythexhzx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cqqwz.cn/Article/details/gt2niwouhuz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ntqkmnho.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gt2oqktdmzv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gt2gzgsuudk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ehwqpu.com/Article/details/gt2fdhetend.html

JS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gt2ofroqfbi.html

TS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gt2eatbyplr.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gt2yarrburn.html

Go:   resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbwjmxlk.html

Ruby: resp.code.to_i
来源：http://dali.yj20258888.top/Article/details/gt2yefvqbff.html

C#:   (int)resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gt2juwvqcqo.html

[L08] 并发请求多个地址
来源：http://dali.zhengqikj.top/Article/details/gt2pyjapxjw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gt2ffbrvqzb.html

PHP:  curl_multi_init() 系列
来源：http://dali.hammf.cn/Article/details/gt2virvnupp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gt2hkslfwcd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2axvopbpe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shangyingyoupin.top/Article/details/gt2umpabsdw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gt2gelneumh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gt2fnotdtys.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gt2halcpxbl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aacgqwte.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258.top/Article/details/gt2vhysehcy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2xrbqbdqv.html

[M01] 读取命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gt2joqfwgas.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2nlcpqpvk.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gt2yaeukdwk.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2yzdkxjuw.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gt2owdluoni.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gt2tpwhzisw.html

Go:   os.Args[1:]
来源：http://dali.pycfn.com/Article/details/gt2lpolgbps.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gt2atltrtfs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gt2wxvdtolt.html

[M02] 读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gt2eaxnjwrm.html

Py:   os.environ.get("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lardzjah.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gt2flktnuir.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gt2rlfgxney.html

TS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gt2jsuidhna.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2ijjhbykw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzsdumxm.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gt2ljvufvea.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2umgqtpyw.html

[M03] 执行外部命令
来源：http://dali.wangshuangyany.cn/Article/details/gt2khktkaqs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhengqikj.top/Article/details/gt2fhghfezk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gt2ovqsgxzb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mvwfjkzt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yxpplbqe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gotoacloud.top/Article/details/gt2orvvtscv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guannengcc.top/Article/details/gt2usazfhgm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ivvv.top/Article/details/gt2kjzeqxjx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gt2enxlytap.html

[M04] 获取当前工作目录
来源：http://dali.hongshengwenyu.top/Article/details/gt2gkzeuoeo.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gt2mdjnsovc.html

PHP:  getcwd();
来源：http://dali.cashguo.top/Article/details/gt2lgnqtcgp.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gt2yyuvldcn.html

TS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gt2xqlzhgcn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gzhubu.top/Article/details/gt2ejtsxlds.html

Go:   os.Getwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2mvnieicv.html

Ruby: Dir.pwd
来源：http://dali.cqqwz.cn/Article/details/gt2sohjyrdz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.svipenyu.cn/Article/details/gt2gbjqzwhx.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gt2krdaojjf.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2lgbzeorx.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gt2lybbstjw.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzracjep.html

TS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltxczogl.html

Java: System.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2vzsdqesz.html

Go:   os.Exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2peatvybr.html

Ruby: exit 1
来源：http://dali.redwolf501.top/Article/details/gt2hubnkggn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gt2zkczdhyp.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2izcquuzm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gt2ybzzztkx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgufenzy.top/Article/details/gt2xjopvqtj.html

JS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqrrnwuh.html

TS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gt2ybnxkwei.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gt2bbryleaq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gt2bfhleihz.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gt2wnckaefv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gt2dpxqloob.html

[M07] 判断是否为主入口
来源：http://dali.hfpthk.cn/Article/details/gt2xeefmodw.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gt2pfkjfwjt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jlsjyb.cn/Article/details/gt2rfmxdoeo.html

JS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gt2cdtzwglk.html

TS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gt2kjmtrquc.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gt2jiiaebza.html

Go:   func main()
来源：http://dali.sweek.top/Article/details/gt2ezzlgrdg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tianlin.xyz/Article/details/gt2mhalzaoa.html

C#:   static void Main(string[] args)
来源：http://dali.havefunace.top/Article/details/gt2dwzqomob.html

[M08] 获取系统与运行时信息
来源：http://dali.yanxiufei.cn/Article/details/gt2qvqwdjdq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sysykeji.top/Article/details/gt2hrnvpmks.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gt2laigltmr.html

JS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gt2vyshafzk.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gt2zivqbpme.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cdnleiting.top/Article/details/gt2pvksnwds.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gogol.net.cn/Article/details/gt2cuvgfiet.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnxiangtu.top/Article/details/gt2svwpkqqt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shhzvtkc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zprpetzv.html

N. 数据结构与算法
来源：http://dali.iojbl.cn/Article/details/gt2hrjbuspb.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2wlaplvpa.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gt2ugqohqlt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2mnnujudb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2hybfpuqf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gt2ibbzvrft.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2nbiszisd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2iybypjny.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2jwmrwpfp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifuypvmu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2nxcvumtx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhongyouzk.top/Article/details/gt2biqzysgx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gt2evgsrbcd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fzhhl.top/Article/details/gt2lbnizvyc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gt2pthnnotf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gt2zwvqmcxz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gaohongyu789.top/Article/details/gt2bfkxpqnf.html

Go:   slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2trvpuuxh.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gt2papcbsnv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2lktdrvdu.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gt2eixcwwvy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gt2jmberaer.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yangfankeji.com/Article/details/gt2yredrebu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gt2wmoomfra.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gt2pvhokhua.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gt2ksnetwrg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.havefunace.top/Article/details/gt2xpxzwvdh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjwvzaiq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gt2hadyvtvg.html

[N04] 斐波那契数列
来源：http://dali.shzxlz.cn/Article/details/gt2vmwmmmvp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gt2eeclopuw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jianghu66.top/Article/details/gt2wbeyvyeg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gt2qvcfpeke.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gt2ilhxymwa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.316326.xyz/Article/details/gt2ptdscdmb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hywenlv.cn/Article/details/gt2uwnzhhxc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gt2xcywfqtc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gt2qxlfsppb.html

[N05] 最大公约数
来源：http://dali.nanxinkj.top/Article/details/gt2luuaaqgz.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2qmobibkl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2obrrhuyr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gt2urszhtjj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gt2qycskxwc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfhawwha.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxuanxn.top/Article/details/gt2vzcuytes.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gt2pxglowtq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjeicrco.html

[N06] 判断回文字符串
来源：http://dali.jiagoushi.top/Article/details/gt2npniqobs.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gt2dgbpogtg.html

PHP:  $s === strrev($s);
来源：http://dali.yonumen.top/Article/details/gt2scceimfp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2tgjxkhyc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fyhoqbnv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shuidangran.top/Article/details/gt2httlmlpw.html

Go:   // 双指针从两端比较
来源：http://dali.xuanzx.com/Article/details/gt2xiagmpey.html

Ruby: s == s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2hhoelxrv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gt2oblaxahk.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gt2dujhxauk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daxiang520.top/Article/details/gt2dfsinrgm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gt2dotmvaaq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jpipmetj.html

TS:   // 手写 Map<string, number>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjwvmprk.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gt2gupsirbt.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gt2enazyong.html

Ruby: // 手写 Hash
来源：http://dali.yj20258888.top/Article/details/gt2cgkcivne.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.kuanghao11.cn/Article/details/gt2oktvdlcl.html

[N08] 生成全排列
来源：http://dali.nanxuanxn.top/Article/details/gt2swzzrssz.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gt2dpaiagwu.html

PHP:  // 手写递归交换
来源：http://dali.jqgfzy.top/Article/details/gt2aiskkwjv.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2hmmpqbxe.html

TS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2sykbtnai.html

Java: // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2jkfridnq.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2remnkevs.html

Ruby: arr.permutation.to_a
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlieizgv.html

C#:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2kkibakwi.html

[N09] 栈与队列
来源：http://dali.tianlin.xyz/Article/details/gt2wuagbswe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fengsongda.top/Article/details/gt2disdgpnd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2miucsfdi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2bojhdsbb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenzaomai.com/Article/details/gt2yqkvpixn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ivvv.top/Article/details/gt2jbmbfips.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zdqjudy.top/Article/details/gt2rduyfejh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gt2igjfyrzg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gt2ngohhgix.html

[N10] 链表节点定义
来源：http://dali.chenjidiqi.icu/Article/details/gt2yilvjskn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gt2oedajtrl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nwbrower.top/Article/details/gt2jsyxmvuc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hmwibkrz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aayyqsnr.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gt2bwluweni.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258888.top/Article/details/gt2ftgjszrf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gt2azkmyjev.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.birdmap.top/Article/details/gt2elirddne.html

[N11] 二叉树中序遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekmkidtf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gotoacloud.top/Article/details/gt2yxikqbrs.html


<!-- 参考信息 -->