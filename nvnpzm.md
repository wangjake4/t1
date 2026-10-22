代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2ipctwfqn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fengsongda.top/Article/details/gt2lnucayve.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gt2gilqnmkd.html

Ruby: JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2toblwkrw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gt2dvrmfnxg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtbxgyhk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gt2ngsrysvf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gt2ivbrokvi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aizjkrih.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmzjqqvk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.c1oappe.top/Article/details/gt2iexhxplm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhixingplan.top/Article/details/gt2ipymneuh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gt2ruorwgmc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.redwolf501.top/Article/details/gt2rdxigsth.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gt2eoghgxgk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gt2bfhgcngf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gt2xuhoyzmq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gt2qpijszkx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gt2ooddvtow.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2ibbifzym.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gt2thfcieby.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cheryme.top/Article/details/gt2zdharikp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gt2lvnoudut.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2ankrniyw.html

Py:   copy.deepcopy(obj)
来源：http://dali.iojbl.cn/Article/details/gt2wmtbqoxj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xziqi.cn/Article/details/gt2ukqfynvp.html

JS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2tlsdekud.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qzirevhz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sxryk.cn/Article/details/gt2rnooligj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ybcxt.top/Article/details/gt2aetezern.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.316326.xyz/Article/details/gt2rlgkzpqh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gt2eawqepbv.html

[K06] 解析 URL 查询串
来源：http://dali.jlsjyb.cn/Article/details/gt2jhbnjyer.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gt2cujhlgnv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.316326.xyz/Article/details/gt2jexyvdcp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzzkmhsz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gt2uolgglab.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gt2dzcpoztn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gt2mfbejdqv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gt2qyugodrv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2zhgebjtd.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gt2kuppzwzq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2ungancrq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gt2faorekid.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2oayhydbk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2cieuxcsw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2kstefjea.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shuidangran.top/Article/details/gt2qxmplbph.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gt2afndhfvi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2niaghluf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cucudq.cn/Article/details/gt2miyylrgi.html

Py:   pickle.dumps(obj)
来源：http://dali.birdmap.top/Article/details/gt2qacirdcz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gt2aciimmek.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gt2pujhydam.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gt2btbjipov.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuanzhike.top/Article/details/gt2ftzcfdxj.html

Go:   encoding/gob
来源：http://dali.yangfankeji.com/Article/details/gt2msakiafv.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fknknisr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cvynhymp.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2gttvuvtu.html

L. 网络请求
来源：http://dali.ivvv.top/Article/details/gt2lsqeursf.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2frayusjj.html

[L01] 发送 GET 请求
来源：http://dali.aibaodan.cn/Article/details/gt2gaggbeem.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gt2ekboadaz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ppjwa.cn/Article/details/gt2vtogncpb.html

JS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gt2qqwdkjmz.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gt2gtwjxhld.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvvdsugb.html

Go:   resp, err := http.Get(url)
来源：http://dali.shuidangran.top/Article/details/gt2fcxpydaq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ybcxt.top/Article/details/gt2vysxrkvb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2hkhdybuz.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gt2dsohmygb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gt2fjlclyub.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zdqjudy.top/Article/details/gt2cssukgae.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gt2adefbnyo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gt2wqcepcps.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gt2tzxbfbxm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aibaodan.cn/Article/details/gt2mlgvxhym.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gt2ogvbwujq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.snrcjt.cn/Article/details/gt2khzbvofq.html

[L03] 设置自定义请求头
来源：http://dali.svipenyu.cn/Article/details/gt2lcrfunth.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gt2dfrpavxx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hysaishi.cn/Article/details/gt2jfwavebm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gt2mcvaaxih.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gt2aifnlzdl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jyoumei.cn/Article/details/gt2gyevjomf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gt2vvfuvdkt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gt2qrnrntrv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gt2xxcipaxm.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yzfpctyd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gt2qhgmxwgj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qisjzkdf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gt2lpvkbyid.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2uuhgkhie.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gt2rjopcfvr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenzaomai.com/Article/details/gt2tuyqytcj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.0kj1m.cn/Article/details/gt2xnxntjyz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gt2ydcubwkk.html

[L05] 上传文件（multipart）
来源：http://dali.aibaodan.cn/Article/details/gt2nzuyzzjs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gt2mvuyukgm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tianlin.xyz/Article/details/gt2yabjnsue.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gt2ahpeftdw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gt2ibopgtfe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sufxvd.cn/Article/details/gt2jqjlcify.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gt2bimuteof.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nwbrower.top/Article/details/gt2jsvwndrr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2hjtefhim.html

[L06] 解析响应为 JSON
来源：http://dali.c1oappe.top/Article/details/gt2dqibloms.html

Py:   resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2obbyxkgy.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gt2rsgtxisx.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2caigsgrl.html

TS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gt2tduclhcq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqklxqfr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigufen.top/Article/details/gt2vketiuyc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhongyouzk.top/Article/details/gt2xuzowaez.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gt2mmfeextc.html

[L07] 处理 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gt2gvzvtduu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hywenlv.cn/Article/details/gt2fkvrljbd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahuyzdda.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gt2ibhztcfr.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gt2vmzxqtel.html

Java: resp.statusCode()
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvybnocf.html

Go:   resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gt2qntoeipf.html

Ruby: resp.code.to_i
来源：http://dali.zhengqikj.top/Article/details/gt2iluzshhr.html

C#:   (int)resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gt2yuhyybtg.html

[L08] 并发请求多个地址
来源：http://dali.shangyingyoupin.top/Article/details/gt2szuaxcky.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ybcxt.top/Article/details/gt2zknjnfqn.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258.top/Article/details/gt2hhihfqsq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gt2ffspviuv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2jbqdayns.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gt2wnzfckvk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gt2nejtmcet.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ehwqpu.com/Article/details/gt2etzxyrrb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2silnwmaf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2qibmwbde.html

M. 命令行 / 进程 / 环境
来源：http://dali.gogol.net.cn/Article/details/gt2tnmunyal.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2mynctetn.html

[M01] 读取命令行参数
来源：http://dali.fzhhl.top/Article/details/gt2gvsvbjww.html

Py:   sys.argv[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2rderlhlz.html

PHP:  $argv;  $argc;
来源：http://dali.jianghu66.top/Article/details/gt2ohzickws.html

JS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gt2vwzrmbql.html

TS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pgeefxyb.html

Java: args 数组（main 方法参数）
来源：http://dali.yj202588.top/Article/details/gt2qszrgtow.html

Go:   os.Args[1:]
来源：http://dali.jlsjyb.cn/Article/details/gt2cfgyfrjs.html

Ruby: ARGV
来源：http://dali.jiagoushi.top/Article/details/gt2qyzmvwxm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gt2jerytwzv.html

[M02] 读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2lldfbjfy.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2qzcccunv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rjnqpuua.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2amkkurbo.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gt2zrpdcqss.html

Java: System.getenv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2qkmlrmyy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2tlflqxgl.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gt2zhdceqdg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2qgecupyx.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gt2gkjamxks.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gt2ptfddjwg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuanzhike.top/Article/details/gt2ywqefrck.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gt2noapafww.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gt2orguzrdg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gt2drrahvwd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.meibo888.top/Article/details/gt2vkwjzjom.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuanzhike.top/Article/details/gt2yjsephil.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jianghu66.top/Article/details/gt2rpugozkh.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gt2wtljgsjr.html

Py:   os.getcwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2tagdavve.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gt2iszjuehu.html

JS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gt2dsteukqi.html

TS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gt2qpqfbcif.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hysaishi.cn/Article/details/gt2qyqxkdal.html

Go:   os.Getwd()
来源：http://dali.yuanzhike.top/Article/details/gt2hrukkvpo.html

Ruby: Dir.pwd
来源：http://dali.jyoumei.cn/Article/details/gt2guwpvrtb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgfzy.top/Article/details/gt2hpoiyosu.html

[M05] 设置退出码
来源：http://dali.wangdashe.top/Article/details/gt2depiwgvq.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gt2inxxaygn.html

PHP:  exit(1);
来源：http://dali.0kj1m.cn/Article/details/gt2sjqzdfei.html

JS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2gjdlyiqe.html

TS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2rnlawibf.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2gzxtjnsy.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2labsgbjb.html

Ruby: exit 1
来源：http://dali.zdqjudy.top/Article/details/gt2ujdzhtje.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sufxvd.cn/Article/details/gt2coifkgyg.html

[M06] 向标准错误输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2uwcxtkjf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gt2zhzvjttj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jianghu66.top/Article/details/gt2mueelhdq.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gt2jkuqqbvh.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gt2nhuourxa.html

Java: System.err.println("err")
来源：http://dali.chenzaomai.com/Article/details/gt2vozwshur.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.vqdsnc.cn/Article/details/gt2axtswvca.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gt2oxmvcuxl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.snrcjt.cn/Article/details/gt2frmbtkvu.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gt2vmmvxcpz.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gt2dgjndvvt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.meibo888.top/Article/details/gt2mfcxhwlw.html

JS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gt2zktnqarw.html

TS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gt2tzjhwlvb.html

Java: public static void main(String[] args)
来源：http://dali.yanxiufei.cn/Article/details/gt2cdskgrkf.html

Go:   func main()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jsfksywr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daria6918.cn/Article/details/gt2aovqqhzz.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yrqnkciw.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gt2kcjjjjie.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gotoacloud.top/Article/details/gt2uraaqvkw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gt2cznlwumn.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gt2jfxyeril.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gt2syiylgvh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bfmwjwxz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.9152youxi.cn/Article/details/gt2yjksdqjh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cashguo.top/Article/details/gt2vecidpep.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yvedp.cn/Article/details/gt2hbrcyrrk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2slkijxts.html

N. 数据结构与算法
来源：http://dali.jinqigufen.top/Article/details/gt2qjyhshba.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2wfkqnqgr.html

[N01] 二分查找（有序数组）
来源：http://dali.quarkkingdee.top/Article/details/gt2fgskleyc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2gphouplt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2uvoccfgo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2rpxnalvh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gt2bkqedqzp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2cvxhwqpi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dusgswjg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zycfv.cn/Article/details/gt2rqyfzbgk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2ixyzqssh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbhinszr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gt2puhdxjnn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gt2gxndhqdz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2qzubpvpo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkngfldg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sufxvd.cn/Article/details/gt2ytrsbyeb.html

Go:   slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2nbeztuzg.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gt2bxzzjvrt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.snrcjt.cn/Article/details/gt2uqyvhsnk.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gt2dmfcuuje.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sysykeji.top/Article/details/gt2klncdfut.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenlongwang.top/Article/details/gt2trfhewjs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uppjbiql.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gt2damfigbs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenzaomai.com/Article/details/gt2hhtxaalj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tianlin.xyz/Article/details/gt2qsnbdrlk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shuidangran.top/Article/details/gt2fwihzzus.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmctzgue.html

[N04] 斐波那契数列
来源：http://dali.cheryme.top/Article/details/gt2iwckmdao.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mvjmyter.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gt2tqdlxwvm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gt2oovaxfdb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2xsyyfqoa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yonumen.top/Article/details/gt2jilhdfuq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2atxooylv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gt2zbhvkfpv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2omovojdb.html

[N05] 最大公约数
来源：http://dali.ehwqpu.com/Article/details/gt2jfdkuisp.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nauynyre.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pycfn.com/Article/details/gt2rgibeqwq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gt2yzwjyosy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gt2bumuqyou.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgfzy.top/Article/details/gt2wcyjwgel.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dianchejie.cn/Article/details/gt2gnfhfsdz.html

Ruby: a.gcd(b)
来源：http://dali.smart0.xyz/Article/details/gt2rqzfnfpy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj202588.top/Article/details/gt2fbvzmunc.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gt2clroedhm.html

Py:   s == s[::-1]
来源：http://dali.daria6918.cn/Article/details/gt2kccwuiod.html

PHP:  $s === strrev($s);
来源：http://dali.pycfn.com/Article/details/gt2bukjegtf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gt2yenurjul.html

TS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2vshmhrxy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdoxfxok.html

Go:   // 双指针从两端比较
来源：http://dali.zdqjudy.top/Article/details/gt2vlnqrklt.html

Ruby: s == s.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2rhvvwvhz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gt2yodqxoce.html

[N07] 两数之和（返回下标）
来源：http://dali.zhoulong.xyz/Article/details/gt2sxbcmxdo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gt2uuarxsts.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuanzhike.top/Article/details/gt2lugmfkay.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuanzx.com/Article/details/gt2qahwrgqp.html

TS:   // 手写 Map<string, number>
来源：http://dali.shuidangran.top/Article/details/gt2qxqaabbv.html

Java: // 手写 HashMap
来源：http://dali.yuxming.cn/Article/details/gt2hcerybfl.html

Go:   // 手写 map[int]int
来源：http://dali.haohaochexian.top/Article/details/gt2uyiwwdlj.html

Ruby: // 手写 Hash
来源：http://dali.jinqigufen.top/Article/details/gt2zzgtuxwc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gt2hhpyflrp.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gt2uctdkjui.html

Py:   itertools.permutations(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2zgonjmxp.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gt2yaicwgbi.html

JS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2kryxowoj.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2nuvseoif.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2mzkcdxtv.html

Go:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2uzzxqpaf.html

Ruby: arr.permutation.to_a
来源：http://dali.c1oappe.top/Article/details/gt2pwbracdc.html

C#:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2nbsybhbi.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdfflhf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yueranfly.top/Article/details/gt2zdnxdxco.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmelpvru.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gt2tgsuqiud.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gt2cnumozqi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwjuxghp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2fyvhchgh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gt2rhgkfjip.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnkvzbeu.html

[N10] 链表节点定义
来源：http://dali.hfpthk.cn/Article/details/gt2kmdqphwi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdvcjgqd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.andypj.xyz/Article/details/gt2psputwpy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yvedp.cn/Article/details/gt2ntmimess.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenzaomai.com/Article/details/gt2lldsaoyz.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gt2bteclmam.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gt2ljclfaes.html


<!-- 参考信息 -->