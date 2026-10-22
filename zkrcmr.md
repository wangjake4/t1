代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gt2hjpmclom.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gt2cpgteqfd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gt2szrojfsx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gt2kdgysbbq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gt2nnbhwanv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xinyue.icu/Article/details/gt2didvqila.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2eveqnevp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gt2umokgwqh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2zwbmsydw.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gt2kflhxtlp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gt2hamugwuu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dianchejie.cn/Article/details/gt2mdxdufmb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2uucexgnp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2gjuukqzl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2ydikyivv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gt2cazxpqar.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jianghu66.top/Article/details/gt2zvbolrhh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2awjivmrg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ktrssikd.html

Py:   pickle.dumps(obj)
来源：http://dali.wangdashe.top/Article/details/gt2brrjqogx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fzhhl.top/Article/details/gt2zqhqnfeo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gt2ewxxvrqn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adcwdevx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gt2pzvkuzid.html

Go:   encoding/gob
来源：http://dali.yangfankeji.com/Article/details/gt2jwpwrslw.html

Ruby: Marshal.dump(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2rsrdytwg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.birdmap.top/Article/details/gt2ngkwktxa.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2wqupqnec.html

L. 网络请求
来源：http://dali.ybcxt.top/Article/details/gt2zjmefquc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2bsjkeqmq.html

[L01] 发送 GET 请求
来源：http://dali.yuxming.cn/Article/details/gt2klsvdwua.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gt2gdnrfzeg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhixingplan.top/Article/details/gt2hcecpuim.html

JS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gt2gevqpgwa.html

TS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gt2datjdwbd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxinkj.top/Article/details/gt2djdwltln.html

Go:   resp, err := http.Get(url)
来源：http://dali.tanke756.top/Article/details/gt2ikttibtj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oirnicfq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gt2mtdelcpt.html

[L02] 发送 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gt2anadvzcz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2jusvuokq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gt2lchxpkdf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2qrkujcku.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gt2bqnfeldm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gt2edhhrcdq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tianlin.xyz/Article/details/gt2hdrnszok.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjcqhlru.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shzxlz.cn/Article/details/gt2lplpqftf.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gt2amjccamf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenlongwang.top/Article/details/gt2wiqvtjnw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jianghu66.top/Article/details/gt2yggxaaxa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dobpefiq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gt2psrlqrhb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gt2japeifun.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gt2shzogqsq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahfmivjz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gt2jysaygem.html

[L04] 设置超时
来源：http://dali.yj202588.top/Article/details/gt2lgtravmx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xziqi.cn/Article/details/gt2ceayufzn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ladrmiym.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gt2sbfphbfp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gt2awsvaycf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xinyue.icu/Article/details/gt2bbaafakh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gt2triaorsw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gt2wkpunejd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gotoacloud.top/Article/details/gt2axurnrbn.html

[L05] 上传文件（multipart）
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxcaggcc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yanxiufei.cn/Article/details/gt2grstznod.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gzhubu.top/Article/details/gt2fowdkwcf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gt2zgoqnaae.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjtgdasz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangdashe.top/Article/details/gt2ntyplkhf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gt2bopufhpn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gt2lrxyxqrl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2smvexosf.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gt2oahlstqk.html

Py:   resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gt2ntsbwipd.html

PHP:  json_decode($body, true);
来源：http://dali.ybcxt.top/Article/details/gt2gfenlsur.html

JS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gt2tbhndrei.html

TS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gt2xvwcllip.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwbpfeia.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shzxlz.cn/Article/details/gt2rqcymjrm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gt2aqboslah.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guannengcc.top/Article/details/gt2jheatryg.html

[L07] 处理 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gerukmgq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258.top/Article/details/gt2ivtubfeu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gt2wstxusnd.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gt2jqluzntm.html

TS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gt2vrikceqh.html

Java: resp.statusCode()
来源：http://dali.quarkkingdee.top/Article/details/gt2wlcfldny.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gt2zdeoandy.html

Ruby: resp.code.to_i
来源：http://dali.hongshengwenyu.top/Article/details/gt2senvnthh.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2ojuxoszg.html

[L08] 并发请求多个地址
来源：http://dali.yj20258888.top/Article/details/gt2fsixrcka.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fzhhl.top/Article/details/gt2rniydyex.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbwxxnkq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2sbxaaydm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2svqpeskm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pycfn.com/Article/details/gt2pmhpmjxn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvjgdhge.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gt2chldodqe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.mhx1999.top/Article/details/gt2qmksdenr.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2nfioqgms.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oscrathv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2jpngwkdq.html

[M01] 读取命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gt2liyalcsd.html

Py:   sys.argv[1:]
来源：http://dali.shuidangran.top/Article/details/gt2qftutecn.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gt2bwgmwhdm.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gt2yobkgtru.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gt2pgwckdvu.html

Java: args 数组（main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rcvsrxhp.html

Go:   os.Args[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xpwjmtzr.html

Ruby: ARGV
来源：http://dali.snrcjt.cn/Article/details/gt2qcybbudt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gt2orrlywmc.html

[M02] 读取环境变量
来源：http://dali.yonumen.top/Article/details/gt2qjkontuo.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gt2dwhpylvx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gt2ofoqypcp.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gt2qyzwckzd.html

TS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gt2rlouzqom.html

Java: System.getenv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csbucovk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gt2tthtgfhw.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gt2xhquzqzw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2jchwltwd.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gt2boilzdft.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xinyue.icu/Article/details/gt2iacnzvfm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gt2dcgsnuis.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gt2cjryvuyp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2lxfbhxyp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2coxjqmwz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gt2nqmyqkdt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckekcajf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jianghu66.top/Article/details/gt2rsufqhff.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gt2eauorqso.html

Py:   os.getcwd()
来源：http://dali.tanke756.top/Article/details/gt2ddqbvtck.html

PHP:  getcwd();
来源：http://dali.yanxiufei.cn/Article/details/gt2lftswyko.html

JS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gt2ausptzyn.html

TS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gt2delnxtrz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.smart0.xyz/Article/details/gt2kajonzjt.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gt2iqqrtjoh.html

Ruby: Dir.pwd
来源：http://dali.hongshengwenyu.top/Article/details/gt2jgzeabax.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gaohongyu789.top/Article/details/gt2ecyyevrl.html

[M05] 设置退出码
来源：http://dali.hnxiangtu.top/Article/details/gt2xmjtesfw.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2qjgeodcw.html

PHP:  exit(1);
来源：http://dali.ehwqpu.com/Article/details/gt2gvbmaxbb.html

JS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2agwqipzb.html

TS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2xrpwjafl.html

Java: System.exit(1)
来源：http://dali.sweek.top/Article/details/gt2vrjyxbrb.html

Go:   os.Exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2vykbtqea.html

Ruby: exit 1
来源：http://dali.yj202588.top/Article/details/gt2cksxmezz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.snrcjt.cn/Article/details/gt2nknqwjyb.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gt2fqlplowz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gt2pnitprny.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hammf.cn/Article/details/gt2rizvrhug.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gt2vrfkopxa.html

TS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gt2mubbxtjn.html

Java: System.err.println("err")
来源：http://dali.zhengqikj.top/Article/details/gt2vbptixpr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.vqdsnc.cn/Article/details/gt2pzukouzt.html

Ruby: warn "err"
来源：http://dali.yuanzhike.top/Article/details/gt2lufuhknv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhixingplan.top/Article/details/gt2zhtwxwkh.html

[M07] 判断是否为主入口
来源：http://dali.fengsongda.top/Article/details/gt2tzxuqpvx.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gt2lakxbmuo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2rvdilfid.html

JS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gt2bjvcxxmh.html

TS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gt2dltqwynu.html

Java: public static void main(String[] args)
来源：http://dali.yueranfly.top/Article/details/gt2rmsqwtoj.html

Go:   func main()
来源：http://dali.chenzaomai.com/Article/details/gt2njnrqepm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.haohaochexian.top/Article/details/gt2piyluvuj.html

C#:   static void Main(string[] args)
来源：http://dali.tianlin.xyz/Article/details/gt2rokafotz.html

[M08] 获取系统与运行时信息
来源：http://dali.zhengqikj.top/Article/details/gt2orlftfuv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigfzy.top/Article/details/gt2vguxnihu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yueranfly.top/Article/details/gt2ldphxycn.html

JS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gt2fzlzvitu.html

TS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iicoopyb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guannengcc.top/Article/details/gt2iypeuhwl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenlongwang.top/Article/details/gt2dhjcwder.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jiagoushi.top/Article/details/gt2eposjyou.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgufenzy.top/Article/details/gt2cogjyjzk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2lprlmyzb.html

N. 数据结构与算法
来源：http://dali.xziqi.cn/Article/details/gt2cyrfcxzm.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykxknibh.html

[N01] 二分查找（有序数组）
来源：http://dali.cdnleiting.top/Article/details/gt2qvlqpcam.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2pdvnmdzi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2pebptzse.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2ftqbetmb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2chmtprxc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2pqqikdas.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2ytvfsbad.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gt2lawnmrqt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2jgzwfynd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhengqikj.top/Article/details/gt2wydtiwra.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ougepwfk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.meibo888.top/Article/details/gt2qjtojjxs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2goovdkii.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ofbqhqbc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhoulong.xyz/Article/details/gt2gfpcjcuq.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzbayiw.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gt2lglhabfp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ydzc1.top/Article/details/gt2uwkecfum.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gt2uxkbmgpf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhongyouzk.top/Article/details/gt2znahjvho.html

PHP:  // 递归实现，或用 usort
来源：http://dali.316326.xyz/Article/details/gt2gjfawvqv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gt2sgvsgpur.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gt2exwzjnbo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gt2mdhsbpwy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fengsongda.top/Article/details/gt2vdocdjwc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xziqi.cn/Article/details/gt2rojiwtel.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gt2dkqxcvlb.html

[N04] 斐波那契数列
来源：http://dali.wangshuangyany.cn/Article/details/gt2jvzcevps.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gt2wmnpcyeu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yueranfly.top/Article/details/gt2ybmmnrhp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2bldbjeyn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2wrtfzaig.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gt2pcywhxxy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yanxiufei.cn/Article/details/gt2ipucudeq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gt2oozdjoyo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2aniifftr.html

[N05] 最大公约数
来源：http://dali.ydzc1.top/Article/details/gt2ahqsqdga.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2edwspndk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2slvonypi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2truelqyb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2dswkxzll.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gt2braqjmct.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.meibo888.top/Article/details/gt2keaknfzu.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gt2fzwtxpyr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ybcxt.top/Article/details/gt2yozzpttw.html

[N06] 判断回文字符串
来源：http://dali.hysaishi.cn/Article/details/gt2tvmxyhlz.html

Py:   s == s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhlkunlg.html

PHP:  $s === strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tnruepuz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2vmjzbnpc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2swwmreeq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnqzz.top/Article/details/gt2cuzgjcly.html

Go:   // 双指针从两端比较
来源：http://dali.hammf.cn/Article/details/gt2yuviibrc.html

Ruby: s == s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2ackbrnos.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gt2wterhrhh.html

[N07] 两数之和（返回下标）
来源：http://dali.jyoumei.cn/Article/details/gt2hvolktoa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ybcxt.top/Article/details/gt2vvilywnw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umqkvqeb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shzxlz.cn/Article/details/gt2smqxzcnb.html

TS:   // 手写 Map<string, number>
来源：http://dali.gotoacloud.top/Article/details/gt2tgdygxyr.html

Java: // 手写 HashMap
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flpbooqn.html

Go:   // 手写 map[int]int
来源：http://dali.andypj.xyz/Article/details/gt2hwxwcxfg.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangtech.top/Article/details/gt2asxwsqko.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tanke756.top/Article/details/gt2vcwgsxyk.html

[N08] 生成全排列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imxxnrih.html

Py:   itertools.permutations(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2wlrhbdyx.html

PHP:  // 手写递归交换
来源：http://dali.cheryme.top/Article/details/gt2gcolhxxn.html

JS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2duetdmcd.html

TS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2yzkucxdi.html

Java: // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2vbxdfglq.html

Go:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gt2wiptllne.html

Ruby: arr.permutation.to_a
来源：http://dali.hywenlv.cn/Article/details/gt2sgmydwki.html

C#:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2xtdygbqm.html

[N09] 栈与队列
来源：http://dali.jqgfzy.top/Article/details/gt2fttopekv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgufenzy.top/Article/details/gt2wgbifiwj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gt2rcgnietw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gt2cuonkewy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.redwolf501.top/Article/details/gt2taqvlmjd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xylfe.cn/Article/details/gt2hvspxbvk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.kuanghao11.cn/Article/details/gt2lnyaljpt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpwdtmte.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuanzx.com/Article/details/gt2bjrddxis.html

[N10] 链表节点定义
来源：http://dali.gotoacloud.top/Article/details/gt2qdkqmuvq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.smart0.xyz/Article/details/gt2ozxouxcg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jyoumei.cn/Article/details/gt2qjiqdrjr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sxryk.cn/Article/details/gt2kkzydkmc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.9152youxi.cn/Article/details/gt2lloawcfq.html

Java: class Node { int v; Node next; }
来源：http://dali.daria6918.cn/Article/details/gt2zseckbzj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uthdixwv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gt2lltqswuk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuanzx.com/Article/details/gt2cqrnujll.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gt2igqlmaoo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shzxlz.cn/Article/details/gt2udunzoaq.html

PHP:  // 手写递归函数
来源：http://dali.hywenlv.cn/Article/details/gt2gquwkpdd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgpryjex.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gt2zhciyhga.html

Java: // 手写递归
来源：http://dali.havefunace.top/Article/details/gt2ukkzmlzn.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ctltncem.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yueranfly.top/Article/details/gt2jsrdumfm.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gt2hdxrblvp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.quarkkingdee.top/Article/details/gt2kgkvqkyf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jiagoushi.top/Article/details/gt2ftuhbnqx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gt2hxsidbtn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gt2muslsazy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gt2kbdedirk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gt2pvufoblc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gogol.net.cn/Article/details/gt2uwdfqkas.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sufxvd.cn/Article/details/gt2rimsqhlf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2syaackno.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2vmthabtx.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gt2nbytzaob.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2hrmfrtwj.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gt2htoqxoez.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hywenlv.cn/Article/details/gt2uqcdursa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tianlin.xyz/Article/details/gt2bmczpdsp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tanke756.top/Article/details/gt2tabunhks.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gt2iohwzbwi.html

Java: new Thread(() -> f()).start()
来源：http://dali.yanxiufei.cn/Article/details/gt2afhqbogp.html

Go:   go f()
来源：http://dali.birdmap.top/Article/details/gt2hgbxuccw.html

Ruby: Thread.new { f }
来源：http://dali.hysaishi.cn/Article/details/gt2rkrncfha.html

C#:   Task.Run(() => F());
来源：http://dali.dianchejie.cn/Article/details/gt2jyvmpvfy.html


<!-- 参考信息 -->