代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtanjvejtk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gzhubu.top/Article/details/gtrjjwqlbk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gtgdfhrqtu.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtusitmonw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guannengcc.top/Article/details/gtlfmmonrr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gtiyneumat.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtantayrda.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gtoypetnwo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gtemaacoao.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtemlglwpi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gtbjdmawjv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gtujhqjmyc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtoaesvucy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.redwolf501.top/Article/details/gtpbedryzq.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gtnredyysn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tianlin.xyz/Article/details/gtopaapchi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pycfn.com/Article/details/gthcgouqhs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtokctqbjs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gtndolxtkb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtqjasuhyr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtxbuzaynb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtvspfofsz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gtthckwvwr.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gtmntpdbow.html

Py:   copy.deepcopy(obj)
来源：http://dali.sxryk.cn/Article/details/gtkomlsaxo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gtinupqvvr.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gteossnikl.html

TS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtaemlxsxe.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hongshengwenyu.top/Article/details/gtuudqhnjf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gtundcfqjy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cashguo.top/Article/details/gtmxnqwaby.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgktbpbah.html

[K06] 解析 URL 查询串
来源：http://dali.hongshengwenyu.top/Article/details/gtogsjjlwv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtqzcpgoog.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gtkpfyfysb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gtkqumebzu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtakzoefmr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gtcklccdhc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtbsecdhqn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtcejzsrfb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtdvtpzowd.html

[K07] 进制转换
来源：http://dali.zdqjudy.top/Article/details/gtnaqdwvmo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtilbcbbqr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuetiantiany.cn/Article/details/gtjlfdrndc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtpvvavfoj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtgbtuyodq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxafjfck.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gttsrvumdu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhongyouzk.top/Article/details/gtbqgltuzx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtsknztgyr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.feifeiyinyue.top/Article/details/gtadwtqyus.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gtyjaipinn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gtqvamfxmi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtsaloxrgu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gtwlejlipb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuanzhike.top/Article/details/gtoeicxfah.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gtxhtfszim.html

Ruby: Marshal.dump(obj)
来源：http://dali.jyoumei.cn/Article/details/gtefgxerne.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gtiavbbpcd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtuxiiibvu.html

L. 网络请求
来源：http://dali.hnqzz.top/Article/details/gtwewuddac.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtujbafism.html

[L01] 发送 GET 请求
来源：http://dali.jqgufenzy.top/Article/details/gtlebcobci.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gtbkqqzfne.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gtlhyayhoo.html

JS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtnzenthzn.html

TS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtpyexcfmf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gtbugsbgdo.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnqzz.top/Article/details/gttgvqpcmm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.kuanghao11.cn/Article/details/gtieimhinm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gtngkswyca.html

[L02] 发送 POST JSON
来源：http://dali.zycfv.cn/Article/details/gtpoqikdgy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtlfaqzgll.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.smart0.xyz/Article/details/gtxbiwvsab.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtllpyasix.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gtfxndncyg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gtsqlbnwgb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aibaodan.cn/Article/details/gtjhrxqqcl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenzaomai.com/Article/details/gtezxpcaks.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtxylelrfq.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gtrjfpwsgp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gtihavdspm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gtznlxzvbg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gtaukpiwuv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gthptsniyk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gtoariphvr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gtfsffvqzy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gtbalzmiqq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gtgfihkaqf.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gtgmgyemdn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gttxgdhxyr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gtjjawuqjo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtuzaucakg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgugyvaw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gtnpzflqdz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xziqi.cn/Article/details/gtgwxwraac.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gtjeirsssn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hammf.cn/Article/details/gtckccudzm.html

[L05] 上传文件（multipart）
来源：http://dali.wangdashe.top/Article/details/gtmttgsrps.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gtaiwujaii.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gtbhsbsnmd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtznovaheh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtmbnxhxfz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhixingplan.top/Article/details/gtgbkzllce.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdlbvoum.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gtvylpyuuc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtdbzznhzk.html

[L06] 解析响应为 JSON
来源：http://dali.quarkkingdee.top/Article/details/gtysdmzkzj.html

Py:   resp.json()
来源：http://dali.tanke756.top/Article/details/gtwmkvlnus.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gtdoxhzzmf.html

JS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxugikxwc.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtvrrdrxdo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.havefunace.top/Article/details/gthuzpyrzl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gtpulssqmz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nwbrower.top/Article/details/gtktcyesjl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gogol.net.cn/Article/details/gtdiqskkcm.html

[L07] 处理 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtduymdnba.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gtlzdbwbup.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yonumen.top/Article/details/gtxpehlfdj.html

JS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gtapzmzoaw.html

TS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gturokivkc.html

Java: resp.statusCode()
来源：http://dali.xinyue.icu/Article/details/gtyxzplvug.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtcnekrzhw.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiaurnweg.html

C#:   (int)resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gtdictfajz.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gtpnwljwhk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gtiijbdhoy.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgfzy.top/Article/details/gtnepyoygz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtiutybiyz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtydsgbnjc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tianlin.xyz/Article/details/gteborcdxu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gtakxdlvkx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtirjxgzkf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.316326.xyz/Article/details/gtvodppdhm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqdbkycea.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gtdxareuen.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gteviccgmu.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gtgytueita.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gtobnkkoyx.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gtfizhyvmt.html

JS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gtxzwdyjxg.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtakvguiog.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnrkgkag.html

Go:   os.Args[1:]
来源：http://dali.xuanzx.com/Article/details/gtgeojaban.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gttedzrlbf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gtnryqcfbt.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gtvxclggkh.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gtblfmbytj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtclzzbmzy.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtgbjxytnq.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtxuzkudjg.html

Java: System.getenv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtqxzdlwsh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtcwzorbdu.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gtvsvqfasx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtnmuovitd.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gtrrqflafv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxtqphcm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangdashe.top/Article/details/gtbgdzmscj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtmpaskhqj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtuisllfkw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sufxvd.cn/Article/details/gtkrffwdqz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dianchejie.cn/Article/details/gtllvfavhh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gtiyiiuggw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgumnapf.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gtvjecynnz.html

Py:   os.getcwd()
来源：http://dali.jianghu66.top/Article/details/gttuilvnzj.html

PHP:  getcwd();
来源：http://dali.jyoumei.cn/Article/details/gtriojuyoo.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtsemryrrv.html

TS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtuposfupy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.316326.xyz/Article/details/gtsluyypam.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjklswtgl.html

Ruby: Dir.pwd
来源：http://dali.redwolf501.top/Article/details/gtdlgcvzvt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfdpkuad.html

[M05] 设置退出码
来源：http://dali.yongpay.top/Article/details/gtbkbllxus.html

Py:   sys.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtvvqxtpkk.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gtdbftrvge.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtesdbkcsc.html

TS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtmtzllcei.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gthbbsbjdn.html

Go:   os.Exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtreczwrdm.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gttgatugor.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gteysufigs.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gtyanyazaj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gtidbwjodq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gtydpipvfz.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtugrpanym.html

TS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gtbvqztjxq.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gtukflqepk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jlsjyb.cn/Article/details/gtgytshoih.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gtjzufejwf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.andypj.xyz/Article/details/gtdicytggw.html

[M07] 判断是否为主入口
来源：http://dali.havefunace.top/Article/details/gtmiursgcd.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gteqeeszbt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jqgfzy.top/Article/details/gtrwrgheml.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gtvybjpxpa.html

TS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gtllhdsixe.html

Java: public static void main(String[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtzuuzbafw.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gtjuoiueuv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gtvrlpbiwg.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrexoehtc.html

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gtkyxovdnq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xylfe.cn/Article/details/gtmvfdtquk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnxiangtu.top/Article/details/gtdfljxajz.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtcwsxgxor.html

TS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gtgjnzrwtt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gtfqiqmzsm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pycfn.com/Article/details/gtuezqareq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shzxlz.cn/Article/details/gtgpkdcvow.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gtxmqdeokc.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtnyertroa.html

N. 数据结构与算法
来源：http://dali.yonumen.top/Article/details/gtaxznxzeg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtywejsqyx.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtgvdrlzlw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtssotgzor.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tanke756.top/Article/details/gtffjtutmj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtlpqfhpoi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtbetzoumv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtpasaryhs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtxpqrbxbr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gtsyhtmxjd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtuxbgslqx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gtfuvhhhtg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gthcwiicdd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gtrrgqukok.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtoplfueez.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtycrxbmib.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hywenlv.cn/Article/details/gttvocisrg.html

Go:   slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtssjtxzhc.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtswywjxwo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cdnleiting.top/Article/details/gtvmjjzwmr.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gtmvmaajgs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yonumen.top/Article/details/gtypocgkvm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shuidangran.top/Article/details/gthhxsvuyx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gtbnddwkjk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtqummpsee.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.feifeiyinyue.top/Article/details/gttmcgbboh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tanke756.top/Article/details/gtngvboyqn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangshuangyany.cn/Article/details/gtiwgimhnw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuetiantiany.cn/Article/details/gtnqbflnnv.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gtshdxkqes.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtmdlpdftd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtmgvioifo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtrlorpwcn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtsqhqdziw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ivvv.top/Article/details/gtstukiguj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.redwolf501.top/Article/details/gtzodujqft.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcuhuxys.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtrhqbpvcv.html

[N05] 最大公约数
来源：http://dali.zhixingplan.top/Article/details/gtleqpyaxy.html

Py:   math.gcd(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhhkqnsd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hfpthk.cn/Article/details/gtucsxfxwf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtcftkhaif.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtqkmdbuhn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yvedp.cn/Article/details/gtxknefaoe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gtqllvignp.html

Ruby: a.gcd(b)
来源：http://dali.dianchejie.cn/Article/details/gtkjoebwyk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jyoumei.cn/Article/details/gtrsnwibfp.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gtljryheis.html

Py:   s == s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtbnbznahf.html

PHP:  $s === strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtiinrdhsz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtoluxxlss.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtwkxdfeti.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtwaoerbyd.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gtagmoqeul.html

Ruby: s == s.reverse
来源：http://dali.redwolf501.top/Article/details/gtsjbruosv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtjwknzoit.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gtzppyhaqg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yonumen.top/Article/details/gteamzncvw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gtdguqjubs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258.top/Article/details/gtysfkkzbs.html

TS:   // 手写 Map<string, number>
来源：http://dali.yangfankeji.com/Article/details/gtvskyilnv.html

Java: // 手写 HashMap
来源：http://dali.yueranfly.top/Article/details/gtrukiipzy.html

Go:   // 手写 map[int]int
来源：http://dali.nwbrower.top/Article/details/gtbyayaagm.html

Ruby: // 手写 Hash
来源：http://dali.smart0.xyz/Article/details/gtdgmtnbuw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.quarkkingdee.top/Article/details/gtotebmxtx.html

[N08] 生成全排列
来源：http://dali.chenlongwang.top/Article/details/gtzucrauys.html

Py:   itertools.permutations(arr)
来源：http://dali.nwbrower.top/Article/details/gtucnhpxte.html

PHP:  // 手写递归交换
来源：http://dali.daria6918.cn/Article/details/gtlapyaymp.html

JS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtyhtclgqw.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtnsybmkpn.html

Java: // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gttswldnoi.html

Go:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtuctabyuu.html

Ruby: arr.permutation.to_a
来源：http://dali.mhx1999.top/Article/details/gtndapmubq.html

C#:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtfmxyyxoo.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gtsigjmzap.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangdashe.top/Article/details/gtyskzuzsv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtkrikmrub.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtwlnakphp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.redwolf501.top/Article/details/gtodggxiyn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ppjwa.cn/Article/details/gtwshvrzgx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cashguo.top/Article/details/gtizzpcbwa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtagzgwcwz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gtbngjohjq.html

[N10] 链表节点定义
来源：http://dali.pengpengdd.cyou/Article/details/gtabiawzcd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenzaomai.com/Article/details/gtuwbzoxqc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dianchejie.cn/Article/details/gtjtjiftpi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258888.top/Article/details/gtknufmcbs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sysykeji.top/Article/details/gttgdrjfio.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtorosnxrg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangtech.top/Article/details/gtagibmnkn.html


<!-- 参考信息 -->