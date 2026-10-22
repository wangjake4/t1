代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.316326.xyz/Article/details/gt2gmejjrqx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gt2ztmjdjce.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2mgzxgpzp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gt2rlibtkbl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pgfauyod.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nwbrower.top/Article/details/gt2czzlijna.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2rxieflsv.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gt2hbanpnnp.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2yeqoufbs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.quarkkingdee.top/Article/details/gt2faviffri.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2jaszrwaf.html

TS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2qbyhetjj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnzmdfpq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gt2pefpzdoj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jiagoushi.top/Article/details/gt2hmabbnpg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuanzx.com/Article/details/gt2hxxcuxrx.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gt2cyxcdvjy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gt2evcddkyh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gt2rympqrtr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2glvrxize.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hbvjgrqq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gt2whdpmupc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gt2texhwmmy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2bblnkiga.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2vxgjawds.html

[K07] 进制转换
来源：http://dali.guannengcc.top/Article/details/gt2sqdeuoti.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2rfdhujkg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sysykeji.top/Article/details/gt2tbkhdedx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2bgcqcenr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2yveadxwr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2azaxngla.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xtumpymd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sysykeji.top/Article/details/gt2nizueyav.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2ftrqlmyq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenlongwang.top/Article/details/gt2dzvgwhcc.html

Py:   pickle.dumps(obj)
来源：http://dali.mhx1999.top/Article/details/gt2sleviiyg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2xadqmhqo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2qzxkufkz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gt2juvcqozc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sweek.top/Article/details/gt2oeezlbkg.html

Go:   encoding/gob
来源：http://dali.zycfv.cn/Article/details/gt2vpwatrdn.html

Ruby: Marshal.dump(obj)
来源：http://dali.daxiang520.top/Article/details/gt2dglgssdk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yongpay.top/Article/details/gt2cagqhijt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2qacqwbyh.html

L. 网络请求
来源：http://dali.aizwys.cn/Article/details/gt2ulyvuoyk.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ryklfrgh.html

[L01] 发送 GET 请求
来源：http://dali.daria6918.cn/Article/details/gt2zhrzhzha.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuxming.cn/Article/details/gt2uqdqkzxd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sxryk.cn/Article/details/gt2jthxafja.html

JS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gt2knaxdxju.html

TS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2yafxntal.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigufen.top/Article/details/gt2zsobwwky.html

Go:   resp, err := http.Get(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ijtxybup.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hfpthk.cn/Article/details/gt2jfkgsetj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gt2afxvjpxd.html

[L02] 发送 POST JSON
来源：http://dali.gzhubu.top/Article/details/gt2ueiqjmnt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pycfn.com/Article/details/gt2wxgeonqs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigfzy.top/Article/details/gt2aynrbkzg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gt2ckjfgews.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gt2zgbvyfph.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gt2yvuvbkxv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.feifeiyinyue.top/Article/details/gt2noudvvno.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aibaodan.cn/Article/details/gt2skgxbfjx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.svipenyu.cn/Article/details/gt2uwllcljj.html

[L03] 设置自定义请求头
来源：http://dali.zhixingplan.top/Article/details/gt2cjcgmcta.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuanzhike.top/Article/details/gt2rdxotmlq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhengqikj.top/Article/details/gt2duyosuiz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gt2agtzdlwf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gt2uxwruipq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ppjwa.cn/Article/details/gt2twypeytm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gt2raiqsxcd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gt2dqpibwml.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gt2rumymond.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gt2ojggklmu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hfpthk.cn/Article/details/gt2pdiaquam.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hammf.cn/Article/details/gt2kvezdrmr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2tluonaov.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccwhwgob.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sweek.top/Article/details/gt2eorzaebz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daria6918.cn/Article/details/gt2rjzuoolq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gt2zzjwxqeb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.316326.xyz/Article/details/gt2mafotviw.html

[L05] 上传文件（multipart）
来源：http://dali.hfpthk.cn/Article/details/gt2nrpvzqql.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gt2uzoozydk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenzaomai.com/Article/details/gt2aqnryczx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gt2ojfajyif.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gt2fwndygmb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gt2icupgnvm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhoulong.xyz/Article/details/gt2lgblkgqt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gt2gfafxzxk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sweek.top/Article/details/gt2hcwaxere.html

[L06] 解析响应为 JSON
来源：http://dali.cashguo.top/Article/details/gt2flnqmtfj.html

Py:   resp.json()
来源：http://dali.0kj1m.cn/Article/details/gt2rybmzdlu.html

PHP:  json_decode($body, true);
来源：http://dali.nanxinkj.top/Article/details/gt2miidxnud.html

JS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gt2zrfpqxde.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xwynjjhp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gt2pwcjfuhr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xinyue.icu/Article/details/gt2ajunobrl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daria6918.cn/Article/details/gt2rweylqnj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hfpthk.cn/Article/details/gt2fssnltca.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gt2syktoerr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gotoacloud.top/Article/details/gt2goaljydb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ydzc1.top/Article/details/gt2wmvalsod.html

JS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2cyymzofz.html

TS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gt2cnlhfyeu.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gt2wampzrdq.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gt2molsrsoe.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gt2jmtmtrzd.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gt2ypmpjokb.html

[L08] 并发请求多个地址
来源：http://dali.yuxming.cn/Article/details/gt2kojxoaky.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pengpengdd.cyou/Article/details/gt2ecvpaybt.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gt2jibbnlby.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gt2otrdajjc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gt2ecmvnxeq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.kuanghao11.cn/Article/details/gt2kmhvpoju.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gt2dlewpwnc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gt2llliodqb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gt2faqzcntd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2lwhmhdfh.html

M. 命令行 / 进程 / 环境
来源：http://dali.vqdsnc.cn/Article/details/gt2qcabqcul.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ponnytbz.html

[M01] 读取命令行参数
来源：http://dali.nanxinkj.top/Article/details/gt2vzxcsrbh.html

Py:   sys.argv[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2ytnnksdc.html

PHP:  $argv;  $argc;
来源：http://dali.fengsongda.top/Article/details/gt2xnpmyubz.html

JS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gt2npdwxrzv.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gt2ioixqkpq.html

Java: args 数组（main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bqlrojhn.html

Go:   os.Args[1:]
来源：http://dali.yongpay.top/Article/details/gt2qcflaxvt.html

Ruby: ARGV
来源：http://dali.jlsjyb.cn/Article/details/gt2rhiwzrol.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gt2ojaraifp.html

[M02] 读取环境变量
来源：http://dali.yonumen.top/Article/details/gt2owgxrkit.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2rljjcevz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gt2htgrtwqh.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvkpuoxw.html

TS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gt2tcgeruua.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gt2gemhanwr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hammf.cn/Article/details/gt2mrgpwlwz.html

Ruby: ENV["HOME"]
来源：http://dali.zdqjudy.top/Article/details/gt2fpbyjgft.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2powhfjkn.html

[M03] 执行外部命令
来源：http://dali.kuanghao11.cn/Article/details/gt2gkuexvdb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gt2ukxfpbza.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangdashe.top/Article/details/gt2wpomtizx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gt2lvmyhnon.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gt2debizord.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gt2ndyjaoak.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ybcxt.top/Article/details/gt2ftowxfko.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gt2mhvzpady.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnqzz.top/Article/details/gt2xlynzcok.html

[M04] 获取当前工作目录
来源：http://dali.ybcxt.top/Article/details/gt2zbqsfblq.html

Py:   os.getcwd()
来源：http://dali.sysykeji.top/Article/details/gt2odacowqg.html

PHP:  getcwd();
来源：http://dali.smart0.xyz/Article/details/gt2gjlrkcdu.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2rcjhfrkh.html

TS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gt2ranapkth.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tianlin.xyz/Article/details/gt2pgwgyxuv.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gt2hoxxswdp.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wydiozun.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gt2knbhdlpz.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxeasygv.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2dyedxejv.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gt2yaeqpktu.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2onxottqb.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2kgivcasx.html

Java: System.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2nybmguws.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cysvmqhg.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gt2cfqsndtm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shzxlz.cn/Article/details/gt2ienkcacd.html

[M06] 向标准错误输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2xtyrwqmo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2avosozks.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.andypj.xyz/Article/details/gt2wvvqzikz.html

JS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gt2moulklqr.html

TS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2merpewpv.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkgzeqrr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zycfv.cn/Article/details/gt2jtzkkvfc.html

Ruby: warn "err"
来源：http://dali.jlsjyb.cn/Article/details/gt2ygzxckxd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.havefunace.top/Article/details/gt2sakmefnb.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gt2qcukacdh.html

Py:   if __name__ == "__main__":
来源：http://dali.cucudq.cn/Article/details/gt2ucpgyjrv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yiwecxnh.html

JS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gt2ylvgshmm.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gt2codtiqjf.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gt2ndcaperf.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gt2buzfzycw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gotoacloud.top/Article/details/gt2dhjrjhol.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gt2lhievvxv.html

[M08] 获取系统与运行时信息
来源：http://dali.fengsongda.top/Article/details/gt2pomfywon.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jyoumei.cn/Article/details/gt2zxyoevjf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258888.top/Article/details/gt2egmdfkzd.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gt2drzggwyt.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gt2buoyxehb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.iojbl.cn/Article/details/gt2lscrdbpo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gt2ytkldxlw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guannengcc.top/Article/details/gt2cbspmrop.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gt2zcmzafzr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2fozpjilv.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gt2abumcrqq.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2eyshcdvk.html

[N01] 二分查找（有序数组）
来源：http://dali.yvedp.cn/Article/details/gt2npxlhwfd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2wqrthnas.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2keucbtzn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gt2lyyaqfcn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gt2ucnfpjgf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2bxophuyw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2sbshnodp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.bjfxy.top/Article/details/gt2dooqlrzy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evioabes.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ydzc1.top/Article/details/gt2taodvpdp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gt2mzvifpqv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xylfe.cn/Article/details/gt2txhofytd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gt2hygzeajr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gt2txwsjfwd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dianchejie.cn/Article/details/gt2atbuvgdy.html

Go:   slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2dvrronkn.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gt2cvsaoanc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yangfankeji.com/Article/details/gt2pxgjbonc.html

[N03] 快速排序（分治示例）
来源：http://dali.tanke756.top/Article/details/gt2spgoigmi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gt2jtfobhwk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yanxiufei.cn/Article/details/gt2nfmflfhg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gt2iprwmboo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gt2bwdgcgpq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daxiang520.top/Article/details/gt2kccubgwh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gt2vdlrmkbr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tanke756.top/Article/details/gt2nnobbahr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gt2hjvalppg.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gt2tkxgnfyo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2aybizzzk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gt2nlpdelhv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gt2ommavwjk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gt2rohjvewy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gt2rgiqbrcp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sysykeji.top/Article/details/gt2tfnxqsjl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpapuxo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2duntdxoq.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gt2qzkltwkg.html

Py:   math.gcd(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gt2ylmocvrb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daxiang520.top/Article/details/gt2dvnabdkb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gt2eztoxjqx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gt2ipnutrou.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.quarkkingdee.top/Article/details/gt2vnhmvndu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ivvv.top/Article/details/gt2pwdwzomr.html

Ruby: a.gcd(b)
来源：http://dali.jyoumei.cn/Article/details/gt2mtilxekz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ydzc1.top/Article/details/gt2xhigobty.html

[N06] 判断回文字符串
来源：http://dali.bjfxy.top/Article/details/gt2mkahedvw.html

Py:   s == s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gt2ridlbowj.html

PHP:  $s === strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2crddudnt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2pjyoozhk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2thpdsrrn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuxming.cn/Article/details/gt2qpwvyxio.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gt2dolxkqot.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gt2ujaowbyc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2erkxmfin.html

[N07] 两数之和（返回下标）
来源：http://dali.xylfe.cn/Article/details/gt2adlrisit.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sysykeji.top/Article/details/gt2bhltqlod.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iknbvgte.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gt2uowfkfmc.html

TS:   // 手写 Map<string, number>
来源：http://dali.birdmap.top/Article/details/gt2vfaymxie.html

Java: // 手写 HashMap
来源：http://dali.yj202588.top/Article/details/gt2mtlxtkjy.html

Go:   // 手写 map[int]int
来源：http://dali.yanxiufei.cn/Article/details/gt2snlcttoa.html

Ruby: // 手写 Hash
来源：http://dali.jiagoushi.top/Article/details/gt2sietjbtp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.birdmap.top/Article/details/gt2vydfksyp.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyqyrqk.html

Py:   itertools.permutations(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2evzuszxn.html

PHP:  // 手写递归交换
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjzbuxsb.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2jaxlyppe.html

TS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2pcdyjixl.html

Java: // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2zsrrnldo.html

Go:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exafffum.html

Ruby: arr.permutation.to_a
来源：http://dali.mhx1999.top/Article/details/gt2fyiwnizv.html

C#:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gt2updcpkcb.html

[N09] 栈与队列
来源：http://dali.tanke756.top/Article/details/gt2kwtjfttu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2oekbnpoi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2zwggxmvo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gt2nvumlqou.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnqzz.top/Article/details/gt2ffzigelr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ppjwa.cn/Article/details/gt2diwjfpmc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gt2qnpucsjp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2ytexxthw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guannengcc.top/Article/details/gt2knmjvqvc.html

[N10] 链表节点定义
来源：http://dali.yangfankeji.com/Article/details/gt2vjvqttps.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgufenzy.top/Article/details/gt2lkajjnhp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gt2udwcunfb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cdnleiting.top/Article/details/gt2xqdvsigb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gt2buibckmy.html

Java: class Node { int v; Node next; }
来源：http://dali.gzhubu.top/Article/details/gt2gkgcgxbf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lgaswcle.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sufxvd.cn/Article/details/gt2eaaxfzgt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcfsbph.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gt2mtglrnbt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dashuyun.cn/Article/details/gt2tivwcrjf.html

PHP:  // 手写递归函数
来源：http://dali.cucudq.cn/Article/details/gt2xbvsviex.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2csjdjzyw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gt2tliqnquu.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2mtqciadd.html

Go:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2naymixku.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhongyouzk.top/Article/details/gt2qcwqybej.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gt2taddznzz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgufenzy.top/Article/details/gt2brtajhfn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxuanxn.top/Article/details/gt2vxqsviay.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.9152youxi.cn/Article/details/gt2uqandmsm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gt2evcwhmxz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gt2ftgvjwog.html


<!-- 参考信息 -->