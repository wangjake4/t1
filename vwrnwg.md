代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.316326.xyz/Article/details/gt2kwifbrne.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenlongwang.top/Article/details/gt2mnbkuksq.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gt2isgkultl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gt2uctcxrpn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gt2cmbzhyrz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gt2orjvfvvo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2kqojtbxp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yifutthf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gt2ymclmlfv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2gwsbizjs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nyrdjxkr.html

[K05] 深拷贝对象
来源：http://dali.daria6918.cn/Article/details/gt2tbqzamzp.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2lafywfks.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gt2manlujzl.html

JS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bubmjcpw.html

TS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gt2zwexcemu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gt2edndcdnl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.redwolf501.top/Article/details/gt2crcpdhsu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gt2giwnhzxg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shzxlz.cn/Article/details/gt2bjmexpaz.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gt2nbfudcpu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhrwnjdu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shuidangran.top/Article/details/gt2aizkqcrh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzzwtrat.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2kryzfupf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgfzy.top/Article/details/gt2hhuqpvgc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2lsvwiznb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yievbzig.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wizlcyyu.html

[K07] 进制转换
来源：http://dali.xinyue.icu/Article/details/gt2dogihzdh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2hsabqpku.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gt2bmsvatuo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2dubciomk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2fedpmehj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2gilvquao.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gt2pxiofjur.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nwbrower.top/Article/details/gt2egpmbabp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2plqqbgfc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gt2cysprqzf.html

Py:   pickle.dumps(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2kpycxexn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj202588.top/Article/details/gt2glarchty.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gt2hnvihlqt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2vgocokhq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigufen.top/Article/details/gt2eyeqaeon.html

Go:   encoding/gob
来源：http://dali.shuidangran.top/Article/details/gt2fxsfadho.html

Ruby: Marshal.dump(obj)
来源：http://dali.sysykeji.top/Article/details/gt2lcenlfwr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pycfn.com/Article/details/gt2tnsqbmrk.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2ojkqjivn.html

L. 网络请求
来源：http://dali.jlsjyb.cn/Article/details/gt2pfrzdbgj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2oqvgsuit.html

[L01] 发送 GET 请求
来源：http://dali.hongshengwenyu.top/Article/details/gt2agxzkeui.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gt2ukrwioya.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gt2vndzloqp.html

JS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gt2hospkacx.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gt2svmgnknf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhoulong.xyz/Article/details/gt2kzlvshxs.html

Go:   resp, err := http.Get(url)
来源：http://dali.gzhubu.top/Article/details/gt2xlysckte.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tcpzlmyz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2ikndttzj.html

[L02] 发送 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gt2gtbjalwn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gt2otodkjdc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gaohongyu789.top/Article/details/gt2oosblknw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gt2ylflordv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gt2pyltfuwo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.c1oappe.top/Article/details/gt2vncqoari.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gt2nxlgkgrk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gt2kdsmtagd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuxming.cn/Article/details/gt2krrzxjgw.html

[L03] 设置自定义请求头
来源：http://dali.sufxvd.cn/Article/details/gt2afbuopgy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhixingplan.top/Article/details/gt2afetzvoi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2rxxxnaep.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gt2wcarefke.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gt2wnqxobqo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gt2tgwpyikt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jjuqtpwt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gt2josnnwjl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gt2fhubxjzo.html

[L04] 设置超时
来源：http://dali.tanke756.top/Article/details/gt2azktgfzx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.mhx1999.top/Article/details/gt2vukzyvpv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gt2ikkcayie.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gt2vacbzkxf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gt2mofnhjaw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gt2fwijigqh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yvedp.cn/Article/details/gt2fbspjcsm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shuidangran.top/Article/details/gt2wlbexubo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gt2dndllmmf.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gt2bgonvewl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.quarkkingdee.top/Article/details/gt2lfshwsph.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhskbvjl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gt2bwwjuvmx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2sderczzl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gt2qfkqwniu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xziqi.cn/Article/details/gt2ymlzdblz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gt2sjzmpqzv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2zpgqqvrm.html

[L06] 解析响应为 JSON
来源：http://dali.yonumen.top/Article/details/gt2sdgbmygc.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gt2ryxippyb.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gt2uhlsaudy.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2vnzmfnfj.html

TS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmtmkgzp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2mnqorbwq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gt2uwymacwg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hammf.cn/Article/details/gt2kgqqnghr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gt2seqpoxxh.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gt2gjutwihc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guannengcc.top/Article/details/gt2trgzwbur.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2elhjgsfb.html

JS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gt2zneffffp.html

TS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gt2bbltncpu.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gt2krubxmvz.html

Go:   resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gt2zdtdjtln.html

Ruby: resp.code.to_i
来源：http://dali.yanxiufei.cn/Article/details/gt2ivqxexnq.html

C#:   (int)resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gt2ptcsejbg.html

[L08] 并发请求多个地址
来源：http://dali.gogol.net.cn/Article/details/gt2xnbxucqs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj202588.top/Article/details/gt2ktyuxswv.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gt2zxqwofqv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gt2xvsjqndh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gt2zyvmydus.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gt2tkjbgcuw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tian-w.cn/Article/details/gt2owbjegfq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ijqzszbj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ydzc1.top/Article/details/gt2uiurebwj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2lsqlqgsk.html

M. 命令行 / 进程 / 环境
来源：http://dali.feifeiyinyue.top/Article/details/gt2gljixjcd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2oxryfgsx.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gt2espbgseg.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gt2dmsquolz.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tdzeppio.html

JS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gt2aafzfjkk.html

TS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gt2itxqlohy.html

Java: args 数组（main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gt2zvkyagav.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gt2hzthptpg.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gt2oxadjogs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tfyaepst.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gt2wnttarto.html

Py:   os.environ.get("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2vcuhvemi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gt2iphngbxa.html

JS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkfnunsl.html

TS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ssolmstt.html

Java: System.getenv("HOME")
来源：http://dali.tanke756.top/Article/details/gt2fashqldy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2yacnczdg.html

Ruby: ENV["HOME"]
来源：http://dali.shuidangran.top/Article/details/gt2jyxwjcjj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aizwys.cn/Article/details/gt2wwjytzng.html

[M03] 执行外部命令
来源：http://dali.zhixingplan.top/Article/details/gt2akgpisiy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuetiantiany.cn/Article/details/gt2awvlmkel.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sufxvd.cn/Article/details/gt2blbcxxip.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gt2hptoinoo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gt2ruvjdxso.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gt2ikizpczc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gt2gpwkfvgu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gt2ytqaaelq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ehwqpu.com/Article/details/gt2umoiwfsp.html

[M04] 获取当前工作目录
来源：http://dali.gaohongyu789.top/Article/details/gt2ypzmoxas.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gt2qkmtusnw.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gt2nlltvhiq.html

JS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gt2vstoptxj.html

TS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gt2hshjjmun.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gt2rxvfvuvg.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gt2fovxktjj.html

Ruby: Dir.pwd
来源：http://dali.aibaodan.cn/Article/details/gt2sgojkhib.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fzhhl.top/Article/details/gt2opcleoio.html

[M05] 设置退出码
来源：http://dali.nwbrower.top/Article/details/gt2zwnksbia.html

Py:   sys.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2wxgruass.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gt2xpiiikwj.html

JS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2rgslmikn.html

TS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2rzulbcqj.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2lgivhrvp.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2uyaxyosh.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gt2gxdjnjuj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.feifeiyinyue.top/Article/details/gt2ncuoeuol.html

[M06] 向标准错误输出
来源：http://dali.guannengcc.top/Article/details/gt2qghdvcqc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gt2cizggwwp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gt2funwxvtz.html

JS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rgugeglp.html

TS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gt2fryfjedk.html

Java: System.err.println("err")
来源：http://dali.jqgfzy.top/Article/details/gt2yehmwxjg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cucudq.cn/Article/details/gt2anmoolcu.html

Ruby: warn "err"
来源：http://dali.xziqi.cn/Article/details/gt2avrvjjky.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wipavgxm.html

[M07] 判断是否为主入口
来源：http://dali.birdmap.top/Article/details/gt2oaqrunmz.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gt2iimpifbe.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xkfznhio.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gt2kshdvbny.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajxcqdjp.html

Java: public static void main(String[] args)
来源：http://dali.hnqzz.top/Article/details/gt2cakkaiwy.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gt2jrdpbomg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhoulong.xyz/Article/details/gt2dbokhadr.html

C#:   static void Main(string[] args)
来源：http://dali.zdqjudy.top/Article/details/gt2mmlnfpau.html

[M08] 获取系统与运行时信息
来源：http://dali.yonumen.top/Article/details/gt2bltgrkei.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daria6918.cn/Article/details/gt2sqkvqava.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gt2yuvozjbv.html

JS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gt2gqwilwno.html

TS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gt2lvetluzo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cheryme.top/Article/details/gt2eojurjha.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sweek.top/Article/details/gt2lopxaldd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sxryk.cn/Article/details/gt2ddlybjyt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gt2arvarvxf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2hojvnryj.html

N. 数据结构与算法
来源：http://dali.jyoumei.cn/Article/details/gt2tskueygf.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2mtovrwdq.html

[N01] 二分查找（有序数组）
来源：http://dali.meibo888.top/Article/details/gt2uhemzlel.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2oqyktpqh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gotoacloud.top/Article/details/gt2ftrpbxjs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2fsxqhkhd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gt2puyqrpyg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2cpwjktgb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2ndkirywj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gt2cnmemdfd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2mijwpdfx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yonumen.top/Article/details/gt2qeaujcja.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2bqzrkmtz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ybcxt.top/Article/details/gt2rmcjgdtt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gt2cfxanffk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gt2xvcqjrvm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zdqjudy.top/Article/details/gt2dkcqtesa.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gt2urnltwhp.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gt2loplggsc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jianghu66.top/Article/details/gt2vekutzho.html

[N03] 快速排序（分治示例）
来源：http://dali.hfpthk.cn/Article/details/gt2xparijqx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gt2fpxwtjke.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ybcxt.top/Article/details/gt2fayyurgj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gt2bfqndchu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gt2pijngqjq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hywenlv.cn/Article/details/gt2khudwqpe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gt2bevhvahy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.316326.xyz/Article/details/gt2kroxlwth.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cdnleiting.top/Article/details/gt2qlzvaooc.html

[N04] 斐波那契数列
来源：http://dali.zhengqikj.top/Article/details/gt2rpdhehun.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qkzjoodz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ychkhkgt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2iekfdqvq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gt2ohawicfv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.smart0.xyz/Article/details/gt2rtrhzynq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oandhbss.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvvlencw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gt2onmibhml.html

[N05] 最大公约数
来源：http://dali.quarkkingdee.top/Article/details/gt2vwumiqgm.html

Py:   math.gcd(a, b)
来源：http://dali.cashguo.top/Article/details/gt2skibilkp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gt2vkjquzjs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gt2mzihuwpm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krcvqmby.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gt2okrbegam.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.c1oappe.top/Article/details/gt2nexgrhof.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gt2avskbxjh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdsoith.html

[N06] 判断回文字符串
来源：http://dali.316326.xyz/Article/details/gt2egpjzlna.html

Py:   s == s[::-1]
来源：http://dali.yuxming.cn/Article/details/gt2fcdvxypq.html

PHP:  $s === strrev($s);
来源：http://dali.shuidangran.top/Article/details/gt2maotdlwl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2slepwedc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2hsgiafdh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yvedp.cn/Article/details/gt2suaywmti.html

Go:   // 双指针从两端比较
来源：http://dali.nanxuanxn.top/Article/details/gt2lfwifiun.html

Ruby: s == s.reverse
来源：http://dali.tanke756.top/Article/details/gt2uqmykwzk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gt2evrvgrrc.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gt2zwsrqwix.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cashguo.top/Article/details/gt2bmqbjihe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dianchejie.cn/Article/details/gt2tghcgxco.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pycfn.com/Article/details/gt2pstuvkgw.html

TS:   // 手写 Map<string, number>
来源：http://dali.ppjwa.cn/Article/details/gt2irdfjcts.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gt2cpvhvkxv.html

Go:   // 手写 map[int]int
来源：http://dali.chenjidiqi.icu/Article/details/gt2ejvjcxru.html

Ruby: // 手写 Hash
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2khbdlhwc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.316326.xyz/Article/details/gt2yfrndfuk.html

[N08] 生成全排列
来源：http://dali.jlsjyb.cn/Article/details/gt2ndaqxemh.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258888.top/Article/details/gt2ccbjuoyo.html

PHP:  // 手写递归交换
来源：http://dali.fengsongda.top/Article/details/gt2umwhfaif.html

JS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2qskxrmkc.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2fgkuugkn.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzevjuur.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2igdpqzve.html

Ruby: arr.permutation.to_a
来源：http://dali.hongshengwenyu.top/Article/details/gt2cfhjyxmz.html

C#:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2twsomcvv.html

[N09] 栈与队列
来源：http://dali.cashguo.top/Article/details/gt2zpnrfcav.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtikqnw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yvedp.cn/Article/details/gt2ibkghysv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gt2fnikovzw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gt2mdyrnpud.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gt2hhcvusry.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guannengcc.top/Article/details/gt2tefxvcyu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2qzdsuiow.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.vqdsnc.cn/Article/details/gt2hmlnyfie.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gt2vcgcabgp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnqzz.top/Article/details/gt2pjlszkpl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cdnleiting.top/Article/details/gt2maihijji.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dashuyun.cn/Article/details/gt2cjhjblhj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxjvtaq.html

Java: class Node { int v; Node next; }
来源：http://dali.daria6918.cn/Article/details/gt2xtabsmmj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gzhubu.top/Article/details/gt2raqxzszy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigfzy.top/Article/details/gt2smipakcz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.bjfxy.top/Article/details/gt2gpbsphyu.html

[N11] 二叉树中序遍历
来源：http://dali.pycfn.com/Article/details/gt2yqjknwim.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigfzy.top/Article/details/gt2dfkgwwbm.html

PHP:  // 手写递归函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxuuezeq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gt2lefsnmfc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gt2tdqqvobm.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gt2vcsrewij.html

Go:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gt2wfshnwfz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tianlin.xyz/Article/details/gt2cyomirpm.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gt2lwddmobj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxinkj.top/Article/details/gt2mdxnyqnz.html


<!-- 参考信息 -->