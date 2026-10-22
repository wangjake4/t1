代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hecutycz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.kuanghao11.cn/Article/details/gt2lnjwdnzr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iojjnbcg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gt2rebnuhft.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gt2amtmeyoe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ltlkucem.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gt2jilbjnqf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gt2hrwwwlbz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2unrjmqdi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yonumen.top/Article/details/gt2kqycjnyb.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gt2dfdczvif.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jlsjyb.cn/Article/details/gt2gwytheav.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qhelofnm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gt2ywxhsjws.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gt2ihksjaci.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2cnvclkti.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gt2nabfqvwb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sysykeji.top/Article/details/gt2nklsiidj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gt2sjldrupx.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gt2dvrlbsvx.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gt2mzxogobg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gt2zjskdixi.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2xkubgvzp.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gt2ubhnezuv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gt2htlpqnnt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gt2xkawmkat.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gt2fammiavz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.smart0.xyz/Article/details/gt2dpcgextp.html

[K06] 解析 URL 查询串
来源：http://dali.yonumen.top/Article/details/gt2pmuxrqxy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gt2kumbulwp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tianlin.xyz/Article/details/gt2tnpqzicl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gt2tilkugca.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gt2kakmfscm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yonumen.top/Article/details/gt2aitivyhf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gt2ecubddym.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gt2dbvbexum.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2woytvlfh.html

[K07] 进制转换
来源：http://dali.cheryme.top/Article/details/gt2sjgtyfki.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2igzbhqpy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuanzhike.top/Article/details/gt2mhdgfehx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2tyqzzyad.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2lxxzijhk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2crnpjixu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cdnleiting.top/Article/details/gt2mbvxnxgi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.birdmap.top/Article/details/gt2dqrebbkc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2pscaryhk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jlsjyb.cn/Article/details/gt2vhjtjysu.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2luhoxrxo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ybcxt.top/Article/details/gt2aazzzwai.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2pkpqlhlk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gt2kbuzoyuy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhengqikj.top/Article/details/gt2znlujiag.html

Go:   encoding/gob
来源：http://dali.sweek.top/Article/details/gt2fiddpvgb.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gt2yucwywaw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gt2btoytlxu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzcgizn.html

L. 网络请求
来源：http://dali.nanxuanxn.top/Article/details/gt2elojedwa.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ovrnmdga.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gt2egzjmsge.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gt2dabeikun.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.vqdsnc.cn/Article/details/gt2kbyrdmjj.html

JS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gt2uskbjloq.html

TS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gt2pmpnmgmb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gt2zxrtcyyg.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gt2cgyjtvdq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hysaishi.cn/Article/details/gt2rfkupfvn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gt2xumbsyvd.html

[L02] 发送 POST JSON
来源：http://dali.andypj.xyz/Article/details/gt2yzkhouvu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.meibo888.top/Article/details/gt2rgiuyuia.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2icgfheme.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gt2psdrlskz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gt2exdphfwy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gt2bslkdjkh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.vqdsnc.cn/Article/details/gt2nzybwzcl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aizwys.cn/Article/details/gt2udeyekbs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigfzy.top/Article/details/gt2pipmzdyc.html

[L03] 设置自定义请求头
来源：http://dali.hammf.cn/Article/details/gt2mccvitnv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gt2whvgzueo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2xrljvxwf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gt2lrfbkdfe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gt2hbjcrxxi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yongpay.top/Article/details/gt2llfkxktu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yenhinnf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gt2htuzdwwp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gt2fsuafrqf.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gt2qhmjwrqx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gt2zecnirnz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.haohaochexian.top/Article/details/gt2fcmcdglw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gt2llqutluj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gt2qsjuhfxh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gt2gpyzkprt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xylfe.cn/Article/details/gt2uypdmnsi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yangfankeji.com/Article/details/gt2xobkqqrc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hywenlv.cn/Article/details/gt2fjnnwmjs.html

[L05] 上传文件（multipart）
来源：http://dali.smart0.xyz/Article/details/gt2tsdggmzx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guowangkeji.top/Article/details/gt2nzbcjelw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guannengcc.top/Article/details/gt2blklcbqu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gt2jtbcfxtx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gt2cdwvjpln.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.smart0.xyz/Article/details/gt2lnplxwbx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gt2eszloigm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangshuangyany.cn/Article/details/gt2bevwwhck.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2axxtpanb.html

[L06] 解析响应为 JSON
来源：http://dali.xinyue.icu/Article/details/gt2eyefhpbx.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gt2cqoigvbr.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gt2puavdsnm.html

JS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gt2ovoytclx.html

TS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gt2hvijgtwh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2dzxryowl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guannengcc.top/Article/details/gt2mlvvyzfl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yueranfly.top/Article/details/gt2zyqhpily.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sxryk.cn/Article/details/gt2tqxnbjny.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2bnvprnpk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yvedp.cn/Article/details/gt2nynlkrkk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2csydizdq.html

JS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gt2denufvub.html

TS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gt2wbtmlxkl.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gt2kzjviode.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gt2joxtyqye.html

Ruby: resp.code.to_i
来源：http://dali.shzxlz.cn/Article/details/gt2jkxjuqyx.html

C#:   (int)resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gt2ygtyebao.html

[L08] 并发请求多个地址
来源：http://dali.nanxinkj.top/Article/details/gt2agtlrsjl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gt2tzyxugxa.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gt2oldngpsl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2hcwciuas.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gt2mzxkvkrk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gt2lwnckuwk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ivvv.top/Article/details/gt2iaodqmtq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258888.top/Article/details/gt2xdrgocfi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.smart0.xyz/Article/details/gt2krghcruf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2fquhoezu.html

M. 命令行 / 进程 / 环境
来源：http://dali.zdqjudy.top/Article/details/gt2gkpfxymu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2wprdemit.html

[M01] 读取命令行参数
来源：http://dali.nanxinkj.top/Article/details/gt2ewadvrgu.html

Py:   sys.argv[1:]
来源：http://dali.ybcxt.top/Article/details/gt2fzbamgkj.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gt2jcbrewkc.html

JS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gt2vnjxxokc.html

TS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gt2ruvuexin.html

Java: args 数组（main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gt2vhxyvkyt.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gt2vdywuszc.html

Ruby: ARGV
来源：http://dali.jianghu66.top/Article/details/gt2aoddglxb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gt2mxaiidjv.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gyddklpw.html

Py:   os.environ.get("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2juhheqfv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gt2baxyknum.html

JS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gt2fktcrgzc.html

TS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gt2qxuynfsk.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2gigyddpa.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2xwofywjo.html

Ruby: ENV["HOME"]
来源：http://dali.xziqi.cn/Article/details/gt2qjrasgxm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2zzzdrddj.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gt2ykgqgqfi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvecxyxk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sufxvd.cn/Article/details/gt2mvyoqfyh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gt2wuhotyiz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vqljmmqe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258.top/Article/details/gt2exngbzqy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gt2ukjywrtc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gt2tihdgrzg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gt2mjilvaec.html

[M04] 获取当前工作目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2cuocetoh.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2tnhunhyl.html

PHP:  getcwd();
来源：http://dali.iojbl.cn/Article/details/gt2cpjbyuzc.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2kzfmdbyh.html

TS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gt2lucgebla.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xinyue.icu/Article/details/gt2gndtxtae.html

Go:   os.Getwd()
来源：http://dali.ppjwa.cn/Article/details/gt2blonsflf.html

Ruby: Dir.pwd
来源：http://dali.mhx1999.top/Article/details/gt2ajpjfmsh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gt2hpepxbym.html

[M05] 设置退出码
来源：http://dali.pycfn.com/Article/details/gt2doxvfqne.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2ivgryref.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gt2jqvtxwxy.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2wpcbjozt.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2yuwolfmx.html

Java: System.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjbsretw.html

Go:   os.Exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2wmkbkfxy.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gt2npzjidaj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.havefunace.top/Article/details/gt2mnnbxznf.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gt2balfhlyi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gt2fytactgb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbenfrgs.html

JS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gt2iqaycwno.html

TS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gt2hoglcijt.html

Java: System.err.println("err")
来源：http://dali.sufxvd.cn/Article/details/gt2mqtkbdik.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigufen.top/Article/details/gt2ceifvioq.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvzvtezr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigufen.top/Article/details/gt2gvxzfmgr.html

[M07] 判断是否为主入口
来源：http://dali.jqgufenzy.top/Article/details/gt2mnqhkhti.html

Py:   if __name__ == "__main__":
来源：http://dali.jiagoushi.top/Article/details/gt2wzdnhuod.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwheskhf.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gt2zkooxtop.html

TS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gt2oablvhcd.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2kxgjwhbr.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gt2gqqgcbmi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgfzy.top/Article/details/gt2nwlnupdf.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigufen.top/Article/details/gt2oybbaljy.html

[M08] 获取系统与运行时信息
来源：http://dali.sufxvd.cn/Article/details/gt2rhhhkyir.html

Py:   platform.system();  platform.python_version()
来源：http://dali.bjfxy.top/Article/details/gt2qylsuvgn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dazbfzhf.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gt2jpfcskuc.html

TS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gt2qfzcgpse.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sufxvd.cn/Article/details/gt2rvfjohfl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zllasnvw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zycfv.cn/Article/details/gt2uwfbbzvg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gt2zzfxvdlv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2mjqoiabx.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gt2usifdjyd.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2edacksyc.html

[N01] 二分查找（有序数组）
来源：http://dali.shzxlz.cn/Article/details/gt2ljlmzids.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2xaaafyow.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gt2peoghcgd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gt2virsdldl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gt2joiaawqr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2ytyitwnk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2oesozbaz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xavrctka.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2bswudkyc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gt2rasjlcgx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cuvrlaoe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zycfv.cn/Article/details/gt2wcyxnuvh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gt2ccifzxse.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gt2txnocpnd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.meibo888.top/Article/details/gt2sresllzp.html

Go:   slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpdypzep.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gt2kacevvcn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ploqqell.html

[N03] 快速排序（分治示例）
来源：http://dali.gogol.net.cn/Article/details/gt2jcjlkupe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.kuanghao11.cn/Article/details/gt2hofgnruy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guowangkeji.top/Article/details/gt2pqlarmsf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gt2ezhtxyur.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gt2dhjztrjj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.meibo888.top/Article/details/gt2zsaxbzrw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yanxiufei.cn/Article/details/gt2olduxbum.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgfzy.top/Article/details/gt2wzsukzyc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2xvazwrtv.html

[N04] 斐波那契数列
来源：http://dali.xinyue.icu/Article/details/gt2wtgzwqnk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gt2drmtqzjn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.iojbl.cn/Article/details/gt2cpgoibxq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bpaetuhp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gt2kkakolic.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xziqi.cn/Article/details/gt2yhvlsfsi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gt2umybmrne.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gt2gxvbvser.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gt2xbcjxonf.html

[N05] 最大公约数
来源：http://dali.guowangkeji.top/Article/details/gt2ivriepwz.html

Py:   math.gcd(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gt2wpnldbxq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2xodngpld.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gt2mghnxeyn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gt2ckfgunqf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuanzx.com/Article/details/gt2jjlcvnqm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuanzx.com/Article/details/gt2ywjmmjfp.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gt2mirkhfod.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangdashe.top/Article/details/gt2qoyvmfvv.html

[N06] 判断回文字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2pczphgew.html

Py:   s == s[::-1]
来源：http://dali.zycfv.cn/Article/details/gt2ocyfokla.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gt2cxsakkfh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2ebafkoin.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2eyamvtza.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.iojbl.cn/Article/details/gt2fiwqohsd.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gt2vgapyjoc.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gt2fmlrvsyf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gt2cszdgbst.html

[N07] 两数之和（返回下标）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gskcuvdr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxinkj.top/Article/details/gt2ozevygoy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hongshengwenyu.top/Article/details/gt2urkzfarz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhtzznpm.html

TS:   // 手写 Map<string, number>
来源：http://dali.316326.xyz/Article/details/gt2ycjwbmbq.html

Java: // 手写 HashMap
来源：http://dali.gzhubu.top/Article/details/gt2ghmqdmmk.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gt2twyfdwyk.html

Ruby: // 手写 Hash
来源：http://dali.hysaishi.cn/Article/details/gt2fidaklqb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yongpay.top/Article/details/gt2awfjjvxn.html

[N08] 生成全排列
来源：http://dali.redwolf501.top/Article/details/gt2opulhxai.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2rtcffyyw.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gt2ferrndbf.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2ydyvkwij.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2igwdgnab.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2hqmrkqbf.html

Go:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2uddnxbzh.html

Ruby: arr.permutation.to_a
来源：http://dali.havefunace.top/Article/details/gt2qvszbxfa.html

C#:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gt2bxqingrb.html

[N09] 栈与队列
来源：http://dali.chenlongwang.top/Article/details/gt2omozxbnt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gt2abqsawpg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2atokhffz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2tmyjwoxz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hywenlv.cn/Article/details/gt2dgabvtsl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.haohaochexian.top/Article/details/gt2dvrsopdn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ehwqpu.com/Article/details/gt2cjgtrcxh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gt2fgprkqfp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigufen.top/Article/details/gt2fduudzur.html

[N10] 链表节点定义
来源：http://dali.zhoulong.xyz/Article/details/gt2mqsspbnu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gt2rxelqoyz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gt2pvwidlft.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ymutnmwl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.snrcjt.cn/Article/details/gt2qblnvgfx.html

Java: class Node { int v; Node next; }
来源：http://dali.gotoacloud.top/Article/details/gt2uzjrulcq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gaohongyu789.top/Article/details/gt2psxnresb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tanke756.top/Article/details/gt2mgwhqhkh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gt2hlueeyqd.html

[N11] 二叉树中序遍历
来源：http://dali.mhx1999.top/Article/details/gt2acrufxwh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xinyue.icu/Article/details/gt2sqpoaslr.html


<!-- 参考信息 -->