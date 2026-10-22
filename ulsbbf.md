代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xinyue.icu/Article/details/gtvxywdsyz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ehwqpu.com/Article/details/gtjjeroiyi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtnirxlzbk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gtezdcsllm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtodjrflry.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtnwzjjsmj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sweek.top/Article/details/gtwioljnpg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shuidangran.top/Article/details/gtbnkjomls.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gttfycvibl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsfbrawr.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gtdkpwzskb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gtsnmowbsa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.bjfxy.top/Article/details/gtquaktwau.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gthvoqstsn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtjpzupvbl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtbndaysks.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtxpfyjaue.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gtqembrjow.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gtctzopejd.html

[K05] 深拷贝对象
来源：http://dali.xuanzx.com/Article/details/gtdxhcemuo.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtjqpzpdag.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nwbrower.top/Article/details/gtolxayxrm.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtriwnzzul.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gteuypuewc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ivvv.top/Article/details/gtriutnnrs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gtvevzjlye.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tianlin.xyz/Article/details/gtqrwoldyi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtsjncpy.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gtcskhdhit.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gtmzempebe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.smart0.xyz/Article/details/gtuwpnjdtv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gtceubxxas.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtvcaymgxg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gtswmewrak.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtgukibruw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtteicenew.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtyhlwccyk.html

[K07] 进制转换
来源：http://dali.chenjidiqi.icu/Article/details/gtfmazbfyl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtnxdlsmku.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuanzhike.top/Article/details/gtckqvdhel.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtguvnqvth.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtskdeuowe.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtrndwxrlw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gtfgwcddsb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvyqicpz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtvcszeufy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnqzz.top/Article/details/gtiwttmihb.html

Py:   pickle.dumps(obj)
来源：http://dali.jianghu66.top/Article/details/gtuepkjufw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tianlin.xyz/Article/details/gtwruiuuyc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gtcvzktgou.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gtzsgyucdz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gtxxwncuxy.html

Go:   encoding/gob
来源：http://dali.sxryk.cn/Article/details/gtwocvslfb.html

Ruby: Marshal.dump(obj)
来源：http://dali.tianlin.xyz/Article/details/gtstxaizwg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gtlzqrtdtc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtkbsyiozt.html

L. 网络请求
来源：http://dali.dashuyun.cn/Article/details/gthzkvdvzw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtwdjkcpph.html

[L01] 发送 GET 请求
来源：http://dali.ydzc1.top/Article/details/gtcelzwxei.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gtzylverfc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gttjrdfqvn.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtmxqkikod.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gthletxnsq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gtbcyktrtx.html

Go:   resp, err := http.Get(url)
来源：http://dali.shzxlz.cn/Article/details/gthixxumsm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.9152youxi.cn/Article/details/gtmtjmsbcu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtuqicjqxn.html

[L02] 发送 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtzmjzekfh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ydzc1.top/Article/details/gtmghvhirf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gzhubu.top/Article/details/gtifkeygnm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtnhzturtu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gtbyxtvxqt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gtmoeiylzs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gtauepzibn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gtsgaiqblk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.snrcjt.cn/Article/details/gtmyismnrh.html

[L03] 设置自定义请求头
来源：http://dali.ydzc1.top/Article/details/gtrwcyylvy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yanxiufei.cn/Article/details/gtawxumkhd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gtosorjmgg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gthfdvsiuw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtsfttwyoj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gtavpkhxbv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcfoxsps.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xylfe.cn/Article/details/gtjhhvayla.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gtobrinhtc.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gtgtaedfbs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gtkcolbfxk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnqzz.top/Article/details/gttpdyxcjf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtborhwawe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtdvzwunau.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gtvcndyeho.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gtccywbobe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sxryk.cn/Article/details/gtxnluaqcb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gtpmmgkwfm.html

[L05] 上传文件（multipart）
来源：http://dali.cdnleiting.top/Article/details/gtnasiidda.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhongyouzk.top/Article/details/gtgkileuxw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gthjbnlhmp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtocwydeqp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtvgngyaqh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenzaomai.com/Article/details/gtctvhfegi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gtolvmvhiy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gtvxvkknfl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtaopymapv.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gthxjssbhl.html

Py:   resp.json()
来源：http://dali.smart0.xyz/Article/details/gthummndkm.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gtoomembzn.html

JS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gttnukysgp.html

TS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gtojzmgfit.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gtmmxhxtqa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gtopopdogc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dianchejie.cn/Article/details/gtrfffkvvs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.quarkkingdee.top/Article/details/gtpmdpkhrl.html

[L07] 处理 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gtgtfhtzfc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gtpezasjlk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ydzc1.top/Article/details/gtmctoyqwq.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gttgnurelz.html

TS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gttwrjxsrd.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gtkervvrrs.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtzazeugut.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrzpohza.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtretkbvjp.html

[L08] 并发请求多个地址
来源：http://dali.tian-w.cn/Article/details/gtafgohywf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258.top/Article/details/gtxgdozxtp.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gtxndiqmah.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtuoknivkt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtkuepswos.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gtvdheugxv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shzxlz.cn/Article/details/gtaoxdklse.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yonumen.top/Article/details/gtqcppcjkz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.mhx1999.top/Article/details/gtxlabrftv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqgjmegda.html

M. 命令行 / 进程 / 环境
来源：http://dali.pengpengdd.cyou/Article/details/gtlxllmgys.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtybnburso.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gtlpzfqdgv.html

Py:   sys.argv[1:]
来源：http://dali.yangfankeji.com/Article/details/gtcngcfgsi.html

PHP:  $argv;  $argc;
来源：http://dali.cdnleiting.top/Article/details/gthpdsbqhh.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtbodchvfz.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gthskaffmi.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtjlpkyvme.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gtjvmrjaur.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gtnaevqcem.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gthroiaezp.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gtgswtxwed.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtboxhjqfh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyhhnnyl.html

JS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gtwqjofess.html

TS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gtkwrbnkog.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtmiwaqkdw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtrokcahye.html

Ruby: ENV["HOME"]
来源：http://dali.ydzc1.top/Article/details/gtryrxqvjn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cheryme.top/Article/details/gtuaewxubf.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gtxudpnyuf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gaohongyu789.top/Article/details/gtiwvvtsrw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyrmomme.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtpmljxvwg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugpcdynr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hfpthk.cn/Article/details/gtgmhececk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gtyxsaqxoi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nwbrower.top/Article/details/gtpbnhnkgs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daria6918.cn/Article/details/gtdsmfmtzv.html

[M04] 获取当前工作目录
来源：http://dali.xinyue.icu/Article/details/gtiaeskynq.html

Py:   os.getcwd()
来源：http://dali.haohaochexian.top/Article/details/gtemjzfdaj.html

PHP:  getcwd();
来源：http://dali.nanxinkj.top/Article/details/gtptgqojmb.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtyoxklgmg.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtlyxcsmdu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnauvhos.html

Go:   os.Getwd()
来源：http://dali.hnxiangtu.top/Article/details/gthzxxxmxi.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gtxhzwazut.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cdnleiting.top/Article/details/gtcejiryko.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gtbdjykgdm.html

Py:   sys.exit(1)
来源：http://dali.daria6918.cn/Article/details/gttmpkdyyf.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gttwmeisyk.html

JS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtcmyzvdoa.html

TS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gtwgrspjsc.html

Java: System.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtaihyftem.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gtulguquzf.html

Ruby: exit 1
来源：http://dali.yongpay.top/Article/details/gtmtpjqryt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jiagoushi.top/Article/details/gtkzxlwyur.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gtrfalkbcc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gtuuvsukle.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gtfvmrdmdn.html

JS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtktmewcfh.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtwbhddooh.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gtzygshcaj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yongpay.top/Article/details/gteecwwptc.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gtrplzdful.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gtuqhfaxrf.html

[M07] 判断是否为主入口
来源：http://dali.tianlin.xyz/Article/details/gtzjrzjajx.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gtwmzijhzp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yueranfly.top/Article/details/gtclmrvvha.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gtkaupwjhy.html

TS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtrvjzxiil.html

Java: public static void main(String[] args)
来源：http://dali.xinyue.icu/Article/details/gtuoevzekj.html

Go:   func main()
来源：http://dali.jqgfzy.top/Article/details/gthodkfgot.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pycfn.com/Article/details/gtbmkoccmg.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gtdwclvexj.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gtshcppzob.html

Py:   platform.system();  platform.python_version()
来源：http://dali.redwolf501.top/Article/details/gtlopaldns.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gtmwozusxa.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gttgepwiye.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtwjtreakn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gtaojpuevh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cdnleiting.top/Article/details/gtabvkavve.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gogol.net.cn/Article/details/gtiacjqccp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxinkj.top/Article/details/gthqagmxkx.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtrqamckpl.html

N. 数据结构与算法
来源：http://dali.shuidangran.top/Article/details/gtbnkkfbtv.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtadexytas.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gtgvodrpbb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtdzvageza.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtsmlnbbbo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtwrdjrenb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gtofyftrfe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtgfvnhlyk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gttkrbbtsb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gtejkapvlv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqycenndp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gtpjwwwvps.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gtnjyghgab.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtydpoxqvm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtezmnlrst.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtjtqnvxum.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gtebhsztsn.html

Go:   slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gttlyajfho.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtkqxtsorj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jianghu66.top/Article/details/gtzmuzbhyr.html

[N03] 快速排序（分治示例）
来源：http://dali.ybcxt.top/Article/details/gtbwubklwr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.iojbl.cn/Article/details/gtveakezet.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangtech.top/Article/details/gtorhdincq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtlinfrxde.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtkgrilkzm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtrsfcnjfo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guannengcc.top/Article/details/gtbjybubbr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dashuyun.cn/Article/details/gtnxrwbggk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gtreshrsmy.html

[N04] 斐波那契数列
来源：http://dali.chenjidiqi.icu/Article/details/gtmivorvmw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gtyqbsikzv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtterwardq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtiaxxqukm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtjpmcglyy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258.top/Article/details/gtnriarosg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daria6918.cn/Article/details/gtvcvkyrjg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtqiyoqrwl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtemdmewsv.html

[N05] 最大公约数
来源：http://dali.birdmap.top/Article/details/gtlsobqsnc.html

Py:   math.gcd(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtovuqmawc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gtdnjcmroj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzojqfew.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtxgixccpi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yanxiufei.cn/Article/details/gtijjvbkdc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cucudq.cn/Article/details/gtelzenrtq.html

Ruby: a.gcd(b)
来源：http://dali.dashuyun.cn/Article/details/gtlgvpkjcr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.9152youxi.cn/Article/details/gtoklmhycp.html

[N06] 判断回文字符串
来源：http://dali.hysaishi.cn/Article/details/gtrhrjmvwi.html

Py:   s == s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gtnkxsssao.html

PHP:  $s === strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtwvvcbuhc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtaiprtorn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtgfmcohet.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysrfngqi.html

Go:   // 双指针从两端比较
来源：http://dali.chenjidiqi.icu/Article/details/gtbrsgltec.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtsqiqapsf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtjptywsgo.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gthyccratd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.smart0.xyz/Article/details/gtaiamuewf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258.top/Article/details/gtznkttvyg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnxiangtu.top/Article/details/gtfmpoiwil.html

TS:   // 手写 Map<string, number>
来源：http://dali.redwolf501.top/Article/details/gtwltxwrfu.html

Java: // 手写 HashMap
来源：http://dali.snrcjt.cn/Article/details/gtnvfmnnlk.html

Go:   // 手写 map[int]int
来源：http://dali.cheryme.top/Article/details/gtnebusaok.html

Ruby: // 手写 Hash
来源：http://dali.jlsjyb.cn/Article/details/gtxqmxvgaq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daria6918.cn/Article/details/gtqiizqqme.html

[N08] 生成全排列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwncxmyzw.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gtxukkintb.html

PHP:  // 手写递归交换
来源：http://dali.guannengcc.top/Article/details/gtdguxyzla.html

JS:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtdtcmgywp.html

TS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtpnbrnuyw.html

Java: // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrncwxed.html

Go:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtfvuufosf.html

Ruby: arr.permutation.to_a
来源：http://dali.sweek.top/Article/details/gtsyvaeaiq.html

C#:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtaefzzbdl.html

[N09] 栈与队列
来源：http://dali.0kj1m.cn/Article/details/gtqxoqwpxo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhixingplan.top/Article/details/gtycukokvx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtsouzucmz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gtorxcbmha.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gtzpojidxa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gtauzzvhlz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tian-w.cn/Article/details/gtkfmwmfay.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtladvusff.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenlongwang.top/Article/details/gtetmlsray.html

[N10] 链表节点定义
来源：http://dali.shangyingyoupin.top/Article/details/gtxrwegqbf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.svipenyu.cn/Article/details/gtxcjxeagp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtnrjynr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdegiben.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hysaishi.cn/Article/details/gtatkofofx.html

Java: class Node { int v; Node next; }
来源：http://dali.ybcxt.top/Article/details/gtzoonnrrj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guowangkeji.top/Article/details/gtstztdbxy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gtwpmseqvb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ydzc1.top/Article/details/gtyhmhrfnc.html

[N11] 二叉树中序遍历
来源：http://dali.c1oappe.top/Article/details/gtuldjmaks.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dashuyun.cn/Article/details/gtatsqojqv.html


<!-- 参考信息 -->