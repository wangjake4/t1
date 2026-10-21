代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtojhtytsx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtpvvzrrtd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtegmtryoh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuufrvmz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xziqi.cn/Article/details/gtbflollbi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtcbqqwnlk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jianghu66.top/Article/details/gtzxiyzsgv.html

Py:   pickle.dumps(obj)
来源：http://dali.gotoacloud.top/Article/details/gtxhgfujbq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sxryk.cn/Article/details/gtzlniityw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtzroyfpyz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gtbhdtqfki.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.quarkkingdee.top/Article/details/gtwpuwfkdm.html

Go:   encoding/gob
来源：http://dali.sufxvd.cn/Article/details/gtqxqjauqv.html

Ruby: Marshal.dump(obj)
来源：http://dali.bjfxy.top/Article/details/gtjoziarmt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtwabauavk.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtckksihpx.html

L. 网络请求
来源：http://dali.xinyue.icu/Article/details/gtggywxnkl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtuqiqzaou.html

[L01] 发送 GET 请求
来源：http://dali.xinyue.icu/Article/details/gtfjwkqdbh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gtafjczemb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobihadic.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gterrlclks.html

TS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtjxfyuhyf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gtvsoiugek.html

Go:   resp, err := http.Get(url)
来源：http://dali.meibo888.top/Article/details/gtpvpsigas.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cheryme.top/Article/details/gtfztllkyj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gttywywkza.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtaawfhhtw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtfjcopgwr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hongshengwenyu.top/Article/details/gtrwxzegod.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gtgqddwxwv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gtpmiiwekq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvhnutwc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gtdagdkunp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuxming.cn/Article/details/gtuulojruy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dashuyun.cn/Article/details/gtpdrnrgle.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gtnxoesyij.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpbbpwkr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnxiangtu.top/Article/details/gturpyhquu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtbxygttan.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gteyvhfjja.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gtcrswdliv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtzamvvgkz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gtzlmacjnv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gtnkixwwym.html

[L04] 设置超时
来源：http://dali.pengpengdd.cyou/Article/details/gtqwirgafh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gogol.net.cn/Article/details/gtbaxuibwj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daria6918.cn/Article/details/gtjknfwiyg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gtqoodyebr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtokjzrqul.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xinyue.icu/Article/details/gthpmeacdh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.0kj1m.cn/Article/details/gtrjaawxhd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gttydxvzlx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gtzxshbafl.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtedademar.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guannengcc.top/Article/details/gthounctlr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yvedp.cn/Article/details/gtemsgewmi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtcionuqhb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gtovukdjeb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuanzhike.top/Article/details/gtivcudetp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenlongwang.top/Article/details/gtughzotik.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gtdqpjrjyg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtgqqtahxw.html

[L06] 解析响应为 JSON
来源：http://dali.quarkkingdee.top/Article/details/gtucjixogl.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gtwljkkwok.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gtmrecisir.html

JS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gthwhgdqzd.html

TS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtkteslyij.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtspugadxy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sxryk.cn/Article/details/gtyqjdjmnr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gtvsvfysom.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sysykeji.top/Article/details/gtngljgcha.html

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtcmptipug.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gthmlaznli.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.snrcjt.cn/Article/details/gtwbmtmqme.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbpszdtx.html

TS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtvlhtirvp.html

Java: resp.statusCode()
来源：http://dali.xylfe.cn/Article/details/gtxwbgyfox.html

Go:   resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtnwlglvtu.html

Ruby: resp.code.to_i
来源：http://dali.zycfv.cn/Article/details/gtqhakkmiz.html

C#:   (int)resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtizrjqnuz.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gtfqexyluy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenjidiqi.icu/Article/details/gtoucdapll.html

PHP:  curl_multi_init() 系列
来源：http://dali.9152youxi.cn/Article/details/gtfotccrdw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtggjczvth.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdgvtzbd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gtcmkkawdp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxokwltmz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gtwahehzek.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtcalqdwkb.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtfftjnpzm.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gtinrgymzo.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxxmuhpjz.html

[M01] 读取命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtyxejfqhk.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gtjpphggwt.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gtpitotxvo.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtgfjuancb.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtvqiloype.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gtyeyenlkb.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gtredqenxw.html

Ruby: ARGV
来源：http://dali.jyoumei.cn/Article/details/gtpgnfgoog.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gtjkofvftd.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtsyvpuclg.html

Py:   os.environ.get("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtbvgskjom.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtoydqoehe.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvopzwvdc.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfdleyhw.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunsaadii.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fengsongda.top/Article/details/gtwfvpjufs.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gtjihvjynk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtbyknvpmq.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gtqxeimyhp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fengsongda.top/Article/details/gtoatytjkp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gtrwgpjjag.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtzuhqcrpi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtgfzucpjf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gtqcbdufrs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pengpengdd.cyou/Article/details/gtapcheytg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fengsongda.top/Article/details/gtrrappjiz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gtqsfnoswi.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gtnfaeleec.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwreclaku.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtxtojqzsb.html

JS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtfkunoaer.html

TS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gteojqmdrb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cdnleiting.top/Article/details/gtipormiov.html

Go:   os.Getwd()
来源：http://dali.cqqwz.cn/Article/details/gtythmqddu.html

Ruby: Dir.pwd
来源：http://dali.yj202588.top/Article/details/gtokeuytnb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigufen.top/Article/details/gthgedyznk.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkabblmg.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtwkpogugw.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtrktvonct.html

JS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtjvdosemh.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtdqsdadlb.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtniytppdf.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtfgfabjaf.html

Ruby: exit 1
来源：http://dali.hysaishi.cn/Article/details/gtpuuetclz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangdashe.top/Article/details/gtjegcbfww.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpeszzmye.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gtyhysybvr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sxryk.cn/Article/details/gtekplxjlf.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gteiumjrpl.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtytxhqsdr.html

Java: System.err.println("err")
来源：http://dali.fzhhl.top/Article/details/gtczpzdqrt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhongyouzk.top/Article/details/gtambxtulf.html

Ruby: warn "err"
来源：http://dali.jqgfzy.top/Article/details/gtzxfidhbv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gtzchzqxmx.html

[M07] 判断是否为主入口
来源：http://dali.c1oappe.top/Article/details/gtofibyupb.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gtosfkdbzp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gtzaytppcp.html

JS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gtrvbhpsfm.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtgxqgmxom.html

Java: public static void main(String[] args)
来源：http://dali.zhengqikj.top/Article/details/gtpvtmjumc.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gtrislszkd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuetiantiany.cn/Article/details/gtpbljxylj.html

C#:   static void Main(string[] args)
来源：http://dali.zdqjudy.top/Article/details/gtnqvktnzd.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gtdvcywcjw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gotoacloud.top/Article/details/gtmoslosnh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuxming.cn/Article/details/gtmbtywins.html

JS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtfyveultl.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gthsymfcbh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gtnleuaaap.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.iojbl.cn/Article/details/gtsedupxey.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gthramaxbi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gogol.net.cn/Article/details/gtfianfbro.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtktdbauxo.html

N. 数据结构与算法
来源：http://dali.jinghuilouyu.cn/Article/details/gtohosudck.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtuquhcrxt.html

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gtrfviciej.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtfkzlsouv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtcxishrpw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gtbubseebr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtwauricxs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gttoberaar.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.meibo888.top/Article/details/gtyvqyaayz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cheryme.top/Article/details/gtgcgrzgdh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtaltoxevd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewwqivhf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtemnxwrve.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tianlin.xyz/Article/details/gtifyvbrvj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gtvknvgfpz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtgodomsac.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gtkszihwwb.html

Go:   slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtlnwpvpoo.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtolxdormi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yanxiufei.cn/Article/details/gtpflipkel.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gtrbgyocgn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.316326.xyz/Article/details/gtxgjtmrcc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aizwys.cn/Article/details/gtlpicrxpv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gtkvhonkny.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gttzrwwocw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gtxgggyhcr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gtnufulzqc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj202588.top/Article/details/gtpdvirmfc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gtfsmcitdt.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gtwlrhvjxa.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtlpwqvuyq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tanke756.top/Article/details/gtoencmlfl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtumoqjbml.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtedzwcalq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtksqywgyx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangdashe.top/Article/details/gtlkfzihxo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtmpnujknx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdcyeokg.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gtotvrnstn.html

Py:   math.gcd(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtvefhhrfq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwlkvfwkl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gtsghyygaz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtiqvzdpll.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhongyouzk.top/Article/details/gtptanyhom.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxuanxn.top/Article/details/gthajgcbxb.html

Ruby: a.gcd(b)
来源：http://dali.0kj1m.cn/Article/details/gtfjfmwfie.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuxming.cn/Article/details/gtpfcueplw.html

[N06] 判断回文字符串
来源：http://dali.dashuyun.cn/Article/details/gtqlwqlkvh.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gtqduvxooa.html

PHP:  $s === strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gtabcjoisy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtegbrduig.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtldirkpul.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zycfv.cn/Article/details/gtjuyvtokt.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gttsauuuci.html

Ruby: s == s.reverse
来源：http://dali.sysykeji.top/Article/details/gtbpusyzpv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtistzpztx.html

[N07] 两数之和（返回下标）
来源：http://dali.cashguo.top/Article/details/gtdaxsqgvn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gtuwrsucqa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.havefunace.top/Article/details/gtpfoykqgx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nwbrower.top/Article/details/gtnvflxujz.html

TS:   // 手写 Map<string, number>
来源：http://dali.9152youxi.cn/Article/details/gtzvgvigpe.html

Java: // 手写 HashMap
来源：http://dali.dianchejie.cn/Article/details/gtinieptas.html

Go:   // 手写 map[int]int
来源：http://dali.zhiwuduotai.top/Article/details/gtcijsyvrq.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gticxfdzsk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gtlsrgcrgu.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gttfwbivwp.html

Py:   itertools.permutations(arr)
来源：http://dali.nwbrower.top/Article/details/gtwxbtvzql.html

PHP:  // 手写递归交换
来源：http://dali.yj20258888.top/Article/details/gtfziijofq.html

JS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtdafpveqx.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtfztzuqdh.html

Java: // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtddyfryqj.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtgorqarvr.html

Ruby: arr.permutation.to_a
来源：http://dali.kuanghao11.cn/Article/details/gtjjmezmdw.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtbupabkso.html

[N09] 栈与队列
来源：http://dali.xylfe.cn/Article/details/gtjtrbwsai.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fzhhl.top/Article/details/gtjkdaoutw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtayeprfzy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtirosatrq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cheryme.top/Article/details/gtsecxhtop.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtnuesmtvz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gtkgvacgkr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtegribnby.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gttrqpfuww.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gtjuqkndej.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hfpthk.cn/Article/details/gtptkatudx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cqqwz.cn/Article/details/gtzyzlktyc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gtodyevvor.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gteejocsws.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gtgvirbauv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gotoacloud.top/Article/details/gtiyxztvzg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegocexdi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuanzhike.top/Article/details/gtastmvnsx.html

[N11] 二叉树中序遍历
来源：http://dali.sweek.top/Article/details/gtrrcsofzm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttccntvkh.html

PHP:  // 手写递归函数
来源：http://dali.fzhhl.top/Article/details/gtdjdssslw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gtygediemb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtzqfwyjac.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gttqfvwkle.html

Go:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbgczjbf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ybcxt.top/Article/details/gtrbfbpbdn.html

C#:   // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtemnmuvsm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangtech.top/Article/details/gthcpvtkrw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigfzy.top/Article/details/gtbmjzblco.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cqqwz.cn/Article/details/gtkwudtfte.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gtqzcavsye.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtualzpvxr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gtbciohzrj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.haohaochexian.top/Article/details/gtovszjwyn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yangfankeji.com/Article/details/gtlagjynbe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtwxtokevu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtseaylzpt.html

O. 并发与异步
来源：http://dali.hongshengwenyu.top/Article/details/gtszbmonyg.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvdnnreit.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gtzfjgzxti.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daria6918.cn/Article/details/gtcguuevpl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sxryk.cn/Article/details/gtkmrcfyrs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuanzhike.top/Article/details/gtcosnzsdh.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gthimwhjdo.html

Java: new Thread(() -> f()).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtqpcdtebp.html

Go:   go f()
来源：http://dali.cdnleiting.top/Article/details/gtvnxgpspm.html

Ruby: Thread.new { f }
来源：http://dali.sysykeji.top/Article/details/gtprpvevfp.html

C#:   Task.Run(() => F());
来源：http://dali.xylfe.cn/Article/details/gtvguxqtos.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gtbmtzxkxi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangtech.top/Article/details/gthlrxtpjq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gteetqycbb.html

JS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gtfyzdqjol.html

TS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtixxdtpdg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.snrcjt.cn/Article/details/gtesxcqsfd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cheryme.top/Article/details/gtgbzyusva.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.0kj1m.cn/Article/details/gtlvnfnjjt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenzaomai.com/Article/details/gtiokziyyd.html

[O03] 加锁保护共享数据
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrbmbdrb.html

Py:   with lock: shared += 1
来源：http://dali.shuidangran.top/Article/details/gtckvunoyb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ppjwa.cn/Article/details/gtlqsodnyp.html


<!-- 参考信息 -->