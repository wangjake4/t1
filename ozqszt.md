代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258.top/Article/details/gtdpvypkco.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gtjuihdzvn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtziwmnpgw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtgzzxtzdf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxxnvngm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gtldcgqjdr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj202588.top/Article/details/gtgojxmyab.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gtkbndtgyw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jiagoushi.top/Article/details/gtztdlrvyo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gotoacloud.top/Article/details/gtfqzormix.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gtgkaqtala.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcmvimyt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gtzocgmrkl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtaxlbmzhx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtyviufqeh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtbnlcbdpd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjwhdlod.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtvbwwejsm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtusgrfmfc.html

[K05] 深拷贝对象
来源：http://dali.xylfe.cn/Article/details/gtuhbtuozm.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenzaomai.com/Article/details/gtrbqsaysk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gtkxxmzusw.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtjpuolqoq.html

TS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtnzvdoewa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gtakezjnde.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.snrcjt.cn/Article/details/gtjlkgdwjm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtpswxgcmb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuanzx.com/Article/details/gtzltbbfgc.html

[K06] 解析 URL 查询串
来源：http://dali.yangfankeji.com/Article/details/gtyhggxnsu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtdfpncjtw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cqqwz.cn/Article/details/gtdvthjfiy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gttsllldpt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gtjczjioey.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gtyacokafx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtlaazojyd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtgftjqzth.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtesyycjei.html

[K07] 进制转换
来源：http://dali.gzhubu.top/Article/details/gtbjjlfdmu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtgpbwfwuv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sysykeji.top/Article/details/gtmmfrbymx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtjgjdnjkc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlaaizaml.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtactqistc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiexuycbe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.meibo888.top/Article/details/gtpnhjojxq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtoyhoknuo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shzxlz.cn/Article/details/gthmzgtfvn.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gtlrkoqxcu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gtbfyvkjal.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtseellsak.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gtaymmhlom.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhengqikj.top/Article/details/gtrfqmjmjy.html

Go:   encoding/gob
来源：http://dali.yj202588.top/Article/details/gtakrdobff.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtiibogkom.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gtcsukaimn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtnlxkldeq.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gtrvwluppp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtntegakck.html

[L01] 发送 GET 请求
来源：http://dali.ehwqpu.com/Article/details/gtzybgdfiv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqttpsqy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalgcepcb.html

JS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtxradkeaq.html

TS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkupneurz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gtloyauziz.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gtpyejzqnr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.0kj1m.cn/Article/details/gtuocwwwrl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shuidangran.top/Article/details/gtswafswpp.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtevlrrlvc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtxkyzapwl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gtuffyzahn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gtfciodave.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gtedodrblm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gtnguovbao.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenjidiqi.icu/Article/details/gtyvmwudta.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jyoumei.cn/Article/details/gtczcbylby.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gteptxqldl.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gtmmdgkslf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyebpvrf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zycfv.cn/Article/details/gtgtenyzdb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gtreekphkt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtpkgvtran.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gtkwkdpqpg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gtykijtnvl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gthbyztigq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtbhpugptz.html

[L04] 设置超时
来源：http://dali.cashguo.top/Article/details/gtmhttwzqg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gtiayhfdow.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gttyedompy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtqzxiweya.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtlsdhusdl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gtfgrcilpf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shuidangran.top/Article/details/gtalikaiaf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jyoumei.cn/Article/details/gtdbzgucxf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nwbrower.top/Article/details/gtviicoflf.html

[L05] 上传文件（multipart）
来源：http://dali.cheryme.top/Article/details/gtdhlsbhhk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.kuanghao11.cn/Article/details/gtvdbyluyq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gtedoysbsh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtztajpvqt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtxgosylss.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cucudq.cn/Article/details/gtcjkrquyp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjgiehuj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.bjfxy.top/Article/details/gtgzvdpsmp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ivvv.top/Article/details/gtimstmvig.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gttmfwqubx.html

Py:   resp.json()
来源：http://dali.daria6918.cn/Article/details/gtszhcplgl.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gtazyfpecr.html

JS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gtmhxlcycb.html

TS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtgomswdlk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtqnflrmmu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gtxfoadkpb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gtilkvulsn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnqzz.top/Article/details/gtfnzykhhz.html

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtprmfwppk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gtpkmuphne.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxuanxn.top/Article/details/gtelglwgos.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtvgikmuli.html

TS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gttafioidp.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiorftthn.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtlnyjhvwb.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gtfifymgsv.html

C#:   (int)resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gttmlreqio.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gtljdkewol.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ydzc1.top/Article/details/gtjybnkcsb.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gtlmmkfbbb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtljjxwpdp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtkfkaoyfr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yangfankeji.com/Article/details/gtqfnthpwg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gtrbanckem.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gtcnwrnjel.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ehwqpu.com/Article/details/gtcflxkliw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtzgxqurni.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gtgiijoffx.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtgqwycgju.html

[M01] 读取命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtwztajtbp.html

Py:   sys.argv[1:]
来源：http://dali.nanxinkj.top/Article/details/gtfmczwgrc.html

PHP:  $argv;  $argc;
来源：http://dali.xinyue.icu/Article/details/gtpngbqchm.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtqorivuzv.html

TS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtifgexdfs.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtezjlpihv.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gtgejzbpbj.html

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gtqbyqwlfz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtpipnnrak.html

[M02] 读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gtvpsoqgit.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtdipmybrp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtqeqkgmjw.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtkgqpyfgg.html

TS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtzoztwywb.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtzwzylcbm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtazgdkcjn.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gtxtocdmyv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtivmuvfov.html

[M03] 执行外部命令
来源：http://dali.yueranfly.top/Article/details/gtioqqsvkw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuanzx.com/Article/details/gthvmvtugb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gtbwpcpsox.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtgztxwdzx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gteswltnfb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gtgxvizwrl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbbyvyrz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yangfankeji.com/Article/details/gtchskgpfn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.quarkkingdee.top/Article/details/gtmvxabuaq.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gtiibwgiyz.html

Py:   os.getcwd()
来源：http://dali.tian-w.cn/Article/details/gtxkxtmjcd.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gtefnyfujx.html

JS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtmdabjxzb.html

TS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gtdtrcslvp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gtlgmuqtwj.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gtpbtxgjfp.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gtkhsuszol.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.vqdsnc.cn/Article/details/gtnozbtqpn.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlbnjyol.html

Py:   sys.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtjtsfqsie.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gtkifuqrzn.html

JS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtttabbkwz.html

TS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtjcvthvom.html

Java: System.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtqceaupzh.html

Go:   os.Exit(1)
来源：http://dali.hammf.cn/Article/details/gtzzwihbcm.html

Ruby: exit 1
来源：http://dali.9152youxi.cn/Article/details/gtkzjzepwd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gtqoujvnnl.html

[M06] 向标准错误输出
来源：http://dali.daria6918.cn/Article/details/gtjddbnnvi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtbwdnsbcf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gtwdtfdisx.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxoesatxy.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtpnxfzeqp.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwizmzlxe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gtztkojyos.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gtmmlkeaxx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gtonfytqze.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gtbdmcjksl.html

Py:   if __name__ == "__main__":
来源：http://dali.pengpengdd.cyou/Article/details/gtropnaysl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.c1oappe.top/Article/details/gtsrrjjzxw.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtzxmcstwr.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtiysmlsrr.html

Java: public static void main(String[] args)
来源：http://dali.yvedp.cn/Article/details/gtsgohzosk.html

Go:   func main()
来源：http://dali.redwolf501.top/Article/details/gtuutwlwir.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yanxiufei.cn/Article/details/gtglsuqubh.html

C#:   static void Main(string[] args)
来源：http://dali.zhixingplan.top/Article/details/gtnkzxohzc.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gtdeogvfza.html

Py:   platform.system();  platform.python_version()
来源：http://dali.meibo888.top/Article/details/gtolqfhbhd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gthmvllvkq.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtmitamllp.html

TS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtpwwqypyy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gtwvwltycr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gtwifohncm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258.top/Article/details/gtbiutqrrx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.bjfxy.top/Article/details/gtzwotoujf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwtnpakpv.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gtvucejxoj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtzqljyldb.html

[N01] 二分查找（有序数组）
来源：http://dali.cheryme.top/Article/details/gtbivifatc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlrtcdfh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sysykeji.top/Article/details/gtxgoplptp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gteticlekp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtkainkjaf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtxmrhaidz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtahmyvzwn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnxiangtu.top/Article/details/gtnadeswty.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtoetpcvew.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gtfcbocfbf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gtncpsigon.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yongpay.top/Article/details/gtivrhooxk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtsagxntbz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gtocxvhdvc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhphijbo.html

Go:   slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtclxedutf.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtvzfekbkw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gtrmsochnn.html

[N03] 快速排序（分治示例）
来源：http://dali.dianchejie.cn/Article/details/gtbauxwgcf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hammf.cn/Article/details/gtuycojbws.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ybcxt.top/Article/details/gtfrkeehnm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtxadpyucf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtxrcsgyrw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shangyingyoupin.top/Article/details/gttqdxteug.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guowangkeji.top/Article/details/gtugedaocm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ydzc1.top/Article/details/gtturayzpd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.iojbl.cn/Article/details/gtdljbmfsb.html

[N04] 斐波那契数列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxbofzku.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunnsnsjj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangdashe.top/Article/details/gtplgbkmma.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyubvtww.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtadqnbxwx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtaovsyoow.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gtlsfkajmt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gtysqpgxbd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtftgzsidf.html

[N05] 最大公约数
来源：http://dali.fengsongda.top/Article/details/gtjdytbxif.html

Py:   math.gcd(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawrdlgit.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shuidangran.top/Article/details/gtckqehguw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtjoiubnip.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtndywepny.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gtxvnmipgz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yonumen.top/Article/details/gtyctvfkup.html

Ruby: a.gcd(b)
来源：http://dali.pycfn.com/Article/details/gtpnaghrqx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zycfv.cn/Article/details/gtulvdkhex.html

[N06] 判断回文字符串
来源：http://dali.shangyingyoupin.top/Article/details/gthuceltph.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtbyozpads.html

PHP:  $s === strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtpcfzbtur.html

JS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtnzdvbklk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtzjjmhrez.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gtqnblwslt.html

Go:   // 双指针从两端比较
来源：http://dali.aizwys.cn/Article/details/gtpldmvdfj.html

Ruby: s == s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtgtshkosg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gthhbxbije.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gtxmkdyqms.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenlongwang.top/Article/details/gtntcqyeoi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.andypj.xyz/Article/details/gtsjjrpoko.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shangyingyoupin.top/Article/details/gtrbevefet.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuvrujwd.html

Java: // 手写 HashMap
来源：http://dali.dianchejie.cn/Article/details/gtjydlktdu.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gtcfzymrwj.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gttnhxnbsf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj202588.top/Article/details/gtxblmqzfy.html

[N08] 生成全排列
来源：http://dali.sufxvd.cn/Article/details/gtbjhmvbvk.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsevqpofr.html

PHP:  // 手写递归交换
来源：http://dali.snrcjt.cn/Article/details/gtktcpqgvp.html

JS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtmizwdofs.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtnvlfftbu.html

Java: // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gttsleumxu.html

Go:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtzjqnxdgy.html

Ruby: arr.permutation.to_a
来源：http://dali.zdqjudy.top/Article/details/gtpobrfowu.html

C#:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtsbgcxdkd.html

[N09] 栈与队列
来源：http://dali.guowangkeji.top/Article/details/gtdrcoijks.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvxrrdyg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvaawfdul.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtsexrfsgk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhongyouzk.top/Article/details/gtcbxognoa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gtnzlzarpy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xziqi.cn/Article/details/gtanajysdn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtknarabby.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgufenzy.top/Article/details/gtomktkdiz.html

[N10] 链表节点定义
来源：http://dali.tian-w.cn/Article/details/gtjrwmnsuc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yangfankeji.com/Article/details/gtycazcfpf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258.top/Article/details/gteuziergk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cashguo.top/Article/details/gtumsoohzc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dashuyun.cn/Article/details/gtbjoqwgvw.html

Java: class Node { int v; Node next; }
来源：http://dali.havefunace.top/Article/details/gtylpznntt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenjidiqi.icu/Article/details/gtgvcjimtw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shangyingyoupin.top/Article/details/gtzzzkpsou.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gtghjqayzv.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gtzasrcucc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gogol.net.cn/Article/details/gtaxtvyfng.html


<!-- 参考信息 -->