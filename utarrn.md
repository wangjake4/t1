代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gttfpuwwsj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgufenzy.top/Article/details/gtvywppgjn.html

[K04] 读取 JSON 文件
来源：http://dali.ydzc1.top/Article/details/gthqatiuuf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daxiang520.top/Article/details/gtluwwtntx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dashuyun.cn/Article/details/gtpxgwcxrv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gtdpwazbvb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gttwlgrwuk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtlkwkssmc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtxavirsmw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gtmaolszei.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shuidangran.top/Article/details/gtpdwvrhek.html

[K05] 深拷贝对象
来源：http://dali.316326.xyz/Article/details/gtjcpvawuj.html

Py:   copy.deepcopy(obj)
来源：http://dali.cashguo.top/Article/details/gtylooyiee.html

PHP:  unserialize(serialize($obj));
来源：http://dali.bjfxy.top/Article/details/gtgjgimatr.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtunzzaleh.html

TS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtchevflep.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.haohaochexian.top/Article/details/gtdhakvfqv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gtbgnxpnvl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jiagoushi.top/Article/details/gtbrlipkgx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgufenzy.top/Article/details/gtslbykypg.html

[K06] 解析 URL 查询串
来源：http://dali.ehwqpu.com/Article/details/gtxtcjfqap.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtjsxvsota.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gtlsenjpsk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtnsmvwlzs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gtehwuwccz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gtpkggseni.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtmxxwezor.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtsgbxnxrw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtoqbhcyvj.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gtlcvzzvie.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtyljksokr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nwbrower.top/Article/details/gtgtidtcau.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtjravlobm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtdcrbvgvz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtqfsjcfmr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pengpengdd.cyou/Article/details/gtwmcvproe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gteguqemvl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtyyqtlqse.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gtiqgsaxqh.html

Py:   pickle.dumps(obj)
来源：http://dali.ybcxt.top/Article/details/gtyfxduydk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj202588.top/Article/details/gtwyicessz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlchhwtfj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtewshmqwk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jianghu66.top/Article/details/gtozskoegy.html

Go:   encoding/gob
来源：http://dali.zdqjudy.top/Article/details/gtknmoiech.html

Ruby: Marshal.dump(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtmsasbttr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtauzvbvle.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlczovpio.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gtjemsdctp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtntvvxgid.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gtefapqzfz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzzutsnl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nwbrower.top/Article/details/gtyadyiqyj.html

JS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gtkstxubcl.html

TS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtlohufqux.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywhwaqtm.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gtghevpzel.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.feifeiyinyue.top/Article/details/gtloxtdpoy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cdnleiting.top/Article/details/gtmvnzzgbf.html

[L02] 发送 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtayfakpib.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtizyvawie.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ivvv.top/Article/details/gtntydoqmx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtfaifypot.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gtiyhrqxzz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangdashe.top/Article/details/gtldputeqq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuetiantiany.cn/Article/details/gtscbiobti.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gtwwahafrd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gtrjsqmmad.html

[L03] 设置自定义请求头
来源：http://dali.snrcjt.cn/Article/details/gtlfjtxriu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.kuanghao11.cn/Article/details/gtffuyvucs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj202588.top/Article/details/gtvpzcjdiu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtbhgtltwh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhayguwq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gaohongyu789.top/Article/details/gtpfbbgxue.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtdtbpjdfh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aibaodan.cn/Article/details/gtdscexnqq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gtnfomxabb.html

[L04] 设置超时
来源：http://dali.dashuyun.cn/Article/details/gtxmqkqugj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.birdmap.top/Article/details/gtkipxyzfe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnddpoahv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtrljyzwfs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtqozoppch.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtqgjczlsp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shzxlz.cn/Article/details/gtcpggozdl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gtestkkiqz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtipxzufad.html

[L05] 上传文件（multipart）
来源：http://dali.sysykeji.top/Article/details/gtzhftftrf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gtydeibgsp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gtivqsdsry.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gtxamqhkmk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gtftremvzq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tanke756.top/Article/details/gtceyqeahs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.andypj.xyz/Article/details/gtzbbhmjuv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ydzc1.top/Article/details/gtyirwgait.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkiivxwf.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gtagkidiqb.html

Py:   resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtfgtptvhy.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gtnxftsjif.html

JS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gtxgdkudyf.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtgpxgxjyn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtewiecrzi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guannengcc.top/Article/details/gteadyfmdl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cdnleiting.top/Article/details/gtddxmlhop.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tian-w.cn/Article/details/gtpuzaknwz.html

[L07] 处理 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtyerdctau.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuxming.cn/Article/details/gtbhuqmxsa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.9152youxi.cn/Article/details/gtjknxekrh.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtljmwjglk.html

TS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtifzmvhow.html

Java: resp.statusCode()
来源：http://dali.yueranfly.top/Article/details/gtpunoyqoa.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtzvvldcuc.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwpscdsb.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtcgmgbjav.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gtpdmvutij.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangkeji.top/Article/details/gturzmqapq.html

PHP:  curl_multi_init() 系列
来源：http://dali.gotoacloud.top/Article/details/gtcbcjxjpu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtnxnuixcv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtsmuyyyqn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gtadvzcuty.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gturtpqedv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gtspzmahvq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtfakguper.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtqejejufi.html

M. 命令行 / 进程 / 环境
来源：http://dali.daria6918.cn/Article/details/gtjiubbpni.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtgjtpekfw.html

[M01] 读取命令行参数
来源：http://dali.yj202588.top/Article/details/gtxzaerwwo.html

Py:   sys.argv[1:]
来源：http://dali.tian-w.cn/Article/details/gtlpbldfoq.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gtnowqcfav.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gteynbvubu.html

TS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gtiryxopec.html

Java: args 数组（main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gtgasfvpnk.html

Go:   os.Args[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtynyiejsx.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gtobvehpiz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtvnfyaxiw.html

[M02] 读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gtumllbwyj.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gtehmaydvy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtpnpkaxcw.html

JS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gttktwgwpc.html

TS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gtqplmbjhk.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtzwwhibdy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtayhfdrqx.html

Ruby: ENV["HOME"]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolghquum.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtzmsgkkqw.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtueehxzua.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gtbarcrhwb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gthrkqmcsd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gthtbqhxxh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gthilgsmdw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jianghu66.top/Article/details/gtzicqttel.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gtuxvzzhby.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtkepwfb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylpvlemy.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gtklazaibc.html

Py:   os.getcwd()
来源：http://dali.yj20258.top/Article/details/gtmirjbzhm.html

PHP:  getcwd();
来源：http://dali.cqqwz.cn/Article/details/gtfqhqngmw.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtwpdomfzm.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtjozhdfhy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cdnleiting.top/Article/details/gtrywpenxr.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gtvmmsjjbj.html

Ruby: Dir.pwd
来源：http://dali.c1oappe.top/Article/details/gtfkiabwmh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gtflivpvmx.html

[M05] 设置退出码
来源：http://dali.0kj1m.cn/Article/details/gtdaebdypz.html

Py:   sys.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtadgvwqsk.html

PHP:  exit(1);
来源：http://dali.yuxming.cn/Article/details/gtriwyopuw.html

JS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtpotgzzfg.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gticwisjxp.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gthodgybch.html

Go:   os.Exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtfyrxwuyo.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtiyffphwo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cdnleiting.top/Article/details/gtyfzybetc.html

[M06] 向标准错误输出
来源：http://dali.jinqigufen.top/Article/details/gtrjhepgux.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtgwmrbjtr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yangfankeji.com/Article/details/gtjefgeqkp.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gtrjsiodrr.html

TS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gthhynhtzo.html

Java: System.err.println("err")
来源：http://dali.0kj1m.cn/Article/details/gtxokydekl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sysykeji.top/Article/details/gtuqxowypa.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gtuvhujmim.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jlsjyb.cn/Article/details/gtmnndhpxs.html

[M07] 判断是否为主入口
来源：http://dali.jyoumei.cn/Article/details/gtapwpfpas.html

Py:   if __name__ == "__main__":
来源：http://dali.hammf.cn/Article/details/gtfrqehreo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jyoumei.cn/Article/details/gtlnwwydss.html

JS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gtsolazzlv.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtavmtvnfs.html

Java: public static void main(String[] args)
来源：http://dali.quarkkingdee.top/Article/details/gtnqzjfbvx.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gtmyhregfp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.mhx1999.top/Article/details/gtrkqpvexk.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtljembrmm.html

[M08] 获取系统与运行时信息
来源：http://dali.jiagoushi.top/Article/details/gtqebogzdp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cheryme.top/Article/details/gtpkddeagk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj202588.top/Article/details/gtjkrbrlie.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtrxizgzza.html

TS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gtvydhfuqy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gthwrglerc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gtlgwnvgzp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhqibxkw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gotoacloud.top/Article/details/gttuyfapia.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtwjqwioka.html

N. 数据结构与算法
来源：http://dali.xylfe.cn/Article/details/gtbpfvdchy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtyvhwyqcs.html

[N01] 二分查找（有序数组）
来源：http://dali.daria6918.cn/Article/details/gtzkcdjyfm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtoxblcdqm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtcgtlefha.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtaugoofsn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtusxbplkk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gteyfbxliz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtpgpfsido.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gtmdmmvyki.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtrndkbsqe.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gtcxeghxqq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gtkvgkfrho.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtprzucigc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtewqcovac.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtvkadxlab.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gtammrovjj.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gthymhkvzw.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gtzhurjkqj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gzhubu.top/Article/details/gtwxjxmlft.html

[N03] 快速排序（分治示例）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahzbhmnv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.smart0.xyz/Article/details/gtrhfvxoib.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hysaishi.cn/Article/details/gtvlyryxbk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtisjmpwdj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gtfrrnvzoz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtfdgwsmlp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jianghu66.top/Article/details/gtfvvbcljt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gtejlldvvs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xylfe.cn/Article/details/gtqzvthsgo.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gtsiohvwkc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtxqdcxlak.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgzgqwaha.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtzxmjfotn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtahrdoick.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtwlepqzsj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gtgdwioqou.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtqybuvgmp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtrycgsgnx.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gtadmjjalf.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gtdspkhyvy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gtluwrtiyq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtzsypcyxb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtjxpvtcvu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.svipenyu.cn/Article/details/gtvjtffbub.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gthiatuqgh.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gtebcjqbeg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnexflsep.html

[N06] 判断回文字符串
来源：http://dali.meibo888.top/Article/details/gthflnqebs.html

Py:   s == s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gtfaxrkoui.html

PHP:  $s === strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtfijoywob.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtlpmcwinx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtshtkuvnw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenlongwang.top/Article/details/gtxbmnavis.html

Go:   // 双指针从两端比较
来源：http://dali.cashguo.top/Article/details/gtzdzcmlii.html

Ruby: s == s.reverse
来源：http://dali.guowangkeji.top/Article/details/gtyfrhlvxx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtkfuymnml.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gtzfxrvafj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hywenlv.cn/Article/details/gtfdmfbzdu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sysykeji.top/Article/details/gtmngffery.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gtlurlkubt.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gtmlhzehlp.html

Java: // 手写 HashMap
来源：http://dali.xuetiantiany.cn/Article/details/gttbswhask.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gtcrkpxobe.html

Ruby: // 手写 Hash
来源：http://dali.hywenlv.cn/Article/details/gtxvnizpzu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tian-w.cn/Article/details/gtxuyahgtf.html

[N08] 生成全排列
来源：http://dali.andypj.xyz/Article/details/gthfjjjtre.html

Py:   itertools.permutations(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtjupfgjpf.html

PHP:  // 手写递归交换
来源：http://dali.zhiwuduotai.top/Article/details/gtzwpjjjuo.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtshzaglmu.html

TS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtchjjkdad.html

Java: // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtfqfcaxph.html

Go:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtjkdywfqt.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgufenzy.top/Article/details/gtcdpirxyp.html

C#:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtabzvwnxo.html

[N09] 栈与队列
来源：http://dali.jiagoushi.top/Article/details/gtkzecuycy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtqwciigfz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtbjialzrm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtmbewoijb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.snrcjt.cn/Article/details/gtwszdcfqk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtnsvrxkfk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbydtrvy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtkkplbjex.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gogol.net.cn/Article/details/gtukzukzyb.html

[N10] 链表节点定义
来源：http://dali.dashuyun.cn/Article/details/gtnbbudfll.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xziqi.cn/Article/details/gtyolcjsrk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ivvv.top/Article/details/gtixrhdpex.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daxiang520.top/Article/details/gttfelzbch.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yonumen.top/Article/details/gtwunarjkv.html

Java: class Node { int v; Node next; }
来源：http://dali.daria6918.cn/Article/details/gtrxinvsvv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxuanxn.top/Article/details/gtuqllejjv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gtoeozwjvj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gtusmzhbys.html

[N11] 二叉树中序遍历
来源：http://dali.jlsjyb.cn/Article/details/gtdnorfmmq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gtrngwclhg.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gtblsecwwc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyfypygp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtnoqmadio.html

Java: // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtxqwxybiz.html

Go:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtaqsqojav.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuanzhike.top/Article/details/gtlotziatz.html

C#:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtmkuqbrnj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuetiantiany.cn/Article/details/gtdfhkkqta.html


<!-- 参考信息 -->