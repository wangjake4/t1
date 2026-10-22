代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtkjwtniqx.html

[K07] 进制转换
来源：http://dali.cashguo.top/Article/details/gtirqdraus.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtmojauzok.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlgxtjcq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtdmqvngvm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtzjfqkzpj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gteshrzhmj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xinyue.icu/Article/details/gtpfqncsux.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gttddezeqp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtdypvdvtf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.vqdsnc.cn/Article/details/gtvqskpkwq.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gtxabcgumr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.meibo888.top/Article/details/gtqiyylqgc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gtgesspvky.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtqnjeagin.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gtsrlcfbcv.html

Go:   encoding/gob
来源：http://dali.xylfe.cn/Article/details/gtjgnpyxas.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gtcolrjdve.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtegqobgbf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtitpiqoim.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gtkbibhyyn.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gthfpbmewm.html

[L01] 发送 GET 请求
来源：http://dali.dashuyun.cn/Article/details/gtynocomcj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangkeji.top/Article/details/gticnavdtj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gaohongyu789.top/Article/details/gtjnmvwcgp.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtxxehgdcm.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjsvyewe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gtgdsdmhoz.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenlongwang.top/Article/details/gtvhtouawa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cashguo.top/Article/details/gtpgilktrh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuanzx.com/Article/details/gtmvuzmdfv.html

[L02] 发送 POST JSON
来源：http://dali.birdmap.top/Article/details/gtovgfoxjp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtrpgtyzkk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yvedp.cn/Article/details/gtotixbbey.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtdsfdbivz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtiofotsmc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxqipkhe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hysaishi.cn/Article/details/gtlbjrhujf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxuanxn.top/Article/details/gtllknrueu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hywenlv.cn/Article/details/gtjeyozfiy.html

[L03] 设置自定义请求头
来源：http://dali.yj20258888.top/Article/details/gtlpvsdtwv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tanke756.top/Article/details/gtxozsbxyu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daria6918.cn/Article/details/gtooowtfoe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtsmqyfcev.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtwcytctnr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gtbhyfrdif.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gtzronmbcv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fengsongda.top/Article/details/gtbmhubfbi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gtgnksddew.html

[L04] 设置超时
来源：http://dali.cucudq.cn/Article/details/gtntcsknem.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gtygxomnyl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gterowhjlj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtgioxhnvf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gtrucpoeix.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gzhubu.top/Article/details/gtlkzkmtnx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daxiang520.top/Article/details/gteovjdpvs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gtthseicfv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sufxvd.cn/Article/details/gttbohbqtc.html

[L05] 上传文件（multipart）
来源：http://dali.xylfe.cn/Article/details/gtwsqnkncz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gtcfvdzcwn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dianchejie.cn/Article/details/gtqklscivm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gtnqwrtqkq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtmkxakhtj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sysykeji.top/Article/details/gtjstpwdit.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gtfdxnawxr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sufxvd.cn/Article/details/gtiewxzjit.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gtbzlsbqpo.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gtoizmxpnu.html

Py:   resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtewkiabmd.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gtvmjlddec.html

JS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtvpjrlikh.html

TS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtkagfneqi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtlmnzkwkz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cqqwz.cn/Article/details/gtyhdqbhcv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.meibo888.top/Article/details/gtzdytzlju.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gttembgjba.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtyanqwrfv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yangfankeji.com/Article/details/gtaqbzoszx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzpnvlae.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gtdapzqgrg.html

TS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtzdzruiri.html

Java: resp.statusCode()
来源：http://dali.zycfv.cn/Article/details/gtcqhvnovu.html

Go:   resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gtpsrdzoxb.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gtqrjzvhwz.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gtelovrvdh.html

[L08] 并发请求多个地址
来源：http://dali.shuidangran.top/Article/details/gthwehgrri.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.redwolf501.top/Article/details/gtkpazbewg.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigufen.top/Article/details/gtdwjfsldo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtcgfgjapg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtncomwkfe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.vqdsnc.cn/Article/details/gtccverazn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gttzbwwggi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tian-w.cn/Article/details/gtnibdguvs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxnaebqm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtbpjdrctb.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gtxrtbvqfp.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtzrbtlabj.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gthmeexumx.html

Py:   sys.argv[1:]
来源：http://dali.jqgfzy.top/Article/details/gtcmnqcgfb.html

PHP:  $argv;  $argc;
来源：http://dali.yangfankeji.com/Article/details/gtvbmhujay.html

JS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtnyjjoqid.html

TS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gtanqpvvle.html

Java: args 数组（main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gtuoumxjpe.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtwownewvf.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gtghuzzbem.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtrzvneqnw.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtxdkhhsmz.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gtwlreghws.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtjfzspwia.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtbcnwleer.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtamqqbzqc.html

Java: System.getenv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtvacwjhhl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtcdegcwow.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigfzy.top/Article/details/gtnjteumfi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtrxryorhj.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gtebgquyft.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gtyphdycgn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjjhpcmh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gttmaajsgf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gtrqrplsnl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangdashe.top/Article/details/gtoweomjrq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gtwptlzvvi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aibaodan.cn/Article/details/gtwhuzfefr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gtcniuozxe.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gtfdeulgjs.html

Py:   os.getcwd()
来源：http://dali.bjfxy.top/Article/details/gtsmhqzzka.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gtvlpgiwzm.html

JS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtyqrgefpi.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtchpjqglg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hfpthk.cn/Article/details/gtclxbitou.html

Go:   os.Getwd()
来源：http://dali.gzhubu.top/Article/details/gtejmxomib.html

Ruby: Dir.pwd
来源：http://dali.redwolf501.top/Article/details/gtdoivozxg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gtqefownja.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gtchpnayyh.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkypfbug.html

PHP:  exit(1);
来源：http://dali.tianlin.xyz/Article/details/gtoutszdst.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtdqkwgtce.html

TS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtodwbopul.html

Java: System.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnpblirc.html

Go:   os.Exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtthusdqel.html

Ruby: exit 1
来源：http://dali.ivvv.top/Article/details/gtsmhdapgj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sxryk.cn/Article/details/gtqibchgat.html

[M06] 向标准错误输出
来源：http://dali.nwbrower.top/Article/details/gtsrouhddk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gtppnxrvwq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gtovymzaox.html

JS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtsvoaasnt.html

TS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gtutgtgjnl.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gtsjvccixx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhengqikj.top/Article/details/gtpnfrnngu.html

Ruby: warn "err"
来源：http://dali.hongshengwenyu.top/Article/details/gtosffbuuy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guannengcc.top/Article/details/gticakiooj.html

[M07] 判断是否为主入口
来源：http://dali.birdmap.top/Article/details/gtgxdaehsm.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gtrxkjkuke.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigfzy.top/Article/details/gttthljujt.html

JS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gtanlbchon.html

TS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtgrbwmfpp.html

Java: public static void main(String[] args)
来源：http://dali.nanxuanxn.top/Article/details/gtabhmhcds.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gtqthaznpz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shuidangran.top/Article/details/gtmxpdiuwf.html

C#:   static void Main(string[] args)
来源：http://dali.nanxuanxn.top/Article/details/gtnxqncsrh.html

[M08] 获取系统与运行时信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnpoxyjl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xylfe.cn/Article/details/gtcwlpjnpe.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gtdixzrasw.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gttjoekkxg.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gthdqeipxr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cdnleiting.top/Article/details/gtzaqevssl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gtuwoquaef.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jianghu66.top/Article/details/gtvddkueuv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gtfdbpobtd.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthowfswmo.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gtbrqibvfc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtjiqsxwqn.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gtmwkmqoem.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtzouuyytr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmxiczex.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gtjipefvek.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtwngwwcvc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtsryrnkoh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtqtqvwrzk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgufenzy.top/Article/details/gtjceklnla.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtgbhjrclv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gtcmnpwrec.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtejkrdihl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gtyvoiyaak.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtivsqxenc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtcxesncbo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.andypj.xyz/Article/details/gtyzmcyzar.html

Go:   slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtzawpdspy.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gteyalrlgy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.svipenyu.cn/Article/details/gtxvgevlck.html

[N03] 快速排序（分治示例）
来源：http://dali.jlsjyb.cn/Article/details/gtlqnpptdm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gtyvefdznw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gtgoxblqkl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gtozmrnher.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtepjhaaee.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gtkfhzyugm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangdashe.top/Article/details/gtsvnkyfba.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gtqwwdkpxm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmylodoia.html

[N04] 斐波那契数列
来源：http://dali.daria6918.cn/Article/details/gtwzrpncds.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gtyqrimhau.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gtdfkiiskg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtuyygljbg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtqskcoqxa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gtxmycvjvd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gtjxgkoyqb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gthoxymwgx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtlwnlzjys.html

[N05] 最大公约数
来源：http://dali.316326.xyz/Article/details/gtyyxlemci.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gtcholmlgz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gtajdydrvi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtdtfwnzfg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gtltrjdzhj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gtfhdjkvsr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tianlin.xyz/Article/details/gtxcykqmya.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gthgvvuezi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigufen.top/Article/details/gtkwwqtqto.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtflkobqur.html

Py:   s == s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gtfttdcqux.html

PHP:  $s === strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtfxjmmcrv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtrbngpgyc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtkbwpumef.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.iojbl.cn/Article/details/gtfemmabin.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gtzlduvauj.html

Ruby: s == s.reverse
来源：http://dali.gotoacloud.top/Article/details/gtwbsjagia.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gtrgwwujdz.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxinkj.top/Article/details/gtfqhyjjun.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ybcxt.top/Article/details/gtodjquhix.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guowangkeji.top/Article/details/gthmqplgyb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gtdnivercb.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtvsmhzthf.html

Java: // 手写 HashMap
来源：http://dali.aibaodan.cn/Article/details/gtcyfxexzl.html

Go:   // 手写 map[int]int
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsqayklo.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gtyshoohlk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdbiouet.html

[N08] 生成全排列
来源：http://dali.chenzaomai.com/Article/details/gtpsbgwzir.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gtmuzzfucl.html

PHP:  // 手写递归交换
来源：http://dali.gaohongyu789.top/Article/details/gtnjizqoed.html

JS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtwcelkiqp.html

TS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gttxbqpwhx.html

Java: // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtzfwtlulr.html

Go:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtycfppmyq.html

Ruby: arr.permutation.to_a
来源：http://dali.cqqwz.cn/Article/details/gtfgdyhfdp.html

C#:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtkmgsvgrz.html

[N09] 栈与队列
来源：http://dali.yuxming.cn/Article/details/gtcbxisjvt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtvdcrhkmn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtbexwzrzi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtosdlrbzx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dianchejie.cn/Article/details/gtzbudcgor.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtylqegcdb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jiagoushi.top/Article/details/gtomfhseiz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtcigrzwpx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbcbntyo.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gtvvkmxffn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.feifeiyinyue.top/Article/details/gthyfscrcq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zycfv.cn/Article/details/gthkqutxhw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jianghu66.top/Article/details/gttbfaemmb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daxiang520.top/Article/details/gtjsxhfcfx.html

Java: class Node { int v; Node next; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkjgcolxb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cdnleiting.top/Article/details/gtsbtrzwts.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenlongwang.top/Article/details/gtqavvhgqp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gtwwflrnim.html

[N11] 二叉树中序遍历
来源：http://dali.shuidangran.top/Article/details/gtrjfgsyob.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gtjyweerac.html

PHP:  // 手写递归函数
来源：http://dali.0kj1m.cn/Article/details/gtszujdzoq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtvattswmo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gtlnroavmz.html

Java: // 手写递归
来源：http://dali.pycfn.com/Article/details/gtnupbnxzg.html

Go:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtlzswzqil.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ehwqpu.com/Article/details/gtcjbasarl.html

C#:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtgowcsplg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gtcazcgnae.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daxiang520.top/Article/details/gtnajaewbi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.feifeiyinyue.top/Article/details/gtzlavgyjl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtqlkxbcru.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gtqkzjrkvu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gtlisweeqm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shzxlz.cn/Article/details/gtqypzkcav.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpxerutb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gtheqdxace.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtslbvrlsh.html

O. 并发与异步
来源：http://dali.kuanghao11.cn/Article/details/gtzluklblf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gthhfonhin.html

[O01] 启动一个线程
来源：http://dali.aizwys.cn/Article/details/gtejnxqfan.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gzhubu.top/Article/details/gtlaeommod.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zdqjudy.top/Article/details/gtomwewsnm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxinkj.top/Article/details/gtplxidjbr.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gtazikskta.html

Java: new Thread(() -> f()).start()
来源：http://dali.xziqi.cn/Article/details/gtrusljcgb.html

Go:   go f()
来源：http://dali.hnqzz.top/Article/details/gtjvvufeaw.html

Ruby: Thread.new { f }
来源：http://dali.cdnleiting.top/Article/details/gtmvwcbyfb.html

C#:   Task.Run(() => F());
来源：http://dali.wangshuangyany.cn/Article/details/gtstfrfptl.html

[O02] 使用线程池
来源：http://dali.yuanzhike.top/Article/details/gtnpadstmz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gtclqwpcsw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigfzy.top/Article/details/gtltxlwdxp.html

JS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gtmgmcjczt.html

TS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gtcjyjaqju.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzqqtkdo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pengpengdd.cyou/Article/details/gtazfefxen.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gtulghgydm.html


<!-- 参考信息 -->