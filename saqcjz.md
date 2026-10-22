代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigufen.top/Article/details/gt2qzrndmbv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guowangkeji.top/Article/details/gt2yyvfmfiq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gt2avrnwqpr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2vnovobmq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gt2owfxkrca.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gt2zrbsgbuc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2gnvzufas.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2stgzacsg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gt2anpjjnxv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gt2okulazll.html

[K04] 读取 JSON 文件
来源：http://dali.c1oappe.top/Article/details/gt2aisaeulo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmhgcrmg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuxming.cn/Article/details/gt2gobwwreu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gt2xhshbenl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gt2umatpotx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2otiyggar.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gt2iiorrmfg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gt2jdgtgfjt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258.top/Article/details/gt2qsskuqni.html

[K05] 深拷贝对象
来源：http://dali.daxiang520.top/Article/details/gt2wderxcxp.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gt2oufknalu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qincjwbt.html

JS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gt2ukjmhtkr.html

TS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gt2wradlbvh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gaohongyu789.top/Article/details/gt2cirtwrvt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ypchuihk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gt2mjqlasek.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gt2obetzmpu.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwiwalav.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gt2omoebvrt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hfpthk.cn/Article/details/gt2jvtvvzmp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gt2argrsuuz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gt2lqfvoilu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ydzc1.top/Article/details/gt2nkmahtvx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gt2iiiyccxf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2ycldwaem.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gt2lsxsrmgf.html

[K07] 进制转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhvxlhif.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2rncdnrqi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.vqdsnc.cn/Article/details/gt2vyrqeehd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2pwicgpsp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2rdxdjcsr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2yvdifczi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gogol.net.cn/Article/details/gt2exhnbpil.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj202588.top/Article/details/gt2atphtojd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2vyfnrykp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlluukhp.html

Py:   pickle.dumps(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2rxvsjuls.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gt2pdspzycl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gt2mizwjwyz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gt2wuwjeefo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gt2cnnaqejc.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gt2eluuvrti.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gt2ylkalazf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gt2obcdkcbp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2xcjcclqr.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gt2hjzpdrcr.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2azaeonue.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gt2rbdqueqi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yonumen.top/Article/details/gt2qredexsl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jianghu66.top/Article/details/gt2vqakeglf.html

JS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gt2upqzcgrs.html

TS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2svmcgnsn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gt2xckfxwvm.html

Go:   resp, err := http.Get(url)
来源：http://dali.aibaodan.cn/Article/details/gt2beuwdwfg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydiuuxji.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hywenlv.cn/Article/details/gt2wnrfvmpz.html

[L02] 发送 POST JSON
来源：http://dali.shuidangran.top/Article/details/gt2azhykric.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gt2xybtvdck.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ydzc1.top/Article/details/gt2qwguddxb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gt2hvlunkxe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gt2fyzpaaqa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2osfpvaxe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jianghu66.top/Article/details/gt2oiiirisf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenzaomai.com/Article/details/gt2unhxbdkr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2zugtllpn.html

[L03] 设置自定义请求头
来源：http://dali.jinqigufen.top/Article/details/gt2mxeyflmp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hammf.cn/Article/details/gt2sabjijdq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daxiang520.top/Article/details/gt2mnpnjgtq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gt2rcilyfvh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gt2klwfuwgy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangdashe.top/Article/details/gt2mebwjswj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gt2vgrslvbe.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.birdmap.top/Article/details/gt2ajeufeed.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gt2ccnzfdaz.html

[L04] 设置超时
来源：http://dali.fengsongda.top/Article/details/gt2zinzcowu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fzhhl.top/Article/details/gt2nurvhonb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gt2warunstn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gt2dmkhablc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gt2mumvueyx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuanzx.com/Article/details/gt2hpqctpvs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.birdmap.top/Article/details/gt2wxusbhxw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gt2ixbdoxbu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gt2smcolxtc.html

[L05] 上传文件（multipart）
来源：http://dali.aibaodan.cn/Article/details/gt2qjyidbda.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sweek.top/Article/details/gt2pyryykaf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yongpay.top/Article/details/gt2jbnxrpis.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gt2jvagecxf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gt2qetdzofv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jebklprf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gt2sbvbtukt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ydzc1.top/Article/details/gt2bjgahrhu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2xsxxufdp.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gt2lvvwlwdx.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gt2qzxljtci.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zamvxtpa.html

JS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gt2kyktsidr.html

TS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkwdmavn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypypazva.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qllsgtmg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gt2eqzcsmja.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daria6918.cn/Article/details/gt2wvgvjapv.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gt2wquajcrb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfbfvyyn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jyoumei.cn/Article/details/gt2faspsmqs.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gt2dozmlflb.html

TS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gt2umypotgg.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gt2iekvudvu.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gt2veundscc.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gt2ncxwzsqw.html

C#:   (int)resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gt2fjudmgge.html

[L08] 并发请求多个地址
来源：http://dali.daxiang520.top/Article/details/gt2zgmzuync.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gt2pchaynoq.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigfzy.top/Article/details/gt2uxhwvlam.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gt2ndgvpqyi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brwxucga.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxuanxn.top/Article/details/gt2ghhkchse.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dianchejie.cn/Article/details/gt2vlpnmacr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gt2xdcybtco.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2fhedpsys.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2zenhqbjc.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gt2vuzsylqe.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ozrfpwfa.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gt2hemcqznz.html

Py:   sys.argv[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2aohcyzlj.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gt2hpvhzgkc.html

JS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gt2ihrcpkxt.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gt2pdpvzicq.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gt2swpwshcs.html

Go:   os.Args[1:]
来源：http://dali.yuanzhike.top/Article/details/gt2puiazmyh.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gt2wgqrdlqk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pycfn.com/Article/details/gt2rjudljql.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gt2xgsitbro.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gt2pjvtresu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gt2bnrnkjwj.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gt2aavmfssq.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gt2wtvhlzvr.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2nsdujzlq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2cdyoegwi.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gt2adfohaqf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2rtzparbd.html

[M03] 执行外部命令
来源：http://dali.wangshuangyany.cn/Article/details/gt2fulcknag.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gt2ldqefhmh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gt2mcnkhuxz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gt2vxalaecx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2kcczedag.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daria6918.cn/Article/details/gt2kmgvsywi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gt2uzqnqpqs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gt2ylerwbsn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigfzy.top/Article/details/gt2tyfjlnor.html

[M04] 获取当前工作目录
来源：http://dali.hnqzz.top/Article/details/gt2gqjovwkp.html

Py:   os.getcwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2wyorpoax.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gt2eeyxctvj.html

JS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2cxiupvxb.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gt2nzzfthok.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxuanxn.top/Article/details/gt2znyhgtxr.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gt2idjlercn.html

Ruby: Dir.pwd
来源：http://dali.svipenyu.cn/Article/details/gt2egewtgxo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xinyue.icu/Article/details/gt2tddrebfj.html

[M05] 设置退出码
来源：http://dali.mhx1999.top/Article/details/gt2cwrztsxt.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2jawnyjia.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gt2nozcrxrw.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2iniqmnmh.html

TS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2lnnngiam.html

Java: System.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2olpnwqbd.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ogfrqfay.html

Ruby: exit 1
来源：http://dali.tian-w.cn/Article/details/gt2mcjhruch.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangshuangyany.cn/Article/details/gt2hujtwqum.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdyuoooh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gt2fhepzfmf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hfpthk.cn/Article/details/gt2ipugnkqe.html

JS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gt2mxpgogrf.html

TS:   console.error("err")
来源：http://dali.smart0.xyz/Article/details/gt2yoeaugsi.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebiyqdag.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gt2dsfoztek.html

Ruby: warn "err"
来源：http://dali.yuanzhike.top/Article/details/gt2encnotjb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gt2xvrhvryr.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gt2ouwpbtsx.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gt2guvkewiz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jyoumei.cn/Article/details/gt2pfwjuvss.html

JS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gt2lsoyemfo.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gt2zkkmdfgj.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gt2wagyvjsb.html

Go:   func main()
来源：http://dali.shuidangran.top/Article/details/gt2vicawlxx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.snrcjt.cn/Article/details/gt2raeuompp.html

C#:   static void Main(string[] args)
来源：http://dali.zdqjudy.top/Article/details/gt2tjvkjpcl.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gt2boodaaoy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenjidiqi.icu/Article/details/gt2blkcjinw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gt2ixvfnxbf.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gt2dfkkqzjn.html

TS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gt2zmuhjfpw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gt2doigoozf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhoulong.xyz/Article/details/gt2ldzsyuju.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.iojbl.cn/Article/details/gt2quiblnmc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhixingplan.top/Article/details/gt2hviiwvhz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2swjtosad.html

N. 数据结构与算法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbefcdoy.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2korcoxbd.html

[N01] 二分查找（有序数组）
来源：http://dali.chenzaomai.com/Article/details/gt2fsbbggdw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2xiokhvlu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2anybstyx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gt2opsdzxrz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gt2lpxksdov.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2rwgoxzwi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2nmqqqard.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aibaodan.cn/Article/details/gt2toiqffga.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2jxiqfxie.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xziqi.cn/Article/details/gt2ybwgnycz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gt2nhlwcwxo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tanke756.top/Article/details/gt2yozuqrvh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gt2mzyylzxe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gt2vidqwvud.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gt2icuzlqab.html

Go:   slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2plbiukax.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gt2ccceqttz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.mhx1999.top/Article/details/gt2iynjbjmi.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gt2daxmbmwa.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenzaomai.com/Article/details/gt2bwrpwylw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ybcxt.top/Article/details/gt2lkhaevin.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gt2fslvzhhx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gt2gmebzfyy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gt2kguciyoz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuetiantiany.cn/Article/details/gt2ykccqvqs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gt2aecefode.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pycfn.com/Article/details/gt2rtvkqswf.html

[N04] 斐波那契数列
来源：http://dali.snrcjt.cn/Article/details/gt2xfpvdsea.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2dylzyudm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2oekanqsd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gt2qjzvqbnw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gt2mkptcwle.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gt2tnjzgyaf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgufenzy.top/Article/details/gt2njjocsxk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gt2sknnjdyr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2rxlofhvm.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gt2jrtgjyba.html

Py:   math.gcd(a, b)
来源：http://dali.gogol.net.cn/Article/details/gt2wlbajamj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gzhubu.top/Article/details/gt2eaknmwmp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258888.top/Article/details/gt2vzogknqv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gt2nfdnfiax.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.snrcjt.cn/Article/details/gt2unwycxto.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ivvv.top/Article/details/gt2rndsqqjw.html

Ruby: a.gcd(b)
来源：http://dali.zhixingplan.top/Article/details/gt2zsbmuyib.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gt2jyciuisb.html

[N06] 判断回文字符串
来源：http://dali.hysaishi.cn/Article/details/gt2vabljayj.html

Py:   s == s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gtyocjfx.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gt2dgqjgqft.html

JS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2ggumgpnd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2aqkrhsfh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ivvv.top/Article/details/gt2dxozoicu.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gt2wmhsetjn.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2rqpsuhvw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gt2opbnwmrv.html

[N07] 两数之和（返回下标）
来源：http://dali.smart0.xyz/Article/details/gt2otsamltq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sxryk.cn/Article/details/gt2agbuvwjw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cdnleiting.top/Article/details/gt2bcnctepi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hammf.cn/Article/details/gt2jvhedeqk.html

TS:   // 手写 Map<string, number>
来源：http://dali.daria6918.cn/Article/details/gt2pebkdrjh.html

Java: // 手写 HashMap
来源：http://dali.tian-w.cn/Article/details/gt2bkngoggx.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gt2emvgcdyl.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gt2zulyppml.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxuanxn.top/Article/details/gt2gdkcmpjp.html

[N08] 生成全排列
来源：http://dali.xziqi.cn/Article/details/gt2wgmknkol.html

Py:   itertools.permutations(arr)
来源：http://dali.havefunace.top/Article/details/gt2grkyvaut.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gt2yblkksox.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2hlubbvui.html

TS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2bvtunwon.html

Java: // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2ywvxnjfw.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2yanduvvi.html

Ruby: arr.permutation.to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2emgoywit.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2jyskzqca.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gt2lephhtre.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2uyklfvuj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gt2cstriklj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhganoeu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guannengcc.top/Article/details/gt2afxxgxqd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yonumen.top/Article/details/gt2amexnicg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangdashe.top/Article/details/gt2kcigawvy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gt2fmechism.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenlongwang.top/Article/details/gt2brvxmrzm.html

[N10] 链表节点定义
来源：http://dali.jqgufenzy.top/Article/details/gt2dvxvskhn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuanzhike.top/Article/details/gt2mnbiospl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tian-w.cn/Article/details/gt2vjzcqwsh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gt2igoisnpt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nwbrower.top/Article/details/gt2tdzgczyr.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gt2hmykqlur.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigufen.top/Article/details/gt2kjxbhkxx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hywenlv.cn/Article/details/gt2jbgkzyud.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigufen.top/Article/details/gt2atgtirkg.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gt2kethhiuu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jlsjyb.cn/Article/details/gt2spswprmp.html


<!-- 参考信息 -->