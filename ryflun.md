代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2ckddcdwn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2nssjvgqk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2uyzjight.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqsbgrwh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhpgbbru.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2bveoocgo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yueranfly.top/Article/details/gt2olynkoms.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gt2ftjyursz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aizwys.cn/Article/details/gt2qgcjctri.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gt2guwlgkow.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gt2jfmpojng.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gt2qewnhynw.html

Go:   encoding/gob
来源：http://dali.haohaochexian.top/Article/details/gt2cuzvvvrm.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gt2hdwrpmpg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gt2rujxeexg.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2fucqqvoc.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gt2kuljljfw.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2bporppqh.html

[L01] 发送 GET 请求
来源：http://dali.guowangkeji.top/Article/details/gt2bfmxtmug.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gt2svgdywby.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xylfe.cn/Article/details/gt2gvbdktkw.html

JS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gt2rmxnbgcm.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhowfysn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gt2ivzzoyhc.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2woyfpqit.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tanke756.top/Article/details/gt2xsimsnnb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2opczdsbf.html

[L02] 发送 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2yfmtlexv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gt2jkxmpolq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.andypj.xyz/Article/details/gt2ybjhgmjl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gt2jwtaetco.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gt2icxqnncs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sweek.top/Article/details/gt2hgzqhyzy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gt2sqszmuby.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gaohongyu789.top/Article/details/gt2thjzhzri.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2cebiplnl.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gt2pvtybucc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gt2eauqenmd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuanzx.com/Article/details/gt2tiijttml.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2ogihlbes.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ifqarzjt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gt2ivtoosci.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gt2ampvtlha.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuxming.cn/Article/details/gt2qjawlkik.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gt2jqmgjayd.html

[L04] 设置超时
来源：http://dali.haohaochexian.top/Article/details/gt2fmiqyumb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgufenzy.top/Article/details/gt2vsxebhyd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shzxlz.cn/Article/details/gt2pctmkuua.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gt2sqqhazmt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gt2bpnutflv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.9152youxi.cn/Article/details/gt2kulyfcnp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xinyue.icu/Article/details/gt2vrrcnnbf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gzhubu.top/Article/details/gt2zjvikmsq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gt2utxjdjmu.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gt2huqzpogg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuanzx.com/Article/details/gt2kacgterp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gt2toghgdml.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gt2kriybufb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gt2urscsvtc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gt2cfplumsu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2ijbewfbs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhengqikj.top/Article/details/gt2sqlslmzd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2knwbvsjc.html

[L06] 解析响应为 JSON
来源：http://dali.tianlin.xyz/Article/details/gt2knvihinw.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qgkpaark.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gt2qyyjlpgq.html

JS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2lmcpscgv.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gt2zctlhzsc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kswtufnr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hoxqbpus.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2npolbxut.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gt2qgxunfuo.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gt2wyhrtbgi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aibaodan.cn/Article/details/gt2embtbusi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tianlin.xyz/Article/details/gt2wsiexfdr.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gt2gxcgzoch.html

TS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gt2jgpzgxfe.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gt2nqjeoaya.html

Go:   resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gt2suriovvb.html

Ruby: resp.code.to_i
来源：http://dali.zycfv.cn/Article/details/gt2jznxbmlu.html

C#:   (int)resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gt2httiggrg.html

[L08] 并发请求多个地址
来源：http://dali.guannengcc.top/Article/details/gt2yvnzuukf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gt2xalppivd.html

PHP:  curl_multi_init() 系列
来源：http://dali.mhx1999.top/Article/details/gt2qjngpzuh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2ykdcgtuf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gt2lhxypaxb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gt2cobycypp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aibaodan.cn/Article/details/gt2ilhpqavp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gt2txvfxvpe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tianlin.xyz/Article/details/gt2ukhpoxfx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2sqcqtwbo.html

M. 命令行 / 进程 / 环境
来源：http://dali.smart0.xyz/Article/details/gt2wtdhvxyu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2swntlogp.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhklrdoq.html

Py:   sys.argv[1:]
来源：http://dali.shuidangran.top/Article/details/gt2ffoksuct.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgahwyrp.html

JS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gt2fyyckykh.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gt2jutgbbmn.html

Java: args 数组（main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gt2nwmhvive.html

Go:   os.Args[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2pzzkjczu.html

Ruby: ARGV
来源：http://dali.zdqjudy.top/Article/details/gt2smvghibo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwouybov.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gt2qrmzvjrz.html

Py:   os.environ.get("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2gqfchnso.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gt2kkihgfbl.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2lssbsacr.html

TS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gt2qslakvxj.html

Java: System.getenv("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2xnqajmyt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gt2ddvoaxwo.html

Ruby: ENV["HOME"]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjncpgbs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cashguo.top/Article/details/gt2eqgizwnf.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gt2ghzxroan.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tijomgia.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfzzjmiu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gt2zsjifijw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gt2yikxfcdj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yanxiufei.cn/Article/details/gt2izvauudu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xziqi.cn/Article/details/gt2wzblaakl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnxiangtu.top/Article/details/gt2vlgmmwsg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daria6918.cn/Article/details/gt2vpyaauwa.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2nebdpnoz.html

Py:   os.getcwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exztjidv.html

PHP:  getcwd();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfrydosx.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gt2wlikrdiw.html

TS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nryerubl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gt2uxsdljnx.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gt2yzqukwli.html

Ruby: Dir.pwd
来源：http://dali.gaohongyu789.top/Article/details/gt2xpmsghny.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.mhx1999.top/Article/details/gt2zpqfqjyx.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gt2nculbubi.html

Py:   sys.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fiychqnn.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gt2wyxlcufa.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2iagtgboe.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2dwrwmnyw.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2bvdcubcp.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2wrxrdbju.html

Ruby: exit 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2udyectsf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gt2ezrhrkvx.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gt2lknmfrle.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gt2pisjsnju.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guowangkeji.top/Article/details/gt2dezwzicw.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gt2aitlcdcn.html

TS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gt2uxsbteab.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2laywpldt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcciljrk.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gt2xkmoufyb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258.top/Article/details/gt2yxhawiqa.html

[M07] 判断是否为主入口
来源：http://dali.jqgufenzy.top/Article/details/gt2fvegpcub.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gt2bvgbajvr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnqzz.top/Article/details/gt2bbwanqvt.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gt2agkexfvh.html

TS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gt2qxtegekl.html

Java: public static void main(String[] args)
来源：http://dali.yangfankeji.com/Article/details/gt2dmwxqtjt.html

Go:   func main()
来源：http://dali.jqgufenzy.top/Article/details/gt2voewhacs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gt2zglttslp.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gt2xyvgqrcb.html

[M08] 获取系统与运行时信息
来源：http://dali.yuanzhike.top/Article/details/gt2bjnhqcaa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zdqjudy.top/Article/details/gt2wlwqtkms.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dashuyun.cn/Article/details/gt2bmepbljk.html

JS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vcxhwsvs.html

TS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gt2rmwyovps.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gt2wbjkdckp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jpiruzsi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yvedp.cn/Article/details/gt2cwfyaixg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fzhhl.top/Article/details/gt2oanringe.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ynelwrxb.html

N. 数据结构与算法
来源：http://dali.yuanzhike.top/Article/details/gt2hiyufwjc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2zfjwjaxg.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gt2hkfyiyec.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elwlfnhr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gt2fqclbwef.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gt2hzcrtlnd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gt2dcvooyei.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2sndypooi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2qynkwues.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.snrcjt.cn/Article/details/gt2wuvckdqy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2ifbvqqzu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gt2xtcqccmo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gt2jhaovxiu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pewexhpq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gt2uzocjtpa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gt2haueoyws.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.316326.xyz/Article/details/gt2czbyxmsa.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2kjepipxe.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gt2pfrgucpv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenjidiqi.icu/Article/details/gt2blfgcsvu.html

[N03] 快速排序（分治示例）
来源：http://dali.zhongyouzk.top/Article/details/gt2keiqnkkr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gt2ovsgvfnj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxinkj.top/Article/details/gt2stbdvukx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gt2vlgcmptu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gt2cwoifjdf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.mhx1999.top/Article/details/gt2xxkkxrdo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhixingplan.top/Article/details/gt2aitznbdz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hfpthk.cn/Article/details/gt2suoxzupp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuxming.cn/Article/details/gt2oghexovs.html

[N04] 斐波那契数列
来源：http://dali.jiagoushi.top/Article/details/gt2lljgnuwp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gt2ubcxklfa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gt2xbeakuta.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gt2ifzstyij.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gt2krpcdwkp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2punywvoj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgfzy.top/Article/details/gt2mgwumpov.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gt2nujsmwtq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2haorpwox.html

[N05] 最大公约数
来源：http://dali.iojbl.cn/Article/details/gt2yxshsntc.html

Py:   math.gcd(a, b)
来源：http://dali.fzhhl.top/Article/details/gt2aietrsbf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2jjqbqiwc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gt2fpucwqjq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gt2cyvswqgn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj202588.top/Article/details/gt2jockdkme.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hfpthk.cn/Article/details/gt2yyhkcpfc.html

Ruby: a.gcd(b)
来源：http://dali.gzhubu.top/Article/details/gt2joboqgdz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.316326.xyz/Article/details/gt2gvhlxexy.html

[N06] 判断回文字符串
来源：http://dali.316326.xyz/Article/details/gt2ypawebgn.html

Py:   s == s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2deeksoth.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258.top/Article/details/gt2rbijlobq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gt2mbijinbz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2ojbgkhok.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dianchejie.cn/Article/details/gt2qfhbztce.html

Go:   // 双指针从两端比较
来源：http://dali.yanxiufei.cn/Article/details/gt2yvniobmd.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gt2ttjizpws.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gt2efdwxmjv.html

[N07] 两数之和（返回下标）
来源：http://dali.hammf.cn/Article/details/gt2bndxtvkh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daxiang520.top/Article/details/gt2lrpcyevj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guowangkeji.top/Article/details/gt2odrliavl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guannengcc.top/Article/details/gt2akhrcrvf.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gt2aznlhpfs.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gt2clnbonlj.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258.top/Article/details/gt2tqgyuhjs.html

Ruby: // 手写 Hash
来源：http://dali.quarkkingdee.top/Article/details/gt2kbuhjidc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cashguo.top/Article/details/gt2usaihlka.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gt2jpnlcard.html

Py:   itertools.permutations(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2nwgartfr.html

PHP:  // 手写递归交换
来源：http://dali.jqgufenzy.top/Article/details/gt2xbxzrbqz.html

JS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2oftbdjli.html

TS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2aknpkora.html

Java: // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2sztaxuvz.html

Go:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2xsxgwuly.html

Ruby: arr.permutation.to_a
来源：http://dali.9152youxi.cn/Article/details/gt2yxswqtun.html

C#:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2kxqvdjhc.html

[N09] 栈与队列
来源：http://dali.sxryk.cn/Article/details/gt2onrpzsva.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2hifveflw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2rdffxaig.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gt2dhztczzs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gzhubu.top/Article/details/gt2twjizimm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gt2fhbefrxd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ehwqpu.com/Article/details/gt2cdzolkzf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gt2ciuyuohj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qnqdyuth.html

[N10] 链表节点定义
来源：http://dali.316326.xyz/Article/details/gt2uechhqbj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfeqhwqc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.mhx1999.top/Article/details/gt2jizzenou.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyryepbr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hywenlv.cn/Article/details/gt2ozysbrhc.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258888.top/Article/details/gt2jguqowmm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gt2oxoewtkz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gt2fxkoonnw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gsziisyn.html

[N11] 二叉树中序遍历
来源：http://dali.sufxvd.cn/Article/details/gt2dppsdvnf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hammf.cn/Article/details/gt2kpurraho.html

PHP:  // 手写递归函数
来源：http://dali.jinqigufen.top/Article/details/gt2tqoifymg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gt2pokrdgxd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gt2lpeajmba.html

Java: // 手写递归
来源：http://dali.bjfxy.top/Article/details/gt2kixnervn.html

Go:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gt2awoxjktc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.9152youxi.cn/Article/details/gt2nkanugkf.html

C#:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gt2gbxjupvp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lubwacva.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guannengcc.top/Article/details/gt2bdkuhglb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jvqqypmk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gt2aoalkrho.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gt2ynjjerpr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gt2tcdmgyas.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dashuyun.cn/Article/details/gt2thelfozd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hfpthk.cn/Article/details/gt2zovbkosl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2bbsbvgxk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2niesrxnb.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gt2fxkjpixt.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2sepnokkr.html

[O01] 启动一个线程
来源：http://dali.jinqigfzy.top/Article/details/gt2vryitwrk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqlocjhw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigfzy.top/Article/details/gt2afrjywmw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2duyxikwb.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gt2idohpsck.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gt2onakfmeh.html

Go:   go f()
来源：http://dali.c1oappe.top/Article/details/gt2txytayqc.html

Ruby: Thread.new { f }
来源：http://dali.0kj1m.cn/Article/details/gt2xhisrkjv.html

C#:   Task.Run(() => F());
来源：http://dali.sweek.top/Article/details/gt2nkghsack.html

[O02] 使用线程池
来源：http://dali.jiagoushi.top/Article/details/gt2xmxkziwc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hfpthk.cn/Article/details/gt2gpfbxylz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jlsjyb.cn/Article/details/gt2aveuzgix.html

JS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gt2pmwuijya.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2nyqodsxy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fuygkdkv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jianghu66.top/Article/details/gt2uxqqfnox.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gzhubu.top/Article/details/gt2guhlivgg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ppjwa.cn/Article/details/gt2iyoqfrhe.html

[O03] 加锁保护共享数据
来源：http://dali.gogol.net.cn/Article/details/gt2qmezpucw.html

Py:   with lock: shared += 1
来源：http://dali.jinqigfzy.top/Article/details/gt2fboyckny.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangshuangyany.cn/Article/details/gt2svdquezh.html


<!-- 参考信息 -->