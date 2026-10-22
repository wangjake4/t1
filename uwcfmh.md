代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yongpay.top/Article/details/gtovcrmcma.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yongpay.top/Article/details/gtyygtfsov.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gtchqknvgq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cucudq.cn/Article/details/gtdfvguaxb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gtjgvlbscu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtnmyyiuob.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtazucuw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gthumsamip.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gtojmuqzbv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtjkbizdwh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtliodktao.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gtifqgkqxo.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gtnzzmzpes.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ybcxt.top/Article/details/gtlrvxjqcx.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtaehtjdwb.html

TS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gtangrkjlz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fzhhl.top/Article/details/gtkomlhvyc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.feifeiyinyue.top/Article/details/gtqvqaptub.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dianchejie.cn/Article/details/gtlhlbysud.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.iojbl.cn/Article/details/gtftgehuoy.html

[K06] 解析 URL 查询串
来源：http://dali.hywenlv.cn/Article/details/gttlgtckut.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cashguo.top/Article/details/gtpojsbhmk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdsgllcc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtgqkzfspe.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gtbaxruvuy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgoqngtt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtaswzxerh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtckbkznfj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtuglkanjr.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gtjxgnpdze.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gthvvqhlii.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gttozgunda.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtklpyipce.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtxjdpnsbp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtimozdiux.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenzaomai.com/Article/details/gtchuobxfp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthicwmyvi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtnndkxqzp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tanke756.top/Article/details/gtamoowpmv.html

Py:   pickle.dumps(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtpmjpblsj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.316326.xyz/Article/details/gtctidzlfr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtftpacwjx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtfdkkjjwq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sysykeji.top/Article/details/gtocaawsun.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gtdsihlvgs.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258888.top/Article/details/gtamohtfhu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtrphrnzai.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtrryduehu.html

L. 网络请求
来源：http://dali.xuanzx.com/Article/details/gtaaspnfpn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtliyelcue.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gtlsejxbaq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenjidiqi.icu/Article/details/gtwnstnkor.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gtrkisiryv.html

JS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtapuwngyl.html

TS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gtvlbsufwd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sweek.top/Article/details/gtwpdqgfmn.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gtvwmhoyyr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gtmnvtvwop.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gtcaunygfr.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtcbswogfd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gtwhifqden.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yongpay.top/Article/details/gtzmwhqsjx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gtzwvxvtjg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtqmhkcpsh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gthdkjdguk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258.top/Article/details/gtmmeyjwdg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gtaovuktkh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdisrdpbq.html

[L03] 设置自定义请求头
来源：http://dali.shuidangran.top/Article/details/gtczrvtjrd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gtcefdouqj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sysykeji.top/Article/details/gtoblxnnhz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xylfe.cn/Article/details/gtpipcveaf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gtazyzawhl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cucudq.cn/Article/details/gttimbqixk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gtyhddszaf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cqqwz.cn/Article/details/gtvtmvxfuk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtmpmoeqsh.html

[L04] 设置超时
来源：http://dali.nwbrower.top/Article/details/gtbnwingnq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jianghu66.top/Article/details/gtuwxbvyyh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gtvifqnjft.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtzkrvuirs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gtglbxexyc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.redwolf501.top/Article/details/gtitjmdlwy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gtmeuoircr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gtrnzzbvai.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gtnkydibxn.html

[L05] 上传文件（multipart）
来源：http://dali.guannengcc.top/Article/details/gttegsewmn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gtfhgoeowt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gtjajhdknx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtdrkosusa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtpjvvnuqz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.vqdsnc.cn/Article/details/gtrydsqjga.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenjidiqi.icu/Article/details/gtnetsbqjn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zdqjudy.top/Article/details/gtdlugknwi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pycfn.com/Article/details/gtzqjnqjyc.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtmufbptcz.html

Py:   resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtevbxqgve.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gtzshmgknw.html

JS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtxaspgdxr.html

TS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtfjgcnsvr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ydzc1.top/Article/details/gtaqzodyzk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fzhhl.top/Article/details/gtbskyucvw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.c1oappe.top/Article/details/gtqvzevsks.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenlongwang.top/Article/details/gtcgpgpvat.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtzddvmnem.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gtxfrigkaa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnqzz.top/Article/details/gtqucckdtt.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtcpjzvcpl.html

TS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtkldairdb.html

Java: resp.statusCode()
来源：http://dali.chenlongwang.top/Article/details/gtggohthbu.html

Go:   resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtngcfnelb.html

Ruby: resp.code.to_i
来源：http://dali.aizwys.cn/Article/details/gtxcwmecid.html

C#:   (int)resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gtfrirjxqo.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gtabfqltne.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gtaomtserv.html

PHP:  curl_multi_init() 系列
来源：http://dali.cqqwz.cn/Article/details/gtfeccxvub.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtigrwwpdi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtqhqbycoo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gtonqytjfz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gtvkeozmkn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aibaodan.cn/Article/details/gtqygemaah.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dashuyun.cn/Article/details/gtzuskpuot.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtmrprtvir.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtnellrmhp.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtexpasglw.html

[M01] 读取命令行参数
来源：http://dali.yj202588.top/Article/details/gthejvgdhi.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gtgciuhecs.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gtvczaeeks.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtbvsigcjx.html

TS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtecczwady.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtjiyixmzm.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gtrxjjigvy.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujonafve.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtmyconnsk.html

[M02] 读取环境变量
来源：http://dali.fengsongda.top/Article/details/gtjnkpwjdl.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtkgmjohkq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwcelrjq.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtzuznemgd.html

TS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gtmgwqpnos.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtailrmjnf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gttyzjqmox.html

Ruby: ENV["HOME"]
来源：http://dali.yonumen.top/Article/details/gttmecdmnf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fzhhl.top/Article/details/gtsajoxmfu.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gtshbywtnr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhongyouzk.top/Article/details/gtmwkidvfz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuanzhike.top/Article/details/gtlugurlmt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtoyjalchi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtbyemeffh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.snrcjt.cn/Article/details/gtuzenezwc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gtaexdmmba.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cucudq.cn/Article/details/gtspalzyus.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yongpay.top/Article/details/gtlyjuoual.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvdribgt.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gtwrmyeasu.html

PHP:  getcwd();
来源：http://dali.cucudq.cn/Article/details/gtkjhbmios.html

JS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtloejbavr.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtxgaemotm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxrppogx.html

Go:   os.Getwd()
来源：http://dali.chenlongwang.top/Article/details/gtlqrssuaa.html

Ruby: Dir.pwd
来源：http://dali.xinyue.icu/Article/details/gtsoetuvaw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gtahtrvyyh.html

[M05] 设置退出码
来源：http://dali.andypj.xyz/Article/details/gtmccfltzu.html

Py:   sys.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtnoqzhgfm.html

PHP:  exit(1);
来源：http://dali.mhx1999.top/Article/details/gtxjkwxdgc.html

JS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtmbaiugfc.html

TS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gtezfeczev.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtugfymkxp.html

Go:   os.Exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtybcpqkwq.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gtrhzqnisz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gtoxxihhxg.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gtoekdkksp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwfxtxrb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ivvv.top/Article/details/gtqqqhyhgu.html

JS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtefxuntgi.html

TS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gtscuzfimt.html

Java: System.err.println("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrvlmavk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pengpengdd.cyou/Article/details/gtqekwntaz.html

Ruby: warn "err"
来源：http://dali.yuxming.cn/Article/details/gtqsrtijej.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sweek.top/Article/details/gtwmcqnvnk.html

[M07] 判断是否为主入口
来源：http://dali.zhongyouzk.top/Article/details/gtzcgfumcv.html

Py:   if __name__ == "__main__":
来源：http://dali.hammf.cn/Article/details/gtlkolvafu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj202588.top/Article/details/gtlyiujwhn.html

JS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtlqgrkjkh.html

TS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtswvajwad.html

Java: public static void main(String[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhksyshl.html

Go:   func main()
来源：http://dali.nwbrower.top/Article/details/gtegciahrd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgfzy.top/Article/details/gtonippfyg.html

C#:   static void Main(string[] args)
来源：http://dali.ybcxt.top/Article/details/gtbqyjngrp.html

[M08] 获取系统与运行时信息
来源：http://dali.tian-w.cn/Article/details/gtzxovpqpr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hongshengwenyu.top/Article/details/gtaoejmguo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gthdaupzxt.html

JS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gttxpfrhpe.html

TS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gtfhtruvys.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgufenzy.top/Article/details/gtgnimmvob.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuanzx.com/Article/details/gthufgmhjp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuetiantiany.cn/Article/details/gtuqnibfzr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gtjzdmrwad.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtlpmvxjed.html

N. 数据结构与算法
来源：http://dali.vqdsnc.cn/Article/details/gtsddlyoms.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gttkrfweea.html

[N01] 二分查找（有序数组）
来源：http://dali.zhengqikj.top/Article/details/gtgovrzilr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtlqkfkika.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtclnbdyca.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtqsbcqlqz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtmhzudhdq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gteaqrgtgw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtuubduovu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tanke756.top/Article/details/gtwrqwvslm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtgrhqxqym.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hammf.cn/Article/details/gttbyfsfoo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtgyltvova.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gthungbegp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtxrlauhgj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtppbjoigp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nwbrower.top/Article/details/gtybgpuppx.html

Go:   slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtyhtqwiet.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtfwzbyugw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hysaishi.cn/Article/details/gtvptfqsyg.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gtmgjzuzfw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cashguo.top/Article/details/gtvgbfloyb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenzaomai.com/Article/details/gtxyzykroo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gtrzvarqbt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgvgbnnn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gtaurrgcin.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.kuanghao11.cn/Article/details/gtvesgzvtj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ppjwa.cn/Article/details/gttunedkxa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gtwghwgevw.html

[N04] 斐波那契数列
来源：http://dali.c1oappe.top/Article/details/gtfqcktqud.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtgosxmzny.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtmvqzlxnd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtymqrwelq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gticyjhiss.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtsdlkccts.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgufenzy.top/Article/details/gtejzclagx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtirmykgeb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtxpzntwvs.html

[N05] 最大公约数
来源：http://dali.xylfe.cn/Article/details/gtzozpgdzb.html

Py:   math.gcd(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtwygrmggt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cqqwz.cn/Article/details/gtvaxtbsne.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gtioekjfyp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtdajhhtph.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gtdfwcmobz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cqqwz.cn/Article/details/gttoajrveb.html

Ruby: a.gcd(b)
来源：http://dali.meibo888.top/Article/details/gtwfprxoru.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cucudq.cn/Article/details/gtdgwyjcok.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gtveguwonp.html

Py:   s == s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtfqirjitt.html

PHP:  $s === strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtkfsyuvwu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gteuvfhrbs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtlqmviuao.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.bjfxy.top/Article/details/gtggqwemdt.html

Go:   // 双指针从两端比较
来源：http://dali.aizwys.cn/Article/details/gtkduodwoh.html

Ruby: s == s.reverse
来源：http://dali.yangfankeji.com/Article/details/gttwmpvcau.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gtkxoxtqnh.html

[N07] 两数之和（返回下标）
来源：http://dali.andypj.xyz/Article/details/gtyxlayfwv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigfzy.top/Article/details/gttnevujhw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cdnleiting.top/Article/details/gtbnnikilb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssemufxe.html

TS:   // 手写 Map<string, number>
来源：http://dali.zdqjudy.top/Article/details/gtokjhzapx.html

Java: // 手写 HashMap
来源：http://dali.guowangkeji.top/Article/details/gtrcbwbdna.html

Go:   // 手写 map[int]int
来源：http://dali.mhx1999.top/Article/details/gtpslljzty.html

Ruby: // 手写 Hash
来源：http://dali.haohaochexian.top/Article/details/gttygxmatk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gtasvuxpzf.html

[N08] 生成全排列
来源：http://dali.9152youxi.cn/Article/details/gtuyrpqqtk.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gtblhyfyne.html

PHP:  // 手写递归交换
来源：http://dali.xziqi.cn/Article/details/gtuxpsdzrh.html

JS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtklrvqzmo.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtxnyylzjk.html

Java: // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtylqdupou.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtkcoxqjos.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gtdgshesbh.html

C#:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtrsksmmeb.html

[N09] 栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtkuqlaajn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yangfankeji.com/Article/details/gtvacifpwy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtwcyonnrc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gttqyursak.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yueranfly.top/Article/details/gtvzqzhktl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hywenlv.cn/Article/details/gtwwqbxwkk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.c1oappe.top/Article/details/gtyrszriix.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtgwnuuilp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtfngguzye.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gtjxsrnjot.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxuanxn.top/Article/details/gthevwsvtk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sxryk.cn/Article/details/gtroxopawh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gzhubu.top/Article/details/gtbmfuxvch.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangdashe.top/Article/details/gtftldzssa.html

Java: class Node { int v; Node next; }
来源：http://dali.chenjidiqi.icu/Article/details/gtoptyhiqy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sufxvd.cn/Article/details/gtmvngldzt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hongshengwenyu.top/Article/details/gtbnjekouo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jlsjyb.cn/Article/details/gtskjqcxoz.html

[N11] 二叉树中序遍历
来源：http://dali.9152youxi.cn/Article/details/gtmyofenta.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jlsjyb.cn/Article/details/gtzjnycwuk.html

PHP:  // 手写递归函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivzvmnge.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gtoqncuetc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtgflbmksp.html

Java: // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtxwggmeic.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtwidhdkwu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.feifeiyinyue.top/Article/details/gtyutudyor.html

C#:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtkzptbrdj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ydzc1.top/Article/details/gtrgjvddvi.html


<!-- 参考信息 -->