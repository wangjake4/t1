代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tian-w.cn/Article/details/gtopagtglx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gtecimgvsn.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gtyfuovici.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpuryzwh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuxming.cn/Article/details/gtdsepcxxw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtvoixcmvj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtlaafgcvk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtgvgyyoxt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gtvsqseygv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gthetptpwe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtfxqqyhen.html

[K05] 深拷贝对象
来源：http://dali.sufxvd.cn/Article/details/gtmvzxuvhr.html

Py:   copy.deepcopy(obj)
来源：http://dali.xziqi.cn/Article/details/gtmaelypyc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gtlgvydeei.html

JS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtsthiudme.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtnfnfrobr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangshuangyany.cn/Article/details/gtalrccyrk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pycfn.com/Article/details/gtkljlwfcl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gtvhjtahgw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gtpeqfmqkb.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gtudoxrlun.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtfqqonqaf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sufxvd.cn/Article/details/gtvwamzpyc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtesnwcqqk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gttyyjdrio.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.snrcjt.cn/Article/details/gtegigpfbq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gtlqmyumwn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtsdalsnlo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtcuzklfda.html

[K07] 进制转换
来源：http://dali.wangshuangyany.cn/Article/details/gtykntzzmv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtirjolqut.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gtdycimcfb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtbthcasaz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtktqbeqsm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtsdcobqjq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gtqaprpofc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtkhnqsqix.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtrfusiqim.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gtrblkztdf.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gtwnoqycnd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gtntrxzqkb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtqibfhmqt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gtipkbnexm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.iojbl.cn/Article/details/gtskmbkazh.html

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gtfhcfvftz.html

Ruby: Marshal.dump(obj)
来源：http://dali.hysaishi.cn/Article/details/gtwutczdda.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtxhottnep.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpnutxjmb.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gtoggmmdkl.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtnqhhvrpq.html

[L01] 发送 GET 请求
来源：http://dali.daxiang520.top/Article/details/gtzrrhjzvr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gaohongyu789.top/Article/details/gtdhldjras.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.bjfxy.top/Article/details/gtirckqsgo.html

JS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gthaezyjga.html

TS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gtfzuvmftk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxuanxn.top/Article/details/gtvhtoexcq.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gtahicitmd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sysykeji.top/Article/details/gtvcetjmpf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkiwqbtd.html

[L02] 发送 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtikacdqia.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtjirdnmwz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhengqikj.top/Article/details/gtzldmdbsd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gtfnooxthi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtwizuebxa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gtboqzykps.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.andypj.xyz/Article/details/gtcnxvtlgj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tian-w.cn/Article/details/gtxifswool.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xylfe.cn/Article/details/gtocjrbzlp.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctalbtzx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xylfe.cn/Article/details/gtjlgmwoco.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aizwys.cn/Article/details/gtwsqkbatk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtergfzlfd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gthdawewcg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdeosiizh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gtjrqtouqz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gtzvnrtmkv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtzlczjfql.html

[L04] 设置超时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfoafoao.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gtuqatasio.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gtxqmmgohy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gtrwlmlbkh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gtemztqqsx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gzhubu.top/Article/details/gtjtpcilee.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhengqikj.top/Article/details/gtdhwhfdky.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gtyskwqhrf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dashuyun.cn/Article/details/gthchtihjd.html

[L05] 上传文件（multipart）
来源：http://dali.316326.xyz/Article/details/gtfluxwilr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jianghu66.top/Article/details/gtwkqogwip.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gtgobcqjuh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtuhjmpkbd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gthkkxsetx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj202588.top/Article/details/gtnwvnevkt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xziqi.cn/Article/details/gtrifwlddr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gtvjerrzzt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtkhflswfg.html

[L06] 解析响应为 JSON
来源：http://dali.pycfn.com/Article/details/gtqwkbqcns.html

Py:   resp.json()
来源：http://dali.jianghu66.top/Article/details/gtoxruojse.html

PHP:  json_decode($body, true);
来源：http://dali.jlsjyb.cn/Article/details/gtfvqbyrwn.html

JS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtvyyoific.html

TS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gthahpyfbh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtpwtsijbb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tanke756.top/Article/details/gtqxcufdko.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gtfeaidufm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gtslpdbuxi.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtfntsmbsw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnqzz.top/Article/details/gtrdnowcnk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gtcvpyqeqn.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtmmizdmiv.html

TS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtmqwcnobu.html

Java: resp.statusCode()
来源：http://dali.jinqigufen.top/Article/details/gtzvjhgpbm.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gttdbgagal.html

Ruby: resp.code.to_i
来源：http://dali.hysaishi.cn/Article/details/gtuizlkjqb.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtdhcijcdt.html

[L08] 并发请求多个地址
来源：http://dali.bjfxy.top/Article/details/gtahuzkfww.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fengsongda.top/Article/details/gtbvhuclgk.html

PHP:  curl_multi_init() 系列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhocdexp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtvgcdnhab.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gthuxiwfxx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pengpengdd.cyou/Article/details/gtfhaqfaac.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxuanxn.top/Article/details/gtdziacosk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xinyue.icu/Article/details/gtsbdkrxsn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtibuvzplr.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtzpiqxxdg.html

M. 命令行 / 进程 / 环境
来源：http://dali.daria6918.cn/Article/details/gtfhskgniu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtavrimxxg.html

[M01] 读取命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtcpdaymjn.html

Py:   sys.argv[1:]
来源：http://dali.hammf.cn/Article/details/gthsvwzgfj.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gtaxebyeer.html

JS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtwdjxiegi.html

TS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gttegltjij.html

Java: args 数组（main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gtffbnoeid.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gtngprurbd.html

Ruby: ARGV
来源：http://dali.tian-w.cn/Article/details/gtqalkxqwy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gtbqqerxsv.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gtckqgxndj.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gtefboqogh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtgfysnbvr.html

JS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtsdbmolqd.html

TS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gtzefzcdlt.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtgtsqcchy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtwplaeboh.html

Ruby: ENV["HOME"]
来源：http://dali.smart0.xyz/Article/details/gtocdgkobx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtusvmikuh.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gtkwogbrfr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gtnhlvbavw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gtjfvfvhca.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtvvrfgchm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzmacxlr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgufenzy.top/Article/details/gthnmfzurt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhixingplan.top/Article/details/gtuirsveho.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gtwvleroqa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gtulesmqte.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gtrttopgvd.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gtikdfjloz.html

PHP:  getcwd();
来源：http://dali.cqqwz.cn/Article/details/gthoinwqmr.html

JS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtphciguel.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtpmlshwof.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gtmcqmgzcc.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gtuoklqsbw.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gtkgfilaef.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahhrbykm.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gtlsbllxik.html

Py:   sys.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtnftuxlgs.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gtjqhbqmqi.html

JS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtrqigbdcl.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtjvqxzqya.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtbnszcomr.html

Go:   os.Exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtiklawqel.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gtqwwwpyiw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gtidcitdfu.html

[M06] 向标准错误输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhcbzfvs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gthlzaovna.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.c1oappe.top/Article/details/gtqlnfqdee.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtbxtzlqfn.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gtlvbvdnnw.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gtvuthnbnp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenjidiqi.icu/Article/details/gtsucssroo.html

Ruby: warn "err"
来源：http://dali.hywenlv.cn/Article/details/gtycqcedlg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gtyfekfvhc.html

[M07] 判断是否为主入口
来源：http://dali.hfpthk.cn/Article/details/gtbtwjrnko.html

Py:   if __name__ == "__main__":
来源：http://dali.cqqwz.cn/Article/details/gtaefzjvdp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gtvjgcgplr.html

JS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gtidrgppxi.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gtgcxelord.html

Java: public static void main(String[] args)
来源：http://dali.smart0.xyz/Article/details/gtlpevmqzi.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gtljxmglyu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gtovmhhlrs.html

C#:   static void Main(string[] args)
来源：http://dali.pycfn.com/Article/details/gtxrhxrfqn.html

[M08] 获取系统与运行时信息
来源：http://dali.hfpthk.cn/Article/details/gtkczmjdvm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gtoqoxistf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aizwys.cn/Article/details/gtxnqcnsgh.html

JS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtbyinckdh.html

TS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtulpvhmzc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.quarkkingdee.top/Article/details/gtzvylbzvw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daria6918.cn/Article/details/gthorvgyda.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gtbxgprtba.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.9152youxi.cn/Article/details/gtegskqimu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtsqttbwhu.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gtlaujfhcr.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtohymcyam.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gtqiwlfenj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbomyivo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtxuopczyh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtahckuatk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtmgyzmyxy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gttoapqwgi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtmmzwiuqi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gtklmyefeh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gttnsvyifa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yonumen.top/Article/details/gtxekkiqgu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gttfmfkukl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtaswecqij.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtsfdngztl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtlnswvbdm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gtaxhdqxwj.html

Go:   slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gthwexcpxe.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtviijfkia.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gtwrmgsdlw.html

[N03] 快速排序（分治示例）
来源：http://dali.quarkkingdee.top/Article/details/gtirtcdteg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gtaiaghthn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenlongwang.top/Article/details/gtlpwxriox.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gtifiombkb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtwtnlhswl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigfzy.top/Article/details/gtirftxqpf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ppjwa.cn/Article/details/gtqfcefdfs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fzhhl.top/Article/details/gtrdszsmsn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gthejlmnkp.html

[N04] 斐波那契数列
来源：http://dali.9152youxi.cn/Article/details/gtisyafmhu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtcxnaknru.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtktwzrxhg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtzlsgmbyy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtpanzxfzv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtgiybwcjg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.meibo888.top/Article/details/gtlezbfhxq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnvrrcmz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gthoyptbgy.html

[N05] 最大公约数
来源：http://dali.iojbl.cn/Article/details/gtsoyqsghi.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gtsyhyzumo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gtxbcjdpch.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtsvsdfkjq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gthoohbqjo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gtkjkpgzda.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gtefsqwnwb.html

Ruby: a.gcd(b)
来源：http://dali.sxryk.cn/Article/details/gtxizkhqog.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.redwolf501.top/Article/details/gtwmotsmph.html

[N06] 判断回文字符串
来源：http://dali.chenzaomai.com/Article/details/gtqhjwkrnh.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtgmlwapfb.html

PHP:  $s === strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtzmzjwqgb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtufgyucmv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gttlhvezgu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigfzy.top/Article/details/gtgajkhlbt.html

Go:   // 双指针从两端比较
来源：http://dali.sufxvd.cn/Article/details/gtdscsmauw.html

Ruby: s == s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtzjnbopql.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gtfpyxorah.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gtrwkaptrw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gtzosvmumg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.kuanghao11.cn/Article/details/gtwzozovcq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yangfankeji.com/Article/details/gtvwuykcoo.html

TS:   // 手写 Map<string, number>
来源：http://dali.ybcxt.top/Article/details/gteriyzeck.html

Java: // 手写 HashMap
来源：http://dali.jianghu66.top/Article/details/gttvqarfaf.html

Go:   // 手写 map[int]int
来源：http://dali.zhixingplan.top/Article/details/gtdxiphvmr.html

Ruby: // 手写 Hash
来源：http://dali.yueranfly.top/Article/details/gtdjujiptg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aibaodan.cn/Article/details/gtjoezsirf.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gtxbqcidpk.html

Py:   itertools.permutations(arr)
来源：http://dali.hysaishi.cn/Article/details/gtevlrupwk.html

PHP:  // 手写递归交换
来源：http://dali.cashguo.top/Article/details/gtdekyeneg.html

JS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtrqwsigmz.html

TS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtpbwfdiwx.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtajtnnpus.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gttfmlnmwy.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgfzy.top/Article/details/gtdzsltclt.html

C#:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtazougoqd.html

[N09] 栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtmszyaiel.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ehwqpu.com/Article/details/gtxfxjxwhv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtfzrmgekk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtilqlavnm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gtwjzonfbx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigufen.top/Article/details/gtdjetnyok.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.mhx1999.top/Article/details/gtfncwbkqk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtyfcyigcq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gtaoednmwq.html

[N10] 链表节点定义
来源：http://dali.yangfankeji.com/Article/details/gtncypwyow.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aibaodan.cn/Article/details/gtufluylgl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.havefunace.top/Article/details/gtwlhltcjb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.haohaochexian.top/Article/details/gtwjfgqdwh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xinyue.icu/Article/details/gtcwdmrycc.html

Java: class Node { int v; Node next; }
来源：http://dali.gzhubu.top/Article/details/gttnfrckmi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gzhubu.top/Article/details/gtcidcvzma.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgufenzy.top/Article/details/gtequapwar.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqbkivht.html

[N11] 二叉树中序遍历
来源：http://dali.hammf.cn/Article/details/gtpzlpzgwb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gtojybpdak.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gtixplczxu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gtjgfbqdut.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtfpdmybtt.html

Java: // 手写递归
来源：http://dali.hammf.cn/Article/details/gtgwuivrig.html

Go:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtkretifzm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.feifeiyinyue.top/Article/details/gtezmitinx.html

C#:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtbeyhuljj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgfzy.top/Article/details/gtekqsgyel.html


<!-- 参考信息 -->