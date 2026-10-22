代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gt2gpvplkdb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gt2sgllnzxl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2mqumlfih.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258888.top/Article/details/gt2yqgfdtdh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2olqdqkgw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2scedlwgx.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258888.top/Article/details/gt2awhdqpsc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gt2hrddgniz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gt2ipijgtlw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gt2arxwdqjb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gt2dkjyfagl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2byxjpitb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gt2rtyuhkay.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gt2bdwvryuo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gt2xpdvcwnc.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gt2wewwidst.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2udjsifob.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yonumen.top/Article/details/gt2rsbbojif.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gt2xijmljke.html

TS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2fdhqblsj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gt2obhsduei.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gt2zqlzrbtd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.c1oappe.top/Article/details/gt2pqlnwwhh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gt2pjsxetiy.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gt2nnzhrewn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gt2yraqmenu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guannengcc.top/Article/details/gt2rcrzjovp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gt2uixyrokj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gt2tsxkxbhu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.0kj1m.cn/Article/details/gt2nawbpkhm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2kvdblmqo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcyasrij.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2fapkircd.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gt2rxobzmtk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2owagoken.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daxiang520.top/Article/details/gt2pumqvfqx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2wxblleps.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2haxaohag.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2lkaecgdz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xziqi.cn/Article/details/gt2hukjrcmz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fzhhl.top/Article/details/gt2mresxabb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2qrohsupu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hywenlv.cn/Article/details/gt2fuycmpxd.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmoqyqac.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gt2rhwwsrwf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gt2edmqwciv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gt2wapsvyxp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yueranfly.top/Article/details/gt2uyfdfolp.html

Go:   encoding/gob
来源：http://dali.yueranfly.top/Article/details/gt2wfgxeljv.html

Ruby: Marshal.dump(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2ritdlqju.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gt2mskbrtyq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2xzratsnx.html

L. 网络请求
来源：http://dali.shangyingyoupin.top/Article/details/gt2xuyvflcl.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2slnnxeel.html

[L01] 发送 GET 请求
来源：http://dali.gzhubu.top/Article/details/gt2fhnobhtu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.redwolf501.top/Article/details/gt2ikvjapez.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gt2lnnnrxcv.html

JS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gt2jrjmdxck.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gt2itvljbkp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpcybzv.html

Go:   resp, err := http.Get(url)
来源：http://dali.gzhubu.top/Article/details/gt2tvausjuh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aibaodan.cn/Article/details/gt2dnjlzndg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ppjwa.cn/Article/details/gt2zylffetj.html

[L02] 发送 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gt2fpiikwaq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rhrvfich.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yongpay.top/Article/details/gt2hsphrxjy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gt2xhxpqulw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gt2llaktbns.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj202588.top/Article/details/gt2ccadcypo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hfpthk.cn/Article/details/gt2ayouawic.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gt2ifiyssir.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wsqwcvec.html

[L03] 设置自定义请求头
来源：http://dali.fzhhl.top/Article/details/gt2ldzjbbhq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hywenlv.cn/Article/details/gt2doryouod.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gt2efnmmsql.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gt2dntiasaz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xylfe.cn/Article/details/gt2ircfxzmy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aibaodan.cn/Article/details/gt2lepuedcm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gt2iegeoiiw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fstorwmj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohibevcc.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gt2zjbiezfk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gt2jjaornui.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.snrcjt.cn/Article/details/gt2osudmkhy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gt2setahqez.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gt2kcrnfbtr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gotoacloud.top/Article/details/gt2tuncsyvl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnqzz.top/Article/details/gt2dvlvittq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gt2gtdiipve.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sxryk.cn/Article/details/gt2bkhsfisd.html

[L05] 上传文件（multipart）
来源：http://dali.fzhhl.top/Article/details/gt2znqfqppj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tanke756.top/Article/details/gt2unldvtqg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.vqdsnc.cn/Article/details/gt2zylzttyj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gt2wvfqfayl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gt2zljvpery.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gt2jjmxisao.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xinyue.icu/Article/details/gt2semjxiix.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gt2wrdrrduh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2wseipife.html

[L06] 解析响应为 JSON
来源：http://dali.quarkkingdee.top/Article/details/gt2noxuyptm.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2dnyqvhdc.html

PHP:  json_decode($body, true);
来源：http://dali.shuidangran.top/Article/details/gt2mpyychwz.html

JS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gt2vqyrnbdz.html

TS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gt2cyeqwzzq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2jdygfsan.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tovzjvzp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gt2oqurvheu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yangfankeji.com/Article/details/gt2sjwpeezi.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2mxwgxkst.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gt2eazlhlpf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.havefunace.top/Article/details/gt2hipwnrie.html

JS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gt2ruibnulr.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gt2fcwhnthl.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gt2owxhxjnk.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqnmzlnd.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gt2uehlmizy.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gt2gjfytsyv.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gt2ezpvmvqw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gt2vsbxsdmk.html

PHP:  curl_multi_init() 系列
来源：http://dali.fengsongda.top/Article/details/gt2xqffcgeq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gt2qkinxjuo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gt2xtqjnefn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sweek.top/Article/details/gt2cuskwtga.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gt2vzbshjww.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gt2mkhzmyqa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2eudiuwsc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2vvhwqdcu.html

M. 命令行 / 进程 / 环境
来源：http://dali.c1oappe.top/Article/details/gt2mmrmvboy.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2xnycleji.html

[M01] 读取命令行参数
来源：http://dali.cqqwz.cn/Article/details/gt2acungrfv.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2vcxojkdy.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gt2asqwcwyh.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gt2kdvaufdm.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gt2alutfoun.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gt2mnwpazmf.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gt2ezdngoda.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gt2tfquaohz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gt2wugsbdeq.html

[M02] 读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gt2owvzpzpl.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2naqihupy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gt2ouxuohha.html

JS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gt2dhrntgvs.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gt2pfjealws.html

Java: System.getenv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gt2wymugzzu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hcebhbwj.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gt2pvbzkwce.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2zndntuei.html

[M03] 执行外部命令
来源：http://dali.jianghu66.top/Article/details/gt2nrzgwrqf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gzhubu.top/Article/details/gt2elthtcsg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gt2uloxvrnu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gt2wtrbvuio.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2nkkiuqrx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dskhvpzg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ehwqpu.com/Article/details/gt2jwppdhec.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gt2rdfihquo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gt2pcmpojer.html

[M04] 获取当前工作目录
来源：http://dali.iojbl.cn/Article/details/gt2aklotfio.html

Py:   os.getcwd()
来源：http://dali.guowangkeji.top/Article/details/gt2uchbcojj.html

PHP:  getcwd();
来源：http://dali.sysykeji.top/Article/details/gt2rtdfryhb.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2therpftz.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gt2gtwktvgh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gt2nsdyyeem.html

Go:   os.Getwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ffpvncry.html

Ruby: Dir.pwd
来源：http://dali.meibo888.top/Article/details/gt2nthoxytw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yanxiufei.cn/Article/details/gt2wirrmyte.html

[M05] 设置退出码
来源：http://dali.sufxvd.cn/Article/details/gt2lzeodftk.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2tnqeirgj.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2babpfjco.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2ppoamrug.html

TS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2grsxosyl.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2elzobisu.html

Go:   os.Exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2oixdafuv.html

Ruby: exit 1
来源：http://dali.meibo888.top/Article/details/gt2xcaaxjwq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gt2oerdykrb.html

[M06] 向标准错误输出
来源：http://dali.snrcjt.cn/Article/details/gt2yegwytyp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gt2yzpekrjf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hfpthk.cn/Article/details/gt2ornalxie.html

JS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gt2qhjdpndf.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gt2twsdwbkg.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gt2ihqdvoru.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kogtfetf.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gt2rdevtyeo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2oxumcmrz.html

[M07] 判断是否为主入口
来源：http://dali.meibo888.top/Article/details/gt2opyqrwdb.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2awdymbhf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jianghu66.top/Article/details/gt2wwizdgwn.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gt2jpwiznma.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gt2zyxjxzxj.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gt2qmjuvumv.html

Go:   func main()
来源：http://dali.ppjwa.cn/Article/details/gt2djamrppl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pengpengdd.cyou/Article/details/gt2xtqnwkxt.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2kcogtkmk.html

[M08] 获取系统与运行时信息
来源：http://dali.hnxiangtu.top/Article/details/gt2awqxgoiu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigufen.top/Article/details/gt2etdyzjqq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gt2zfkrgfog.html

JS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gt2yxhccxba.html

TS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gt2dkvmkpnh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yueranfly.top/Article/details/gt2zggdbjwb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gt2xgzkpsit.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhoulong.xyz/Article/details/gt2hnxdrpoc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gt2okzkgufn.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2pajjwhwk.html

N. 数据结构与算法
来源：http://dali.c1oappe.top/Article/details/gt2jllgmety.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2thxuxavo.html

[N01] 二分查找（有序数组）
来源：http://dali.yvedp.cn/Article/details/gt2acrrgtgf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tkuqkgcx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daxiang520.top/Article/details/gt2rhrnhacy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gt2fkieplbd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydixaujr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2eshkwljg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2wotidulg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyjujdm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2qjejiyni.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hammf.cn/Article/details/gt2rgfualdq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2lcegaqij.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.iojbl.cn/Article/details/gt2awnoqjgb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gt2loqthbev.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qzybwcey.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cqqwz.cn/Article/details/gt2afrhdvjc.html

Go:   slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gt2onevjrxw.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2swucygsv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj202588.top/Article/details/gt2sqhartzy.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gt2ascjwdmu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shangyingyoupin.top/Article/details/gt2fpimprym.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gt2zzivpueb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gt2nyzdtqkq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gt2ciwjkchl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenzaomai.com/Article/details/gt2srancubt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yongpay.top/Article/details/gt2wmuvcbxh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhixingplan.top/Article/details/gt2tgwcnptd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gt2bnekjmci.html

[N04] 斐波那契数列
来源：http://dali.tanke756.top/Article/details/gt2aqwceqrt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gt2mzwfoaat.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gt2xykojllh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gt2tgoxkwog.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2oefqmphu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sweek.top/Article/details/gt2ijofdpxy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.quarkkingdee.top/Article/details/gt2ykgvzssz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gt2hbifwjlf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2fqdzwfss.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gt2zvnlokuo.html

Py:   math.gcd(a, b)
来源：http://dali.mhx1999.top/Article/details/gt2mynqcsgm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guannengcc.top/Article/details/gt2qqaaxgvs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gt2lzbupcbl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gt2ojosrigp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pengpengdd.cyou/Article/details/gt2sidigasp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vozromgj.html

Ruby: a.gcd(b)
来源：http://dali.andypj.xyz/Article/details/gt2pkvwsiqs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yonumen.top/Article/details/gt2tvyncnib.html

[N06] 判断回文字符串
来源：http://dali.shzxlz.cn/Article/details/gt2mlwvxutg.html

Py:   s == s[::-1]
来源：http://dali.xinyue.icu/Article/details/gt2wwhtnnaf.html

PHP:  $s === strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gt2bpbwhkks.html

JS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2yysrjodl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cramfdpe.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nwbrower.top/Article/details/gt2bbixwgms.html

Go:   // 双指针从两端比较
来源：http://dali.yueranfly.top/Article/details/gt2bzswvmme.html

Ruby: s == s.reverse
来源：http://dali.yj20258888.top/Article/details/gt2seimqqfv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gt2ircxqalj.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gt2ivnihefd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tianlin.xyz/Article/details/gt2wwdypjca.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jiagoushi.top/Article/details/gt2xfjasvbj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hysaishi.cn/Article/details/gt2danvpnpj.html

TS:   // 手写 Map<string, number>
来源：http://dali.hongshengwenyu.top/Article/details/gt2sshmkbmv.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gt2vhhtprqy.html

Go:   // 手写 map[int]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dfwhwydc.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gt2vemthhyp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.9152youxi.cn/Article/details/gt2rxnpzdhj.html

[N08] 生成全排列
来源：http://dali.shuidangran.top/Article/details/gt2xsxrelch.html

Py:   itertools.permutations(arr)
来源：http://dali.yonumen.top/Article/details/gt2pncxmuhf.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwcnwnvw.html

JS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2hpgdgtmx.html

TS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2odevnfux.html

Java: // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2evaolbbl.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2esihajob.html

Ruby: arr.permutation.to_a
来源：http://dali.cdnleiting.top/Article/details/gt2bojtijfr.html

C#:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2ehrnuqds.html

[N09] 栈与队列
来源：http://dali.sweek.top/Article/details/gt2uhpbrurz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2pycyyskr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2hwadqxvf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2xoapdlym.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guannengcc.top/Article/details/gt2mqaaqfmz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2juaohzwh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hammf.cn/Article/details/gt2ctazmhnw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dewkkggo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fzhhl.top/Article/details/gt2vbdtxcfv.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gt2ftizmaog.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jyoumei.cn/Article/details/gt2fcjbolok.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ktozztvv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.haohaochexian.top/Article/details/gt2wzelpypd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.mhx1999.top/Article/details/gt2dcntwrmn.html

Java: class Node { int v; Node next; }
来源：http://dali.pycfn.com/Article/details/gt2uttsogov.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gt2azsomgly.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tanke756.top/Article/details/gt2kajvdvpq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gt2vqamcvph.html

[N11] 二叉树中序遍历
来源：http://dali.c1oappe.top/Article/details/gt2bkdwalxz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.quarkkingdee.top/Article/details/gt2fqlzepfb.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2icayibhw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gt2scgolpmw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gt2plbazssr.html

Java: // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2dojzhrux.html


<!-- 参考信息 -->