代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtwvqfguom.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tanke756.top/Article/details/gtiruxycsq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtefjctqlz.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtlcwfdbaf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shzxlz.cn/Article/details/gtteinjpxp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hammf.cn/Article/details/gtimayohcm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtielywspt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtamwinmav.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtjlexgyqd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtdhgsztbt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangdashe.top/Article/details/gtwlpsmkcf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gtlqcodfgy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gtxxxyklwk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gtekambbbq.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gtzybqssvd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzalfxqto.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgfzy.top/Article/details/gtmghcjctq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtqnenaeyh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtsvmavykx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtgeekubuo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gtltvxfgox.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gtssawumsi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtmlkrkaly.html

[K05] 深拷贝对象
来源：http://dali.jqgufenzy.top/Article/details/gtakujypks.html

Py:   copy.deepcopy(obj)
来源：http://dali.sysykeji.top/Article/details/gtkznoyrwi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gtefeiamrb.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtiucusidd.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtfzqpgzfc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrrroqpv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xinyue.icu/Article/details/gtljmkibdm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xinyue.icu/Article/details/gtpwqourrt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yueranfly.top/Article/details/gtzptnzvgz.html

[K06] 解析 URL 查询串
来源：http://dali.ydzc1.top/Article/details/gtaokzwzoh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtmxcxapsp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aibaodan.cn/Article/details/gtkjxejjhk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtgejcobor.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtwvxdyuin.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zdqjudy.top/Article/details/gtvylrkwrh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtgphybdoa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtwvibyoei.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtziwvwnwq.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gttvlfhzlf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gteyvwlhhe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gaohongyu789.top/Article/details/gtoccsdipn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtnkznawmd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtwpckjwqd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtqrdtvpfc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gthhfhigsn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.snrcjt.cn/Article/details/gtwhefiyzw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtshujvjci.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigfzy.top/Article/details/gtveemyxtp.html

Py:   pickle.dumps(obj)
来源：http://dali.bjfxy.top/Article/details/gtbjctgrho.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigufen.top/Article/details/gtrbmfhlwx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtiswiekfe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gttrurpwzx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.havefunace.top/Article/details/gtblfcahul.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gtmpfunywf.html

Ruby: Marshal.dump(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtyxmfluzh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtnrgevzoy.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtqhjngjfm.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gtblprjgby.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gthypysrke.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvmbylyf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gtoeyrmjcp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gtustmrwhn.html

JS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gtocsbaqgx.html

TS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gtlimkxypt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gtnzwvxzmp.html

Go:   resp, err := http.Get(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtakueyqzy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jiagoushi.top/Article/details/gtxbioddph.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.svipenyu.cn/Article/details/gtsqxskscx.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtthqxdjsl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtebqamnqv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.haohaochexian.top/Article/details/gtmgorfbtm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtrlszyxxw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtmnnkmsee.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zdqjudy.top/Article/details/gtjsmyfoqr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gtprfbnuem.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ydzc1.top/Article/details/gthglkakjl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gtogcmgwrf.html

[L03] 设置自定义请求头
来源：http://dali.gotoacloud.top/Article/details/gtsxtgwxhd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yvedp.cn/Article/details/gteizeansl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gtftfztpjl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gtmfmmvqbt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtweajjnmc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gtrgmszhsy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gtuqxoqxbz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tianlin.xyz/Article/details/gtdopsssnu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gtnobvruai.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gtpqyqnkdj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangdashe.top/Article/details/gtuevjsxia.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gtjdyegmjn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtoyaebzwz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtbtoeeipi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gtgzvgstug.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gthdyyurqt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gtquzfkqcy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gtirierskv.html

[L05] 上传文件（multipart）
来源：http://dali.xuanzx.com/Article/details/gtxicukqfe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shuidangran.top/Article/details/gtmfvgckzg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gtmvimtpzq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtotcbwvwk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gtmpdnjmji.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.iojbl.cn/Article/details/gtfcmhquhw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvkztqao.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnztiwgt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuanzx.com/Article/details/gtgivuokgm.html

[L06] 解析响应为 JSON
来源：http://dali.316326.xyz/Article/details/gtilfkcajt.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gtgeldzfnz.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gtqypkqoop.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtvdpfquks.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtbprrtdsb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ivvv.top/Article/details/gtdsydnzid.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gthojhszuw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gtnstuslcv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gtfopshljl.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtndmyyqkq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sysykeji.top/Article/details/gttakamhyn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gtyvryxski.html

JS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtfakdyijh.html

TS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gtjktrzmnz.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gtzcuqutwp.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gttdgcsucx.html

Ruby: resp.code.to_i
来源：http://dali.jinqigufen.top/Article/details/gtngkjgrgd.html

C#:   (int)resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gtkdgehrdu.html

[L08] 并发请求多个地址
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbcivpkc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenlongwang.top/Article/details/gtmrykbhbj.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gthidvhixh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtjtaynuwg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtaqqhldxk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj202588.top/Article/details/gtwuzokroj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gtjrmvqyjs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zdqjudy.top/Article/details/gtwfyyfajt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gtuefekeik.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtcbjsmunv.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258.top/Article/details/gtsmzhloyg.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtfmbvmfgo.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtsvhevrop.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gtujjxgwjh.html

PHP:  $argv;  $argc;
来源：http://dali.kuanghao11.cn/Article/details/gtuxaiyyht.html

JS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gtaoqmgwxc.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtsxztodun.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtdzdmgmqk.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gtcebnwfdt.html

Ruby: ARGV
来源：http://dali.fzhhl.top/Article/details/gtvqfvwdds.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtoyrudfar.html

[M02] 读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gtdmnjozdi.html

Py:   os.environ.get("HOME")
来源：http://dali.sysykeji.top/Article/details/gtzoquxbsq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gthwhohuri.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtwcnciafa.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtmwqovagi.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gthydqfpfi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtcgqwqiuh.html

Ruby: ENV["HOME"]
来源：http://dali.xylfe.cn/Article/details/gtdwukjsyc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cheryme.top/Article/details/gttdutxbpi.html

[M03] 执行外部命令
来源：http://dali.tianlin.xyz/Article/details/gttunxwqgg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtslfbwbgv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gtzkwhnspa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtonkmjxae.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtadeugzyo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gtwurvjptz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gtsbvpgolf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxinkj.top/Article/details/gtcyucttbq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gtoniehpbw.html

[M04] 获取当前工作目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrgmfuyr.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gtfkhyngxe.html

PHP:  getcwd();
来源：http://dali.316326.xyz/Article/details/gtrusrgcjv.html

JS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gtgzgtjtxj.html

TS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtauiqrxcp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sweek.top/Article/details/gtrzkqevjw.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gtfvrbgiar.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsthjbjsb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gtcjphiier.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gthscmntjl.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gttxfgyiiv.html

PHP:  exit(1);
来源：http://dali.hnqzz.top/Article/details/gtevdkjpfk.html

JS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtkmbcexzu.html

TS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtjwcswudg.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtorwjpdhk.html

Go:   os.Exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtcwiuyrti.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gtkbojpnta.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gtybuhebra.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gtzkftxnop.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gtkncbbbiv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gtxwmybtjf.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gttzgmgoji.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtqrgliilv.html

Java: System.err.println("err")
来源：http://dali.0kj1m.cn/Article/details/gtsthqukrg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gtshrjgswa.html

Ruby: warn "err"
来源：http://dali.vqdsnc.cn/Article/details/gtyogggrlq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gttytcsrvz.html

[M07] 判断是否为主入口
来源：http://dali.hywenlv.cn/Article/details/gtusxjcozr.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gthcuxvspn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gtkskbdvuf.html

JS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gtbhkbcwvp.html

TS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfnrccqq.html

Java: public static void main(String[] args)
来源：http://dali.birdmap.top/Article/details/gtapnlruwu.html

Go:   func main()
来源：http://dali.haohaochexian.top/Article/details/gtpumsynto.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hysaishi.cn/Article/details/gtpvuhbgrr.html

C#:   static void Main(string[] args)
来源：http://dali.havefunace.top/Article/details/gtdzgytbwu.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gtupihgtxj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hywenlv.cn/Article/details/gtntiofopg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigufen.top/Article/details/gtjdxyvypa.html

JS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gteofmfpeq.html

TS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtfcfegvbn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhoulong.xyz/Article/details/gtwodqgylv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fzhhl.top/Article/details/gtvszxhrlt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.snrcjt.cn/Article/details/gtzqoqupac.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhiwuduotai.top/Article/details/gtxkvphqry.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtpzbiicex.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gtqoaqdcrs.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtaomlftwy.html

[N01] 二分查找（有序数组）
来源：http://dali.hfpthk.cn/Article/details/gtovhamfcc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jianghu66.top/Article/details/gttjtnpixc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ivvv.top/Article/details/gtvmlhltzh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtcsywhbtk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtfivughlc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtdewzszub.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtupxlyuxf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gttdgbfina.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtxbozbjgl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gtpkfahola.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtwgtwhkyc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gtzpinicsc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtwqdsfquy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtrdydlpfr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ybcxt.top/Article/details/gtjpmkbjbn.html

Go:   slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtkwazbjzr.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gthtnmyxgo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gtqwzvarla.html

[N03] 快速排序（分治示例）
来源：http://dali.guannengcc.top/Article/details/gtqtfqashk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gtjhccspta.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fzhhl.top/Article/details/gtohlqthzk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gttwyigzfr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtwigjxrjo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sweek.top/Article/details/gtgiqajzcw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.havefunace.top/Article/details/gtvjunrqnb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ppjwa.cn/Article/details/gtnecaxxlq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtaycfnpal.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbebofex.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gticsxzjid.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gtqgqmbrgo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbachunpl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtoksoklzy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guannengcc.top/Article/details/gthlevydic.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.0kj1m.cn/Article/details/gtjebyglwp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gtjdmmhuep.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtjmqwvnse.html

[N05] 最大公约数
来源：http://dali.c1oappe.top/Article/details/gtwzlaubgd.html

Py:   math.gcd(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtvekhhiwz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pycfn.com/Article/details/gtmcpdoczn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gtgqjknllq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtrgcdiabl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gtstcleoue.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfeaopeu.html

Ruby: a.gcd(b)
来源：http://dali.svipenyu.cn/Article/details/gtamqiirnk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nwbrower.top/Article/details/gtxasmdtxp.html

[N06] 判断回文字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqyczjzds.html

Py:   s == s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtpdoijogy.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gtaqjbgbhd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtgwabtsyr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtzmcnjkps.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gaohongyu789.top/Article/details/gtcktferlk.html

Go:   // 双指针从两端比较
来源：http://dali.guowangkeji.top/Article/details/gtgucgubit.html

Ruby: s == s.reverse
来源：http://dali.zycfv.cn/Article/details/gtxruqusgk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gtfhaaoyhm.html

[N07] 两数之和（返回下标）
来源：http://dali.birdmap.top/Article/details/gtoqiuqfsi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jyoumei.cn/Article/details/gttjugalzz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zycfv.cn/Article/details/gtolqmsddx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shangyingyoupin.top/Article/details/gtkifzsxqj.html

TS:   // 手写 Map<string, number>
来源：http://dali.andypj.xyz/Article/details/gthveajofx.html

Java: // 手写 HashMap
来源：http://dali.xziqi.cn/Article/details/gtpdrfmjky.html

Go:   // 手写 map[int]int
来源：http://dali.tanke756.top/Article/details/gtiwrjrfob.html

Ruby: // 手写 Hash
来源：http://dali.guowangkeji.top/Article/details/gtlxpkkkij.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jiagoushi.top/Article/details/gtlebqtvcp.html

[N08] 生成全排列
来源：http://dali.hongshengwenyu.top/Article/details/gtembazsqb.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtiwucfqjm.html

PHP:  // 手写递归交换
来源：http://dali.gotoacloud.top/Article/details/gthoxltual.html

JS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtfzizbsaf.html

TS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtzdweglfi.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gttepmgcqw.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtamktwvwr.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgufenzy.top/Article/details/gtxbpsnsae.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gthqcmjnzq.html

[N09] 栈与队列
来源：http://dali.xuanzx.com/Article/details/gtkpgvquwn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gtglcbkajl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtcmtcinoi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtomtpljqn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.redwolf501.top/Article/details/gtuzmqumbf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpkpdvfc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daxiang520.top/Article/details/gtmgftalme.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtlgnrrian.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhixingplan.top/Article/details/gtpegbclfb.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gtjzsbgikr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlimwljhv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gtcwicfcva.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gtwemhhixa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gtzydcians.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gtgjqpqmin.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yanxiufei.cn/Article/details/gtoahohkqj.html


<!-- 参考信息 -->