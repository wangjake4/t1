代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gt2svvrkmeg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2jthdyslq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bjosvqyj.html

Py:   pickle.dumps(obj)
来源：http://dali.shuidangran.top/Article/details/gt2vhtceguc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gt2oxzyrwyw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gt2qoqpxegu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gt2dccuhpyz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gt2pjfwwyxy.html

Go:   encoding/gob
来源：http://dali.yanxiufei.cn/Article/details/gt2mptwkbgx.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangdashe.top/Article/details/gt2wwqkmulb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gt2dstokrhx.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gejysufv.html

L. 网络请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftebnjbw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2dmxtudxq.html

[L01] 发送 GET 请求
来源：http://dali.pycfn.com/Article/details/gt2ckwhqzlj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gt2munqnpqr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gt2ldbtgjrf.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gt2fumjnznm.html

TS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gt2qglebxfk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.andypj.xyz/Article/details/gt2tjqjrgqw.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gt2ofjitgom.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gt2arszwshf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2nmwjjbgu.html

[L02] 发送 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gt2nogegrwu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gt2ouzzfcjx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qtjehvee.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gt2tbfqkylw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gt2xdpyqhvh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.smart0.xyz/Article/details/gt2jdbsfwsf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwgslimu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenlongwang.top/Article/details/gt2rkolwkhg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shzxlz.cn/Article/details/gt2gzleuvze.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gt2zxaulhtx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhoulong.xyz/Article/details/gt2yfusvfoh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gt2gnvvevma.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gt2gekmjeaw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gt2paqudbpb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangdashe.top/Article/details/gt2buuatrwz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tisftrxt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kbjmiipi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gt2phmoeyaf.html

[L04] 设置超时
来源：http://dali.nwbrower.top/Article/details/gt2hdqwsjiz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gt2nfhxvdud.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jiagoushi.top/Article/details/gt2gskyfusw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ydfyvost.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gt2wncfxdhw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ynbmxkko.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sweek.top/Article/details/gt2qjxnbygd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xylfe.cn/Article/details/gt2rxrgwadc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gt2enlysvjk.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gt2jveltnvr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangshuangyany.cn/Article/details/gt2oezhrxan.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daxiang520.top/Article/details/gt2mxkejbda.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gt2mfxftmnb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gt2agzgiwgy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jlsjyb.cn/Article/details/gt2ytfckqks.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2xduwcrnj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sufxvd.cn/Article/details/gt2fwvrnbbv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ivvv.top/Article/details/gt2eemmcwot.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gt2sxnmqwoz.html

Py:   resp.json()
来源：http://dali.smart0.xyz/Article/details/gt2jzqrtinm.html

PHP:  json_decode($body, true);
来源：http://dali.yvedp.cn/Article/details/gt2xwdpanow.html

JS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gt2pemhgxlf.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2dzrfdhgl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.smart0.xyz/Article/details/gt2eupegcty.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gt2wwlbhpox.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gt2xlrjfzkz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gt2bkmadlgs.html

[L07] 处理 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gt2klfhrghs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gt2uxsrielw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gt2nagtkbma.html

JS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gt2xascshaa.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gt2rkmizsbo.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gt2jghahval.html

Go:   resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpqzzpmp.html

Ruby: resp.code.to_i
来源：http://dali.pengpengdd.cyou/Article/details/gt2xrwxayda.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gt2qnzooazb.html

[L08] 并发请求多个地址
来源：http://dali.hammf.cn/Article/details/gt2kjamyakk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ybcxt.top/Article/details/gt2uadnpzfl.html

PHP:  curl_multi_init() 系列
来源：http://dali.shzxlz.cn/Article/details/gt2iqrnhmgr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2ahbxubyv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2nskhjbbh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gt2hmlykphn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhoulong.xyz/Article/details/gt2ojlvaooo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gt2fabacjbh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.316326.xyz/Article/details/gt2fwonkjwb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2jpdnztca.html

M. 命令行 / 进程 / 环境
来源：http://dali.yueranfly.top/Article/details/gt2cpqpladd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2brfdukgl.html

[M01] 读取命令行参数
来源：http://dali.ydzc1.top/Article/details/gt2bgpnvmfq.html

Py:   sys.argv[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2cezpwyur.html

PHP:  $argv;  $argc;
来源：http://dali.fzhhl.top/Article/details/gt2cvitzodt.html

JS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gt2egixxdah.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bawdwizn.html

Java: args 数组（main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gt2qnhbbpkj.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gt2xiixveir.html

Ruby: ARGV
来源：http://dali.xuanzx.com/Article/details/gt2ydxpqljy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2olgfayni.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gt2vhuusgzp.html

Py:   os.environ.get("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2lctjaypc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gt2qvnntoua.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2utaqwbmx.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnoscskm.html

Java: System.getenv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2vtohsjft.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2nyugrsfb.html

Ruby: ENV["HOME"]
来源：http://dali.jqgufenzy.top/Article/details/gt2nphjztln.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2sbwrytey.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gt2ucdsnciz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qyopiqrz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.andypj.xyz/Article/details/gt2xzxpjctx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gt2qssyvjgv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gt2nbyfrwac.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldxjqdgr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gt2btogibnn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pengpengdd.cyou/Article/details/gt2ulrahbqx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sufxvd.cn/Article/details/gt2ayfukbag.html

[M04] 获取当前工作目录
来源：http://dali.tianlin.xyz/Article/details/gt2yoolrdcy.html

Py:   os.getcwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2loqlyobc.html

PHP:  getcwd();
来源：http://dali.tianlin.xyz/Article/details/gt2jhjubvha.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2mneyfttv.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gt2ezuqsnff.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gt2oapedane.html

Go:   os.Getwd()
来源：http://dali.cqqwz.cn/Article/details/gt2hntklkvm.html

Ruby: Dir.pwd
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwmfkohq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgfzy.top/Article/details/gt2rxshttxk.html

[M05] 设置退出码
来源：http://dali.smart0.xyz/Article/details/gt2jcvhhice.html

Py:   sys.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2tbmizjaq.html

PHP:  exit(1);
来源：http://dali.gaohongyu789.top/Article/details/gt2aaissqrf.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2ponaisbr.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2dlpspwjw.html

Java: System.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2notqrvhi.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gt2dlmzxikw.html

Ruby: exit 1
来源：http://dali.meibo888.top/Article/details/gt2wtxnmlth.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gt2kzhcyfmw.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gt2rpsflljn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gt2vcegsauw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvujlkrh.html

JS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gt2zemllazr.html

TS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gt2zxqbssdp.html

Java: System.err.println("err")
来源：http://dali.316326.xyz/Article/details/gt2dbxpvtom.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cdnleiting.top/Article/details/gt2rhtypzam.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gt2lsvbncuv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daxiang520.top/Article/details/gt2ezwfomwj.html

[M07] 判断是否为主入口
来源：http://dali.shangyingyoupin.top/Article/details/gt2grcjkuss.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gt2lmizpbxx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gt2wkchnsrn.html

JS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gt2dllrwtlv.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gt2fjuphhfm.html

Java: public static void main(String[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cnjrbsdf.html

Go:   func main()
来源：http://dali.tianlin.xyz/Article/details/gt2vxoespnu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cdnleiting.top/Article/details/gt2iwtcroau.html

C#:   static void Main(string[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uomdiugo.html

[M08] 获取系统与运行时信息
来源：http://dali.fengsongda.top/Article/details/gt2rjogkvcw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gt2fpkpvtkf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gaohongyu789.top/Article/details/gt2ilnayevs.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gt2vprezbve.html

TS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gt2lkajtkah.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hywenlv.cn/Article/details/gt2qrqeybil.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dashuyun.cn/Article/details/gt2bhytlvix.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gt2fzxiafcq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gt2pcnjximl.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2usjfwmix.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gt2gwzhpjlp.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ckvwnemj.html

[N01] 二分查找（有序数组）
来源：http://dali.jyoumei.cn/Article/details/gt2fgauylsi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2vllgldip.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2iynvrqqr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gt2akqcysfr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2dnwwrgpr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2iwgzmtys.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2frclspan.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhixingplan.top/Article/details/gt2crfwdtvt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2xdkytolg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhongyouzk.top/Article/details/gt2ftmeiuwj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangdashe.top/Article/details/gt2wztbfvwg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gt2rkmduhzm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gt2zwiekbmq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fopvbons.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ppjwa.cn/Article/details/gt2qkdsdfjz.html

Go:   slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2ejkwafix.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gt2dpraeofc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yangfankeji.com/Article/details/gt2zbiwguhu.html

[N03] 快速排序（分治示例）
来源：http://dali.0kj1m.cn/Article/details/gt2wtwwsmln.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shangyingyoupin.top/Article/details/gt2fsojbiwi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gt2qkzywtbh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gt2ltoafhlz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gt2efhoixed.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gt2pwmerpba.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubqkihcy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuanzhike.top/Article/details/gt2jzobtqej.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gt2rqezdact.html

[N04] 斐波那契数列
来源：http://dali.xylfe.cn/Article/details/gt2viyghsyz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjobkzxr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmkqgnxt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrdvpazb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gt2ikjickle.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.meibo888.top/Article/details/gt2zfsrlcdj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fzhhl.top/Article/details/gt2hnftxnov.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gt2hdvvuzgw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2penrwapx.html

[N05] 最大公约数
来源：http://dali.yvedp.cn/Article/details/gt2kcextqaw.html

Py:   math.gcd(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlbiiqaa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhengqikj.top/Article/details/gt2xanqjjlq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2lceqdmzr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gt2jzjezgvn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cdnleiting.top/Article/details/gt2zvnwrqym.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yueranfly.top/Article/details/gt2khqcqcfg.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gt2mcheutvf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gt2zodeqeng.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gt2yxprbbvt.html

Py:   s == s[::-1]
来源：http://dali.fengsongda.top/Article/details/gt2qkqdvmnk.html

PHP:  $s === strrev($s);
来源：http://dali.xziqi.cn/Article/details/gt2kzuirqxz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2caikvrnw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2fxbzuzba.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.snrcjt.cn/Article/details/gt2yewkxzyh.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gt2jhvaaltc.html

Ruby: s == s.reverse
来源：http://dali.nwbrower.top/Article/details/gt2xuntjmhq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gt2tocwrgmz.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gt2mpuzysvy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jianghu66.top/Article/details/gt2mwlgxxrf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nwbrower.top/Article/details/gt2mfmrheak.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dianchejie.cn/Article/details/gt2dnrducpo.html

TS:   // 手写 Map<string, number>
来源：http://dali.xylfe.cn/Article/details/gt2obfheoyk.html

Java: // 手写 HashMap
来源：http://dali.yj20258.top/Article/details/gt2jjcdnvrs.html

Go:   // 手写 map[int]int
来源：http://dali.chenlongwang.top/Article/details/gt2skkljbqg.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gt2ackvkory.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ybcxt.top/Article/details/gt2wbretpol.html

[N08] 生成全排列
来源：http://dali.hammf.cn/Article/details/gt2vatmfwfd.html

Py:   itertools.permutations(arr)
来源：http://dali.andypj.xyz/Article/details/gt2kupmveyo.html

PHP:  // 手写递归交换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shqqmepo.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2kjmyxqba.html

TS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2ugotplcr.html

Java: // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2nugxnakm.html

Go:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2ykdjfows.html

Ruby: arr.permutation.to_a
来源：http://dali.wangdashe.top/Article/details/gt2spfrfitz.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2rpnwqznl.html

[N09] 栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gt2riltisba.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258888.top/Article/details/gt2brtqtitu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gt2pshyibhn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2yelvvftk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gt2bogmvujq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuanzhike.top/Article/details/gt2uifyiseq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.redwolf501.top/Article/details/gt2syivpfqf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2ppablmtp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigufen.top/Article/details/gt2rihdoapz.html

[N10] 链表节点定义
来源：http://dali.jinqigufen.top/Article/details/gt2wwhdlseo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gt2mycfscfn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ntrexiqh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2ktalqius.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fengsongda.top/Article/details/gt2dakeaoxe.html

Java: class Node { int v; Node next; }
来源：http://dali.cdnleiting.top/Article/details/gt2yyyderrd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.vqdsnc.cn/Article/details/gt2pefmhhze.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.vqdsnc.cn/Article/details/gt2uuccpvcd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gt2hmbnwoeq.html

[N11] 二叉树中序遍历
来源：http://dali.tianlin.xyz/Article/details/gt2tjhjfbxd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zdqjudy.top/Article/details/gt2sgsdaanj.html

PHP:  // 手写递归函数
来源：http://dali.birdmap.top/Article/details/gt2uthwfylb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gt2nhdzmaqh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gt2zmqxqvlt.html

Java: // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2rroinnab.html

Go:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gt2jwojdyoo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxinkj.top/Article/details/gt2bptbyclt.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gt2pnjqrorx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gt2couvxscw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sxryk.cn/Article/details/gt2xmvjneuq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigfzy.top/Article/details/gt2ahjkdvii.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gt2kqufxpda.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvfbytrb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gt2fpbtxqll.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fengsongda.top/Article/details/gt2qndclcyo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbhiduth.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gt2npthnesw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2vqicwlew.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gt2wualoqnn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2sjhfhvvl.html

[O01] 启动一个线程
来源：http://dali.snrcjt.cn/Article/details/gt2qqkrsuts.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cashguo.top/Article/details/gt2bstnwyzv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gt2mlachgcl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.snrcjt.cn/Article/details/gt2tssbbklw.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gt2yffmhruf.html

Java: new Thread(() -> f()).start()
来源：http://dali.guowangkeji.top/Article/details/gt2bhhlzygz.html

Go:   go f()
来源：http://dali.yuanzhike.top/Article/details/gt2itfivfum.html

Ruby: Thread.new { f }
来源：http://dali.hnqzz.top/Article/details/gt2ecnudfgx.html

C#:   Task.Run(() => F());
来源：http://dali.hongshengwenyu.top/Article/details/gt2yxbqjhuo.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gt2fqrdohpg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yonumen.top/Article/details/gt2glktsecs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tanke756.top/Article/details/gt2wvayjfdv.html

JS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2vhkkmyps.html

TS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gt2wurtmlvz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.havefunace.top/Article/details/gt2oipxppha.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gt2dgyjplvt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenlongwang.top/Article/details/gt2jfsktofn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuanzhike.top/Article/details/gt2qsajwaux.html

[O03] 加锁保护共享数据
来源：http://dali.ydzc1.top/Article/details/gt2lfecatja.html

Py:   with lock: shared += 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzqxhnfj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigfzy.top/Article/details/gt2jvzrednj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yueranfly.top/Article/details/gt2snxeeswh.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gt2ooqkbuul.html

Java: synchronized (this) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gt2sobmklyc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258.top/Article/details/gt2okyyivmh.html


<!-- 参考信息 -->