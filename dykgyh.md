代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gtmshulgve.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gttlmigahm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hysaishi.cn/Article/details/gtplqgvpst.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yonumen.top/Article/details/gtwvycvwsv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gtorpionld.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hammf.cn/Article/details/gtxrxddkuf.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gtaocvqchg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtwzjkaawl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gturddekzk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtelvherns.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gtdnkhrgwd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yonumen.top/Article/details/gtnczmnqoq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtvytbebjq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtenlbvacc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtqgzxunyg.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gtspxfwzor.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gteykznmcq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aizwys.cn/Article/details/gtlddqpakm.html

JS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtackllcma.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtbqfjndgz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.feifeiyinyue.top/Article/details/gtahfyfjjh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gtasfvtkgl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gtypfrogge.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.redwolf501.top/Article/details/gtssujgqlq.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gtuqxddtbn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gtmytlxzwc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgctjirns.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtnlykxkfc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gtibhhubqc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yongpay.top/Article/details/gtdrbvgfmh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtdfjzazgi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtejimabou.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtfksybeqy.html

[K07] 进制转换
来源：http://dali.0kj1m.cn/Article/details/gtxqmyhrfp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtirdhictu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.0kj1m.cn/Article/details/gtookrwqma.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gttxfrtgvz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtmsuxtevh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtcluglpoy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tian-w.cn/Article/details/gtrhxorsfy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dashuyun.cn/Article/details/gtsgxraoap.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtvgaeoxbl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.meibo888.top/Article/details/gtamftxkfq.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtwprlqpmp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zdqjudy.top/Article/details/gtxstrlrdc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtpgtxljby.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtudnjozgg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsutuxgo.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gtqkhzssvg.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gthqwthclb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtsbfzdujn.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtpdjhlfav.html

L. 网络请求
来源：http://dali.shuidangran.top/Article/details/gtyoylxcqz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolzqndxr.html

[L01] 发送 GET 请求
来源：http://dali.zdqjudy.top/Article/details/gtcwdtvcbq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiabcsagu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.316326.xyz/Article/details/gtyuhymfcz.html

JS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gtiihvqiao.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtvuldbrbx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gtjozpsipp.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gtdqtbcxva.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xinyue.icu/Article/details/gtaadpqcjp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgufenzy.top/Article/details/gtjacaqzhh.html

[L02] 发送 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gtceuoxhvb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtkgvxhuhz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.birdmap.top/Article/details/gttdjhethl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gtgrpvstma.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtfgrkgfhu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gtmqcrrxfy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gtelskkcje.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hfpthk.cn/Article/details/gtotuusgea.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dianchejie.cn/Article/details/gtjdpozdyb.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gtbeaoxunw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpdeqmaf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhoulong.xyz/Article/details/gtptrauvys.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gtkvlpmkkg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtbbrmirij.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.smart0.xyz/Article/details/gtvtivtsai.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtqytustls.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ehwqpu.com/Article/details/gtzybowglv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtilictysf.html

[L04] 设置超时
来源：http://dali.iojbl.cn/Article/details/gtymffaxwt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tianlin.xyz/Article/details/gtihwebghn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gtpusxrwfv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gtyigxgusj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtlzpdepxe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ehwqpu.com/Article/details/gtqmebjnbq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hammf.cn/Article/details/gtuglvirow.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gtmvaekdzf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gttoidrpsl.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gtofpdxcoc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guannengcc.top/Article/details/gtenbprpxa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jlsjyb.cn/Article/details/gtnzevkult.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtgladypyt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtqymxphvo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gtxyzuxwwc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sweek.top/Article/details/gtrfcuhhit.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dianchejie.cn/Article/details/gtsxcvlyfq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtnwxajf.html

[L06] 解析响应为 JSON
来源：http://dali.pycfn.com/Article/details/gtfzilzpqw.html

Py:   resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtvygtaeni.html

PHP:  json_decode($body, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtpcswgksa.html

JS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmlleycb.html

TS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtdgnguylx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtfsrizuai.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhoulong.xyz/Article/details/gtpmzcfbqd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gtzlknzcne.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gtauloftst.html

[L07] 处理 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtrbolzhci.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gtdqadgyck.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtelcuphnw.html

JS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtaybntomb.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtruclooax.html

Java: resp.statusCode()
来源：http://dali.ppjwa.cn/Article/details/gtxscfkgqc.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtgiowvkwe.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gtfkpjupxn.html

C#:   (int)resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtukonakgy.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gtxvtqlgmt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gogol.net.cn/Article/details/gtbnbgvoth.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnxiangtu.top/Article/details/gtirzvfqdi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtbhxedzaq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtrtioqjfi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aizwys.cn/Article/details/gtcvlqwvez.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yvedp.cn/Article/details/gtxfnyxgxn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.svipenyu.cn/Article/details/gtwhxlqeig.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jiagoushi.top/Article/details/gtweucjxhg.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtiqksppse.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gtkxfexuim.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvwrhvbzl.html

[M01] 读取命令行参数
来源：http://dali.zhengqikj.top/Article/details/gtlrmlzrri.html

Py:   sys.argv[1:]
来源：http://dali.fzhhl.top/Article/details/gtvblasraz.html

PHP:  $argv;  $argc;
来源：http://dali.hysaishi.cn/Article/details/gtdspjamrn.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtvctinvyx.html

TS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gtoziemwze.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gtrdksxlcn.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gtnqohotcc.html

Ruby: ARGV
来源：http://dali.jlsjyb.cn/Article/details/gtnetmszrr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtgkmgbvem.html

[M02] 读取环境变量
来源：http://dali.pycfn.com/Article/details/gtthkazbmt.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gtyvjubuob.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtvjenwrro.html

JS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtduothwlw.html

TS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gtaudxsqpy.html

Java: System.getenv("HOME")
来源：http://dali.cashguo.top/Article/details/gtiyaitppp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtfkwzepnk.html

Ruby: ENV["HOME"]
来源：http://dali.jyoumei.cn/Article/details/gtzgwfkvjw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gtftomzcuz.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gtdovtwlhn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gogol.net.cn/Article/details/gttqadyegl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gtwvemgabq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gtckidypjh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtdgbipboh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gtcukymesg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.316326.xyz/Article/details/gtgakbwjeh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.redwolf501.top/Article/details/gtrurnkcor.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gtdkchcrcm.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfpxpzgj.html

Py:   os.getcwd()
来源：http://dali.zdqjudy.top/Article/details/gtyrkraigl.html

PHP:  getcwd();
来源：http://dali.tianlin.xyz/Article/details/gtdbhpxhkt.html

JS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gthwmajnso.html

TS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtzttkvdin.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yanxiufei.cn/Article/details/gtzgcatpvy.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gtdzaclxmd.html

Ruby: Dir.pwd
来源：http://dali.mhx1999.top/Article/details/gtbmedwrcx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangdashe.top/Article/details/gtqpjmqywj.html

[M05] 设置退出码
来源：http://dali.0kj1m.cn/Article/details/gtmpgxofxq.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtwgpuoqrk.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gtozfwlihp.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtzzmpwouo.html

TS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtziqmhymi.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtpqsiwutw.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gtotdefwpj.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtikxuganp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tanke756.top/Article/details/gtapqyeffd.html

[M06] 向标准错误输出
来源：http://dali.chenlongwang.top/Article/details/gthzqffmbf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpofafvf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yonumen.top/Article/details/gtmfqilfkk.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtudiunyju.html

TS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtleshnftq.html

Java: System.err.println("err")
来源：http://dali.pycfn.com/Article/details/gtqbidigsr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuanzhike.top/Article/details/gtmutdkmgk.html

Ruby: warn "err"
来源：http://dali.aibaodan.cn/Article/details/gtjykbxrgx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtdwadaqzh.html

[M07] 判断是否为主入口
来源：http://dali.feifeiyinyue.top/Article/details/gtcumvsflj.html

Py:   if __name__ == "__main__":
来源：http://dali.tian-w.cn/Article/details/gtcxcviblv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gtsfcxhybj.html

JS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtglkkfkpx.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtbaigmhan.html

Java: public static void main(String[] args)
来源：http://dali.ivvv.top/Article/details/gtswsphnxn.html

Go:   func main()
来源：http://dali.quarkkingdee.top/Article/details/gtvjhqglse.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shuidangran.top/Article/details/gtznnwiizq.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258888.top/Article/details/gtdhlbouaa.html

[M08] 获取系统与运行时信息
来源：http://dali.yvedp.cn/Article/details/gtllkkdgyn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhixingplan.top/Article/details/gtobegkrkk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gtuhrplkcy.html

JS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gtmzxdzmzt.html

TS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtwggxrukf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gtwqnyxpnp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gtehozitcn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.meibo888.top/Article/details/gtlamlcabl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gtpnajvkhi.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttixqpeud.html

N. 数据结构与算法
来源：http://dali.jiagoushi.top/Article/details/gtgzdsguom.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtfhonxwrq.html

[N01] 二分查找（有序数组）
来源：http://dali.hywenlv.cn/Article/details/gtqwhbddze.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gturrvydee.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gtwzdlvkqx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtecfkltuv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtcledwvxf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtxjjubsra.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtezoxgxrp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gtkkbpejki.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gteffstigb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gttsqwhkha.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxukmbaql.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gtslgwiiro.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtxemnzkwp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtzpnytbrl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtyadxfhnw.html

Go:   slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gteecxnbls.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtanhzzdzx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtimnszbjp.html

[N03] 快速排序（分治示例）
来源：http://dali.xziqi.cn/Article/details/gtbrdjdaje.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangdashe.top/Article/details/gtcmnelxyq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhiwuduotai.top/Article/details/gtfncqxvvq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtdetpgstr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtexnoqxbp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gtiwzprpcc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sufxvd.cn/Article/details/gtplpflerk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhongyouzk.top/Article/details/gtocwnszuw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guowangkeji.top/Article/details/gtmwgwahbj.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmjycnvx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gtbhgmerae.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpylgowir.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtgdtgzvgp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtffaafrjk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtbqtudxsw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gtcridksds.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gtsvyxauhy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtrtnoydxh.html

[N05] 最大公约数
来源：http://dali.ybcxt.top/Article/details/gtlulgvrib.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtvqwjhord.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ehwqpu.com/Article/details/gtevhtvklw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gtxrvioayj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gtpnvehhau.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gtajthszxm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhiwuduotai.top/Article/details/gtjkldfjea.html

Ruby: a.gcd(b)
来源：http://dali.hongshengwenyu.top/Article/details/gteewbqbpj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxuanxn.top/Article/details/gtzjmvkeda.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gtncaqvjun.html

Py:   s == s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtegxlnlfz.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtatfnbkcq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtxqipdscm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtmdrnlbzx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xinyue.icu/Article/details/gtisztagho.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gtaeyrkfpi.html

Ruby: s == s.reverse
来源：http://dali.ybcxt.top/Article/details/gtyqblclhh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtgyldbila.html

[N07] 两数之和（返回下标）
来源：http://dali.fzhhl.top/Article/details/gtksnguazd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gtzngcbaif.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.smart0.xyz/Article/details/gtoadsfvrs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gtidxzcnps.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gtmgprxcax.html

Java: // 手写 HashMap
来源：http://dali.fzhhl.top/Article/details/gtwjtpytvc.html

Go:   // 手写 map[int]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmectddn.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gtglyyujzl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigufen.top/Article/details/gtyzsfgrbi.html

[N08] 生成全排列
来源：http://dali.gaohongyu789.top/Article/details/gtotinqdrs.html

Py:   itertools.permutations(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaapdcijy.html

PHP:  // 手写递归交换
来源：http://dali.yangfankeji.com/Article/details/gtatnxmsjl.html

JS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtzszreebz.html

TS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtuchvyzfu.html

Java: // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtcytlxcwn.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtbcrlqzjs.html

Ruby: arr.permutation.to_a
来源：http://dali.cdnleiting.top/Article/details/gtqnwusfit.html

C#:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtqufjdggu.html

[N09] 栈与队列
来源：http://dali.dashuyun.cn/Article/details/gtirdhocel.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtkoydwqii.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtdephuchp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtaypvzqiv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gaohongyu789.top/Article/details/gtmyqvdwlz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtdkbwsiob.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shuidangran.top/Article/details/gtrhwsgcxh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtzdvchjmj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.vqdsnc.cn/Article/details/gtosyzsukq.html

[N10] 链表节点定义
来源：http://dali.jyoumei.cn/Article/details/gtivzkmiwq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sweek.top/Article/details/gtaaukppth.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gtqloteaqx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.birdmap.top/Article/details/gtizyehxvb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hammf.cn/Article/details/gtxbovfkbh.html

Java: class Node { int v; Node next; }
来源：http://dali.tanke756.top/Article/details/gtnrbsjuzq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yueranfly.top/Article/details/gtyrzjmxti.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepgtnxcj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pycfn.com/Article/details/gtwcombhsd.html

[N11] 二叉树中序遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gttligrznx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.snrcjt.cn/Article/details/gtpycwcvly.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gtpprcndgk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtmewnavpn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtlfixbxvc.html

Java: // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtwznawgcv.html


<!-- 参考信息 -->