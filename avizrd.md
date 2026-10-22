代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtrfwrjsba.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tanke756.top/Article/details/gtsmncamuh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gtqotvqlkk.html

Ruby: JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtameknelc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yanxiufei.cn/Article/details/gtpllejdme.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gtntyjxpmw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gtobgojqkk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtpxohccxu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtjyrulrsl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gtquxwmwlo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dashuyun.cn/Article/details/gtvivcjeng.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.daria6918.cn/Article/details/gtbakmnwiv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sweek.top/Article/details/gtkzfualth.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtampqrvub.html

[K04] 读取 JSON 文件
来源：http://dali.chenlongwang.top/Article/details/gtcyskbyzv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gtexmyuzfb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gtvpncjraq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtptuclwht.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtcykeimwk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtddvicivz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gtyafeuysp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fengsongda.top/Article/details/gteqbkawzl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtzmwecgse.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gtrdifzoib.html

Py:   copy.deepcopy(obj)
来源：http://dali.snrcjt.cn/Article/details/gtyuviyttc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hysaishi.cn/Article/details/gtergnfqne.html

JS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtrwpuifzn.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gtgpjepxgs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gtuvjwyfup.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gtqgouhgqi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gtkgcojtpr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgufenzy.top/Article/details/gtevvzxsse.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gtihduxetd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gteqtewoxu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dashuyun.cn/Article/details/gtgeustusf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtbxcmydjo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gtjzryqpyi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjolfzqo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gtrpjhpnnj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtzeirxoha.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gthkxrzobn.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gtboyainmr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtkanjrupp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gtxubwiocx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtzgojvhei.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtpxteqvwp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtbpzyaazn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tian-w.cn/Article/details/gtytwlrsei.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcgfjrip.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtrhzserqt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gtrrlmvtok.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gtypkkgkwz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jyoumei.cn/Article/details/gtfpyirboh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtbjvsbzrc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gteexygrfm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xinyue.icu/Article/details/gtydldufkp.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gtdhouaalx.html

Ruby: Marshal.dump(obj)
来源：http://dali.havefunace.top/Article/details/gtrymeqhfp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gtxgmngllk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmpbwylht.html

L. 网络请求
来源：http://dali.hongshengwenyu.top/Article/details/gtcgvtkelq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtepthfimg.html

[L01] 发送 GET 请求
来源：http://dali.0kj1m.cn/Article/details/gtyfadmpnq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.vqdsnc.cn/Article/details/gttodraziw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jianghu66.top/Article/details/gtpdgfbdmm.html

JS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gtclbrggrq.html

TS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtuzuypnrl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gtigcneljy.html

Go:   resp, err := http.Get(url)
来源：http://dali.nwbrower.top/Article/details/gtrqfxnudv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jiagoushi.top/Article/details/gtqsgchhmb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hysaishi.cn/Article/details/gtirqertoc.html

[L02] 发送 POST JSON
来源：http://dali.fengsongda.top/Article/details/gtnlzkotzj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtgllmolxy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xylfe.cn/Article/details/gtnzervhuw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gthjhbhgem.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gtkyevhyjc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zdqjudy.top/Article/details/gtxbcwzule.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.feifeiyinyue.top/Article/details/gtyiosgemb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sweek.top/Article/details/gteqpukvqv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gtvixjstgx.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gtyxbfsgke.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hongshengwenyu.top/Article/details/gtyrfrwlsk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtvhcznuzp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gtpmtzvbge.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtqokdmvrt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gtvfawolwh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gtxuaaqcwm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gtlaqyuvfr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gthewoyaac.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gtwrfwlqaj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgufenzy.top/Article/details/gttdoldxmk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuanzx.com/Article/details/gtstyahesc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtyhwroikg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtmefljnng.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.smart0.xyz/Article/details/gtosxrynzy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gtzlilydgi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.meibo888.top/Article/details/gtupozouhb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gtngamzuqh.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gtreorzvfr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pycfn.com/Article/details/gtrqqrxuhz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.9152youxi.cn/Article/details/gttzjjiike.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gtesgiqsgg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gtzvxahrwj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.redwolf501.top/Article/details/gtgyrvdqzb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sufxvd.cn/Article/details/gtufaqczde.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jianghu66.top/Article/details/gtkqhkttlq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258.top/Article/details/gtuztbztxo.html

[L06] 解析响应为 JSON
来源：http://dali.zhixingplan.top/Article/details/gtiibrpfll.html

Py:   resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtjwvksjgv.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gtuxfabgnd.html

JS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gtdougtrol.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtqyaghvsb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtsuzdpiel.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sxryk.cn/Article/details/gtvrnkoqed.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhongyouzk.top/Article/details/gtmarcwape.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtatengedc.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtfdpwonvo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258.top/Article/details/gtbjoceqnl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gtghjvigpt.html

JS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gteqquiyir.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtebuhwbgg.html

Java: resp.statusCode()
来源：http://dali.yvedp.cn/Article/details/gtnbsiguus.html

Go:   resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtkypprcqb.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gtmfifmeug.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtopbrpczv.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gtanykrcod.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cheryme.top/Article/details/gtvoxxgkbn.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenjidiqi.icu/Article/details/gtylorxghq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyihujmd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtncdnuvmh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodfpjmat.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gtrrbtxoen.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shuidangran.top/Article/details/gtuhusdbvn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sysykeji.top/Article/details/gtgbownvqp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfquhsqrm.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gtcacgzdto.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjngucecs.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gtyfbwpuea.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtnrjkfqjj.html

PHP:  $argv;  $argc;
来源：http://dali.guowangkeji.top/Article/details/gttlgmwemo.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtgtjxdsrx.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtfocryblc.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtcutzkmsw.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gtxnnpjbvr.html

Ruby: ARGV
来源：http://dali.jlsjyb.cn/Article/details/gtncagsclk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtznzbvxag.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gttxiuugmw.html

Py:   os.environ.get("HOME")
来源：http://dali.fengsongda.top/Article/details/gtgvagkqvp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtooyshgmv.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtobukpqdk.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtyowqvdoe.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtavirksgt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtxnsoxodx.html

Ruby: ENV["HOME"]
来源：http://dali.guannengcc.top/Article/details/gtwzeucjkr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtmvojmsho.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvkqkbhe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtipqzkuyf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gterfsrptc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gtrzavmylt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtvydbqvwa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gtyqgepyrj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhixingplan.top/Article/details/gtvocxtfdr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dashuyun.cn/Article/details/gtuvibbopl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.smart0.xyz/Article/details/gtuvnxzbap.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gtmrsadjyj.html

Py:   os.getcwd()
来源：http://dali.mhx1999.top/Article/details/gtduucuisy.html

PHP:  getcwd();
来源：http://dali.shuidangran.top/Article/details/gtluyppnux.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtgfxhwbco.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gtphnykmbi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gtrcuvwlgm.html

Go:   os.Getwd()
来源：http://dali.sxryk.cn/Article/details/gtkpduprto.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gtrhagvnqk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gtebkjaooi.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gtkazbjyyv.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtbvxcoowi.html

PHP:  exit(1);
来源：http://dali.daxiang520.top/Article/details/gtdeqsskew.html

JS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtgxkdserc.html

TS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtjldavyyg.html

Java: System.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtrvekyqud.html

Go:   os.Exit(1)
来源：http://dali.aizwys.cn/Article/details/gtkqgmhmiy.html

Ruby: exit 1
来源：http://dali.snrcjt.cn/Article/details/gtdxejqvua.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hfpthk.cn/Article/details/gtofdowihn.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gtkgysuiwu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtpodtvkjt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigfzy.top/Article/details/gtgclfwypy.html

JS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtyzyxrpde.html

TS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtlargvqpd.html

Java: System.err.println("err")
来源：http://dali.havefunace.top/Article/details/gtesqcukim.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gtwmxvyryj.html

Ruby: warn "err"
来源：http://dali.yonumen.top/Article/details/gtpqlyfaco.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gtirkjxaot.html

[M07] 判断是否为主入口
来源：http://dali.yonumen.top/Article/details/gtobqmyogo.html

Py:   if __name__ == "__main__":
来源：http://dali.iojbl.cn/Article/details/gtdtetjhpb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhengqikj.top/Article/details/gtiarnjxiv.html

JS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtxuzzojpw.html

TS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gtznuykzeb.html

Java: public static void main(String[] args)
来源：http://dali.sufxvd.cn/Article/details/gtcyqbrjpr.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gtcjvcqpxg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jianghu66.top/Article/details/gtgosfsmxq.html

C#:   static void Main(string[] args)
来源：http://dali.yueranfly.top/Article/details/gtyrjopsdx.html

[M08] 获取系统与运行时信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggunqnaj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxinkj.top/Article/details/gtgvifctzc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gtmazmpeqj.html

JS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtqpgrcscn.html

TS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gteekpjvnk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yueranfly.top/Article/details/gtyzhdytzt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnqzz.top/Article/details/gtsfyhgnol.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cqqwz.cn/Article/details/gtwnencfwm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhixingplan.top/Article/details/gtamdfryqy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwoijlacx.html

N. 数据结构与算法
来源：http://dali.pengpengdd.cyou/Article/details/gtbeyvvbai.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtwwfmlkbi.html

[N01] 二分查找（有序数组）
来源：http://dali.svipenyu.cn/Article/details/gtwogqndfv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtpnnyswhr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yonumen.top/Article/details/gtkqtvmvtf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gttipdvvpg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtvvelvtma.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gtmaqjsmrd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtvsmwhbya.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zdqjudy.top/Article/details/gtfqcoqzpb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtycaozxwq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cqqwz.cn/Article/details/gtwxgtmorb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtgtmnafcb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtvqyzxypz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtdhnzepyn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtcnnwtwhb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigfzy.top/Article/details/gtenyacmfy.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtsgrqzxih.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gtxvqyvlzb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gtjrdyjfnd.html

[N03] 快速排序（分治示例）
来源：http://dali.nwbrower.top/Article/details/gtcrqvwtts.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtieqxjbqo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gtxagefdlj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtflzikxsa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtiwddrjnh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtalmwzugc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.316326.xyz/Article/details/gtipeshxjc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gtyzpxyjsl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hysaishi.cn/Article/details/gtlzipxzqy.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gteazphiwf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtuptoyqtd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtahzqrkiu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gteigxyjil.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtynistagf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtwxcmloas.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhoulong.xyz/Article/details/gtjlzgxfqq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtvdkpeqqg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtohqswgyl.html

[N05] 最大公约数
来源：http://dali.9152youxi.cn/Article/details/gtfgcmhlfb.html

Py:   math.gcd(a, b)
来源：http://dali.iojbl.cn/Article/details/gthifcztkt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtpvlukssk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtfbdtoujw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtecobeern.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwdmefrh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhongyouzk.top/Article/details/gtkipljoqw.html

Ruby: a.gcd(b)
来源：http://dali.haohaochexian.top/Article/details/gtubscgjic.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258.top/Article/details/gtsvzfeaml.html

[N06] 判断回文字符串
来源：http://dali.ehwqpu.com/Article/details/gtfiobeyoc.html

Py:   s == s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtvhimibmj.html

PHP:  $s === strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gtkanfngay.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtzturkrhb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgycbnggk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fengsongda.top/Article/details/gtgvnekzbf.html

Go:   // 双指针从两端比较
来源：http://dali.cashguo.top/Article/details/gttenqewpb.html

Ruby: s == s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtztljecub.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtpktbrlgw.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gtlcneppwr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fengsongda.top/Article/details/gtqfxkjffg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhoulong.xyz/Article/details/gtqwoqpzfr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gogol.net.cn/Article/details/gttfnysyzg.html

TS:   // 手写 Map<string, number>
来源：http://dali.yangfankeji.com/Article/details/gtsquggzpa.html

Java: // 手写 HashMap
来源：http://dali.gzhubu.top/Article/details/gtlxtdurdz.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigfzy.top/Article/details/gtypafetpt.html

Ruby: // 手写 Hash
来源：http://dali.jlsjyb.cn/Article/details/gttfsvvgla.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cdnleiting.top/Article/details/gtyxrzwiyp.html

[N08] 生成全排列
来源：http://dali.nwbrower.top/Article/details/gtvtrblopu.html

Py:   itertools.permutations(arr)
来源：http://dali.tanke756.top/Article/details/gtsitubmdr.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gtdmhbmqbk.html

JS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtlztfnbmb.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtabyhdqzz.html

Java: // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gttocbevdf.html

Go:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtwynwniur.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gtsanjkidh.html

C#:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtulhdmhat.html

[N09] 栈与队列
来源：http://dali.hammf.cn/Article/details/gthzpoinyb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtlalicnpl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtitlyfgad.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtxushdxqe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ppjwa.cn/Article/details/gtlshptwxd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtmupoxbak.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.kuanghao11.cn/Article/details/gtpycoisdy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gthiubkxhr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daria6918.cn/Article/details/gtadylkptd.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gtuybpzaqh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.birdmap.top/Article/details/gtjydhkavd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gtqibemiqe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtbpahgb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigufen.top/Article/details/gthxsuwnne.html

Java: class Node { int v; Node next; }
来源：http://dali.hfpthk.cn/Article/details/gtvulohujt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.redwolf501.top/Article/details/gtdiwbtwvp.html


<!-- 参考信息 -->