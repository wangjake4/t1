代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtpdefwoad.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gttlrlzlgd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gtwroymuye.html

Ruby: JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtfpddbilu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aizwys.cn/Article/details/gtqmcjtche.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.meibo888.top/Article/details/gthtmkrgdy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtealsuano.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtlgjceokf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtoesnhmtm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtvubtowsv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenlongwang.top/Article/details/gtfdrgpmnl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenlongwang.top/Article/details/gtkajghtuc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gtimveqedx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjwoccdz.html

[K04] 读取 JSON 文件
来源：http://dali.jyoumei.cn/Article/details/gthrivikwp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gaohongyu789.top/Article/details/gtcvzqkvms.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gotoacloud.top/Article/details/gtizmqumce.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtwweedpcy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtftrvntag.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtwsprggxs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtcfgrbxde.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.bjfxy.top/Article/details/gtkzufmtwy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shuidangran.top/Article/details/gthcvitqwl.html

[K05] 深拷贝对象
来源：http://dali.jyoumei.cn/Article/details/gtttcuecev.html

Py:   copy.deepcopy(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtbrfjqspo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gogol.net.cn/Article/details/gtufzxezlu.html

JS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gtnhnfxpyo.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtwcgnwgnc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dashuyun.cn/Article/details/gtcmcxzdvd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gtmffegzzy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwzzyjhs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.vqdsnc.cn/Article/details/gtzwryopmo.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnovrscu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gtlsyzjrzp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fengsongda.top/Article/details/gtntktdxwm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtndlqrluq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwlcryzk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gtqcwwzypg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtfbhneasr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtjmmxyzzq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtqqcjenaa.html

[K07] 进制转换
来源：http://dali.wangshuangyany.cn/Article/details/gtsccebkgf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtngokzzwy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zdqjudy.top/Article/details/gtoitajnrv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtavaezxpc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtrxqprcun.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtvtrmjyva.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gtclcpxokj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gthkrntxwo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtifdeyckn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xinyue.icu/Article/details/gtrdeuosfs.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gtdnxxpccz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgufenzy.top/Article/details/gtevkdwbii.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtfwxknskp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gtiocwqndx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gtddrrbldj.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gttijywrgq.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkittcpxg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtyihghbcz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gttvsvyllg.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gtipquqenq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtwfmvpqgd.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gtagxzbwuw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258888.top/Article/details/gtzbczmqis.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gtocvgknpi.html

JS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gtwxsvwwxl.html

TS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtznbuigwy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sweek.top/Article/details/gtnckbtjip.html

Go:   resp, err := http.Get(url)
来源：http://dali.aibaodan.cn/Article/details/gtbxsfvvni.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhiwuduotai.top/Article/details/gtlddjnzww.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tianlin.xyz/Article/details/gtkbplymve.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtppoydjeo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.meibo888.top/Article/details/gtofxvbczi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jlsjyb.cn/Article/details/gtviayugaj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gtdrwnbnrl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gttfhumung.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gttqrszyft.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tanke756.top/Article/details/gtavzridrm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gtjyvqgyph.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtquxvtyrp.html

[L03] 设置自定义请求头
来源：http://dali.haohaochexian.top/Article/details/gtajgxavui.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cdnleiting.top/Article/details/gtcfesizgu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shzxlz.cn/Article/details/gtgdelczrm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gtndmonxml.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gthgkltdny.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxinkj.top/Article/details/gtcomnvzhc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtemkotzhn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.feifeiyinyue.top/Article/details/gtgmqvbxwu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gtpmchlyqx.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gtqwnxuqzo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwjwvrxf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhengqikj.top/Article/details/gtnqgrdftp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gteaxzhxbs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gtvjhxvrvn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gtibkfocqa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenlongwang.top/Article/details/gtpfuirxzf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xziqi.cn/Article/details/gtxbbmwtuj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sufxvd.cn/Article/details/gtblaqbrox.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtvshqwgyy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cucudq.cn/Article/details/gtnskxbatr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guannengcc.top/Article/details/gtpymkmcrd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gthuessdcm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtvtvwnhyh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnxiangtu.top/Article/details/gteydnkxlr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.iojbl.cn/Article/details/gttmlhzqja.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhbymdye.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtmwhiqcam.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtbumpfttf.html

Py:   resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtotehbwap.html

PHP:  json_decode($body, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtumnvswms.html

JS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gthfiuxoqr.html

TS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtjtxzhbmg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzivlljyc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gtipyjspdq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteexvylsa.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gtceejbgyc.html

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gttczpsxkj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cheryme.top/Article/details/gtdvmaijby.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gtgthddbkd.html

JS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gtseiaoraj.html

TS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtokjpwroh.html

Java: resp.statusCode()
来源：http://dali.9152youxi.cn/Article/details/gtfhlgwcbu.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtgumjyzvi.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gtrytuikpd.html

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtunupbzcn.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gthjnspxuu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gtydapaslf.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gthovszkkm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtfrgngbos.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtarwyemhj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gtniaeuzuf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jiagoushi.top/Article/details/gtlzimehgu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gtxpnjidhm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jianghu66.top/Article/details/gtznjdibsy.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtlirjlvpg.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvozqqnob.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gteapcpnyi.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gtksqfssmm.html

Py:   sys.argv[1:]
来源：http://dali.haohaochexian.top/Article/details/gtrjbouppf.html

PHP:  $argv;  $argc;
来源：http://dali.zhixingplan.top/Article/details/gthzqjnwie.html

JS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtuhsazure.html

TS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gtankubcwl.html

Java: args 数组（main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtxnnuhpeh.html

Go:   os.Args[1:]
来源：http://dali.zdqjudy.top/Article/details/gteqlbxewq.html

Ruby: ARGV
来源：http://dali.aizwys.cn/Article/details/gtkrntmdls.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtilaensmx.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gtcnqxgdlm.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gtclbtatfq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtfbemqolq.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gtlrtefpnx.html

TS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtswqmqhss.html

Java: System.getenv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtwllbbuno.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzddvprzw.html

Ruby: ENV["HOME"]
来源：http://dali.jqgfzy.top/Article/details/gtgihyacec.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cashguo.top/Article/details/gtrkcuzfil.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gtiitvcomi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvihsdfo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ehwqpu.com/Article/details/gtlahusqtu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtrjzouedo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtzziemgbd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gtarqnrlfw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuanzhike.top/Article/details/gtoavuwmia.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gtibowqmux.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gtqhrecekf.html

[M04] 获取当前工作目录
来源：http://dali.smart0.xyz/Article/details/gtjdevciwz.html

Py:   os.getcwd()
来源：http://dali.hammf.cn/Article/details/gtpudupipg.html

PHP:  getcwd();
来源：http://dali.xylfe.cn/Article/details/gtzqvqbpky.html

JS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gtxltpkhzo.html

TS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gtbwjjpsrm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gtbdxqotjf.html

Go:   os.Getwd()
来源：http://dali.yj202588.top/Article/details/gtkgjiivmj.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayhkajrk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gtwsedcpky.html

[M05] 设置退出码
来源：http://dali.xinyue.icu/Article/details/gtgheaqvko.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gtfeyhwcij.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtldpxhobt.html

JS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtkmuzlqus.html

TS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtqiqlqnsw.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtrfrnyrni.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtkvmcwosu.html

Ruby: exit 1
来源：http://dali.shangyingyoupin.top/Article/details/gtdcajuzgy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhongyouzk.top/Article/details/gthtbhdreu.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gtyrdvxwfm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqyywntbu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yonumen.top/Article/details/gtywplaltf.html

JS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtiyjufsvc.html

TS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gtxkwovqbi.html

Java: System.err.println("err")
来源：http://dali.daria6918.cn/Article/details/gtrgucuggd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gtgfrskajx.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gtcdipobyi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cdnleiting.top/Article/details/gtqwkcvhqs.html

[M07] 判断是否为主入口
来源：http://dali.nanxuanxn.top/Article/details/gtpxtsnuac.html

Py:   if __name__ == "__main__":
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpwbahnw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrtsbybr.html

JS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtbkethoyl.html

TS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gtyajunarw.html

Java: public static void main(String[] args)
来源：http://dali.cheryme.top/Article/details/gtlzwpsnxo.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gtilgcepml.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuetiantiany.cn/Article/details/gtqprbwkft.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gtppbxsawo.html

[M08] 获取系统与运行时信息
来源：http://dali.gaohongyu789.top/Article/details/gtoglijfrm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gtpptysgta.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.bjfxy.top/Article/details/gtpozfcqot.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gttvzvgrle.html

TS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gtopqpffol.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gthouqgobe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ppjwa.cn/Article/details/gtiurqnasn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tanke756.top/Article/details/gtvzwjzutq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gtccqfwxly.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqybqybe.html

N. 数据结构与算法
来源：http://dali.jqgfzy.top/Article/details/gtfjaiatgs.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtvmyujatr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhongyouzk.top/Article/details/gtmezozhgz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtnjdzzwqu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtmkejxsxe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtvtjklvps.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gttjmthgiu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtlksgkkhx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtifcjxmmj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuanzx.com/Article/details/gtbdryoqbz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtoqvkibye.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhiwuduotai.top/Article/details/gtzithcmqs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdalqwxxa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gtvsymgmjs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtgmvwoooi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtkmfahhxq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuanzx.com/Article/details/gtttktocot.html

Go:   slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtjnymjwzf.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtetagqylq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangdashe.top/Article/details/gtfwrdppyw.html

[N03] 快速排序（分治示例）
来源：http://dali.zdqjudy.top/Article/details/gtcmxbflxd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cqqwz.cn/Article/details/gttuppnona.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuxming.cn/Article/details/gtgnmlhgqt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtidrxoftq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gthnwojsii.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ppjwa.cn/Article/details/gtrvfgzabi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xziqi.cn/Article/details/gtjdeahbaq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.redwolf501.top/Article/details/gtohfigesg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yvedp.cn/Article/details/gtwfckqvju.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gtxxpqhwxt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtsideykwq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtcfgnhomu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtxwvqpjml.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtifaxwngn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gtcvxumltt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxuanxn.top/Article/details/gtpdolbqpx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtibzslmly.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzynsfjj.html

[N05] 最大公约数
来源：http://dali.dashuyun.cn/Article/details/gtmlahzhzj.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gttqbqdpzz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtdgisfclo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtzszjxxty.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtevauuykk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gtaaehcsgn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gaohongyu789.top/Article/details/gtjumenfiy.html

Ruby: a.gcd(b)
来源：http://dali.hysaishi.cn/Article/details/gtulunlmqa.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cqqwz.cn/Article/details/gtepcmoxmn.html

[N06] 判断回文字符串
来源：http://dali.fzhhl.top/Article/details/gtvuwsmjkv.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gtjvrdedae.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtnjedqsow.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtxoqkjtbx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfejzihj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258888.top/Article/details/gtdleqeksb.html

Go:   // 双指针从两端比较
来源：http://dali.xuetiantiany.cn/Article/details/gtyaipjxnz.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gtogdbfumn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtjhnrgypm.html

[N07] 两数之和（返回下标）
来源：http://dali.guowangkeji.top/Article/details/gtjxdfetka.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fzhhl.top/Article/details/gthixybdku.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jyoumei.cn/Article/details/gtqgkleoph.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.bjfxy.top/Article/details/gtlrlbtshm.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gtnzpurgji.html

Java: // 手写 HashMap
来源：http://dali.ehwqpu.com/Article/details/gtqrezawhz.html

Go:   // 手写 map[int]int
来源：http://dali.hnqzz.top/Article/details/gttrujzfnn.html

Ruby: // 手写 Hash
来源：http://dali.yj20258888.top/Article/details/gtvhjjzkts.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gtefvjyxlc.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gtvdrlsghm.html

Py:   itertools.permutations(arr)
来源：http://dali.sufxvd.cn/Article/details/gtvlrnmlvh.html

PHP:  // 手写递归交换
来源：http://dali.fengsongda.top/Article/details/gtmdpnoezw.html

JS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtwytdoshq.html

TS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtrnzkqyjg.html

Java: // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtppeadioj.html

Go:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtqiyxamrk.html

Ruby: arr.permutation.to_a
来源：http://dali.gzhubu.top/Article/details/gthwssugal.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtbmpumvuf.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gtclxcislg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gtxdngkaff.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtuzjopccr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtudxgzptf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.316326.xyz/Article/details/gtmcwrkcbs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsgzborn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlxuopnp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtqvstdfsu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cashguo.top/Article/details/gtgyzmkqry.html

[N10] 链表节点定义
来源：http://dali.tianlin.xyz/Article/details/gthyvifceg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shangyingyoupin.top/Article/details/gtcinhwqkk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gtaurjjqzx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gtbverlhjl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yonumen.top/Article/details/gtgbkleijz.html

Java: class Node { int v; Node next; }
来源：http://dali.fengsongda.top/Article/details/gtshblstfa.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hywenlv.cn/Article/details/gtkxdvmbvh.html


<!-- 参考信息 -->