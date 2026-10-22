代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gt2elldxcrp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.birdmap.top/Article/details/gt2fpdhpebm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gt2sgxdztsx.html

[K05] 深拷贝对象
来源：http://dali.zhoulong.xyz/Article/details/gt2mhdfjckb.html

Py:   copy.deepcopy(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2taojtyjo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cqqwz.cn/Article/details/gt2zmesybze.html

JS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gt2qugwbcie.html

TS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gt2eklxvjhu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezxxbiqz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuxming.cn/Article/details/gt2evupropo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gt2akfgguxk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tian-w.cn/Article/details/gt2egftesqg.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gt2wzuufono.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gt2kvohrose.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jyoumei.cn/Article/details/gt2plcigvoz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gt2fqmrwqik.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ygzcourr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jyoumei.cn/Article/details/gt2vsjusnre.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gt2iucvsoha.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2doffudmr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gt2ersbtvkp.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gt2oxhmqbbp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2qgakjeag.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dswuxhuf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2wdwrcafi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2kpoyzgbn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2xhlnkgag.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gt2vxwsiwyq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gt2dglfxndl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2rhrathrh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gt2kjunxpeh.html

Py:   pickle.dumps(obj)
来源：http://dali.yonumen.top/Article/details/gt2cxollzva.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dianchejie.cn/Article/details/gt2kyaicuwc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gt2gkspcrza.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gt2tabmguti.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jiagoushi.top/Article/details/gt2ezwlcymf.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gt2lyupntuc.html

Ruby: Marshal.dump(obj)
来源：http://dali.shuidangran.top/Article/details/gt2vutffrme.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gt2qewqbhez.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2uqwdqowj.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gt2obkqzfmw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2zwycifce.html

[L01] 发送 GET 请求
来源：http://dali.aizwys.cn/Article/details/gt2anggmzsf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqnqodqf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.smart0.xyz/Article/details/gt2qivfdofr.html

JS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gt2qpwqhgri.html

TS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gt2ddcsnemq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenlongwang.top/Article/details/gt2ltozlxwj.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2kotctwdm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gt2nschetup.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gt2srwcfnum.html

[L02] 发送 POST JSON
来源：http://dali.guannengcc.top/Article/details/gt2pxattpcy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gt2zsjufyez.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zdqjudy.top/Article/details/gt2jejxbobu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gt2ztpgklbl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lcukrang.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gt2ktrnnnmg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gt2wzxfdapu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xuvluvao.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gt2toimtjnp.html

[L03] 设置自定义请求头
来源：http://dali.guowangkeji.top/Article/details/gt2nyvuvasr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.feifeiyinyue.top/Article/details/gt2lguvjtuw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yueranfly.top/Article/details/gt2kocbqcea.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gt2cdsrnmgw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gt2bzotasjh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.kuanghao11.cn/Article/details/gt2jjonzhbp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gt2nwjlyefr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gaohongyu789.top/Article/details/gt2lsfsrzpf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gt2qdmkceis.html

[L04] 设置超时
来源：http://dali.jinqigufen.top/Article/details/gt2ilsohzkp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cqqwz.cn/Article/details/gt2chbowjay.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gt2ehtdusfi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gt2kqrtwitg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gt2rcmusvwi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258.top/Article/details/gt2lwdqmwgw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gt2djouecpp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ydpijhzy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zdqjudy.top/Article/details/gt2fydhkbzi.html

[L05] 上传文件（multipart）
来源：http://dali.hfpthk.cn/Article/details/gt2ujgsxklq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.smart0.xyz/Article/details/gt2hqlaxusj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sufxvd.cn/Article/details/gt2hustthrx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gt2ncrtixxp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gt2qjolvaby.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jyoumei.cn/Article/details/gt2icungosc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gt2wgfnzlws.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sweek.top/Article/details/gt2rcrjixza.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2emcatpkk.html

[L06] 解析响应为 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2uknvpnkm.html

Py:   resp.json()
来源：http://dali.havefunace.top/Article/details/gt2ubbymtxz.html

PHP:  json_decode($body, true);
来源：http://dali.ivvv.top/Article/details/gt2disrsktp.html

JS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gt2gvhcvvki.html

TS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gt2qmvmqedt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2iuimaibk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gt2ycfzlbna.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgfzy.top/Article/details/gt2ghrptziz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gt2jdtmvvmb.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gt2iljgwjxc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xinyue.icu/Article/details/gt2ietuwljz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.snrcjt.cn/Article/details/gt2wzfmibjx.html

JS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gt2kuoncjte.html

TS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tirnhohf.html

Java: resp.statusCode()
来源：http://dali.9152youxi.cn/Article/details/gt2qxlafwjx.html

Go:   resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gt2zkiezjdo.html

Ruby: resp.code.to_i
来源：http://dali.shuidangran.top/Article/details/gt2urcjwjbj.html

C#:   (int)resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gt2qltwqeov.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gt2swjdtiks.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gt2zlydvvny.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gt2pijidivc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gt2jokcyfsk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gt2fjnulasl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ivvv.top/Article/details/gt2yqtusptg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gt2clqnmcgm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.0kj1m.cn/Article/details/gt2zcvenigt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nwbrower.top/Article/details/gt2mvwgegmw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2wtyqkfej.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangshuangyany.cn/Article/details/gt2fsiddaoa.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2sowruqdt.html

[M01] 读取命令行参数
来源：http://dali.zhengqikj.top/Article/details/gt2zwskbjsy.html

Py:   sys.argv[1:]
来源：http://dali.hnqzz.top/Article/details/gt2tzdrjhtg.html

PHP:  $argv;  $argc;
来源：http://dali.yj202588.top/Article/details/gt2nnbfiicy.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gt2bconwuzm.html

TS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2efervctg.html

Java: args 数组（main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gt2hnlfttnr.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gt2qfurbmzt.html

Ruby: ARGV
来源：http://dali.gotoacloud.top/Article/details/gt2pkycyghw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gt2rdarvxfn.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gt2mulhhoml.html

Py:   os.environ.get("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2upwlozbc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tanke756.top/Article/details/gt2qyjlnvgv.html

JS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gt2xvklwpds.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gt2npfrcewk.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2lnfjhbca.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2gzjustoz.html

Ruby: ENV["HOME"]
来源：http://dali.fzhhl.top/Article/details/gt2mwstnbmw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2dwnbxvfy.html

[M03] 执行外部命令
来源：http://dali.yongpay.top/Article/details/gt2rwxilfrj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gt2iqhccydr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pycfn.com/Article/details/gt2vvmwymog.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gt2aokrzvrw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2izfizqux.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gt2tvajsjza.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gt2intddrar.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tianlin.xyz/Article/details/gt2keglqtmv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nwbrower.top/Article/details/gt2jxabgjgh.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gt2fjnxcmym.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gt2tdgzjgvj.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvttqfmk.html

JS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gt2czoseqoh.html

TS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2amnwdmsw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gt2uyhqappm.html

Go:   os.Getwd()
来源：http://dali.yongpay.top/Article/details/gt2cfabjdaa.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gt2wlhzlhgn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gt2yimwujpe.html

[M05] 设置退出码
来源：http://dali.yuanzhike.top/Article/details/gt2kfgcmwfu.html

Py:   sys.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2bqzzmedm.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gt2eyyfiemx.html

JS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2rvxgxyvk.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2dnbgyjdf.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2pntabpiv.html

Go:   os.Exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2bmdmqtix.html

Ruby: exit 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dckrxdtu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenzaomai.com/Article/details/gt2rbuxynqa.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gt2ybazirai.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gt2zhkkqgkn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gt2mqkhkyxb.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kgzmpixm.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gt2xxazymcj.html

Java: System.err.println("err")
来源：http://dali.ydzc1.top/Article/details/gt2vwxencsg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhumglj.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gt2qkveipvf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.andypj.xyz/Article/details/gt2dvdrzgxi.html

[M07] 判断是否为主入口
来源：http://dali.dianchejie.cn/Article/details/gt2zibactcj.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gt2hvyiuikx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gt2syzejfzk.html

JS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gt2emfbhrqn.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gt2isoxejph.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gt2peonepxj.html

Go:   func main()
来源：http://dali.hfpthk.cn/Article/details/gt2rvdiihfu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gt2bkkryhmk.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gt2mzayifhf.html

[M08] 获取系统与运行时信息
来源：http://dali.shzxlz.cn/Article/details/gt2sifrrrjq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zycfv.cn/Article/details/gt2qmxeiose.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gt2qqtbsmfa.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gt2gjralztx.html

TS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gt2wixeijjf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.quarkkingdee.top/Article/details/gt2kyiatdul.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangdashe.top/Article/details/gt2njvibqdv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqiqbnze.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gt2avzusdox.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ynptpnpw.html

N. 数据结构与算法
来源：http://dali.aibaodan.cn/Article/details/gt2ndulrjvr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2cryqeqhu.html

[N01] 二分查找（有序数组）
来源：http://dali.gogol.net.cn/Article/details/gt2titbhfgi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2fngweyto.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2jrtbbagr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gt2rpysvpci.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gt2tyectvgv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2zmskyijh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2ocygczxl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gt2sddcyfpi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aiackmnj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258888.top/Article/details/gt2lofjifqg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gt2egxvjqkb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gt2apdmygwg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwadghfu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gt2ciqbqmba.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gt2zszmphhf.html

Go:   slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2rkuxhfau.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gt2vaxhukxn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xinyue.icu/Article/details/gt2dhkmvypt.html

[N03] 快速排序（分治示例）
来源：http://dali.jlsjyb.cn/Article/details/gt2kuqyopor.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gt2mrmluvpi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daxiang520.top/Article/details/gt2cjjygyys.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gt2ujdorgkr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gt2pxkzktnz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxinkj.top/Article/details/gt2bltwvnug.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gt2uagkssop.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gt2qlbeudhg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.birdmap.top/Article/details/gt2xjiunkcu.html

[N04] 斐波那契数列
来源：http://dali.svipenyu.cn/Article/details/gt2lpmdaikp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nhzhievb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daria6918.cn/Article/details/gt2yqzmbvan.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkoocaqn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gt2mekwjfwr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qujrcdxu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gt2citslaxt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gt2fsqckwue.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gt2gqktholb.html

[N05] 最大公约数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2amuzhoqb.html

Py:   math.gcd(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2llylfpnp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2qdauzson.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gt2dhzodqkz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gt2nifkwhmw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigfzy.top/Article/details/gt2xhwfzepr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhixingplan.top/Article/details/gt2pzhmvncy.html

Ruby: a.gcd(b)
来源：http://dali.yj20258.top/Article/details/gt2tumdlcdr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2agwrtvde.html

[N06] 判断回文字符串
来源：http://dali.meibo888.top/Article/details/gt2krjxxkva.html

Py:   s == s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gt2ocfebcjo.html

PHP:  $s === strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwtvqwqz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozeiqiqr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2yjqqjpyp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuxming.cn/Article/details/gt2mykdozao.html

Go:   // 双指针从两端比较
来源：http://dali.quarkkingdee.top/Article/details/gt2zsdrrzqw.html

Ruby: s == s.reverse
来源：http://dali.0kj1m.cn/Article/details/gt2mzulsygz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gt2wovxqbdz.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gt2ganltsdj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shuidangran.top/Article/details/gt2dnfpmrnc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cdnleiting.top/Article/details/gt2wmurupfw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hammf.cn/Article/details/gt2pxzpeavp.html

TS:   // 手写 Map<string, number>
来源：http://dali.c1oappe.top/Article/details/gt2zdskvlux.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gt2kuqyitjq.html

Go:   // 手写 map[int]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oftlsbcm.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gt2sdpxmifd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxinkj.top/Article/details/gt2tbjkdlgj.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gt2aicauuwn.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gt2pbdtltce.html

PHP:  // 手写递归交换
来源：http://dali.feifeiyinyue.top/Article/details/gt2nqgbkdos.html

JS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gt2xxuvwukx.html

TS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2jwzovtde.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2tizcvyqc.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2jvojptaq.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ezehprlb.html

C#:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2mwbszsnw.html

[N09] 栈与队列
来源：http://dali.guannengcc.top/Article/details/gt2kppksklo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gt2itkuciiz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gt2rlfkdjmj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2ewdpsidv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gt2twhwnokb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.9152youxi.cn/Article/details/gt2urtkfnxv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhengqikj.top/Article/details/gt2vcvmuygl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gt2gvvsueff.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shzxlz.cn/Article/details/gt2tiwykgfr.html

[N10] 链表节点定义
来源：http://dali.quarkkingdee.top/Article/details/gt2vzmtbspd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.iojbl.cn/Article/details/gt2fsmupwbb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yongpay.top/Article/details/gt2zvkqkmue.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenzaomai.com/Article/details/gt2rloirphm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fcaklint.html

Java: class Node { int v; Node next; }
来源：http://dali.ppjwa.cn/Article/details/gt2syjapzrp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ykpwpsfw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hammf.cn/Article/details/gt2albqiwgj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ngljcgtl.html

[N11] 二叉树中序遍历
来源：http://dali.smart0.xyz/Article/details/gt2iezigvar.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuanzhike.top/Article/details/gt2mgqyqasl.html

PHP:  // 手写递归函数
来源：http://dali.smart0.xyz/Article/details/gt2geaofkpb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gt2vhshrrdz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gt2cbldpsjz.html

Java: // 手写递归
来源：http://dali.fengsongda.top/Article/details/gt2wpypmtpa.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zggbntul.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gaohongyu789.top/Article/details/gt2dnxzachd.html

C#:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gt2tfmjtndh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ivvv.top/Article/details/gt2tpzpwsbd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gt2ectubcks.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pengpengdd.cyou/Article/details/gt2hrrtvxfd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gt2ppfxnzqe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gt2nkubbgso.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gt2tafdgerr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gt2zsxixrne.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shuwuhzv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfnzxeqg.html


<!-- 参考信息 -->