代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtnmcywluh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtztzoqlik.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangdashe.top/Article/details/gtjuxjjqaj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hfpthk.cn/Article/details/gtvlahnoqp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxinkj.top/Article/details/gtrgyhognk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gtkxysvtzu.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gtknofzzqa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gtlyugxwtm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gtfjgebivn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnydcipcr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtugspjlgf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gtwestrqts.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gtqhxrhbzo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.birdmap.top/Article/details/gtoirnhggx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtlgaxcbfx.html

[K05] 深拷贝对象
来源：http://dali.fengsongda.top/Article/details/gtqhezbhzn.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gtyznnsdop.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gtvwgbsmoa.html

JS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtiribupjb.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtjmzfjmbb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjypofpeb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.feifeiyinyue.top/Article/details/gtlehpbawy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwidgrob.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gtwjlvicyg.html

[K06] 解析 URL 查询串
来源：http://dali.zdqjudy.top/Article/details/gtioithrii.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtapnmlqfj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhixingplan.top/Article/details/gttomkuqdg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gtqacvfetp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gtdboprqyg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.havefunace.top/Article/details/gtzyacbjqd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtgoffamdg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtmfplrisf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gteyohsdjq.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnuhnujtj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtbjtovqck.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuanzhike.top/Article/details/gtykqmdwuf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gttqdmwobw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtcvzjbcmk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtejxncqwa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sufxvd.cn/Article/details/gtocgwshla.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fzhhl.top/Article/details/gtegwkxpsd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gthaoqrabs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gtcxatmcvj.html

Py:   pickle.dumps(obj)
来源：http://dali.havefunace.top/Article/details/gtscybizsv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gtizfucygu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gtddxktgcd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtcjewxnnj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jyoumei.cn/Article/details/gthblygswf.html

Go:   encoding/gob
来源：http://dali.mhx1999.top/Article/details/gtchwovlhr.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gthvkvgkhh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtdngogxen.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrpuwbzcu.html

L. 网络请求
来源：http://dali.chenzaomai.com/Article/details/gtppngskwa.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtiuccwgzu.html

[L01] 发送 GET 请求
来源：http://dali.zhengqikj.top/Article/details/gtbeoyareb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gtqafbghwk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj202588.top/Article/details/gtvvjomwjr.html

JS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gthvztzpxt.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtxvsbwbyt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gtalfyloms.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gtyageblym.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangshuangyany.cn/Article/details/gtxauxpytc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shzxlz.cn/Article/details/gtjpeakmzm.html

[L02] 发送 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gtfstuxgvk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtqydrhmlu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yueranfly.top/Article/details/gtytswsufw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtlhcrxbha.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gtxyijidrq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.iojbl.cn/Article/details/gtbnvevnzh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ppjwa.cn/Article/details/gtkdnbzmgl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.mhx1999.top/Article/details/gtrfoxkuwl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtufeolkbs.html

[L03] 设置自定义请求头
来源：http://dali.yuxming.cn/Article/details/gtffsgprkg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tanke756.top/Article/details/gtdugoqner.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gtosgcizyx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtugbpqglc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtpjvcfqcj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhengqikj.top/Article/details/gtmuivukiq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtqdcgueca.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sufxvd.cn/Article/details/gtvmjeednx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gtiqfuikgm.html

[L04] 设置超时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvdrmckh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guowangkeji.top/Article/details/gtgflcplic.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gtvuhrtrxt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudtsjghi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtxtnfaoid.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gtiehtxxtn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gtdgwmszoi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zycfv.cn/Article/details/gtlkoankcb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdydnocfr.html

[L05] 上传文件（multipart）
来源：http://dali.shzxlz.cn/Article/details/gtjbxcgunj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yanxiufei.cn/Article/details/gtwedvnmed.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.snrcjt.cn/Article/details/gtgptjwhas.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gtpipzvanr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtxszfkluy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gtoevgqsep.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gtdgboyghu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gtathwbubg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.havefunace.top/Article/details/gtqesqgbxs.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gtypicraqb.html

Py:   resp.json()
来源：http://dali.iojbl.cn/Article/details/gtujhfyoxr.html

PHP:  json_decode($body, true);
来源：http://dali.jlsjyb.cn/Article/details/gtmujhrltv.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gtsqyyokef.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtaslczsmy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtxcjzdhhp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuxming.cn/Article/details/gtxjumxcgg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gthgeodeqy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhixingplan.top/Article/details/gtlrjeoiuy.html

[L07] 处理 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gtzxzevoak.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhongyouzk.top/Article/details/gtnriusxnm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gotoacloud.top/Article/details/gtscruzqxf.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtyzikpwdg.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gtrsjsqxgm.html

Java: resp.statusCode()
来源：http://dali.pycfn.com/Article/details/gtdjxglnpj.html

Go:   resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtcxbkjwrz.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gthndfvjsl.html

C#:   (int)resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gthdtctkyc.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gthypgaxji.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yueranfly.top/Article/details/gttnjxxpvj.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gtbtsbegbp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtwipcxwew.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtwoontyuq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj202588.top/Article/details/gtdlokamff.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gtqfydzyir.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtausdhiag.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtxgniykou.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtmepxhuol.html

M. 命令行 / 进程 / 环境
来源：http://dali.cheryme.top/Article/details/gtqsmnqogv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtxnyrbpeb.html

[M01] 读取命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtcgeusraj.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gtbxxlmxhj.html

PHP:  $argv;  $argc;
来源：http://dali.iojbl.cn/Article/details/gtipacavzv.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtlaxwcxtz.html

TS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtslmseqqx.html

Java: args 数组（main 方法参数）
来源：http://dali.meibo888.top/Article/details/gttkldpmwj.html

Go:   os.Args[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtfalnpmyi.html

Ruby: ARGV
来源：http://dali.316326.xyz/Article/details/gtqyzgrjnl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtkrlrvkzl.html

[M02] 读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gtxbfmqsxh.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gtvsamrwdz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gthksjporv.html

JS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtrxhgiysm.html

TS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtczayrgvv.html

Java: System.getenv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoezpbxdq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtmhbclkvl.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gtfenbjxdl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gtcjhbvexs.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gtqtbagziy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gtuhojghtl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tanke756.top/Article/details/gteclcajfx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gttfkqfgvz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gtfwfgkhaj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gtyfzdcsmk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gtmadwngil.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.andypj.xyz/Article/details/gterhuttuq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gthfvtzthv.html

[M04] 获取当前工作目录
来源：http://dali.quarkkingdee.top/Article/details/gtreuyolrg.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gtqrbykwca.html

PHP:  getcwd();
来源：http://dali.cashguo.top/Article/details/gtldrakesh.html

JS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gtmntcvbrw.html

TS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gthndkzlxu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ybcxt.top/Article/details/gtzkihedkc.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gtvpbynryr.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhyzesoz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sysykeji.top/Article/details/gtfxsackpi.html

[M05] 设置退出码
来源：http://dali.jqgufenzy.top/Article/details/gthjgfztqn.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtdjvqrnlj.html

PHP:  exit(1);
来源：http://dali.jqgufenzy.top/Article/details/gtemdkhwpn.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtlvbeddnj.html

TS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtkauspfck.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtbpybeonl.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gtpdjwahyk.html

Ruby: exit 1
来源：http://dali.meibo888.top/Article/details/gtktkmobgh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gttwdevpnt.html

[M06] 向标准错误输出
来源：http://dali.tianlin.xyz/Article/details/gtkczlgfrp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gtpdygedvx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigufen.top/Article/details/gtyjxauylu.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtonrtceah.html

TS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtmihtfhej.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gtzdzosipy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gtzzddiqnw.html

Ruby: warn "err"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzxsecrl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.vqdsnc.cn/Article/details/gtdibnfgpo.html

[M07] 判断是否为主入口
来源：http://dali.ivvv.top/Article/details/gtihhwcbbo.html

Py:   if __name__ == "__main__":
来源：http://dali.gogol.net.cn/Article/details/gtehhrswcn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gaohongyu789.top/Article/details/gtucltjwlx.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtjdrkkpjl.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtgpnbsrdq.html

Java: public static void main(String[] args)
来源：http://dali.nwbrower.top/Article/details/gtdbcndbgm.html

Go:   func main()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkwmcgwg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gtbpdyrohz.html

C#:   static void Main(string[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtexkyvssf.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gtzzdwtjbl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gtfsjysctc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gtqbtvkxwi.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtdnpsgcti.html

TS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gthgqyzixe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.kuanghao11.cn/Article/details/gtiknrecjb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gtovmaudbr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenlongwang.top/Article/details/gtfrscwdfe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gtcefcidnp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtskaqfzec.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gtypfvvjeu.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtdqjutdsr.html

[N01] 二分查找（有序数组）
来源：http://dali.bjfxy.top/Article/details/gtevvcghad.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj202588.top/Article/details/gtiulccvkc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtdhfumatq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtnovncsug.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtgsxobjhv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtaogakaeo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtkgoldcwk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpzmdetw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtokfxdsyi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gtoqjdboxf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gttbunspqv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtayjxhhwe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtkabtcbhy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gtqbnwwoup.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ivvv.top/Article/details/gtkpmldorj.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtxnaykirk.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtznmaxcis.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhengqikj.top/Article/details/gtqetesywd.html

[N03] 快速排序（分治示例）
来源：http://dali.yueranfly.top/Article/details/gtkfmqsegu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgfzy.top/Article/details/gtjzbqjwty.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xylfe.cn/Article/details/gtcvwjisej.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gtgqwexbpw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gtqrtashud.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuanzx.com/Article/details/gtyifoeyem.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.9152youxi.cn/Article/details/gtdmkyfxqy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yangfankeji.com/Article/details/gtzvlvhinx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gtrlovcqsc.html

[N04] 斐波那契数列
来源：http://dali.zhongyouzk.top/Article/details/gtjdzfmaxd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gtrcpcdajk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtakcwmrio.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikmmvjhf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gthvihbsmp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yueranfly.top/Article/details/gttrufbhdo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gtvzmhhnur.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtoqtlqvew.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtqxntofjz.html

[N05] 最大公约数
来源：http://dali.sufxvd.cn/Article/details/gtvlrvwubk.html

Py:   math.gcd(a, b)
来源：http://dali.fzhhl.top/Article/details/gtjfbbhrke.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsgpdfwac.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtaydxqdjl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gtlqrjybss.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gtfuxnuoju.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ivvv.top/Article/details/gtomadzzin.html

Ruby: a.gcd(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtdehelboi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuxming.cn/Article/details/gtqidwxdcw.html

[N06] 判断回文字符串
来源：http://dali.yanxiufei.cn/Article/details/gthlfuagcq.html

Py:   s == s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchnmxxfy.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtozcufaeq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtfafupmwy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtmtitldrb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtixwxqufo.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gtesuwdvyd.html

Ruby: s == s.reverse
来源：http://dali.birdmap.top/Article/details/gtonuvjmbq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gtemmwvgnq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyjwruaz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gaohongyu789.top/Article/details/gtbywdcrca.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gtsuqselpa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuetiantiany.cn/Article/details/gtxfupfmmz.html

TS:   // 手写 Map<string, number>
来源：http://dali.ydzc1.top/Article/details/gtqzfsbyof.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gtjijckdyb.html

Go:   // 手写 map[int]int
来源：http://dali.zycfv.cn/Article/details/gtmnxhklxy.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gthixbbpkv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jlsjyb.cn/Article/details/gtprjfjhwl.html

[N08] 生成全排列
来源：http://dali.shzxlz.cn/Article/details/gtebahukjq.html

Py:   itertools.permutations(arr)
来源：http://dali.andypj.xyz/Article/details/gtibstmkiz.html

PHP:  // 手写递归交换
来源：http://dali.cucudq.cn/Article/details/gtudefksnt.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtsgikwlxb.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtzivxfovz.html

Java: // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtzyceiwtf.html

Go:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtjdshiflf.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxinkj.top/Article/details/gthetbzfoj.html

C#:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtolbnajhf.html

[N09] 栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtwxxwkszo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daxiang520.top/Article/details/gtjtsgqusl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gthmldhcms.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gttxpelgyt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.meibo888.top/Article/details/gtmimbssew.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gtzjqkpkoo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pycfn.com/Article/details/gtmpvufitc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtentkvfyn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtfgjnbkdt.html

[N10] 链表节点定义
来源：http://dali.sweek.top/Article/details/gtbagmkazb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.redwolf501.top/Article/details/gturpqoiem.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tian-w.cn/Article/details/gtqfcdsgwf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnyesixo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gteiqlvhxo.html

Java: class Node { int v; Node next; }
来源：http://dali.yangfankeji.com/Article/details/gtqcyuslqt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gtlrzmbmcr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.svipenyu.cn/Article/details/gtkwzsopta.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaghreje.html

[N11] 二叉树中序遍历
来源：http://dali.jiagoushi.top/Article/details/gtissasguo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jianghu66.top/Article/details/gtspcwvxjn.html

PHP:  // 手写递归函数
来源：http://dali.feifeiyinyue.top/Article/details/gtctsjdxrn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtyevmoisg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gtairzyolz.html

Java: // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtacejvwum.html


<!-- 参考信息 -->