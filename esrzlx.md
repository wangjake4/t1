代发 wailian999

L. 网络请求
来源：http://dali.xuanzx.com/Article/details/gt2jqqwyznc.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmteunra.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gt2mjqqsoct.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgfzy.top/Article/details/gt2cjnfaajb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.iojbl.cn/Article/details/gt2kohdeppb.html

JS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gt2xcqqcvbs.html

TS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gt2kulpvxoo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fzhhl.top/Article/details/gt2alcowsqn.html

Go:   resp, err := http.Get(url)
来源：http://dali.haohaochexian.top/Article/details/gt2nwfoaysx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.redwolf501.top/Article/details/gt2qsvmzany.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xinyue.icu/Article/details/gt2lncixfux.html

[L02] 发送 POST JSON
来源：http://dali.cucudq.cn/Article/details/gt2enkvrzie.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gt2hyqnoigy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gt2htyupisn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gt2ogxavoim.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gt2gwqhoczw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gt2hrfpgupw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258.top/Article/details/gt2qvxfvqxc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gt2mrciqxst.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gt2narnwzla.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gt2hetsleyd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cucudq.cn/Article/details/gt2qzjtvhwa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gt2ziwkljyw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gt2vlfnhhmy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2veiracjx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gt2gqzgxutg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gt2blujigmj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuetiantiany.cn/Article/details/gt2bwledgnd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gt2favnqofb.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gt2glucebpt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gt2lxprlnnr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gt2yxixwxep.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2greyojvx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gt2rxuvdomx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dashuyun.cn/Article/details/gt2ioevghhe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cdnleiting.top/Article/details/gt2qsvrbqhd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dianchejie.cn/Article/details/gt2zvecbnvr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gt2mrkdhxbl.html

[L05] 上传文件（multipart）
来源：http://dali.sysykeji.top/Article/details/gt2bwmimfkl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daria6918.cn/Article/details/gt2ccbhufnt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gt2crkqapmg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gt2nagovdar.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2skfifjia.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj202588.top/Article/details/gt2xagbohkb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cashguo.top/Article/details/gt2sjkxrqxt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gt2achxoxpu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2mdqlagmi.html

[L06] 解析响应为 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgdnlnhn.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gt2sindjwsp.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fjkbuhir.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gt2zazaylox.html

TS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gt2kyqmgzsj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2deolimhp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkjmljub.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aibaodan.cn/Article/details/gt2ezyogupq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gt2ttlrltie.html

[L07] 处理 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gt2ssfkvsxy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gt2rmzkxgtq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gt2ektgfwro.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gt2jqwyibnq.html

TS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gt2asytmjns.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fshldwca.html

Go:   resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gt2avywbjqi.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gt2pjkdsezl.html

C#:   (int)resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2bdtsjkzs.html

[L08] 并发请求多个地址
来源：http://dali.yonumen.top/Article/details/gt2hfevlqqm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qqanbojs.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gt2rgbkdqhe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ryzodekv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2mwuvcczn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gotoacloud.top/Article/details/gt2ejbnhdcj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gt2nfyohdpi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gt2xsuuporz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gt2ubdasdmx.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2wavechav.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gt2hcwkbpox.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2egifkxyu.html

[M01] 读取命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swbtqbyr.html

Py:   sys.argv[1:]
来源：http://dali.chenlongwang.top/Article/details/gt2cuatmfsu.html

PHP:  $argv;  $argc;
来源：http://dali.wangdashe.top/Article/details/gt2wgyhyztg.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2pgyhebku.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gt2nnejgvry.html

Java: args 数组（main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddfpvppt.html

Go:   os.Args[1:]
来源：http://dali.fzhhl.top/Article/details/gt2ryxrlaku.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gt2fxxpjggb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gt2uojxuzqu.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gt2sziqiysc.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gt2kznhdcqr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2uiuuonop.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gt2mmxifmrl.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gt2ujgkqceb.html

Java: System.getenv("HOME")
来源：http://dali.yongpay.top/Article/details/gt2nunqcjsy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2chnbsyoz.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bmcylyst.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2daxkrkgv.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gt2wsjluiah.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gt2wldnspbe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gt2qkyeqkhj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gt2nfsvjmsc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2haoueint.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.svipenyu.cn/Article/details/gt2oriwlaod.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yongpay.top/Article/details/gt2lfacfpnf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2euquxvhn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxinkj.top/Article/details/gt2wsrqhhki.html

[M04] 获取当前工作目录
来源：http://dali.quarkkingdee.top/Article/details/gt2hxdbqzii.html

Py:   os.getcwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqnbgawh.html

PHP:  getcwd();
来源：http://dali.bjfxy.top/Article/details/gt2dtanuuqq.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2frjtmjas.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gt2ptspshri.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhoulong.xyz/Article/details/gt2zkpwdhob.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gt2ddwokkcd.html

Ruby: Dir.pwd
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqwxzbzc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fengsongda.top/Article/details/gt2zufhnkab.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gt2noigzudf.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2ehxctltx.html

PHP:  exit(1);
来源：http://dali.yueranfly.top/Article/details/gt2qjldbing.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2smvszayb.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2glkrpqzd.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2emuqykzu.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2cjlwdjgx.html

Ruby: exit 1
来源：http://dali.tianlin.xyz/Article/details/gt2yxtukyfe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gt2nwiqerep.html

[M06] 向标准错误输出
来源：http://dali.mhx1999.top/Article/details/gt2faehukcl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gt2edtsofnq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.c1oappe.top/Article/details/gt2psiazujj.html

JS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gt2yvxjbehs.html

TS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gt2maytndyf.html

Java: System.err.println("err")
来源：http://dali.yonumen.top/Article/details/gt2zupgjdfi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhixingplan.top/Article/details/gt2aqpstvhi.html

Ruby: warn "err"
来源：http://dali.jianghu66.top/Article/details/gt2quecprbk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gt2ruxigzxe.html

[M07] 判断是否为主入口
来源：http://dali.ybcxt.top/Article/details/gt2rrwdinft.html

Py:   if __name__ == "__main__":
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yudvaunu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2tchnnqgr.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gt2jakkherp.html

TS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gt2oxidnkkl.html

Java: public static void main(String[] args)
来源：http://dali.yj20258888.top/Article/details/gt2mnfqfwgm.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gt2gracbwmd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zdqjudy.top/Article/details/gt2crvjwwwt.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigufen.top/Article/details/gt2znthplxj.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxuanxn.top/Article/details/gt2oydbffbo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gt2drigveku.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ybcxt.top/Article/details/gt2bheextpa.html

JS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gt2wbueejza.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gt2sjagocau.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gt2euvwfqft.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gt2nvvokeah.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gt2zvcpycxq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fengsongda.top/Article/details/gt2yehxdbka.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2kjeswjii.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gt2ncdfkxmv.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ueopairm.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mlkfbnce.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2pptpwygy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwabegxj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2enxpgusg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2chcyucin.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2ccwuhtku.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2swueistx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gt2hijwugju.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xojujdaz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gt2dwmtmpvk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gt2qnunhuqn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ybcxt.top/Article/details/gt2rijgghjx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gt2avsevlgd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gt2fixcijmy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qrkhqygh.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2ljaqooxw.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gt2fskbdkzn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gt2nuijxqlt.html

[N03] 快速排序（分治示例）
来源：http://dali.xuanzx.com/Article/details/gt2bceqqaut.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zdqjudy.top/Article/details/gt2qlztxpvs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aibaodan.cn/Article/details/gt2yuttvuwr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gt2ozysidau.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gt2gsxllutb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxinkj.top/Article/details/gt2vhqqakjp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgufenzy.top/Article/details/gt2uidxsocv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cheryme.top/Article/details/gt2wwqiiweg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnqzz.top/Article/details/gt2zqxiaivn.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gt2wwlbupao.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gt2ypjfzehn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangdashe.top/Article/details/gt2lnegdfbs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zvxrsznh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gt2qzhrkupr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yonumen.top/Article/details/gt2icjhpppa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yanxiufei.cn/Article/details/gt2bkewyggi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gt2uuuspide.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gt2ruvoybhh.html

[N05] 最大公约数
来源：http://dali.yj20258888.top/Article/details/gt2oxwdrqxv.html

Py:   math.gcd(a, b)
来源：http://dali.redwolf501.top/Article/details/gt2blpwmsjm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.andypj.xyz/Article/details/gt2zokbjapj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gt2rowwexri.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gt2vvvbrtno.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hfpthk.cn/Article/details/gt2cablcouo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cdnleiting.top/Article/details/gt2fgdtnytk.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gt2xifitfov.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gt2hfoftuog.html

[N06] 判断回文字符串
来源：http://dali.cdnleiting.top/Article/details/gt2wuehlzvg.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gt2ybihaulv.html

PHP:  $s === strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gt2afwrqvbl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2mrxcvvau.html

TS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2xvnwefcm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yongpay.top/Article/details/gt2tmcphvxq.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gt2fjgmvdkf.html

Ruby: s == s.reverse
来源：http://dali.snrcjt.cn/Article/details/gt2qnwqwzbq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gt2jpmtifcd.html

[N07] 两数之和（返回下标）
来源：http://dali.gogol.net.cn/Article/details/gt2lyivfndg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hammf.cn/Article/details/gt2tycwtmzc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yongpay.top/Article/details/gt2vpnnbfut.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sufxvd.cn/Article/details/gt2skebcgmn.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhengqikj.top/Article/details/gt2mheaedru.html

Java: // 手写 HashMap
来源：http://dali.kuanghao11.cn/Article/details/gt2reteihkk.html

Go:   // 手写 map[int]int
来源：http://dali.zhoulong.xyz/Article/details/gt2hctoezmo.html

Ruby: // 手写 Hash
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bovacsss.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yanxiufei.cn/Article/details/gt2cnhrasks.html

[N08] 生成全排列
来源：http://dali.iojbl.cn/Article/details/gt2fmcmctvu.html

Py:   itertools.permutations(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2qvryxeqg.html

PHP:  // 手写递归交换
来源：http://dali.yangfankeji.com/Article/details/gt2ziigpfwb.html

JS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2mpfwgilo.html

TS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2ftbsjlgg.html

Java: // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2hzyewlny.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2enuuozif.html

Ruby: arr.permutation.to_a
来源：http://dali.yongpay.top/Article/details/gt2unhkchej.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mxfhewek.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gt2nvyrohno.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2bkwzyqso.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2krxxvlvp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gt2thtmgltf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuanzx.com/Article/details/gt2eakjggky.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gt2zihbnzfq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2smxbpbuk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gt2oxvvwjbi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sxryk.cn/Article/details/gt2uucivuwx.html

[N10] 链表节点定义
来源：http://dali.9152youxi.cn/Article/details/gt2ssogcxjx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xylfe.cn/Article/details/gt2bpfhfrdw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gyezitxm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dianchejie.cn/Article/details/gt2krnwpmxl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dashuyun.cn/Article/details/gt2hxnvxioy.html

Java: class Node { int v; Node next; }
来源：http://dali.iojbl.cn/Article/details/gt2ufbbgpdz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ekhzgizy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tanke756.top/Article/details/gt2ccucgsub.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cqqwz.cn/Article/details/gt2wxkhbjsv.html

[N11] 二叉树中序遍历
来源：http://dali.wangdashe.top/Article/details/gt2jhpoxala.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.316326.xyz/Article/details/gt2pewjxukk.html

PHP:  // 手写递归函数
来源：http://dali.chenzaomai.com/Article/details/gt2ihlqhwop.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gt2vdpdsquc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gt2kbjhvrod.html

Java: // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2lvbapgwh.html

Go:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2utgjxvrq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.kuanghao11.cn/Article/details/gt2tnaqcxgt.html

C#:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrefxbob.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gt2qeljfylo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guannengcc.top/Article/details/gt2yfdlmbvi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gaohongyu789.top/Article/details/gt2kzvaasxq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jilqkqiw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gt2rbkjdadg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxqsjsts.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.mhx1999.top/Article/details/gt2wpycxsws.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnqzz.top/Article/details/gt2dmbcgzwc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gt2llnoqxkd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2nmromrbg.html

O. 并发与异步
来源：http://dali.chenlongwang.top/Article/details/gt2ytojzqgm.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2dpmgpxhp.html

[O01] 启动一个线程
来源：http://dali.wangshuangyany.cn/Article/details/gt2ddzcafuz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ppjwa.cn/Article/details/gt2joeyyuno.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ayklommb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.guowangkeji.top/Article/details/gt2uuhnflve.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gt2xlverwuw.html

Java: new Thread(() -> f()).start()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytpergoo.html

Go:   go f()
来源：http://dali.aibaodan.cn/Article/details/gt2bzdupyoz.html

Ruby: Thread.new { f }
来源：http://dali.nwbrower.top/Article/details/gt2srekyhex.html

C#:   Task.Run(() => F());
来源：http://dali.aizwys.cn/Article/details/gt2kqnwkhwf.html

[O02] 使用线程池
来源：http://dali.yuxming.cn/Article/details/gt2xjcpybll.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258888.top/Article/details/gt2sgvhztqf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zdqjudy.top/Article/details/gt2tprbiqln.html

JS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gt2wemmocus.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gt2yrezuvty.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gt2rlyckghq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hysaishi.cn/Article/details/gt2hrvyyboj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hywenlv.cn/Article/details/gt2wgbttzfw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gt2ekahwxdc.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258888.top/Article/details/gt2zkhicxxd.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gt2wwfwtdwm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gt2bpnfhfty.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxuanxn.top/Article/details/gt2adxojolu.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gt2ktlatqha.html

Java: synchronized (this) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2paqtjsnf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ybcxt.top/Article/details/gt2xxlrnotn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dianchejie.cn/Article/details/gt2lfmyrnyl.html

C#:   lock (gate) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gt2ammcsxrl.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gt2fimqyupd.html

Py:   async def f():⏎    await g()
来源：http://dali.yvedp.cn/Article/details/gt2wobffarq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gt2hydlwina.html

JS:   async function f() { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gt2ktvrvaci.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gt2cnpkmhdy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gt2sdrvhwow.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnxiangtu.top/Article/details/gt2lanunhhg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tian-w.cn/Article/details/gt2katxrasq.html

C#:   async Task F() { await G(); }
来源：http://dali.xinyue.icu/Article/details/gt2woxoizbp.html

[O05] 并发执行并等待全部完成
来源：http://dali.tianlin.xyz/Article/details/gt2anrphyym.html


<!-- 参考信息 -->