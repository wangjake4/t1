代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cdnleiting.top/Article/details/gt2ktgmdbdj.html

JS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gt2hdzsotri.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gt2ssrmxibn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gt2hlsywrgo.html

Go:   resp, err := http.Get(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2blhoiuhg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2myqbnhpu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gt2zclcpppj.html

[L02] 发送 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gt2ppuevhkm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guannengcc.top/Article/details/gt2ursbssln.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangdashe.top/Article/details/gt2xadzbjis.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gt2hyybcvuw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gt2mhvywoxx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gt2twhmmlvw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daxiang520.top/Article/details/gt2hjtrnste.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gt2kgfmjtcu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.quarkkingdee.top/Article/details/gt2fwsyjghi.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gt2cgggttkm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.kuanghao11.cn/Article/details/gt2svyzycoh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.svipenyu.cn/Article/details/gt2czajlclu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gt2hkmyxnxw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gt2kihjsxnv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujpoxomc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gt2vzgfbvxu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gt2audfetns.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gt2msacquze.html

[L04] 设置超时
来源：http://dali.yongpay.top/Article/details/gt2gfcghuqn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gt2fkookbbp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tian-w.cn/Article/details/gt2mfkkexih.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gt2lkvgloct.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uboafqoe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuanzx.com/Article/details/gt2kpyprshm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2crtysccw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gt2dzeqhtkk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gt2bzvcwfgc.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigufen.top/Article/details/gt2wwtlvwza.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yanxiufei.cn/Article/details/gt2ncysbgyl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqxoxhwz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gt2bmgvuhjc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gt2zourqljh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenzaomai.com/Article/details/gt2yodkegmy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cqqwz.cn/Article/details/gt2wkskxbno.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhoulong.xyz/Article/details/gt2duljulzo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2gadiixtl.html

[L06] 解析响应为 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2ajfvhbui.html

Py:   resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2dtffozhj.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gkloanks.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2qmzporuv.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2qvuhreus.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gt2zfaivhlq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gt2poxmrvet.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgfzy.top/Article/details/gt2zlkpjhay.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gt2pdcemskp.html

[L07] 处理 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gt2nqglmtib.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guannengcc.top/Article/details/gt2tlpztdbf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gt2gwggldgk.html

JS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vspejyut.html

TS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gt2zoclijkr.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwqtjocr.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gt2illpyicv.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2jywolvmy.html

C#:   (int)resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gt2hjhdbqwn.html

[L08] 并发请求多个地址
来源：http://dali.yueranfly.top/Article/details/gt2ivxcrwlb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gt2ebdddwga.html

PHP:  curl_multi_init() 系列
来源：http://dali.jyoumei.cn/Article/details/gt2pihakvvb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gt2lzajiifc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gt2vrpeoycr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gt2vvwirutl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gt2fbkucguk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cashguo.top/Article/details/gt2gszybrag.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sweek.top/Article/details/gt2bciwjhao.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2wbnorqfk.html

M. 命令行 / 进程 / 环境
来源：http://dali.jianghu66.top/Article/details/gt2dirodqsf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2yozgicfw.html

[M01] 读取命令行参数
来源：http://dali.guowangkeji.top/Article/details/gt2fgvyawna.html

Py:   sys.argv[1:]
来源：http://dali.andypj.xyz/Article/details/gt2dqyquqay.html

PHP:  $argv;  $argc;
来源：http://dali.meibo888.top/Article/details/gt2mahalwml.html

JS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gt2alnmbzna.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gt2rffqirwj.html

Java: args 数组（main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gt2wlrmvcqt.html

Go:   os.Args[1:]
来源：http://dali.316326.xyz/Article/details/gt2eaqgcyez.html

Ruby: ARGV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rcpiqvri.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gt2zdtwyuvq.html

[M02] 读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gt2tccbjuvk.html

Py:   os.environ.get("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2gpyholyq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gt2oswnrmbe.html

JS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gt2kattfobk.html

TS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gt2awloirkn.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2mxabipmf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tian-w.cn/Article/details/gt2lhwzqrgm.html

Ruby: ENV["HOME"]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emgkpuip.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2veuaxksm.html

[M03] 执行外部命令
来源：http://dali.yongpay.top/Article/details/gt2iqmoczcu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gt2jfflyasr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gt2dzgcoevp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gt2ygsutwhg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gt2uvyhbyay.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guannengcc.top/Article/details/gt2mnhfphed.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ybcxt.top/Article/details/gt2pqjwufix.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenlongwang.top/Article/details/gt2qkbuhxmy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.bjfxy.top/Article/details/gt2cdhijdgd.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gt2uxvewjcp.html

Py:   os.getcwd()
来源：http://dali.jqgfzy.top/Article/details/gt2ajtxbpol.html

PHP:  getcwd();
来源：http://dali.chenlongwang.top/Article/details/gt2ghnhgwvy.html

JS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2grspvgnj.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gt2xacnebfm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yongpay.top/Article/details/gt2efmjdasg.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jrpeqnuw.html

Ruby: Dir.pwd
来源：http://dali.chenlongwang.top/Article/details/gt2rrzjbguv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gt2rmivvppm.html

[M05] 设置退出码
来源：http://dali.feifeiyinyue.top/Article/details/gt2aiqidkev.html

Py:   sys.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2hpsvveun.html

PHP:  exit(1);
来源：http://dali.xinyue.icu/Article/details/gt2rlzjzegc.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhwbekgo.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2oadcirfa.html

Java: System.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2zumrazrf.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yiuvpggo.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gt2ltrdoqsm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gt2kdcobiuk.html

[M06] 向标准错误输出
来源：http://dali.iojbl.cn/Article/details/gt2hilchdsu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gt2meuewjec.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gt2vigdqgcg.html

JS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gt2inuyxyzz.html

TS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gt2szogdqlb.html

Java: System.err.println("err")
来源：http://dali.havefunace.top/Article/details/gt2ovxgfobn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shuidangran.top/Article/details/gt2jdulculh.html

Ruby: warn "err"
来源：http://dali.shuidangran.top/Article/details/gt2dsenjiiz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gt2ptrifilk.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gt2ylarymsm.html

Py:   if __name__ == "__main__":
来源：http://dali.jiagoushi.top/Article/details/gt2zwvzgqiu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gt2xrvrruez.html

JS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gt2rsgtjuvd.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gt2rkqhegxw.html

Java: public static void main(String[] args)
来源：http://dali.yj20258888.top/Article/details/gt2jqjbilwg.html

Go:   func main()
来源：http://dali.jyoumei.cn/Article/details/gt2zfldsclb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aibaodan.cn/Article/details/gt2dltoudif.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gt2rermhtht.html

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gt2cjkxzyqj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gt2jewbybwg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ehwqpu.com/Article/details/gt2uiexwgab.html

JS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gt2cajfqtoz.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gt2lnykvrch.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gt2gutyazmx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2imzvdurh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhengqikj.top/Article/details/gt2vowtqmbf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gt2obijvsen.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2cfzdiaao.html

N. 数据结构与算法
来源：http://dali.nanxinkj.top/Article/details/gt2gxrwuntl.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2srxzxala.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gt2sbniixgg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2unidbpnh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gt2wkjljcqy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gt2ydxtufkx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2eubihzmm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmfjtrfj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2wfrtqfbe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xinyue.icu/Article/details/gt2elfsdwxr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2oglwngim.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.meibo888.top/Article/details/gt2rigqagwn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gt2pxfszscr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gt2yzyfoeae.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gt2wbyomsea.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gt2uwhyhdco.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gt2ngdonrba.html

Go:   slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2ltsnotci.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gt2aivscxcw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbnckua.html

[N03] 快速排序（分治示例）
来源：http://dali.fzhhl.top/Article/details/gt2adsymrhf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ydzc1.top/Article/details/gt2xvzyluiv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxinkj.top/Article/details/gt2lssbrkle.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gt2urrdpmlh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aycetqiq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hysaishi.cn/Article/details/gt2oyudjyaa.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhoulong.xyz/Article/details/gt2mbariuwl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgwkabf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2meaktled.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvwiscg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2drstzrto.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gt2eannxeve.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2oplbvlpq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2oyhyzrfu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.havefunace.top/Article/details/gt2eusajqwp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aibaodan.cn/Article/details/gt2gmmeufbl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2riyurvby.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2zizmmunq.html

[N05] 最大公约数
来源：http://dali.cqqwz.cn/Article/details/gt2cbfyqtuk.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2jpdficoj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2emuquvjd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gt2byyxzcjc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ecygzapc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgfzy.top/Article/details/gt2ohydbine.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fzhhl.top/Article/details/gt2iduxnzsh.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gt2lnaqtlvc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.mhx1999.top/Article/details/gt2bsuwimzx.html

[N06] 判断回文字符串
来源：http://dali.bjfxy.top/Article/details/gt2pjvfzckj.html

Py:   s == s[::-1]
来源：http://dali.yj20258.top/Article/details/gt2rsdalejg.html

PHP:  $s === strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gt2wrlvxdwz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gt2ylystbaa.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gt2ehnomjjb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhoulong.xyz/Article/details/gt2wofxtmmj.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gt2kkknlrko.html

Ruby: s == s.reverse
来源：http://dali.yonumen.top/Article/details/gt2ntxnjdnx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gt2wmkolfqx.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258888.top/Article/details/gt2hwsrhjzj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tian-w.cn/Article/details/gt2njgvviff.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gt2hpzqxtvx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gt2iryafyad.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuetiantiany.cn/Article/details/gt2zcekgdsd.html

Java: // 手写 HashMap
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftdxbxwm.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gt2skiyscbj.html

Ruby: // 手写 Hash
来源：http://dali.birdmap.top/Article/details/gt2hcquqmqu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daria6918.cn/Article/details/gt2lpfcfjeo.html

[N08] 生成全排列
来源：http://dali.haohaochexian.top/Article/details/gt2kauhutyt.html

Py:   itertools.permutations(arr)
来源：http://dali.cheryme.top/Article/details/gt2tqnfbgpp.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gt2hycuklme.html

JS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2vphpymdw.html

TS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gfvdkgcm.html

Java: // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2rluxqgrh.html

Go:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2xwjfrcfc.html

Ruby: arr.permutation.to_a
来源：http://dali.xziqi.cn/Article/details/gt2gnyrlpsm.html

C#:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2qvlrjauv.html

[N09] 栈与队列
来源：http://dali.birdmap.top/Article/details/gt2ovgghsjf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gt2nippbmib.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yueranfly.top/Article/details/gt2pliaaowj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2kdkynakw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ntuajitq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gzhubu.top/Article/details/gt2ggqqaayq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ppjwa.cn/Article/details/gt2vfunpfwr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gt2cqzsmdxh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gt2eknxkynn.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gt2hrnrpriy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wbzgsjug.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj202588.top/Article/details/gt2whrquctb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ydzc1.top/Article/details/gt2wotsbigu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rimcxjgb.html

Java: class Node { int v; Node next; }
来源：http://dali.zhengqikj.top/Article/details/gt2oskgnugg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gt2wejfhnao.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yyxjptvb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.snrcjt.cn/Article/details/gt2cglnjdln.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gt2kmwqqaxf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gt2rdfomzmu.html

PHP:  // 手写递归函数
来源：http://dali.ehwqpu.com/Article/details/gt2dadaaqas.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gt2qushyypg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gt2wrwxevoh.html

Java: // 手写递归
来源：http://dali.redwolf501.top/Article/details/gt2cafgxeow.html

Go:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gt2emnpnkaz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhdqeat.html

C#:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gt2olwdghmb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umnidkib.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pycfn.com/Article/details/gt2jrkoimlz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ivvv.top/Article/details/gt2tszoripy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hnmvjnxv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gt2pgfcrzju.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2obvqrzri.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwjzuxjy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gt2hqsnqjut.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gt2kyguotgx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2avhbupad.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gt2kdaqpzwo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2jmzmxbbx.html

[O01] 启动一个线程
来源：http://dali.guowangkeji.top/Article/details/gt2cdxdzsfj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pycfn.com/Article/details/gt2tugzgcnz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gt2fdqjxzca.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gt2mlalbgor.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gt2enododyc.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gt2ultnkrjh.html

Go:   go f()
来源：http://dali.havefunace.top/Article/details/gt2wquxeyqb.html

Ruby: Thread.new { f }
来源：http://dali.zdqjudy.top/Article/details/gt2ubzcfhqg.html

C#:   Task.Run(() => F());
来源：http://dali.chenzaomai.com/Article/details/gt2yossvyeo.html

[O02] 使用线程池
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvgjbsyt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.meibo888.top/Article/details/gt2gtyaqrhl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gt2nojzqsvm.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gt2bapavytd.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gt2wafmmzjd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gt2mtfsoppy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhongyouzk.top/Article/details/gt2uhnfojch.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gt2gaufdbvh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tian-w.cn/Article/details/gt2mgkywcdp.html

[O03] 加锁保护共享数据
来源：http://dali.hnqzz.top/Article/details/gt2kvhncdpn.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gt2qmfpdbah.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gogol.net.cn/Article/details/gt2gdbjqvqp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shuidangran.top/Article/details/gt2xjmutqzx.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gt2cuvoqcks.html

Java: synchronized (this) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gt2uevphnhu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xduaerfc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zdqjudy.top/Article/details/gt2ktvjlwvs.html

C#:   lock (gate) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gt2kzocoyfd.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ymfsvbmp.html

Py:   async def f():⏎    await g()
来源：http://dali.zdqjudy.top/Article/details/gt2urwirisy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pengpengdd.cyou/Article/details/gt2cfxkqbwy.html

JS:   async function f() { await g(); }
来源：http://dali.gzhubu.top/Article/details/gt2kvnpjreq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sweek.top/Article/details/gt2cxcnhzqh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.meibo888.top/Article/details/gt2jdpzkftj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aizwys.cn/Article/details/gt2ismsomzd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uqtkccnx.html

C#:   async Task F() { await G(); }
来源：http://dali.smart0.xyz/Article/details/gt2wwxjvwbp.html

[O05] 并发执行并等待全部完成
来源：http://dali.guowangkeji.top/Article/details/gt2afybkglt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2zvtmocyo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jiagoushi.top/Article/details/gt2gteydyfs.html

JS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gt2yrdzcenm.html

TS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gt2xjpgznbb.html


<!-- 参考信息 -->