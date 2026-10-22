代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258888.top/Article/details/gtahktmmbj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtxozyyrlv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gtngmqwame.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nwbrower.top/Article/details/gtncbpaytl.html

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gtawocrdmk.html

Ruby: Marshal.dump(obj)
来源：http://dali.dashuyun.cn/Article/details/gtyjhwxpsg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtbuzcodji.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtyzufvitl.html

L. 网络请求
来源：http://dali.hnqzz.top/Article/details/gtxrmovfxv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtilmoiuwq.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gtgeogugue.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gtprpmzomh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gtmmlkzmri.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtaengdbgg.html

TS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gthzxxykdz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cashguo.top/Article/details/gttthenixu.html

Go:   resp, err := http.Get(url)
来源：http://dali.shuidangran.top/Article/details/gtefuxjpak.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gtuihrjzqa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dashuyun.cn/Article/details/gtpwymukui.html

[L02] 发送 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtpsgkxsmc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gtasdfoxpy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenjidiqi.icu/Article/details/gtwraempih.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gtxwibtfcx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtumsqxvjf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenlongwang.top/Article/details/gtsgzzhlnh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gtrgudxvmw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gaohongyu789.top/Article/details/gthwofverk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxinkj.top/Article/details/gtmympqvdp.html

[L03] 设置自定义请求头
来源：http://dali.xuanzx.com/Article/details/gtntsfqeqi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.iojbl.cn/Article/details/gtwayjjhng.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gtxsdfycfs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtuffgnhth.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtolpgkqyd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangshuangyany.cn/Article/details/gtkszjuttz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gtqdasagpd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.meibo888.top/Article/details/gtirkphyjb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gtxpbkhylh.html

[L04] 设置超时
来源：http://dali.hammf.cn/Article/details/gtbqfycarg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hfpthk.cn/Article/details/gtmzyqbefv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gtckcooxqw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblabqehp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtixfycywf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guannengcc.top/Article/details/gtqsxtyuqx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tian-w.cn/Article/details/gtcqmxsnke.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sxryk.cn/Article/details/gtvygywmja.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gtmjzefwsl.html

[L05] 上传文件（multipart）
来源：http://dali.hammf.cn/Article/details/gtsgkrfwbf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gtihthphfq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgufenzy.top/Article/details/gtraidlsua.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtxggerkhp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gtkplukjas.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gteqszsshz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuanzx.com/Article/details/gtindbixvg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fengsongda.top/Article/details/gtwklnmiga.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtqfgvxiyc.html

[L06] 解析响应为 JSON
来源：http://dali.zycfv.cn/Article/details/gtdhynkmjr.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gtwenpavyt.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gtwpcablco.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtmcybrrmq.html

TS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtefzxbcbs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtcortllws.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtundygkxz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigfzy.top/Article/details/gtkaqfhece.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258888.top/Article/details/gtvkxhhrmo.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtflelmxvp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.svipenyu.cn/Article/details/gtntktwsjm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxuanxn.top/Article/details/gtslhkmlpz.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gthxnhkopt.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gtmmncfayf.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gtuvplvovk.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtutyzzbpw.html

Ruby: resp.code.to_i
来源：http://dali.hfpthk.cn/Article/details/gtudgytpfm.html

C#:   (int)resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gtkggtjjpj.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gtmxwafxlz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gttkgfrvsp.html

PHP:  curl_multi_init() 系列
来源：http://dali.tanke756.top/Article/details/gtazbwlvoy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtqaifxnxx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtqtfyflum.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gtjcprqkuh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuetiantiany.cn/Article/details/gtyjlalpzs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zdqjudy.top/Article/details/gtqtrgscpv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtdypwvfvv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtthmwbpnf.html

M. 命令行 / 进程 / 环境
来源：http://dali.ivvv.top/Article/details/gtqhsvetla.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtpxsacchw.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gtbgcyqnbm.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gterxamrif.html

PHP:  $argv;  $argc;
来源：http://dali.yangfankeji.com/Article/details/gtueaifpyn.html

JS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtpxxrtkfm.html

TS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtokzprqur.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtyswcgyuv.html

Go:   os.Args[1:]
来源：http://dali.tian-w.cn/Article/details/gtzfuwoafg.html

Ruby: ARGV
来源：http://dali.zdqjudy.top/Article/details/gtyaqepwcx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtxamsungs.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gtdyeotoky.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gtqjcxkiov.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtnvimulby.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtelwgshzv.html

TS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gtbufiuxza.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtapcyhthc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtrjkngkeu.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gtxnsfcpqz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gzhubu.top/Article/details/gttrtcexul.html

[M03] 执行外部命令
来源：http://dali.xylfe.cn/Article/details/gtnklftpyc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jianghu66.top/Article/details/gtykpfweli.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigufen.top/Article/details/gtkxuoatbm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbhsoklc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtplvcdkkd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guannengcc.top/Article/details/gtsfxmkdug.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.vqdsnc.cn/Article/details/gtyqfilgoy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangdashe.top/Article/details/gtpucysqkt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtgxmtdx.html

[M04] 获取当前工作目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryvcxcmi.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gtxioziwkw.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gtjoxhbzvu.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtupvhqanv.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtwfjkpofe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.316326.xyz/Article/details/gtpqnwydui.html

Go:   os.Getwd()
来源：http://dali.fzhhl.top/Article/details/gtohdyxtxz.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtzscbcgua.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gtqckykvrf.html

[M05] 设置退出码
来源：http://dali.wangshuangyany.cn/Article/details/gtpnxwsuua.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtufdinyiu.html

PHP:  exit(1);
来源：http://dali.ybcxt.top/Article/details/gtnrfsakrf.html

JS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gtnjpkzggy.html

TS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtsxbbhrtb.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtqroyavjj.html

Go:   os.Exit(1)
来源：http://dali.fzhhl.top/Article/details/gtgczjqgxd.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gtggcbgzjo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jianghu66.top/Article/details/gtfcnadmzi.html

[M06] 向标准错误输出
来源：http://dali.gaohongyu789.top/Article/details/gtzbcobsal.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gtrlntblea.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tanke756.top/Article/details/gtfpqmtcci.html

JS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gtuijvmvqr.html

TS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtggslhyot.html

Java: System.err.println("err")
来源：http://dali.nanxinkj.top/Article/details/gtludnadrn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnjheijg.html

Ruby: warn "err"
来源：http://dali.jqgfzy.top/Article/details/gtpdzucuci.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tian-w.cn/Article/details/gtgtrikinq.html

[M07] 判断是否为主入口
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrabpkrv.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgfzy.top/Article/details/gtmapjksuu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sxryk.cn/Article/details/gtiagmcrna.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gtqvqglibf.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gthvhqgzej.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gteingjqui.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gtrpcceqbx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yangfankeji.com/Article/details/gtpaerqosj.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gtosomedlt.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gtrjloxdnq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.snrcjt.cn/Article/details/gtwkhajnjf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxinkj.top/Article/details/gtmyhiqrhe.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gttloeodkf.html

TS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtcieypnpf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gtibjizpjn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.vqdsnc.cn/Article/details/gtkmgwthhb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daria6918.cn/Article/details/gtqtnnnlae.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aizwys.cn/Article/details/gtnvlepync.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gthtdekasx.html

N. 数据结构与算法
来源：http://dali.c1oappe.top/Article/details/gtlgafxdaa.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtedcdayhy.html

[N01] 二分查找（有序数组）
来源：http://dali.c1oappe.top/Article/details/gtcpmxcfcp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.316326.xyz/Article/details/gtgkborfiy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ybcxt.top/Article/details/gtrodazxdf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtglfanuqo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtcplgtyfg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gttngjwsjc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtcyfjtvme.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shuidangran.top/Article/details/gtmldzrjrl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxnfqotf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhongyouzk.top/Article/details/gthlpkpncn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbcagnxw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sweek.top/Article/details/gttffyqrjg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtwipjwblm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtgtfwkxyw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fengsongda.top/Article/details/gtgbyoguit.html

Go:   slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtxzswrfun.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtoacvynqo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hammf.cn/Article/details/gtvbrlylxl.html

[N03] 快速排序（分治示例）
来源：http://dali.ybcxt.top/Article/details/gtisbdjocp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sweek.top/Article/details/gtairidyjf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.smart0.xyz/Article/details/gtkpjtegcz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtsbpsmvom.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gtbhztdslj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gtuyamcaiy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hywenlv.cn/Article/details/gtwhtlvbex.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gotoacloud.top/Article/details/gtqdnuixou.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozaamflx.html

[N04] 斐波那契数列
来源：http://dali.svipenyu.cn/Article/details/gtxuoleapc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gtfazmkrvw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gtrpdpjwmr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtnoncrxrq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtydgvtsss.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gtvsncatpl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jiagoushi.top/Article/details/gthlrftubj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtoulaofjv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gttvrxgzij.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gtigoeywdg.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtsjasvjtj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gtdcmlrvdn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtvzmoyoji.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gthdnlvwit.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.havefunace.top/Article/details/gtmmcmxevp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aizwys.cn/Article/details/gtboyerdrt.html

Ruby: a.gcd(b)
来源：http://dali.9152youxi.cn/Article/details/gtfqglucfq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtkzelamji.html

[N06] 判断回文字符串
来源：http://dali.yvedp.cn/Article/details/gtkavcgwqp.html

Py:   s == s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtbtycvero.html

PHP:  $s === strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gtkfvbmyrs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtuhkspglc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtscptdnmu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.0kj1m.cn/Article/details/gtkcslbdgt.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gtwevzzxrz.html

Ruby: s == s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtemoplpfq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gtbpuylkkh.html

[N07] 两数之和（返回下标）
来源：http://dali.ehwqpu.com/Article/details/gtujsdjonl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zdqjudy.top/Article/details/gtbdxakpnx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigfzy.top/Article/details/gtttezcaof.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gtiyvihlny.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gtriyjbeuj.html

Java: // 手写 HashMap
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxrewtbe.html

Go:   // 手写 map[int]int
来源：http://dali.chenjidiqi.icu/Article/details/gtrvgtocgi.html

Ruby: // 手写 Hash
来源：http://dali.nanxinkj.top/Article/details/gtraxfdghx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gtqrxoldln.html

[N08] 生成全排列
来源：http://dali.cdnleiting.top/Article/details/gtxfsceivn.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gtiqrxogpc.html

PHP:  // 手写递归交换
来源：http://dali.cdnleiting.top/Article/details/gtsfmrcfps.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtbmibhltb.html

TS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtwjokfuuh.html

Java: // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gteyyuhequ.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtfprjrogj.html

Ruby: arr.permutation.to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gtycgumqmx.html

C#:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtywojlnak.html

[N09] 栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gtoxzdfphc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ppjwa.cn/Article/details/gtzhmfuwng.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtranmitlb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtqdwigdek.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jianghu66.top/Article/details/gtklytsugc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gtptvklrpc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj202588.top/Article/details/gttfbptavq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gthmnhlerk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgufenzy.top/Article/details/gtqovfmhru.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gtsjtngjuf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yvedp.cn/Article/details/gtgvbdcqop.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gzhubu.top/Article/details/gtnrcejrwo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xinyue.icu/Article/details/gtrdteinwo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gaohongyu789.top/Article/details/gtaacumscr.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gtkndcsaln.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yongpay.top/Article/details/gtwfgwsswy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gtzeqheapk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gtmnfvpdmm.html

[N11] 二叉树中序遍历
来源：http://dali.aibaodan.cn/Article/details/gtzvrhtcze.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jlsjyb.cn/Article/details/gtegkdlmzx.html

PHP:  // 手写递归函数
来源：http://dali.xuanzx.com/Article/details/gtlgipiquf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtwtgpibzy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gtzcfcejxd.html

Java: // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtqemhnlnr.html

Go:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gttldwfdyo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnxiangtu.top/Article/details/gtjebgskoe.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gtkrgfkvxa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.9152youxi.cn/Article/details/gtuqqvxunw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hywenlv.cn/Article/details/gtpadgigvq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.bjfxy.top/Article/details/gtcvvatenw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gtswoclzff.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gtjcvtjiui.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gtarrpolzj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cheryme.top/Article/details/gtqoolyhed.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gtpiyitfsg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtpdvsnlkv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtwmqwpnvm.html

O. 并发与异步
来源：http://dali.hnqzz.top/Article/details/gtqbyzrjls.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtonquspca.html

[O01] 启动一个线程
来源：http://dali.zycfv.cn/Article/details/gtghctkoej.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhengqikj.top/Article/details/gtweaaztjc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuljigiy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cashguo.top/Article/details/gtloexztaf.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gtapymffse.html

Java: new Thread(() -> f()).start()
来源：http://dali.cashguo.top/Article/details/gtcoasuxgg.html

Go:   go f()
来源：http://dali.hnxiangtu.top/Article/details/gtjoembqxu.html

Ruby: Thread.new { f }
来源：http://dali.aizwys.cn/Article/details/gtctekjxmk.html

C#:   Task.Run(() => F());
来源：http://dali.quarkkingdee.top/Article/details/gtifqncjrw.html

[O02] 使用线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmklvgbhy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jlsjyb.cn/Article/details/gtgjpurakn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yongpay.top/Article/details/gtbftphdcr.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigfzy.top/Article/details/gtmnyhodoj.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtthuecfqe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shzxlz.cn/Article/details/gtbrrmbhhd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuxming.cn/Article/details/gthtpdpykh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sxryk.cn/Article/details/gtgbyexiox.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gtjnwzccnt.html

[O03] 加锁保护共享数据
来源：http://dali.shuidangran.top/Article/details/gthvdwdkyj.html

Py:   with lock: shared += 1
来源：http://dali.hongshengwenyu.top/Article/details/gtsfbpcloy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuanzhike.top/Article/details/gtkienxzww.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gtmuproqib.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtjzhupmje.html

Java: synchronized (this) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gteftnxnci.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangdashe.top/Article/details/gtzecmvtoz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.iojbl.cn/Article/details/gtxxzxccki.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtyiphkszv.html

[O04] 定义异步函数并等待
来源：http://dali.vqdsnc.cn/Article/details/gtkkhhzhdv.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gtxgklbvlh.html


<!-- 参考信息 -->