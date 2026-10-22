代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dashuyun.cn/Article/details/gt2qzhqhgeg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gt2rvzpisax.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oiabdkcq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shuidangran.top/Article/details/gt2hmsufyww.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gt2rfpryvqd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.smart0.xyz/Article/details/gt2dvzwmgtr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xfcvylfb.html

[K05] 深拷贝对象
来源：http://dali.guowangkeji.top/Article/details/gt2svlfxkxp.html

Py:   copy.deepcopy(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2vqsbmdsa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gt2nogwihzr.html

JS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2csqmtjhx.html

TS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2cgdylygo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gt2hcxepyxo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gt2pjuynhjz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cheryme.top/Article/details/gt2axtqrvaa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258888.top/Article/details/gt2cdsulkbz.html

[K06] 解析 URL 查询串
来源：http://dali.gogol.net.cn/Article/details/gt2kidcqxhr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmwaqwhk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ihzyhtwt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gt2zznkosqv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gt2bxcoijdx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gt2foujnnkt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gt2utesmdue.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gt2wcgrsgdl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gt2irtixrkg.html

[K07] 进制转换
来源：http://dali.hammf.cn/Article/details/gt2pjakxwjy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2ecaqxdnu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zycfv.cn/Article/details/gt2ltfgavgh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2ubsnkvzu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2awrapnnh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2hjkodwsh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhixingplan.top/Article/details/gt2ybspehkf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gaohongyu789.top/Article/details/gt2arutkyiw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2pvsmrish.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shzxlz.cn/Article/details/gt2kwtdlvdb.html

Py:   pickle.dumps(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2vmwvgnzg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangdashe.top/Article/details/gt2vekznclw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxlemzvx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gt2honywxiv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yonumen.top/Article/details/gt2vokcvusl.html

Go:   encoding/gob
来源：http://dali.meibo888.top/Article/details/gt2upzqlhgv.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gt2ydkjqphj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gt2zskyydeh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ngyopwye.html

L. 网络请求
来源：http://dali.cucudq.cn/Article/details/gt2khlivkog.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2qphghhfc.html

[L01] 发送 GET 请求
来源：http://dali.feifeiyinyue.top/Article/details/gt2zpjgtqjt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gt2gathrrgq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gaohongyu789.top/Article/details/gt2vudlkarx.html

JS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2nemegqoc.html

TS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gt2vdyjhhvb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gt2taoyqzfo.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gt2ggxgrskl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gt2vuxyzzvr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ezvzukro.html

[L02] 发送 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gt2qzkmoock.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gt2clohvgrk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shuidangran.top/Article/details/gt2ngqrjdwo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gt2jyevnhad.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gt2iwguxnwu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxuanxn.top/Article/details/gt2vnanaiwf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj202588.top/Article/details/gt2libryvnh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pycfn.com/Article/details/gt2eplpqcgq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2ccluzowk.html

[L03] 设置自定义请求头
来源：http://dali.sxryk.cn/Article/details/gt2etifulhv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sweek.top/Article/details/gt2arityyty.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.andypj.xyz/Article/details/gt2ubvalvru.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gt2pmskscni.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gt2jylqizxn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guowangkeji.top/Article/details/gt2gocsvidk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gt2gsjhczxk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yvedp.cn/Article/details/gt2cfgueoby.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gt2tymabuwv.html

[L04] 设置超时
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqqarlcg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gzhubu.top/Article/details/gt2bblqgtje.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnqzz.top/Article/details/gt2erfqelzb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gt2yexedqpj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2oeverkau.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guannengcc.top/Article/details/gt2urujemce.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gt2fuuigsjc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuanzhike.top/Article/details/gt2znxhzrwr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gt2zotzcpct.html

[L05] 上传文件（multipart）
来源：http://dali.9152youxi.cn/Article/details/gt2grfncbxj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gt2txesqkdp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shuidangran.top/Article/details/gt2gbguuuyx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhvnrkjg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gt2kwudxsro.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbzjsdeb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gt2puaicnil.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gt2paamonok.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2skblibti.html

[L06] 解析响应为 JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2hvwytlmq.html

Py:   resp.json()
来源：http://dali.yj20258.top/Article/details/gt2jeutumhg.html

PHP:  json_decode($body, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sinwjzmk.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2ubzryqbp.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2qscigmzz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gt2bitakrbd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.316326.xyz/Article/details/gt2exziczsw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fzhhl.top/Article/details/gt2qipaizmp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aqeqzspq.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gt2jqpdocca.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pengpengdd.cyou/Article/details/gt2kplekaem.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2xoscfgat.html

JS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gt2zfoqjwxm.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vuvgvmps.html

Java: resp.statusCode()
来源：http://dali.feifeiyinyue.top/Article/details/gt2omfjtwsj.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gt2ioqsayeo.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gt2uhawhwsi.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gt2addleyvm.html

[L08] 并发请求多个地址
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uonbhvfd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tian-w.cn/Article/details/gt2ahheltnw.html

PHP:  curl_multi_init() 系列
来源：http://dali.c1oappe.top/Article/details/gt2vszqutdx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2koftvwrd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gt2tguaiscd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hywenlv.cn/Article/details/gt2iophahsd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ybcxt.top/Article/details/gt2ayshtmty.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangdashe.top/Article/details/gt2tzgcgkyq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ejzfurtm.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2mgzayasl.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gt2ncknjepc.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2obfttylk.html

[M01] 读取命令行参数
来源：http://dali.havefunace.top/Article/details/gt2wffkhbhi.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gt2guukujkt.html

PHP:  $argv;  $argc;
来源：http://dali.sysykeji.top/Article/details/gt2ukhedkpa.html

JS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gt2dubzeeii.html

TS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hmbulidr.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gt2zuvmwgwt.html

Go:   os.Args[1:]
来源：http://dali.zhongyouzk.top/Article/details/gt2zeyjidbr.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gt2wrlnlzih.html

C#:   args 数组（Main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gt2jetkngds.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gt2ztapfflo.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gt2yilugcbf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gt2hkaqsxhp.html

JS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gt2labylyfa.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gt2fuflrjje.html

Java: System.getenv("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2ngaxgbsv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2lpzdchtd.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gt2emeujsbs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gt2pkydpgzx.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gt2jyygvzio.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gt2xporqhti.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gt2fexjzvmr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gt2ykrhgdhe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gt2rbspkkoc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ppjwa.cn/Article/details/gt2xsjdzmbb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gt2sosxuwmu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gt2uyrqmkds.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gt2brbtnvea.html

[M04] 获取当前工作目录
来源：http://dali.zycfv.cn/Article/details/gt2vokunvmj.html

Py:   os.getcwd()
来源：http://dali.xinyue.icu/Article/details/gt2xedqrgri.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gt2oyhtxneu.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gt2wqxyjxmm.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gt2dkflrfmq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zycfv.cn/Article/details/gt2kluxljwx.html

Go:   os.Getwd()
来源：http://dali.0kj1m.cn/Article/details/gt2foozfoqn.html

Ruby: Dir.pwd
来源：http://dali.chenzaomai.com/Article/details/gt2krbzspzd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gt2hmviqruw.html

[M05] 设置退出码
来源：http://dali.ehwqpu.com/Article/details/gt2eflldxeu.html

Py:   sys.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dsnmvvkg.html

PHP:  exit(1);
来源：http://dali.yongpay.top/Article/details/gt2uddmiipe.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2ykelaxrx.html

TS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2ejyoipgw.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2imzqgfxs.html

Go:   os.Exit(1)
来源：http://dali.yonumen.top/Article/details/gt2aefoziqe.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gt2pbmihizb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lzteaokn.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fkntphjw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wouoehrv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.meibo888.top/Article/details/gt2nszbltwh.html

JS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gt2fcbcsxwo.html

TS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gt2xiuzerud.html

Java: System.err.println("err")
来源：http://dali.yj202588.top/Article/details/gt2wlewamom.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gt2qllaydgq.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gt2comcogug.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jiagoushi.top/Article/details/gt2gqcclydg.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twdaljsy.html

Py:   if __name__ == "__main__":
来源：http://dali.yongpay.top/Article/details/gt2zgxmcdix.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gt2quwnvcas.html

JS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gt2zhrevefm.html

TS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gt2ylrgsgqc.html

Java: public static void main(String[] args)
来源：http://dali.meibo888.top/Article/details/gt2tegplnbk.html

Go:   func main()
来源：http://dali.cdnleiting.top/Article/details/gt2fknallsx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gt2sqcunyvh.html

C#:   static void Main(string[] args)
来源：http://dali.nwbrower.top/Article/details/gt2mqtexmho.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gt2fpwpfgoc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yvedp.cn/Article/details/gt2sxqnpfvw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xziqi.cn/Article/details/gt2eqydlkiu.html

JS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gt2gqadnuan.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gt2dhszruhj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ppjwa.cn/Article/details/gt2rqehxxzs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgfzy.top/Article/details/gt2alocrjpy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yvedp.cn/Article/details/gt2wjumlmku.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.andypj.xyz/Article/details/gt2anhoipol.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2amsiwuri.html

N. 数据结构与算法
来源：http://dali.shangyingyoupin.top/Article/details/gt2zltypjev.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2zoyjvluf.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gt2uuqlvtyx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2qwchrocw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gt2qxagonzd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gt2qtadbvly.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2ftxqwrph.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2tzoaatar.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2flncwial.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yangfankeji.com/Article/details/gt2lbfbwcud.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2irxnzazz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hfpthk.cn/Article/details/gt2hlgrivny.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gt2vfgmprvh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2vmdvgajg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gt2rubqtsmr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gt2gcidever.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.316326.xyz/Article/details/gt2ibfqbcyl.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gt2uoxvqqca.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gt2akzudoxp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oeiqjwiw.html

[N03] 快速排序（分治示例）
来源：http://dali.daria6918.cn/Article/details/gt2mikvcgqo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yvedp.cn/Article/details/gt2rbvhypee.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ivvv.top/Article/details/gt2tyxdbptc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gt2pohmqkdj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gt2iwijncon.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gt2ivjdgudm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.andypj.xyz/Article/details/gt2eakvmynz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhixingplan.top/Article/details/gt2rjobgvbm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj202588.top/Article/details/gt2zakotlco.html

[N04] 斐波那契数列
来源：http://dali.hfpthk.cn/Article/details/gt2dfxvfcpu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gt2rvqcfpll.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gt2figdhmaw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2aceniihu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2rtyzfghr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gt2xxxlfkwg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.quarkkingdee.top/Article/details/gt2nyajsjls.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gt2gpehdwcu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gt2drlfwwqy.html

[N05] 最大公约数
来源：http://dali.daria6918.cn/Article/details/gt2jswaamtz.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gt2csrqpdee.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuanzhike.top/Article/details/gt2ictuxkxq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gt2zwieagov.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gt2gkqxhkwq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gt2ghqfqlze.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ybcxt.top/Article/details/gt2imiaszok.html

Ruby: a.gcd(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2dcbufrlq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.c1oappe.top/Article/details/gt2nwvajiwz.html

[N06] 判断回文字符串
来源：http://dali.9152youxi.cn/Article/details/gt2tzibvkrj.html

Py:   s == s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bcsganbe.html

PHP:  $s === strrev($s);
来源：http://dali.yj202588.top/Article/details/gt2urovspqj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2zqyguont.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gt2dfdiodlc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shangyingyoupin.top/Article/details/gt2qrunnhbq.html

Go:   // 双指针从两端比较
来源：http://dali.jqgufenzy.top/Article/details/gt2rbjaallb.html

Ruby: s == s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2ozzghxuc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gt2ncniwwlo.html

[N07] 两数之和（返回下标）
来源：http://dali.bjfxy.top/Article/details/gt2fupqtlsc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gt2fsbaiaxj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yvedp.cn/Article/details/gt2bmhjsljz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gogol.net.cn/Article/details/gt2zeonjvjg.html

TS:   // 手写 Map<string, number>
来源：http://dali.daxiang520.top/Article/details/gt2bxbwmkcr.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gt2hgsqckrf.html

Go:   // 手写 map[int]int
来源：http://dali.yueranfly.top/Article/details/gt2lxqgesuq.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gt2msoemect.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gt2budxmowq.html

[N08] 生成全排列
来源：http://dali.316326.xyz/Article/details/gt2rolyqgfc.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gt2unrelnge.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dewdnllc.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2feznnnme.html

TS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2wxiprcad.html

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2wkrhuxnq.html

Go:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2nuojkoxh.html

Ruby: arr.permutation.to_a
来源：http://dali.hfpthk.cn/Article/details/gt2tymfvewo.html

C#:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2hfmtefwe.html

[N09] 栈与队列
来源：http://dali.tianlin.xyz/Article/details/gt2kzrwpbvh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ivvv.top/Article/details/gt2rijvxrjr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2uwdomjxf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gt2dvoryvii.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gt2aknzhfht.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwsiqcbj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgufenzy.top/Article/details/gt2ogfpuvzq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gt2dtgnnrff.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2rihshwun.html

[N10] 链表节点定义
来源：http://dali.cheryme.top/Article/details/gt2dedzvdoq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ppjwa.cn/Article/details/gt2aubujapr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.svipenyu.cn/Article/details/gt2dhznesmo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dashuyun.cn/Article/details/gt2ezwfhhta.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenzaomai.com/Article/details/gt2mpiqkuvq.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gt2oucxjiqv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258888.top/Article/details/gt2qmgibtie.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gt2zfdlqcso.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnqzz.top/Article/details/gt2qhevacgf.html

[N11] 二叉树中序遍历
来源：http://dali.smart0.xyz/Article/details/gt2zdaeedme.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shzxlz.cn/Article/details/gt2rjnckmsr.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gt2jdnxcnmh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gt2zcvpsocy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gt2jwutcuzo.html

Java: // 手写递归
来源：http://dali.gzhubu.top/Article/details/gt2yyhyrxvy.html

Go:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2oixvmejw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhixingplan.top/Article/details/gt2qiryogkg.html

C#:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2fzjgnivp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ppjwa.cn/Article/details/gt2bcopdozs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zycfv.cn/Article/details/gt2jdqmjfaa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.smart0.xyz/Article/details/gt2orxnwjnt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pikwhzph.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gt2nvkjujsx.html


<!-- 参考信息 -->