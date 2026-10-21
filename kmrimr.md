代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtwiqsfnyy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258888.top/Article/details/gtwwoqkvog.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtpkxnjkal.html

Ruby: JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtsawjjijg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gtvaoswvwz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ybcxt.top/Article/details/gttmnxwsnl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtcatjckub.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtvkysiypg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtyqbsimfd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtjpkotpgq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtrkkkmdfc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gtoeqdujfh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sysykeji.top/Article/details/gtxaurirer.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gteqjbbbcd.html

[K04] 读取 JSON 文件
来源：http://dali.sufxvd.cn/Article/details/gtxxihtmez.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhengqikj.top/Article/details/gtnvvpfnvt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gtegcllebp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtkyqripxm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtckovewrd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.meibo888.top/Article/details/gtswwkgxii.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gteggplptp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtzepyiiul.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtaaveebcp.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gtpyikxgnw.html

Py:   copy.deepcopy(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtgevdoddw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shangyingyoupin.top/Article/details/gtmdqxcfhs.html

JS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtygfllxxi.html

TS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcydytxy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gtqiamdviv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvafszfu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xylfe.cn/Article/details/gtiujylgzg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gtptcjshwu.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gtjeeptjlo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtlbdbsxne.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlaycjgkl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtesdkxfha.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtzpumubio.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigfzy.top/Article/details/gtuwrvxscb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gttfdhwqvp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtvfxfnnco.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtoxhvloab.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpstwgum.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtzijbxwoi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tanke756.top/Article/details/gtgltdodlb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtukgzxyiq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtulfbfdxh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtfjldrods.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmchavtvm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.9152youxi.cn/Article/details/gttudopbzd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtmkmmrdxw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gtfbuhjmdn.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gtrquvslnb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtooekcqut.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtnlpcmmrk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtnrvdrvfe.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ppjwa.cn/Article/details/gtwhljnczn.html

Go:   encoding/gob
来源：http://dali.bjfxy.top/Article/details/gtxabeeqya.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gtvorwfitf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtikkonzkn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtbymukhcs.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gtiuihqxca.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtjaxqxndl.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gtgdineujv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gtxoykkxaf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gtcaiicpdn.html

JS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtgmgpuxwp.html

TS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gtimvfknma.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gtuyeutbwe.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnqzz.top/Article/details/gtsgbfbjzx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yanxiufei.cn/Article/details/gtuicxxxns.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tian-w.cn/Article/details/gtkgiialsc.html

[L02] 发送 POST JSON
来源：http://dali.tanke756.top/Article/details/gtnipiovuw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gtiawwbqce.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.9152youxi.cn/Article/details/gtpcdcjozh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtdlgkoryf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtuqahzgpq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zycfv.cn/Article/details/gtmdwgyvqs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gtrgcgmcsx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shzxlz.cn/Article/details/gtachvgpjx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gtveypxplc.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gtjhwrunvs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gtdnmpciak.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gtjcoklwkg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtbldvzrku.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtkvoevlay.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gtknjxdxkx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gtparxlwzs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gthqkvobyv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtmepmtabe.html

[L04] 设置超时
来源：http://dali.gzhubu.top/Article/details/gttoywsgvf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gtcviemzdz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gtxrookbkz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gttnzjbsfm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtjutpcqrr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gthtdpmafm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gtdybhlnle.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnxiangtu.top/Article/details/gttwcreokc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnxiangtu.top/Article/details/gtnjzkdqpe.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxjcvkif.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shzxlz.cn/Article/details/gtjbaucfyh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangtech.top/Article/details/gttaaivxws.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gtxgnhamkp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtrsnpoyfe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yonumen.top/Article/details/gtfjxayqaw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xinyue.icu/Article/details/gtommoousm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhoulong.xyz/Article/details/gtzdtgqfan.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtfwqyxxjf.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gtipzxkpps.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gtrajdcvxp.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gtrfqvweew.html

JS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtlyjharbc.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gthykvlisb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtpxkfamjh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ehwqpu.com/Article/details/gtwxbpaimm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.c1oappe.top/Article/details/gtvksdrnty.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuanzhike.top/Article/details/gtflcwoibw.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtbqyzgibj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.9152youxi.cn/Article/details/gtofygiecb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dianchejie.cn/Article/details/gtxvarjecj.html

JS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtwgtuumds.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtzvxuiufs.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gtddexbvxk.html

Go:   resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtgrpomkmo.html

Ruby: resp.code.to_i
来源：http://dali.jyoumei.cn/Article/details/gtuxuhwtpo.html

C#:   (int)resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtcdzwodse.html

[L08] 并发请求多个地址
来源：http://dali.haohaochexian.top/Article/details/gtfpstejvb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pengpengdd.cyou/Article/details/gtpmqhwuza.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gtwcsrhfiu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtlunmbkyo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtqtqwgxaj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gtaanprdum.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yvedp.cn/Article/details/gthakwhfrn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtdwujlptc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtezcbedys.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtyykpcpai.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxinkj.top/Article/details/gtmiomical.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfoeyastm.html

[M01] 读取命令行参数
来源：http://dali.havefunace.top/Article/details/gtruqqgzzx.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gtxxpmlktr.html

PHP:  $argv;  $argc;
来源：http://dali.haohaochexian.top/Article/details/gtnptjmoes.html

JS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtwxjlkhjl.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtuyuzlopu.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtoclsjsyb.html

Go:   os.Args[1:]
来源：http://dali.fengsongda.top/Article/details/gtzzrjwjhv.html

Ruby: ARGV
来源：http://dali.xuanzx.com/Article/details/gtmyouqbsp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gtfyqlzfcj.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gtqkguxqmx.html

Py:   os.environ.get("HOME")
来源：http://dali.tian-w.cn/Article/details/gtwbpzoesm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtqevzjgsl.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtqyofxnsy.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtqijiphsm.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gtxrwhwgci.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtasmbimaf.html

Ruby: ENV["HOME"]
来源：http://dali.nanxuanxn.top/Article/details/gtxhfmbzzy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtageiadkf.html

[M03] 执行外部命令
来源：http://dali.jianghu66.top/Article/details/gtkfxkkopy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.havefunace.top/Article/details/gtpelgqlif.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gtaprcujij.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtoefllkpo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtlazjkwkt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hongshengwenyu.top/Article/details/gtilyujnir.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigfzy.top/Article/details/gtfdgqgkgz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gtlffytuxw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yongpay.top/Article/details/gtzhizdldx.html

[M04] 获取当前工作目录
来源：http://dali.svipenyu.cn/Article/details/gtoweefqyy.html

Py:   os.getcwd()
来源：http://dali.cucudq.cn/Article/details/gtpjbnaxdl.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gtgpuzdatt.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtuqxmdvby.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gtmwfeegfa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxinkj.top/Article/details/gtcsidkaqj.html

Go:   os.Getwd()
来源：http://dali.zhoulong.xyz/Article/details/gtjcmkiqtr.html

Ruby: Dir.pwd
来源：http://dali.tian-w.cn/Article/details/gtwkuphzqs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ydzc1.top/Article/details/gtuzoddmyq.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gtaqgfmlqv.html

Py:   sys.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtjcdensrc.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gtwdkzszcd.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtonkpfzas.html

TS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtjyhkuzlr.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtpbioeika.html

Go:   os.Exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtbmvynfye.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gtxwnpotsa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hongshengwenyu.top/Article/details/gtxpbzwfgs.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gtdiyjmqrz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gteiwlplxi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gtvzobpsgv.html

JS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gtlnquimpa.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtzacgrvit.html

Java: System.err.println("err")
来源：http://dali.0kj1m.cn/Article/details/gtixdsgthh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gtamtywyba.html

Ruby: warn "err"
来源：http://dali.fengsongda.top/Article/details/gteoyrepwc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjrgwlmp.html

[M07] 判断是否为主入口
来源：http://dali.jinqigfzy.top/Article/details/gtwhfbogay.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gtoadhtpjw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guannengcc.top/Article/details/gtbieuttfa.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gtnrqkoyrn.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtggutqsgk.html

Java: public static void main(String[] args)
来源：http://dali.ivvv.top/Article/details/gtpecqfdif.html

Go:   func main()
来源：http://dali.quarkkingdee.top/Article/details/gtvywuhydm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.vqdsnc.cn/Article/details/gtapdeyztj.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gtfxhxonuc.html

[M08] 获取系统与运行时信息
来源：http://dali.yuxming.cn/Article/details/gtkmxljqlk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenjidiqi.icu/Article/details/gttfrhqdab.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gttajbohec.html

JS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gtwvhwxtkz.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtqaijupbv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gtfpcjdurd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gtirxqkocx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gtzniwbnjk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gtcenhrrzw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtvrslwubn.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gtgvwwqoda.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtpbezyqkd.html

[N01] 二分查找（有序数组）
来源：http://dali.yangfankeji.com/Article/details/gthpkhnkiz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtotffcxmm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gteaqswjpo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtopajwvao.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gthrdufgjw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtqrigaost.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtwhwnnqwb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zdqjudy.top/Article/details/gtqoubebjh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtatrqxivn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gtlkdyjcdd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtznfytetb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shuidangran.top/Article/details/gttimsiwxg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtjruskdkk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gthyxscvvy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gthfnlqteo.html

Go:   slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gtvswsfqur.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gtaisxkyml.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zycfv.cn/Article/details/gtwoqlhhxe.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgumzzxqg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gthunqziit.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aizwys.cn/Article/details/gtnbtdprcs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtgzikjkdx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtaqloymah.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gtdjnczwmu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gteqmqidgn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenjidiqi.icu/Article/details/gtxkyrubvo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gtltljvxdr.html

[N04] 斐波那契数列
来源：http://dali.aibaodan.cn/Article/details/gttpcpnbvk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtzxicnkyw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtbpaptkhe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gttyxkqyoe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzfpsyvr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtehmchzxk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gaohongyu789.top/Article/details/gtqtfvodrh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtyurdvakk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtzoygevsp.html

[N05] 最大公约数
来源：http://dali.cdnleiting.top/Article/details/gtztuhkbeg.html

Py:   math.gcd(a, b)
来源：http://dali.sysykeji.top/Article/details/gtgmbhqupr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gtmobvjaag.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpgvqhav.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtvcxeekcy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daxiang520.top/Article/details/gtalceuaxd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhixingplan.top/Article/details/gtvcgzarfp.html

Ruby: a.gcd(b)
来源：http://dali.jqgfzy.top/Article/details/gtvmjuikqp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sysykeji.top/Article/details/gtawmyjmii.html

[N06] 判断回文字符串
来源：http://dali.zdqjudy.top/Article/details/gtwrpbzyji.html

Py:   s == s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gtfrtyykrh.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gtvxknlucq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdyqgfzn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtygcnnmbs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.c1oappe.top/Article/details/gtkjjcbrgc.html

Go:   // 双指针从两端比较
来源：http://dali.zhoulong.xyz/Article/details/gtwehfhtle.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtnpzjtjhr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gtbttqnjxv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhiwuduotai.top/Article/details/gttcxcoegz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.haohaochexian.top/Article/details/gtoqqygram.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhixingplan.top/Article/details/gthhzohjse.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.0kj1m.cn/Article/details/gtolijkxrq.html

TS:   // 手写 Map<string, number>
来源：http://dali.dashuyun.cn/Article/details/gtvxmcjmog.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gthdjeamjs.html

Go:   // 手写 map[int]int
来源：http://dali.jqgfzy.top/Article/details/gtkjpmlmzw.html

Ruby: // 手写 Hash
来源：http://dali.pycfn.com/Article/details/gthxkjoelv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ydzc1.top/Article/details/gtfopznwzx.html

[N08] 生成全排列
来源：http://dali.nanxinkj.top/Article/details/gtdccwpsll.html

Py:   itertools.permutations(arr)
来源：http://dali.yueranfly.top/Article/details/gtjuyepftt.html

PHP:  // 手写递归交换
来源：http://dali.vqdsnc.cn/Article/details/gtfjqrsbeo.html

JS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtgwzgmhra.html

TS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxttyqvp.html

Java: // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtvmerybnz.html

Go:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtezwthutp.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258888.top/Article/details/gtxjwzkmwo.html

C#:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtkevevlge.html

[N09] 栈与队列
来源：http://dali.tanke756.top/Article/details/gttubuoium.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258.top/Article/details/gtcbrbxsnr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtkrzyiwdt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtpzaffefo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtglwbfazg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gtlyxsvlgr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ybcxt.top/Article/details/gtfgbuyikz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtibmoebch.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ivvv.top/Article/details/gtuwemxxiv.html

[N10] 链表节点定义
来源：http://dali.iojbl.cn/Article/details/gtfmznelwd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyhtmdvq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258888.top/Article/details/gtkqmieeuv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gtlznxvspy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavpowgsh.html

Java: class Node { int v; Node next; }
来源：http://dali.yanxiufei.cn/Article/details/gtyzaqclmu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shangyingyoupin.top/Article/details/gtpnjlsgjg.html


<!-- 参考信息 -->