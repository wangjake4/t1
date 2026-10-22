代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigfzy.top/Article/details/gt2rqabmhsz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvtxfjjv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gt2ntujtbbk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2ywvejakg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gt2evhuxbua.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gt2hvobjtuu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daxiang520.top/Article/details/gt2ibkpspva.html

[K05] 深拷贝对象
来源：http://dali.jqgfzy.top/Article/details/gt2oldjbiln.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gt2mydayydz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gt2vcrlhzyf.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gt2lmcffctx.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfoiuax.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fzhhl.top/Article/details/gt2afdfhtbf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gt2etcrowoj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gt2qbqvyhqi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guannengcc.top/Article/details/gt2ixkhzpgi.html

[K06] 解析 URL 查询串
来源：http://dali.hywenlv.cn/Article/details/gt2uegdzose.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gt2elnwsxzu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgufenzy.top/Article/details/gt2xjigoxyn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gt2ymmlqtrz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gt2jsbufnlp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.havefunace.top/Article/details/gt2joxaeyxa.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkrmlij.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gt2mxrzenhl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gt2wnfjtisf.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gt2uiivqxrd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2xxgpskud.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.redwolf501.top/Article/details/gt2ulwkkvfo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2vvkhahgq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2peubryqy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2pytwfhdn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yueranfly.top/Article/details/gt2tkvbfrma.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gt2bpkhdfde.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2iiqaolzs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.c1oappe.top/Article/details/gt2fmdaywjv.html

Py:   pickle.dumps(obj)
来源：http://dali.redwolf501.top/Article/details/gt2gqreezxe.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangdashe.top/Article/details/gt2hnkzffsr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vwluzasm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gt2hsxugarq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gt2xumaobeq.html

Go:   encoding/gob
来源：http://dali.yueranfly.top/Article/details/gt2mntjovkf.html

Ruby: Marshal.dump(obj)
来源：http://dali.fengsongda.top/Article/details/gt2gjxicaaz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gt2lseefeke.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2jkcxmtex.html

L. 网络请求
来源：http://dali.hysaishi.cn/Article/details/gt2ltuypuzm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ycvemaid.html

[L01] 发送 GET 请求
来源：http://dali.daria6918.cn/Article/details/gt2wegwqiuy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gt2axdjjqxg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gt2wbtyhtca.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gt2lodpqmwi.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sotulbxs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gzhubu.top/Article/details/gt2lwdhecqb.html

Go:   resp, err := http.Get(url)
来源：http://dali.ydzc1.top/Article/details/gt2xncodeue.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gt2bihzgvsq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.bjfxy.top/Article/details/gt2skkocjfj.html

[L02] 发送 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gt2blytojqf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2qdemjsgy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gt2vzsvrvvj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gt2xbakgjwo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gt2oihffygy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gt2vjbmmqad.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gt2khhizvqf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gt2vmmixmim.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hammf.cn/Article/details/gt2pgrgvsox.html

[L03] 设置自定义请求头
来源：http://dali.nanxuanxn.top/Article/details/gt2ybotamtn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tianlin.xyz/Article/details/gt2nufsfksy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gt2uzcjgskc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gt2otrqpibw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gt2ftjmclos.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hywenlv.cn/Article/details/gt2iagcydea.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gt2gdkikltr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jyoumei.cn/Article/details/gt2qmhpkppk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gt2hvmcblvk.html

[L04] 设置超时
来源：http://dali.cashguo.top/Article/details/gt2lortffns.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jianghu66.top/Article/details/gt2lruzuhzv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ifrgoxdp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gt2lhbzszxk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2npfcskye.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sweek.top/Article/details/gt2tamrwqrn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggjdzzca.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gt2plkdrmab.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wqmpmynk.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gt2qygitrcb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gt2kcxwoxhe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aizwys.cn/Article/details/gt2mncrdotm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gt2exwysipd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gt2zomtjzbd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gt2srneqhnw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2acwfdaig.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gt2ronuggzp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2emcsdggt.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gt2lpzywygg.html

Py:   resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gt2ypnrwbnw.html

PHP:  json_decode($body, true);
来源：http://dali.svipenyu.cn/Article/details/gt2ruqjusot.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2neimncbq.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ejhfcxhz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hammf.cn/Article/details/gt2ucebwxyh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenlongwang.top/Article/details/gt2rvcppcwi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gt2isxnansu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.smart0.xyz/Article/details/gt2lgueufhn.html

[L07] 处理 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gt2oiowfzaa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fzhhl.top/Article/details/gt2orswzdql.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuanzx.com/Article/details/gt2hohvknzh.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gt2rjrbsxwi.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gt2obacxzgl.html

Java: resp.statusCode()
来源：http://dali.jianghu66.top/Article/details/gt2hpwioatb.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gt2avhmxvvo.html

Ruby: resp.code.to_i
来源：http://dali.zycfv.cn/Article/details/gt2nlqrnrms.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2vtsfcmqk.html

[L08] 并发请求多个地址
来源：http://dali.xylfe.cn/Article/details/gt2uodsrkpk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenlongwang.top/Article/details/gt2gewckqrs.html

PHP:  curl_multi_init() 系列
来源：http://dali.cqqwz.cn/Article/details/gt2zovreskm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gt2qegwnqtx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2ghnodsdf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gt2wxmupfzs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zdqjudy.top/Article/details/gt2ncnlwqwg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gt2usuqxwog.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2yoccvaxj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2fhlgbktb.html

M. 命令行 / 进程 / 环境
来源：http://dali.fengsongda.top/Article/details/gt2lvpiwmrv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhfqntho.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gt2nflnulmv.html

Py:   sys.argv[1:]
来源：http://dali.gotoacloud.top/Article/details/gt2riblgyqp.html

PHP:  $argv;  $argc;
来源：http://dali.yj202588.top/Article/details/gt2idektdha.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2xmcrlbfa.html

TS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gt2wnngnezj.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gt2iaiiipax.html

Go:   os.Args[1:]
来源：http://dali.zdqjudy.top/Article/details/gt2tfjenwev.html

Ruby: ARGV
来源：http://dali.smart0.xyz/Article/details/gt2mbjviofu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tanke756.top/Article/details/gt2wcsxtptk.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gt2dofdautq.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gt2neyrexyb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gt2jeblgaug.html

JS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gt2bqsspqdh.html

TS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gt2wtpbckag.html

Java: System.getenv("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2blvznebm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2osjdpujp.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gt2qaauqzdz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2lgvvcbqp.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gt2wcqgvvmf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jianghu66.top/Article/details/gt2kviiirxw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yueranfly.top/Article/details/gt2hdhqutgg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gt2pggpfuvg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gt2naxnhkpe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gt2pqstmnsm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gt2jfbgohfx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daria6918.cn/Article/details/gt2uxugpzqu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gt2sjnzmugq.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gt2zyxujurv.html

Py:   os.getcwd()
来源：http://dali.316326.xyz/Article/details/gt2czmkpeqv.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gt2kxllgyco.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gt2wuwbaxss.html

TS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwzxqogd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnqzz.top/Article/details/gt2cgixtavy.html

Go:   os.Getwd()
来源：http://dali.316326.xyz/Article/details/gt2nzrebjnm.html

Ruby: Dir.pwd
来源：http://dali.fzhhl.top/Article/details/gt2triygbzk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yonumen.top/Article/details/gt2nkbxdbfl.html

[M05] 设置退出码
来源：http://dali.meibo888.top/Article/details/gt2hygtetmn.html

Py:   sys.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2rtcwljkk.html

PHP:  exit(1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2yirjucay.html

JS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2hfrirwyb.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2mcvdidab.html

Java: System.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2oilozyxg.html

Go:   os.Exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2ciyuceuq.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gt2errnworu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gt2jwqloava.html

[M06] 向标准错误输出
来源：http://dali.gzhubu.top/Article/details/gt2vxipgfnn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gt2xblpayqi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gt2wpbzxfpp.html

JS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gt2tdkyslco.html

TS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2kdtuxxlk.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2advrgzkw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gt2rmouwsxr.html

Ruby: warn "err"
来源：http://dali.hongshengwenyu.top/Article/details/gt2enmyyfbn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sweek.top/Article/details/gt2lsjglixg.html

[M07] 判断是否为主入口
来源：http://dali.svipenyu.cn/Article/details/gt2qauwmhvr.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigufen.top/Article/details/gt2ylwjohsc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gt2hqiqtnrh.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gt2evmdffce.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gt2csrpjbqz.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gt2pesgsalt.html

Go:   func main()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjswbyxk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gaohongyu789.top/Article/details/gt2dguoovzk.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkrxdvrs.html

[M08] 获取系统与运行时信息
来源：http://dali.yonumen.top/Article/details/gt2hvcraaap.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shuidangran.top/Article/details/gt2kxspaqku.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnxiangtu.top/Article/details/gt2fzhioxgi.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gt2plywryxi.html

TS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gt2ouhbaqcd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hammf.cn/Article/details/gt2cwbywfcm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yyntmccm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gt2bqihwpyr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dianchejie.cn/Article/details/gt2cuzuoqgy.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ozrkajmn.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gt2qicxsiui.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2uvxnqzui.html

[N01] 二分查找（有序数组）
来源：http://dali.ydzc1.top/Article/details/gt2rfcvswoy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2nswrkcfn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gt2ridiyxex.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2idomgffq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ryavotcn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2mxyotflz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2yfcfcznv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258888.top/Article/details/gt2psigmnlc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2mpzwmwvj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.redwolf501.top/Article/details/gt2sttdmylv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gt2cncxreur.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ppjwa.cn/Article/details/gt2oriznpiq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gt2ozoqarhf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2htvldjtq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gt2sspklssm.html

Go:   slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2zdvoypws.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmenplxv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gt2xcpseoae.html

[N03] 快速排序（分治示例）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2upgeaasy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gt2gtnbqphr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.smart0.xyz/Article/details/gt2fejqxzdj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gt2xijwnovd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjnelmlg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gt2hhjbdtnp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jianghu66.top/Article/details/gt2yyvdolrj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenjidiqi.icu/Article/details/gt2fujeptdr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yueranfly.top/Article/details/gt2bqorlymw.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gt2daulmazb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gt2bqaamspp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zarenhwp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gt2epfnssov.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2irgpvvum.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgiiijwm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ybcxt.top/Article/details/gt2eokudxlv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gt2nwbgmspc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2tokglnzf.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gt2bjpmuvtf.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2wgvylyxx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lijgmyki.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bswflxjr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gt2itvrqysr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gt2ryumsrsf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.havefunace.top/Article/details/gt2nwcenaip.html

Ruby: a.gcd(b)
来源：http://dali.jqgfzy.top/Article/details/gt2krwahqxg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jlsjyb.cn/Article/details/gt2rkkvvevo.html

[N06] 判断回文字符串
来源：http://dali.gogol.net.cn/Article/details/gt2evsiqozq.html

Py:   s == s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gt2bxcrcacv.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gt2fufpczfb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sannstob.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2ipjzocuq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gaohongyu789.top/Article/details/gt2zlboqbex.html

Go:   // 双指针从两端比较
来源：http://dali.smart0.xyz/Article/details/gt2suwxylog.html

Ruby: s == s.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2cefgzqeq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gt2xvrjbtmi.html

[N07] 两数之和（返回下标）
来源：http://dali.pengpengdd.cyou/Article/details/gt2zletduzc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhwkvpmw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yvedp.cn/Article/details/gt2bwvesvbl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gaohongyu789.top/Article/details/gt2gmjhqdds.html

TS:   // 手写 Map<string, number>
来源：http://dali.feifeiyinyue.top/Article/details/gt2uweqmzbu.html

Java: // 手写 HashMap
来源：http://dali.xuanzx.com/Article/details/gt2lwghusnb.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gt2lsbaiqha.html

Ruby: // 手写 Hash
来源：http://dali.hysaishi.cn/Article/details/gt2onafbhrf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxinkj.top/Article/details/gt2rgjbwonr.html

[N08] 生成全排列
来源：http://dali.snrcjt.cn/Article/details/gt2pnuliotk.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gt2duubqlej.html

PHP:  // 手写递归交换
来源：http://dali.quarkkingdee.top/Article/details/gt2xzeuubzf.html

JS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2brkaqnoq.html

TS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2oecemrwn.html

Java: // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2fkzzhrnm.html

Go:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eabwtuhh.html

Ruby: arr.permutation.to_a
来源：http://dali.cucudq.cn/Article/details/gt2srrniurq.html

C#:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2fnozrjrj.html

[N09] 栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epuauhjh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhixingplan.top/Article/details/gt2magfpndd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aizwys.cn/Article/details/gt2qsyvsaog.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2fuylnbpx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jyoumei.cn/Article/details/gt2zfecsfji.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guowangkeji.top/Article/details/gt2xyglzpoc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tian-w.cn/Article/details/gt2fpalrkdw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gt2cvtwrmst.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgufenzy.top/Article/details/gt2trijqlpr.html

[N10] 链表节点定义
来源：http://dali.cqqwz.cn/Article/details/gt2rerllovj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.birdmap.top/Article/details/gt2ndznrkrw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.quarkkingdee.top/Article/details/gt2kyolwrmi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuanzx.com/Article/details/gt2ptixpztd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258888.top/Article/details/gt2ihtetvus.html

Java: class Node { int v; Node next; }
来源：http://dali.xuanzx.com/Article/details/gt2jkvaojhg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shuidangran.top/Article/details/gt2ixaqswix.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.birdmap.top/Article/details/gt2dulpvcvw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sxryk.cn/Article/details/gt2lzjubusd.html

[N11] 二叉树中序遍历
来源：http://dali.hfpthk.cn/Article/details/gt2gobrzbcu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gt2viyjxjsv.html

PHP:  // 手写递归函数
来源：http://dali.chenzaomai.com/Article/details/gt2rhxppnwt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gt2vcswfyzu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhixingplan.top/Article/details/gt2bhvqvmda.html

Java: // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gt2ozsywcuk.html

Go:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gt2hamspqhl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.meibo888.top/Article/details/gt2zzqtvbrv.html

C#:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2vfdnhfvz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ydzc1.top/Article/details/gt2huinzrrk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.316326.xyz/Article/details/gt2zqxzvmlh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuanzx.com/Article/details/gt2jsuzxozw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gt2wwzacakn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gt2vybygrzj.html


<!-- 参考信息 -->