代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2mynansbd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gt2foxjsgwt.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gt2wjzhxvln.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gt2bxtnbago.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sxryk.cn/Article/details/gt2adskceyu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gt2tejmdrmu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgnpcygn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2ymjzhwjr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nhnznwbu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gt2uhemtotf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gt2dyioerrn.html

[K05] 深拷贝对象
来源：http://dali.guowangkeji.top/Article/details/gt2khqfxncj.html

Py:   copy.deepcopy(obj)
来源：http://dali.sweek.top/Article/details/gt2thbihlcq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrekvfwo.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2udnfurqq.html

TS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2brlcbypq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.9152youxi.cn/Article/details/gt2qerpcsof.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.smart0.xyz/Article/details/gt2njnoakfs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gt2tkxcqnls.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjgujyrg.html

[K06] 解析 URL 查询串
来源：http://dali.ydzc1.top/Article/details/gt2myxalgmz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gt2xllaautg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gt2vluyvcpd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gt2hullcrpw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2swrhixfy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gt2zujaiexw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2gwjxznsu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2fehypzmq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yaijwhfv.html

[K07] 进制转换
来源：http://dali.yj20258888.top/Article/details/gt2kanysytg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2bkjuqemn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.316326.xyz/Article/details/gt2rhfdumin.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2btuztmaa.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2rjbecyoy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2ejkpszyd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuxming.cn/Article/details/gt2hoohmixg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daxiang520.top/Article/details/gt2sxsvtayb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uomtudyw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.iojbl.cn/Article/details/gt2kayvibsf.html

Py:   pickle.dumps(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2cklqewpp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gt2oilvckig.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gt2inrwpryg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gt2bznntill.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpeobtoh.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gt2udienzik.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2jaqnrpao.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gt2jsemfonm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2rlfpdwtx.html

L. 网络请求
来源：http://dali.jiagoushi.top/Article/details/gt2dbnalsua.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2vmgxruac.html

[L01] 发送 GET 请求
来源：http://dali.jianghu66.top/Article/details/gt2tudhxbua.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.havefunace.top/Article/details/gt2pxpvluyb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigfzy.top/Article/details/gt2xbvwroow.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2huvhbxyg.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvbfvqoi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gt2zicckpdc.html

Go:   resp, err := http.Get(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2vmiptmig.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhengqikj.top/Article/details/gt2swjovvpa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.redwolf501.top/Article/details/gt2blmigbmo.html

[L02] 发送 POST JSON
来源：http://dali.sysykeji.top/Article/details/gt2xxqduefb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gt2vzmuuedy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.0kj1m.cn/Article/details/gt2yvdxgsja.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gt2bannytuz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gt2iicuxqha.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.9152youxi.cn/Article/details/gt2grgmtpum.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2tpywzdam.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yvedp.cn/Article/details/gt2uppfllkt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgfzy.top/Article/details/gt2jedajoqz.html

[L03] 设置自定义请求头
来源：http://dali.guowangkeji.top/Article/details/gt2jzrwfhie.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2wjokpylk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2rahwuzem.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gt2axfrovzd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gt2uxpgcian.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gt2spndfcil.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gt2egqnhpra.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gt2otzsvrcv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gt2doydtlua.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gt2mjnxvwdj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnkbfckb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cashguo.top/Article/details/gt2wdpasrle.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2ixzquyqh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gt2pecsnipk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gt2factdjnu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zdqjudy.top/Article/details/gt2giacmlgq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gt2gdjabovm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ehwqpu.com/Article/details/gt2mawfdfps.html

[L05] 上传文件（multipart）
来源：http://dali.aibaodan.cn/Article/details/gt2wylcvesg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gt2oiombsxg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuanzx.com/Article/details/gt2jsorcxwf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gt2ltddxovw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gt2ipqfnfze.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aizwys.cn/Article/details/gt2sgyhpjsr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuanzhike.top/Article/details/gt2nkuyldrj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iponecdx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2jrzfvtpy.html

[L06] 解析响应为 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzwznklo.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gt2ixvgvdjb.html

PHP:  json_decode($body, true);
来源：http://dali.jlsjyb.cn/Article/details/gt2yzqkwrpx.html

JS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gt2dicsrzkk.html

TS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gt2xymlcrfv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2iolsocbt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hywenlv.cn/Article/details/gt2lblfszxq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fengsongda.top/Article/details/gt2jlhbtzrm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gt2kwpanwmg.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gt2wkejaiab.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.9152youxi.cn/Article/details/gt2laxcizfi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gt2lirmohqb.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gt2qbtxldap.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gt2rjxvwicv.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gt2gtyovfjn.html

Go:   resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gt2vrfkfupa.html

Ruby: resp.code.to_i
来源：http://dali.hysaishi.cn/Article/details/gt2txtzmlgz.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gt2twaflygf.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gt2uyfjxuxj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gt2jcgruatq.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gt2irbuoipf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gt2wbkwtrkk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gt2pwgjcldi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.havefunace.top/Article/details/gt2lxhitazx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gt2kwlqblqn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gt2ixyblzby.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gt2rfrqqobr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2dsslmrhx.html

M. 命令行 / 进程 / 环境
来源：http://dali.meibo888.top/Article/details/gt2lsceyglm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2eilqkinv.html

[M01] 读取命令行参数
来源：http://dali.hnqzz.top/Article/details/gt2mtackjsg.html

Py:   sys.argv[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2cdsfnxsu.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdbphnpa.html

JS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gt2sblowadv.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qzsdhzwl.html

Java: args 数组（main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gt2oosjwxuw.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gt2cdquhhnc.html

Ruby: ARGV
来源：http://dali.dianchejie.cn/Article/details/gt2hvnetdxt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gt2fangxgta.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gt2jffpdlvn.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2vvsumixt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gt2jrkclpkd.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gt2cqkggsbs.html

TS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gt2znnkeahn.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2wofzxisq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sweek.top/Article/details/gt2rjresahk.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gt2ubmuhfjz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cheryme.top/Article/details/gt2yfwmripm.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gt2mcgfubrs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qdznenlu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gt2wwzxyowg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gt2ftsoqsqm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gt2gvewqtrv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gotoacloud.top/Article/details/gt2sfxphcgp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnrxlrzo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigufen.top/Article/details/gt2jxtffnco.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ityqwmqx.html

[M04] 获取当前工作目录
来源：http://dali.hammf.cn/Article/details/gt2ppzubivq.html

Py:   os.getcwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2blibjsjl.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gt2caoftgrr.html

JS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vylehfks.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gt2sdwlerec.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gt2qnogwawl.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwuxjdds.html

Ruby: Dir.pwd
来源：http://dali.guowangkeji.top/Article/details/gt2lkclffmj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dashuyun.cn/Article/details/gt2axtttlsv.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gt2jcjxvjsj.html

Py:   sys.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2xoxwvcaf.html

PHP:  exit(1);
来源：http://dali.pycfn.com/Article/details/gt2enqxbwxr.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2edbnzbcy.html

TS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2jveawxgp.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2qldmwsfx.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpwltoww.html

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gt2ursznfmd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gt2sixsrcox.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gt2sdiidmre.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gt2bwispmdd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenzaomai.com/Article/details/gt2psnbtphc.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gt2cgdhqskx.html

TS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gt2nildrgno.html

Java: System.err.println("err")
来源：http://dali.hfpthk.cn/Article/details/gt2cabjopjp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.havefunace.top/Article/details/gt2pxerxfje.html

Ruby: warn "err"
来源：http://dali.9152youxi.cn/Article/details/gt2vozdpwze.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.bjfxy.top/Article/details/gt2acmjwrwr.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gt2tzpyecqz.html

Py:   if __name__ == "__main__":
来源：http://dali.gotoacloud.top/Article/details/gt2nabfiqci.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shzxlz.cn/Article/details/gt2lqllwxuv.html

JS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gt2wvgtdbmo.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gt2lnwigshw.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gt2menwxnhw.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gt2qdvlggcm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gt2jnwpmqmg.html

C#:   static void Main(string[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugfcztff.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gt2pvlxfgug.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cucudq.cn/Article/details/gt2ncusbcxz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.mhx1999.top/Article/details/gt2wxrbvoaw.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2simnajwc.html

TS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gt2egyseegt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.smart0.xyz/Article/details/gt2efbcjbng.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aibaodan.cn/Article/details/gt2fyaorfmq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj202588.top/Article/details/gt2pfwzlupu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gt2ssjlxhgf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2vllldrya.html

N. 数据结构与算法
来源：http://dali.aibaodan.cn/Article/details/gt2ywjanlns.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ypqckolg.html

[N01] 二分查找（有序数组）
来源：http://dali.yangfankeji.com/Article/details/gt2dplzswta.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2jwbodjlv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2brixynio.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gt2rtagyqyy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2vjkmajom.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2ryrjoemy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2hmbqksjb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gt2jxgepyux.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2aooknjmf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.316326.xyz/Article/details/gt2chrrzgjb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gt2tvmuebyd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shzxlz.cn/Article/details/gt2zzwzuupo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2neqiiefd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gt2dspdjkqw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lfysoytd.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gt2atnpqtcv.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gt2entsacii.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuxming.cn/Article/details/gt2fddgaqjv.html

[N03] 快速排序（分治示例）
来源：http://dali.guowangkeji.top/Article/details/gt2zrekucei.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258.top/Article/details/gt2ozmdgvwi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhixingplan.top/Article/details/gt2foorxllx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gt2atoireev.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gt2dgkdcxhl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yongpay.top/Article/details/gt2rxszmwvm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.smart0.xyz/Article/details/gt2xlhdekoi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gt2oydwzhjk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258.top/Article/details/gt2buoldmcw.html

[N04] 斐波那契数列
来源：http://dali.sxryk.cn/Article/details/gt2qrojftjl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gt2pibmmgse.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xinyue.icu/Article/details/gt2ppilixvk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2fhzsawva.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gt2ylafawsg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gt2wkjstdvd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuxming.cn/Article/details/gt2fcuigtvh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gt2bqehuyqk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hptlnuat.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gt2dgztnyau.html

Py:   math.gcd(a, b)
来源：http://dali.cucudq.cn/Article/details/gt2bmlfdnri.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2rlzbsrvs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gt2wmvajtlt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jzsvuasx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhixingplan.top/Article/details/gt2flbowpqm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hysaishi.cn/Article/details/gt2baorrjea.html

Ruby: a.gcd(b)
来源：http://dali.guowangkeji.top/Article/details/gt2bcklhkxf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tianlin.xyz/Article/details/gt2zxhzmhja.html

[N06] 判断回文字符串
来源：http://dali.daria6918.cn/Article/details/gt2kodwinfx.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gt2peighlon.html

PHP:  $s === strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gt2rmkxdodj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2ppvqbmlu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gt2bfyevusb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmxfyqor.html

Go:   // 双指针从两端比较
来源：http://dali.kuanghao11.cn/Article/details/gt2bqykzazi.html

Ruby: s == s.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2dwdkzrzz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gt2dwzbotve.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gt2bkrmqzjo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2blrommjc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qmnlggbl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lksfwfar.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenzaomai.com/Article/details/gt2rphvyzue.html

Java: // 手写 HashMap
来源：http://dali.jqgufenzy.top/Article/details/gt2gobkfgrw.html

Go:   // 手写 map[int]int
来源：http://dali.aizwys.cn/Article/details/gt2cvbysshg.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gt2lgpqkvgu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.birdmap.top/Article/details/gt2spidvctk.html

[N08] 生成全排列
来源：http://dali.zhiwuduotai.top/Article/details/gt2pjarfcte.html

Py:   itertools.permutations(arr)
来源：http://dali.fzhhl.top/Article/details/gt2grszrlmn.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gt2qkexaxvf.html

JS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2bcgqongo.html

TS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2cxnyizny.html

Java: // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2pufhhqdh.html

Go:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2pjggwgob.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxinkj.top/Article/details/gt2cypjvrqq.html

C#:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2ywmjegft.html

[N09] 栈与队列
来源：http://dali.fengsongda.top/Article/details/gt2eaacmdld.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gt2uoloygnt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xziqi.cn/Article/details/gt2fwtfxyep.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gt2fonnemdv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.snrcjt.cn/Article/details/gt2atdljvql.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guannengcc.top/Article/details/gt2nggvaadf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gaohongyu789.top/Article/details/gt2rckhsvtt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gt2zpsmapai.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhixingplan.top/Article/details/gt2kbtzvyiq.html

[N10] 链表节点定义
来源：http://dali.jiagoushi.top/Article/details/gt2zxtuyqyr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shzxlz.cn/Article/details/gt2easlatzd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.316326.xyz/Article/details/gt2xoqavuwu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2vevbacwf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jiagoushi.top/Article/details/gt2oxrosxnt.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gt2zjhjtlxf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxuanxn.top/Article/details/gt2ylqzsejs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.iojbl.cn/Article/details/gt2jaylsqnw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gt2vxnfsnhg.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gt2ycyjbuwl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gzhubu.top/Article/details/gt2frrocbxz.html

PHP:  // 手写递归函数
来源：http://dali.jqgufenzy.top/Article/details/gt2ecfhpntj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gt2kttwwbfx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gt2mhksgorc.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2kawckqdv.html

Go:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yaluhzsu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zatrvguc.html

C#:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gt2ilbvwewl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.bjfxy.top/Article/details/gt2tlqdztya.html


<!-- 参考信息 -->